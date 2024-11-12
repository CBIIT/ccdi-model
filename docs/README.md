<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Childhood Cancer Data Initiative Model

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
<svg width="2945pt" height="305pt"
 viewBox="0.00 0.00 2945.19 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2941.1938,-301 2941.1938,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1404.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1404.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1703.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1703.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1420.2293,-173.9633C1431.3944,-162.6124 1447.2703,-148.7001 1464.1938,-141 1493.529,-127.6527 1573.7138,-117.3613 1633.1609,-111.2643"/>
<polygon fill="#000000" stroke="#000000" points="1633.6568,-114.7321 1643.2561,-110.2484 1632.9559,-107.7673 1633.6568,-114.7321"/>
<text text-anchor="middle" x="1532.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1612.1938" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1612.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1605.98,-174.0016C1603.535,-163.503 1602.6593,-150.4999 1609.1938,-141 1614.2493,-133.6502 1630.2227,-126.4371 1647.6017,-120.4206"/>
<polygon fill="#000000" stroke="#000000" points="1648.9407,-123.6644 1657.3409,-117.2079 1646.7478,-117.0168 1648.9407,-123.6644"/>
<text text-anchor="middle" x="1692.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1835.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1835.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1816.6718,-174.2199C1805.2609,-163.7987 1790.0201,-150.8003 1775.1938,-141 1766.2704,-135.1016 1756.2468,-129.5122 1746.5785,-124.5743"/>
<polygon fill="#000000" stroke="#000000" points="1747.9787,-121.3619 1737.4653,-120.0508 1744.8664,-127.632 1747.9787,-121.3619"/>
<text text-anchor="middle" x="1873.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="899.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="899.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="504.1938" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="504.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M862.2339,-202.0052C849.6209,-205.0539 835.3739,-208.0986 822.1938,-210 787.3861,-215.0214 530.8402,-202.9133 506.1938,-228 500.2778,-234.0216 498.4879,-242.6241 498.5725,-251.0528"/>
<polygon fill="#000000" stroke="#000000" points="495.0901,-251.4081 499.4539,-261.0625 502.0632,-250.7941 495.0901,-251.4081"/>
<text text-anchor="middle" x="542.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="773.1938" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="773.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M860.3234,-183.2445C825.6763,-175.0532 779.6105,-163.052 774.1938,-156 769.3176,-149.6517 767.7601,-141.4282 767.7858,-133.4452"/>
<polygon fill="#000000" stroke="#000000" points="771.2913,-133.5106 768.5854,-123.2671 764.3129,-132.9623 771.2913,-133.5106"/>
<text text-anchor="middle" x="810.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M940.4411,-185.3698C969.6665,-179.7813 1009.3553,-170.3611 1042.1938,-156 1053.3753,-151.11 1053.5983,-144.8058 1065.1938,-141 1117.6799,-123.7734 1474.6882,-111.5607 1630.598,-106.9876"/>
<polygon fill="#000000" stroke="#000000" points="1631.1264,-110.4738 1641.0204,-106.6845 1630.9229,-103.4768 1631.1264,-110.4738"/>
<text text-anchor="middle" x="1101.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="641.1938" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="641.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M651.9078,-260.8656C659.6542,-249.4735 671.1974,-235.5519 685.1938,-228 739.2406,-198.8384 761.7753,-221.0031 822.1938,-210 831.7168,-208.2657 841.8351,-206.1213 851.4984,-203.9243"/>
<polygon fill="#000000" stroke="#000000" points="852.4127,-207.3051 861.3598,-201.6307 850.8269,-200.4871 852.4127,-207.3051"/>
<text text-anchor="middle" x="751.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="773.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="773.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M84.656,-87.2032C95.3279,-75.4891 110.9449,-61.0602 128.1938,-54 183.0729,-31.5371 587.4876,-21.619 726.4567,-18.8492"/>
<polygon fill="#000000" stroke="#000000" points="726.8372,-22.3425 736.7667,-18.6472 726.7,-15.3439 726.8372,-22.3425"/>
<text text-anchor="middle" x="184.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="236.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="236.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M238.3847,-86.9333C240.7746,-75.5698 245.7675,-61.6547 256.1938,-54 293.5883,-26.5459 606.2773,-19.9621 726.4247,-18.4399"/>
<polygon fill="#000000" stroke="#000000" points="726.4708,-21.9397 736.4278,-18.3193 726.3863,-14.9402 726.4708,-21.9397"/>
<text text-anchor="middle" x="318.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="394.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="394.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M386.2456,-86.8064C382.8633,-75.9708 381.2869,-62.6828 389.1938,-54 411.5139,-29.4895 629.0919,-21.3574 726.4794,-18.9314"/>
<polygon fill="#000000" stroke="#000000" points="726.7177,-22.4268 736.6311,-18.6884 726.5501,-15.4288 726.7177,-22.4268"/>
<text text-anchor="middle" x="440.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2132.1938" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2132.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2097.1562,-177.5376C2067.7481,-165.9624 2024.3792,-150.194 1985.1938,-141 1914.367,-124.3821 1831.6119,-114.9659 1774.1455,-109.9674"/>
<polygon fill="#000000" stroke="#000000" points="1774.3358,-106.4711 1764.076,-109.1142 1773.7448,-113.4461 1774.3358,-106.4711"/>
<text text-anchor="middle" x="2081.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="818.1938" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="818.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M817.9342,-260.8963C818.6497,-250.3603 821.1178,-237.3549 828.1938,-228 834.8961,-219.139 844.3905,-212.2932 854.2625,-207.0706"/>
<polygon fill="#000000" stroke="#000000" points="855.8525,-210.1899 863.3654,-202.7195 852.8337,-203.8743 855.8525,-210.1899"/>
<text text-anchor="middle" x="889.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2256.1938" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2256.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2227.4778,-177.2253C2202.8728,-165.2972 2166.1343,-149.1966 2132.1938,-141 2066.4529,-125.1237 1879.2685,-113.7033 1775.1981,-108.3729"/>
<polygon fill="#000000" stroke="#000000" points="1775.2499,-104.8712 1765.0856,-107.8608 1774.8958,-111.8622 1775.2499,-104.8712"/>
<text text-anchor="middle" x="2216.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1028.1938" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1028.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1000.9734,-261.3665C992.0878,-255.5615 982.1934,-249.0453 973.1938,-243 958.9567,-233.4366 943.3026,-222.683 930.0733,-213.5246"/>
<polygon fill="#000000" stroke="#000000" points="931.9809,-210.5883 921.7691,-207.7651 927.9915,-216.3403 931.9809,-210.5883"/>
<text text-anchor="middle" x="1064.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node13" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2396.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2396.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2362.1022,-176.0052C2335.0934,-164.1287 2296.0653,-148.7079 2260.1938,-141 2169.796,-121.5758 1904.6578,-111.1063 1775.5273,-107.0347"/>
<polygon fill="#000000" stroke="#000000" points="1775.4457,-103.5306 1765.3417,-106.7179 1775.228,-110.5272 1775.4457,-103.5306"/>
<text text-anchor="middle" x="2368.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node14" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1251.1938" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1251.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1215.9798,-262.3945C1204.1378,-256.5469 1190.9528,-249.7449 1179.1938,-243 1168.6076,-236.9279 1167.6218,-232.2825 1156.1938,-228 1137.5339,-221.0075 1021.9221,-206.4863 952.2745,-198.1819"/>
<polygon fill="#000000" stroke="#000000" points="952.2741,-194.6574 941.9312,-196.954 951.4488,-201.6085 952.2741,-194.6574"/>
<text text-anchor="middle" x="1250.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="704.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="704.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M641.4236,-177.3153C583.5183,-160.7102 511.0233,-130.2381 543.1938,-87 565.3067,-57.2796 667.562,-35.5705 728.0308,-25.0728"/>
<polygon fill="#000000" stroke="#000000" points="728.8103,-28.4905 738.0822,-23.364 727.6371,-21.5896 728.8103,-28.4905"/>
<text text-anchor="middle" x="629.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M780.5225,-179.0565C802.7107,-173.647 826.522,-166.1764 847.1938,-156 856.8464,-151.2482 856.1081,-144.7461 866.1938,-141 884.0136,-134.3812 1431.2071,-114.5546 1631.0441,-107.5143"/>
<polygon fill="#000000" stroke="#000000" points="1631.2774,-111.0083 1641.1481,-107.1588 1631.0312,-104.0127 1631.2774,-111.0083"/>
<text text-anchor="middle" x="952.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M526.7896,-268.1132C556.5319,-253.862 606.1217,-230.4009 615.1938,-228 704.4676,-204.374 730.9997,-224.5476 822.1938,-210 831.8532,-208.4591 842.1003,-206.3816 851.8599,-204.1856"/>
<polygon fill="#000000" stroke="#000000" points="852.8616,-207.5461 861.8087,-201.8717 851.2758,-200.7281 852.8616,-207.5461"/>
<text text-anchor="middle" x="639.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M499.4264,-261.1838C498.1035,-255.4252 496.8505,-248.9824 496.1938,-243 495.4663,-236.3731 495.8125,-234.6558 496.1938,-228 500.9514,-144.9443 491.3412,-92.2973 565.1938,-54 592.7204,-39.7257 674.7388,-28.5926 727.1823,-22.685"/>
<polygon fill="#000000" stroke="#000000" points="727.696,-26.1496 737.2517,-21.5738 726.9281,-19.1919 727.696,-26.1496"/>
<text text-anchor="middle" x="526.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1971.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1971.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1919.307,-276.8484C1797.4833,-271.5848 1500.1782,-257.4315 1457.1938,-243 1445.6244,-239.1157 1445.8034,-231.7623 1434.1938,-228 1356.306,-202.7591 1147.8196,-216.3898 1066.1938,-210 1027.8936,-207.0018 984.7865,-202.3225 951.963,-198.4863"/>
<polygon fill="#000000" stroke="#000000" points="952.0278,-194.9698 941.6865,-197.2737 951.2074,-201.9216 952.0278,-194.9698"/>
<text text-anchor="middle" x="1499.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2023.2816,-278.5582C2194.3318,-276.5731 2730.8439,-265.9043 2782.1938,-210 2793.0173,-198.2165 2792.3726,-186.3447 2782.1938,-174 2717.5815,-95.6393 1116.6113,-31.0607 820.1725,-19.7549"/>
<polygon fill="#000000" stroke="#000000" points="819.9112,-16.2425 809.7855,-19.3602 819.6453,-23.2375 819.9112,-16.2425"/>
<text text-anchor="middle" x="2776.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1972.0015,-260.8246C1973.0776,-227.3203 1973.2548,-157.7115 1957.1938,-141 1944.582,-127.8774 1844.5184,-116.8354 1773.8242,-110.5672"/>
<polygon fill="#000000" stroke="#000000" points="1773.8873,-107.0595 1763.6209,-109.6773 1773.279,-114.033 1773.8873,-107.0595"/>
<text text-anchor="middle" x="2013.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node19" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2567.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2567.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2532.8556,-175.7299C2505.8747,-163.7881 2466.9991,-148.4107 2431.1938,-141 2307.5897,-115.4174 1934.5349,-107.8449 1775.8731,-105.7483"/>
<polygon fill="#000000" stroke="#000000" points="1775.7815,-102.247 1765.7373,-105.618 1775.6914,-109.2464 1775.7815,-102.247"/>
<text text-anchor="middle" x="2544.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="927.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="927.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M906.029,-87.3142C892.8131,-76.7998 875.1423,-63.6718 858.1938,-54 843.693,-45.725 826.9176,-38.2231 812.1204,-32.2355"/>
<polygon fill="#000000" stroke="#000000" points="813.3126,-28.9433 802.726,-28.5265 810.7421,-35.4543 813.3126,-28.9433"/>
<text text-anchor="middle" x="949.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node21" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1092.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1092.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1074.1318,-87.7091C1061.0428,-76.227 1042.3465,-61.8675 1023.1938,-54 987.2468,-39.2338 881.2337,-27.6575 819.4094,-21.9324"/>
<polygon fill="#000000" stroke="#000000" points="819.4215,-18.4191 809.1454,-20.998 818.7869,-25.3903 819.4215,-18.4191"/>
<text text-anchor="middle" x="1098.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M734.1382,-116.0498C713.1063,-122.874 690.2502,-132.0171 684.1938,-141 680.4669,-146.5277 679.7951,-150.9904 684.1938,-156 704.5989,-179.2395 791.7652,-168.4732 822.1938,-174 831.7176,-175.7298 841.8363,-177.8722 851.4997,-180.0687"/>
<polygon fill="#000000" stroke="#000000" points="850.8282,-183.5059 861.3611,-182.3622 852.4139,-176.6878 850.8282,-183.5059"/>
<text text-anchor="middle" x="724.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M773.1938,-86.9735C773.1938,-75.1918 773.1938,-59.5607 773.1938,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="776.6939,-46.0033 773.1938,-36.0034 769.6939,-46.0034 776.6939,-46.0033"/>
<text text-anchor="middle" x="813.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge32" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1643.6033,-99.4254C1470.9734,-83.2762 973.0524,-36.6965 819.1034,-22.2948"/>
<polygon fill="#000000" stroke="#000000" points="819.327,-18.8005 809.0444,-21.3538 818.6749,-25.7701 819.327,-18.8005"/>
<text text-anchor="middle" x="1344.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node24" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1248.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1248.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1273.2734,-176.0588C1293.084,-164.2937 1321.8556,-148.9938 1349.1938,-141 1400.4534,-126.0115 1543.9564,-114.8474 1631.7159,-109.179"/>
<polygon fill="#000000" stroke="#000000" points="1632.1118,-112.661 1641.8688,-108.5317 1631.6664,-105.6752 1632.1118,-112.661"/>
<text text-anchor="middle" x="1392.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- generic_file -->
<g id="node25" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2683.1938" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2683.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2618.2338,-275.9399C2444.0106,-267.7666 1951.8059,-244.8989 1542.1938,-228 1330.6669,-219.2733 1277.3431,-225.3529 1066.1938,-210 1027.8776,-207.214 984.7709,-202.5285 951.9516,-198.6363"/>
<polygon fill="#000000" stroke="#000000" points="952.0223,-195.1198 941.6766,-197.4039 951.1886,-202.07 952.0223,-195.1198"/>
<text text-anchor="middle" x="1940.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2719.2348,-263.9073C2773.4172,-239.1825 2865.2641,-188.0796 2823.1938,-141 2772.5112,-84.2827 1794.0341,-56.872 1731.1938,-54 1381.1836,-38.0035 958.999,-23.9717 820.0261,-19.4906"/>
<polygon fill="#000000" stroke="#000000" points="819.8549,-15.9833 809.7475,-19.1599 819.6297,-22.9797 819.8549,-15.9833"/>
<text text-anchor="middle" x="2884.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2682.1586,-260.8083C2680.1231,-238.6153 2674.0872,-200.7537 2656.1938,-174 2642.6041,-153.6812 2635.2263,-149.1874 2612.1938,-141 2534.4419,-113.3613 1977.8236,-106.8568 1776.0241,-105.4"/>
<polygon fill="#000000" stroke="#000000" points="1775.8486,-101.8988 1765.8243,-105.3285 1775.7994,-108.8986 1775.8486,-101.8988"/>
<text text-anchor="middle" x="2725.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- diagnosis -->
<g id="node26" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1549.1938" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1549.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1495.6162,-275.4592C1453.5125,-271.2907 1394.0274,-262.2949 1345.1938,-243 1333.8436,-238.5154 1333.7626,-231.8859 1322.1938,-228 1268.1326,-209.8414 1122.9985,-215.0566 1066.1938,-210 1027.9278,-206.5937 984.8196,-201.9263 951.9871,-198.1979"/>
<polygon fill="#000000" stroke="#000000" points="952.0402,-194.6812 941.7074,-197.0231 951.2453,-201.636 952.0402,-194.6812"/>
<text text-anchor="middle" x="1389.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1601.4888,-273.5681C1645.0357,-267.1149 1696.1969,-253.7995 1671.1938,-228 1626.7866,-182.1785 1141.6009,-255.8215 1097.1938,-210 1086.0588,-198.5104 1086.7952,-186.1602 1097.1938,-174 1114.4494,-153.821 1476.7425,-122.9001 1632.7514,-110.4613"/>
<polygon fill="#000000" stroke="#000000" points="1633.0319,-113.9501 1642.7232,-109.669 1632.4774,-106.9721 1633.0319,-113.9501"/>
<text text-anchor="middle" x="1141.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
