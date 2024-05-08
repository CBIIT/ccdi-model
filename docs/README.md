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
<svg width="2787pt" height="305pt"
 viewBox="0.00 0.00 2786.88 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2782.8835,-301 2782.8835,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="669.6897" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="669.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1254.6897" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1254.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M691.247,-176.2785C711.3888,-161.66 738.7885,-141.9842 741.6897,-141 841.9324,-106.9948 1115.0048,-148.705 1217.6897,-123 1219.8856,-122.4503 1222.1047,-121.7609 1224.3077,-120.9749"/>
<polygon fill="#000000" stroke="#000000" points="1225.8571,-124.121 1233.7407,-117.0428 1223.1638,-117.6598 1225.8571,-124.121"/>
<text text-anchor="middle" x="778.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1535.6897" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1535.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M709.6093,-184.0297C739.037,-177.6882 779.8384,-167.915 814.6897,-156 830.318,-150.657 832.5801,-144.6426 848.6897,-141 982.0482,-110.8456 1328.2479,-141.689 1463.6897,-123 1469.4135,-122.2102 1475.3413,-121.1448 1481.226,-119.9245"/>
<polygon fill="#000000" stroke="#000000" points="1482.0407,-123.329 1491.0452,-117.7461 1480.5245,-116.4951 1482.0407,-123.329"/>
<text text-anchor="middle" x="885.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node13" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="565.6897" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="565.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M625.536,-189.7493C576.3257,-186.2082 501.3244,-177.3751 483.6897,-156 470.0326,-139.4461 490.5359,-126.6955 514.4519,-118.0837"/>
<polygon fill="#000000" stroke="#000000" points="515.7038,-121.3558 524.0844,-114.8738 513.4908,-114.7149 515.7038,-121.3558"/>
<text text-anchor="middle" x="520.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1233.7456,-117.0627C1228.6458,-119.4665 1223.0982,-121.6607 1217.6897,-123 1188.0141,-130.3486 688.9509,-119.0317 667.6897,-141 661.8192,-147.0659 660.5948,-155.6797 661.3716,-164.1051"/>
<polygon fill="#000000" stroke="#000000" points="657.9514,-164.8642 663.1339,-174.1049 664.8451,-163.6492 657.9514,-164.8642"/>
<text text-anchor="middle" x="691.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1456.6897" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1456.6897" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1271.3944,-90.3651C1285.1355,-79.0035 1305.5578,-63.6145 1325.6897,-54 1353.1223,-40.8988 1386.1387,-31.8643 1412.1624,-26.1225"/>
<polygon fill="#000000" stroke="#000000" points="1413.0711,-29.5077 1422.1268,-24.0082 1411.6181,-22.6602 1413.0711,-29.5077"/>
<text text-anchor="middle" x="1349.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- therapeutic_procedure -->
<g id="node3" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2198.6897" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2198.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2113.3099,-179.5023C2086.5894,-174.0391 2057.3862,-166.4265 2031.6897,-156 2020.034,-151.2706 2019.7001,-144.738 2007.6897,-141 1922.5186,-114.4921 1694.9341,-136.0277 1606.6897,-123 1601.2646,-122.1991 1595.6525,-121.1572 1590.0703,-119.9783"/>
<polygon fill="#000000" stroke="#000000" points="1590.6265,-116.5159 1580.1015,-117.7306 1589.0868,-123.3445 1590.6265,-116.5159"/>
<text text-anchor="middle" x="2124.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="927.6897" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="927.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M924.4892,-173.8029C923.6667,-162.6831 924.8985,-149.0889 933.6897,-141 955.3701,-121.0516 1434.5144,-127.0955 1463.6897,-123 1469.4116,-122.1968 1475.3382,-121.1226 1481.2222,-119.8971"/>
<polygon fill="#000000" stroke="#000000" points="1482.0393,-123.301 1491.0406,-117.7129 1480.5192,-116.468 1482.0393,-123.301"/>
<text text-anchor="middle" x="997.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="950.6897" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="950.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M905.8819,-268.5248C883.3594,-262.4679 855.9763,-253.8779 832.6897,-243 821.6326,-237.8349 820.8588,-232.9183 809.6897,-228 781.3807,-215.5343 747.8784,-206.7271 720.7458,-200.9452"/>
<polygon fill="#000000" stroke="#000000" points="721.1829,-197.4619 710.6829,-198.876 719.773,-204.3185 721.1829,-197.4619"/>
<text text-anchor="middle" x="877.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M992.5346,-267.3379C1005.9201,-261.8319 1019.8123,-253.9823 1029.6897,-243 1051.3064,-218.9655 1028.1767,-195.0725 1052.6897,-174 1122.4807,-114.0047 1372.8804,-137.9631 1463.6897,-123 1469.1723,-122.0966 1474.851,-120.9868 1480.504,-119.7657"/>
<polygon fill="#000000" stroke="#000000" points="1481.6294,-123.0992 1490.604,-117.4682 1480.0767,-116.2736 1481.6294,-123.0992"/>
<text text-anchor="middle" x="1097.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1007.6897" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1007.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1024.4053,-87.406C1036.5983,-75.7849 1054.1697,-61.3839 1072.6897,-54 1132.8926,-29.9973 1321.627,-21.7101 1410.0783,-19.096"/>
<polygon fill="#000000" stroke="#000000" points="1410.2022,-22.594 1420.0988,-18.8115 1410.0035,-15.5968 1410.2022,-22.594"/>
<text text-anchor="middle" x="1123.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1203.6897" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1203.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1221.9679,-174.9271C1235.6587,-163.2323 1255.4444,-148.5252 1275.6897,-141 1354.368,-111.7552 1380.9651,-137.2187 1463.6897,-123 1469.0866,-122.0724 1474.6759,-120.9567 1480.2451,-119.7409"/>
<polygon fill="#000000" stroke="#000000" points="1481.2341,-123.1051 1490.2019,-117.4634 1479.6732,-116.2814 1481.2341,-123.1051"/>
<text text-anchor="middle" x="1319.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1148.6897" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1148.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1161.3496,-87.3944C1170.6119,-75.9247 1184.2236,-61.7068 1199.6897,-54 1235.6915,-36.0604 1346.5024,-25.6323 1410.249,-20.9649"/>
<polygon fill="#000000" stroke="#000000" points="1410.7109,-24.441 1420.4367,-20.2387 1410.2131,-17.4587 1410.7109,-24.441"/>
<text text-anchor="middle" x="1248.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- family_relationship -->
<g id="node10" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1374.6897" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1374.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1368.3988,-173.5661C1366.0072,-162.9131 1365.3772,-149.9006 1372.6897,-141 1398.8616,-109.1443 1423.4565,-132.0024 1463.6897,-123 1468.6701,-121.8856 1473.833,-120.6851 1479.0027,-119.4519"/>
<polygon fill="#000000" stroke="#000000" points="1480.0108,-122.809 1488.9064,-117.054 1478.3635,-116.0056 1480.0108,-122.809"/>
<text text-anchor="middle" x="1452.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1528.5753,-86.692C1523.9538,-76.3393 1517.2038,-63.5893 1508.6897,-54 1503.205,-47.8227 1496.4529,-42.1669 1489.6521,-37.2597"/>
<polygon fill="#000000" stroke="#000000" points="1491.3439,-34.1781 1481.1033,-31.4614 1487.4146,-39.9713 1491.3439,-34.1781"/>
<text text-anchor="middle" x="1569.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node12" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1377.6897" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1377.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1376.1895,-86.9609C1376.2229,-76.4479 1377.9223,-63.4439 1384.6897,-54 1392.205,-43.5125 1403.6635,-35.9073 1415.2439,-30.4695"/>
<polygon fill="#000000" stroke="#000000" points="1416.6388,-33.6798 1424.4842,-26.5594 1413.9108,-27.2332 1416.6388,-33.6798"/>
<text text-anchor="middle" x="1446.6897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M561.2686,-123.1275C559.782,-133.6718 559.9343,-146.6777 566.6897,-156 573.5465,-165.4621 597.717,-174.1653 620.9206,-180.6435"/>
<polygon fill="#000000" stroke="#000000" points="620.1872,-184.0704 630.7525,-183.2794 621.9999,-177.3092 620.1872,-184.0704"/>
<text text-anchor="middle" x="607.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M611.6274,-98.242C685.3274,-87.5899 834.6141,-66.7939 961.6897,-54 1126.2482,-37.4324 1322.3213,-25.4705 1410.1368,-20.5218"/>
<polygon fill="#000000" stroke="#000000" points="1410.5111,-24.0064 1420.3,-19.9532 1410.12,-17.0174 1410.5111,-24.0064"/>
<text text-anchor="middle" x="1002.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1540.6897" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1540.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1538.3318,-173.7143C1537.6888,-168.0462 1537.0663,-161.7731 1536.6897,-156 1536.2173,-148.7563 1535.9449,-140.9228 1535.7928,-133.6197"/>
<polygon fill="#000000" stroke="#000000" points="1539.2898,-133.3787 1535.6469,-123.4299 1532.2905,-133.479 1539.2898,-133.3787"/>
<text text-anchor="middle" x="1576.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- cytogenomic_file -->
<g id="node15" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="509.6897" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="509.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M510.647,-260.6274C512.1803,-249.7244 515.8935,-236.4285 524.6897,-228 538.0851,-215.1647 581.7861,-205.4329 617.7409,-199.3441"/>
<polygon fill="#000000" stroke="#000000" points="618.3413,-202.7925 627.645,-197.7238 617.2111,-195.8843 618.3413,-202.7925"/>
<text text-anchor="middle" x="596.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node16" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1702.6897" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1702.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1680.4086,-87.4893C1665.2149,-76.3606 1644.2009,-62.4981 1623.6897,-54 1584.4558,-37.7447 1536.8657,-28.411 1502.5413,-23.3414"/>
<polygon fill="#000000" stroke="#000000" points="1502.7297,-19.8334 1492.3388,-21.9021 1501.7518,-26.7648 1502.7297,-19.8334"/>
<text text-anchor="middle" x="1720.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="115.6897" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="115.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M131.3679,-261.038C142.6856,-249.4091 159.032,-235.1475 176.6897,-228 216.4969,-211.8868 495.4568,-198.9622 615.2464,-194.091"/>
<polygon fill="#000000" stroke="#000000" points="615.454,-197.5855 625.305,-193.6857 615.1721,-190.5912 615.454,-197.5855"/>
<text text-anchor="middle" x="268.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node18" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1624.6897" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1624.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1573.6231,-274.8472C1448.3454,-264.5875 1115.8036,-236.9186 838.6897,-210 799.6991,-206.2125 755.6962,-201.5122 722.3669,-197.8646"/>
<polygon fill="#000000" stroke="#000000" points="722.7056,-194.3808 712.3833,-196.7685 721.9416,-201.339 722.7056,-194.3808"/>
<text text-anchor="middle" x="1225.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1676.4489,-277.1158C1868.438,-269.8802 2530.3654,-242.6421 2560.6897,-210 2576.8536,-192.6007 2592.2243,-122.5606 2557.6897,-87 2520.3943,-48.5965 1708.217,-24.6374 1503.3081,-19.1897"/>
<polygon fill="#000000" stroke="#000000" points="1503.2667,-15.6875 1493.1778,-18.9224 1503.082,-22.6851 1503.2667,-15.6875"/>
<text text-anchor="middle" x="2620.1897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1625.7469,-260.9883C1627.3214,-228.0938 1628.8281,-159.9376 1615.6897,-141 1609.8947,-132.6471 1601.6828,-126.2026 1592.7083,-121.2392"/>
<polygon fill="#000000" stroke="#000000" points="1594.0617,-118.0049 1583.541,-116.7536 1590.9851,-124.2926 1594.0617,-118.0049"/>
<text text-anchor="middle" x="1668.1897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2442.6897" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2442.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2436.7497,-174.0061C2432.0444,-162.6734 2424.3034,-148.7651 2412.6897,-141 2181.742,13.4162 2069.405,-88.0929 1793.6897,-54 1689.9729,-41.1752 1567.9562,-28.8172 1502.9572,-22.4516"/>
<polygon fill="#000000" stroke="#000000" points="1502.9376,-18.9331 1492.6448,-21.4452 1502.2576,-25.9 1502.9376,-18.9331"/>
<text text-anchor="middle" x="2467.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2364.0911,-179.5322C2312.4571,-171.0754 2252.3641,-160.6241 2240.6897,-156 2229.3434,-151.5058 2229.3353,-144.6494 2217.6897,-141 2152.8791,-120.6903 1673.9542,-132.4016 1606.6897,-123 1601.2586,-122.2409 1595.6425,-121.2267 1590.0578,-120.065"/>
<polygon fill="#000000" stroke="#000000" points="1590.6086,-116.6019 1580.0861,-117.8377 1589.0826,-123.4335 1590.6086,-116.6019"/>
<text text-anchor="middle" x="2326.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node20" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="325.6897" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="325.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M342.1243,-261.3476C353.9213,-249.8569 370.8333,-235.6333 388.6897,-228 428.3723,-211.0364 545.6987,-200.413 615.5693,-195.4088"/>
<polygon fill="#000000" stroke="#000000" points="616.2067,-198.8728 625.9376,-194.6825 615.7174,-191.8899 616.2067,-198.8728"/>
<text text-anchor="middle" x="449.6897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1800.6897" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1800.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1756.6329,-177.5361C1709.8587,-162.18 1636.0226,-137.9395 1586.7429,-121.7609"/>
<polygon fill="#000000" stroke="#000000" points="1587.8225,-118.4316 1577.2297,-118.6376 1585.639,-125.0823 1587.8225,-118.4316"/>
<text text-anchor="middle" x="1742.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2708.6897" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2708.6897" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2687.3708,-87.7638C2671.2212,-75.8249 2647.9166,-60.8865 2624.6897,-54 2570.1462,-37.8284 1714.2489,-22.3541 1503.3674,-18.7737"/>
<polygon fill="#000000" stroke="#000000" points="1503.3035,-15.2722 1493.2457,-18.6026 1503.1851,-22.2712 1503.3035,-15.2722"/>
<text text-anchor="middle" x="2712.1897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node23" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1977.6897" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1977.6897" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1934.0943,-176.4615C1899.6748,-164.8336 1850.1984,-149.5244 1805.6897,-141 1718.4695,-124.2954 1694.2264,-137.9585 1606.6897,-123 1601.5721,-122.1255 1596.2809,-121.0721 1591.0017,-119.9191"/>
<polygon fill="#000000" stroke="#000000" points="1591.4429,-116.4293 1580.913,-117.5999 1589.8746,-123.2514 1591.4429,-116.4293"/>
<text text-anchor="middle" x="1935.6897" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sequencing_file -->
<g id="node24" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="700.6897" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="700.6897" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M686.5246,-261.1942C682.7626,-255.648 679.0852,-249.3218 676.6897,-243 674.0208,-235.9563 672.3504,-228.0228 671.3105,-220.5487"/>
<polygon fill="#000000" stroke="#000000" points="674.7715,-219.9974 670.2217,-210.4293 667.8117,-220.7463 674.7715,-219.9974"/>
<text text-anchor="middle" x="743.1897" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
