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
<svg width="2256pt" height="305pt"
 viewBox="0.00 0.00 2256.29 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2252.2907,-301 2252.2907,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="27.9475" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="27.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1181.9475" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1181.9475" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M21.5464,-261.0353C18.8737,-251.2532 16.8284,-238.9456 18.9475,-228 26.8697,-187.0815 26.1822,-172.0834 53.9475,-141 87.5966,-103.3297 105.9232,-102.6516 153.9475,-87 257.5742,-53.227 288.4013,-63.8396 396.9475,-54 676.5061,-28.6582 1013.7766,-20.797 1135.4033,-18.6874"/>
<polygon fill="#000000" stroke="#000000" points="1135.5422,-22.1856 1145.4817,-18.5173 1135.4241,-15.1866 1135.5422,-22.1856"/>
<text text-anchor="middle" x="77.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node18" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="194.9475" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="194.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M51.0647,-268.8091C65.8884,-262.0186 85.3872,-252.6053 101.9475,-243 112.1844,-237.0624 113.7599,-234.0218 123.9475,-228 134.3456,-221.8538 145.9193,-215.7083 156.6538,-210.2793"/>
<polygon fill="#000000" stroke="#000000" points="158.4316,-213.3039 165.8206,-205.7109 155.3093,-207.0389 158.4316,-213.3039"/>
<text text-anchor="middle" x="147.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="159.9475" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="159.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M167.1995,-260.9735C172.0332,-248.9585 178.4774,-232.9401 183.9388,-219.3646"/>
<polygon fill="#000000" stroke="#000000" points="187.2195,-220.5871 187.7048,-210.0034 180.7254,-217.9744 187.2195,-220.5871"/>
<text text-anchor="middle" x="246.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="361.9475" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="361.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1256.9475" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1256.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M388.2309,-174.4587C407.6802,-162.5371 435.3109,-147.7514 461.9475,-141 617.9529,-101.4583 1026.5075,-144.9117 1185.9475,-123 1191.4591,-122.2425 1197.1605,-121.2183 1202.8259,-120.0405"/>
<polygon fill="#000000" stroke="#000000" points="1203.9409,-123.3777 1212.9358,-117.7792 1202.4129,-116.5465 1203.9409,-123.3777"/>
<text text-anchor="middle" x="544.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="557.9475" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="557.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M587.3957,-175.3091C610.2219,-163.3124 643.0647,-148.0579 673.9475,-141 784.9341,-115.6353 1073.2408,-139.0801 1185.9475,-123 1191.3765,-122.2254 1196.9912,-121.201 1202.5749,-120.033"/>
<polygon fill="#000000" stroke="#000000" points="1203.5532,-123.4006 1212.5456,-117.7982 1202.0221,-116.5701 1203.5532,-123.4006"/>
<text text-anchor="middle" x="732.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="968.9475" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="968.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M977.2615,-86.9504C983.355,-75.7438 992.6963,-61.9985 1004.9475,-54 1026.1408,-40.1634 1090.9848,-29.4625 1136.003,-23.4443"/>
<polygon fill="#000000" stroke="#000000" points="1136.6685,-26.8873 1146.1322,-22.124 1135.7636,-19.946 1136.6685,-26.8873"/>
<text text-anchor="middle" x="1061.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1116.9475" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1116.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1117.5548,-86.6884C1118.6739,-76.3345 1121.4239,-63.5845 1127.9475,-54 1132.8232,-46.8366 1139.6429,-40.7282 1146.7986,-35.6874"/>
<polygon fill="#000000" stroke="#000000" points="1148.7298,-38.6069 1155.2566,-30.2612 1144.9499,-32.7151 1148.7298,-38.6069"/>
<text text-anchor="middle" x="1176.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="969.9475" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="969.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M980.9336,-173.7415C988.868,-162.297 1000.6762,-148.3636 1014.9475,-141 1082.86,-105.9587 1110.716,-136.4245 1185.9475,-123 1191.0586,-122.088 1196.3454,-121.009 1201.6217,-119.8396"/>
<polygon fill="#000000" stroke="#000000" points="1202.7568,-123.1692 1211.7067,-117.4992 1201.1743,-116.3504 1202.7568,-123.1692"/>
<text text-anchor="middle" x="1082.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge32" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1247.5421,-87.0635C1241.7403,-76.8347 1233.7403,-64.0847 1224.9475,-54 1220.5806,-48.9915 1215.4859,-44.0948 1210.3618,-39.6062"/>
<polygon fill="#000000" stroke="#000000" points="1212.301,-36.6652 1202.3858,-32.9314 1207.8084,-42.0334 1212.301,-36.6652"/>
<text text-anchor="middle" x="1287.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1844.9475" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1844.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1818.2933,-87.7757C1798.5973,-76.0076 1770.6722,-61.2751 1743.9475,-54 1647.3384,-27.7005 1345.5732,-20.4399 1228.772,-18.5878"/>
<polygon fill="#000000" stroke="#000000" points="1228.7649,-15.0874 1218.7127,-18.4346 1228.6581,-22.0866 1228.7649,-15.0874"/>
<text text-anchor="middle" x="1850.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1120.9475" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1120.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1135.8833,-174.7558C1145.8535,-164.016 1159.7073,-150.4874 1173.9475,-141 1184.2617,-134.1283 1196.103,-128.0725 1207.5501,-122.9826"/>
<polygon fill="#000000" stroke="#000000" points="1209.2066,-126.0811 1217.0308,-118.9374 1206.4594,-119.6427 1209.2066,-126.0811"/>
<text text-anchor="middle" x="1213.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="757.9475" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="757.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M773.6374,-174.1549C785.151,-162.4186 801.8765,-147.9831 819.9475,-141 895.9052,-111.648 1105.4147,-135.0655 1185.9475,-123 1191.3709,-122.1875 1196.9819,-121.1379 1202.5634,-119.9542"/>
<polygon fill="#000000" stroke="#000000" points="1203.5492,-123.3197 1212.5313,-117.7009 1202.0057,-116.492 1203.5492,-123.3197"/>
<text text-anchor="middle" x="905.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M681.9714,-179.0797C657.7202,-173.3015 635.2496,-165.599 627.9475,-156 623.9112,-150.6941 624.6629,-146.8013 627.9475,-141 678.2985,-52.0705 1010.8517,-26.4986 1135.1681,-19.9981"/>
<polygon fill="#000000" stroke="#000000" points="1135.6842,-23.4766 1145.4951,-19.4772 1135.3315,-16.4855 1135.6842,-23.4766"/>
<text text-anchor="middle" x="788.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- molecular_test -->
<g id="node12" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1266.9475" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1266.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1261.5617,-173.84C1260.1116,-168.177 1258.7293,-161.8752 1257.9475,-156 1256.963,-148.6014 1256.5183,-140.5466 1256.3648,-133.0695"/>
<polygon fill="#000000" stroke="#000000" points="1259.8646,-132.9954 1256.3156,-123.0127 1252.8646,-133.0297 1259.8646,-132.9954"/>
<text text-anchor="middle" x="1321.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line -->
<g id="node13" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="211.9475" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="211.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M255.0553,-95.8694C312.1509,-84.1569 416.1209,-64.1467 505.9475,-54 741.5515,-27.3864 1025.6347,-20.3617 1135.471,-18.5794"/>
<polygon fill="#000000" stroke="#000000" points="1135.6045,-22.0779 1145.5489,-18.4229 1135.4957,-15.0787 1135.6045,-22.0779"/>
<text text-anchor="middle" x="546.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M169.9062,-114.4636C144.7966,-121.0623 116.3759,-130.5347 108.9475,-141 95.5248,-159.9104 119.5316,-172.9727 145.5581,-181.1408"/>
<polygon fill="#000000" stroke="#000000" points="144.5933,-184.5051 155.1726,-183.9304 146.544,-177.7824 144.5933,-184.5051"/>
<text text-anchor="middle" x="149.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2012.9475" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2012.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge28" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1990.5214,-88.1387C1973.2965,-76.2217 1948.3905,-61.1457 1923.9475,-54 1857.6101,-34.6067 1382.1375,-22.4503 1229.199,-19.0084"/>
<polygon fill="#000000" stroke="#000000" points="1228.8304,-15.4994 1218.7549,-18.7757 1228.6744,-22.4977 1228.8304,-15.4994"/>
<text text-anchor="middle" x="2007.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1422.9475" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1422.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1413.9466,-173.9937C1407.5551,-162.95 1397.9816,-149.369 1385.9475,-141 1367.7378,-128.3363 1345.1871,-120.1116 1324.0591,-114.7762"/>
<polygon fill="#000000" stroke="#000000" points="1324.6859,-111.3282 1314.1508,-112.4524 1323.0875,-118.1433 1324.6859,-111.3282"/>
<text text-anchor="middle" x="1446.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="783.9475" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="783.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M762.8519,-261.5733C747.1247,-249.7073 724.5441,-234.9408 701.9475,-228 605.4299,-198.3534 347.2203,-228.4252 247.9475,-210 244.293,-209.3217 240.5473,-208.4443 236.8193,-207.4423"/>
<polygon fill="#000000" stroke="#000000" points="237.6496,-204.038 227.0672,-204.5507 235.6596,-210.7492 237.6496,-204.038"/>
<text text-anchor="middle" x="794.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M151.1874,-195.4529C107.3397,-199.9201 44.2167,-209.4399 28.9475,-228 23.7256,-234.3474 22.1587,-242.7958 22.2828,-250.9875"/>
<polygon fill="#000000" stroke="#000000" points="18.8064,-251.4066 23.1967,-261.0489 25.7777,-250.7733 18.8064,-251.4066"/>
<text text-anchor="middle" x="65.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M225.3019,-178.8287C255.6766,-166.3851 304.0712,-148.5367 347.9475,-141 531.5241,-109.4667 1001.3742,-148.0479 1185.9475,-123 1191.4604,-122.2519 1197.1626,-121.2337 1202.8285,-120.0597"/>
<polygon fill="#000000" stroke="#000000" points="1203.9417,-123.3974 1212.939,-117.8028 1202.4167,-116.5656 1203.9417,-123.3974"/>
<text text-anchor="middle" x="384.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M198.4699,-173.9735C200.7721,-162.1918 203.8265,-146.5607 206.4454,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="209.9468,-133.489 208.4296,-123.0034 203.0768,-132.1465 209.9468,-133.489"/>
<text text-anchor="middle" x="241.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node19" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2170.9475" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2170.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2143.2273,-88.0988C2122.0667,-76.1614 2091.7422,-61.0774 2062.9475,-54 1981.8631,-34.0705 1399.0595,-21.9625 1228.6374,-18.82"/>
<polygon fill="#000000" stroke="#000000" points="1228.5459,-15.3179 1218.4836,-18.6344 1228.4179,-22.3167 1228.5459,-15.3179"/>
<text text-anchor="middle" x="2164.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node20" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="573.9475" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="573.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M548.2017,-261.3668C529.778,-249.7277 503.9163,-235.3213 478.9475,-228 380.1301,-199.0248 348.8195,-230.7191 247.9475,-210 244.3066,-209.2521 240.5704,-208.3259 236.8488,-207.2913"/>
<polygon fill="#000000" stroke="#000000" points="237.6918,-203.8898 227.1069,-204.3477 235.6671,-210.5906 237.6918,-203.8898"/>
<text text-anchor="middle" x="606.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node21" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1641.9475" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1641.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1639.6432,-260.9788C1635.7835,-237.9015 1625.9194,-198.0299 1601.9475,-174 1564.3033,-136.2648 1417.6431,-117.9118 1328.1023,-110.0519"/>
<polygon fill="#000000" stroke="#000000" points="1328.2756,-106.554 1318.0138,-109.1893 1327.6793,-113.5285 1328.2756,-106.554"/>
<text text-anchor="middle" x="1666.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1692.658,-274.6476C1802.2051,-264.7326 2053.1222,-239.063 2077.9475,-210 2088.3394,-197.8342 2085.8307,-187.9232 2077.9475,-174 2063.9022,-149.1933 2050.1557,-149.5063 2022.9475,-141 1906.4671,-104.5839 1870.0454,-138.1372 1748.9475,-123 1551.7449,-98.3497 1319.4312,-48.79 1225.0447,-27.7762"/>
<polygon fill="#000000" stroke="#000000" points="1225.8074,-24.3604 1215.2848,-25.5954 1224.2809,-31.192 1225.8074,-24.3604"/>
<text text-anchor="middle" x="2104.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1594.6247,-271.3023C1572.3151,-267.8423 1545.306,-263.8955 1520.9475,-261 1357.0045,-241.512 1315.8001,-236.9838 1150.9475,-228 1050.7429,-222.5392 346.7913,-227.3404 247.9475,-210 244.2356,-209.3488 240.432,-208.4818 236.6497,-207.4794"/>
<polygon fill="#000000" stroke="#000000" points="237.3468,-204.036 226.7651,-204.5647 235.3669,-210.7502 237.3468,-204.036"/>
<text text-anchor="middle" x="1403.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1797.9475" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1797.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1765.3706,-177.6046C1737.0343,-165.742 1694.5703,-149.5312 1655.9475,-141 1595.4372,-127.6342 1425.845,-115.433 1328.3461,-109.251"/>
<polygon fill="#000000" stroke="#000000" points="1328.4738,-105.7522 1318.2738,-108.6175 1328.0343,-112.7384 1328.4738,-105.7522"/>
<text text-anchor="middle" x="1750.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1456.9475" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1456.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1471.2744,-261.5878C1492.8997,-233.1082 1528.2941,-176.2163 1497.9475,-141 1486.8331,-128.102 1394.393,-117.1895 1327.306,-110.8659"/>
<polygon fill="#000000" stroke="#000000" points="1327.4694,-107.3662 1317.1891,-109.9287 1326.8236,-114.3363 1327.4694,-107.3662"/>
<text text-anchor="middle" x="1553.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1404.7115,-273.5498C1300.9974,-262.9475 1061.6811,-239.5744 859.9475,-228 724.1121,-220.2065 381.8469,-234.1446 247.9475,-210 244.2387,-209.3312 240.4373,-208.452 236.6565,-207.4414"/>
<polygon fill="#000000" stroke="#000000" points="237.3564,-203.9985 226.7742,-204.514 235.3682,-210.7102 237.3564,-203.9985"/>
<text text-anchor="middle" x="1102.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1968.9475" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1968.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1924.6062,-175.7957C1890.4697,-164.0538 1841.8523,-148.9053 1797.9475,-141 1710.0918,-125.1812 1455.454,-113.0413 1329.3943,-107.8122"/>
<polygon fill="#000000" stroke="#000000" points="1329.2096,-104.3018 1319.0741,-107.3877 1328.9218,-111.2959 1329.2096,-104.3018"/>
<text text-anchor="middle" x="1939.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="350.9475" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="350.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M343.0549,-260.9287C337.3325,-249.859 328.5614,-236.2735 316.9475,-228 291.1347,-209.6114 278.3054,-219.1019 247.9475,-210 244.7827,-209.0511 241.5237,-208.0368 238.2513,-206.9911"/>
<polygon fill="#000000" stroke="#000000" points="239.0675,-203.5757 228.4749,-203.7943 236.8918,-210.229 239.0675,-203.5757"/>
<text text-anchor="middle" x="403.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
</g>
</svg>
</div>
