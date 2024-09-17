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
<svg width="2642pt" height="305pt"
 viewBox="0.00 0.00 2642.13 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2638.1271,-301 2638.1271,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="273.0349" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="273.0349" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1894.0349" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1894.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M324.715,-276.499C482.9045,-268.8702 974.5222,-245.3605 1382.0349,-228 1484.0208,-223.6553 1740.6665,-228.6062 1841.0349,-210 1844.6896,-209.3225 1848.4353,-208.4456 1852.1634,-207.444"/>
<polygon fill="#000000" stroke="#000000" points="1853.3228,-210.751 1861.9156,-204.5529 1851.3332,-204.0397 1853.3228,-210.751"/>
<text text-anchor="middle" x="1424.5349" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node18" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1069.0349" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1069.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M270.7227,-260.7006C268.8723,-237.3224 269.5802,-197.1259 292.0349,-174 341.4026,-123.1566 377.7948,-150.4107 448.0349,-141 552.1324,-127.0531 856.5403,-113.5174 996.7747,-107.8194"/>
<polygon fill="#000000" stroke="#000000" points="997.1383,-111.3077 1006.9887,-107.4065 996.8555,-104.3134 997.1383,-111.3077"/>
<text text-anchor="middle" x="334.5349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1899.0349" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1899.0349" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M223.5475,-273.1841C154.8033,-263.9711 35.9136,-243.5441 10.0349,-210 -9.1348,-185.1522 3.0963,-163.4408 25.0349,-141 87.7095,-76.8906 119.7587,-74.5182 207.0349,-54 289.2396,-34.6741 1588.6919,-21.0229 1852.5192,-18.4428"/>
<polygon fill="#000000" stroke="#000000" points="1852.5678,-21.9426 1862.5332,-18.3453 1852.4996,-14.9429 1852.5678,-21.9426"/>
<text text-anchor="middle" x="67.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="574.0349" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="574.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M594.0801,-174.6274C608.7966,-162.9498 629.838,-148.3899 651.0349,-141 712.8747,-119.4406 894.0866,-110.4064 996.4545,-106.9389"/>
<polygon fill="#000000" stroke="#000000" points="996.8352,-110.4283 1006.7145,-106.601 996.6047,-103.4321 996.8352,-110.4283"/>
<text text-anchor="middle" x="710.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1549.0349" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1549.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1497.4631,-176.242C1481.3061,-170.6149 1463.6298,-163.7294 1448.0349,-156 1437.1002,-150.5804 1436.5429,-145.0623 1425.0349,-141 1374.3928,-123.1235 1229.7608,-112.9726 1141.2032,-108.2662"/>
<polygon fill="#000000" stroke="#000000" points="1141.1258,-104.7575 1130.9572,-107.7326 1140.7617,-111.748 1141.1258,-104.7575"/>
<text text-anchor="middle" x="1531.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1836.0349" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1836.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge25" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1833.1238,-86.7831C1832.4035,-76.4607 1833.1535,-63.7107 1839.0349,-54 1844.1726,-45.517 1852.1356,-38.7833 1860.5993,-33.5459"/>
<polygon fill="#000000" stroke="#000000" points="1862.4479,-36.5232 1869.5032,-28.6191 1859.0588,-30.3983 1862.4479,-36.5232"/>
<text text-anchor="middle" x="1890.0349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- molecular_test -->
<g id="node5" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1752.0349" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1752.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1698.4993,-178.5572C1678.7301,-172.7395 1656.4302,-165.1461 1637.0349,-156 1625.9966,-150.7947 1625.6119,-144.8613 1614.0349,-141 1570.3485,-126.4291 1279.1308,-113.242 1141.2125,-107.729"/>
<polygon fill="#000000" stroke="#000000" points="1141.2836,-104.2291 1131.1526,-107.3296 1141.0058,-111.2236 1141.2836,-104.2291"/>
<text text-anchor="middle" x="1701.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2083.0349" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2083.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1935.3536,-185.2843C1973.3186,-178.5461 2026.3001,-167.537 2044.0349,-156 2053.8059,-149.6436 2062.1021,-139.9697 2068.4979,-130.7494"/>
<polygon fill="#000000" stroke="#000000" points="2071.552,-132.4716 2074.0337,-122.1715 2065.6705,-128.6759 2071.552,-132.4716"/>
<text text-anchor="middle" x="2095.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1706.0349" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1706.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1928.9576,-180.6556C1952.403,-171.2602 1976.5636,-156.9094 1962.0349,-141 1947.1382,-124.6877 1785.7035,-127.2976 1764.0349,-123 1759.9628,-122.1924 1755.7712,-121.2074 1751.5933,-120.1186"/>
<polygon fill="#000000" stroke="#000000" points="1752.5048,-116.7393 1741.9321,-117.4247 1750.6246,-123.4821 1752.5048,-116.7393"/>
<text text-anchor="middle" x="2003.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1860.1426,-180.3684C1853.8008,-178.2264 1847.222,-176.0273 1841.0349,-174 1815.7891,-165.7279 1807.5117,-168.4345 1784.0349,-156 1774.5272,-150.9643 1775.1041,-144.7899 1765.0349,-141 1707.8779,-119.487 1307.9711,-109.5154 1141.4941,-106.2615"/>
<polygon fill="#000000" stroke="#000000" points="1141.4153,-102.7594 1131.3497,-106.0659 1141.2803,-109.7581 1141.4153,-102.7594"/>
<text text-anchor="middle" x="1820.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2166.0349" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2166.0349" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2147.3212,-261.4098C2134.2264,-250.0993 2115.7836,-236.06 2097.0349,-228 2070.655,-216.6594 1997.6021,-205.393 1946.7424,-198.5625"/>
<polygon fill="#000000" stroke="#000000" points="1946.9421,-195.0585 1936.5692,-197.2154 1946.0231,-201.9979 1946.9421,-195.0585"/>
<text text-anchor="middle" x="2184.0349" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2106.7265,-114.6981C2117.7515,-120.5569 2129.7875,-129.2043 2136.0349,-141 2139.1551,-146.8914 2140.3883,-150.951 2136.0349,-156 2123.8986,-170.0753 2015.2494,-181.7311 1947.7227,-187.6971"/>
<polygon fill="#000000" stroke="#000000" points="1947.3267,-184.2182 1937.667,-188.5704 1947.9324,-191.1919 1947.3267,-184.2182"/>
<text text-anchor="middle" x="2162.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2077.2111,-87.3478C2072.6282,-76.1593 2065.1375,-62.2835 2054.0349,-54 2036.8738,-41.1964 1983.6678,-30.6994 1944.3586,-24.4098"/>
<polygon fill="#000000" stroke="#000000" points="1944.8617,-20.946 1934.442,-22.8642 1943.7837,-27.8625 1944.8617,-20.946"/>
<text text-anchor="middle" x="2090.0349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1636.0349" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1636.0349" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1652.5214,-261.597C1664.5397,-250.0635 1681.8446,-235.6886 1700.0349,-228 1758.2255,-203.4041 1779.483,-224.2294 1841.0349,-210 1844.4522,-209.21 1847.9594,-208.2849 1851.4633,-207.2786"/>
<polygon fill="#000000" stroke="#000000" points="1852.7201,-210.5541 1861.2517,-204.2721 1850.6648,-203.8626 1852.7201,-210.5541"/>
<text text-anchor="middle" x="1744.5349" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1597.0469,-266.2623C1589.1752,-264.145 1580.9006,-262.2381 1573.0349,-261 1456.6225,-242.6761 1160.773,-248.0344 1043.0349,-243 971.8943,-239.9581 452.0713,-261.63 403.0349,-210 341.9676,-145.7029 400.2976,-166.3663 618.0349,-141 751.7569,-125.4214 908.5803,-114.5661 997.6318,-109.0925"/>
<polygon fill="#000000" stroke="#000000" points="997.8522,-112.5857 1007.6207,-108.4837 997.4262,-105.5986 997.8522,-112.5857"/>
<text text-anchor="middle" x="447.5349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1977.0349" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1977.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1966.0382,-87.1944C1959.3726,-77.0092 1950.3726,-64.2592 1941.0349,-54 1936.6229,-49.1527 1931.5782,-44.3312 1926.5517,-39.8664"/>
<polygon fill="#000000" stroke="#000000" points="1928.6325,-37.0402 1918.7615,-33.1912 1924.0778,-42.3557 1928.6325,-37.0402"/>
<text text-anchor="middle" x="2001.5349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1448.0349" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1448.0349" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1456.9089,-261.038C1463.7025,-249.4092 1474.249,-235.1477 1488.0349,-228 1557.7659,-191.846 1763.8898,-224.7704 1841.0349,-210 1844.6855,-209.301 1848.4285,-208.4091 1852.1546,-207.3975"/>
<polygon fill="#000000" stroke="#000000" points="1853.3209,-210.702 1861.9038,-204.4903 1851.3206,-203.9939 1853.3209,-210.702"/>
<text text-anchor="middle" x="1579.5349" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="719.0349" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="719.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M741.1614,-175.4935C757.8447,-163.9174 781.7593,-149.1132 805.0349,-141 839.7591,-128.8961 933.1834,-117.9407 998.9998,-111.3761"/>
<polygon fill="#000000" stroke="#000000" points="999.7038,-114.8238 1009.3127,-110.3607 999.0178,-107.8575 999.7038,-114.8238"/>
<text text-anchor="middle" x="848.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="890.0349" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="890.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M890.9118,-173.5424C892.4149,-162.6075 896.1245,-149.3078 905.0349,-141 919.0775,-127.907 962.0918,-118.7565 1000.5441,-112.9578"/>
<polygon fill="#000000" stroke="#000000" points="1001.3247,-116.3813 1010.7193,-111.4831 1000.3207,-109.4537 1001.3247,-116.3813"/>
<text text-anchor="middle" x="984.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="128.0349" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="128.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M122.748,-173.567C120.8365,-162.6413 120.8465,-149.3427 129.0349,-141 144.1932,-125.5559 778.9473,-111.0015 996.648,-106.4556"/>
<polygon fill="#000000" stroke="#000000" points="996.7703,-109.9539 1006.6954,-106.2467 996.6247,-102.9554 996.7703,-109.9539"/>
<text text-anchor="middle" x="215.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M118.0683,-173.8225C113.6136,-162.993 110.9687,-149.7057 119.0349,-141 333.2174,90.1654 511.6741,-109.1121 826.0349,-87 1223.3664,-59.0518 1703.7945,-29.7567 1852.7528,-20.7768"/>
<polygon fill="#000000" stroke="#000000" points="1853.1278,-24.2607 1862.8992,-20.1657 1852.7069,-17.2733 1853.1278,-24.2607"/>
<text text-anchor="middle" x="912.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1066.0349" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1066.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1066.6565,-173.9735C1067.0627,-162.1918 1067.6017,-146.5607 1068.0639,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1071.5673,-133.1181 1068.414,-123.0034 1064.5714,-132.8768 1071.5673,-133.1181"/>
<text text-anchor="middle" x="1115.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cytogenomic_file -->
<g id="node16" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1798.0349" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1798.0349" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1793.2701,-260.9731C1791.581,-250.4644 1791.4786,-237.4607 1798.0349,-228 1799.7299,-225.5541 1825.8569,-215.8377 1850.4246,-207.1153"/>
<polygon fill="#000000" stroke="#000000" points="1851.7994,-210.3418 1860.0649,-203.7137 1849.4701,-203.7407 1851.7994,-210.3418"/>
<text text-anchor="middle" x="1869.5349" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1742.6711,-117.0826C1749.7199,-119.2045 1757.0747,-121.2805 1764.0349,-123 1806.6022,-133.5162 1824.6002,-116.6057 1861.0349,-141 1869.8803,-146.9223 1876.8807,-156.103 1882.1159,-165.0519"/>
<polygon fill="#000000" stroke="#000000" points="1879.1607,-166.9503 1886.9358,-174.1475 1885.3459,-163.6726 1879.1607,-166.9503"/>
<text text-anchor="middle" x="1917.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1716.6864,-87.3401C1724.3332,-76.1484 1735.6312,-62.2718 1749.0349,-54 1766.4817,-43.233 1816.7126,-32.4681 1854.2728,-25.554"/>
<polygon fill="#000000" stroke="#000000" points="1855.2738,-28.93 1864.493,-23.7092 1854.0302,-22.0413 1855.2738,-28.93"/>
<text text-anchor="middle" x="1789.5349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1127.7295,-98.8477C1284.7927,-82.3844 1712.309,-37.5725 1853.27,-22.797"/>
<polygon fill="#000000" stroke="#000000" points="1853.725,-26.2686 1863.3056,-21.7451 1852.9952,-19.3068 1853.725,-26.2686"/>
<text text-anchor="middle" x="1584.5349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node19" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2206.0349" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2206.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2181.8022,-87.7217C2164.7542,-76.398 2140.9746,-62.2202 2118.0349,-54 2060.6593,-33.4401 1990.5764,-24.5433 1945.3946,-20.7462"/>
<polygon fill="#000000" stroke="#000000" points="1945.5521,-17.2478 1935.3073,-19.9486 1945.0003,-24.226 1945.5521,-17.2478"/>
<text text-anchor="middle" x="2210.0349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node20" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1227.0349" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1227.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1208.3481,-174.2069C1196.3885,-163.522 1180.1421,-150.2518 1164.0349,-141 1150.987,-133.5055 1136.0852,-127.0081 1122.0142,-121.6755"/>
<polygon fill="#000000" stroke="#000000" points="1123.0322,-118.3211 1112.4384,-118.1718 1120.6269,-124.8949 1123.0322,-118.3211"/>
<text text-anchor="middle" x="1255.0349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node22" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1378.0349" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1378.0349" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1364.0933,-174.4048C1353.9757,-162.9397 1339.261,-148.7231 1323.0349,-141 1291.4945,-125.9878 1203.2448,-115.8567 1139.6219,-110.2613"/>
<polygon fill="#000000" stroke="#000000" points="1139.898,-106.7722 1129.6348,-109.4021 1139.298,-113.7464 1139.898,-106.7722"/>
<text text-anchor="middle" x="1385.5349" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2372.0349" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2372.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2346.7511,-88.0053C2328.0547,-76.3483 2301.5205,-61.6544 2276.0349,-54 2215.2974,-35.7581 2032.0236,-24.5665 1945.3762,-20.158"/>
<polygon fill="#000000" stroke="#000000" points="1945.4657,-16.6582 1935.3032,-19.654 1945.1158,-23.6495 1945.4657,-16.6582"/>
<text text-anchor="middle" x="2367.5349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_personnel -->
<g id="node24" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2547.0349" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2547.0349" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2515.7175,-88.1144C2492.2843,-76.3498 2459.0645,-61.4758 2428.0349,-54 2337.113,-32.0946 2057.251,-22.2829 1945.6661,-19.1672"/>
<polygon fill="#000000" stroke="#000000" points="1945.4969,-15.6613 1935.4048,-18.8864 1945.3053,-22.6587 1945.4969,-15.6613"/>
<text text-anchor="middle" x="2540.5349" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node25" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1989.0349" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1989.0349" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1975.3492,-261.0432C1967.1206,-250.8076 1956.1206,-238.0576 1945.0349,-228 1939.3509,-222.8433 1932.9093,-217.7849 1926.564,-213.1649"/>
<polygon fill="#000000" stroke="#000000" points="1928.2423,-210.066 1918.0513,-207.1688 1924.2113,-215.7889 1928.2423,-210.066"/>
<text text-anchor="middle" x="2026.5349" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
