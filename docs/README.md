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
<svg width="5053pt" height="1965pt"
 viewBox="0.00 0.00 5053.28 1965.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1961)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1961 5049.2839,-1961 5049.2839,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M4564.2839,-1370C4564.2839,-1370 5033.2839,-1370 5033.2839,-1370 5039.2839,-1370 5045.2839,-1376 5045.2839,-1382 5045.2839,-1382 5045.2839,-1933 5045.2839,-1933 5045.2839,-1939 5039.2839,-1945 5033.2839,-1945 5033.2839,-1945 4564.2839,-1945 4564.2839,-1945 4558.2839,-1945 4552.2839,-1939 4552.2839,-1933 4552.2839,-1933 4552.2839,-1382 4552.2839,-1382 4552.2839,-1376 4558.2839,-1370 4564.2839,-1370"/>
<text text-anchor="middle" x="4616.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="4680.2839,-1370 4680.2839,-1945 "/>
<text text-anchor="middle" x="4690.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1370 4701.2839,-1945 "/>
<text text-anchor="middle" x="4862.7839" y="-1929.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1922 5024.2839,-1922 "/>
<text text-anchor="middle" x="4862.7839" y="-1906.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1899 5024.2839,-1899 "/>
<text text-anchor="middle" x="4862.7839" y="-1883.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1876 5024.2839,-1876 "/>
<text text-anchor="middle" x="4862.7839" y="-1860.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1853 5024.2839,-1853 "/>
<text text-anchor="middle" x="4862.7839" y="-1837.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1830 5024.2839,-1830 "/>
<text text-anchor="middle" x="4862.7839" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1807 5024.2839,-1807 "/>
<text text-anchor="middle" x="4862.7839" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1784 5024.2839,-1784 "/>
<text text-anchor="middle" x="4862.7839" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1761 5024.2839,-1761 "/>
<text text-anchor="middle" x="4862.7839" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1738 5024.2839,-1738 "/>
<text text-anchor="middle" x="4862.7839" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1715 5024.2839,-1715 "/>
<text text-anchor="middle" x="4862.7839" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1692 5024.2839,-1692 "/>
<text text-anchor="middle" x="4862.7839" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1669 5024.2839,-1669 "/>
<text text-anchor="middle" x="4862.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1646 5024.2839,-1646 "/>
<text text-anchor="middle" x="4862.7839" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1623 5024.2839,-1623 "/>
<text text-anchor="middle" x="4862.7839" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1600 5024.2839,-1600 "/>
<text text-anchor="middle" x="4862.7839" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1577 5024.2839,-1577 "/>
<text text-anchor="middle" x="4862.7839" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1554 5024.2839,-1554 "/>
<text text-anchor="middle" x="4862.7839" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1531 5024.2839,-1531 "/>
<text text-anchor="middle" x="4862.7839" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1508 5024.2839,-1508 "/>
<text text-anchor="middle" x="4862.7839" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1485 5024.2839,-1485 "/>
<text text-anchor="middle" x="4862.7839" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1462 5024.2839,-1462 "/>
<text text-anchor="middle" x="4862.7839" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1439 5024.2839,-1439 "/>
<text text-anchor="middle" x="4862.7839" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1416 5024.2839,-1416 "/>
<text text-anchor="middle" x="4862.7839" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="4701.2839,-1393 5024.2839,-1393 "/>
<text text-anchor="middle" x="4862.7839" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="5024.2839,-1370 5024.2839,-1945 "/>
<text text-anchor="middle" x="5034.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node20" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M3526.7839,-927C3526.7839,-927 3840.7839,-927 3840.7839,-927 3846.7839,-927 3852.7839,-933 3852.7839,-939 3852.7839,-939 3852.7839,-1076 3852.7839,-1076 3852.7839,-1082 3846.7839,-1088 3840.7839,-1088 3840.7839,-1088 3526.7839,-1088 3526.7839,-1088 3520.7839,-1088 3514.7839,-1082 3514.7839,-1076 3514.7839,-1076 3514.7839,-939 3514.7839,-939 3514.7839,-933 3520.7839,-927 3526.7839,-927"/>
<text text-anchor="middle" x="3548.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="3582.7839,-927 3582.7839,-1088 "/>
<text text-anchor="middle" x="3593.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3603.7839,-927 3603.7839,-1088 "/>
<text text-anchor="middle" x="3717.7839" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="3603.7839,-1065 3831.7839,-1065 "/>
<text text-anchor="middle" x="3717.7839" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3603.7839,-1042 3831.7839,-1042 "/>
<text text-anchor="middle" x="3717.7839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="3603.7839,-1019 3831.7839,-1019 "/>
<text text-anchor="middle" x="3717.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="3603.7839,-996 3831.7839,-996 "/>
<text text-anchor="middle" x="3717.7839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="3603.7839,-973 3831.7839,-973 "/>
<text text-anchor="middle" x="3717.7839" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="3603.7839,-950 3831.7839,-950 "/>
<text text-anchor="middle" x="3717.7839" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="3831.7839,-927 3831.7839,-1088 "/>
<text text-anchor="middle" x="3842.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4558.4682,-1369.7892C4553.2815,-1365.7394 4548.0519,-1361.8046 4542.7839,-1358 4332.0834,-1205.8293 4045.7146,-1106.2358 3862.7814,-1053.3968"/>
<polygon fill="#000000" stroke="#000000" points="3863.6399,-1050.0019 3853.0623,-1050.6054 3861.7075,-1056.7299 3863.6399,-1050.0019"/>
<text text-anchor="middle" x="4568.2839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M2281.2839,-1554C2281.2839,-1554 2610.2839,-1554 2610.2839,-1554 2616.2839,-1554 2622.2839,-1560 2622.2839,-1566 2622.2839,-1566 2622.2839,-1749 2622.2839,-1749 2622.2839,-1755 2616.2839,-1761 2610.2839,-1761 2610.2839,-1761 2281.2839,-1761 2281.2839,-1761 2275.2839,-1761 2269.2839,-1755 2269.2839,-1749 2269.2839,-1749 2269.2839,-1566 2269.2839,-1566 2269.2839,-1560 2275.2839,-1554 2281.2839,-1554"/>
<text text-anchor="middle" x="2290.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="2312.2839,-1554 2312.2839,-1761 "/>
<text text-anchor="middle" x="2322.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1554 2333.2839,-1761 "/>
<text text-anchor="middle" x="2467.2839" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1738 2601.2839,-1738 "/>
<text text-anchor="middle" x="2467.2839" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1715 2601.2839,-1715 "/>
<text text-anchor="middle" x="2467.2839" y="-1699.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1692 2601.2839,-1692 "/>
<text text-anchor="middle" x="2467.2839" y="-1676.8" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1669 2601.2839,-1669 "/>
<text text-anchor="middle" x="2467.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1646 2601.2839,-1646 "/>
<text text-anchor="middle" x="2467.2839" y="-1630.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1623 2601.2839,-1623 "/>
<text text-anchor="middle" x="2467.2839" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1600 2601.2839,-1600 "/>
<text text-anchor="middle" x="2467.2839" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="2333.2839,-1577 2601.2839,-1577 "/>
<text text-anchor="middle" x="2467.2839" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2601.2839,-1554 2601.2839,-1761 "/>
<text text-anchor="middle" x="2611.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2480.8277,-1553.9088C2509.7288,-1485.7726 2557.9572,-1401.4412 2630.7839,-1358 2651.6933,-1345.5275 3484.9818,-1319.6508 3505.7839,-1307 3582.1661,-1260.5482 3629.6824,-1167.9042 3656.2039,-1097.8883"/>
<polygon fill="#000000" stroke="#000000" points="3659.6138,-1098.7592 3659.8077,-1088.1661 3653.0502,-1096.3262 3659.6138,-1098.7592"/>
<text text-anchor="middle" x="3243.7839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1621.2839,-1634.5C1621.2839,-1634.5 1922.2839,-1634.5 1922.2839,-1634.5 1928.2839,-1634.5 1934.2839,-1640.5 1934.2839,-1646.5 1934.2839,-1646.5 1934.2839,-1668.5 1934.2839,-1668.5 1934.2839,-1674.5 1928.2839,-1680.5 1922.2839,-1680.5 1922.2839,-1680.5 1621.2839,-1680.5 1621.2839,-1680.5 1615.2839,-1680.5 1609.2839,-1674.5 1609.2839,-1668.5 1609.2839,-1668.5 1609.2839,-1646.5 1609.2839,-1646.5 1609.2839,-1640.5 1615.2839,-1634.5 1621.2839,-1634.5"/>
<text text-anchor="middle" x="1649.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="1689.2839,-1634.5 1689.2839,-1680.5 "/>
<text text-anchor="middle" x="1699.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1710.2839,-1634.5 1710.2839,-1680.5 "/>
<text text-anchor="middle" x="1811.7839" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="1710.2839,-1657.5 1913.2839,-1657.5 "/>
<text text-anchor="middle" x="1811.7839" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="1913.2839,-1634.5 1913.2839,-1680.5 "/>
<text text-anchor="middle" x="1923.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1957.7839,-541.5C1957.7839,-541.5 2261.7839,-541.5 2261.7839,-541.5 2267.7839,-541.5 2273.7839,-547.5 2273.7839,-553.5 2273.7839,-553.5 2273.7839,-644.5 2273.7839,-644.5 2273.7839,-650.5 2267.7839,-656.5 2261.7839,-656.5 2261.7839,-656.5 1957.7839,-656.5 1957.7839,-656.5 1951.7839,-656.5 1945.7839,-650.5 1945.7839,-644.5 1945.7839,-644.5 1945.7839,-553.5 1945.7839,-553.5 1945.7839,-547.5 1951.7839,-541.5 1957.7839,-541.5"/>
<text text-anchor="middle" x="1993.7839" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2041.7839,-541.5 2041.7839,-656.5 "/>
<text text-anchor="middle" x="2052.2839" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2062.7839,-541.5 2062.7839,-656.5 "/>
<text text-anchor="middle" x="2157.7839" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2062.7839,-633.5 2252.7839,-633.5 "/>
<text text-anchor="middle" x="2157.7839" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2062.7839,-610.5 2252.7839,-610.5 "/>
<text text-anchor="middle" x="2157.7839" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2062.7839,-587.5 2252.7839,-587.5 "/>
<text text-anchor="middle" x="2157.7839" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2062.7839,-564.5 2252.7839,-564.5 "/>
<text text-anchor="middle" x="2157.7839" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2252.7839,-541.5 2252.7839,-656.5 "/>
<text text-anchor="middle" x="2263.2839" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1770.4195,-1634.3037C1762.4986,-1496.1285 1724.683,-784.9157 1780.7839,-708 1800.8502,-680.4886 1867.4836,-655.9975 1935.5849,-637.2337"/>
<polygon fill="#000000" stroke="#000000" points="1936.9027,-640.5028 1945.6379,-634.5072 1935.0704,-633.7469 1936.9027,-640.5028"/>
<text text-anchor="middle" x="1823.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2909.7839,-.5C2909.7839,-.5 3299.7839,-.5 3299.7839,-.5 3305.7839,-.5 3311.7839,-6.5 3311.7839,-12.5 3311.7839,-12.5 3311.7839,-264.5 3311.7839,-264.5 3311.7839,-270.5 3305.7839,-276.5 3299.7839,-276.5 3299.7839,-276.5 2909.7839,-276.5 2909.7839,-276.5 2903.7839,-276.5 2897.7839,-270.5 2897.7839,-264.5 2897.7839,-264.5 2897.7839,-12.5 2897.7839,-12.5 2897.7839,-6.5 2903.7839,-.5 2909.7839,-.5"/>
<text text-anchor="middle" x="2925.7839" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2953.7839,-.5 2953.7839,-276.5 "/>
<text text-anchor="middle" x="2964.2839" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2974.7839,-.5 2974.7839,-276.5 "/>
<text text-anchor="middle" x="3132.7839" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-253.5 3290.7839,-253.5 "/>
<text text-anchor="middle" x="3132.7839" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-230.5 3290.7839,-230.5 "/>
<text text-anchor="middle" x="3132.7839" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_shorthand</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-207.5 3290.7839,-207.5 "/>
<text text-anchor="middle" x="3132.7839" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-184.5 3290.7839,-184.5 "/>
<text text-anchor="middle" x="3132.7839" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-161.5 3290.7839,-161.5 "/>
<text text-anchor="middle" x="3132.7839" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-138.5 3290.7839,-138.5 "/>
<text text-anchor="middle" x="3132.7839" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-115.5 3290.7839,-115.5 "/>
<text text-anchor="middle" x="3132.7839" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-92.5 3290.7839,-92.5 "/>
<text text-anchor="middle" x="3132.7839" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-69.5 3290.7839,-69.5 "/>
<text text-anchor="middle" x="3132.7839" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-46.5 3290.7839,-46.5 "/>
<text text-anchor="middle" x="3132.7839" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2974.7839,-23.5 3290.7839,-23.5 "/>
<text text-anchor="middle" x="3132.7839" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="3290.7839,-.5 3290.7839,-276.5 "/>
<text text-anchor="middle" x="3301.2839" y="-134.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1609.1262,-1648.9075C1219.3775,-1624.6754 249.2701,-1541.583 44.7839,-1307 -42.8586,-1206.4581 25.7839,-1140.8787 25.7839,-1007.5 25.7839,-1007.5 25.7839,-1007.5 25.7839,-409 25.7839,-265.178 2185.7493,-172.5167 2887.457,-146.2086"/>
<polygon fill="#000000" stroke="#000000" points="2887.8184,-149.6976 2897.6806,-145.8261 2887.5567,-142.7025 2887.8184,-149.6976"/>
<text text-anchor="middle" x="68.2839" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1798.254,-1634.4925C1867.9531,-1575.512 2064.6467,-1419.2606 2259.7839,-1358 2501.4678,-1282.1267 2575.6962,-1335.701 2828.7839,-1325 2866.3747,-1323.4106 3473.3321,-1326.0389 3505.7839,-1307 3583.1405,-1261.6161 3630.6015,-1168.3301 3656.8468,-1097.8574"/>
<polygon fill="#000000" stroke="#000000" points="3660.2771,-1098.6661 3660.4102,-1088.0721 3653.6996,-1096.2708 3660.2771,-1098.6661"/>
<text text-anchor="middle" x="2871.2839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node4" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2915.2839,-374.5C2915.2839,-374.5 3294.2839,-374.5 3294.2839,-374.5 3300.2839,-374.5 3306.2839,-380.5 3306.2839,-386.5 3306.2839,-386.5 3306.2839,-431.5 3306.2839,-431.5 3306.2839,-437.5 3300.2839,-443.5 3294.2839,-443.5 3294.2839,-443.5 2915.2839,-443.5 2915.2839,-443.5 2909.2839,-443.5 2903.2839,-437.5 2903.2839,-431.5 2903.2839,-431.5 2903.2839,-386.5 2903.2839,-386.5 2903.2839,-380.5 2909.2839,-374.5 2915.2839,-374.5"/>
<text text-anchor="middle" x="2962.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3022.2839,-374.5 3022.2839,-443.5 "/>
<text text-anchor="middle" x="3032.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3043.2839,-374.5 3043.2839,-443.5 "/>
<text text-anchor="middle" x="3164.2839" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3043.2839,-420.5 3285.2839,-420.5 "/>
<text text-anchor="middle" x="3164.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3043.2839,-397.5 3285.2839,-397.5 "/>
<text text-anchor="middle" x="3164.2839" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3285.2839,-374.5 3285.2839,-443.5 "/>
<text text-anchor="middle" x="3295.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3104.7839,-374.4662C3104.7839,-351.5553 3104.7839,-319.7488 3104.7839,-286.8978"/>
<polygon fill="#000000" stroke="#000000" points="3108.284,-286.6778 3104.7839,-276.6779 3101.284,-286.6779 3108.284,-286.6778"/>
<text text-anchor="middle" x="3166.7839" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node5" class="node">
<title>single_cell_sequencing_file</title>
<path fill="none" stroke="#000000" d="M2652.2839,-1358.5C2652.2839,-1358.5 3261.2839,-1358.5 3261.2839,-1358.5 3267.2839,-1358.5 3273.2839,-1364.5 3273.2839,-1370.5 3273.2839,-1370.5 3273.2839,-1944.5 3273.2839,-1944.5 3273.2839,-1950.5 3267.2839,-1956.5 3261.2839,-1956.5 3261.2839,-1956.5 2652.2839,-1956.5 2652.2839,-1956.5 2646.2839,-1956.5 2640.2839,-1950.5 2640.2839,-1944.5 2640.2839,-1944.5 2640.2839,-1370.5 2640.2839,-1370.5 2640.2839,-1364.5 2646.2839,-1358.5 2652.2839,-1358.5"/>
<text text-anchor="middle" x="2746.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2852.2839,-1358.5 2852.2839,-1956.5 "/>
<text text-anchor="middle" x="2862.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1358.5 2873.2839,-1956.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cell_Barcode</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1933.5 3252.2839,-1933.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">Cryopreserved_Cells_in_Sample</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1910.5 3252.2839,-1910.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">Dissociation_Method</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1887.5 3252.2839,-1887.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">End_Bias</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1864.5 3252.2839,-1864.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">Input_Cells_and_Nuclei</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1841.5 3252.2839,-1841.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Construction_Method</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1818.5 3252.2839,-1818.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">Library_Preparation_Date</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1795.5 3252.2839,-1795.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">Nucleic_Acid_Capture_Date</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1772.5 3252.2839,-1772.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">Paired_End</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1749.5 3252.2839,-1749.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">Protocols_Link</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1726.5 3252.2839,-1726.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read1</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1703.5 3252.2839,-1703.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">Read2</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1680.5 3252.2839,-1680.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Feature_barcoding</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1657.5 3252.2839,-1657.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Oligo_dT_Poly_dT</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1634.5 3252.2839,-1634.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">Reverse_Transcription_Primer_Random</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1611.5 3252.2839,-1611.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">Sequencing_Library_Construction_Date</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1588.5 3252.2839,-1588.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Dissociation_Date</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1565.5 3252.2839,-1565.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">Single_Cell_Isolation_Method</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1542.5 3252.2839,-1542.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">Spike_In</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1519.5 3252.2839,-1519.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">Total_Number_of_Input_Cells</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1496.5 3252.2839,-1496.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">UMI</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1473.5 3252.2839,-1473.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1450.5 3252.2839,-1450.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Length</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1427.5 3252.2839,-1427.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">cDNA_Offset</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1404.5 3252.2839,-1404.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2873.2839,-1381.5 3252.2839,-1381.5 "/>
<text text-anchor="middle" x="3062.7839" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 23 properties</text>
<polyline fill="none" stroke="#000000" points="3252.2839,-1358.5 3252.2839,-1956.5 "/>
<text text-anchor="middle" x="3262.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3273.51,-1363.2824C3276.2654,-1361.4976 3279.0236,-1359.7363 3281.7839,-1358 3315.3861,-1336.8625 3326.347,-1334.9252 3364.7839,-1325 3425.9527,-1309.205 3452.9667,-1341.6621 3505.7839,-1307 3580.0415,-1258.2673 3627.6761,-1166.8986 3654.7975,-1097.8407"/>
<polygon fill="#000000" stroke="#000000" points="3658.1627,-1098.841 3658.4889,-1088.2512 3651.63,-1096.3262 3658.1627,-1098.841"/>
<text text-anchor="middle" x="3473.2839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node6" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M66.2839,-904C66.2839,-904 429.2839,-904 429.2839,-904 435.2839,-904 441.2839,-910 441.2839,-916 441.2839,-916 441.2839,-1099 441.2839,-1099 441.2839,-1105 435.2839,-1111 429.2839,-1111 429.2839,-1111 66.2839,-1111 66.2839,-1111 60.2839,-1111 54.2839,-1105 54.2839,-1099 54.2839,-1099 54.2839,-916 54.2839,-916 54.2839,-910 60.2839,-904 66.2839,-904"/>
<text text-anchor="middle" x="96.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="139.2839,-904 139.2839,-1111 "/>
<text text-anchor="middle" x="149.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="160.2839,-904 160.2839,-1111 "/>
<text text-anchor="middle" x="290.2839" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="160.2839,-1088 420.2839,-1088 "/>
<text text-anchor="middle" x="290.2839" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="160.2839,-1065 420.2839,-1065 "/>
<text text-anchor="middle" x="290.2839" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="160.2839,-1042 420.2839,-1042 "/>
<text text-anchor="middle" x="290.2839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="160.2839,-1019 420.2839,-1019 "/>
<text text-anchor="middle" x="290.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="160.2839,-996 420.2839,-996 "/>
<text text-anchor="middle" x="290.2839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="160.2839,-973 420.2839,-973 "/>
<text text-anchor="middle" x="290.2839" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="160.2839,-950 420.2839,-950 "/>
<text text-anchor="middle" x="290.2839" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="160.2839,-927 420.2839,-927 "/>
<text text-anchor="middle" x="290.2839" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="420.2839,-904 420.2839,-1111 "/>
<text text-anchor="middle" x="430.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M289.0676,-903.9728C321.9326,-836.097 374.916,-752.0472 449.7839,-708 575.4215,-634.0833 1535.2726,-608.9617 1935.4578,-601.6439"/>
<polygon fill="#000000" stroke="#000000" points="1935.7444,-605.1393 1945.6793,-601.4586 1935.6175,-598.1405 1935.7444,-605.1393"/>
<text text-anchor="middle" x="605.7839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M3303.2839,-1542.5C3303.2839,-1542.5 3670.2839,-1542.5 3670.2839,-1542.5 3676.2839,-1542.5 3682.2839,-1548.5 3682.2839,-1554.5 3682.2839,-1554.5 3682.2839,-1760.5 3682.2839,-1760.5 3682.2839,-1766.5 3676.2839,-1772.5 3670.2839,-1772.5 3670.2839,-1772.5 3303.2839,-1772.5 3303.2839,-1772.5 3297.2839,-1772.5 3291.2839,-1766.5 3291.2839,-1760.5 3291.2839,-1760.5 3291.2839,-1554.5 3291.2839,-1554.5 3291.2839,-1548.5 3297.2839,-1542.5 3303.2839,-1542.5"/>
<text text-anchor="middle" x="3380.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="3469.2839,-1542.5 3469.2839,-1772.5 "/>
<text text-anchor="middle" x="3479.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1542.5 3490.2839,-1772.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1749.5 3661.2839,-1749.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1726.5 3661.2839,-1726.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1703.5 3661.2839,-1703.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1680.5 3661.2839,-1680.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1657.5 3661.2839,-1657.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1634.5 3661.2839,-1634.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1611.5 3661.2839,-1611.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1588.5 3661.2839,-1588.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="3490.2839,-1565.5 3661.2839,-1565.5 "/>
<text text-anchor="middle" x="3575.7839" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="3661.2839,-1542.5 3661.2839,-1772.5 "/>
<text text-anchor="middle" x="3671.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3521.6632,-1542.4159C3560.1449,-1415.4457 3621.2704,-1213.7628 3656.4404,-1097.7195"/>
<polygon fill="#000000" stroke="#000000" points="3659.793,-1098.7246 3659.344,-1088.1393 3653.0939,-1096.6942 3659.793,-1098.7246"/>
<text text-anchor="middle" x="3677.2839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2128.2462,-541.3239C2151.2658,-478.944 2196.7356,-381.2957 2269.7839,-328 2366.7906,-257.2244 2673.9217,-200.3067 2887.3239,-167.9443"/>
<polygon fill="#000000" stroke="#000000" points="2888.048,-171.3747 2897.4139,-166.4218 2887.0036,-164.4531 2888.048,-171.3747"/>
<text text-anchor="middle" x="2320.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2392.2839,-374.5C2392.2839,-374.5 2689.2839,-374.5 2689.2839,-374.5 2695.2839,-374.5 2701.2839,-380.5 2701.2839,-386.5 2701.2839,-386.5 2701.2839,-431.5 2701.2839,-431.5 2701.2839,-437.5 2695.2839,-443.5 2689.2839,-443.5 2689.2839,-443.5 2392.2839,-443.5 2392.2839,-443.5 2386.2839,-443.5 2380.2839,-437.5 2380.2839,-431.5 2380.2839,-431.5 2380.2839,-386.5 2380.2839,-386.5 2380.2839,-380.5 2386.2839,-374.5 2392.2839,-374.5"/>
<text text-anchor="middle" x="2426.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2472.2839,-374.5 2472.2839,-443.5 "/>
<text text-anchor="middle" x="2482.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2493.2839,-374.5 2493.2839,-443.5 "/>
<text text-anchor="middle" x="2586.7839" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2493.2839,-420.5 2680.2839,-420.5 "/>
<text text-anchor="middle" x="2586.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2493.2839,-397.5 2680.2839,-397.5 "/>
<text text-anchor="middle" x="2586.7839" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2680.2839,-374.5 2680.2839,-443.5 "/>
<text text-anchor="middle" x="2690.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2240.2677,-541.4781C2309.1997,-511.0905 2391.9527,-474.61 2453.1523,-447.6311"/>
<polygon fill="#000000" stroke="#000000" points="2454.6636,-450.7899 2462.4021,-443.5535 2451.8399,-444.3847 2454.6636,-450.7899"/>
<text text-anchor="middle" x="2363.2839" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- imaging_file -->
<g id="node9" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M3712.7839,-1496.5C3712.7839,-1496.5 4046.7839,-1496.5 4046.7839,-1496.5 4052.7839,-1496.5 4058.7839,-1502.5 4058.7839,-1508.5 4058.7839,-1508.5 4058.7839,-1806.5 4058.7839,-1806.5 4058.7839,-1812.5 4052.7839,-1818.5 4046.7839,-1818.5 4046.7839,-1818.5 3712.7839,-1818.5 3712.7839,-1818.5 3706.7839,-1818.5 3700.7839,-1812.5 3700.7839,-1806.5 3700.7839,-1806.5 3700.7839,-1508.5 3700.7839,-1508.5 3700.7839,-1502.5 3706.7839,-1496.5 3712.7839,-1496.5"/>
<text text-anchor="middle" x="3752.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="3804.7839,-1496.5 3804.7839,-1818.5 "/>
<text text-anchor="middle" x="3815.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1496.5 3825.7839,-1818.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1795.5 4037.7839,-1795.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1772.5 4037.7839,-1772.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1749.5 4037.7839,-1749.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1726.5 4037.7839,-1726.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1703.5 4037.7839,-1703.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1680.5 4037.7839,-1680.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1657.5 4037.7839,-1657.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1634.5 4037.7839,-1634.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1611.5 4037.7839,-1611.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1588.5 4037.7839,-1588.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1565.5 4037.7839,-1565.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1542.5 4037.7839,-1542.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3825.7839,-1519.5 4037.7839,-1519.5 "/>
<text text-anchor="middle" x="3931.7839" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="4037.7839,-1496.5 4037.7839,-1818.5 "/>
<text text-anchor="middle" x="4048.2839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3831.2086,-1496.4084C3793.3187,-1370.7532 3742.0765,-1200.8174 3711.0593,-1097.9541"/>
<polygon fill="#000000" stroke="#000000" points="3714.3599,-1096.7765 3708.1219,-1088.2127 3707.658,-1098.7974 3714.3599,-1096.7765"/>
<text text-anchor="middle" x="3836.2839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M3336.2839,-351.5C3336.2839,-351.5 3643.2839,-351.5 3643.2839,-351.5 3649.2839,-351.5 3655.2839,-357.5 3655.2839,-363.5 3655.2839,-363.5 3655.2839,-454.5 3655.2839,-454.5 3655.2839,-460.5 3649.2839,-466.5 3643.2839,-466.5 3643.2839,-466.5 3336.2839,-466.5 3336.2839,-466.5 3330.2839,-466.5 3324.2839,-460.5 3324.2839,-454.5 3324.2839,-454.5 3324.2839,-363.5 3324.2839,-363.5 3324.2839,-357.5 3330.2839,-351.5 3336.2839,-351.5"/>
<text text-anchor="middle" x="3391.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="3458.2839,-351.5 3458.2839,-466.5 "/>
<text text-anchor="middle" x="3468.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3479.2839,-351.5 3479.2839,-466.5 "/>
<text text-anchor="middle" x="3556.7839" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="3479.2839,-443.5 3634.2839,-443.5 "/>
<text text-anchor="middle" x="3556.7839" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="3479.2839,-420.5 3634.2839,-420.5 "/>
<text text-anchor="middle" x="3556.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="3479.2839,-397.5 3634.2839,-397.5 "/>
<text text-anchor="middle" x="3556.7839" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="3479.2839,-374.5 3634.2839,-374.5 "/>
<text text-anchor="middle" x="3556.7839" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="3634.2839,-351.5 3634.2839,-466.5 "/>
<text text-anchor="middle" x="3644.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3407.6639,-351.3027C3378.6321,-330.905 3344.5411,-306.9528 3309.9029,-282.6161"/>
<polygon fill="#000000" stroke="#000000" points="3311.7584,-279.6423 3301.564,-276.7572 3307.7342,-285.3699 3311.7584,-279.6423"/>
<text text-anchor="middle" x="3413.2839" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M471.2839,-973C471.2839,-973 840.2839,-973 840.2839,-973 846.2839,-973 852.2839,-979 852.2839,-985 852.2839,-985 852.2839,-1030 852.2839,-1030 852.2839,-1036 846.2839,-1042 840.2839,-1042 840.2839,-1042 471.2839,-1042 471.2839,-1042 465.2839,-1042 459.2839,-1036 459.2839,-1030 459.2839,-1030 459.2839,-985 459.2839,-985 459.2839,-979 465.2839,-973 471.2839,-973"/>
<text text-anchor="middle" x="536.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="613.2839,-973 613.2839,-1042 "/>
<text text-anchor="middle" x="623.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="634.2839,-973 634.2839,-1042 "/>
<text text-anchor="middle" x="732.7839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="634.2839,-1019 831.2839,-1019 "/>
<text text-anchor="middle" x="732.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="634.2839,-996 831.2839,-996 "/>
<text text-anchor="middle" x="732.7839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="831.2839,-973 831.2839,-1042 "/>
<text text-anchor="middle" x="841.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M668.0951,-972.7567C693.0766,-907.9792 756.3813,-769.7461 860.7839,-708 951.0784,-654.5977 1613.6741,-619.8122 1935.4194,-605.8885"/>
<polygon fill="#000000" stroke="#000000" points="1935.9389,-609.3695 1945.779,-605.4423 1935.6376,-602.376 1935.9389,-609.3695"/>
<text text-anchor="middle" x="1067.2839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample_diagnosis -->
<g id="node12" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M4089.2839,-1496.5C4089.2839,-1496.5 4522.2839,-1496.5 4522.2839,-1496.5 4528.2839,-1496.5 4534.2839,-1502.5 4534.2839,-1508.5 4534.2839,-1508.5 4534.2839,-1806.5 4534.2839,-1806.5 4534.2839,-1812.5 4528.2839,-1818.5 4522.2839,-1818.5 4522.2839,-1818.5 4089.2839,-1818.5 4089.2839,-1818.5 4083.2839,-1818.5 4077.2839,-1812.5 4077.2839,-1806.5 4077.2839,-1806.5 4077.2839,-1508.5 4077.2839,-1508.5 4077.2839,-1502.5 4083.2839,-1496.5 4089.2839,-1496.5"/>
<text text-anchor="middle" x="4148.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4220.2839,-1496.5 4220.2839,-1818.5 "/>
<text text-anchor="middle" x="4230.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1496.5 4241.2839,-1818.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1795.5 4513.2839,-1795.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1772.5 4513.2839,-1772.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1749.5 4513.2839,-1749.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1726.5 4513.2839,-1726.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1703.5 4513.2839,-1703.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1680.5 4513.2839,-1680.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1657.5 4513.2839,-1657.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1634.5 4513.2839,-1634.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1611.5 4513.2839,-1611.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1588.5 4513.2839,-1588.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1565.5 4513.2839,-1565.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1542.5 4513.2839,-1542.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="4241.2839,-1519.5 4513.2839,-1519.5 "/>
<text text-anchor="middle" x="4377.2839" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="4513.2839,-1496.5 4513.2839,-1818.5 "/>
<text text-anchor="middle" x="4523.7839" y="-1653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M4185.2789,-1496.1914C4148.9555,-1450.2845 4108.0147,-1401.0788 4067.7839,-1358 3978.7087,-1262.619 3867.7601,-1163.1735 3788.0595,-1094.68"/>
<polygon fill="#000000" stroke="#000000" points="3790.3149,-1092.0034 3780.4459,-1088.1493 3785.7575,-1097.3166 3790.3149,-1092.0034"/>
<text text-anchor="middle" x="4122.7839" y="-1328.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M882.2839,-766C882.2839,-766 1293.2839,-766 1293.2839,-766 1299.2839,-766 1305.2839,-772 1305.2839,-778 1305.2839,-778 1305.2839,-1237 1305.2839,-1237 1305.2839,-1243 1299.2839,-1249 1293.2839,-1249 1293.2839,-1249 882.2839,-1249 882.2839,-1249 876.2839,-1249 870.2839,-1243 870.2839,-1237 870.2839,-1237 870.2839,-778 870.2839,-778 870.2839,-772 876.2839,-766 882.2839,-766"/>
<text text-anchor="middle" x="911.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="952.2839,-766 952.2839,-1249 "/>
<text text-anchor="middle" x="962.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="973.2839,-766 973.2839,-1249 "/>
<text text-anchor="middle" x="1128.7839" y="-1233.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1226 1284.2839,-1226 "/>
<text text-anchor="middle" x="1128.7839" y="-1210.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1203 1284.2839,-1203 "/>
<text text-anchor="middle" x="1128.7839" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1180 1284.2839,-1180 "/>
<text text-anchor="middle" x="1128.7839" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1157 1284.2839,-1157 "/>
<text text-anchor="middle" x="1128.7839" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1134 1284.2839,-1134 "/>
<text text-anchor="middle" x="1128.7839" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1111 1284.2839,-1111 "/>
<text text-anchor="middle" x="1128.7839" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1088 1284.2839,-1088 "/>
<text text-anchor="middle" x="1128.7839" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1065 1284.2839,-1065 "/>
<text text-anchor="middle" x="1128.7839" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1042 1284.2839,-1042 "/>
<text text-anchor="middle" x="1128.7839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="973.2839,-1019 1284.2839,-1019 "/>
<text text-anchor="middle" x="1128.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="973.2839,-996 1284.2839,-996 "/>
<text text-anchor="middle" x="1128.7839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="973.2839,-973 1284.2839,-973 "/>
<text text-anchor="middle" x="1128.7839" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="973.2839,-950 1284.2839,-950 "/>
<text text-anchor="middle" x="1128.7839" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="973.2839,-927 1284.2839,-927 "/>
<text text-anchor="middle" x="1128.7839" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="973.2839,-904 1284.2839,-904 "/>
<text text-anchor="middle" x="1128.7839" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="973.2839,-881 1284.2839,-881 "/>
<text text-anchor="middle" x="1128.7839" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="973.2839,-858 1284.2839,-858 "/>
<text text-anchor="middle" x="1128.7839" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="973.2839,-835 1284.2839,-835 "/>
<text text-anchor="middle" x="1128.7839" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="973.2839,-812 1284.2839,-812 "/>
<text text-anchor="middle" x="1128.7839" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="973.2839,-789 1284.2839,-789 "/>
<text text-anchor="middle" x="1128.7839" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="1284.2839,-766 1284.2839,-1249 "/>
<text text-anchor="middle" x="1294.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1242.3605,-765.6794C1264.4123,-743.5683 1288.6019,-723.6477 1314.7839,-708 1416.4323,-647.2497 1733.6739,-619.1162 1935.3381,-607.0703"/>
<polygon fill="#000000" stroke="#000000" points="1935.6745,-610.5566 1945.4511,-606.4739 1935.2623,-603.5688 1935.6745,-610.5566"/>
<text text-anchor="middle" x="1433.2839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- molecular_test -->
<g id="node14" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1335.7839,-708.5C1335.7839,-708.5 1723.7839,-708.5 1723.7839,-708.5 1729.7839,-708.5 1735.7839,-714.5 1735.7839,-720.5 1735.7839,-720.5 1735.7839,-1294.5 1735.7839,-1294.5 1735.7839,-1300.5 1729.7839,-1306.5 1723.7839,-1306.5 1723.7839,-1306.5 1335.7839,-1306.5 1335.7839,-1306.5 1329.7839,-1306.5 1323.7839,-1300.5 1323.7839,-1294.5 1323.7839,-1294.5 1323.7839,-720.5 1323.7839,-720.5 1323.7839,-714.5 1329.7839,-708.5 1335.7839,-708.5"/>
<text text-anchor="middle" x="1385.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1446.7839,-708.5 1446.7839,-1306.5 "/>
<text text-anchor="middle" x="1457.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1467.7839,-708.5 1467.7839,-1306.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1283.5 1714.7839,-1283.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1260.5 1714.7839,-1260.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1237.5 1714.7839,-1237.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1214.5 1714.7839,-1214.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1191.5 1714.7839,-1191.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1168.5 1714.7839,-1168.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1145.5 1714.7839,-1145.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1122.5 1714.7839,-1122.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1099.5 1714.7839,-1099.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1076.5 1714.7839,-1076.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1053.5 1714.7839,-1053.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1030.5 1714.7839,-1030.5 "/>
<text text-anchor="middle" x="1591.2839" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-1007.5 1714.7839,-1007.5 "/>
<text text-anchor="middle" x="1591.2839" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-984.5 1714.7839,-984.5 "/>
<text text-anchor="middle" x="1591.2839" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-961.5 1714.7839,-961.5 "/>
<text text-anchor="middle" x="1591.2839" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-938.5 1714.7839,-938.5 "/>
<text text-anchor="middle" x="1591.2839" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-915.5 1714.7839,-915.5 "/>
<text text-anchor="middle" x="1591.2839" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-892.5 1714.7839,-892.5 "/>
<text text-anchor="middle" x="1591.2839" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-869.5 1714.7839,-869.5 "/>
<text text-anchor="middle" x="1591.2839" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-846.5 1714.7839,-846.5 "/>
<text text-anchor="middle" x="1591.2839" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-823.5 1714.7839,-823.5 "/>
<text text-anchor="middle" x="1591.2839" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-800.5 1714.7839,-800.5 "/>
<text text-anchor="middle" x="1591.2839" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-777.5 1714.7839,-777.5 "/>
<text text-anchor="middle" x="1591.2839" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-754.5 1714.7839,-754.5 "/>
<text text-anchor="middle" x="1591.2839" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1467.7839,-731.5 1714.7839,-731.5 "/>
<text text-anchor="middle" x="1591.2839" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 11 properties</text>
<polyline fill="none" stroke="#000000" points="1714.7839,-708.5 1714.7839,-1306.5 "/>
<text text-anchor="middle" x="1725.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1599.1135,-708.468C1608.1433,-696.2828 1618.3192,-685.0115 1629.7839,-675 1674.8622,-635.6352 1817.3846,-616.5601 1935.5083,-607.3759"/>
<polygon fill="#000000" stroke="#000000" points="1936.0648,-610.8438 1945.7715,-606.5978 1935.5355,-603.8639 1936.0648,-610.8438"/>
<text text-anchor="middle" x="1693.7839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1886.7839,-812C1886.7839,-812 2260.7839,-812 2260.7839,-812 2266.7839,-812 2272.7839,-818 2272.7839,-824 2272.7839,-824 2272.7839,-1191 2272.7839,-1191 2272.7839,-1197 2266.7839,-1203 2260.7839,-1203 2260.7839,-1203 1886.7839,-1203 1886.7839,-1203 1880.7839,-1203 1874.7839,-1197 1874.7839,-1191 1874.7839,-1191 1874.7839,-824 1874.7839,-824 1874.7839,-818 1880.7839,-812 1886.7839,-812"/>
<text text-anchor="middle" x="1916.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1958.7839,-812 1958.7839,-1203 "/>
<text text-anchor="middle" x="1969.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1979.7839,-812 1979.7839,-1203 "/>
<text text-anchor="middle" x="2115.7839" y="-1187.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1180 2251.7839,-1180 "/>
<text text-anchor="middle" x="2115.7839" y="-1164.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1157 2251.7839,-1157 "/>
<text text-anchor="middle" x="2115.7839" y="-1141.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1134 2251.7839,-1134 "/>
<text text-anchor="middle" x="2115.7839" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1111 2251.7839,-1111 "/>
<text text-anchor="middle" x="2115.7839" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1088 2251.7839,-1088 "/>
<text text-anchor="middle" x="2115.7839" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1065 2251.7839,-1065 "/>
<text text-anchor="middle" x="2115.7839" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1042 2251.7839,-1042 "/>
<text text-anchor="middle" x="2115.7839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-1019 2251.7839,-1019 "/>
<text text-anchor="middle" x="2115.7839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-996 2251.7839,-996 "/>
<text text-anchor="middle" x="2115.7839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-973 2251.7839,-973 "/>
<text text-anchor="middle" x="2115.7839" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-950 2251.7839,-950 "/>
<text text-anchor="middle" x="2115.7839" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-927 2251.7839,-927 "/>
<text text-anchor="middle" x="2115.7839" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-904 2251.7839,-904 "/>
<text text-anchor="middle" x="2115.7839" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-881 2251.7839,-881 "/>
<text text-anchor="middle" x="2115.7839" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-858 2251.7839,-858 "/>
<text text-anchor="middle" x="2115.7839" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1979.7839,-835 2251.7839,-835 "/>
<text text-anchor="middle" x="2115.7839" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2251.7839,-812 2251.7839,-1203 "/>
<text text-anchor="middle" x="2262.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2091.0194,-811.9243C2095.6218,-759.7 2100.291,-706.7181 2103.8204,-666.6686"/>
<polygon fill="#000000" stroke="#000000" points="2107.324,-666.7815 2104.7154,-656.5128 2100.351,-666.1669 2107.324,-666.7815"/>
<text text-anchor="middle" x="2148.2839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M3132.7839,-881C3132.7839,-881 3484.7839,-881 3484.7839,-881 3490.7839,-881 3496.7839,-887 3496.7839,-893 3496.7839,-893 3496.7839,-1122 3496.7839,-1122 3496.7839,-1128 3490.7839,-1134 3484.7839,-1134 3484.7839,-1134 3132.7839,-1134 3132.7839,-1134 3126.7839,-1134 3120.7839,-1128 3120.7839,-1122 3120.7839,-1122 3120.7839,-893 3120.7839,-893 3120.7839,-887 3126.7839,-881 3132.7839,-881"/>
<text text-anchor="middle" x="3204.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="3287.7839,-881 3287.7839,-1134 "/>
<text text-anchor="middle" x="3298.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3308.7839,-881 3308.7839,-1134 "/>
<text text-anchor="middle" x="3392.2839" y="-1118.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-1111 3475.7839,-1111 "/>
<text text-anchor="middle" x="3392.2839" y="-1095.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-1088 3475.7839,-1088 "/>
<text text-anchor="middle" x="3392.2839" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-1065 3475.7839,-1065 "/>
<text text-anchor="middle" x="3392.2839" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-1042 3475.7839,-1042 "/>
<text text-anchor="middle" x="3392.2839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-1019 3475.7839,-1019 "/>
<text text-anchor="middle" x="3392.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-996 3475.7839,-996 "/>
<text text-anchor="middle" x="3392.2839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-973 3475.7839,-973 "/>
<text text-anchor="middle" x="3392.2839" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-950 3475.7839,-950 "/>
<text text-anchor="middle" x="3392.2839" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-927 3475.7839,-927 "/>
<text text-anchor="middle" x="3392.2839" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="3308.7839,-904 3475.7839,-904 "/>
<text text-anchor="middle" x="3392.2839" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3475.7839,-881 3475.7839,-1134 "/>
<text text-anchor="middle" x="3486.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3259.3249,-880.8964C3227.3781,-817.2679 3179.0559,-745.8177 3111.7839,-708 3062.3567,-680.214 2655.8417,-707.1132 2601.7839,-690 2590.1489,-686.3167 2590.1652,-679.4049 2578.7839,-675 2525.8604,-654.517 2394.337,-634.0968 2283.9962,-619.5893"/>
<polygon fill="#000000" stroke="#000000" points="2284.4354,-616.117 2274.0662,-618.2921 2283.5285,-623.058 2284.4354,-616.117"/>
<text text-anchor="middle" x="2731.2839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3233.4683,-880.7476C3198.8262,-825.8376 3155.7106,-761.9215 3111.7839,-708 3025.2421,-601.7671 2946.2198,-616.5914 2893.7839,-490 2866.2307,-423.4807 2864.457,-393.7566 2893.7839,-328 2900.5101,-312.9184 2909.0956,-298.5359 2918.9376,-284.9282"/>
<polygon fill="#000000" stroke="#000000" points="2922.0179,-286.6549 2925.2227,-276.5563 2916.4199,-282.4522 2922.0179,-286.6549"/>
<text text-anchor="middle" x="2995.7839" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M2302.7839,-973C2302.7839,-973 2656.7839,-973 2656.7839,-973 2662.7839,-973 2668.7839,-979 2668.7839,-985 2668.7839,-985 2668.7839,-1030 2668.7839,-1030 2668.7839,-1036 2662.7839,-1042 2656.7839,-1042 2656.7839,-1042 2302.7839,-1042 2302.7839,-1042 2296.7839,-1042 2290.7839,-1036 2290.7839,-1030 2290.7839,-1030 2290.7839,-985 2290.7839,-985 2290.7839,-979 2296.7839,-973 2302.7839,-973"/>
<text text-anchor="middle" x="2356.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="2421.7839,-973 2421.7839,-1042 "/>
<text text-anchor="middle" x="2432.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2442.7839,-973 2442.7839,-1042 "/>
<text text-anchor="middle" x="2545.2839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="2442.7839,-1019 2647.7839,-1019 "/>
<text text-anchor="middle" x="2545.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="2442.7839,-996 2647.7839,-996 "/>
<text text-anchor="middle" x="2545.2839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="2647.7839,-973 2647.7839,-1042 "/>
<text text-anchor="middle" x="2658.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2465.5585,-972.7586C2438.6123,-911.0281 2374.4126,-781.7955 2281.7839,-708 2263.9637,-693.803 2253.823,-700.8419 2233.7839,-690 2218.9612,-681.9804 2203.9105,-672.3841 2189.645,-662.4759"/>
<polygon fill="#000000" stroke="#000000" points="2191.5321,-659.5238 2181.3441,-656.6156 2187.4949,-665.2423 2191.5321,-659.5238"/>
<text text-anchor="middle" x="2301.7839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node19" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M3723.7839,-328.5C3723.7839,-328.5 4049.7839,-328.5 4049.7839,-328.5 4055.7839,-328.5 4061.7839,-334.5 4061.7839,-340.5 4061.7839,-340.5 4061.7839,-477.5 4061.7839,-477.5 4061.7839,-483.5 4055.7839,-489.5 4049.7839,-489.5 4049.7839,-489.5 3723.7839,-489.5 3723.7839,-489.5 3717.7839,-489.5 3711.7839,-483.5 3711.7839,-477.5 3711.7839,-477.5 3711.7839,-340.5 3711.7839,-340.5 3711.7839,-334.5 3717.7839,-328.5 3723.7839,-328.5"/>
<text text-anchor="middle" x="3765.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3819.7839,-328.5 3819.7839,-489.5 "/>
<text text-anchor="middle" x="3830.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3840.7839,-328.5 3840.7839,-489.5 "/>
<text text-anchor="middle" x="3940.7839" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3840.7839,-466.5 4040.7839,-466.5 "/>
<text text-anchor="middle" x="3940.7839" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3840.7839,-443.5 4040.7839,-443.5 "/>
<text text-anchor="middle" x="3940.7839" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3840.7839,-420.5 4040.7839,-420.5 "/>
<text text-anchor="middle" x="3940.7839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3840.7839,-397.5 4040.7839,-397.5 "/>
<text text-anchor="middle" x="3940.7839" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3840.7839,-374.5 4040.7839,-374.5 "/>
<text text-anchor="middle" x="3940.7839" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3840.7839,-351.5 4040.7839,-351.5 "/>
<text text-anchor="middle" x="3940.7839" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="4040.7839,-328.5 4040.7839,-489.5 "/>
<text text-anchor="middle" x="4051.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3764.3969,-328.3588C3742.7515,-316.0921 3720.0157,-304.4097 3697.7839,-295 3577.4953,-244.0875 3436.32,-206.0322 3321.8975,-180.2028"/>
<polygon fill="#000000" stroke="#000000" points="3322.4856,-176.7478 3311.9621,-177.9755 3320.9543,-183.5783 3322.4856,-176.7478"/>
<text text-anchor="middle" x="3782.2839" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3659.4554,-926.8598C3633.5497,-856.2141 3585.1473,-757.3423 3505.7839,-708 3404.3083,-644.91 2635.2898,-614.4351 2283.9387,-603.6908"/>
<polygon fill="#000000" stroke="#000000" points="2284.0245,-600.1918 2273.9228,-603.3864 2283.8118,-607.1886 2284.0245,-600.1918"/>
<text text-anchor="middle" x="3490.2839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3686.4896,-926.8652C3691.4595,-757.2091 3698.5824,-375.0625 3663.7839,-328 3621.4671,-270.7697 3460.4734,-219.8504 3322.0612,-185.2449"/>
<polygon fill="#000000" stroke="#000000" points="3322.6851,-181.7936 3312.1365,-182.7816 3320.9989,-188.5875 3322.6851,-181.7936"/>
<text text-anchor="middle" x="3725.2839" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M4091.7839,-391C4091.7839,-391 4301.7839,-391 4301.7839,-391 4307.7839,-391 4313.7839,-397 4313.7839,-403 4313.7839,-403 4313.7839,-415 4313.7839,-415 4313.7839,-421 4307.7839,-427 4301.7839,-427 4301.7839,-427 4091.7839,-427 4091.7839,-427 4085.7839,-427 4079.7839,-421 4079.7839,-415 4079.7839,-415 4079.7839,-403 4079.7839,-403 4079.7839,-397 4085.7839,-391 4091.7839,-391"/>
<text text-anchor="middle" x="4128.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="4176.7839,-391 4176.7839,-427 "/>
<text text-anchor="middle" x="4187.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4197.7839,-391 4197.7839,-427 "/>
<text text-anchor="middle" x="4245.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="4292.7839,-391 4292.7839,-427 "/>
<text text-anchor="middle" x="4303.2839" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge19" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4174.5492,-390.9616C4150.4376,-372.334 4110.1087,-343.822 4070.7839,-328 3824.8192,-229.0381 3522.2268,-180.4274 3321.9586,-157.4843"/>
<polygon fill="#000000" stroke="#000000" points="3322.2349,-153.9932 3311.9041,-156.3441 3321.4461,-160.9487 3322.2349,-153.9932"/>
<text text-anchor="middle" x="4072.7839" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2606.7692,-374.3416C2650.9626,-351.3584 2710.5735,-320.7969 2763.7839,-295 2803.9198,-275.5417 2846.9819,-255.2959 2888.5332,-236.0759"/>
<polygon fill="#000000" stroke="#000000" points="2890.0434,-239.2337 2897.6535,-231.8624 2887.1076,-232.8791 2890.0434,-239.2337"/>
<text text-anchor="middle" x="2812.2839" y="-298.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node23" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2698.7839,-950C2698.7839,-950 3090.7839,-950 3090.7839,-950 3096.7839,-950 3102.7839,-956 3102.7839,-962 3102.7839,-962 3102.7839,-1053 3102.7839,-1053 3102.7839,-1059 3096.7839,-1065 3090.7839,-1065 3090.7839,-1065 2698.7839,-1065 2698.7839,-1065 2692.7839,-1065 2686.7839,-1059 2686.7839,-1053 2686.7839,-1053 2686.7839,-962 2686.7839,-962 2686.7839,-956 2692.7839,-950 2698.7839,-950"/>
<text text-anchor="middle" x="2777.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2867.7839,-950 2867.7839,-1065 "/>
<text text-anchor="middle" x="2878.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2888.7839,-950 2888.7839,-1065 "/>
<text text-anchor="middle" x="2985.2839" y="-1049.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2888.7839,-1042 3081.7839,-1042 "/>
<text text-anchor="middle" x="2985.2839" y="-1026.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2888.7839,-1019 3081.7839,-1019 "/>
<text text-anchor="middle" x="2985.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2888.7839,-996 3081.7839,-996 "/>
<text text-anchor="middle" x="2985.2839" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2888.7839,-973 3081.7839,-973 "/>
<text text-anchor="middle" x="2985.2839" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3081.7839,-950 3081.7839,-1065 "/>
<text text-anchor="middle" x="3092.2839" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2871.5508,-949.7508C2839.6022,-878.8447 2774.8043,-761.4356 2677.7839,-708 2622.1976,-677.385 2453.0122,-709.9916 2392.7839,-690 2381.2013,-686.1554 2380.8711,-680.1002 2369.7839,-675 2342.7224,-662.5516 2313.1356,-651.6107 2283.9298,-642.1933"/>
<polygon fill="#000000" stroke="#000000" points="2284.6342,-638.745 2274.044,-639.058 2282.518,-645.4174 2284.6342,-638.745"/>
<text text-anchor="middle" x="2485.7839" y="-678.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
