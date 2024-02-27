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
<svg width="2905pt" height="305pt"
 viewBox="0.00 0.00 2904.73 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2900.733,-301 2900.733,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1074.5404" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1074.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M124.828,-174.0962C136.755,-162.3331 154.0327,-147.8896 172.5404,-141 249.2345,-112.4503 801.2238,-106.5231 1001.8753,-105.3083"/>
<polygon fill="#000000" stroke="#000000" points="1002.0391,-108.8075 1012.0184,-105.2491 1001.9982,-101.8076 1002.0391,-108.8075"/>
<text text-anchor="middle" x="258.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1797.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1797.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M115.9397,-173.9554C121.6732,-162.4476 130.8012,-148.359 143.5404,-141 362.0066,-14.7998 1023.888,-72.0295 1275.5404,-54 1451.3403,-41.4049 1660.5061,-27.2226 1751.48,-21.0938"/>
<polygon fill="#000000" stroke="#000000" points="1751.7207,-24.5856 1761.463,-20.4216 1751.2504,-17.6014 1751.7207,-24.5856"/>
<text text-anchor="middle" x="395.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node2" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2574.5404" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2574.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node25" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2302.5404" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2302.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2541.6084,-261.4538C2520.1442,-250.5936 2491.258,-237.0442 2464.5404,-228 2428.3418,-215.7464 2386.1628,-206.5261 2353.9192,-200.4854"/>
<polygon fill="#000000" stroke="#000000" points="2354.2866,-196.9945 2343.8197,-198.636 2353.0257,-203.8801 2354.2866,-196.9945"/>
<text text-anchor="middle" x="2610.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node3" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="987.5404" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="987.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M998.1834,-173.857C1004.7311,-163.5593 1013.7311,-150.8093 1023.5404,-141 1028.3804,-136.16 1033.9363,-131.5171 1039.5603,-127.2685"/>
<polygon fill="#000000" stroke="#000000" points="1041.7073,-130.0354 1047.7734,-121.349 1037.6144,-124.3566 1041.7073,-130.0354"/>
<text text-anchor="middle" x="1091.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1126.7778,-95.0402C1187.7232,-83.7184 1291.6191,-65.3422 1381.5404,-54 1515.1451,-37.1478 1673.8967,-25.797 1750.951,-20.8371"/>
<polygon fill="#000000" stroke="#000000" points="1751.5132,-24.3085 1761.2704,-20.1797 1751.0681,-17.3226 1751.5132,-24.3085"/>
<text text-anchor="middle" x="1432.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1190.5404" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1190.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1183.0508,-173.9892C1177.8078,-163.2224 1169.8892,-149.9425 1159.5404,-141 1150.4459,-133.1414 1139.3846,-126.7976 1128.2895,-121.7554"/>
<polygon fill="#000000" stroke="#000000" points="1129.5772,-118.4999 1119.0041,-117.8215 1126.8465,-124.9453 1129.5772,-118.4999"/>
<text text-anchor="middle" x="1251.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node6" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1363.5404" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1363.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1357.9565,-174.0107C1353.4748,-162.6799 1346.0069,-148.7721 1334.5404,-141 1304.777,-120.8262 1212.9098,-111.8443 1146.8147,-107.9221"/>
<polygon fill="#000000" stroke="#000000" points="1146.6234,-104.4058 1136.4416,-107.3351 1146.2278,-111.3946 1146.6234,-104.4058"/>
<text text-anchor="middle" x="1393.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1491.5404" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1491.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1479.6238,-174.1941C1470.8349,-162.6349 1457.7872,-148.3925 1442.5404,-141 1392.0846,-116.5364 1239.1141,-108.6966 1147.0438,-106.1844"/>
<polygon fill="#000000" stroke="#000000" points="1147.0418,-102.6833 1136.9547,-105.9238 1146.8609,-109.681 1147.0418,-102.6833"/>
<text text-anchor="middle" x="1507.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node8" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1458.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1458.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1470.1953,-87.32C1478.7966,-75.817 1491.5758,-61.59 1506.5404,-54 1548.2438,-32.8481 1679.9569,-23.5149 1751.014,-19.9306"/>
<polygon fill="#000000" stroke="#000000" points="1751.2217,-23.4247 1761.0398,-19.4427 1750.8815,-16.433 1751.2217,-23.4247"/>
<text text-anchor="middle" x="1555.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1613.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1613.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1608.7285,-86.9981C1606.9957,-76.2347 1607.0268,-62.9553 1614.5404,-54 1631.6999,-33.5479 1702.6833,-24.5068 1751.0303,-20.6621"/>
<polygon fill="#000000" stroke="#000000" points="1751.5652,-24.132 1761.2769,-19.8973 1751.044,-17.1514 1751.5652,-24.132"/>
<text text-anchor="middle" x="1676.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2813.5404" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2813.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2789.3487,-261.6634C2771.7199,-250.0028 2746.7764,-235.4484 2722.5404,-228 2655.7197,-207.4643 2454.7373,-197.5302 2357.0399,-193.8108"/>
<polygon fill="#000000" stroke="#000000" points="2356.9067,-190.3035 2346.7833,-193.4288 2356.646,-197.2987 2356.9067,-190.3035"/>
<text text-anchor="middle" x="2823.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node12" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1644.5404" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1644.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1620.9623,-174.5775C1603.7596,-162.8765 1579.3768,-148.309 1555.5404,-141 1517.5291,-129.3445 1271.2071,-115.1703 1146.5596,-108.6286"/>
<polygon fill="#000000" stroke="#000000" points="1146.5119,-105.1215 1136.3429,-108.0953 1146.1468,-112.1119 1146.5119,-105.1215"/>
<text text-anchor="middle" x="1652.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- synonym -->
<g id="node13" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1750.5404" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1750.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1698.7806,-277.1409C1505.9931,-269.9696 839.0832,-242.8619 808.5404,-210 747.4132,-144.2316 905.403,-118.9849 1003.4281,-109.8299"/>
<polygon fill="#000000" stroke="#000000" points="1003.9505,-113.2972 1013.5976,-108.9173 1003.3247,-106.3252 1003.9505,-113.2972"/>
<text text-anchor="middle" x="851.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1748.9632,-260.9604C1747.0575,-234.4358 1744.9714,-183.4602 1752.5404,-141 1757.0053,-115.9526 1762.832,-110.9055 1771.5404,-87 1776.5536,-73.2381 1782.2791,-57.9949 1787.0788,-45.3434"/>
<polygon fill="#000000" stroke="#000000" points="1790.4133,-46.4215 1790.6984,-35.8305 1783.8709,-43.9322 1790.4133,-46.4215"/>
<text text-anchor="middle" x="1795.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1777.9503,-263.6946C1800.6773,-251.7881 1834.2197,-235.991 1865.5404,-228 1936.5142,-209.8921 2147.7231,-198.6654 2248.227,-194.2069"/>
<polygon fill="#000000" stroke="#000000" points="2248.6326,-197.6926 2258.4702,-193.7589 2248.3268,-190.6992 2248.6326,-197.6926"/>
<text text-anchor="middle" x="1908.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1843.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1843.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1834.0091,-86.9735C1827.5519,-74.7609 1818.9078,-58.4123 1811.656,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="1814.6704,-42.9101 1806.902,-35.7057 1808.4821,-46.182 1814.6704,-42.9101"/>
<text text-anchor="middle" x="1873.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node15" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1994.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1994.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1975.967,-87.4419C1963.4283,-76.437 1946.0308,-62.7319 1928.5404,-54 1901.3411,-40.4211 1868.3231,-31.3899 1842.2402,-25.7692"/>
<polygon fill="#000000" stroke="#000000" points="1842.7506,-22.3008 1832.2497,-23.7085 1841.3365,-29.1565 1842.7506,-22.3008"/>
<text text-anchor="middle" x="2008.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_personnel -->
<g id="node16" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2169.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2169.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2141.8805,-87.8326C2122.1611,-76.4072 2094.6265,-62.0646 2068.5404,-54 1992.2882,-30.4263 1899.2783,-22.2891 1844.4288,-19.4804"/>
<polygon fill="#000000" stroke="#000000" points="1844.4686,-15.9784 1834.3141,-19.001 1844.1371,-22.9706 1844.4686,-15.9784"/>
<text text-anchor="middle" x="2175.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="291.5404" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="291.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M313.8904,-175.4134C331.3398,-163.4713 356.7129,-148.2395 381.5404,-141 439.8827,-123.9878 836.7723,-111.4287 1002.289,-106.8715"/>
<polygon fill="#000000" stroke="#000000" points="1002.4753,-110.3678 1012.3759,-106.5958 1002.2839,-103.3704 1002.4753,-110.3678"/>
<text text-anchor="middle" x="425.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2302.5404" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2302.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2290.3202,-88.5871C2280.4738,-76.7359 2265.5089,-61.542 2248.5404,-54 2212.2888,-37.8874 1952.3886,-24.786 1844.4009,-19.9775"/>
<polygon fill="#000000" stroke="#000000" points="1844.2767,-16.4687 1834.1323,-19.5249 1843.9684,-23.4619 1844.2767,-16.4687"/>
<text text-anchor="middle" x="2293.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2302.5404,-123.0034C2302.5404,-134.7801 2302.5404,-150.4102 2302.5404,-163.8156"/>
<polygon fill="#000000" stroke="#000000" points="2299.0405,-163.9735 2302.5404,-173.9735 2306.0405,-163.9736 2299.0405,-163.9735"/>
<text text-anchor="middle" x="2326.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pathology_file -->
<g id="node19" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1896.5404" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1896.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1921.3884,-261.8903C1939.4634,-250.3366 1964.974,-235.8167 1989.5404,-228 2036.3977,-213.0906 2171.825,-201.3664 2248.3013,-195.7075"/>
<polygon fill="#000000" stroke="#000000" points="2248.9672,-199.1683 2258.6858,-194.9496 2248.4576,-192.1869 2248.9672,-199.1683"/>
<text text-anchor="middle" x="2050.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node20" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="436.5404" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="436.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M451.6391,-174.2329C462.7423,-162.5324 478.9166,-148.1077 496.5404,-141 542.2689,-122.5576 857.3065,-111.2407 1002.0714,-106.9581"/>
<polygon fill="#000000" stroke="#000000" points="1002.3009,-110.453 1012.1942,-106.6619 1002.0961,-103.4559 1002.3009,-110.453"/>
<text text-anchor="middle" x="555.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node21" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="645.5404" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="645.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M628.6178,-173.7909C620.8424,-163.2176 615.0363,-150.21 623.5404,-141 636.1899,-127.3005 878.2691,-114.1149 1002.4162,-108.22"/>
<polygon fill="#000000" stroke="#000000" points="1002.7749,-111.707 1012.5991,-107.7402 1002.4455,-104.7148 1002.7749,-111.707"/>
<text text-anchor="middle" x="716.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2106.5404" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2106.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2109.1933,-260.8816C2111.7656,-249.7931 2116.7882,-236.2044 2126.5404,-228 2144.8068,-212.6326 2204.1568,-202.7715 2248.9272,-197.3262"/>
<polygon fill="#000000" stroke="#000000" points="2249.5733,-200.7745 2259.0976,-196.1336 2248.758,-193.8221 2249.5733,-200.7745"/>
<text text-anchor="middle" x="2218.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node23" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2397.5404" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2397.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2378.7554,-88.2634C2364.233,-76.4101 2343.0383,-61.3591 2321.5404,-54 2277.1035,-38.7885 1964.7872,-24.7438 1844.559,-19.8406"/>
<polygon fill="#000000" stroke="#000000" points="1844.3441,-16.3291 1834.2107,-19.4219 1844.061,-23.3234 1844.3441,-16.3291"/>
<text text-anchor="middle" x="2391.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2425.0655,-120.1887C2439.4522,-130.1085 2452.236,-143.4957 2442.5404,-156 2431.6931,-169.9894 2390.286,-179.493 2355.2943,-185.2064"/>
<polygon fill="#000000" stroke="#000000" points="2354.4961,-181.7885 2345.1551,-186.7883 2355.5752,-188.7049 2354.4961,-181.7885"/>
<text text-anchor="middle" x="2486.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2329.5404" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2329.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2323.946,-260.9735C2320.2533,-249.0751 2315.3423,-233.2508 2311.1557,-219.7606"/>
<polygon fill="#000000" stroke="#000000" points="2314.4344,-218.5166 2308.1276,-210.0034 2307.749,-220.5914 2314.4344,-218.5166"/>
<text text-anchor="middle" x="2389.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2260.3661,-186.3282C2179.3618,-175.6581 1996.3122,-152.6284 1841.5404,-141 1641.0573,-125.9372 1590.3526,-132.7352 1389.5404,-123 1305.969,-118.9485 1209.9827,-113.3236 1146.1489,-109.4453"/>
<polygon fill="#000000" stroke="#000000" points="1145.989,-105.9291 1135.7946,-108.8144 1145.5632,-112.9162 1145.989,-105.9291"/>
<text text-anchor="middle" x="2030.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2261.4907,-185.287C2228.5396,-178.04 2190.3862,-164.285 2207.5404,-141 2223.5493,-119.2696 2240.4437,-132.9324 2265.5404,-123 2267.3836,-122.2705 2269.2619,-121.4877 2271.1462,-120.6717"/>
<polygon fill="#000000" stroke="#000000" points="2272.839,-123.7463 2280.4808,-116.4078 2269.9305,-117.3791 2272.839,-123.7463"/>
<text text-anchor="middle" x="2244.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2325.7332,-176.432C2334.1539,-170.4046 2343.5549,-163.2225 2351.5404,-156 2360.3421,-148.0393 2369.2532,-138.5595 2376.858,-129.9452"/>
<polygon fill="#000000" stroke="#000000" points="2379.5371,-132.198 2383.4342,-122.3459 2374.2439,-127.6174 2379.5371,-132.198"/>
<text text-anchor="middle" x="2402.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
