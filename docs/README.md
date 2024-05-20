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
<svg width="2802pt" height="305pt"
 viewBox="0.00 0.00 2801.54 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2797.5404,-301 2797.5404,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1103.5404" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1103.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1199.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1199.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge31" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1105.9447,-86.6537C1108.1697,-76.0317 1112.4268,-63.0211 1120.5404,-54 1130.3541,-43.0886 1144.1307,-35.2696 1157.4362,-29.7691"/>
<polygon fill="#000000" stroke="#000000" points="1158.8613,-32.9721 1166.9779,-26.1625 1156.3863,-26.4243 1158.8613,-32.9721"/>
<text text-anchor="middle" x="1171.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="617.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="617.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M638.998,-87.7961C654.9677,-76.0378 677.8412,-61.3087 700.5404,-54 783.8536,-27.1745 1045.2585,-20.2743 1152.7099,-18.5524"/>
<polygon fill="#000000" stroke="#000000" points="1152.9743,-22.0489 1162.9198,-18.3971 1152.8677,-15.0497 1152.9743,-22.0489"/>
<text text-anchor="middle" x="757.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1979.5404" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1979.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2110.5404" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2110.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1979.8741,-260.8358C1981.0164,-250.0113 1984.2125,-236.7247 1992.5404,-228 2002.2211,-217.858 2032.8623,-208.6739 2060.4931,-202.1206"/>
<polygon fill="#000000" stroke="#000000" points="2061.5272,-205.4744 2070.4923,-199.8283 2059.963,-198.6514 2061.5272,-205.4744"/>
<text text-anchor="middle" x="2053.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="768.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="768.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge25" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M789.2186,-87.7382C804.3704,-76.1128 825.9754,-61.5698 847.5404,-54 902.7782,-34.6102 1070.8835,-24.1374 1153.1719,-20.0518"/>
<polygon fill="#000000" stroke="#000000" points="1153.4255,-23.5437 1163.2438,-19.5624 1153.0857,-16.5519 1153.4255,-23.5437"/>
<text text-anchor="middle" x="898.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="689.5404" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="689.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M706.8064,-174.2392C719.3911,-162.5416 737.5081,-148.1177 756.5404,-141 814.1098,-119.4702 971.8299,-132.5924 1032.5404,-123 1037.8786,-122.1565 1043.4012,-121.097 1048.8999,-119.9165"/>
<polygon fill="#000000" stroke="#000000" points="1049.752,-123.3121 1058.7265,-117.6812 1048.1993,-116.4865 1049.752,-123.3121"/>
<text text-anchor="middle" x="815.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2406.5404" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2406.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2371.1923,-262.6239C2359.0894,-256.74 2345.5717,-249.8572 2333.5404,-243 2322.9375,-236.957 2321.8829,-232.504 2310.5404,-228 2263.2336,-209.2148 2205.7262,-200.1692 2164.5407,-195.8516"/>
<polygon fill="#000000" stroke="#000000" points="2164.7335,-192.3537 2154.4377,-194.8528 2164.0448,-199.3198 2164.7335,-192.3537"/>
<text text-anchor="middle" x="2400.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node7" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="936.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="936.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M942.9764,-86.8C947.9267,-75.5317 955.9116,-61.7741 967.5404,-54 997.1088,-34.2328 1094.1838,-24.6862 1152.9817,-20.6118"/>
<polygon fill="#000000" stroke="#000000" points="1153.3903,-24.0924 1163.1358,-19.936 1152.9254,-17.1079 1153.3903,-24.0924"/>
<text text-anchor="middle" x="1037.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2564.5404" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2564.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2569.2147,-261.1262C2570.928,-250.1353 2570.7655,-236.5634 2562.5404,-228 2548.943,-213.8435 2282.0914,-199.8905 2164.9215,-194.4194"/>
<polygon fill="#000000" stroke="#000000" points="2164.884,-190.914 2154.7327,-193.9475 2164.56,-197.9065 2164.884,-190.914"/>
<text text-anchor="middle" x="2592.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2586.5279,-267.7326C2600.5123,-260.0579 2616.6912,-250.0504 2620.5404,-243 2623.735,-237.1486 2624.6251,-233.2687 2620.5404,-228 2424.6486,24.675 2239.4263,-96.4448 1922.5404,-54 1791.1236,-36.3976 1385.1682,-23.3553 1246.5189,-19.3142"/>
<polygon fill="#000000" stroke="#000000" points="1246.3335,-15.8075 1236.2365,-19.0168 1246.1311,-22.8045 1246.3335,-15.8075"/>
<text text-anchor="middle" x="2576.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1261.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1261.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1248.9256,-87.0286C1242.04,-77.2444 1233.3497,-64.9371 1225.5404,-54 1223.0708,-50.5413 1220.4592,-46.9029 1217.8812,-43.3225"/>
<polygon fill="#000000" stroke="#000000" points="1220.6996,-41.2468 1212.0098,-35.1856 1215.0231,-45.3429 1220.6996,-41.2468"/>
<text text-anchor="middle" x="1296.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- molecular_test -->
<g id="node10" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1410.5404" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1410.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1389.5056,-174.5755C1374.3568,-163.0321 1352.9022,-148.6543 1331.5404,-141 1265.8375,-117.4575 1244.207,-135.4901 1175.5404,-123 1170.1528,-122.02 1164.5696,-120.8693 1159.0043,-119.6316"/>
<polygon fill="#000000" stroke="#000000" points="1159.5839,-116.1733 1149.0522,-117.3278 1158.0052,-122.993 1159.5839,-116.1733"/>
<text text-anchor="middle" x="1425.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node11" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="310.5404" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="310.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M313.6448,-173.9586C316.6493,-162.4521 322.457,-148.3639 333.5404,-141 365.8961,-119.5027 994.0582,-128.306 1032.5404,-123 1038.0516,-122.2401 1043.7528,-121.2142 1049.418,-120.0355"/>
<polygon fill="#000000" stroke="#000000" points="1050.5335,-123.3725 1059.5278,-117.773 1049.0048,-116.5414 1050.5335,-123.3725"/>
<text text-anchor="middle" x="377.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2070.878,-184.0395C2000.814,-170.0027 1861.4561,-142.2076 1850.5404,-141 1552.2534,-108.0019 1472.8832,-163.6351 1175.5404,-123 1169.8156,-122.2176 1163.8871,-121.1571 1158.002,-119.9397"/>
<polygon fill="#000000" stroke="#000000" points="1158.7027,-116.5101 1148.1823,-117.7645 1157.1887,-123.3445 1158.7027,-116.5101"/>
<text text-anchor="middle" x="1963.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2154.658,-193.8573C2236.8262,-197.7441 2410.0856,-208.0717 2466.5404,-228 2478.0485,-232.0623 2478.9056,-237.0134 2489.5404,-243 2503.1116,-250.6396 2518.5563,-258.2304 2531.8885,-264.4581"/>
<polygon fill="#000000" stroke="#000000" points="2530.6191,-267.7269 2541.1661,-268.7332 2533.5487,-261.3694 2530.6191,-267.7269"/>
<text text-anchor="middle" x="2526.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2014.5404" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2014.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2073.0651,-182.4449C2049.6109,-175.6306 2022.5528,-165.9465 2015.5404,-156 2010.9279,-149.4576 2009.4479,-141.1771 2009.4635,-133.2015"/>
<polygon fill="#000000" stroke="#000000" points="2012.966,-133.2937 2010.2076,-123.0642 2005.9848,-132.7811 2012.966,-133.2937"/>
<text text-anchor="middle" x="2052.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1416.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1416.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1402.2841,-87.2985C1392.3098,-76.0892 1378.0381,-62.2087 1362.5404,-54 1326.1022,-34.6998 1279.8173,-25.7328 1245.8867,-21.5747"/>
<polygon fill="#000000" stroke="#000000" points="1246.1075,-18.0775 1235.7777,-20.4326 1245.3215,-25.0332 1246.1075,-18.0775"/>
<text text-anchor="middle" x="1430.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2051.7295,-116.9705C2064.6806,-122.6085 2078.4732,-130.4638 2088.5404,-141 2094.6971,-147.4436 2099.2758,-155.8818 2102.6135,-164.0347"/>
<polygon fill="#000000" stroke="#000000" points="2099.4081,-165.4638 2106.0918,-173.6845 2105.9934,-163.0901 2099.4081,-165.4638"/>
<text text-anchor="middle" x="2139.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1972.7383,-95.2373C1920.9067,-83.5238 1829.711,-64.1925 1750.5404,-54 1564.7332,-30.0789 1341.5165,-21.7007 1246.2829,-19.075"/>
<polygon fill="#000000" stroke="#000000" points="1246.2109,-15.5719 1236.121,-18.8035 1246.0239,-22.5694 1246.2109,-15.5719"/>
<text text-anchor="middle" x="1878.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node15" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="429.5404" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="429.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M424.3175,-174.0382C422.3098,-163.0122 422.1925,-149.4342 430.5404,-141 454.0777,-117.2193 999.4041,-127.6389 1032.5404,-123 1037.9713,-122.2397 1043.5874,-121.2247 1049.172,-120.0625"/>
<polygon fill="#000000" stroke="#000000" points="1050.1474,-123.431 1059.1436,-117.8347 1048.621,-116.5994 1050.1474,-123.431"/>
<text text-anchor="middle" x="470.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M116.35,-173.9401C122.456,-162.2676 132.1627,-147.994 145.5404,-141 189.2191,-118.1643 983.6962,-129.599 1032.5404,-123 1038.0537,-122.2551 1043.7562,-121.2391 1049.4222,-120.0665"/>
<polygon fill="#000000" stroke="#000000" points="1050.5349,-123.4044 1059.533,-117.8111 1049.0108,-116.5723 1050.5349,-123.4044"/>
<text text-anchor="middle" x="231.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M110.2079,-173.5081C112.1649,-162.5603 116.399,-149.259 125.5404,-141 206.9883,-67.4132 258.2673,-105.0484 366.5404,-87 663.4363,-37.5095 1026.0662,-22.9198 1153.0065,-19.1647"/>
<polygon fill="#000000" stroke="#000000" points="1153.2516,-22.6592 1163.1469,-18.8731 1153.0504,-15.662 1153.2516,-22.6592"/>
<text text-anchor="middle" x="452.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1608.5404" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1608.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1577.8921,-174.7482C1555.321,-162.9668 1523.4748,-148.2297 1493.5404,-141 1355.9372,-107.7663 1315.4942,-144.2609 1175.5404,-123 1170.0469,-122.1655 1164.361,-121.1013 1158.7035,-119.9085"/>
<polygon fill="#000000" stroke="#000000" points="1159.1215,-116.4155 1148.5982,-117.6445 1157.5911,-123.2462 1159.1215,-116.4155"/>
<text text-anchor="middle" x="1615.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1703.5404" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1703.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1651.3094,-277.9239C1427.8445,-273.0704 561.8025,-251.623 522.5404,-210 417.0814,-98.1997 928.7387,-139.0623 1032.5404,-123 1037.8813,-122.1735 1043.4056,-121.1254 1048.9054,-119.952"/>
<polygon fill="#000000" stroke="#000000" points="1049.754,-123.3485 1058.7334,-117.7252 1048.2072,-116.5215 1049.754,-123.3485"/>
<text text-anchor="middle" x="565.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1722.4375,-262.0078C1736.5625,-250.3521 1756.9165,-235.6586 1777.5404,-228 1784.0261,-225.5916 1964.9997,-206.8587 2057.3735,-197.4111"/>
<polygon fill="#000000" stroke="#000000" points="2057.7823,-200.8876 2067.3747,-196.3891 2057.0706,-193.9239 2057.7823,-200.8876"/>
<text text-anchor="middle" x="1820.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1710.0201,-260.7389C1719.4464,-230.4907 1732.3733,-170.4142 1698.5404,-141 1620.4362,-73.0968 1582.6957,-80.0773 1482.5404,-54 1400.8705,-32.7357 1302.5432,-23.8296 1245.915,-20.251"/>
<polygon fill="#000000" stroke="#000000" points="1246.0326,-16.7518 1235.8399,-19.643 1245.6109,-23.7391 1246.0326,-16.7518"/>
<text text-anchor="middle" x="1753.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment -->
<g id="node20" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="838.5404" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="838.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M855.3634,-174.6669C867.6057,-163.1654 885.1918,-148.8002 903.5404,-141 956.8151,-118.3523 975.7316,-134.1297 1032.5404,-123 1037.5593,-122.0167 1042.7537,-120.8981 1047.9444,-119.711"/>
<polygon fill="#000000" stroke="#000000" points="1048.9498,-123.0698 1057.8751,-117.3611 1047.3379,-116.2579 1048.9498,-123.0698"/>
<text text-anchor="middle" x="950.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- methylation_array_file -->
<g id="node21" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2189.5404" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2189.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2150.1897,-261.9099C2141.8194,-256.8124 2133.6695,-250.5293 2127.5404,-243 2122.1546,-236.3839 2118.4476,-227.9905 2115.9071,-219.9325"/>
<polygon fill="#000000" stroke="#000000" points="2119.2339,-218.824 2113.2745,-210.064 2112.4704,-220.6283 2119.2339,-218.824"/>
<text text-anchor="middle" x="2219.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="999.5404" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="999.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M998.5173,-173.6401C998.8814,-163.0133 1001.0857,-150.0025 1008.5404,-141 1014.3301,-134.0081 1030.8237,-126.8185 1048.4771,-120.7206"/>
<polygon fill="#000000" stroke="#000000" points="1049.9504,-123.9197 1058.3432,-117.4534 1047.7498,-117.2746 1049.9504,-123.9197"/>
<text text-anchor="middle" x="1076.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node23" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1207.5404" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1207.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1186.2435,-174.1843C1170.616,-161.1114 1149.2247,-143.2167 1132.1127,-128.9019"/>
<polygon fill="#000000" stroke="#000000" points="1134.0159,-125.9308 1124.1,-122.199 1129.5244,-131.2999 1134.0159,-125.9308"/>
<text text-anchor="middle" x="1244.5404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1830.5404" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1830.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1836.2586,-260.6611C1844.2825,-230.8488 1854.575,-172.0849 1822.5404,-141 1796.7343,-115.959 1211.1648,-127.8894 1175.5404,-123 1169.816,-122.2143 1163.8879,-121.1516 1158.0029,-119.933"/>
<polygon fill="#000000" stroke="#000000" points="1158.7039,-116.5035 1148.1835,-117.7563 1157.189,-123.3376 1158.7039,-116.5035"/>
<text text-anchor="middle" x="1888.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1846.1182,-261.5317C1857.3203,-250.1233 1873.4179,-235.9222 1890.5404,-228 1919.3912,-214.6514 2001.8064,-203.6103 2057.1612,-197.412"/>
<polygon fill="#000000" stroke="#000000" points="2057.606,-200.8843 2067.1632,-196.3115 2056.8404,-193.9262 2057.606,-200.8843"/>
<text text-anchor="middle" x="1935.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2700.5404" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2700.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2679.3068,-261.2784C2663.9971,-249.5988 2642.2801,-235.1803 2620.5404,-228 2537.2757,-200.4989 2278.7416,-194.0042 2165.0845,-192.4721"/>
<polygon fill="#000000" stroke="#000000" points="2164.9168,-188.9698 2154.8732,-192.3427 2164.828,-195.9693 2164.9168,-188.9698"/>
<text text-anchor="middle" x="2722.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
</g>
</svg>
</div>
