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
<svg width="2685pt" height="1735pt"
 viewBox="0.00 0.00 2685.00 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 2681,-1731 2681,4 -4,4"/>
<!-- imaging_file -->
<g id="node1" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M12,-1278C12,-1278 346,-1278 346,-1278 352,-1278 358,-1284 358,-1290 358,-1290 358,-1588 358,-1588 358,-1594 352,-1600 346,-1600 346,-1600 12,-1600 12,-1600 6,-1600 0,-1594 0,-1588 0,-1588 0,-1290 0,-1290 0,-1284 6,-1278 12,-1278"/>
<text text-anchor="middle" x="52" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="104,-1278 104,-1600 "/>
<text text-anchor="middle" x="114.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="125,-1278 125,-1600 "/>
<text text-anchor="middle" x="231" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="125,-1577 337,-1577 "/>
<text text-anchor="middle" x="231" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="125,-1554 337,-1554 "/>
<text text-anchor="middle" x="231" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="125,-1531 337,-1531 "/>
<text text-anchor="middle" x="231" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="125,-1508 337,-1508 "/>
<text text-anchor="middle" x="231" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="125,-1485 337,-1485 "/>
<text text-anchor="middle" x="231" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="125,-1462 337,-1462 "/>
<text text-anchor="middle" x="231" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="125,-1439 337,-1439 "/>
<text text-anchor="middle" x="231" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="125,-1416 337,-1416 "/>
<text text-anchor="middle" x="231" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="125,-1393 337,-1393 "/>
<text text-anchor="middle" x="231" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="125,-1370 337,-1370 "/>
<text text-anchor="middle" x="231" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="125,-1347 337,-1347 "/>
<text text-anchor="middle" x="231" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="125,-1324 337,-1324 "/>
<text text-anchor="middle" x="231" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="125,-1301 337,-1301 "/>
<text text-anchor="middle" x="231" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="337,-1278 337,-1600 "/>
<text text-anchor="middle" x="347.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M907,-800.5C907,-800.5 1221,-800.5 1221,-800.5 1227,-800.5 1233,-806.5 1233,-812.5 1233,-812.5 1233,-949.5 1233,-949.5 1233,-955.5 1227,-961.5 1221,-961.5 1221,-961.5 907,-961.5 907,-961.5 901,-961.5 895,-955.5 895,-949.5 895,-949.5 895,-812.5 895,-812.5 895,-806.5 901,-800.5 907,-800.5"/>
<text text-anchor="middle" x="929" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="963,-800.5 963,-961.5 "/>
<text text-anchor="middle" x="973.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="984,-800.5 984,-961.5 "/>
<text text-anchor="middle" x="1098" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="984,-938.5 1212,-938.5 "/>
<text text-anchor="middle" x="1098" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="984,-915.5 1212,-915.5 "/>
<text text-anchor="middle" x="1098" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="984,-892.5 1212,-892.5 "/>
<text text-anchor="middle" x="1098" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="984,-869.5 1212,-869.5 "/>
<text text-anchor="middle" x="1098" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="984,-846.5 1212,-846.5 "/>
<text text-anchor="middle" x="1098" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="984,-823.5 1212,-823.5 "/>
<text text-anchor="middle" x="1098" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1212,-800.5 1212,-961.5 "/>
<text text-anchor="middle" x="1222.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M259.5369,-1277.6845C288.4315,-1231.9981 324.5527,-1185.3974 367,-1151 519.1755,-1027.6839 734.1993,-955.923 885.0621,-917.7913"/>
<polygon fill="#000000" stroke="#000000" points="886.0539,-921.1511 894.905,-915.328 884.3544,-914.3605 886.0539,-921.1511"/>
<text text-anchor="middle" x="453.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M318,-333.5C318,-333.5 528,-333.5 528,-333.5 534,-333.5 540,-339.5 540,-345.5 540,-345.5 540,-357.5 540,-357.5 540,-363.5 534,-369.5 528,-369.5 528,-369.5 318,-369.5 318,-369.5 312,-369.5 306,-363.5 306,-357.5 306,-357.5 306,-345.5 306,-345.5 306,-339.5 312,-333.5 318,-333.5"/>
<text text-anchor="middle" x="354.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="403,-333.5 403,-369.5 "/>
<text text-anchor="middle" x="413.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="424,-333.5 424,-369.5 "/>
<text text-anchor="middle" x="471.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="519,-333.5 519,-369.5 "/>
<text text-anchor="middle" x="529.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1230,-.5C1230,-.5 1620,-.5 1620,-.5 1626,-.5 1632,-6.5 1632,-12.5 1632,-12.5 1632,-195.5 1632,-195.5 1632,-201.5 1626,-207.5 1620,-207.5 1620,-207.5 1230,-207.5 1230,-207.5 1224,-207.5 1218,-201.5 1218,-195.5 1218,-195.5 1218,-12.5 1218,-12.5 1218,-6.5 1224,-.5 1230,-.5"/>
<text text-anchor="middle" x="1246" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1274,-.5 1274,-207.5 "/>
<text text-anchor="middle" x="1284.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1295,-.5 1295,-207.5 "/>
<text text-anchor="middle" x="1453" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="1295,-184.5 1611,-184.5 "/>
<text text-anchor="middle" x="1453" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1295,-161.5 1611,-161.5 "/>
<text text-anchor="middle" x="1453" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="1295,-138.5 1611,-138.5 "/>
<text text-anchor="middle" x="1453" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="1295,-115.5 1611,-115.5 "/>
<text text-anchor="middle" x="1453" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="1295,-92.5 1611,-92.5 "/>
<text text-anchor="middle" x="1453" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="1295,-69.5 1611,-69.5 "/>
<text text-anchor="middle" x="1453" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1295,-46.5 1611,-46.5 "/>
<text text-anchor="middle" x="1453" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1295,-23.5 1611,-23.5 "/>
<text text-anchor="middle" x="1453" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1611,-.5 1611,-207.5 "/>
<text text-anchor="middle" x="1621.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge15" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M441.7448,-333.3393C464.9389,-311.9804 506.5848,-277.143 549,-259 664.6392,-209.5355 987.7162,-160.2716 1207.4721,-130.9749"/>
<polygon fill="#000000" stroke="#000000" points="1208.0785,-134.4252 1217.5303,-129.6383 1207.1564,-127.4862 1208.0785,-134.4252"/>
<text text-anchor="middle" x="704" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M570.5,-317C570.5,-317 949.5,-317 949.5,-317 955.5,-317 961.5,-323 961.5,-329 961.5,-329 961.5,-374 961.5,-374 961.5,-380 955.5,-386 949.5,-386 949.5,-386 570.5,-386 570.5,-386 564.5,-386 558.5,-380 558.5,-374 558.5,-374 558.5,-329 558.5,-329 558.5,-323 564.5,-317 570.5,-317"/>
<text text-anchor="middle" x="618" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="677.5,-317 677.5,-386 "/>
<text text-anchor="middle" x="688" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="698.5,-317 698.5,-386 "/>
<text text-anchor="middle" x="819.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="698.5,-363 940.5,-363 "/>
<text text-anchor="middle" x="819.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="698.5,-340 940.5,-340 "/>
<text text-anchor="middle" x="819.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="940.5,-317 940.5,-386 "/>
<text text-anchor="middle" x="951" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M834.5534,-316.987C874.6514,-298.8903 925.1517,-276.8398 971,-259 1047.5742,-229.2046 1132.5537,-199.3545 1208.0881,-173.9168"/>
<polygon fill="#000000" stroke="#000000" points="1209.3626,-177.1809 1217.7266,-170.6775 1207.1326,-170.5456 1209.3626,-177.1809"/>
<text text-anchor="middle" x="1119" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M992,-259.5C992,-259.5 1318,-259.5 1318,-259.5 1324,-259.5 1330,-265.5 1330,-271.5 1330,-271.5 1330,-431.5 1330,-431.5 1330,-437.5 1324,-443.5 1318,-443.5 1318,-443.5 992,-443.5 992,-443.5 986,-443.5 980,-437.5 980,-431.5 980,-431.5 980,-271.5 980,-271.5 980,-265.5 986,-259.5 992,-259.5"/>
<text text-anchor="middle" x="1034" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="1088,-259.5 1088,-443.5 "/>
<text text-anchor="middle" x="1098.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1109,-259.5 1109,-443.5 "/>
<text text-anchor="middle" x="1209" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1109,-420.5 1309,-420.5 "/>
<text text-anchor="middle" x="1209" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1109,-397.5 1309,-397.5 "/>
<text text-anchor="middle" x="1209" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1109,-374.5 1309,-374.5 "/>
<text text-anchor="middle" x="1209" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1109,-351.5 1309,-351.5 "/>
<text text-anchor="middle" x="1209" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="1109,-328.5 1309,-328.5 "/>
<text text-anchor="middle" x="1209" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="1109,-305.5 1309,-305.5 "/>
<text text-anchor="middle" x="1209" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="1109,-282.5 1309,-282.5 "/>
<text text-anchor="middle" x="1209" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="1309,-259.5 1309,-443.5 "/>
<text text-anchor="middle" x="1319.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1203.8178,-259.3639C1212.0678,-247.4793 1221.1776,-235.9894 1231,-226 1234.8356,-222.0992 1238.8189,-218.2654 1242.9228,-214.5028"/>
<polygon fill="#000000" stroke="#000000" points="1245.298,-217.0742 1250.4345,-207.8077 1240.6405,-211.8485 1245.298,-217.0742"/>
<text text-anchor="middle" x="1287.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1125.7386,-800.3266C1187.7626,-715.7341 1282.0849,-576.8679 1339,-444 1370.134,-371.318 1391.8112,-284.8833 1405.6144,-217.3522"/>
<polygon fill="#000000" stroke="#000000" points="1409.0493,-218.0241 1407.594,-207.5297 1402.1873,-216.6411 1409.0493,-218.0241"/>
<text text-anchor="middle" x="1367.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1684,-495.5C1684,-495.5 1988,-495.5 1988,-495.5 1994,-495.5 2000,-501.5 2000,-507.5 2000,-507.5 2000,-598.5 2000,-598.5 2000,-604.5 1994,-610.5 1988,-610.5 1988,-610.5 1684,-610.5 1684,-610.5 1678,-610.5 1672,-604.5 1672,-598.5 1672,-598.5 1672,-507.5 1672,-507.5 1672,-501.5 1678,-495.5 1684,-495.5"/>
<text text-anchor="middle" x="1720" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1768,-495.5 1768,-610.5 "/>
<text text-anchor="middle" x="1778.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1789,-495.5 1789,-610.5 "/>
<text text-anchor="middle" x="1884" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1789,-587.5 1979,-587.5 "/>
<text text-anchor="middle" x="1884" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1789,-564.5 1979,-564.5 "/>
<text text-anchor="middle" x="1884" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1789,-541.5 1979,-541.5 "/>
<text text-anchor="middle" x="1884" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1789,-518.5 1979,-518.5 "/>
<text text-anchor="middle" x="1884" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1979,-495.5 1979,-610.5 "/>
<text text-anchor="middle" x="1989.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1109.2546,-800.2772C1140.3468,-752.4585 1186.0642,-694.9496 1242,-662 1281.2867,-638.8577 1298.136,-652.1383 1343,-644 1448.9741,-624.7764 1567.6896,-602.8746 1662.067,-585.3755"/>
<polygon fill="#000000" stroke="#000000" points="1662.7996,-588.7994 1671.9937,-583.5346 1661.5231,-581.9168 1662.7996,-588.7994"/>
<text text-anchor="middle" x="1459.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M1657.5,-823.5C1657.5,-823.5 2014.5,-823.5 2014.5,-823.5 2020.5,-823.5 2026.5,-829.5 2026.5,-835.5 2026.5,-835.5 2026.5,-926.5 2026.5,-926.5 2026.5,-932.5 2020.5,-938.5 2014.5,-938.5 2014.5,-938.5 1657.5,-938.5 1657.5,-938.5 1651.5,-938.5 1645.5,-932.5 1645.5,-926.5 1645.5,-926.5 1645.5,-835.5 1645.5,-835.5 1645.5,-829.5 1651.5,-823.5 1657.5,-823.5"/>
<text text-anchor="middle" x="1736" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="1826.5,-823.5 1826.5,-938.5 "/>
<text text-anchor="middle" x="1837" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1847.5,-823.5 1847.5,-938.5 "/>
<text text-anchor="middle" x="1926.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1847.5,-915.5 2005.5,-915.5 "/>
<text text-anchor="middle" x="1926.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1847.5,-892.5 2005.5,-892.5 "/>
<text text-anchor="middle" x="1926.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1847.5,-869.5 2005.5,-869.5 "/>
<text text-anchor="middle" x="1926.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1847.5,-846.5 2005.5,-846.5 "/>
<text text-anchor="middle" x="1926.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2005.5,-823.5 2005.5,-938.5 "/>
<text text-anchor="middle" x="2016" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1836,-823.4914C1836,-766.9583 1836,-680.6815 1836,-620.8296"/>
<polygon fill="#000000" stroke="#000000" points="1839.5001,-620.7182 1836,-610.7183 1832.5001,-620.7183 1839.5001,-620.7182"/>
<text text-anchor="middle" x="1929" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M388.5,-1151.5C388.5,-1151.5 857.5,-1151.5 857.5,-1151.5 863.5,-1151.5 869.5,-1157.5 869.5,-1163.5 869.5,-1163.5 869.5,-1714.5 869.5,-1714.5 869.5,-1720.5 863.5,-1726.5 857.5,-1726.5 857.5,-1726.5 388.5,-1726.5 388.5,-1726.5 382.5,-1726.5 376.5,-1720.5 376.5,-1714.5 376.5,-1714.5 376.5,-1163.5 376.5,-1163.5 376.5,-1157.5 382.5,-1151.5 388.5,-1151.5"/>
<text text-anchor="middle" x="440.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="504.5,-1151.5 504.5,-1726.5 "/>
<text text-anchor="middle" x="515" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="525.5,-1151.5 525.5,-1726.5 "/>
<text text-anchor="middle" x="687" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="525.5,-1703.5 848.5,-1703.5 "/>
<text text-anchor="middle" x="687" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="525.5,-1680.5 848.5,-1680.5 "/>
<text text-anchor="middle" x="687" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="525.5,-1657.5 848.5,-1657.5 "/>
<text text-anchor="middle" x="687" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="525.5,-1634.5 848.5,-1634.5 "/>
<text text-anchor="middle" x="687" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="525.5,-1611.5 848.5,-1611.5 "/>
<text text-anchor="middle" x="687" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="525.5,-1588.5 848.5,-1588.5 "/>
<text text-anchor="middle" x="687" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="525.5,-1565.5 848.5,-1565.5 "/>
<text text-anchor="middle" x="687" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="525.5,-1542.5 848.5,-1542.5 "/>
<text text-anchor="middle" x="687" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="525.5,-1519.5 848.5,-1519.5 "/>
<text text-anchor="middle" x="687" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="525.5,-1496.5 848.5,-1496.5 "/>
<text text-anchor="middle" x="687" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="525.5,-1473.5 848.5,-1473.5 "/>
<text text-anchor="middle" x="687" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="525.5,-1450.5 848.5,-1450.5 "/>
<text text-anchor="middle" x="687" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="525.5,-1427.5 848.5,-1427.5 "/>
<text text-anchor="middle" x="687" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="525.5,-1404.5 848.5,-1404.5 "/>
<text text-anchor="middle" x="687" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="525.5,-1381.5 848.5,-1381.5 "/>
<text text-anchor="middle" x="687" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="525.5,-1358.5 848.5,-1358.5 "/>
<text text-anchor="middle" x="687" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="525.5,-1335.5 848.5,-1335.5 "/>
<text text-anchor="middle" x="687" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="525.5,-1312.5 848.5,-1312.5 "/>
<text text-anchor="middle" x="687" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="525.5,-1289.5 848.5,-1289.5 "/>
<text text-anchor="middle" x="687" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="525.5,-1266.5 848.5,-1266.5 "/>
<text text-anchor="middle" x="687" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="525.5,-1243.5 848.5,-1243.5 "/>
<text text-anchor="middle" x="687" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="525.5,-1220.5 848.5,-1220.5 "/>
<text text-anchor="middle" x="687" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="525.5,-1197.5 848.5,-1197.5 "/>
<text text-anchor="middle" x="687" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="525.5,-1174.5 848.5,-1174.5 "/>
<text text-anchor="middle" x="687" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="848.5,-1151.5 848.5,-1726.5 "/>
<text text-anchor="middle" x="859" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M850.282,-1151.4187C902.6137,-1085.2031 954.4356,-1019.6325 993.9421,-969.6447"/>
<polygon fill="#000000" stroke="#000000" points="996.7205,-971.7739 1000.1751,-961.7581 991.2285,-967.4335 996.7205,-971.7739"/>
<text text-anchor="middle" x="936.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1263,-754.5C1263,-754.5 1615,-754.5 1615,-754.5 1621,-754.5 1627,-760.5 1627,-766.5 1627,-766.5 1627,-995.5 1627,-995.5 1627,-1001.5 1621,-1007.5 1615,-1007.5 1615,-1007.5 1263,-1007.5 1263,-1007.5 1257,-1007.5 1251,-1001.5 1251,-995.5 1251,-995.5 1251,-766.5 1251,-766.5 1251,-760.5 1257,-754.5 1263,-754.5"/>
<text text-anchor="middle" x="1334.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1418,-754.5 1418,-1007.5 "/>
<text text-anchor="middle" x="1428.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1439,-754.5 1439,-1007.5 "/>
<text text-anchor="middle" x="1522.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1439,-984.5 1606,-984.5 "/>
<text text-anchor="middle" x="1522.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1439,-961.5 1606,-961.5 "/>
<text text-anchor="middle" x="1522.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1439,-938.5 1606,-938.5 "/>
<text text-anchor="middle" x="1522.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1439,-915.5 1606,-915.5 "/>
<text text-anchor="middle" x="1522.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1439,-892.5 1606,-892.5 "/>
<text text-anchor="middle" x="1522.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1439,-869.5 1606,-869.5 "/>
<text text-anchor="middle" x="1522.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1439,-846.5 1606,-846.5 "/>
<text text-anchor="middle" x="1522.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1439,-823.5 1606,-823.5 "/>
<text text-anchor="middle" x="1522.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1439,-800.5 1606,-800.5 "/>
<text text-anchor="middle" x="1522.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1439,-777.5 1606,-777.5 "/>
<text text-anchor="middle" x="1522.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1606,-754.5 1606,-1007.5 "/>
<text text-anchor="middle" x="1616.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1430.8951,-754.0769C1426.3207,-671.0169 1421.589,-560.1011 1422,-462 1422.3419,-380.3956 1423.1222,-288.3308 1423.8013,-217.9993"/>
<polygon fill="#000000" stroke="#000000" points="1427.3031,-217.8177 1423.9007,-207.784 1420.3034,-217.7495 1427.3031,-217.8177"/>
<text text-anchor="middle" x="1508" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1482.3018,-754.3199C1503.3663,-709.1494 1532.9845,-661.4712 1573,-629 1588.6929,-616.2658 1622.9831,-603.6051 1661.7829,-592.3743"/>
<polygon fill="#000000" stroke="#000000" points="1663.0707,-595.6472 1671.7358,-589.5507 1661.1602,-588.9129 1663.0707,-595.6472"/>
<text text-anchor="middle" x="1702.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- pdx -->
<g id="node10" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M899.5,-1335.5C899.5,-1335.5 1228.5,-1335.5 1228.5,-1335.5 1234.5,-1335.5 1240.5,-1341.5 1240.5,-1347.5 1240.5,-1347.5 1240.5,-1530.5 1240.5,-1530.5 1240.5,-1536.5 1234.5,-1542.5 1228.5,-1542.5 1228.5,-1542.5 899.5,-1542.5 899.5,-1542.5 893.5,-1542.5 887.5,-1536.5 887.5,-1530.5 887.5,-1530.5 887.5,-1347.5 887.5,-1347.5 887.5,-1341.5 893.5,-1335.5 899.5,-1335.5"/>
<text text-anchor="middle" x="909" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="930.5,-1335.5 930.5,-1542.5 "/>
<text text-anchor="middle" x="941" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="951.5,-1335.5 951.5,-1542.5 "/>
<text text-anchor="middle" x="1085.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="951.5,-1519.5 1219.5,-1519.5 "/>
<text text-anchor="middle" x="1085.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="951.5,-1496.5 1219.5,-1496.5 "/>
<text text-anchor="middle" x="1085.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="951.5,-1473.5 1219.5,-1473.5 "/>
<text text-anchor="middle" x="1085.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="951.5,-1450.5 1219.5,-1450.5 "/>
<text text-anchor="middle" x="1085.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="951.5,-1427.5 1219.5,-1427.5 "/>
<text text-anchor="middle" x="1085.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="951.5,-1404.5 1219.5,-1404.5 "/>
<text text-anchor="middle" x="1085.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="951.5,-1381.5 1219.5,-1381.5 "/>
<text text-anchor="middle" x="1085.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="951.5,-1358.5 1219.5,-1358.5 "/>
<text text-anchor="middle" x="1085.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="1219.5,-1335.5 1219.5,-1542.5 "/>
<text text-anchor="middle" x="1230" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1064,-1335.3522C1064,-1230.9891 1064,-1071.5767 1064,-971.9709"/>
<polygon fill="#000000" stroke="#000000" points="1067.5001,-971.9248 1064,-961.9248 1060.5001,-971.9248 1067.5001,-971.9248"/>
<text text-anchor="middle" x="1088" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1685.5583,-495.4412C1617.6664,-469.435 1552.3565,-444.3597 1552,-444 1491.6333,-383.0885 1459.558,-290.8461 1442.7544,-217.8019"/>
<polygon fill="#000000" stroke="#000000" points="1446.0779,-216.625 1440.4834,-207.6277 1439.2461,-218.15 1446.0779,-216.625"/>
<text text-anchor="middle" x="1602.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2022.5,-317C2022.5,-317 2319.5,-317 2319.5,-317 2325.5,-317 2331.5,-323 2331.5,-329 2331.5,-329 2331.5,-374 2331.5,-374 2331.5,-380 2325.5,-386 2319.5,-386 2319.5,-386 2022.5,-386 2022.5,-386 2016.5,-386 2010.5,-380 2010.5,-374 2010.5,-374 2010.5,-329 2010.5,-329 2010.5,-323 2016.5,-317 2022.5,-317"/>
<text text-anchor="middle" x="2056.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2102.5,-317 2102.5,-386 "/>
<text text-anchor="middle" x="2113" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2123.5,-317 2123.5,-386 "/>
<text text-anchor="middle" x="2217" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2123.5,-363 2310.5,-363 "/>
<text text-anchor="middle" x="2217" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2123.5,-340 2310.5,-340 "/>
<text text-anchor="middle" x="2217" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2310.5,-317 2310.5,-386 "/>
<text text-anchor="middle" x="2321" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1931.9976,-495.2582C1987.2624,-462.0168 2055.3118,-421.0856 2104.6464,-391.4112"/>
<polygon fill="#000000" stroke="#000000" points="2106.5583,-394.3456 2113.3236,-386.1919 2102.9503,-388.3471 2106.5583,-394.3456"/>
<text text-anchor="middle" x="2033.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample_diagnosis -->
<g id="node12" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M1270.5,-1220.5C1270.5,-1220.5 1703.5,-1220.5 1703.5,-1220.5 1709.5,-1220.5 1715.5,-1226.5 1715.5,-1232.5 1715.5,-1232.5 1715.5,-1645.5 1715.5,-1645.5 1715.5,-1651.5 1709.5,-1657.5 1703.5,-1657.5 1703.5,-1657.5 1270.5,-1657.5 1270.5,-1657.5 1264.5,-1657.5 1258.5,-1651.5 1258.5,-1645.5 1258.5,-1645.5 1258.5,-1232.5 1258.5,-1232.5 1258.5,-1226.5 1264.5,-1220.5 1270.5,-1220.5"/>
<text text-anchor="middle" x="1330" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1401.5,-1220.5 1401.5,-1657.5 "/>
<text text-anchor="middle" x="1412" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1422.5,-1220.5 1422.5,-1657.5 "/>
<text text-anchor="middle" x="1558.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1634.5 1694.5,-1634.5 "/>
<text text-anchor="middle" x="1558.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1611.5 1694.5,-1611.5 "/>
<text text-anchor="middle" x="1558.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1588.5 1694.5,-1588.5 "/>
<text text-anchor="middle" x="1558.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1565.5 1694.5,-1565.5 "/>
<text text-anchor="middle" x="1558.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1542.5 1694.5,-1542.5 "/>
<text text-anchor="middle" x="1558.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1519.5 1694.5,-1519.5 "/>
<text text-anchor="middle" x="1558.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1496.5 1694.5,-1496.5 "/>
<text text-anchor="middle" x="1558.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1473.5 1694.5,-1473.5 "/>
<text text-anchor="middle" x="1558.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1450.5 1694.5,-1450.5 "/>
<text text-anchor="middle" x="1558.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1427.5 1694.5,-1427.5 "/>
<text text-anchor="middle" x="1558.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1404.5 1694.5,-1404.5 "/>
<text text-anchor="middle" x="1558.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1381.5 1694.5,-1381.5 "/>
<text text-anchor="middle" x="1558.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1358.5 1694.5,-1358.5 "/>
<text text-anchor="middle" x="1558.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1335.5 1694.5,-1335.5 "/>
<text text-anchor="middle" x="1558.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1312.5 1694.5,-1312.5 "/>
<text text-anchor="middle" x="1558.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1289.5 1694.5,-1289.5 "/>
<text text-anchor="middle" x="1558.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1266.5 1694.5,-1266.5 "/>
<text text-anchor="middle" x="1558.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1422.5,-1243.5 1694.5,-1243.5 "/>
<text text-anchor="middle" x="1558.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1694.5,-1220.5 1694.5,-1657.5 "/>
<text text-anchor="middle" x="1705" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1321.3366,-1220.4653C1255.0194,-1132.983 1182.3862,-1037.169 1131.2467,-969.7085"/>
<polygon fill="#000000" stroke="#000000" points="1133.9489,-967.4793 1125.1186,-961.6246 1128.3706,-971.708 1133.9489,-967.4793"/>
<text text-anchor="middle" x="1325" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1673.5,-294C1673.5,-294 1980.5,-294 1980.5,-294 1986.5,-294 1992.5,-300 1992.5,-306 1992.5,-306 1992.5,-397 1992.5,-397 1992.5,-403 1986.5,-409 1980.5,-409 1980.5,-409 1673.5,-409 1673.5,-409 1667.5,-409 1661.5,-403 1661.5,-397 1661.5,-397 1661.5,-306 1661.5,-306 1661.5,-300 1667.5,-294 1673.5,-294"/>
<text text-anchor="middle" x="1728.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1795.5,-294 1795.5,-409 "/>
<text text-anchor="middle" x="1806" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1816.5,-294 1816.5,-409 "/>
<text text-anchor="middle" x="1894" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1816.5,-386 1971.5,-386 "/>
<text text-anchor="middle" x="1894" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1816.5,-363 1971.5,-363 "/>
<text text-anchor="middle" x="1894" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1816.5,-340 1971.5,-340 "/>
<text text-anchor="middle" x="1894" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1816.5,-317 1971.5,-317 "/>
<text text-anchor="middle" x="1894" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1971.5,-294 1971.5,-409 "/>
<text text-anchor="middle" x="1982" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1733.5096,-293.9406C1694.2821,-269.7894 1647.3135,-240.8721 1601.9961,-212.9715"/>
<polygon fill="#000000" stroke="#000000" points="1603.6077,-209.8536 1593.2572,-207.5912 1599.9377,-215.8144 1603.6077,-209.8536"/>
<text text-anchor="middle" x="1707.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2057,-662.5C2057,-662.5 2431,-662.5 2431,-662.5 2437,-662.5 2443,-668.5 2443,-674.5 2443,-674.5 2443,-1087.5 2443,-1087.5 2443,-1093.5 2437,-1099.5 2431,-1099.5 2431,-1099.5 2057,-1099.5 2057,-1099.5 2051,-1099.5 2045,-1093.5 2045,-1087.5 2045,-1087.5 2045,-674.5 2045,-674.5 2045,-668.5 2051,-662.5 2057,-662.5"/>
<text text-anchor="middle" x="2087" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2129,-662.5 2129,-1099.5 "/>
<text text-anchor="middle" x="2139.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2150,-662.5 2150,-1099.5 "/>
<text text-anchor="middle" x="2286" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2150,-1076.5 2422,-1076.5 "/>
<text text-anchor="middle" x="2286" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2150,-1053.5 2422,-1053.5 "/>
<text text-anchor="middle" x="2286" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2150,-1030.5 2422,-1030.5 "/>
<text text-anchor="middle" x="2286" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2150,-1007.5 2422,-1007.5 "/>
<text text-anchor="middle" x="2286" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="2150,-984.5 2422,-984.5 "/>
<text text-anchor="middle" x="2286" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="2150,-961.5 2422,-961.5 "/>
<text text-anchor="middle" x="2286" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="2150,-938.5 2422,-938.5 "/>
<text text-anchor="middle" x="2286" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2150,-915.5 2422,-915.5 "/>
<text text-anchor="middle" x="2286" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2150,-892.5 2422,-892.5 "/>
<text text-anchor="middle" x="2286" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2150,-869.5 2422,-869.5 "/>
<text text-anchor="middle" x="2286" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2150,-846.5 2422,-846.5 "/>
<text text-anchor="middle" x="2286" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2150,-823.5 2422,-823.5 "/>
<text text-anchor="middle" x="2286" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2150,-800.5 2422,-800.5 "/>
<text text-anchor="middle" x="2286" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2150,-777.5 2422,-777.5 "/>
<text text-anchor="middle" x="2286" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="2150,-754.5 2422,-754.5 "/>
<text text-anchor="middle" x="2286" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="2150,-731.5 2422,-731.5 "/>
<text text-anchor="middle" x="2286" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2150,-708.5 2422,-708.5 "/>
<text text-anchor="middle" x="2286" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2150,-685.5 2422,-685.5 "/>
<text text-anchor="middle" x="2286" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2422,-662.5 2422,-1099.5 "/>
<text text-anchor="middle" x="2432.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2067.6604,-662.4132C2054.1794,-650.4274 2040.2518,-639.1543 2026,-629 2019.4898,-624.3616 2012.6563,-619.9514 2005.6066,-615.7652"/>
<polygon fill="#000000" stroke="#000000" points="2006.9852,-612.5211 1996.5693,-610.5821 2003.5026,-618.5934 2006.9852,-612.5211"/>
<text text-anchor="middle" x="2084.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2115.9207,-316.9839C2083.6531,-297.8889 2041.578,-274.8822 2002,-259 1886.2472,-212.5498 1751.9327,-175.5386 1642.0321,-149.3474"/>
<polygon fill="#000000" stroke="#000000" points="1642.6868,-145.9056 1632.1492,-147.0055 1641.0727,-152.717 1642.6868,-145.9056"/>
<text text-anchor="middle" x="1989.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1745.5,-1324C1745.5,-1324 2112.5,-1324 2112.5,-1324 2118.5,-1324 2124.5,-1330 2124.5,-1336 2124.5,-1336 2124.5,-1542 2124.5,-1542 2124.5,-1548 2118.5,-1554 2112.5,-1554 2112.5,-1554 1745.5,-1554 1745.5,-1554 1739.5,-1554 1733.5,-1548 1733.5,-1542 1733.5,-1542 1733.5,-1336 1733.5,-1336 1733.5,-1330 1739.5,-1324 1745.5,-1324"/>
<text text-anchor="middle" x="1822.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1911.5,-1324 1911.5,-1554 "/>
<text text-anchor="middle" x="1922" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1932.5,-1324 1932.5,-1554 "/>
<text text-anchor="middle" x="2018" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1531 2103.5,-1531 "/>
<text text-anchor="middle" x="2018" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1508 2103.5,-1508 "/>
<text text-anchor="middle" x="2018" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1485 2103.5,-1485 "/>
<text text-anchor="middle" x="2018" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1462 2103.5,-1462 "/>
<text text-anchor="middle" x="2018" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1439 2103.5,-1439 "/>
<text text-anchor="middle" x="2018" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1416 2103.5,-1416 "/>
<text text-anchor="middle" x="2018" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1393 2103.5,-1393 "/>
<text text-anchor="middle" x="2018" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1370 2103.5,-1370 "/>
<text text-anchor="middle" x="2018" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1932.5,-1347 2103.5,-1347 "/>
<text text-anchor="middle" x="2018" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2103.5,-1324 2103.5,-1554 "/>
<text text-anchor="middle" x="2114" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1877.1555,-1323.6363C1843.0768,-1261.7957 1792.2785,-1190.4061 1725,-1151 1713.3586,-1144.1815 1253.8606,-1106.4296 1242,-1100 1187.7646,-1070.5993 1143.8196,-1017.1406 1113.1627,-970.4022"/>
<polygon fill="#000000" stroke="#000000" points="1115.9526,-968.2703 1107.5935,-961.7607 1110.0687,-972.0623 1115.9526,-968.2703"/>
<text text-anchor="middle" x="1644.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2328.5,-1416C2328.5,-1416 2629.5,-1416 2629.5,-1416 2635.5,-1416 2641.5,-1422 2641.5,-1428 2641.5,-1428 2641.5,-1450 2641.5,-1450 2641.5,-1456 2635.5,-1462 2629.5,-1462 2629.5,-1462 2328.5,-1462 2328.5,-1462 2322.5,-1462 2316.5,-1456 2316.5,-1450 2316.5,-1450 2316.5,-1428 2316.5,-1428 2316.5,-1422 2322.5,-1416 2328.5,-1416"/>
<text text-anchor="middle" x="2356.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2396.5,-1416 2396.5,-1462 "/>
<text text-anchor="middle" x="2407" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2417.5,-1416 2417.5,-1462 "/>
<text text-anchor="middle" x="2519" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2417.5,-1439 2620.5,-1439 "/>
<text text-anchor="middle" x="2519" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2620.5,-1416 2620.5,-1462 "/>
<text text-anchor="middle" x="2631" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2487.2542,-1415.9465C2506.2983,-1361.6867 2553.3322,-1221.3351 2575,-1100 2592.1624,-1003.8942 2592,-978.6261 2592,-881 2592,-881 2592,-881 2592,-351.5 2592,-255.5405 1980.3793,-168.806 1642.6976,-128.2317"/>
<polygon fill="#000000" stroke="#000000" points="1642.6367,-124.6994 1632.2915,-126.9855 1641.8043,-131.6498 1642.6367,-124.6994"/>
<text text-anchor="middle" x="2634.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2460.3042,-1415.6615C2412.8944,-1358.4409 2281.2396,-1211.4508 2134,-1151 1971.4428,-1084.2604 1915.4097,-1128.51 1740,-1118 1684.7297,-1114.6884 1291.5593,-1124.6912 1242,-1100 1186.1501,-1072.1748 1141.8164,-1017.8359 1111.3626,-970.2493"/>
<polygon fill="#000000" stroke="#000000" points="1114.3114,-968.3636 1106.0278,-961.758 1108.3841,-972.0875 1114.3114,-968.3636"/>
<text text-anchor="middle" x="2121.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2479.8975,-1415.6393C2484.4137,-1292.2851 2502.5081,-720.1483 2452,-662 2395.4076,-596.847 2171.684,-570.5802 2010.1462,-560.028"/>
<polygon fill="#000000" stroke="#000000" points="2010.2863,-556.5299 2000.0836,-559.3856 2009.8403,-563.5157 2010.2863,-556.5299"/>
<text text-anchor="middle" x="2528.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
