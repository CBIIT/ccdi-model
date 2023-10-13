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
<svg width="2431pt" height="392pt"
 viewBox="0.00 0.00 2431.09 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2427.0877,-388 2427.0877,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1890.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1890.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="539.9954" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="539.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1810.4351,-353.0176C1796.0029,-351.0598 1781.0777,-349.2729 1766.9954,-348 1711.8507,-343.0157 1320.9659,-349.1009 1268.9954,-330 1258.897,-326.2885 1260.0666,-318.7848 1249.9954,-315 1218.3654,-303.1133 721.1697,-285.2154 578.183,-280.2925"/>
<polygon fill="#000000" stroke="#000000" points="578.2408,-276.7925 568.1266,-279.9476 578.0007,-283.7884 578.2408,-276.7925"/>
<text text-anchor="middle" x="1360.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="921.9954" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="921.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1979.5263,-354.3842C2007.5236,-348.7707 2033.436,-340.84 2041.9954,-330 2055.5027,-312.8939 2057.8895,-285.5164 2027.9954,-261 1938.9663,-187.9867 1106.9432,-226.5231 992.9954,-210 984.7642,-208.8064 976.1044,-207.0478 967.7723,-205.0907"/>
<polygon fill="#000000" stroke="#000000" points="968.3701,-201.6332 957.8223,-202.6297 966.6894,-208.4284 968.3701,-201.6332"/>
<text text-anchor="middle" x="2142.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1374.9954" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1374.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1875.9344,-348.0727C1865.0338,-336.4594 1849.236,-322.2021 1831.9954,-315 1796.1749,-300.0363 1549.4945,-286.9703 1434.1769,-281.6014"/>
<polygon fill="#000000" stroke="#000000" points="1434.2548,-278.1013 1424.104,-281.1364 1433.932,-285.0939 1434.2548,-278.1013"/>
<text text-anchor="middle" x="1946.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1685.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1685.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge34" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M520.0181,-266.2402C515.8581,-264.1247 511.3965,-262.2242 506.9954,-261 462.4221,-248.6018 122.9951,-276.4143 90.9954,-243 69.7847,-220.8517 71.0233,-197.2715 90.9954,-174 194.6042,-53.2751 1386.2015,-23.7473 1639.0317,-18.8244"/>
<polygon fill="#000000" stroke="#000000" points="1639.4081,-22.3179 1649.3393,-18.6273 1639.2742,-15.3192 1639.4081,-22.3179"/>
<text text-anchor="middle" x="171.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M567.1256,-274.4551C623.7385,-264.7212 758.382,-240.2639 868.9954,-210 872.3302,-209.0876 875.7617,-208.0811 879.1987,-207.0244"/>
<polygon fill="#000000" stroke="#000000" points="880.363,-210.3268 888.8235,-203.9494 878.2326,-203.6588 880.363,-210.3268"/>
<text text-anchor="middle" x="821.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1456.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1456.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1465.2661,-86.8835C1471.3418,-75.6494 1480.6796,-61.8987 1492.9954,-54 1516.7678,-38.7535 1590.6342,-28.161 1639.7802,-22.5858"/>
<polygon fill="#000000" stroke="#000000" points="1640.3097,-26.0487 1649.8653,-21.4724 1639.5415,-19.0909 1640.3097,-26.0487"/>
<text text-anchor="middle" x="1554.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1486.9954" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1486.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1009.9954" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1009.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1432.0965,-180.0169C1422.7242,-177.9933 1413.0828,-175.9254 1403.9954,-174 1365.3673,-165.8156 1353.5015,-171.047 1316.9954,-156 1305.7122,-151.3493 1305.4511,-145.2076 1293.9954,-141 1256.0881,-127.077 1151.8653,-116.3238 1080.7959,-110.3265"/>
<polygon fill="#000000" stroke="#000000" points="1080.8181,-106.8163 1070.5626,-109.4763 1080.2385,-113.7923 1080.8181,-106.8163"/>
<text text-anchor="middle" x="1375.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1695.9954" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1695.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1609.5017,-179.7953C1544.434,-170.4724 1465.2565,-158.7664 1457.9954,-156 1446.591,-151.655 1446.5361,-144.9685 1434.9954,-141 1371.8018,-119.2697 1186.4576,-110.2859 1082.6166,-106.8768"/>
<polygon fill="#000000" stroke="#000000" points="1082.6282,-103.3755 1072.5216,-106.5545 1082.4048,-110.3719 1082.6282,-103.3755"/>
<text text-anchor="middle" x="1550.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1611.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1611.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1615.4023,-86.5688C1618.0379,-76.175 1622.5379,-63.425 1629.9954,-54 1635.5623,-46.9642 1642.9021,-40.8853 1650.4277,-35.8298"/>
<polygon fill="#000000" stroke="#000000" points="1652.5904,-38.6075 1659.2524,-30.3692 1648.9071,-32.6549 1652.5904,-38.6075"/>
<text text-anchor="middle" x="1678.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1759.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1759.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1750.1121,-87.1628C1744.0677,-76.9671 1735.8177,-64.2171 1726.9954,-54 1722.9501,-49.3151 1718.2986,-44.6764 1713.6141,-40.3655"/>
<polygon fill="#000000" stroke="#000000" points="1715.6139,-37.4624 1705.8002,-33.4698 1710.9821,-42.7109 1715.6139,-37.4624"/>
<text text-anchor="middle" x="1794.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M917.7661,-174.0076C916.3476,-163.5111 916.5041,-150.5081 922.9954,-141 929.4823,-131.4983 938.9785,-124.5001 949.3389,-119.347"/>
<polygon fill="#000000" stroke="#000000" points="950.8618,-122.5009 958.612,-115.2769 948.0485,-116.0911 950.8618,-122.5009"/>
<text text-anchor="middle" x="959.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1423.6668,-275.8077C1576.1832,-265.5807 2036.0098,-232.9582 2057.9954,-210 2095.8364,-170.4849 2098.0273,-129.0255 2062.9954,-87 2021.4077,-37.11 1824.001,-23.1847 1732.6168,-19.3847"/>
<polygon fill="#000000" stroke="#000000" points="1732.6682,-15.8841 1722.5385,-18.9889 1732.3935,-22.8787 1732.6682,-15.8841"/>
<text text-anchor="middle" x="2127.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1331.2482,-270.5719C1276.5419,-260.1255 1179.9779,-241.992 1096.9954,-228 1045.1159,-219.2524 1031.26,-221.8295 979.9954,-210 975.3596,-208.9303 970.556,-207.6784 965.7877,-206.3418"/>
<polygon fill="#000000" stroke="#000000" points="966.6957,-202.9608 956.1151,-203.5105 964.7292,-209.6789 966.6957,-202.9608"/>
<text text-anchor="middle" x="1222.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1349.4016,-263.572C1328.1436,-251.5944 1296.6861,-235.7615 1266.9954,-228 1239.4077,-220.7883 1030.5374,-230.7652 1010.9954,-210 992.0588,-189.8781 995.1953,-156.7758 1000.9054,-133.1174"/>
<polygon fill="#000000" stroke="#000000" points="1004.3263,-133.8736 1003.5462,-123.3075 997.567,-132.0539 1004.3263,-133.8736"/>
<text text-anchor="middle" x="1051.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="325.9954" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="325.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M339.1021,-173.9757C348.7056,-162.3191 362.845,-148.0498 378.9954,-141 428.9772,-119.1824 781.8792,-109.5401 937.0683,-106.3208"/>
<polygon fill="#000000" stroke="#000000" points="937.52,-109.8124 947.4464,-106.1089 937.3771,-102.8138 937.52,-109.8124"/>
<text text-anchor="middle" x="458.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="205.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="205.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M211.0682,-347.7852C215.2608,-336.3592 222.441,-322.43 233.9954,-315 279.3531,-285.8327 422.8853,-306.3468 475.9954,-297 485.5956,-295.3105 495.8269,-292.7767 505.228,-290.1396"/>
<polygon fill="#000000" stroke="#000000" points="506.4183,-293.4382 515.0343,-287.2726 504.4539,-286.7195 506.4183,-293.4382"/>
<text text-anchor="middle" x="305.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M187.3718,-348.1248C166.0892,-325.5655 136.9963,-286.6217 159.9954,-261 182.7651,-235.6338 431.0075,-230.5932 464.9954,-228 644.2082,-214.3263 692.3605,-243.2314 868.9954,-210 872.6483,-209.3128 876.3928,-208.429 880.12,-207.4229"/>
<polygon fill="#000000" stroke="#000000" points="881.2825,-210.7288 889.8708,-204.5245 879.288,-204.0189 881.2825,-210.7288"/>
<text text-anchor="middle" x="231.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M269.4546,-353.2049C281.23,-351.1889 293.4551,-349.3335 304.9954,-348 384.1249,-338.8562 588.4249,-358.0058 662.9954,-330 673.0674,-326.2174 671.8933,-318.7015 681.9954,-315 737.0085,-294.8428 1150.5536,-301.1609 1208.9954,-297 1245.3929,-294.4086 1286.1314,-290.0137 1318.1418,-286.2153"/>
<polygon fill="#000000" stroke="#000000" points="1318.7002,-289.6735 1328.2115,-285.0061 1317.8655,-282.7235 1318.7002,-289.6735"/>
<text text-anchor="middle" x="753.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node13" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1939.9954" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1939.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1938.6264,-173.8326C1937.0106,-163.2741 1933.5179,-150.2674 1925.9954,-141 1914.9713,-127.4189 1903.4005,-135.3324 1890.9954,-123 1866.465,-98.6134 1882.5339,-74.9303 1854.9954,-54 1835.9249,-39.5057 1774.8814,-29.0857 1731.6531,-23.2971"/>
<polygon fill="#000000" stroke="#000000" points="1731.9984,-19.8127 1721.6307,-21.9945 1731.0962,-26.7543 1731.9984,-19.8127"/>
<text text-anchor="middle" x="1976.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1861.3851,-179.4892C1848.5662,-177.5691 1835.4198,-175.6719 1822.9954,-174 1753.8255,-164.6921 1732.6433,-179.6951 1666.9954,-156 1655.5162,-151.8567 1655.5902,-144.8078 1643.9954,-141 1630.7995,-136.6663 1245.306,-116.8374 1081.99,-108.602"/>
<polygon fill="#000000" stroke="#000000" points="1081.7237,-105.0842 1071.5603,-108.0766 1081.3715,-112.0754 1081.7237,-105.0842"/>
<text text-anchor="middle" x="1796.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- follow_up -->
<g id="node14" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="498.9954" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="498.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M516.6495,-174.8393C529.9038,-163.102 549.1204,-148.3802 568.9954,-141 634.5719,-116.6495 830.0446,-108.7256 937.4005,-106.1801"/>
<polygon fill="#000000" stroke="#000000" points="937.5896,-109.6768 947.5074,-105.9502 937.4303,-102.6786 937.5896,-109.6768"/>
<text text-anchor="middle" x="613.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge37" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1065.4399,-96.7354C1136.4201,-86.2594 1263.2385,-67.8932 1371.9954,-54 1467.1818,-41.8404 1578.8536,-29.4938 1640.0661,-22.8903"/>
<polygon fill="#000000" stroke="#000000" points="1640.6021,-26.3529 1650.1702,-21.8031 1639.8531,-19.3931 1640.6021,-26.3529"/>
<text text-anchor="middle" x="1422.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="396.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="396.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M385.6807,-347.7376C380.7007,-337.1454 377.489,-324.1366 384.9954,-315 411.1672,-283.1443 435.8979,-306.5886 475.9954,-297 485.3934,-294.7526 495.4892,-292.0501 504.8213,-289.4305"/>
<polygon fill="#000000" stroke="#000000" points="505.9231,-292.7559 514.5787,-286.646 504.0021,-286.0246 505.9231,-292.7559"/>
<text text-anchor="middle" x="451.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M335.2781,-353.8896C283.3681,-343.6683 217.4847,-330.5969 216.9954,-330 212.7688,-324.8444 212.7688,-320.1556 216.9954,-315 242.8572,-283.4537 268.7933,-311.304 306.9954,-297 337.1968,-285.6917 339.2885,-270.8532 369.9954,-261 476.1318,-226.9433 760.0863,-233.7403 868.9954,-210 872.5766,-209.2193 876.2531,-208.278 879.9191,-207.2402"/>
<polygon fill="#000000" stroke="#000000" points="880.9806,-210.5757 889.5257,-204.3121 878.9396,-203.8798 880.9806,-210.5757"/>
<text text-anchor="middle" x="436.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M479.8991,-364.3543C634.4282,-360.827 960.878,-351.0841 1071.9954,-330 1092.7077,-326.0699 1096.4696,-319.8102 1116.9954,-315 1184.4892,-299.1829 1263.6534,-289.4007 1316.3156,-284.097"/>
<polygon fill="#000000" stroke="#000000" points="1316.8746,-287.559 1326.4833,-283.0956 1316.1884,-280.5927 1316.8746,-287.559"/>
<text text-anchor="middle" x="1183.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="626.9954" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="626.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M642.1314,-174.2482C653.0654,-162.7132 668.8724,-148.4774 685.9954,-141 729.7036,-121.9132 856.296,-112.3545 937.6914,-108.0511"/>
<polygon fill="#000000" stroke="#000000" points="938.07,-111.5364 947.8771,-107.5275 937.7106,-104.5456 938.07,-111.5364"/>
<text text-anchor="middle" x="730.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1082.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1082.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1007.4847,-363.6559C862.2506,-358.7814 556.845,-346.608 540.9954,-330 535.1708,-323.8967 533.5427,-315.2733 533.7945,-306.8506"/>
<polygon fill="#000000" stroke="#000000" points="537.2794,-307.1783 534.8782,-296.8592 530.3202,-306.4235 537.2794,-307.1783"/>
<text text-anchor="middle" x="601.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1080.7592,-347.9162C1078.8472,-337.6383 1075.3472,-324.8883 1068.9954,-315 1040.2694,-270.2802 990.1638,-233.4818 956.5401,-212.129"/>
<polygon fill="#000000" stroke="#000000" points="958.2871,-209.0938 947.948,-206.7801 954.5876,-215.0364 958.2871,-209.0938"/>
<text text-anchor="middle" x="1116.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge22" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1158.6187,-364.038C1261.8591,-360.5658 1436.4229,-351.5524 1455.9954,-330 1470.3949,-314.1438 1449.7619,-301.3261 1425.7225,-292.5067"/>
<polygon fill="#000000" stroke="#000000" points="1426.6377,-289.1209 1416.0432,-289.2081 1424.3797,-295.7468 1426.6377,-289.1209"/>
<text text-anchor="middle" x="1521.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- molecular_test -->
<g id="node19" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="779.9954" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="779.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M777.1228,-173.6743C776.511,-162.789 777.8517,-149.4952 785.9954,-141 796.7267,-129.8055 879.0235,-118.7605 940.7752,-111.9174"/>
<polygon fill="#000000" stroke="#000000" points="941.3203,-115.3787 950.8814,-110.8143 940.5607,-108.4201 941.3203,-115.3787"/>
<text text-anchor="middle" x="849.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node20" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2167.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2167.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2148.2583,-87.8949C2133.525,-76.1845 2112.3334,-61.472 2090.9954,-54 2025.9625,-31.2273 1824.5856,-22.2514 1732.6377,-19.2731"/>
<polygon fill="#000000" stroke="#000000" points="1732.6134,-15.7707 1722.5084,-18.955 1732.3936,-22.7672 1732.6134,-15.7707"/>
<text text-anchor="middle" x="2170.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- synonym -->
<g id="node21" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M42.2339,-261.3079C28.044,-232.9343 6.1806,-176.8152 32.9954,-141 84.0746,-72.7759 133.212,-102.6187 216.9954,-87 499.4418,-34.347 1420.673,-20.9432 1639.1979,-18.4726"/>
<polygon fill="#000000" stroke="#000000" points="1639.4025,-21.9707 1649.363,-18.3599 1639.3248,-14.9711 1639.4025,-21.9707"/>
<text text-anchor="middle" x="75.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M66.2343,-261.5321C77.0954,-249.646 93.1848,-234.8727 110.9954,-228 189.5928,-197.6712 786.0445,-224.7153 868.9954,-210 872.706,-209.3417 876.5088,-208.4698 880.2905,-207.4641"/>
<polygon fill="#000000" stroke="#000000" points="881.5755,-210.7341 890.1742,-204.5443 879.5923,-204.0209 881.5755,-210.7341"/>
<text text-anchor="middle" x="153.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M59.7574,-261.1025C71.4544,-236.5905 96.1157,-193.4088 131.9954,-174 202.0609,-136.0988 739.8807,-114.1799 937.4755,-107.3387"/>
<polygon fill="#000000" stroke="#000000" points="937.8766,-110.8271 947.7506,-106.9859 937.6363,-103.8312 937.8766,-110.8271"/>
<text text-anchor="middle" x="174.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1185.9954" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1185.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1123.1809,-179.8347C1092.9753,-173.1504 1060.6247,-164.5075 1047.9954,-156 1038.7919,-149.8002 1030.9581,-140.6082 1024.837,-131.7289"/>
<polygon fill="#000000" stroke="#000000" points="1027.6379,-129.6124 1019.2995,-123.0762 1021.7419,-133.3856 1027.6379,-129.6124"/>
<text text-anchor="middle" x="1115.9954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2335.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2335.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2306.7536,-87.823C2285.1997,-76.0777 2254.7505,-61.3532 2225.9954,-54 2133.1982,-30.2702 1845.6943,-21.5039 1732.4834,-18.9181"/>
<polygon fill="#000000" stroke="#000000" points="1732.4768,-15.4172 1722.4014,-18.6937 1732.321,-22.4154 1732.4768,-15.4172"/>
<text text-anchor="middle" x="2335.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node24" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1619.9954" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1619.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1487.9062,-360.7308C1272.0096,-351.9919 865.8598,-334.9688 850.9954,-330 839.7716,-326.2482 840.0661,-319.1819 828.9954,-315 783.9858,-297.9979 646.1719,-286.3787 578.4173,-281.5357"/>
<polygon fill="#000000" stroke="#000000" points="578.39,-278.0253 568.1695,-280.8168 577.9001,-285.0081 578.39,-278.0253"/>
<text text-anchor="middle" x="959.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1713.9779,-352.7913C1768.7618,-344.6335 1827.9156,-334.831 1831.9954,-330 1836.2968,-324.9066 1836.3359,-320.0601 1831.9954,-315 1749.2852,-218.5791 1393.2742,-241.8435 1266.9954,-228 1145.6819,-214.7008 1113.5357,-229.075 992.9954,-210 984.8696,-208.7141 976.3164,-206.9286 968.0708,-204.9781"/>
<polygon fill="#000000" stroke="#000000" points="968.7628,-201.5438 958.2149,-202.5395 967.0816,-208.3389 968.7628,-201.5438"/>
<text text-anchor="middle" x="1915.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1617.8376,-347.7566C1615.5384,-336.6182 1610.7919,-323.0209 1600.9954,-315 1576.164,-294.6693 1492.6723,-285.6619 1434.4448,-281.7828"/>
<polygon fill="#000000" stroke="#000000" points="1434.4489,-278.2762 1424.248,-281.1382 1434.0072,-285.2622 1434.4489,-278.2762"/>
<text text-anchor="middle" x="1719.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node25" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1341.9954" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1341.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1301.7075,-180.0451C1294.4922,-177.9778 1287.0319,-175.8881 1279.9954,-174 1247.7209,-165.3398 1237.6444,-169.3147 1206.9954,-156 1195.802,-151.1373 1195.2785,-145.6507 1183.9954,-141 1150.524,-127.2038 1111.1732,-118.4911 1078.3681,-113.1004"/>
<polygon fill="#000000" stroke="#000000" points="1078.8339,-109.6307 1068.4111,-111.5321 1077.7448,-116.5455 1078.8339,-109.6307"/>
<text text-anchor="middle" x="1250.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
