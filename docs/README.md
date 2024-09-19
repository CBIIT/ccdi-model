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
<svg width="2593pt" height="305pt"
 viewBox="0.00 0.00 2593.23 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2589.2301,-301 2589.2301,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="474.5404" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="474.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1210.5404" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1210.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M506.5613,-178.3691C522.0127,-171.726 540.7891,-163.5569 557.5404,-156 571.8581,-149.5409 574.3142,-144.8574 589.5404,-141 691.3517,-115.2069 996.9474,-107.8264 1137.8845,-105.7689"/>
<polygon fill="#000000" stroke="#000000" points="1138.2006,-109.2649 1148.1503,-105.6242 1138.1019,-102.2656 1138.2006,-109.2649"/>
<text text-anchor="middle" x="629.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1885.5404" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1885.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node20" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2065.5404" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2065.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1895.5974,-260.9623C1902.7786,-249.7606 1913.4653,-236.0163 1926.5404,-228 1959.8319,-207.5889 1974.8722,-220.2978 2012.5404,-210 2015.8753,-209.0883 2019.307,-208.0823 2022.7441,-207.0259"/>
<polygon fill="#000000" stroke="#000000" points="2023.9081,-210.3284 2032.369,-203.9515 2021.7782,-203.6603 2023.9081,-210.3284"/>
<text text-anchor="middle" x="1993.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="640.5404" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="640.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M653.9949,-174.0372C663.8244,-162.408 678.2429,-148.1463 694.5404,-141 734.1163,-123.6462 1005.8975,-112.0364 1138.3215,-107.3437"/>
<polygon fill="#000000" stroke="#000000" points="1138.5098,-110.8394 1148.381,-106.9911 1138.2644,-103.8437 1138.5098,-110.8394"/>
<text text-anchor="middle" x="774.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="863.5404" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="863.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M858.4485,-173.7523C856.6105,-162.8963 856.6291,-149.6059 864.5404,-141 882.6808,-121.2667 1042.0582,-111.5898 1138.0582,-107.5114"/>
<polygon fill="#000000" stroke="#000000" points="1138.4432,-110.9986 1148.2897,-107.0877 1138.1535,-104.0046 1138.4432,-110.9986"/>
<text text-anchor="middle" x="947.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M204.6419,-183.6113C264.2388,-177.4047 334.5968,-167.9642 362.5404,-156 372.4308,-151.7653 371.4555,-144.7482 381.5404,-141 451.3184,-115.0659 948.8519,-107.5419 1137.9035,-105.6057"/>
<polygon fill="#000000" stroke="#000000" points="1138.0562,-109.1045 1148.0206,-105.5045 1137.986,-102.1048 1138.0562,-109.1045"/>
<text text-anchor="middle" x="467.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1541.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1541.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M97.6633,-173.823C85.544,-150.9448 70.1581,-111.6645 90.5404,-87 140.1248,-26.9979 185.1623,-62.4559 262.5404,-54 508.4964,-27.1219 1294.8631,-19.7618 1494.9015,-18.3037"/>
<polygon fill="#000000" stroke="#000000" points="1495.0949,-21.8025 1505.0696,-18.231 1495.0448,-14.8027 1495.0949,-21.8025"/>
<text text-anchor="middle" x="176.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1004.5404" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1004.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1000.6476,-260.9322C996.8512,-238.1693 994.1414,-199.0107 1013.5404,-174 1030.7541,-151.8066 1099.3496,-131.1916 1150.7916,-118.3806"/>
<polygon fill="#000000" stroke="#000000" points="1151.6247,-121.78 1160.5056,-116.0025 1149.9602,-114.9808 1151.6247,-121.78"/>
<text text-anchor="middle" x="1056.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M952.57,-277.6019C770.7641,-271.8012 179.3046,-244.8193 273.5404,-141 357.2717,-48.7534 1275.8175,-23.6059 1494.8494,-18.9021"/>
<polygon fill="#000000" stroke="#000000" points="1495.1172,-22.3973 1505.0412,-18.6872 1494.9696,-15.3989 1495.1172,-22.3973"/>
<text text-anchor="middle" x="316.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1055.3633,-274.7342C1167.2166,-265.4332 1443.1701,-242.9647 1674.5404,-228 1824.6618,-218.2904 1864.8211,-238.4556 2012.5404,-210 2016.1902,-209.2969 2019.9326,-208.4021 2023.6584,-207.3885"/>
<polygon fill="#000000" stroke="#000000" points="2024.826,-210.6926 2033.407,-204.4783 2022.8236,-203.9851 2024.826,-210.6926"/>
<text text-anchor="middle" x="1717.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2062.5404" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2062.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2063.162,-260.9735C2063.5682,-249.1918 2064.1072,-233.5607 2064.5694,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="2068.0728,-220.1181 2064.9196,-210.0034 2061.0769,-219.8768 2068.0728,-220.1181"/>
<text text-anchor="middle" x="2124.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node8" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2246.5404" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2246.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2230.6456,-261.17C2219.99,-250.1966 2205.1022,-236.6277 2189.5404,-228 2166.9975,-215.5019 2139.6891,-206.9683 2116.4441,-201.3592"/>
<polygon fill="#000000" stroke="#000000" points="2116.9497,-197.8843 2106.42,-199.0578 2115.3833,-204.7068 2116.9497,-197.8843"/>
<text text-anchor="middle" x="2281.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1165.5404" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1165.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1174.8644,-173.9735C1181.1394,-161.8418 1189.5255,-145.6287 1196.5905,-131.9698"/>
<polygon fill="#000000" stroke="#000000" points="1199.7428,-133.4935 1201.2283,-123.0034 1193.5252,-130.2776 1199.7428,-133.4935"/>
<text text-anchor="middle" x="1237.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1226.0434,-87.3667C1237.2121,-75.8846 1253.3005,-61.6633 1270.5404,-54 1309.7012,-36.5925 1428.4683,-25.8299 1495.0417,-20.9996"/>
<polygon fill="#000000" stroke="#000000" points="1495.5306,-24.4738 1505.258,-20.2752 1495.0354,-17.4914 1495.5306,-24.4738"/>
<text text-anchor="middle" x="1321.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node11" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1326.5404" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1326.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1316.0878,-173.6686C1309.314,-163.052 1299.689,-150.0417 1288.5404,-141 1279.9377,-134.0231 1269.762,-128.0645 1259.6498,-123.1205"/>
<polygon fill="#000000" stroke="#000000" points="1260.9745,-119.8771 1250.428,-118.8653 1258.0416,-126.2331 1260.9745,-119.8771"/>
<text text-anchor="middle" x="1370.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1350.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1350.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1361.1894,-86.8496C1368.6169,-75.7484 1379.5137,-62.1574 1392.5404,-54 1409.7553,-43.2198 1459.4177,-32.4958 1496.7111,-25.5939"/>
<polygon fill="#000000" stroke="#000000" points="1497.65,-28.9808 1506.8645,-23.7517 1496.4002,-22.0932 1497.65,-28.9808"/>
<text text-anchor="middle" x="1441.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node14" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1456.5404" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1456.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge19" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1471.7367,-89.4461C1484.6678,-76.2108 1503.4469,-56.9898 1518.2707,-41.8172"/>
<polygon fill="#000000" stroke="#000000" points="1521.1253,-43.9038 1525.6102,-34.305 1516.1183,-39.0119 1521.1253,-43.9038"/>
<text text-anchor="middle" x="1527.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1477.4827,-117.07C1482.5826,-119.4735 1488.1306,-121.6657 1493.5404,-123 1525.0018,-130.7599 2053.9834,-117.7358 2076.5404,-141 2082.6791,-147.3312 2082.5576,-156.2232 2080.0496,-164.8124"/>
<polygon fill="#000000" stroke="#000000" points="2076.7507,-163.6393 2076.4105,-174.2287 2083.2801,-166.1628 2076.7507,-163.6393"/>
<text text-anchor="middle" x="2105.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1503.5404" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1503.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1487.7726,-174.2535C1476.4149,-162.7208 1460.0575,-148.4856 1442.5404,-141 1376.331,-112.7066 1352.3809,-135.8772 1281.5404,-123 1276.4322,-122.0715 1271.1475,-120.9812 1265.8725,-119.8046"/>
<polygon fill="#000000" stroke="#000000" points="1266.3226,-116.3157 1255.7892,-117.4549 1264.7339,-123.1331 1266.3226,-116.3157"/>
<text text-anchor="middle" x="1525.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1671.5404" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1671.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1646.4414,-262.7879C1639.2651,-257.2041 1631.9359,-250.4573 1626.5404,-243 1598.1826,-203.8058 1627.4481,-169.7496 1588.5404,-141 1561.0591,-120.6936 1315.3087,-128.222 1281.5404,-123 1276.1994,-122.1741 1270.675,-121.1263 1265.1752,-119.953"/>
<polygon fill="#000000" stroke="#000000" points="1265.8733,-116.5226 1255.3471,-117.7265 1264.3267,-123.3496 1265.8733,-116.5226"/>
<text text-anchor="middle" x="1657.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1704.8412,-264.6357C1733.7985,-252.7924 1777.1723,-236.5927 1816.5404,-228 1902.006,-209.3458 1926.9752,-228.192 2012.5404,-210 2016.1256,-209.2378 2019.8049,-208.3094 2023.4727,-207.2803"/>
<polygon fill="#000000" stroke="#000000" points="2024.5283,-210.6177 2033.0823,-204.3664 2022.4969,-203.9189 2024.5283,-210.6177"/>
<text text-anchor="middle" x="1861.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- molecular_test -->
<g id="node17" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1799.5404" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1799.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1739.4705,-180.0837C1704.1734,-172.6505 1663.2851,-163.1685 1646.5404,-156 1635.3212,-151.197 1635.143,-144.7838 1623.5404,-141 1551.1855,-117.4038 1356.786,-134.4059 1281.5404,-123 1276.1184,-122.1781 1270.5083,-121.1224 1264.9274,-119.9348"/>
<polygon fill="#000000" stroke="#000000" points="1265.4863,-116.4728 1254.9602,-117.677 1263.9398,-123.2998 1265.4863,-116.4728"/>
<text text-anchor="middle" x="1710.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1589.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1589.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1579.5947,-86.9735C1572.8121,-74.6801 1563.7173,-58.1956 1556.1196,-44.4249"/>
<polygon fill="#000000" stroke="#000000" points="1559.0411,-42.4747 1551.1457,-35.4097 1552.912,-45.8563 1559.0411,-42.4747"/>
<text text-anchor="middle" x="1637.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node19" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2469.5404" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2469.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2437.8763,-261.5962C2415.741,-250.2165 2385.1387,-236.0234 2356.5404,-228 2276.0873,-205.4286 2179.1685,-197.0018 2119.9754,-193.8606"/>
<polygon fill="#000000" stroke="#000000" points="2119.8949,-190.3523 2109.733,-193.35 2119.5463,-197.3436 2119.8949,-190.3523"/>
<text text-anchor="middle" x="2489.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2032.711,-179.92C2026.0912,-177.7485 2019.1387,-175.6534 2012.5404,-174 1964.9124,-162.0651 1948.4538,-175.8406 1903.5404,-156 1893.699,-151.6525 1894.6504,-144.6797 1884.5404,-141 1821.5529,-118.0745 1347.9231,-132.2915 1281.5404,-123 1276.1094,-122.2398 1270.4934,-121.225 1264.9087,-120.0628"/>
<polygon fill="#000000" stroke="#000000" points="1265.4597,-116.5997 1254.9371,-117.835 1263.9334,-123.4313 1265.4597,-116.5997"/>
<text text-anchor="middle" x="1940.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2039.4201,-177.2337C2028.2851,-170.8359 2015.1985,-163.1795 2003.5404,-156 1993.1488,-149.6005 1992.1722,-144.693 1980.5404,-141 1877.3215,-108.2292 1598.6061,-149.2533 1493.5404,-123 1491.3443,-122.4513 1489.125,-121.7626 1486.9219,-120.977"/>
<polygon fill="#000000" stroke="#000000" points="1488.0655,-117.6619 1477.4886,-117.0461 1485.373,-124.1234 1488.0655,-117.6619"/>
<text text-anchor="middle" x="2040.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node25" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2219.5404" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2219.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2097.8106,-179.6096C2113.2206,-173.249 2131.709,-164.9595 2147.5404,-156 2155.9204,-151.2575 2173.4338,-138.8734 2189.0891,-127.4968"/>
<polygon fill="#000000" stroke="#000000" points="2191.5144,-130.0596 2197.5255,-121.3351 2187.3857,-124.4068 2191.5144,-130.0596"/>
<text text-anchor="middle" x="2205.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1950.5404" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1950.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1910.6557,-179.8653C1903.3301,-177.795 1895.7277,-175.7506 1888.5404,-174 1848.4834,-164.2433 1835.7258,-171.5444 1797.5404,-156 1786.237,-151.3987 1786.1731,-144.6904 1774.5404,-141 1670.0441,-107.8495 1390.0594,-138.5576 1281.5404,-123 1276.1119,-122.2218 1270.4976,-121.1949 1264.9141,-120.0253"/>
<polygon fill="#000000" stroke="#000000" points="1265.4673,-116.5625 1254.9437,-117.7887 1263.9351,-123.3928 1265.4673,-116.5625"/>
<text text-anchor="middle" x="1841.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1764.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1764.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1750.3043,-87.2602C1740.3385,-76.0348 1726.0688,-62.1506 1710.5404,-54 1672.1013,-33.8239 1623.116,-24.9546 1587.7913,-21.0562"/>
<polygon fill="#000000" stroke="#000000" points="1588.0544,-17.565 1577.7529,-20.0409 1587.35,-24.5295 1588.0544,-17.565"/>
<text text-anchor="middle" x="1786.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node23" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1915.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1915.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1897.5404,-87.5555C1884.4798,-76.0029 1865.792,-61.6224 1846.5404,-54 1800.6481,-35.8295 1661.6066,-25.1119 1588.1546,-20.571"/>
<polygon fill="#000000" stroke="#000000" points="1588.0053,-17.0556 1577.8123,-19.9457 1587.5828,-24.0429 1588.0053,-17.0556"/>
<text text-anchor="middle" x="1923.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node24" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2073.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2073.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2048.5752,-87.9014C2030.1004,-76.1941 2003.8519,-61.4828 1978.5404,-54 1906.4321,-32.6829 1685.3803,-22.828 1588.2008,-19.4392"/>
<polygon fill="#000000" stroke="#000000" points="1588.198,-15.9372 1578.0845,-19.0943 1587.9594,-22.9331 1588.198,-15.9372"/>
<text text-anchor="middle" x="2075.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge31" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2200.2038,-88.2096C2185.27,-76.3288 2163.506,-61.267 2141.5404,-54 2089.6325,-36.827 1720.6005,-23.6446 1588.4599,-19.4281"/>
<polygon fill="#000000" stroke="#000000" points="1588.3622,-15.9234 1578.2565,-19.1054 1588.1408,-22.9199 1588.3622,-15.9234"/>
<text text-anchor="middle" x="2211.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2236.7345,-122.2679C2245.0823,-132.7551 2251.7188,-146.0019 2243.5404,-156 2228.0577,-174.9274 2165.9849,-184.1349 2119.4672,-188.4524"/>
<polygon fill="#000000" stroke="#000000" points="2119.1594,-184.9659 2109.5033,-189.3257 2119.7707,-191.9391 2119.1594,-184.9659"/>
<text text-anchor="middle" x="2287.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
</g>
</svg>
</div>
