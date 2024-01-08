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
<svg width="3948pt" height="392pt"
 viewBox="0.00 0.00 3948.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3944.3423,-388 3944.3423,4 -4,4"/>
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1229.25" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1229.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3163.25" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3163.25" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1223.9949,-87.006C1221.9743,-75.9672 1221.8547,-62.387 1230.25,-54 1247.4753,-36.7916 2822.8119,-21.1912 3116.4212,-18.4317"/>
<polygon fill="#000000" stroke="#000000" points="3116.7471,-21.9289 3126.7138,-18.3353 3116.6815,-14.9292 3116.7471,-21.9289"/>
<text text-anchor="middle" x="1278.75" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- therapeutic_procedure -->
<g id="node3" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2874.25" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2874.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2229.25" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2229.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2791.6198,-179.0991C2766.5097,-173.6498 2739.2303,-166.1467 2715.25,-156 2704.0107,-151.2444 2703.8044,-144.9286 2692.25,-141 2622.0216,-117.1215 2413.5485,-108.9706 2301.8458,-106.2746"/>
<polygon fill="#000000" stroke="#000000" points="2301.7531,-102.7716 2291.6743,-106.0377 2301.5901,-109.7697 2301.7531,-102.7716"/>
<text text-anchor="middle" x="2808.25" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1379.25" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1379.25" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1413.341,-267.3619C1421.1314,-264.999 1429.423,-262.7156 1437.25,-261 1497.238,-247.8511 1513.3877,-251.2 1574.25,-243 1680.5198,-228.6823 1717.2284,-257.7297 1813.25,-210 1833.5122,-199.9282 1829.3321,-184.7368 1849.25,-174 1913.1634,-139.5474 1937.8518,-154.1988 2009.25,-141 2061.1518,-131.4053 2120.1896,-121.8167 2164.031,-114.9506"/>
<polygon fill="#000000" stroke="#000000" points="2164.648,-118.3967 2173.9889,-113.3969 2163.5688,-111.4804 2164.648,-118.3967"/>
<text text-anchor="middle" x="1885.75" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1412.25" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1412.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1414.6282,-267.992C1448.3665,-257.4844 1494.0937,-243.2127 1494.25,-243 1498.1976,-237.6278 1497.8954,-233.5817 1494.25,-228 1489.7371,-221.0901 1474.865,-213.7201 1459.0018,-207.46"/>
<polygon fill="#000000" stroke="#000000" points="1460.2096,-204.1749 1449.618,-203.9142 1457.7353,-210.723 1460.2096,-204.1749"/>
<text text-anchor="middle" x="1533.75" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="917.25" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="917.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1345.1636,-267.3406C1337.3729,-264.9788 1329.0801,-262.7013 1321.25,-261 1259.5151,-247.5868 1242.6258,-253.0186 1180.25,-243 1099.0519,-229.9583 1004.553,-210.6022 953.8635,-199.876"/>
<polygon fill="#000000" stroke="#000000" points="954.5385,-196.4414 944.0294,-197.7869 953.0838,-203.2886 954.5385,-196.4414"/>
<text text-anchor="middle" x="1216.75" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="297.25" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="297.25" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M357.5024,-353.4858C368.0577,-351.5013 378.9551,-349.5842 389.25,-348 518.771,-328.0692 551.5268,-324.1864 682.25,-315 823.9568,-305.0417 1181.1123,-320.2687 1321.25,-297 1326.257,-296.1686 1331.4319,-295.0134 1336.5345,-293.6855"/>
<polygon fill="#000000" stroke="#000000" points="1337.5215,-297.0438 1346.1948,-290.9589 1335.62,-290.307 1337.5215,-297.0438"/>
<text text-anchor="middle" x="748.75" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M298.6819,-347.6948C301.6393,-323.5309 310.6792,-281.6431 338.25,-261 379.1288,-230.3927 1133.6794,-201.7332 1352.9596,-194.0227"/>
<polygon fill="#000000" stroke="#000000" points="1353.1206,-197.5193 1362.992,-193.6715 1352.8756,-190.5236 1353.1206,-197.5193"/>
<text text-anchor="middle" x="404.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M215.3296,-362.547C111.7604,-355.2097 -46.3011,-332.3197 13.25,-261 65.9397,-197.8976 113.5814,-237.4 195.25,-228 329.5571,-212.5413 749.1612,-197.605 878.7413,-193.2604"/>
<polygon fill="#000000" stroke="#000000" points="879.0916,-196.7507 888.9694,-192.9193 878.8582,-189.7546 879.0916,-196.7507"/>
<text text-anchor="middle" x="79.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node6" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1037.25" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1037.25" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1057.0049,-348.1168C1071.0628,-336.5232 1090.983,-322.2713 1111.25,-315 1199.4225,-283.366 1229.3175,-314.9869 1321.25,-297 1325.9805,-296.0745 1330.8713,-294.9054 1335.7141,-293.6093"/>
<polygon fill="#000000" stroke="#000000" points="1336.8668,-296.9201 1345.5208,-290.8079 1334.944,-290.1894 1336.8668,-296.9201"/>
<text text-anchor="middle" x="1219.75" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1044.8364,-347.9848C1059.4959,-314.0647 1092.209,-242.7909 1114.25,-228 1133.6759,-214.964 1272.4727,-202.5032 1353.6183,-196.2247"/>
<polygon fill="#000000" stroke="#000000" points="1353.9959,-199.7061 1363.6998,-195.4534 1353.4619,-192.7265 1353.9959,-199.7061"/>
<text text-anchor="middle" x="1195.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge32" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M902.0533,-362.5192C794.7221,-358.3177 659.8207,-349.2449 642.25,-330 611.6838,-296.5214 612.3472,-262.0725 642.25,-228 657.651,-210.4515 807.5779,-198.8288 879.34,-194.2262"/>
<polygon fill="#000000" stroke="#000000" points="879.5746,-197.7184 889.3354,-193.5982 879.1356,-190.7322 879.5746,-197.7184"/>
<text text-anchor="middle" x="731.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2288.7401,-99.4586C2461.7635,-83.3419 2962.3164,-36.7165 3117.0923,-22.2995"/>
<polygon fill="#000000" stroke="#000000" points="3117.5731,-25.7699 3127.2053,-21.3575 3116.9238,-18.8001 3117.5731,-25.7699"/>
<text text-anchor="middle" x="2802.75" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3368.25" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3368.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3341.5175,-88.0966C3323.7681,-77.3604 3299.6889,-63.7087 3277.25,-54 3254.1239,-43.994 3227.2932,-35.3819 3205.4729,-29.092"/>
<polygon fill="#000000" stroke="#000000" points="3206.4062,-25.7188 3195.8313,-26.3689 3204.5035,-32.4552 3206.4062,-25.7188"/>
<text text-anchor="middle" x="3367.25" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge42" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1421.2057,-174.1921C1428.0357,-162.6321 1438.5922,-148.3894 1452.25,-141 1697.4718,-8.3246 1799.2173,-107.8408 2077.25,-87 2479.2416,-56.8674 2965.593,-29.0294 3116.3943,-20.5952"/>
<polygon fill="#000000" stroke="#000000" points="3116.8771,-24.0738 3126.6664,-20.0217 3116.4868,-17.0847 3116.8771,-24.0738"/>
<text text-anchor="middle" x="2117.75" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1405.4211,-210.0034C1400.8656,-222.0133 1394.7901,-238.0307 1389.6395,-251.6093"/>
<polygon fill="#000000" stroke="#000000" points="1386.3617,-250.3822 1386.0876,-260.9735 1392.9067,-252.8649 1386.3617,-250.3822"/>
<text text-anchor="middle" x="1438.75" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1429.5601,-175.1393C1443.0051,-163.2227 1462.7576,-148.1468 1483.25,-141 1545.6339,-119.2433 1981.5419,-109.311 2156.6674,-106.1657"/>
<polygon fill="#000000" stroke="#000000" points="2156.8812,-109.6626 2166.8176,-105.9858 2156.7571,-102.6637 2156.8812,-109.6626"/>
<text text-anchor="middle" x="1523.75" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1335.25" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1335.25" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1332.0327,-347.6878C1331.1122,-337.5755 1331.4297,-325.0636 1336.25,-315 1338.7209,-309.8412 1342.3224,-305.1543 1346.4054,-300.9942"/>
<polygon fill="#000000" stroke="#000000" points="1349.0102,-303.3604 1354.1346,-294.0872 1344.3459,-298.1408 1349.0102,-303.3604"/>
<text text-anchor="middle" x="1427.75" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1423.2663,-354.283C1454.1554,-348.7377 1488.7438,-340.8774 1519.25,-330 1532.5476,-325.2585 1534.2138,-320.4191 1547.25,-315 1572.5652,-304.4766 1589.9362,-319.0333 1606.25,-297 1626.3654,-269.8323 1604.1257,-243.8164 1574.25,-228 1533.1789,-206.2567 1516.449,-220.8008 1471.25,-210 1467.2073,-209.034 1463.0343,-207.9471 1458.8634,-206.7983"/>
<polygon fill="#000000" stroke="#000000" points="1459.7744,-203.4185 1449.1974,-204.0328 1457.8489,-210.1485 1459.7744,-203.4185"/>
<text text-anchor="middle" x="1705.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1244.8067,-354.6761C1177.6574,-346.0323 1095.0843,-334.8147 1079.25,-330 1064.6061,-325.5472 1062.9626,-319.2201 1048.25,-315 1012.5831,-304.7695 907.0327,-324.6153 882.25,-297 861.7898,-274.2013 880.3857,-239.0783 897.3286,-215.8221"/>
<polygon fill="#000000" stroke="#000000" points="900.1384,-217.9095 903.4205,-207.8358 894.5727,-213.664 900.1384,-217.9095"/>
<text text-anchor="middle" x="973.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3534.25" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3534.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3507.4353,-88.3278C3487.6615,-76.8269 3459.7095,-62.1871 3433.25,-54 3357.28,-30.4934 3264.613,-22.3352 3209.9657,-19.5041"/>
<polygon fill="#000000" stroke="#000000" points="3210.0445,-16.0039 3199.8882,-19.0204 3209.7089,-22.9959 3210.0445,-16.0039"/>
<text text-anchor="middle" x="3526.75" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3685.25" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3685.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge37" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3660.2211,-88.4274C3641.0835,-76.6577 3613.5918,-61.6395 3587.25,-54 3517.4936,-33.7696 3304.7558,-23.3782 3209.8322,-19.6464"/>
<polygon fill="#000000" stroke="#000000" points="3209.7947,-16.1425 3199.6673,-19.2547 3209.5251,-23.1373 3209.7947,-16.1425"/>
<text text-anchor="middle" x="3674.25" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3853.25" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3853.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3820.7996,-88.214C3796.3304,-76.4178 3761.5705,-61.4607 3729.25,-54 3630.8826,-31.2935 3326.9396,-21.8649 3209.877,-19.0118"/>
<polygon fill="#000000" stroke="#000000" points="3209.8799,-15.5109 3199.7992,-18.7712 3209.7128,-22.5089 3209.8799,-15.5109"/>
<text text-anchor="middle" x="3843.75" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1986.25" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1986.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1997.4246,-174.0906C2005.4386,-162.7936 2017.2647,-148.8933 2031.25,-141 2053.0518,-128.695 2112.4912,-118.8852 2160.5979,-112.6331"/>
<polygon fill="#000000" stroke="#000000" points="2161.1945,-116.0855 2170.6737,-111.3533 2160.3124,-109.1413 2161.1945,-116.0855"/>
<text text-anchor="middle" x="2075.75" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- follow_up -->
<g id="node15" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2114.25" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2114.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2117.104,-173.9091C2119.6641,-163.1121 2124.4403,-149.8287 2133.25,-141 2142.8683,-131.361 2155.3108,-124.268 2168.0307,-119.0602"/>
<polygon fill="#000000" stroke="#000000" points="2169.6192,-122.2036 2177.7696,-115.4343 2167.1768,-115.6435 2169.6192,-122.2036"/>
<text text-anchor="middle" x="2178.25" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2261.25" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2261.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2242.0704,-174.596C2237.3158,-169.1518 2232.8425,-162.7793 2230.25,-156 2227.541,-148.9161 2226.5326,-140.8642 2226.3901,-133.2849"/>
<polygon fill="#000000" stroke="#000000" points="2229.8958,-133.1292 2226.6783,-123.0347 2222.8985,-132.9324 2229.8958,-133.1292"/>
<text text-anchor="middle" x="2289.25" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pathology_file -->
<g id="node17" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="474.25" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="474.25" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M543.9716,-358.8135C613.6642,-351.6091 723.8875,-340.1581 819.25,-330 880.5975,-323.4652 895.747,-319.859 957.25,-315 1118.7223,-302.243 1161.7531,-325.2276 1321.25,-297 1326.0581,-296.1491 1331.0248,-295.0169 1335.9352,-293.7331"/>
<polygon fill="#000000" stroke="#000000" points="1337.1957,-297.0141 1345.867,-290.9266 1335.2921,-290.2779 1337.1957,-297.0141"/>
<text text-anchor="middle" x="1018.25" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M471.7139,-347.612C469.5739,-323.7525 470.0247,-282.6272 494.25,-261 498.2806,-257.4016 1151.2343,-210.5984 1353.3334,-196.1914"/>
<polygon fill="#000000" stroke="#000000" points="1353.7346,-199.6718 1363.4605,-195.4697 1353.2369,-192.6895 1353.7346,-199.6718"/>
<text text-anchor="middle" x="555.25" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M417.437,-353.8654C326.5022,-334.4113 158.2811,-298.2798 157.25,-297 147.2112,-284.5411 146.4599,-272.8141 157.25,-261 206.3351,-207.2566 731.1589,-194.9372 878.8034,-192.5259"/>
<polygon fill="#000000" stroke="#000000" points="879.2222,-196.0198 889.1659,-192.363 879.1121,-189.0207 879.2222,-196.0198"/>
<text text-anchor="middle" x="218.25" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M944.6356,-187.7078C1007.4319,-177.7202 1166.5368,-151.587 1298.25,-123 1361.8763,-109.1905 1375.8176,-96.3533 1440.25,-87 1777.2427,-38.0806 2875.9367,-21.6166 3116.4488,-18.5564"/>
<polygon fill="#000000" stroke="#000000" points="3116.6458,-22.0543 3126.6009,-18.4288 3116.5577,-15.0549 3116.6458,-22.0543"/>
<text text-anchor="middle" x="1464.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M945.0807,-193.9016C1015.2956,-198.8664 1198.2387,-212.8866 1257.25,-228 1286.7644,-235.559 1318.4655,-248.9871 1342.1539,-260.1676"/>
<polygon fill="#000000" stroke="#000000" points="1340.9328,-263.4638 1351.4622,-264.6396 1343.9642,-257.1542 1340.9328,-263.4638"/>
<text text-anchor="middle" x="1326.25" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2362.25" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2362.25" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2413.9278,-363.7394C2605.3786,-355.0289 3263.25,-321.971 3263.25,-279 3263.25,-279 3263.25,-279 3263.25,-105 3263.25,-70.9901 3229.9206,-47.2526 3201.745,-33.2619"/>
<polygon fill="#000000" stroke="#000000" points="3202.982,-29.976 3192.4429,-28.8901 3200.0045,-36.3112 3202.982,-29.976"/>
<text text-anchor="middle" x="3305.75" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2311.5416,-361.8213C2201.8833,-352.8315 1934.4779,-331.1612 1710.25,-315 1588.9678,-306.2586 1556.808,-319.1736 1437.25,-297 1432.449,-296.1096 1427.4869,-294.9523 1422.5791,-293.6537"/>
<polygon fill="#000000" stroke="#000000" points="1423.2264,-290.1991 1412.6504,-290.8302 1421.3116,-296.9321 1423.2264,-290.1991"/>
<text text-anchor="middle" x="1950.75" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2367.3501,-347.8472C2377.8604,-306.2096 2397.0758,-202.6815 2348.25,-141 2340.6513,-131.4007 2316.4197,-123.2397 2291.7883,-117.1273"/>
<polygon fill="#000000" stroke="#000000" points="2292.5342,-113.7072 2281.9962,-114.8029 2290.9175,-120.518 2292.5342,-113.7072"/>
<text text-anchor="middle" x="2422.75" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node20" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2475.25" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2475.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2442.8309,-175.3473C2431.0003,-169.265 2417.5169,-162.3268 2405.25,-156 2392.3533,-149.3484 2389.8371,-146.095 2376.25,-141 2349.1991,-130.8563 2318.2675,-122.7851 2291.7789,-116.8773"/>
<polygon fill="#000000" stroke="#000000" points="2292.3774,-113.4257 2281.8618,-114.7192 2290.8889,-120.2656 2292.3774,-113.4257"/>
<text text-anchor="middle" x="2473.25" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- molecular_test -->
<g id="node21" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2658.25" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2658.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2613.4148,-177.0363C2597.5643,-171.1734 2579.816,-163.9427 2564.25,-156 2553.3794,-150.4531 2552.7291,-145.1433 2541.25,-141 2498.4244,-125.5425 2378.6981,-114.9322 2300.6285,-109.4231"/>
<polygon fill="#000000" stroke="#000000" points="2300.5939,-105.9123 2290.3757,-108.7119 2300.1095,-112.8956 2300.5939,-105.9123"/>
<text text-anchor="middle" x="2628.25" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3118.25" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3118.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3112.3756,-173.6075C3108.6469,-163.4701 3103.2087,-150.9598 3096.25,-141 3089.5878,-131.4646 3081.8462,-133.6857 3077.25,-123 3070.9279,-108.302 3070.3292,-101.4258 3077.25,-87 3087.9004,-64.8003 3109.5598,-47.4894 3128.4764,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="3130.37,-38.7057 3137.2029,-30.6086 3126.812,-32.6774 3130.37,-38.7057"/>
<text text-anchor="middle" x="3163.25" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3041.4426,-179.2225C2992.1542,-170.7668 2935.3612,-160.4469 2924.25,-156 2912.9197,-151.4654 2912.8508,-144.7893 2901.25,-141 2845.5209,-122.7968 2464.0746,-111.0075 2301.9303,-106.7647"/>
<polygon fill="#000000" stroke="#000000" points="2301.6605,-103.2566 2291.5731,-106.4961 2301.479,-110.2543 2301.6605,-103.2566"/>
<text text-anchor="middle" x="3010.25" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- exposure -->
<g id="node23" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1533.25" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1533.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1547.4839,-174.4589C1558.1615,-162.7019 1573.8791,-148.1163 1591.25,-141 1642.3676,-120.0586 2000.1368,-109.9115 2156.452,-106.4385"/>
<polygon fill="#000000" stroke="#000000" points="2156.9808,-109.9278 2166.9017,-106.2096 2156.8274,-102.9295 2156.9808,-109.9278"/>
<text text-anchor="middle" x="1634.75" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1832.25" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1832.25" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1749.7245,-358.9405C1697.0493,-353.4169 1627.5758,-344.2387 1567.25,-330 1547.1418,-325.2539 1543.1762,-320.4598 1523.25,-315 1485.5877,-304.6805 1475.0512,-306.7982 1437.25,-297 1432.8247,-295.853 1428.2347,-294.5781 1423.6626,-293.2517"/>
<polygon fill="#000000" stroke="#000000" points="1424.3364,-289.8003 1413.7531,-290.2949 1422.3349,-296.5081 1424.3364,-289.8003"/>
<text text-anchor="middle" x="1638.75" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1840.915,-347.7786C1844.4282,-337.9213 1846.8951,-325.6237 1843.25,-315 1833.3826,-286.241 1827.3931,-276.5236 1801.25,-261 1673.6433,-185.2278 1616.1481,-242.0845 1471.25,-210 1467.133,-209.0884 1462.8867,-208.0314 1458.6482,-206.8952"/>
<polygon fill="#000000" stroke="#000000" points="1459.4117,-203.4742 1448.8373,-204.1319 1457.5139,-210.212 1459.4117,-203.4742"/>
<text text-anchor="middle" x="1908.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1832.3016,-347.7907C1831.2802,-336.5185 1827.9155,-322.7602 1818.25,-315 1787.1066,-289.9957 1494.5139,-315.7504 1459.25,-297 1441.5911,-287.6105 1448.0035,-273.3218 1432.25,-261 1428.5438,-258.1012 1358.819,-229.124 1354.25,-228 1279.0557,-209.5016 1047.3852,-197.6687 955.4334,-193.5899"/>
<polygon fill="#000000" stroke="#000000" points="955.33,-190.0821 945.1867,-193.1419 955.0242,-197.0754 955.33,-190.0821"/>
<text text-anchor="middle" x="1530.75" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- family_relationship -->
<g id="node25" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1704.25" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1704.25" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1689.7107,-174.0643C1682.8312,-163.3257 1677.7809,-150.0492 1686.25,-141 1702.0901,-124.0749 2012.8754,-111.9398 2156.9925,-107.1996"/>
<polygon fill="#000000" stroke="#000000" points="2157.1938,-110.695 2167.0745,-106.8711 2156.9658,-103.6987 2157.1938,-110.695"/>
<text text-anchor="middle" x="1765.75" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
