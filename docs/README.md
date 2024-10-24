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
<svg width="2741pt" height="305pt"
 viewBox="0.00 0.00 2741.09 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2737.0923,-301 2737.0923,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2383.0923" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2383.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1540.0923" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1540.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2380.3509,-173.9726C2377.5761,-162.4722 2372.0456,-148.3855 2361.0923,-141 2324.9696,-116.6436 1619.4326,-133.2657 1577.0923,-123 1574.8924,-122.4666 1572.6703,-121.7895 1570.4651,-121.0124"/>
<polygon fill="#000000" stroke="#000000" points="1571.6051,-117.6963 1561.027,-117.101 1568.9251,-124.1629 1571.6051,-117.6963"/>
<text text-anchor="middle" x="2409.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1635.0923" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1635.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2420.6489,-182.4542C2432.2988,-179.6038 2445.2005,-176.5593 2457.0923,-174 2478.3115,-169.4334 2539.2306,-172.7023 2553.0923,-156 2557.3498,-150.8699 2557.7567,-145.7632 2553.0923,-141 2536.3939,-123.9481 1717.6593,-126.7678 1694.0923,-123 1689.6294,-122.2865 1685.0344,-121.319 1680.4723,-120.2008"/>
<polygon fill="#000000" stroke="#000000" points="1681.167,-116.7634 1670.6015,-117.5518 1679.3526,-123.5242 1681.167,-116.7634"/>
<text text-anchor="middle" x="2592.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1424.0923" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1424.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2349.3094,-180.3124C2323.042,-171.1249 2290.0827,-159.3392 2284.0923,-156 2274.6948,-150.7616 2275.2137,-144.6483 2265.0923,-141 2185.4197,-112.282 1587.1342,-133.4596 1503.0923,-123 1495.6187,-122.0699 1487.8158,-120.7415 1480.1482,-119.2221"/>
<polygon fill="#000000" stroke="#000000" points="1480.691,-115.7599 1470.1854,-117.1322 1479.2538,-122.6108 1480.691,-115.7599"/>
<text text-anchor="middle" x="2320.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1561.0246,-117.1111C1566.1249,-119.5129 1571.6756,-121.6941 1577.0923,-123 1600.9418,-128.75 2442.9226,-123.4768 2460.0923,-141 2475.002,-156.2168 2453.695,-169.3759 2429.7479,-178.5144"/>
<polygon fill="#000000" stroke="#000000" points="2428.3941,-175.2812 2420.1504,-181.9365 2430.7451,-181.8746 2428.3941,-175.2812"/>
<text text-anchor="middle" x="2488.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1416.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1416.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1536.1543,-86.8111C1532.9518,-75.9772 1527.3933,-62.6895 1518.0923,-54 1502.5508,-39.4805 1480.7965,-30.762 1461.3684,-25.5534"/>
<polygon fill="#000000" stroke="#000000" points="1462.0108,-22.1076 1451.4661,-23.1375 1460.3516,-28.9081 1462.0108,-22.1076"/>
<text text-anchor="middle" x="1553.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1670.5995,-117.5642C1678.2562,-119.7835 1686.3713,-121.774 1694.0923,-123 1720.2964,-127.1611 2630.5086,-122.0627 2649.0923,-141 2653.7617,-145.7583 2653.5809,-151.0709 2649.0923,-156 2634.6656,-171.8424 2478.2245,-170.4585 2457.0923,-174 2448.2811,-175.4766 2438.9659,-177.4278 2430.0265,-179.5001"/>
<polygon fill="#000000" stroke="#000000" points="2429.0476,-176.1355 2420.1404,-181.8724 2430.681,-182.9423 2429.0476,-176.1355"/>
<text text-anchor="middle" x="2692.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1620.8429,-87.2855C1610.8715,-76.0707 1596.6005,-62.1889 1581.0923,-54 1544.0853,-34.459 1497.0519,-25.5171 1462.677,-21.4298"/>
<polygon fill="#000000" stroke="#000000" points="1462.7616,-17.9183 1452.4404,-20.3109 1462.0009,-24.8769 1462.7616,-17.9183"/>
<text text-anchor="middle" x="1641.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2236.0923" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2236.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2184.6956,-177.6221C2166.7136,-171.8359 2146.642,-164.5041 2129.0923,-156 2118.1097,-150.6782 2117.7372,-144.6517 2106.0923,-141 2042.1334,-120.9435 1569.5829,-131.4855 1503.0923,-123 1495.7187,-122.059 1488.023,-120.7395 1480.4525,-119.2379"/>
<polygon fill="#000000" stroke="#000000" points="1481.1152,-115.8008 1470.6099,-117.1754 1479.6795,-122.652 1481.1152,-115.8008"/>
<text text-anchor="middle" x="2197.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node5" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="781.0923" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="781.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M799.5908,-174.9793C813.6774,-163.1476 834.1557,-148.2488 855.0923,-141 900.8319,-125.1637 1208.8682,-112.5103 1351.665,-107.4214"/>
<polygon fill="#000000" stroke="#000000" points="1352.1983,-110.9048 1362.0684,-107.0536 1351.9509,-103.9092 1352.1983,-110.9048"/>
<text text-anchor="middle" x="898.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node6" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1617.0923" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1617.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1645.3451,-262.0072C1666.9073,-250.0231 1697.7972,-234.9207 1727.0923,-228 1857.5606,-197.1779 2198.1655,-233.8188 2330.0923,-210 2333.8009,-209.3304 2337.6022,-208.4506 2341.383,-207.4397"/>
<polygon fill="#000000" stroke="#000000" points="2342.6716,-210.7084 2351.2652,-204.5116 2340.6829,-203.9968 2342.6716,-210.7084"/>
<text text-anchor="middle" x="1788.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M89.1787,-86.7878C91.5245,-75.3629 96.5075,-61.4339 107.0923,-54 133.4455,-35.4916 1139.1175,-21.5384 1369.4338,-18.5815"/>
<polygon fill="#000000" stroke="#000000" points="1369.543,-22.0805 1379.4974,-18.453 1369.4535,-15.0811 1369.543,-22.0805"/>
<text text-anchor="middle" x="176.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="255.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="255.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge28" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M249.8727,-87.0414C247.8663,-76.0167 247.7492,-62.4389 256.0923,-54 275.9867,-33.8771 1154.6926,-21.3437 1369.2214,-18.5802"/>
<polygon fill="#000000" stroke="#000000" points="1369.5568,-22.0763 1379.5111,-18.4486 1369.4672,-15.0769 1369.5568,-22.0763"/>
<text text-anchor="middle" x="307.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="952.0923" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="952.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M946.5009,-173.729C944.3967,-162.8642 944.1484,-149.5728 952.0923,-141 965.4677,-126.5655 1223.1165,-113.5756 1351.9745,-107.9508"/>
<polygon fill="#000000" stroke="#000000" points="1352.3135,-111.4395 1362.1527,-107.5101 1352.0106,-104.4461 1352.3135,-111.4395"/>
<text text-anchor="middle" x="1031.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node10" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="601.0923" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="601.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M605.7452,-173.8655C609.5912,-162.624 616.2274,-148.8718 627.0923,-141 747.2782,-53.923 1218.3441,-26.4628 1369.285,-19.8077"/>
<polygon fill="#000000" stroke="#000000" points="1369.7501,-23.291 1379.5903,-19.3639 1369.4489,-16.2975 1369.7501,-23.291"/>
<text text-anchor="middle" x="851.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M613.2139,-173.9386C622.1652,-162.2655 635.4745,-147.9917 651.0923,-141 682.7205,-126.8409 1165.5921,-112.1179 1351.708,-106.9394"/>
<polygon fill="#000000" stroke="#000000" points="1352.0414,-110.4316 1361.9406,-106.656 1351.8475,-103.4343 1352.0414,-110.4316"/>
<text text-anchor="middle" x="737.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1118.0923" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1118.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1114.2828,-173.6463C1113.1619,-162.7504 1113.9716,-149.4553 1122.0923,-141 1137.7984,-124.6466 1268.3874,-114.0313 1352.6231,-108.8162"/>
<polygon fill="#000000" stroke="#000000" points="1352.8858,-112.3068 1362.6552,-108.207 1352.4614,-105.3197 1352.8858,-112.3068"/>
<text text-anchor="middle" x="1161.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_admin -->
<g id="node12" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1773.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1773.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1749.9682,-87.9876C1733.1163,-76.4798 1709.27,-61.9748 1686.0923,-54 1645.7684,-40.1257 1528.2549,-27.9328 1462.3252,-21.9383"/>
<polygon fill="#000000" stroke="#000000" points="1462.4793,-18.4381 1452.2065,-21.0301 1461.8535,-25.4101 1462.4793,-18.4381"/>
<text text-anchor="middle" x="1775.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1921.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1921.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1899.369,-88.1429C1882.9522,-76.3924 1859.3426,-61.5237 1836.0923,-54 1767.7206,-31.8751 1557.0784,-22.5099 1462.6857,-19.348"/>
<polygon fill="#000000" stroke="#000000" points="1462.6826,-15.8461 1452.5738,-19.0182 1462.4544,-22.8424 1462.6826,-15.8461"/>
<text text-anchor="middle" x="1917.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- generic_file -->
<g id="node14" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1196.0923" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1196.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1238.7067,-265.2868C1279.4085,-252.9104 1342.7231,-235.5264 1399.0923,-228 1604.1996,-200.6142 2126.2666,-245.6948 2330.0923,-210 2333.8044,-209.3499 2337.6081,-208.4837 2341.3905,-207.4818"/>
<polygon fill="#000000" stroke="#000000" points="2342.673,-210.7527 2351.2752,-204.5679 2340.6936,-204.0384 2342.673,-210.7527"/>
<text text-anchor="middle" x="1452.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1130.4154,-277.4214C972.2098,-273.344 578.8516,-261.4703 522.0923,-243 450.9195,-219.8394 344.4426,-201.8004 388.0923,-141 431.8618,-80.0326 475.4011,-105.6756 548.0923,-87 628.5615,-66.326 649.5587,-63.5353 732.0923,-54 970.6936,-26.4339 1258.5873,-19.9563 1369.4549,-18.4501"/>
<polygon fill="#000000" stroke="#000000" points="1369.6697,-21.9477 1379.6238,-18.3193 1369.5796,-14.9483 1369.6697,-21.9477"/>
<text text-anchor="middle" x="441.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1198.1482,-260.9261C1201.7051,-237.7919 1211.0998,-197.8587 1235.0923,-174 1267.8586,-141.4163 1317.2303,-124.0828 1357.2957,-114.9391"/>
<polygon fill="#000000" stroke="#000000" points="1358.2295,-118.3183 1367.2656,-112.7867 1356.7522,-111.4759 1358.2295,-118.3183"/>
<text text-anchor="middle" x="1288.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1794.0923" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1794.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1818.6777,-261.582C1836.9015,-249.7201 1862.8541,-234.9551 1888.0923,-228 1982.8631,-201.8831 2233.4489,-227.9909 2330.0923,-210 2333.7465,-209.3197 2337.4919,-208.4409 2341.2197,-207.4381"/>
<polygon fill="#000000" stroke="#000000" points="2342.38,-210.7447 2350.9715,-204.5449 2340.389,-204.0338 2342.38,-210.7447"/>
<text text-anchor="middle" x="1954.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2441.0923" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2441.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2406.8014,-264.7934C2397.8485,-259.3484 2389.2672,-252.1751 2384.0923,-243 2380.2638,-236.2121 2378.9492,-228.0645 2378.8726,-220.2941"/>
<polygon fill="#000000" stroke="#000000" points="2382.3789,-220.267 2379.4157,-210.095 2375.3888,-219.8947 2382.3789,-220.267"/>
<text text-anchor="middle" x="2428.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2460.6342,-262.0935C2465.6686,-256.5726 2470.4177,-250.0347 2473.0923,-243 2485.9228,-209.2531 2494.6956,-176.0241 2450.0923,-141 2429.3992,-124.751 1529.2086,-126.1892 1503.0923,-123 1495.6166,-122.0871 1487.8125,-120.7688 1480.1442,-119.2545"/>
<polygon fill="#000000" stroke="#000000" points="1480.686,-115.7921 1470.1809,-117.1686 1479.2515,-122.6435 1480.686,-115.7921"/>
<text text-anchor="middle" x="2527.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment -->
<g id="node18" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1505.0923" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1505.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1488.7007,-174.3943C1476.8434,-161.6586 1460.6513,-144.2671 1447.4436,-130.081"/>
<polygon fill="#000000" stroke="#000000" points="1449.8353,-127.5136 1440.4595,-122.5796 1444.712,-132.2835 1449.8353,-127.5136"/>
<text text-anchor="middle" x="1517.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1419.9164,-86.7781C1418.7891,-81.1126 1417.711,-74.8249 1417.0923,-69 1416.3255,-61.7816 1415.9472,-53.9571 1415.7873,-46.6546"/>
<polygon fill="#000000" stroke="#000000" points="1419.2854,-46.4266 1415.6894,-36.4607 1412.2857,-46.4939 1419.2854,-46.4266"/>
<text text-anchor="middle" x="1467.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node20" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2076.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2076.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2048.4397,-88.0464C2027.6876,-76.2481 1998.1416,-61.3616 1970.0923,-54 1874.8293,-28.9979 1578.5947,-20.9718 1462.9802,-18.7514"/>
<polygon fill="#000000" stroke="#000000" points="1462.7554,-15.2467 1452.692,-18.56 1462.6252,-22.2455 1462.7554,-15.2467"/>
<text text-anchor="middle" x="2072.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node21" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1685.0923" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1685.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1650.1104,-174.9292C1627.1696,-164.1919 1596.3062,-150.6017 1568.0923,-141 1552.2295,-135.6017 1515.3226,-126.3978 1482.8458,-118.648"/>
<polygon fill="#000000" stroke="#000000" points="1483.4752,-115.2002 1472.9372,-116.2953 1481.8581,-122.0109 1483.4752,-115.2002"/>
<text text-anchor="middle" x="1688.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2011.0923" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2011.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2016.1347,-260.7377C2020.3145,-249.2916 2027.4918,-235.3579 2039.0923,-228 2093.805,-193.2971 2266.5248,-222.528 2330.0923,-210 2333.7391,-209.2813 2337.4793,-208.3755 2341.2037,-207.3546"/>
<polygon fill="#000000" stroke="#000000" points="2342.3763,-210.657 2350.95,-204.4327 2340.3661,-203.9518 2342.3763,-210.657"/>
<text text-anchor="middle" x="2130.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- molecular_test -->
<g id="node23" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1888.0923" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1888.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1858.4643,-175.0775C1836.2675,-163.2946 1804.7429,-148.4139 1775.0923,-141 1657.5575,-111.6113 1622.9733,-140.512 1503.0923,-123 1495.9153,-121.9516 1488.4245,-120.5953 1481.0375,-119.0977"/>
<polygon fill="#000000" stroke="#000000" points="1481.5764,-115.6342 1471.0678,-116.9835 1480.1242,-122.4819 1481.5764,-115.6342"/>
<text text-anchor="middle" x="1881.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2059.0923" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2059.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2027.602,-175.7136C2000.9786,-162.2622 1964.7444,-144.7845 1949.0923,-141 1852.6787,-117.6882 1601.4188,-136.0731 1503.0923,-123 1495.7237,-122.0203 1488.031,-120.6781 1480.462,-119.1648"/>
<polygon fill="#000000" stroke="#000000" points="1481.1272,-115.7282 1470.6207,-117.0929 1479.6851,-122.578 1481.1272,-115.7282"/>
<text text-anchor="middle" x="2044.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2234.0923" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2234.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2227.8698,-261.0203C2225.3715,-250.2652 2224.6058,-236.9867 2232.0923,-228 2260.4367,-193.9753 2287.2348,-221.1501 2330.0923,-210 2333.4382,-209.1295 2336.8778,-208.1533 2340.3204,-207.1176"/>
<polygon fill="#000000" stroke="#000000" points="2341.4706,-210.4249 2349.9551,-204.0795 2339.3654,-203.7489 2341.4706,-210.4249"/>
<text text-anchor="middle" x="2303.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- synonym -->
<g id="node26" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1350.0923" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1350.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1391.8502,-268.0341C1440.8456,-255.724 1524.7221,-236.3784 1598.0923,-228 1759.7574,-209.5388 2169.8899,-238.4892 2330.0923,-210 2333.8027,-209.3402 2337.6052,-208.4672 2341.3867,-207.4607"/>
<polygon fill="#000000" stroke="#000000" points="2342.6723,-210.7305 2351.2703,-204.5397 2340.6883,-204.0176 2342.6723,-210.7305"/>
<text text-anchor="middle" x="1640.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1308.0968,-268.1249C1296.2064,-265.4029 1283.2031,-262.7602 1271.0923,-261 1184.2658,-248.3808 543.096,-274.0128 483.0923,-210 472.15,-198.3267 476.0162,-188.3502 483.0923,-174 507.7468,-124.0009 638.1731,-92.9117 659.0923,-87 744.9439,-62.7386 768.4649,-64.2131 857.0923,-54 1046.3577,-32.1897 1273.3107,-22.6781 1369.4324,-19.4144"/>
<polygon fill="#000000" stroke="#000000" points="1369.8039,-22.9041 1379.682,-19.0734 1369.5711,-15.9079 1369.8039,-22.9041"/>
<text text-anchor="middle" x="558.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1346.657,-261.0214C1343.3878,-239.3717 1340.6174,-202.3816 1353.0923,-174 1361.1455,-155.6781 1376.5611,-139.7487 1390.9756,-127.8258"/>
<polygon fill="#000000" stroke="#000000" points="1393.1492,-130.5691 1398.8276,-121.6244 1388.8107,-125.0757 1393.1492,-130.5691"/>
<text text-anchor="middle" x="1395.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
