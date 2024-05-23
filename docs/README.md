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
<svg width="2416pt" height="305pt"
 viewBox="0.00 0.00 2416.04 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2412.0433,-301 2412.0433,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1299.0433" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1299.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node24" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="899.0433" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="899.0433" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1281.065,-87.5002C1268.0144,-75.9223 1249.3296,-61.5342 1230.0433,-54 1179.3525,-34.1975 1024.1581,-24.0495 945.6154,-20.0669"/>
<polygon fill="#000000" stroke="#000000" points="945.6768,-16.5658 935.5161,-19.5674 945.331,-23.5572 945.6768,-16.5658"/>
<text text-anchor="middle" x="1306.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node2" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="425.0433" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="425.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="401.0433" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="401.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M427.0585,-260.6878C427.5602,-250.8039 427.2261,-238.5099 424.0433,-228 423.0235,-224.6327 421.5919,-221.2773 419.9361,-218.0448"/>
<polygon fill="#000000" stroke="#000000" points="422.914,-216.2039 414.8319,-209.3532 416.8779,-219.7487 422.914,-216.2039"/>
<text text-anchor="middle" x="498.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1203.0433" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1203.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1225.1384,-262.2978C1240.475,-249.5716 1260.2045,-230.7468 1272.0433,-210 1285.6717,-186.1168 1292.5384,-155.2971 1295.9225,-133.236"/>
<polygon fill="#000000" stroke="#000000" points="1299.4104,-133.5647 1297.3184,-123.1784 1292.4769,-132.6023 1299.4104,-133.5647"/>
<text text-anchor="middle" x="1330.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1160.1238,-267.8519C1111.1373,-255.664 1028.4255,-236.7105 956.0433,-228 734.829,-201.379 674.3002,-249.6335 455.0433,-210 451.1079,-209.2886 447.0673,-208.3524 443.053,-207.2801"/>
<polygon fill="#000000" stroke="#000000" points="443.7852,-203.8473 433.2041,-204.385 441.8111,-210.5632 443.7852,-203.8473"/>
<text text-anchor="middle" x="1088.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="865.0433" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="865.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M845.6672,-261.4167C831.4029,-249.6399 810.9307,-235.0479 790.0433,-228 719.4044,-204.1647 528.2854,-223.9125 455.0433,-210 451.1674,-209.2638 447.1872,-208.3194 443.2294,-207.2498"/>
<polygon fill="#000000" stroke="#000000" points="444.0917,-203.8551 433.5098,-204.38 442.1094,-210.5686 444.0917,-203.8551"/>
<text text-anchor="middle" x="885.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node5" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1736.0433" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1736.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1693.0767,-176.4295C1660.3042,-165.096 1613.8338,-150.1831 1572.0433,-141 1503.911,-126.0285 1424.7532,-116.4282 1369.2744,-110.9401"/>
<polygon fill="#000000" stroke="#000000" points="1369.49,-107.4447 1359.1988,-109.9629 1368.8142,-114.412 1369.49,-107.4447"/>
<text text-anchor="middle" x="1694.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node6" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="733.0433" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="733.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M740.3508,-173.7929C746.0445,-162.2145 755.1625,-148.1083 768.0433,-141 812.7295,-116.3395 1176.5184,-130.2276 1227.0433,-123 1232.763,-122.1818 1238.6882,-121.0979 1244.5714,-119.8665"/>
<polygon fill="#000000" stroke="#000000" points="1245.3912,-123.2697 1254.3889,-117.6758 1243.8666,-116.4378 1245.3912,-123.2697"/>
<text text-anchor="middle" x="851.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1037.0433" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1037.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1043.9647,-173.872C1049.3041,-162.4826 1057.8559,-148.5617 1070.0433,-141 1099.8836,-122.4855 1192.4904,-129.272 1227.0433,-123 1232.4312,-122.022 1238.0146,-120.8726 1243.58,-119.6357"/>
<polygon fill="#000000" stroke="#000000" points="1244.5788,-122.9971 1253.5323,-117.3329 1243.0007,-116.1773 1244.5788,-122.9971"/>
<text text-anchor="middle" x="1109.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- cell_line -->
<g id="node8" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="246.0433" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="246.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M278.1741,-265.2111C291.4804,-259.0344 306.8537,-251.279 320.0433,-243 329.1557,-237.2802 330.1465,-234.0498 339.0433,-228 347.3698,-222.3379 356.6253,-216.6594 365.391,-211.5401"/>
<polygon fill="#000000" stroke="#000000" points="367.3592,-214.4461 374.2892,-206.432 363.8741,-208.3753 367.3592,-214.4461"/>
<text text-anchor="middle" x="379.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M237.2681,-261.2539C224.8211,-233.2965 206.0649,-178.343 230.0433,-141 261.2059,-92.4684 294.1504,-107.5422 348.0433,-87 394.5455,-69.2748 406.1732,-63.4002 455.0433,-54 530.2409,-39.5357 754.7921,-25.9069 852.6265,-20.4766"/>
<polygon fill="#000000" stroke="#000000" points="853.0106,-23.9608 862.8029,-19.916 852.6255,-16.9714 853.0106,-23.9608"/>
<text text-anchor="middle" x="270.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1183.0433" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1183.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1164.1842,-174.0299C1155.7311,-163.7898 1149.2311,-151.0398 1157.0433,-141 1157.3953,-140.5475 1202.4511,-129.1711 1241.7115,-119.3273"/>
<polygon fill="#000000" stroke="#000000" points="1242.688,-122.6909 1251.5374,-116.8652 1240.9865,-115.9008 1242.688,-122.6909"/>
<text text-anchor="middle" x="1221.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="518.0433" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="518.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M533.1809,-87.2519C544.1156,-75.7186 559.9228,-61.4832 577.0433,-54 625.2859,-32.9135 775.1487,-23.416 852.2207,-19.834"/>
<polygon fill="#000000" stroke="#000000" points="852.7621,-23.3133 862.5946,-19.3673 852.4474,-16.3204 852.7621,-23.3133"/>
<text text-anchor="middle" x="646.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M427.0025,-177.1981C450.0796,-164.904 485.1613,-148.2917 518.0433,-141 671.9117,-106.8789 1070.8748,-144.2405 1227.0433,-123 1232.7685,-122.2213 1238.6973,-121.1631 1244.5826,-119.9472"/>
<polygon fill="#000000" stroke="#000000" points="1245.3953,-123.3521 1254.4025,-117.7735 1243.8824,-116.5175 1245.3953,-123.3521"/>
<text text-anchor="middle" x="554.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M357.7653,-196.2338C317.2092,-201.1929 260.8183,-210.9788 247.0433,-228 242.0075,-234.2225 240.4032,-242.409 240.4349,-250.3969"/>
<polygon fill="#000000" stroke="#000000" points="236.9659,-250.9194 241.2681,-260.6014 243.9427,-250.3497 236.9659,-250.9194"/>
<text text-anchor="middle" x="283.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node22" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="385.0433" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="385.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M360.5309,-184.4637C344.4838,-179.2799 327.6091,-170.5759 318.0433,-156 306.7246,-138.7533 328.2435,-125.0236 349.8365,-116.1742"/>
<polygon fill="#000000" stroke="#000000" points="351.2164,-119.3941 359.3213,-112.5705 348.7302,-112.8504 351.2164,-119.3941"/>
<text text-anchor="middle" x="354.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node12" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="683.0433" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="683.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M698.2956,-87.3453C708.9102,-76.1557 723.9941,-62.2796 740.0433,-54 775.3365,-35.7925 819.7074,-26.7292 852.6022,-22.2559"/>
<polygon fill="#000000" stroke="#000000" points="853.3715,-25.6866 862.8531,-20.9591 852.4929,-18.742 853.3715,-25.6866"/>
<text text-anchor="middle" x="788.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="824.0433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="824.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge32" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M831.2953,-86.8119C835.9627,-76.4991 842.7127,-63.7491 851.0433,-54 855.8816,-48.3377 861.7617,-43.0301 867.724,-38.3207"/>
<polygon fill="#000000" stroke="#000000" points="869.8873,-41.0737 875.8155,-32.2926 865.7053,-35.4602 869.8873,-41.0737"/>
<text text-anchor="middle" x="902.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="975.0433" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="975.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M969.9716,-86.6098C966.4477,-76.2298 960.9477,-63.4798 953.0433,-54 947.494,-47.3447 940.4054,-41.4392 933.2032,-36.4335"/>
<polygon fill="#000000" stroke="#000000" points="935.0779,-33.4777 924.7817,-30.9797 931.2728,-39.3533 935.0779,-33.4777"/>
<text text-anchor="middle" x="1019.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1580.0433" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1580.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1545.039,-178.4175C1516.4802,-167.5816 1474.9647,-152.3854 1438.0433,-141 1411.8724,-132.9298 1382.5642,-125.156 1357.6314,-118.9107"/>
<polygon fill="#000000" stroke="#000000" points="1358.1433,-115.4316 1347.5946,-116.4195 1356.457,-122.2255 1358.1433,-115.4316"/>
<text text-anchor="middle" x="1524.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="648.0433" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="648.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M627.514,-261.0339C613.4262,-249.7129 593.7746,-235.8073 574.0433,-228 524.3048,-208.3194 507.0519,-222.5036 455.0433,-210 451.4191,-209.1287 447.6906,-208.1234 443.9673,-207.0425"/>
<polygon fill="#000000" stroke="#000000" points="444.7852,-203.6325 434.1984,-204.0448 442.7316,-210.3245 444.7852,-203.6325"/>
<text text-anchor="middle" x="694.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1141.0433" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1141.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1124.5616,-87.2294C1113.1349,-75.9909 1096.9775,-62.1039 1080.0433,-54 1037.2482,-33.5204 983.4018,-24.6879 945.6073,-20.8805"/>
<polygon fill="#000000" stroke="#000000" points="945.6758,-17.372 935.3955,-19.9344 945.03,-24.3421 945.6758,-17.372"/>
<text text-anchor="middle" x="1164.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="76.0433" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="76.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M85.0537,-260.8663C91.7145,-249.4745 101.8999,-235.553 115.0433,-228 153.3496,-205.9867 274.8663,-197.2138 346.5886,-193.8889"/>
<polygon fill="#000000" stroke="#000000" points="346.9581,-197.3761 356.7934,-193.437 346.6483,-190.3829 346.9581,-197.3761"/>
<text text-anchor="middle" x="176.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1424.0433" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1424.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1419.0808,-261.01C1412.4258,-239.0203 1399.078,-201.3636 1379.0433,-174 1366.0335,-156.2312 1347.6288,-139.9515 1331.7518,-127.6729"/>
<polygon fill="#000000" stroke="#000000" points="1333.8164,-124.8463 1323.7215,-121.63 1329.6074,-130.4395 1333.8164,-124.8463"/>
<text text-anchor="middle" x="1441.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1380.0811,-269.0749C1324.0107,-256.9053 1223.8943,-236.8129 1137.0433,-228 986.2095,-212.6946 604.3605,-236.2572 455.0433,-210 451.1045,-209.3074 447.0616,-208.3839 443.0459,-207.3199"/>
<polygon fill="#000000" stroke="#000000" points="443.7753,-203.8866 433.1948,-204.437 441.8092,-210.6049 443.7753,-203.8866"/>
<text text-anchor="middle" x="1282.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1476.0516,-278.4187C1652.9441,-275.9581 2223.7135,-263.8754 2284.0433,-210 2325.2056,-173.2414 2338.9549,-127.1028 2301.0433,-87 2253.4363,-36.6415 1183.2962,-21.2961 945.5549,-18.5029"/>
<polygon fill="#000000" stroke="#000000" points="945.5499,-15.0027 935.51,-18.3866 945.4687,-22.0022 945.5499,-15.0027"/>
<text text-anchor="middle" x="2365.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node20" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1939.0433" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1939.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1874.4014,-178.2021C1850.1493,-172.3226 1822.5397,-164.78 1798.0433,-156 1783.2571,-150.7003 1781.232,-145.0021 1766.0433,-141 1693.6033,-121.9127 1483.5323,-111.6525 1371.4652,-107.4005"/>
<polygon fill="#000000" stroke="#000000" points="1371.3868,-103.8953 1361.2632,-107.0198 1371.1257,-110.8904 1371.3868,-103.8953"/>
<text text-anchor="middle" x="1877.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="537.0433" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="537.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M560.9355,-174.7542C578.9592,-162.8106 604.8138,-147.8705 630.0433,-141 758.1067,-106.1258 1095.5701,-141.2004 1227.0433,-123 1232.7667,-122.2077 1238.6942,-121.1406 1244.5788,-119.9194"/>
<polygon fill="#000000" stroke="#000000" points="1245.394,-123.3237 1254.3979,-117.7399 1243.877,-116.49 1245.394,-123.3237"/>
<text text-anchor="middle" x="689.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M388.3542,-123.0034C390.5201,-134.7801 393.3945,-150.4102 395.8599,-163.8156"/>
<polygon fill="#000000" stroke="#000000" points="392.4769,-164.7716 397.728,-173.9735 399.3615,-163.5054 392.4769,-164.7716"/>
<text text-anchor="middle" x="418.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M406.2599,-93.109C429.1255,-80.935 466.9675,-62.6146 502.0433,-54 567.3391,-37.9633 762.2249,-25.5312 852.3637,-20.4705"/>
<polygon fill="#000000" stroke="#000000" points="852.7727,-23.9532 862.5633,-19.9043 852.3847,-16.964 852.7727,-23.9532"/>
<text text-anchor="middle" x="526.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2166.0433" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2166.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2086.2127,-179.6747C2044.97,-172.6859 1999.3275,-163.8041 1980.0433,-156 1968.7305,-151.4218 1968.642,-144.7959 1957.0433,-141 1902.6482,-123.1984 1531.2517,-111.2305 1371.6676,-106.8532"/>
<polygon fill="#000000" stroke="#000000" points="1371.5595,-103.349 1361.468,-106.5758 1371.3691,-110.3464 1371.5595,-103.349"/>
<text text-anchor="middle" x="2066.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2165.9374,-173.9809C2164.8514,-162.7868 2161.4739,-149.0441 2152.0433,-141 1882.9588,88.5212 1713.1688,-87.0754 1361.0433,-54 1209.1444,-39.732 1028.7688,-26.8478 945.4611,-21.1268"/>
<polygon fill="#000000" stroke="#000000" points="945.5301,-17.6234 935.3144,-20.4325 945.0521,-24.6071 945.5301,-17.6234"/>
<text text-anchor="middle" x="2211.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment -->
<g id="node25" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="913.0433" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="913.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M922.9388,-174.0804C930.4007,-162.4705 941.7818,-148.2141 956.0433,-141 1009.8999,-113.757 1167.418,-132.3564 1227.0433,-123 1232.5326,-122.1386 1238.2157,-121.0566 1243.8715,-119.8528"/>
<polygon fill="#000000" stroke="#000000" points="1244.989,-123.1888 1253.9748,-117.5758 1243.4499,-116.3601 1244.989,-123.1888"/>
<text text-anchor="middle" x="1003.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
</g>
</svg>
</div>
