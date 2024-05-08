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
<svg width="2068pt" height="305pt"
 viewBox="0.00 0.00 2067.79 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2063.7947,-301 2063.7947,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1102.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1102.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5852,-87.0514C52.5828,-76.0306 52.4664,-62.4535 60.7947,-54 78.501,-36.0274 856.1016,-22.0485 1056.2234,-18.7441"/>
<polygon fill="#000000" stroke="#000000" points="1056.462,-22.2407 1066.4032,-18.577 1056.3471,-15.2416 1056.462,-22.2407"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1521.7947" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1521.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge24" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1549.7352,-277.2388C1650.1677,-270.6282 1988.5869,-245.8299 2019.7947,-210 2030.3034,-197.9349 2024.891,-189.1667 2019.7947,-174 2013.9339,-156.5581 2011.1808,-149.3705 1994.7947,-141 1914.132,-99.7952 1255.8861,-172.1366 1179.7947,-123 1151.2379,-104.5592 1167.7863,-80.7377 1146.7947,-54 1142.7149,-48.8035 1137.7605,-43.8632 1132.6676,-39.4004"/>
<polygon fill="#000000" stroke="#000000" points="1134.6034,-36.4608 1124.6565,-32.8124 1130.1571,-41.8674 1134.6034,-36.4608"/>
<text text-anchor="middle" x="2035.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node21" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="725.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="725.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1499.7868,-267.7348C1474.3145,-255.3432 1430.7371,-236.1115 1390.7947,-228 1257.6753,-200.9661 913.5424,-233.7307 779.7947,-210 775.857,-209.3013 771.8149,-208.3738 767.7996,-207.3071"/>
<polygon fill="#000000" stroke="#000000" points="768.5299,-203.874 757.9492,-204.4203 766.5612,-210.5915 768.5299,-203.874"/>
<text text-anchor="middle" x="1462.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="703.7947" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="703.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M746.4947,-95.6895C822.9733,-79.0137 982.5026,-44.2291 1059.4472,-27.4517"/>
<polygon fill="#000000" stroke="#000000" points="1060.272,-30.8542 1069.2968,-25.3041 1058.7807,-24.0149 1060.272,-30.8542"/>
<text text-anchor="middle" x="967.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M701.9495,-123.2625C701.4976,-133.1319 701.825,-145.4279 704.7947,-156 705.6948,-159.2044 706.9495,-162.4195 708.4022,-165.5381"/>
<polygon fill="#000000" stroke="#000000" points="705.3928,-167.3327 713.1982,-174.4969 711.5642,-164.0289 705.3928,-167.3327"/>
<text text-anchor="middle" x="745.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1275.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1275.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1242.6039,-88.1989C1222.9062,-78.2383 1197.437,-65.3771 1174.7947,-54 1162.6749,-47.9101 1149.3961,-41.2635 1137.5791,-35.3575"/>
<polygon fill="#000000" stroke="#000000" points="1138.9756,-32.1428 1128.4656,-30.8047 1135.8472,-38.4049 1138.9756,-32.1428"/>
<text text-anchor="middle" x="1271.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="722.7947" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="722.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M723.4163,-260.9735C723.8226,-249.1918 724.3616,-233.5607 724.8237,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="728.3271,-220.1181 725.1739,-210.0034 721.3312,-219.8768 728.3271,-220.1181"/>
<text text-anchor="middle" x="816.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="861.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="861.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1044.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1044.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M876.6486,-174.0851C886.6619,-163.0779 900.752,-149.5031 915.7947,-141 935.6298,-129.7878 959.1812,-121.8845 980.6976,-116.3997"/>
<polygon fill="#000000" stroke="#000000" points="981.5236,-119.8009 990.4196,-114.0467 979.8769,-112.9974 981.5236,-119.8009"/>
<text text-anchor="middle" x="974.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="534.7947" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="534.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M562.3755,-263.381C581.5552,-252.7979 607.8734,-238.8235 631.7947,-228 648.0121,-220.6622 666.2057,-213.4643 682.2354,-207.4567"/>
<polygon fill="#000000" stroke="#000000" points="683.7365,-210.6332 691.8996,-203.8793 681.3064,-204.0685 683.7365,-210.6332"/>
<text text-anchor="middle" x="676.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M549.1514,-261.3779C553.2918,-255.7368 557.5596,-249.3121 560.7947,-243 583.0047,-199.6655 560.2784,-168.0109 600.7947,-141 608.452,-135.8952 850.3175,-118.4703 973.7755,-109.8749"/>
<polygon fill="#000000" stroke="#000000" points="974.1658,-113.3563 983.8991,-109.1714 973.6805,-106.3732 974.1658,-113.3563"/>
<text text-anchor="middle" x="621.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1593.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1593.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1567.743,-174.6729C1548.4731,-162.8551 1521.1135,-148.1054 1494.7947,-141 1420.0345,-120.8168 1223.736,-131.7452 1146.7947,-123 1133.5536,-121.495 1119.4308,-119.3529 1106.0465,-117.0687"/>
<polygon fill="#000000" stroke="#000000" points="1106.4366,-113.5837 1095.9821,-115.3024 1105.2266,-120.4784 1106.4366,-113.5837"/>
<text text-anchor="middle" x="1599.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1796.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1796.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1764.129,-174.9362C1739.4859,-163 1704.4545,-147.9895 1671.7947,-141 1557.6442,-116.5709 1262.8934,-135.1734 1146.7947,-123 1133.4698,-121.6028 1119.261,-119.4942 1105.8116,-117.2066"/>
<polygon fill="#000000" stroke="#000000" points="1106.1566,-113.7137 1095.7019,-115.4312 1104.9458,-120.6082 1106.1566,-113.7137"/>
<text text-anchor="middle" x="1797.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1962.7947" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1962.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1943.051,-175.4768C1927.2992,-163.399 1904.0856,-147.962 1880.7947,-141 1802.6319,-117.636 1227.9705,-131.1116 1146.7947,-123 1133.4631,-121.6678 1119.2516,-119.5864 1105.8015,-117.3046"/>
<polygon fill="#000000" stroke="#000000" points="1106.1464,-113.8117 1095.6918,-115.5298 1104.936,-120.7063 1106.1464,-113.8117"/>
<text text-anchor="middle" x="1951.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="308.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="308.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M299.3619,-173.9365C295.2912,-163.4148 292.8621,-150.4103 299.7947,-141 347.8214,-75.8089 394.5198,-103.4904 473.7947,-87 688.5196,-42.3339 950.8787,-25.3699 1055.9853,-20.0656"/>
<polygon fill="#000000" stroke="#000000" points="1056.4342,-23.5478 1066.2497,-19.5597 1056.0895,-16.5563 1056.4342,-23.5478"/>
<text text-anchor="middle" x="559.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M303.5123,-173.5714C301.6025,-162.6474 301.6127,-149.3489 309.7947,-141 327.3847,-123.0511 736.6972,-124.2977 761.7947,-123 834.1487,-119.2588 916.8371,-113.8706 974.0679,-109.9653"/>
<polygon fill="#000000" stroke="#000000" points="974.3561,-113.4539 984.0935,-109.2786 973.8776,-106.4702 974.3561,-113.4539"/>
<text text-anchor="middle" x="395.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="939.7947" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="939.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M934.5683,-261.0163C930.3107,-249.6878 923.116,-235.7805 911.7947,-228 862.9978,-194.4644 837.4634,-223.42 779.7947,-210 776.1643,-209.1552 772.4314,-208.1685 768.7051,-207.1002"/>
<polygon fill="#000000" stroke="#000000" points="769.5173,-203.6889 758.9314,-204.1229 767.4774,-210.3851 769.5173,-203.6889"/>
<text text-anchor="middle" x="991.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="409.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="409.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M363.0939,-270.905C305.1066,-259.7921 211.3049,-237.9662 190.7947,-210 172.1774,-184.6148 184.7552,-163.4783 206.7947,-141 243.8106,-103.2471 262.2602,-102.5474 312.7947,-87 453.1853,-43.8077 908.3871,-24.6808 1056.0676,-19.5092"/>
<polygon fill="#000000" stroke="#000000" points="1056.2873,-23.0038 1066.1606,-19.1608 1056.0457,-16.008 1056.2873,-23.0038"/>
<text text-anchor="middle" x="249.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M435.7189,-263.1921C456.1716,-251.4987 485.8212,-236.2302 513.7947,-228 579.9032,-208.5499 600.3787,-224.2732 667.7947,-210 672.5104,-209.0016 677.3916,-207.7857 682.2288,-206.4619"/>
<polygon fill="#000000" stroke="#000000" points="683.3947,-209.7682 692.0288,-203.628 681.4501,-203.0437 683.3947,-209.7682"/>
<text text-anchor="middle" x="556.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M417.7631,-261.123C429.0203,-237.8293 451.7247,-197.3287 482.7947,-174 519.5467,-146.405 535.7624,-150.181 580.7947,-141 618.1523,-133.3837 852.658,-117.4284 973.2892,-109.5711"/>
<polygon fill="#000000" stroke="#000000" points="973.787,-113.0462 983.539,-108.9051 973.333,-106.0609 973.787,-113.0462"/>
<text text-anchor="middle" x="525.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cytogenomic_file -->
<g id="node15" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1130.7947" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1130.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1112.9187,-261.2296C1099.915,-249.5276 1081.2442,-235.1024 1061.7947,-228 1002.8102,-206.4606 841.4261,-222.0286 779.7947,-210 775.9226,-209.2443 771.945,-208.2865 767.9889,-207.2081"/>
<polygon fill="#000000" stroke="#000000" points="768.8543,-203.8142 758.2718,-204.3254 766.8633,-210.5251 768.8543,-203.8142"/>
<text text-anchor="middle" x="1159.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1032.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1032.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1035.2811,-173.9735C1036.9062,-162.1918 1039.0622,-146.5607 1040.9108,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1044.4122,-133.3878 1042.3115,-123.0034 1037.4778,-132.4313 1044.4122,-133.3878"/>
<text text-anchor="middle" x="1102.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pathology_file -->
<g id="node17" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1314.7947" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1314.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1294.2845,-261.5739C1278.9752,-249.7081 1256.9573,-234.9417 1234.7947,-228 1138.2304,-197.7543 879.3383,-228.1803 779.7947,-210 775.8606,-209.2815 771.8209,-208.3403 767.8072,-207.2649"/>
<polygon fill="#000000" stroke="#000000" points="768.5405,-203.8323 757.9591,-204.3653 766.5634,-210.5473 768.5405,-203.8323"/>
<text text-anchor="middle" x="1325.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1457.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1457.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1427.0247,-88.3085C1404.7901,-76.952 1373.7053,-62.4958 1344.7947,-54 1278.4031,-34.4899 1198.5078,-25.2323 1149.1825,-21.0793"/>
<polygon fill="#000000" stroke="#000000" points="1149.3861,-17.5845 1139.1369,-20.2688 1148.823,-24.5618 1149.3861,-17.5845"/>
<text text-anchor="middle" x="1444.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node19" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1615.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1615.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1588.8062,-88.4815C1568.214,-76.7394 1538.7241,-61.7321 1510.7947,-54 1443.8172,-35.4576 1241.2574,-24.2431 1149.2085,-19.9764"/>
<polygon fill="#000000" stroke="#000000" points="1149.2216,-16.4734 1139.0724,-19.514 1148.9025,-23.4662 1149.2216,-16.4734"/>
<text text-anchor="middle" x="1599.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1183.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1183.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1183.5154,-173.7834C1182.3936,-162.9391 1179.2,-149.6501 1170.7947,-141 1161.5106,-131.4455 1134.35,-123.0985 1107.6125,-116.8538"/>
<polygon fill="#000000" stroke="#000000" points="1108.3393,-113.4299 1097.8149,-114.65 1106.803,-120.2593 1108.3393,-113.4299"/>
<text text-anchor="middle" x="1222.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M757.9449,-204.4446C765.0406,-206.7023 772.5916,-208.7385 779.7947,-210 819.2073,-216.9024 1466.642,-205.5969 1499.7947,-228 1507.7475,-233.3742 1512.8419,-242.2795 1516.0984,-251.1576"/>
<polygon fill="#000000" stroke="#000000" points="1512.8198,-252.4093 1519.0485,-260.9798 1519.5239,-250.3957 1512.8198,-252.4093"/>
<text text-anchor="middle" x="1548.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M690.5306,-181.0263C683.0279,-178.6999 675.1508,-176.2636 667.7947,-174 641.5918,-165.937 625.1085,-178.0333 608.7947,-156 593.933,-135.928 620.3652,-122.9254 649.0861,-115.0754"/>
<polygon fill="#000000" stroke="#000000" points="650.0189,-118.4498 658.8577,-112.6079 648.3051,-111.6628 650.0189,-118.4498"/>
<text text-anchor="middle" x="645.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M750.9046,-177.1236C773.7678,-163.8121 805.9963,-145.6936 819.7947,-141 869.7593,-124.0041 928.753,-114.9455 973.7956,-110.1673"/>
<polygon fill="#000000" stroke="#000000" points="974.1707,-113.6473 983.766,-109.155 973.4636,-106.6831 974.1707,-113.6473"/>
<text text-anchor="middle" x="856.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1041.1181,-86.905C1039.9759,-76.6233 1040.2259,-63.8733 1045.7947,-54 1050.2581,-46.0865 1057.2555,-39.6621 1064.8397,-34.5514"/>
<polygon fill="#000000" stroke="#000000" points="1067.1038,-37.276 1073.8959,-29.1448 1063.5156,-31.2657 1067.1038,-37.276"/>
<text text-anchor="middle" x="1096.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1766.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1766.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1737.9134,-88.3146C1715.9005,-76.4874 1684.4259,-61.4467 1654.7947,-54 1559.6189,-30.0812 1264.6069,-21.4088 1149.4821,-18.8836"/>
<polygon fill="#000000" stroke="#000000" points="1149.31,-15.3792 1139.2375,-18.6648 1149.1604,-22.3776 1149.31,-15.3792"/>
<text text-anchor="middle" x="1752.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- therapeutic_procedure -->
<g id="node24" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1372.7947" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1372.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1343.6334,-174.4648C1323.5537,-163.1781 1295.8901,-149.1447 1269.7947,-141 1217.0549,-124.5392 1201.338,-131.8017 1146.7947,-123 1134.1878,-120.9656 1120.7261,-118.6748 1107.8539,-116.4263"/>
<polygon fill="#000000" stroke="#000000" points="1108.1398,-112.9229 1097.6847,-114.6379 1106.9273,-119.8171 1108.1398,-112.9229"/>
<text text-anchor="middle" x="1397.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
