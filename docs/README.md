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
<svg width="2573pt" height="392pt"
 viewBox="0.00 0.00 2573.43 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2569.4333,-388 2569.4333,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1222.4333" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1222.4333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1109.4333" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1109.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1204.2779,-265.0219C1186.512,-251.3438 1159.1691,-230.2922 1138.398,-214.3003"/>
<polygon fill="#000000" stroke="#000000" points="1140.288,-211.3382 1130.2291,-208.011 1136.0176,-216.8848 1140.288,-211.3382"/>
<text text-anchor="middle" x="1196.4333" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="999.4333" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="999.4333" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1250.6569,-278.1686C1369.918,-274.3704 1828.3555,-256.7962 1870.4333,-210 1881.1312,-198.1024 1876.3246,-188.8759 1870.4333,-174 1805.3941,-9.772 1857.212,-118.0446 1417.4333,-54 1283.5396,-34.5012 1123.8653,-24.3447 1046.3264,-20.2394"/>
<polygon fill="#000000" stroke="#000000" points="1046.1098,-16.7235 1035.9417,-19.6999 1045.7466,-23.7141 1046.1098,-16.7235"/>
<text text-anchor="middle" x="1885.4333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1380.4333" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1380.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="919.4333" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="919.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1353.207,-174.7699C1333.0996,-162.999 1304.614,-148.2655 1277.4333,-141 1153.962,-107.9958 1116.6981,-142.7892 990.4333,-123 985.094,-122.1632 979.5707,-121.1081 974.0716,-119.9303"/>
<polygon fill="#000000" stroke="#000000" points="974.7712,-116.5002 964.2444,-117.6984 973.2208,-123.3263 974.7712,-116.5002"/>
<text text-anchor="middle" x="1383.4333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="121.4333" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="121.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M126.6858,-86.8982C131.055,-75.3655 138.523,-61.2707 150.4333,-54 184.8693,-32.9784 780.5233,-21.5944 952.9975,-18.7286"/>
<polygon fill="#000000" stroke="#000000" points="953.0884,-22.2276 963.0294,-18.5636 952.9732,-15.2286 953.0884,-22.2276"/>
<text text-anchor="middle" x="219.9333" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1583.4333" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1583.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1549.9262,-174.9837C1524.6628,-163.0714 1488.7797,-148.0701 1455.4333,-141 1253.1092,-98.1036 1195.1292,-152.5751 990.4333,-123 985.0057,-122.2158 979.3919,-121.185 973.8087,-120.013"/>
<polygon fill="#000000" stroke="#000000" points="974.3627,-116.5503 963.8388,-117.7735 972.8286,-123.3801 974.3627,-116.5503"/>
<text text-anchor="middle" x="1581.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1100.1737,-174.2767C1093.4076,-163.0582 1083.1986,-149.1756 1070.4333,-141 1039.7434,-121.3447 1025.8777,-131.4788 990.4333,-123 985.7336,-121.8758 980.8648,-120.6887 975.9806,-119.4822"/>
<polygon fill="#000000" stroke="#000000" points="976.5321,-116.0127 965.9827,-116.9924 974.8405,-122.8053 976.5321,-116.0127"/>
<text text-anchor="middle" x="1121.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- molecular_test -->
<g id="node6" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1781.4333" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1781.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1752.0021,-175.2339C1729.1848,-163.1977 1696.3457,-147.9269 1665.4333,-141 1519.011,-108.1896 1139.0709,-143.5637 990.4333,-123 984.9223,-122.2376 979.2214,-121.21 973.5563,-120.0303"/>
<polygon fill="#000000" stroke="#000000" points="973.9699,-116.5363 963.4467,-117.7666 972.4403,-123.3671 973.9699,-116.5363"/>
<text text-anchor="middle" x="1771.4333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="567.4333" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="567.4333" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M590.3331,-348.28C607.0793,-336.4387 630.8916,-321.8259 654.4333,-315 766.764,-282.4297 1066.2834,-322.4721 1180.4333,-297 1183.8666,-296.2339 1187.3708,-295.193 1190.8181,-293.9957"/>
<polygon fill="#000000" stroke="#000000" points="1192.2335,-297.2005 1200.2773,-290.305 1189.6891,-290.6793 1192.2335,-297.2005"/>
<text text-anchor="middle" x="745.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M564.9769,-347.9264C562.8918,-324.4149 563.2624,-283.674 586.4333,-261 661.5208,-187.5225 953.4283,-230.6655 1056.4333,-210 1060.0776,-209.2688 1063.8161,-208.3543 1067.5393,-207.3276"/>
<polygon fill="#000000" stroke="#000000" points="1068.7158,-210.6287 1077.2838,-204.3964 1066.6994,-203.9254 1068.7158,-210.6287"/>
<text text-anchor="middle" x="677.9333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2040.4333" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2040.4333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M647.6507,-352.9508C662.1872,-350.9869 677.2367,-349.2152 691.4333,-348 766.2972,-341.592 1296.7856,-355.5849 1367.4333,-330 1377.5492,-326.3365 1376.3244,-318.6828 1386.4333,-315 1448.1616,-292.5116 1912.5174,-307.1017 1977.4333,-297 1982.8425,-296.1583 1988.4443,-294.9969 1993.9753,-293.6658"/>
<polygon fill="#000000" stroke="#000000" points="1994.996,-297.0169 2003.7974,-291.1189 1993.239,-290.241 1994.996,-297.0169"/>
<text text-anchor="middle" x="1477.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="303.4333" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="303.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M295.3575,-86.6877C291.9272,-75.8075 290.3451,-62.5142 298.4333,-54 320.9701,-30.2761 799.2722,-21.0182 952.5893,-18.6534"/>
<polygon fill="#000000" stroke="#000000" points="952.6876,-22.1524 962.6334,-18.5012 952.5815,-15.1532 952.6876,-22.1524"/>
<text text-anchor="middle" x="360.4333" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="143.4333" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="143.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge35" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M143.4533,-173.8788C144.5041,-162.6427 147.8747,-148.8916 157.4333,-141 177.3714,-124.539 363.7764,-126.1965 389.4333,-123 602.8823,-96.4076 855.4737,-47.2068 955.501,-27.0104"/>
<polygon fill="#000000" stroke="#000000" points="956.4327,-30.3928 965.539,-24.9774 955.0432,-23.5321 956.4327,-30.3928"/>
<text text-anchor="middle" x="709.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M149.0322,-173.8805C153.6239,-162.3401 161.3672,-148.2434 173.4333,-141 214.0518,-116.6161 552.115,-125.3304 599.4333,-123 684.8944,-118.7911 783.1467,-113.1439 847.9879,-109.305"/>
<polygon fill="#000000" stroke="#000000" points="848.3255,-112.7912 858.1005,-108.7049 847.9107,-105.8035 848.3255,-112.7912"/>
<text text-anchor="middle" x="302.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node10" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="838.4333" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="838.4333" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M838.394,-347.806C839.4204,-336.5401 842.7861,-322.783 852.4333,-315 880.8404,-292.082 1144.8939,-305.3159 1180.4333,-297 1183.8586,-296.1985 1187.3574,-295.1346 1190.8015,-293.9232"/>
<polygon fill="#000000" stroke="#000000" points="1192.2253,-297.1244 1200.2566,-290.2143 1189.669,-290.6079 1192.2253,-297.1244"/>
<text text-anchor="middle" x="960.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M815.9631,-348.0132C791.1854,-326.0268 757.6546,-288.3734 780.4333,-261 860.2248,-165.1136 935.7257,-241.4733 1056.4333,-210 1059.7787,-209.1277 1063.218,-208.1502 1066.6604,-207.1136"/>
<polygon fill="#000000" stroke="#000000" points="1067.8111,-210.4207 1076.2946,-204.0739 1065.7049,-203.745 1067.8111,-210.4207"/>
<text text-anchor="middle" x="888.9333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M933.7271,-352.9686C950.5926,-351.0288 968.0088,-349.2607 984.4333,-348 1049.7162,-342.9889 1511.9148,-352.4156 1573.4333,-330 1583.542,-326.3167 1582.3546,-318.7649 1592.4333,-315 1672.6669,-285.0282 1892.9127,-310.8576 1977.4333,-297 1982.7653,-296.1258 1988.2876,-294.9563 1993.7459,-293.6312"/>
<polygon fill="#000000" stroke="#000000" points="1994.65,-297.0126 2003.4471,-291.1081 1992.888,-290.2379 1994.65,-297.0126"/>
<text text-anchor="middle" x="1700.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- follow_up -->
<g id="node11" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="325.4333" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="325.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M368.8871,-180.8021C389.8091,-174.689 414.955,-166.2631 436.4333,-156 447.4447,-150.7383 447.8799,-144.9316 459.4333,-141 495.1254,-128.8542 727.0969,-115.1031 847.3563,-108.6764"/>
<polygon fill="#000000" stroke="#000000" points="847.7789,-112.159 857.5792,-108.1334 847.4075,-105.1689 847.7789,-112.159"/>
<text text-anchor="middle" x="504.4333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="416.4333" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="416.4333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M423.259,-261.0209C428.7134,-249.3844 437.5901,-235.1207 450.4333,-228 509.3471,-195.336 990.1411,-221.9637 1056.4333,-210 1060.1419,-209.3307 1063.9433,-208.4511 1067.7241,-207.4403"/>
<polygon fill="#000000" stroke="#000000" points="1069.0126,-210.709 1077.6063,-204.5124 1067.024,-203.9974 1069.0126,-210.709"/>
<text text-anchor="middle" x="492.9333" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M364.4425,-277.7654C268.1913,-274.2646 68.1314,-260.8929 25.4333,-210 -9.7029,-168.1205 -7.0299,-130.984 25.4333,-87 54.9861,-46.9591 83.3875,-62.4355 132.4333,-54 292.264,-26.5101 796.5031,-19.796 952.7843,-18.3559"/>
<polygon fill="#000000" stroke="#000000" points="953.0291,-21.854 962.9975,-18.2648 952.9666,-14.8543 953.0291,-21.854"/>
<text text-anchor="middle" x="43.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M411.8892,-260.7114C407.2835,-237.345 403.5922,-197.1611 425.4333,-174 444.5364,-153.7422 521.9251,-160.3141 549.4333,-156 589.0623,-149.785 598.7536,-146.8832 638.4333,-141 711.0636,-130.2313 794.5433,-119.7798 851.5197,-112.9376"/>
<polygon fill="#000000" stroke="#000000" points="851.9745,-116.4083 861.4878,-111.7449 851.1428,-109.4578 851.9745,-116.4083"/>
<text text-anchor="middle" x="467.9333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1062.4333" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1062.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge27" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1053.4982,-86.8841C1048.2104,-76.8332 1041.0659,-64.3174 1033.4333,-54 1030.3176,-49.7885 1026.7588,-45.5422 1023.1443,-41.5162"/>
<polygon fill="#000000" stroke="#000000" points="1025.6114,-39.03 1016.2267,-34.1129 1020.4967,-43.8092 1025.6114,-39.03"/>
<text text-anchor="middle" x="1093.4333" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node14" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1083.4333" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1083.4333" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1076.2288,-348.0209C1073.2046,-337.266 1071.9058,-323.9875 1079.4333,-315 1108.7099,-280.0444 1136.7492,-310.0658 1180.4333,-297 1183.6254,-296.0452 1186.9007,-294.9192 1190.1458,-293.7039"/>
<polygon fill="#000000" stroke="#000000" points="1191.7049,-296.8494 1199.6776,-289.8718 1189.0938,-290.3546 1191.7049,-296.8494"/>
<text text-anchor="middle" x="1150.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1018.6875,-353.5353C1007.6128,-351.5675 996.2068,-349.643 985.4333,-348 918.8105,-337.8398 792.4538,-365.1864 837.4333,-315 861.9031,-287.6975 968.267,-312.6268 1001.4333,-297 1011.6397,-292.191 1057.1664,-246.148 1085.7538,-216.6509"/>
<polygon fill="#000000" stroke="#000000" points="1088.541,-218.8033 1092.9746,-209.1807 1083.508,-213.9383 1088.541,-218.8033"/>
<text text-anchor="middle" x="1111.9333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1172.6746,-364.1249C1339.5042,-360.2009 1692.6765,-349.8026 1813.4333,-330 1837.5914,-326.0384 1842.5334,-320.3014 1866.4333,-315 1915.2251,-304.1771 1928.655,-307.8838 1977.4333,-297 1982.372,-295.898 1987.4966,-294.6355 1992.5934,-293.3016"/>
<polygon fill="#000000" stroke="#000000" points="1993.5671,-296.664 2002.3044,-290.6716 1991.7371,-289.9074 1993.5671,-296.664"/>
<text text-anchor="middle" x="1937.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="637.4333" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="637.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M637.6293,-173.8078C638.7673,-162.69 642.1689,-149.0961 651.4333,-141 666.0984,-128.1841 774.3624,-116.8564 848.7174,-110.4727"/>
<polygon fill="#000000" stroke="#000000" points="849.3016,-113.9358 858.9709,-109.6051 848.7114,-106.9607 849.3016,-113.9358"/>
<text text-anchor="middle" x="744.4333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="846.4333" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="846.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M841.9447,-173.7182C840.4485,-163.3743 840.4485,-150.6243 846.4333,-141 851.0994,-133.4962 857.8415,-127.5103 865.367,-122.7485"/>
<polygon fill="#000000" stroke="#000000" points="867.4289,-125.6077 874.4837,-117.7032 864.0394,-119.483 867.4289,-125.6077"/>
<text text-anchor="middle" x="905.4333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1213.4333" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1213.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1195.5483,-87.4943C1183.2362,-76.3677 1165.9886,-62.5057 1148.4333,-54 1115.6198,-38.1016 1075.2503,-28.909 1044.8118,-23.7983"/>
<polygon fill="#000000" stroke="#000000" points="1045.3215,-20.3354 1034.8952,-22.2178 1044.2197,-27.2482 1045.3215,-20.3354"/>
<text text-anchor="middle" x="1227.9333" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="992.4333" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="992.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M986.4021,-173.7541C982.3918,-163.4222 976.3918,-150.6722 968.4333,-141 964.4278,-136.1321 959.6247,-131.5763 954.6139,-127.4519"/>
<polygon fill="#000000" stroke="#000000" points="956.7178,-124.6546 946.6539,-121.3428 952.456,-130.2077 956.7178,-124.6546"/>
<text text-anchor="middle" x="1021.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1361.4333" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1361.4333" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1342.496,-87.8576C1328.5753,-76.2885 1308.6372,-61.7636 1288.4333,-54 1245.2244,-37.3964 1115.9828,-26.1275 1045.8801,-21.056"/>
<polygon fill="#000000" stroke="#000000" points="1045.794,-17.5411 1035.5712,-20.3241 1045.2982,-24.5236 1045.794,-17.5411"/>
<text text-anchor="middle" x="1364.9333" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2001.8602,-267.4854C1952.4475,-252.7754 1872.3123,-229.072 1865.4333,-228 1711.0234,-203.9383 1316.2789,-237.4392 1162.4333,-210 1158.7232,-209.3383 1154.9209,-208.464 1151.1395,-207.4567"/>
<polygon fill="#000000" stroke="#000000" points="1151.8383,-204.0136 1141.2562,-204.5343 1149.8534,-210.7263 1151.8383,-204.0136"/>
<text text-anchor="middle" x="1956.9333" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge39" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2048.7915,-261.0202C2057.8098,-238.7013 2068.7165,-200.3659 2051.4333,-174 1998.291,-92.9306 1945.3399,-111.0393 1851.4333,-87 1696.8436,-47.4264 1200.7119,-25.6474 1045.9757,-19.6934"/>
<polygon fill="#000000" stroke="#000000" points="1045.9846,-16.1913 1035.8585,-19.308 1045.718,-23.1862 1045.9846,-16.1913"/>
<text text-anchor="middle" x="2077.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2029.7316,-261.409C2022.654,-250.8002 2012.6352,-237.539 2001.4333,-228 1997.5444,-224.6884 1844.3733,-142.2984 1839.4333,-141 1748.178,-117.0154 1083.9325,-135.6753 990.4333,-123 984.9203,-122.2526 979.218,-121.235 973.5521,-120.0613"/>
<polygon fill="#000000" stroke="#000000" points="973.9638,-116.5672 963.4415,-117.8048 972.439,-123.3991 973.9638,-116.5672"/>
<text text-anchor="middle" x="2007.9333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M918.7679,-86.9205C919.2588,-76.3932 921.4709,-63.3883 928.4333,-54 935.8939,-43.9398 946.9699,-36.4908 958.1667,-31.065"/>
<polygon fill="#000000" stroke="#000000" points="959.7657,-34.1858 967.5237,-26.9703 956.9593,-27.773 959.7657,-34.1858"/>
<text text-anchor="middle" x="978.9333" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node23" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2327.4333" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2327.4333" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2258.4662,-355.9132C2229.8871,-350.3325 2196.8447,-342.0216 2168.4333,-330 2157.1939,-325.2444 2157.0613,-318.7048 2145.4333,-315 2124.0244,-308.1789 1432.2953,-285.6973 1260.6733,-280.2141"/>
<polygon fill="#000000" stroke="#000000" points="1260.695,-276.7131 1250.5884,-279.8923 1260.4717,-283.7095 1260.695,-276.7131"/>
<text text-anchor="middle" x="2234.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2403.3124,-358.4811C2440.7948,-351.6895 2474.1828,-338.9035 2454.4333,-315 2330.6896,-165.2295 1378.8855,-248.1424 1162.4333,-210 1158.7218,-209.346 1154.9186,-208.477 1151.1366,-207.4733"/>
<polygon fill="#000000" stroke="#000000" points="1151.834,-204.03 1141.2523,-204.5565 1149.8528,-210.7438 1151.834,-204.03"/>
<text text-anchor="middle" x="2498.9333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2324.2841,-347.8648C2321.3532,-336.623 2315.8022,-322.8708 2305.4333,-315 2274.0825,-291.2025 2168.0217,-283.1361 2099.9618,-280.4019"/>
<polygon fill="#000000" stroke="#000000" points="2099.9198,-276.898 2089.7959,-280.0216 2099.658,-283.8931 2099.9198,-276.898"/>
<text text-anchor="middle" x="2383.9333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node24" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1993.4333" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1993.4333" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1917.4563,-364.4711C1732.6796,-360.4674 1272.8738,-348.6769 1245.4333,-330 1237.4991,-324.5998 1232.2632,-315.7701 1228.8247,-306.963"/>
<polygon fill="#000000" stroke="#000000" points="1232.076,-305.6429 1225.6582,-297.2131 1225.4183,-307.8052 1232.076,-305.6429"/>
<text text-anchor="middle" x="1306.4333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1993.253,-347.7898C1992.1212,-336.6647 1988.7207,-323.0697 1979.4333,-315 1970.7972,-307.4963 1173.5787,-212.5815 1162.4333,-210 1159.0163,-209.2086 1155.5093,-208.2825 1152.0055,-207.2754"/>
<polygon fill="#000000" stroke="#000000" points="1152.8044,-203.8595 1142.2174,-204.2677 1150.7482,-210.5507 1152.8044,-203.8595"/>
<text text-anchor="middle" x="1915.4333" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2003.1717,-347.9735C2009.7693,-335.7609 2018.6013,-319.4123 2026.0107,-305.697"/>
<polygon fill="#000000" stroke="#000000" points="2029.1944,-307.1675 2030.8681,-296.7057 2023.0356,-303.8403 2029.1944,-307.1675"/>
<text text-anchor="middle" x="2080.4333" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- exposure -->
<g id="node25" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1224.4333" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1224.4333" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1208.8674,-174.7151C1197.2885,-163.0789 1180.4335,-148.5323 1162.4333,-141 1091.5289,-111.3296 1066.104,-136.4792 990.4333,-123 985.3219,-122.0895 980.0349,-121.0116 974.7585,-119.8428"/>
<polygon fill="#000000" stroke="#000000" points="975.2056,-116.3537 964.6733,-117.5034 973.6238,-123.1726 975.2056,-116.3537"/>
<text text-anchor="middle" x="1229.9333" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
