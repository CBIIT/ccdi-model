<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Children's Cancer Data Initiative Model

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
<svg width="2563pt" height="1574pt"
 viewBox="0.00 0.00 2563.34 1574.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1570)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1570 2559.3365,-1570 2559.3365,4 -4,4"/>
<!-- imaging_file -->
<g id="node1" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1697.8365,-1117C1697.8365,-1117 2031.8365,-1117 2031.8365,-1117 2037.8365,-1117 2043.8365,-1123 2043.8365,-1129 2043.8365,-1129 2043.8365,-1427 2043.8365,-1427 2043.8365,-1433 2037.8365,-1439 2031.8365,-1439 2031.8365,-1439 1697.8365,-1439 1697.8365,-1439 1691.8365,-1439 1685.8365,-1433 1685.8365,-1427 1685.8365,-1427 1685.8365,-1129 1685.8365,-1129 1685.8365,-1123 1691.8365,-1117 1697.8365,-1117"/>
<text text-anchor="middle" x="1737.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1789.8365,-1117 1789.8365,-1439 "/>
<text text-anchor="middle" x="1800.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1117 1810.8365,-1439 "/>
<text text-anchor="middle" x="1916.8365" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1416 2022.8365,-1416 "/>
<text text-anchor="middle" x="1916.8365" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1393 2022.8365,-1393 "/>
<text text-anchor="middle" x="1916.8365" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1370 2022.8365,-1370 "/>
<text text-anchor="middle" x="1916.8365" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1347 2022.8365,-1347 "/>
<text text-anchor="middle" x="1916.8365" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1324 2022.8365,-1324 "/>
<text text-anchor="middle" x="1916.8365" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1301 2022.8365,-1301 "/>
<text text-anchor="middle" x="1916.8365" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1278 2022.8365,-1278 "/>
<text text-anchor="middle" x="1916.8365" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1255 2022.8365,-1255 "/>
<text text-anchor="middle" x="1916.8365" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1232 2022.8365,-1232 "/>
<text text-anchor="middle" x="1916.8365" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1209 2022.8365,-1209 "/>
<text text-anchor="middle" x="1916.8365" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1186 2022.8365,-1186 "/>
<text text-anchor="middle" x="1916.8365" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1163 2022.8365,-1163 "/>
<text text-anchor="middle" x="1916.8365" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1810.8365,-1140 2022.8365,-1140 "/>
<text text-anchor="middle" x="1916.8365" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="2022.8365,-1117 2022.8365,-1439 "/>
<text text-anchor="middle" x="2033.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1433.8365,-720C1433.8365,-720 1747.8365,-720 1747.8365,-720 1753.8365,-720 1759.8365,-726 1759.8365,-732 1759.8365,-732 1759.8365,-846 1759.8365,-846 1759.8365,-852 1753.8365,-858 1747.8365,-858 1747.8365,-858 1433.8365,-858 1433.8365,-858 1427.8365,-858 1421.8365,-852 1421.8365,-846 1421.8365,-846 1421.8365,-732 1421.8365,-732 1421.8365,-726 1427.8365,-720 1433.8365,-720"/>
<text text-anchor="middle" x="1455.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1489.8365,-720 1489.8365,-858 "/>
<text text-anchor="middle" x="1500.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1510.8365,-720 1510.8365,-858 "/>
<text text-anchor="middle" x="1624.8365" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1510.8365,-835 1738.8365,-835 "/>
<text text-anchor="middle" x="1624.8365" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1510.8365,-812 1738.8365,-812 "/>
<text text-anchor="middle" x="1624.8365" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1510.8365,-789 1738.8365,-789 "/>
<text text-anchor="middle" x="1624.8365" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1510.8365,-766 1738.8365,-766 "/>
<text text-anchor="middle" x="1624.8365" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1510.8365,-743 1738.8365,-743 "/>
<text text-anchor="middle" x="1624.8365" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1738.8365,-720 1738.8365,-858 "/>
<text text-anchor="middle" x="1749.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1811.9606,-1116.6837C1791.6028,-1063.9936 1765.9084,-1006.3712 1735.8365,-957 1716.3259,-924.9681 1690.6865,-893.0044 1666.4008,-865.6889"/>
<polygon fill="#000000" stroke="#000000" points="1668.8798,-863.2112 1659.593,-858.1116 1663.6727,-867.8895 1668.8798,-863.2112"/>
<text text-anchor="middle" x="1794.3365" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M343.3365,-1255C343.3365,-1255 644.3365,-1255 644.3365,-1255 650.3365,-1255 656.3365,-1261 656.3365,-1267 656.3365,-1267 656.3365,-1289 656.3365,-1289 656.3365,-1295 650.3365,-1301 644.3365,-1301 644.3365,-1301 343.3365,-1301 343.3365,-1301 337.3365,-1301 331.3365,-1295 331.3365,-1289 331.3365,-1289 331.3365,-1267 331.3365,-1267 331.3365,-1261 337.3365,-1255 343.3365,-1255"/>
<text text-anchor="middle" x="371.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="411.3365,-1255 411.3365,-1301 "/>
<text text-anchor="middle" x="421.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="432.3365,-1255 432.3365,-1301 "/>
<text text-anchor="middle" x="533.8365" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="432.3365,-1278 635.3365,-1278 "/>
<text text-anchor="middle" x="533.8365" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="635.3365,-1255 635.3365,-1301 "/>
<text text-anchor="middle" x="645.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M675.8365,-.5C675.8365,-.5 1065.8365,-.5 1065.8365,-.5 1071.8365,-.5 1077.8365,-6.5 1077.8365,-12.5 1077.8365,-12.5 1077.8365,-195.5 1077.8365,-195.5 1077.8365,-201.5 1071.8365,-207.5 1065.8365,-207.5 1065.8365,-207.5 675.8365,-207.5 675.8365,-207.5 669.8365,-207.5 663.8365,-201.5 663.8365,-195.5 663.8365,-195.5 663.8365,-12.5 663.8365,-12.5 663.8365,-6.5 669.8365,-.5 675.8365,-.5"/>
<text text-anchor="middle" x="691.8365" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="719.8365,-.5 719.8365,-207.5 "/>
<text text-anchor="middle" x="730.3365" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="740.8365,-.5 740.8365,-207.5 "/>
<text text-anchor="middle" x="898.8365" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="740.8365,-184.5 1056.8365,-184.5 "/>
<text text-anchor="middle" x="898.8365" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="740.8365,-161.5 1056.8365,-161.5 "/>
<text text-anchor="middle" x="898.8365" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="740.8365,-138.5 1056.8365,-138.5 "/>
<text text-anchor="middle" x="898.8365" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="740.8365,-115.5 1056.8365,-115.5 "/>
<text text-anchor="middle" x="898.8365" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="740.8365,-92.5 1056.8365,-92.5 "/>
<text text-anchor="middle" x="898.8365" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="740.8365,-69.5 1056.8365,-69.5 "/>
<text text-anchor="middle" x="898.8365" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="740.8365,-46.5 1056.8365,-46.5 "/>
<text text-anchor="middle" x="898.8365" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="740.8365,-23.5 1056.8365,-23.5 "/>
<text text-anchor="middle" x="898.8365" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1056.8365,-.5 1056.8365,-207.5 "/>
<text text-anchor="middle" x="1067.3365" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M435.5692,-1254.8289C332.7302,-1210.5719 120.6731,-1103.5312 22.8365,-939 -11.5094,-881.2409 3.8365,-856.1994 3.8365,-789 3.8365,-789 3.8365,-789 3.8365,-351.5 3.8365,-216.6283 396.6846,-151.1853 653.5005,-122.8132"/>
<polygon fill="#000000" stroke="#000000" points="654.159,-126.2621 663.7193,-121.6958 653.3981,-119.3036 654.159,-126.2621"/>
<text text-anchor="middle" x="46.3365" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M672.3365,-495.5C672.3365,-495.5 903.3365,-495.5 903.3365,-495.5 909.3365,-495.5 915.3365,-501.5 915.3365,-507.5 915.3365,-507.5 915.3365,-575.5 915.3365,-575.5 915.3365,-581.5 909.3365,-587.5 903.3365,-587.5 903.3365,-587.5 672.3365,-587.5 672.3365,-587.5 666.3365,-587.5 660.3365,-581.5 660.3365,-575.5 660.3365,-575.5 660.3365,-507.5 660.3365,-507.5 660.3365,-501.5 666.3365,-495.5 672.3365,-495.5"/>
<text text-anchor="middle" x="708.3365" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="756.3365,-495.5 756.3365,-587.5 "/>
<text text-anchor="middle" x="766.8365" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="777.3365,-495.5 777.3365,-587.5 "/>
<text text-anchor="middle" x="835.8365" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="777.3365,-564.5 894.3365,-564.5 "/>
<text text-anchor="middle" x="835.8365" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="777.3365,-541.5 894.3365,-541.5 "/>
<text text-anchor="middle" x="835.8365" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="777.3365,-518.5 894.3365,-518.5 "/>
<text text-anchor="middle" x="835.8365" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="894.3365,-495.5 894.3365,-587.5 "/>
<text text-anchor="middle" x="904.8365" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M485.6117,-1254.7559C455.4402,-1164.9852 359.8281,-836.1203 502.8365,-639 521.5304,-613.2326 586.905,-589.9217 650.3308,-572.5588"/>
<polygon fill="#000000" stroke="#000000" points="651.3319,-575.914 660.0766,-569.9324 649.5103,-569.1551 651.3319,-575.914"/>
<text text-anchor="middle" x="545.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M508.5237,-1254.6723C546.0154,-1197.4763 651.6285,-1050.5379 782.8365,-990 814.6705,-975.3121 1379.3992,-952.3029 1411.8365,-939 1452.1249,-922.4773 1490.1135,-893.4178 1520.6412,-865.2485"/>
<polygon fill="#000000" stroke="#000000" points="1523.3448,-867.511 1528.2386,-858.1141 1518.5529,-862.4082 1523.3448,-867.511"/>
<text text-anchor="middle" x="1245.3365" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M525.3365,-317C525.3365,-317 822.3365,-317 822.3365,-317 828.3365,-317 834.3365,-323 834.3365,-329 834.3365,-329 834.3365,-374 834.3365,-374 834.3365,-380 828.3365,-386 822.3365,-386 822.3365,-386 525.3365,-386 525.3365,-386 519.3365,-386 513.3365,-380 513.3365,-374 513.3365,-374 513.3365,-329 513.3365,-329 513.3365,-323 519.3365,-317 525.3365,-317"/>
<text text-anchor="middle" x="559.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="605.3365,-317 605.3365,-386 "/>
<text text-anchor="middle" x="615.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="626.3365,-317 626.3365,-386 "/>
<text text-anchor="middle" x="719.8365" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="626.3365,-363 813.3365,-363 "/>
<text text-anchor="middle" x="719.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="626.3365,-340 813.3365,-340 "/>
<text text-anchor="middle" x="719.8365" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="813.3365,-317 813.3365,-386 "/>
<text text-anchor="middle" x="823.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M695.7868,-316.7713C712.4774,-291.0564 736.4784,-255.5137 759.8365,-226 762.6104,-222.4951 765.4587,-218.964 768.362,-215.423"/>
<polygon fill="#000000" stroke="#000000" points="771.1091,-217.5933 774.7983,-207.6614 765.7208,-213.1249 771.1091,-217.5933"/>
<text text-anchor="middle" x="808.3365" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M156.8365,-259.5C156.8365,-259.5 482.8365,-259.5 482.8365,-259.5 488.8365,-259.5 494.8365,-265.5 494.8365,-271.5 494.8365,-271.5 494.8365,-431.5 494.8365,-431.5 494.8365,-437.5 488.8365,-443.5 482.8365,-443.5 482.8365,-443.5 156.8365,-443.5 156.8365,-443.5 150.8365,-443.5 144.8365,-437.5 144.8365,-431.5 144.8365,-431.5 144.8365,-271.5 144.8365,-271.5 144.8365,-265.5 150.8365,-259.5 156.8365,-259.5"/>
<text text-anchor="middle" x="198.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="252.8365,-259.5 252.8365,-443.5 "/>
<text text-anchor="middle" x="263.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="273.8365,-259.5 273.8365,-443.5 "/>
<text text-anchor="middle" x="373.8365" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="273.8365,-420.5 473.8365,-420.5 "/>
<text text-anchor="middle" x="373.8365" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="273.8365,-397.5 473.8365,-397.5 "/>
<text text-anchor="middle" x="373.8365" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="273.8365,-374.5 473.8365,-374.5 "/>
<text text-anchor="middle" x="373.8365" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="273.8365,-351.5 473.8365,-351.5 "/>
<text text-anchor="middle" x="373.8365" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="273.8365,-328.5 473.8365,-328.5 "/>
<text text-anchor="middle" x="373.8365" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="273.8365,-305.5 473.8365,-305.5 "/>
<text text-anchor="middle" x="373.8365" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="273.8365,-282.5 473.8365,-282.5 "/>
<text text-anchor="middle" x="373.8365" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="473.8365,-259.5 473.8365,-443.5 "/>
<text text-anchor="middle" x="484.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M495.0118,-263.1034C497.9719,-261.7182 500.9152,-260.3494 503.8365,-259 552.1595,-236.6788 604.596,-213.7701 654.3056,-192.6443"/>
<polygon fill="#000000" stroke="#000000" points="655.7151,-195.8484 663.5542,-188.721 652.9814,-189.4042 655.7151,-195.8484"/>
<text text-anchor="middle" x="630.3365" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1008.3365,-639.5C1008.3365,-639.5 1391.3365,-639.5 1391.3365,-639.5 1397.3365,-639.5 1403.3365,-645.5 1403.3365,-651.5 1403.3365,-651.5 1403.3365,-926.5 1403.3365,-926.5 1403.3365,-932.5 1397.3365,-938.5 1391.3365,-938.5 1391.3365,-938.5 1008.3365,-938.5 1008.3365,-938.5 1002.3365,-938.5 996.3365,-932.5 996.3365,-926.5 996.3365,-926.5 996.3365,-651.5 996.3365,-651.5 996.3365,-645.5 1002.3365,-639.5 1008.3365,-639.5"/>
<text text-anchor="middle" x="1038.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1080.3365,-639.5 1080.3365,-938.5 "/>
<text text-anchor="middle" x="1090.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1101.3365,-639.5 1101.3365,-938.5 "/>
<text text-anchor="middle" x="1241.8365" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-915.5 1382.3365,-915.5 "/>
<text text-anchor="middle" x="1241.8365" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-892.5 1382.3365,-892.5 "/>
<text text-anchor="middle" x="1241.8365" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-869.5 1382.3365,-869.5 "/>
<text text-anchor="middle" x="1241.8365" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-846.5 1382.3365,-846.5 "/>
<text text-anchor="middle" x="1241.8365" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-823.5 1382.3365,-823.5 "/>
<text text-anchor="middle" x="1241.8365" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-800.5 1382.3365,-800.5 "/>
<text text-anchor="middle" x="1241.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-777.5 1382.3365,-777.5 "/>
<text text-anchor="middle" x="1241.8365" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-754.5 1382.3365,-754.5 "/>
<text text-anchor="middle" x="1241.8365" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-731.5 1382.3365,-731.5 "/>
<text text-anchor="middle" x="1241.8365" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-708.5 1382.3365,-708.5 "/>
<text text-anchor="middle" x="1241.8365" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-685.5 1382.3365,-685.5 "/>
<text text-anchor="middle" x="1241.8365" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1101.3365,-662.5 1382.3365,-662.5 "/>
<text text-anchor="middle" x="1241.8365" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1382.3365,-639.5 1382.3365,-938.5 "/>
<text text-anchor="middle" x="1392.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1030.6319,-639.446C1013.3617,-627.2964 995.6168,-615.9067 977.8365,-606 961.3167,-596.7957 943.2591,-588.5945 925.0589,-581.3851"/>
<polygon fill="#000000" stroke="#000000" points="926.1251,-578.0449 915.5357,-577.7053 923.6021,-584.5744 926.1251,-578.0449"/>
<text text-anchor="middle" x="1043.3365" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node7" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M2074.3365,-990.5C2074.3365,-990.5 2543.3365,-990.5 2543.3365,-990.5 2549.3365,-990.5 2555.3365,-996.5 2555.3365,-1002.5 2555.3365,-1002.5 2555.3365,-1553.5 2555.3365,-1553.5 2555.3365,-1559.5 2549.3365,-1565.5 2543.3365,-1565.5 2543.3365,-1565.5 2074.3365,-1565.5 2074.3365,-1565.5 2068.3365,-1565.5 2062.3365,-1559.5 2062.3365,-1553.5 2062.3365,-1553.5 2062.3365,-1002.5 2062.3365,-1002.5 2062.3365,-996.5 2068.3365,-990.5 2074.3365,-990.5"/>
<text text-anchor="middle" x="2126.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="2190.3365,-990.5 2190.3365,-1565.5 "/>
<text text-anchor="middle" x="2200.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2211.3365,-990.5 2211.3365,-1565.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1542.5 2534.3365,-1542.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1519.5 2534.3365,-1519.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1496.5 2534.3365,-1496.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1473.5 2534.3365,-1473.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1450.5 2534.3365,-1450.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1427.5 2534.3365,-1427.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1404.5 2534.3365,-1404.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1381.5 2534.3365,-1381.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1358.5 2534.3365,-1358.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1335.5 2534.3365,-1335.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1312.5 2534.3365,-1312.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1289.5 2534.3365,-1289.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1266.5 2534.3365,-1266.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1243.5 2534.3365,-1243.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1220.5 2534.3365,-1220.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1197.5 2534.3365,-1197.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1174.5 2534.3365,-1174.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1151.5 2534.3365,-1151.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1128.5 2534.3365,-1128.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1105.5 2534.3365,-1105.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1082.5 2534.3365,-1082.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1059.5 2534.3365,-1059.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1036.5 2534.3365,-1036.5 "/>
<text text-anchor="middle" x="2372.8365" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2211.3365,-1013.5 2534.3365,-1013.5 "/>
<text text-anchor="middle" x="2372.8365" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2534.3365,-990.5 2534.3365,-1565.5 "/>
<text text-anchor="middle" x="2544.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2062.1462,-996.9016C2059.0545,-994.5593 2055.9508,-992.2577 2052.8365,-990 1967.1667,-927.8958 1859.3012,-879.6033 1769.3456,-845.9366"/>
<polygon fill="#000000" stroke="#000000" points="1770.4572,-842.616 1759.8643,-842.4173 1768.0213,-849.1785 1770.4572,-842.616"/>
<text text-anchor="middle" x="2085.3365" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M759.9489,-495.0208C741.6693,-464.5547 717.9293,-424.988 700.0063,-395.1164"/>
<polygon fill="#000000" stroke="#000000" points="702.7895,-392.9522 694.6433,-386.178 696.787,-396.5537 702.7895,-392.9522"/>
<text text-anchor="middle" x="798.3365" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M841.8844,-495.2092C846.2055,-489.4899 849.9922,-483.3907 852.8365,-477 872.7507,-432.2551 875.4286,-310.4046 874.2788,-218.0462"/>
<polygon fill="#000000" stroke="#000000" points="877.7749,-217.7389 874.1341,-207.7893 870.7756,-217.8377 877.7749,-217.7389"/>
<text text-anchor="middle" x="925.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1611.2883,-719.575C1646.9115,-592.1851 1711.3951,-327.8353 1654.8365,-259 1584.2608,-173.1052 1294.833,-134.0103 1088.2016,-116.7818"/>
<polygon fill="#000000" stroke="#000000" points="1088.3706,-113.2839 1078.1174,-115.9528 1087.797,-120.2604 1088.3706,-113.2839"/>
<text text-anchor="middle" x="1704.3365" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1525.9727,-719.771C1494.3735,-690.2254 1454.107,-658.194 1411.8365,-639 1327.4547,-600.6843 1082.4414,-570.4583 925.7197,-554.3445"/>
<polygon fill="#000000" stroke="#000000" points="925.8309,-550.8378 915.527,-553.3036 925.1196,-557.8015 925.8309,-550.8378"/>
<text text-anchor="middle" x="1388.3365" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample_diagnosis -->
<g id="node10" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M803.8365,-1059.5C803.8365,-1059.5 1245.8365,-1059.5 1245.8365,-1059.5 1251.8365,-1059.5 1257.8365,-1065.5 1257.8365,-1071.5 1257.8365,-1071.5 1257.8365,-1484.5 1257.8365,-1484.5 1257.8365,-1490.5 1251.8365,-1496.5 1245.8365,-1496.5 1245.8365,-1496.5 803.8365,-1496.5 803.8365,-1496.5 797.8365,-1496.5 791.8365,-1490.5 791.8365,-1484.5 791.8365,-1484.5 791.8365,-1071.5 791.8365,-1071.5 791.8365,-1065.5 797.8365,-1059.5 803.8365,-1059.5"/>
<text text-anchor="middle" x="863.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="934.8365,-1059.5 934.8365,-1496.5 "/>
<text text-anchor="middle" x="945.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="955.8365,-1059.5 955.8365,-1496.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1473.5 1236.8365,-1473.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1450.5 1236.8365,-1450.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1427.5 1236.8365,-1427.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1404.5 1236.8365,-1404.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1381.5 1236.8365,-1381.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1358.5 1236.8365,-1358.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1335.5 1236.8365,-1335.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis_reference_source</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1312.5 1236.8365,-1312.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1289.5 1236.8365,-1289.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1266.5 1236.8365,-1266.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1243.5 1236.8365,-1243.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1220.5 1236.8365,-1220.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1197.5 1236.8365,-1197.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1174.5 1236.8365,-1174.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1151.5 1236.8365,-1151.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1128.5 1236.8365,-1128.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1105.5 1236.8365,-1105.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="955.8365,-1082.5 1236.8365,-1082.5 "/>
<text text-anchor="middle" x="1096.3365" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1236.8365,-1059.5 1236.8365,-1496.5 "/>
<text text-anchor="middle" x="1247.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1185.9584,-1059.4243C1211.0606,-1033.7958 1238.2344,-1009.7823 1266.8365,-990 1323.0217,-951.1402 1352.4788,-972.8162 1411.8365,-939 1447.4097,-918.7338 1482.7692,-891.1178 1512.5491,-865.1031"/>
<polygon fill="#000000" stroke="#000000" points="1515.2167,-867.4168 1520.3951,-858.1738 1510.5829,-862.1701 1515.2167,-867.4168"/>
<text text-anchor="middle" x="1439.8365" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node11" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M609.3365,-731.5C609.3365,-731.5 966.3365,-731.5 966.3365,-731.5 972.3365,-731.5 978.3365,-737.5 978.3365,-743.5 978.3365,-743.5 978.3365,-834.5 978.3365,-834.5 978.3365,-840.5 972.3365,-846.5 966.3365,-846.5 966.3365,-846.5 609.3365,-846.5 609.3365,-846.5 603.3365,-846.5 597.3365,-840.5 597.3365,-834.5 597.3365,-834.5 597.3365,-743.5 597.3365,-743.5 597.3365,-737.5 603.3365,-731.5 609.3365,-731.5"/>
<text text-anchor="middle" x="687.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="778.3365,-731.5 778.3365,-846.5 "/>
<text text-anchor="middle" x="788.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="799.3365,-731.5 799.3365,-846.5 "/>
<text text-anchor="middle" x="878.3365" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="799.3365,-823.5 957.3365,-823.5 "/>
<text text-anchor="middle" x="878.3365" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="799.3365,-800.5 957.3365,-800.5 "/>
<text text-anchor="middle" x="878.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="799.3365,-777.5 957.3365,-777.5 "/>
<text text-anchor="middle" x="878.3365" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="799.3365,-754.5 957.3365,-754.5 "/>
<text text-anchor="middle" x="878.3365" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="957.3365,-731.5 957.3365,-846.5 "/>
<text text-anchor="middle" x="967.8365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M787.8365,-731.2846C787.8365,-691.0756 787.8365,-637.7127 787.8365,-597.8141"/>
<polygon fill="#000000" stroke="#000000" points="791.3366,-597.7183 787.8365,-587.7183 784.3366,-597.7184 791.3366,-597.7183"/>
<text text-anchor="middle" x="880.8365" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1001.8365,-333.5C1001.8365,-333.5 1211.8365,-333.5 1211.8365,-333.5 1217.8365,-333.5 1223.8365,-339.5 1223.8365,-345.5 1223.8365,-345.5 1223.8365,-357.5 1223.8365,-357.5 1223.8365,-363.5 1217.8365,-369.5 1211.8365,-369.5 1211.8365,-369.5 1001.8365,-369.5 1001.8365,-369.5 995.8365,-369.5 989.8365,-363.5 989.8365,-357.5 989.8365,-357.5 989.8365,-345.5 989.8365,-345.5 989.8365,-339.5 995.8365,-333.5 1001.8365,-333.5"/>
<text text-anchor="middle" x="1038.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1086.8365,-333.5 1086.8365,-369.5 "/>
<text text-anchor="middle" x="1097.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1107.8365,-333.5 1107.8365,-369.5 "/>
<text text-anchor="middle" x="1155.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1202.8365,-333.5 1202.8365,-369.5 "/>
<text text-anchor="middle" x="1213.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1089.4828,-333.3007C1065.3842,-308.0279 1019.8492,-260.2739 976.5461,-214.8607"/>
<polygon fill="#000000" stroke="#000000" points="979.053,-212.418 969.619,-207.5961 973.9869,-217.2487 979.053,-212.418"/>
<text text-anchor="middle" x="1047.8365" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node13" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M1254.3365,-317C1254.3365,-317 1633.3365,-317 1633.3365,-317 1639.3365,-317 1645.3365,-323 1645.3365,-329 1645.3365,-329 1645.3365,-374 1645.3365,-374 1645.3365,-380 1639.3365,-386 1633.3365,-386 1633.3365,-386 1254.3365,-386 1254.3365,-386 1248.3365,-386 1242.3365,-380 1242.3365,-374 1242.3365,-374 1242.3365,-329 1242.3365,-329 1242.3365,-323 1248.3365,-317 1254.3365,-317"/>
<text text-anchor="middle" x="1301.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="1361.3365,-317 1361.3365,-386 "/>
<text text-anchor="middle" x="1371.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1382.3365,-317 1382.3365,-386 "/>
<text text-anchor="middle" x="1503.3365" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1382.3365,-363 1624.3365,-363 "/>
<text text-anchor="middle" x="1503.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1382.3365,-340 1624.3365,-340 "/>
<text text-anchor="middle" x="1503.3365" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1624.3365,-317 1624.3365,-386 "/>
<text text-anchor="middle" x="1634.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1365.2497,-316.8571C1325.5829,-299.4197 1276.6937,-278.0022 1232.8365,-259 1185.8376,-238.6366 1135.3426,-216.9165 1087.4234,-196.378"/>
<polygon fill="#000000" stroke="#000000" points="1088.7623,-193.144 1078.1921,-192.4223 1086.0052,-199.5781 1088.7623,-193.144"/>
<text text-anchor="middle" x="1245.8365" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M43.8365,-662.5C43.8365,-662.5 395.8365,-662.5 395.8365,-662.5 401.8365,-662.5 407.8365,-668.5 407.8365,-674.5 407.8365,-674.5 407.8365,-903.5 407.8365,-903.5 407.8365,-909.5 401.8365,-915.5 395.8365,-915.5 395.8365,-915.5 43.8365,-915.5 43.8365,-915.5 37.8365,-915.5 31.8365,-909.5 31.8365,-903.5 31.8365,-903.5 31.8365,-674.5 31.8365,-674.5 31.8365,-668.5 37.8365,-662.5 43.8365,-662.5"/>
<text text-anchor="middle" x="115.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="198.8365,-662.5 198.8365,-915.5 "/>
<text text-anchor="middle" x="209.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="219.8365,-662.5 219.8365,-915.5 "/>
<text text-anchor="middle" x="303.3365" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="219.8365,-892.5 386.8365,-892.5 "/>
<text text-anchor="middle" x="303.3365" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="219.8365,-869.5 386.8365,-869.5 "/>
<text text-anchor="middle" x="303.3365" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="219.8365,-846.5 386.8365,-846.5 "/>
<text text-anchor="middle" x="303.3365" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="219.8365,-823.5 386.8365,-823.5 "/>
<text text-anchor="middle" x="303.3365" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="219.8365,-800.5 386.8365,-800.5 "/>
<text text-anchor="middle" x="303.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="219.8365,-777.5 386.8365,-777.5 "/>
<text text-anchor="middle" x="303.3365" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="219.8365,-754.5 386.8365,-754.5 "/>
<text text-anchor="middle" x="303.3365" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="219.8365,-731.5 386.8365,-731.5 "/>
<text text-anchor="middle" x="303.3365" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="219.8365,-708.5 386.8365,-708.5 "/>
<text text-anchor="middle" x="303.3365" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="219.8365,-685.5 386.8365,-685.5 "/>
<text text-anchor="middle" x="303.3365" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="386.8365,-662.5 386.8365,-915.5 "/>
<text text-anchor="middle" x="397.3365" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M150.0081,-662.3605C95.834,-545.0942 43.9915,-372.2337 135.8365,-259 200.1819,-179.6699 460.9961,-139.388 653.7391,-120.0704"/>
<polygon fill="#000000" stroke="#000000" points="654.123,-123.5496 663.7297,-119.0817 653.4336,-116.5836 654.123,-123.5496"/>
<text text-anchor="middle" x="176.8365" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M197.4694,-662.476C199.875,-641.6258 206.7234,-621.7229 220.8365,-606 249.0462,-574.5726 491.2051,-556.3962 649.8014,-547.7609"/>
<polygon fill="#000000" stroke="#000000" points="650.3262,-551.2378 660.1239,-547.2059 649.9503,-544.2479 650.3262,-551.2378"/>
<text text-anchor="middle" x="350.3365" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1288.3365,-1163C1288.3365,-1163 1655.3365,-1163 1655.3365,-1163 1661.3365,-1163 1667.3365,-1169 1667.3365,-1175 1667.3365,-1175 1667.3365,-1381 1667.3365,-1381 1667.3365,-1387 1661.3365,-1393 1655.3365,-1393 1655.3365,-1393 1288.3365,-1393 1288.3365,-1393 1282.3365,-1393 1276.3365,-1387 1276.3365,-1381 1276.3365,-1381 1276.3365,-1175 1276.3365,-1175 1276.3365,-1169 1282.3365,-1163 1288.3365,-1163"/>
<text text-anchor="middle" x="1365.3365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1454.3365,-1163 1454.3365,-1393 "/>
<text text-anchor="middle" x="1464.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1163 1475.3365,-1393 "/>
<text text-anchor="middle" x="1560.8365" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1370 1646.3365,-1370 "/>
<text text-anchor="middle" x="1560.8365" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1347 1646.3365,-1347 "/>
<text text-anchor="middle" x="1560.8365" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1324 1646.3365,-1324 "/>
<text text-anchor="middle" x="1560.8365" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1301 1646.3365,-1301 "/>
<text text-anchor="middle" x="1560.8365" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1278 1646.3365,-1278 "/>
<text text-anchor="middle" x="1560.8365" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1255 1646.3365,-1255 "/>
<text text-anchor="middle" x="1560.8365" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1232 1646.3365,-1232 "/>
<text text-anchor="middle" x="1560.8365" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1209 1646.3365,-1209 "/>
<text text-anchor="middle" x="1560.8365" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1475.3365,-1186 1646.3365,-1186 "/>
<text text-anchor="middle" x="1560.8365" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1646.3365,-1163 1646.3365,-1393 "/>
<text text-anchor="middle" x="1656.8365" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1499.8871,-1162.733C1521.9622,-1072.0212 1552.1421,-948.0044 1571.5649,-868.1915"/>
<polygon fill="#000000" stroke="#000000" points="1575.0327,-868.7435 1573.9965,-858.1994 1568.2312,-867.0882 1575.0327,-868.7435"/>
<text text-anchor="middle" x="1640.3365" y="-960.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node16" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1714.3365,-294C1714.3365,-294 2021.3365,-294 2021.3365,-294 2027.3365,-294 2033.3365,-300 2033.3365,-306 2033.3365,-306 2033.3365,-397 2033.3365,-397 2033.3365,-403 2027.3365,-409 2021.3365,-409 2021.3365,-409 1714.3365,-409 1714.3365,-409 1708.3365,-409 1702.3365,-403 1702.3365,-397 1702.3365,-397 1702.3365,-306 1702.3365,-306 1702.3365,-300 1708.3365,-294 1714.3365,-294"/>
<text text-anchor="middle" x="1769.3365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1836.3365,-294 1836.3365,-409 "/>
<text text-anchor="middle" x="1846.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1857.3365,-294 1857.3365,-409 "/>
<text text-anchor="middle" x="1934.8365" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1857.3365,-386 2012.3365,-386 "/>
<text text-anchor="middle" x="1934.8365" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1857.3365,-363 2012.3365,-363 "/>
<text text-anchor="middle" x="1934.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1857.3365,-340 2012.3365,-340 "/>
<text text-anchor="middle" x="1934.8365" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1857.3365,-317 2012.3365,-317 "/>
<text text-anchor="middle" x="1934.8365" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2012.3365,-294 2012.3365,-409 "/>
<text text-anchor="middle" x="2022.8365" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1801.2207,-293.9583C1769.003,-269.1608 1728.545,-242.1909 1687.8365,-226 1581.8811,-183.8587 1292.3135,-146.997 1088.1278,-125.1163"/>
<polygon fill="#000000" stroke="#000000" points="1088.4806,-121.6341 1078.1657,-124.0533 1087.7379,-128.5946 1088.4806,-121.6341"/>
<text text-anchor="middle" x="1784.3365" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
