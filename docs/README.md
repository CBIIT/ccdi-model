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
<svg width="2615pt" height="392pt"
 viewBox="0.00 0.00 2615.44 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2611.4354,-388 2611.4354,4 -4,4"/>
<!-- follow_up -->
<g id="node1" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="946.3431" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="946.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1108.3431" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1108.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M965.5314,-175.0053C978.397,-164.2317 996.0853,-150.5725 1013.3431,-141 1026.6268,-133.6318 1041.7249,-127.1468 1055.913,-121.7846"/>
<polygon fill="#000000" stroke="#000000" points="1057.3692,-124.9788 1065.5568,-118.2547 1054.963,-118.4053 1057.3692,-124.9788"/>
<text text-anchor="middle" x="1058.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node22" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1845.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1845.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.093,-87.011C70.0744,-75.9742 69.9552,-62.3944 78.3431,-54 109.6427,-22.6765 1522.0415,-18.5709 1798.6384,-18.067"/>
<polygon fill="#000000" stroke="#000000" points="1798.7457,-21.5669 1808.7395,-18.0493 1798.7334,-14.5669 1798.7457,-21.5669"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="329.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="329.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M324.323,-347.8273C314.8963,-309.2411 299.6129,-218.9891 348.3431,-174 388.0407,-137.3501 411.9461,-149.2382 465.3431,-141 718.4732,-101.9466 787.9749,-160.4768 1041.3431,-123 1046.0122,-122.3094 1050.8218,-121.4084 1055.6195,-120.3777"/>
<polygon fill="#000000" stroke="#000000" points="1056.4531,-123.7773 1065.4019,-118.1055 1054.8693,-116.9588 1056.4531,-123.7773"/>
<text text-anchor="middle" x="361.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node10" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1367.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1367.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M377.245,-358.7022C454.4993,-347.2545 611.4927,-325.3196 745.3431,-315 870.3693,-305.3607 1185.6783,-317.7714 1309.3431,-297 1314.1585,-296.1912 1319.1298,-295.0859 1324.043,-293.8179"/>
<polygon fill="#000000" stroke="#000000" points="1325.2958,-297.1016 1333.9779,-291.0295 1323.4041,-290.362 1325.2958,-297.1016"/>
<text text-anchor="middle" x="787.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M290.4549,-353.9799C257.7681,-341.1749 216.3431,-317.3763 216.3431,-279 216.3431,-279 216.3431,-279 216.3431,-105 216.3431,-64.2786 1531.8453,-26.4879 1798.5267,-19.2452"/>
<polygon fill="#000000" stroke="#000000" points="1798.7462,-22.7406 1808.6478,-18.9713 1798.5568,-15.7432 1798.7462,-22.7406"/>
<text text-anchor="middle" x="258.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node4" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1642.3431" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1642.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1552.7432,-180.2399C1524.7361,-174.8138 1494.163,-167.0367 1467.3431,-156 1456.0573,-151.3557 1455.8391,-145.0966 1444.3431,-141 1397.2608,-124.2223 1263.9993,-113.8303 1180.1385,-108.7562"/>
<polygon fill="#000000" stroke="#000000" points="1180.1028,-105.248 1169.9129,-108.149 1179.6878,-112.2357 1180.1028,-105.248"/>
<text text-anchor="middle" x="1560.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge28" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1166.1743,-98.1733C1308.0996,-81.4195 1671.357,-38.5384 1799.6377,-23.3954"/>
<polygon fill="#000000" stroke="#000000" points="1800.3686,-26.8335 1809.8893,-22.1852 1799.5479,-19.8817 1800.3686,-26.8335"/>
<text text-anchor="middle" x="1570.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1863.3431" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1863.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1800.1157,-179.9005C1746.1452,-169.5615 1677.0891,-156.3015 1676.3431,-156 1665.0281,-151.4275 1664.9202,-144.8613 1653.3431,-141 1609.6568,-126.4291 1318.4391,-113.242 1180.5208,-107.729"/>
<polygon fill="#000000" stroke="#000000" points="1180.5918,-104.2291 1170.4608,-107.3296 1180.3141,-111.2236 1180.5918,-104.2291"/>
<text text-anchor="middle" x="1744.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cell_line -->
<g id="node7" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="406.3431" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="406.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M430.2579,-176.2269C449.8306,-164.2214 478.7,-148.5218 506.3431,-141 604.1031,-114.399 898.1031,-107.4435 1035.7636,-105.6328"/>
<polygon fill="#000000" stroke="#000000" points="1035.8442,-109.1322 1045.7993,-105.5063 1035.7559,-102.1327 1035.8442,-109.1322"/>
<text text-anchor="middle" x="546.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M441.5485,-204.6376C448.985,-206.8215 456.8508,-208.7793 464.3431,-210 553.7421,-224.5649 1192.8108,-201.2332 1279.3431,-228 1291.0021,-231.6064 1291.8872,-236.7062 1302.3431,-243 1311.6398,-248.5961 1321.8449,-254.4014 1331.3577,-259.6743"/>
<polygon fill="#000000" stroke="#000000" points="1329.7644,-262.7924 1340.2137,-264.5424 1333.1364,-256.6581 1329.7644,-262.7924"/>
<text text-anchor="middle" x="1342.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M421.0042,-174.742C431.9514,-163.1185 447.9678,-148.576 465.3431,-141 666.5836,-53.2548 737.764,-107.4968 956.3431,-87 1278.2312,-56.8156 1666.5808,-29.9586 1798.7287,-21.0886"/>
<polygon fill="#000000" stroke="#000000" points="1799.151,-24.5682 1808.8948,-20.4078 1798.6832,-17.5839 1799.151,-24.5682"/>
<text text-anchor="middle" x="996.8431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2229.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2229.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2208.6185,-204.2696C2203.7605,-206.5997 2198.4948,-208.7101 2193.3431,-210 2049.7224,-245.9594 1668.6765,-183.8991 1527.3431,-228 1515.6931,-231.6352 1515.5122,-238.0817 1504.3431,-243 1474.944,-255.9458 1465.4107,-252.8326 1434.3431,-261 1427.769,-262.7283 1420.8371,-264.5694 1414.0248,-266.3896"/>
<polygon fill="#000000" stroke="#000000" points="1412.9387,-263.057 1404.1851,-269.0258 1414.7503,-269.8186 1412.9387,-263.057"/>
<text text-anchor="middle" x="1551.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2228.8033,-173.9841C2226.7145,-142.0464 2217.0421,-76.7264 2173.3431,-54 2125.4933,-29.1149 1970.5837,-21.3611 1891.9929,-19.0004"/>
<polygon fill="#000000" stroke="#000000" points="1891.9804,-15.4987 1881.8853,-18.714 1891.7821,-22.4959 1891.9804,-15.4987"/>
<text text-anchor="middle" x="2243.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1900.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1900.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1818.6575,-362.5543C1683.0777,-356.5559 1417.2956,-343.5362 1324.3431,-330 1259.798,-320.6006 1237.4391,-330.2816 1181.3431,-297 1162.9323,-286.0769 1168.5325,-270.489 1149.3431,-261 1012.5147,-193.3389 614.308,-238.4709 464.3431,-210 460.2646,-209.2257 456.0686,-208.2637 451.8877,-207.1902"/>
<polygon fill="#000000" stroke="#000000" points="452.7933,-203.8093 442.2222,-204.5185 450.9283,-210.5563 452.7933,-203.8093"/>
<text text-anchor="middle" x="1247.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1980.6509,-361.1058C2069.2078,-353.7905 2203.1989,-336.3814 2233.3431,-297 2250.074,-275.1423 2245.6924,-242.5729 2239.2738,-219.5128"/>
<polygon fill="#000000" stroke="#000000" points="2242.5298,-218.1925 2236.2499,-209.6594 2235.8378,-220.2462 2242.5298,-218.1925"/>
<text text-anchor="middle" x="2310.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1826.4335,-357.7303C1734.1422,-346.7915 1571.6749,-325.5155 1434.3431,-297 1427.5291,-295.5851 1420.3777,-293.892 1413.3885,-292.1182"/>
<polygon fill="#000000" stroke="#000000" points="1413.8829,-288.6298 1403.3226,-289.4848 1412.1112,-295.4019 1413.8829,-288.6298"/>
<text text-anchor="middle" x="1678.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1383.3841,-262.1021C1408.2544,-233.8624 1450.1095,-176.6689 1418.3431,-141 1402.7669,-123.5102 1266.8173,-113.2236 1180.2018,-108.3884"/>
<polygon fill="#000000" stroke="#000000" points="1180.332,-104.8904 1170.156,-107.8396 1179.9501,-111.88 1180.332,-104.8904"/>
<text text-anchor="middle" x="1465.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1332.888,-267.5135C1325.1904,-265.1699 1317.0296,-262.8563 1309.3431,-261 1264.1702,-250.0906 1249.5775,-260.041 1206.3431,-243 1194.9892,-238.5248 1194.9968,-231.6236 1183.3431,-228 1107.0332,-204.2719 543.1981,-222.9664 464.3431,-210 460.1882,-209.3168 455.9181,-208.4087 451.6699,-207.3625"/>
<polygon fill="#000000" stroke="#000000" points="452.4282,-203.9419 441.8614,-204.7115 450.6018,-210.6994 452.4282,-203.9419"/>
<text text-anchor="middle" x="1242.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1385.4234,-262.4121C1400.5341,-248.9731 1421.1935,-231.6845 1431.3431,-228 1510.9503,-199.1011 2111.1539,-230.4298 2193.3431,-210 2195.2758,-209.5196 2197.2244,-208.9231 2199.1613,-208.2422"/>
<polygon fill="#000000" stroke="#000000" points="2200.7484,-211.3722 2208.6217,-204.2826 2198.0458,-204.9149 2200.7484,-211.3722"/>
<text text-anchor="middle" x="1467.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="528.3431" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="528.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M553.094,-175.8511C572.6653,-163.9744 601.133,-148.6255 628.3431,-141 702.938,-120.095 921.2526,-110.5877 1035.9867,-106.9339"/>
<polygon fill="#000000" stroke="#000000" points="1036.1993,-110.429 1046.0853,-106.6189 1035.981,-103.4324 1036.1993,-110.429"/>
<text text-anchor="middle" x="672.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1972.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1972.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1947.8563,-88.2255C1927.112,-74.0149 1897.2985,-53.5915 1875.1658,-38.4297"/>
<polygon fill="#000000" stroke="#000000" points="1877.0251,-35.4609 1866.7972,-32.6968 1873.069,-41.2359 1877.0251,-35.4609"/>
<text text-anchor="middle" x="1967.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2279.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2279.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2227.2259,-349.8181C2194.1011,-339.6227 2150.2766,-326.2985 2111.3431,-315 2082.5547,-306.6456 2070.2754,-315.0503 2046.3431,-297 2031.3727,-285.7089 2040.3472,-270.7711 2024.3431,-261 1939.7099,-209.3279 1678.4028,-232.4688 1579.3431,-228 1455.564,-222.416 586.6944,-229.5606 464.3431,-210 460.1267,-209.3259 455.7927,-208.4146 451.4839,-207.358"/>
<polygon fill="#000000" stroke="#000000" points="452.1097,-203.9016 441.5429,-204.6721 450.2839,-210.6593 452.1097,-203.9016"/>
<text text-anchor="middle" x="2137.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2326.4129,-349.4955C2371.1329,-331.0931 2428.0192,-298.8838 2402.3431,-261 2372.2395,-216.5836 2308.4751,-200.7574 2267.3354,-195.1191"/>
<polygon fill="#000000" stroke="#000000" points="2267.7511,-191.644 2257.3979,-193.894 2266.8945,-198.5914 2267.7511,-191.644"/>
<text text-anchor="middle" x="2499.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2184.1756,-355.7186C2078.168,-344.5283 1901.6516,-326.6753 1749.3431,-315 1609.5249,-304.2822 1572.7856,-319.3091 1434.3431,-297 1427.1491,-295.8407 1419.6133,-294.2241 1412.2992,-292.431"/>
<polygon fill="#000000" stroke="#000000" points="1413.0732,-289.0161 1402.5156,-289.9028 1411.3219,-295.7935 1413.0732,-289.0161"/>
<text text-anchor="middle" x="2015.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="684.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="684.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge35" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M623.4046,-355.1508C560.9226,-342.9035 469.323,-321.4673 443.3431,-297 437.522,-291.5177 423.7652,-249.2457 414.7651,-220.0394"/>
<polygon fill="#000000" stroke="#000000" points="418.0697,-218.8767 411.8009,-210.3355 411.3751,-220.9217 418.0697,-218.8767"/>
<text text-anchor="middle" x="504.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M738.0567,-353.0843C748.3847,-351.0393 759.1569,-349.2046 769.3431,-348 806.4866,-343.6075 1413.7045,-354.0573 1442.3431,-330 1466.3029,-309.8731 1433.6699,-282.5658 1456.3431,-261 1475.7223,-242.5675 1548.9891,-247.558 1575.3431,-243 1609.6986,-237.0581 1617.6993,-231.9255 1652.3431,-228 1771.8671,-214.4569 2076.748,-239.5796 2193.3431,-210 2195.2735,-209.5103 2197.2202,-208.9065 2199.1557,-208.2201"/>
<polygon fill="#000000" stroke="#000000" points="2200.7496,-211.3469 2208.6125,-204.2458 2198.0375,-204.8936 2200.7496,-211.3469"/>
<text text-anchor="middle" x="1517.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M734.8124,-352.3544C781.7137,-340.296 853.7064,-323.3641 917.3431,-315 1090.2617,-292.2724 1137.5528,-327.0912 1309.3431,-297 1314.1527,-296.1575 1319.1204,-295.0308 1324.0314,-293.7502"/>
<polygon fill="#000000" stroke="#000000" points="1325.2903,-297.0317 1333.9638,-290.9473 1323.3891,-290.2948 1325.2903,-297.0317"/>
<text text-anchor="middle" x="978.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="674.3431" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="674.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M694.4348,-174.468C708.9422,-162.8753 729.5623,-148.4828 750.3431,-141 801.2752,-122.6603 947.3395,-112.6523 1036.3749,-108.1008"/>
<polygon fill="#000000" stroke="#000000" points="1036.5937,-111.5943 1046.4062,-107.5987 1036.2437,-104.6031 1036.5937,-111.5943"/>
<text text-anchor="middle" x="809.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node16" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="916.3431" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="916.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M816.3384,-353.5488C800.6161,-351.6506 784.5416,-349.7446 769.3431,-348 732.0411,-343.7181 632.3675,-351.1486 601.3431,-330 572.7623,-310.5171 590.6597,-284.5694 565.3431,-261 548.1139,-244.9598 492.5551,-222.7532 451.9532,-207.9088"/>
<polygon fill="#000000" stroke="#000000" points="453.0983,-204.6011 442.504,-204.4876 450.7151,-211.183 453.0983,-204.6011"/>
<text text-anchor="middle" x="690.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1040.5547,-358.0973C1202.2678,-347.7847 1465.094,-330.9319 1470.3431,-330 1521.4376,-320.9285 1538.524,-324.7997 1582.3431,-297 1600.4195,-285.532 1595.3002,-270.7796 1614.3431,-261 1739.1688,-196.8952 1788.5408,-240.0902 1928.3431,-228 2045.9533,-217.829 2079.4375,-241.0018 2193.3431,-210 2195.2647,-209.477 2197.2047,-208.8474 2199.135,-208.1413"/>
<polygon fill="#000000" stroke="#000000" points="2200.7525,-211.2566 2208.5779,-204.1141 2198.0064,-204.8177 2200.7525,-211.2566"/>
<text text-anchor="middle" x="1722.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M968.9002,-349.3477C1006.9629,-337.9335 1059.8572,-323.3911 1107.3431,-315 1196.1015,-299.3158 1220.9161,-314.4558 1309.3431,-297 1314.0721,-296.0665 1318.9618,-294.8923 1323.8041,-293.5932"/>
<polygon fill="#000000" stroke="#000000" points="1324.9583,-296.9035 1333.6101,-290.7882 1323.0331,-290.1734 1324.9583,-296.9035"/>
<text text-anchor="middle" x="1215.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2123.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2123.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2095.5004,-88.3901C2075.6971,-77.2203 2048.1374,-62.9543 2022.3431,-54 1978.9334,-38.9307 1927.2262,-29.3176 1890.9435,-23.8518"/>
<polygon fill="#000000" stroke="#000000" points="1891.0731,-20.3337 1880.6726,-22.3531 1890.0624,-27.2604 1891.0731,-20.3337"/>
<text text-anchor="middle" x="2112.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="819.3431" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="819.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M840.4871,-175.1993C855.9267,-163.7912 877.8362,-149.3184 899.3431,-141 943.4398,-123.9444 995.8848,-114.9412 1037.2077,-110.2036"/>
<polygon fill="#000000" stroke="#000000" points="1037.6291,-113.6785 1047.1915,-109.1166 1036.8713,-106.7196 1037.6291,-113.6785"/>
<text text-anchor="middle" x="942.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2075.3431" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2075.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1995.374,-179.7472C1982.6537,-177.8138 1969.6394,-175.8449 1957.3431,-174 1903.1406,-165.8674 1886.5964,-175.4203 1835.3431,-156 1823.9309,-151.6758 1823.9486,-144.7752 1812.3431,-141 1753.53,-121.8685 1348.6532,-110.5042 1180.9002,-106.5694"/>
<polygon fill="#000000" stroke="#000000" points="1180.7592,-103.0652 1170.6806,-106.332 1180.5966,-110.0634 1180.7592,-103.0652"/>
<text text-anchor="middle" x="1964.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2090.451,-174.053C2097.6227,-163.3102 2102.943,-150.0332 2094.3431,-141 2066.2687,-111.5109 1756.4176,-152.4891 1728.3431,-123 1695.6642,-88.6744 1761.1513,-52.6043 1806.6656,-32.9499"/>
<polygon fill="#000000" stroke="#000000" points="1808.1705,-36.114 1816.0321,-29.0116 1805.4572,-29.6612 1808.1705,-36.114"/>
<text text-anchor="middle" x="1814.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2355.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2355.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2327.3251,-89.0211C2305.2456,-77.2358 2273.2917,-61.927 2243.3431,-54 2178.1021,-36.7315 1982.1665,-24.9186 1891.8572,-20.2422"/>
<polygon fill="#000000" stroke="#000000" points="1891.8071,-16.7352 1881.6415,-19.7204 1891.4499,-23.7261 1891.8071,-16.7352"/>
<text text-anchor="middle" x="2332.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_personnel -->
<g id="node21" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2520.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2520.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge38" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2485.1187,-88.407C2458.375,-76.6269 2420.3543,-61.6047 2385.3431,-54 2291.8538,-33.6933 2005.3973,-22.9134 1892.135,-19.3534"/>
<polygon fill="#000000" stroke="#000000" points="1892.1484,-15.8522 1882.0449,-19.041 1891.9318,-22.8488 1892.1484,-15.8522"/>
<text text-anchor="middle" x="2503.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- family_relationship -->
<g id="node23" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1119.3431" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1119.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1113.353,-173.8765C1111.7415,-168.215 1110.2071,-161.9049 1109.3431,-156 1108.2626,-148.6148 1107.7852,-140.5645 1107.6308,-133.0876"/>
<polygon fill="#000000" stroke="#000000" points="1111.1307,-133.0171 1107.5986,-123.0284 1104.1308,-133.0396 1111.1307,-133.0171"/>
<text text-anchor="middle" x="1188.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1298.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1298.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1243.6238,-351.6277C1202.0066,-340.9137 1143.2502,-326.2513 1091.3431,-315 964.0682,-287.412 931.7547,-282.6906 803.3431,-261 653.1092,-235.6233 612.8607,-244.011 464.3431,-210 460.5213,-209.1248 456.5859,-208.124 452.6507,-207.0526"/>
<polygon fill="#000000" stroke="#000000" points="453.5104,-203.6583 442.9335,-204.2753 451.5866,-210.3888 453.5104,-203.6583"/>
<text text-anchor="middle" x="1073.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1379.51,-358.2742C1446.3914,-351.6371 1543.6632,-341.3617 1628.3431,-330 1720.6775,-317.6113 1749.9423,-334.2264 1835.3431,-297 1859.1415,-286.6263 1857.5653,-271.4206 1881.3431,-261 2010.0343,-204.6015 2059.6558,-253.2425 2193.3431,-210 2195.1881,-209.4032 2197.0561,-208.7243 2198.9205,-207.9881"/>
<polygon fill="#000000" stroke="#000000" points="2200.3513,-211.1824 2208.0883,-203.9444 2197.5263,-204.7777 2200.3513,-211.1824"/>
<text text-anchor="middle" x="1952.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1312.64,-347.9735C1322.5775,-335.4437 1335.9679,-318.56 1347.0131,-304.6335"/>
<polygon fill="#000000" stroke="#000000" points="1350.0637,-306.4196 1353.5354,-296.4097 1344.5792,-302.0698 1350.0637,-306.4196"/>
<text text-anchor="middle" x="1407.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- molecular_test -->
<g id="node25" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1317.3431" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1317.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1304.3298,-173.797C1295.4292,-162.6748 1282.6757,-149.0803 1268.3431,-141 1241.0539,-125.6151 1207.6665,-116.8049 1178.4638,-111.7597"/>
<polygon fill="#000000" stroke="#000000" points="1178.755,-108.2616 1168.3258,-110.1276 1177.6424,-115.1726 1178.755,-108.2616"/>
<text text-anchor="middle" x="1350.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
</g>
</svg>
</div>
