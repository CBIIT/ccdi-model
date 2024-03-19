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
<svg width="2661pt" height="305pt"
 viewBox="0.00 0.00 2661.11 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2657.1125,-301 2657.1125,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="128.0681" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="128.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1949.0681" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1949.0681" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M118.1166,-173.8364C113.6676,-163.0122 111.0234,-149.7255 119.0681,-141 289.3352,43.6762 995.3481,-69.353 1246.0681,-54 1493.2885,-38.8613 1789.687,-25.1291 1902.4445,-20.0649"/>
<polygon fill="#000000" stroke="#000000" points="1902.6276,-23.5603 1912.4609,-19.6161 1902.3142,-16.5673 1902.6276,-23.5603"/>
<text text-anchor="middle" x="281.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node25" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1185.0681" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1185.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M122.812,-174.0051C120.791,-162.9659 120.6714,-149.3856 129.0681,-141 148.4116,-121.6819 1085.9667,-126.5882 1113.0681,-123 1118.8779,-122.2308 1124.8961,-121.1667 1130.8652,-119.9368"/>
<polygon fill="#000000" stroke="#000000" points="1131.812,-123.312 1140.8191,-117.7331 1130.2989,-116.4775 1131.812,-123.312"/>
<text text-anchor="middle" x="215.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="982.0681" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="982.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M991.7519,-173.9155C998.7056,-162.6946 1009.1212,-148.9465 1022.0681,-141 1057.2055,-119.4335 1072.8349,-132.0024 1113.0681,-123 1118.0485,-121.8856 1123.2113,-120.6851 1128.381,-119.4519"/>
<polygon fill="#000000" stroke="#000000" points="1129.3892,-122.809 1138.2847,-117.054 1127.7419,-116.0056 1129.3892,-122.809"/>
<text text-anchor="middle" x="1101.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="860.0681" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="860.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1803.0681" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1803.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M886.6351,-261.4418C906.2889,-249.5121 934.1994,-234.7236 961.0681,-228 1131.201,-185.4259 1577.371,-240.553 1750.0681,-210 1753.779,-209.3435 1757.582,-208.4728 1761.3638,-207.4679"/>
<polygon fill="#000000" stroke="#000000" points="1762.6483,-210.738 1771.2477,-204.5493 1760.6659,-204.0246 1762.6483,-210.738"/>
<text text-anchor="middle" x="1052.5681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1990.0681" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1990.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1832.284,-205.7198C1844.8343,-211.9981 1859.4786,-219.8488 1872.0681,-228 1881.0992,-233.8473 1881.6706,-237.7616 1891.0681,-243 1910.9287,-254.0709 1934.8488,-262.8796 1954.201,-269.0121"/>
<polygon fill="#000000" stroke="#000000" points="1953.2722,-272.3881 1963.8589,-271.9729 1955.324,-265.6955 1953.2722,-272.3881"/>
<text text-anchor="middle" x="1927.5681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node11" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1901.0681" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1901.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1817.4683,-174.6022C1826.3683,-164.3165 1838.3046,-151.3263 1850.0681,-141 1855.7237,-136.0354 1862.0634,-131.1154 1868.2999,-126.5811"/>
<polygon fill="#000000" stroke="#000000" points="1870.5195,-129.2984 1876.6665,-120.669 1866.4799,-123.5816 1870.5195,-129.2984"/>
<text text-anchor="middle" x="1886.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1782.8622,-175.9196C1764.8452,-161.7366 1740.5002,-143.0102 1735.0681,-141 1691.4016,-124.8409 1396.2252,-112.4439 1257.21,-107.4288"/>
<polygon fill="#000000" stroke="#000000" points="1257.192,-103.926 1247.0732,-107.0662 1256.9417,-110.9215 1257.192,-103.926"/>
<text text-anchor="middle" x="1791.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1034.0681" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1034.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1085.5471,-92.5551C1094.998,-90.5163 1104.8031,-88.5629 1114.0681,-87 1411.5751,-36.8134 1775.1387,-22.6556 1902.4115,-19.0895"/>
<polygon fill="#000000" stroke="#000000" points="1902.6772,-22.5836 1912.5784,-18.8132 1902.487,-15.5862 1902.6772,-22.5836"/>
<text text-anchor="middle" x="1398.5681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1986.6354,-260.89C1983.6007,-249.8049 1978.0404,-236.2168 1968.0681,-228 1951.0832,-214.0052 1897.2782,-204.0442 1855.6775,-198.1985"/>
<polygon fill="#000000" stroke="#000000" points="1856.0442,-194.7163 1845.6637,-196.8366 1855.1007,-201.6524 1856.0442,-194.7163"/>
<text text-anchor="middle" x="2003.0681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2010.6705,-266.4905C2018.5964,-260.4739 2026.7706,-252.4923 2031.0681,-243 2033.8176,-236.9267 2031.6735,-234.6391 2031.0681,-228 2027.4978,-188.8473 2025.4472,-178.9203 2015.0681,-141 2004.1915,-101.2623 2004.7654,-89.023 1983.0681,-54 1980.4337,-49.7476 1977.2403,-45.5685 1973.8781,-41.649"/>
<polygon fill="#000000" stroke="#000000" points="1976.2119,-39.0163 1966.8649,-34.0279 1971.061,-43.7564 1976.2119,-39.0163"/>
<text text-anchor="middle" x="2042.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1070.0681" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1070.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1101.1412,-262.2895C1125.2014,-250.2825 1159.7651,-235.0237 1192.0681,-228 1313.2999,-201.6402 1628.0041,-232.1897 1750.0681,-210 1753.7759,-209.326 1757.5766,-208.4431 1761.357,-207.4301"/>
<polygon fill="#000000" stroke="#000000" points="1762.647,-210.6982 1771.2387,-204.4987 1760.6562,-203.9873 1762.647,-210.6982"/>
<text text-anchor="middle" x="1253.0681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node8" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1254.0681" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1254.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1280.9702,-261.6287C1300.8535,-249.7894 1329.0524,-235.0322 1356.0681,-228 1525.7088,-183.8422 1577.8149,-242.5077 1750.0681,-210 1753.7206,-209.3107 1757.4648,-208.4255 1761.1918,-207.4184"/>
<polygon fill="#000000" stroke="#000000" points="1762.355,-210.7241 1770.9424,-204.5185 1760.3595,-204.0145 1762.355,-210.7241"/>
<text text-anchor="middle" x="1427.5681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1508.0681" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1508.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1497.0458,-174.3539C1488.8685,-162.8661 1476.6399,-148.6432 1462.0681,-141 1427.4801,-122.858 1326.7521,-113.2936 1256.8099,-108.6952"/>
<polygon fill="#000000" stroke="#000000" points="1256.9279,-105.1957 1246.7255,-108.0523 1256.4826,-112.1815 1256.9279,-105.1957"/>
<text text-anchor="middle" x="1526.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- molecular_test -->
<g id="node10" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1661.0681" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1661.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1635.0021,-174.8103C1614.4844,-161.6123 1587.3692,-144.9901 1575.0681,-141 1517.8116,-122.4278 1353.2125,-112.3255 1257.1325,-107.8608"/>
<polygon fill="#000000" stroke="#000000" points="1257.0602,-104.354 1246.9113,-107.3951 1256.7415,-111.3468 1257.0602,-104.354"/>
<text text-anchor="middle" x="1667.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1919.0037,-121.9216C1927.787,-132.2784 1934.9458,-145.5099 1927.0681,-156 1918.0278,-168.0381 1884.3389,-177.3542 1854.355,-183.4908"/>
<polygon fill="#000000" stroke="#000000" points="1853.5089,-180.09 1844.3695,-185.4493 1854.8562,-186.9591 1853.5089,-180.09"/>
<text text-anchor="middle" x="1970.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge15" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1897.6828,-86.605C1896.7097,-76.4669 1897.0307,-63.9566 1902.0681,-54 1905.248,-47.7148 1910.0935,-42.2148 1915.4851,-37.53"/>
<polygon fill="#000000" stroke="#000000" points="1917.8526,-40.1246 1923.6446,-31.2531 1913.5844,-34.5764 1917.8526,-40.1246"/>
<text text-anchor="middle" x="1942.5681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_arm -->
<g id="node12" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2085.0681" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2085.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2061.7181,-88.2208C2047.3066,-78.0377 2028.3339,-64.9394 2011.0681,-54 2001.8255,-48.144 1991.6199,-42.0649 1982.2024,-36.6064"/>
<polygon fill="#000000" stroke="#000000" points="1983.8863,-33.5374 1973.4719,-31.5906 1980.3992,-39.607 1983.8863,-33.5374"/>
<text text-anchor="middle" x="2081.5681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="429.0681" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="429.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M460.262,-177.2857C487.9048,-165.0477 529.7169,-148.4686 568.0681,-141 805.9535,-94.6734 873.0512,-156.5782 1113.0681,-123 1118.7903,-122.1995 1124.7171,-121.1271 1130.6013,-119.9026"/>
<polygon fill="#000000" stroke="#000000" points="1131.4179,-123.3066 1140.4199,-117.7195 1129.8986,-116.4734 1131.4179,-123.3066"/>
<text text-anchor="middle" x="611.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node14" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1499.0681" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1499.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1499.0838,-260.8735C1500.1329,-249.6353 1503.5031,-235.8838 1513.0681,-228 1553.826,-194.4059 1698.3194,-220.5763 1750.0681,-210 1753.7098,-209.2557 1757.4464,-208.332 1761.1684,-207.2991"/>
<polygon fill="#000000" stroke="#000000" points="1762.349,-210.5988 1770.9108,-204.3581 1760.326,-203.8974 1762.349,-210.5988"/>
<text text-anchor="middle" x="1621.5681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node15" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2250.0681" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2250.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2217.319,-88.2599C2194.487,-77.1765 2163.0423,-63.0646 2134.0681,-54 2087.5409,-39.4439 2032.5073,-29.637 1994.6287,-23.9818"/>
<polygon fill="#000000" stroke="#000000" points="1994.8211,-20.473 1984.4212,-22.4963 1993.8129,-27.4 1994.8211,-20.473"/>
<text text-anchor="middle" x="2242.5681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1738.0681" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1738.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1734.2043,-260.7963C1732.9997,-250.4784 1733.2497,-237.7284 1739.0681,-228 1743.9215,-219.885 1751.335,-213.4503 1759.4178,-208.4035"/>
<polygon fill="#000000" stroke="#000000" points="1761.304,-211.36 1768.3616,-203.458 1757.9167,-205.2341 1761.304,-211.36"/>
<text text-anchor="middle" x="1805.5681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node18" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="618.0681" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="618.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M634.976,-174.1029C647.3268,-162.3428 665.1596,-147.9002 684.0681,-141 773.7033,-108.2896 1018.631,-136.6413 1113.0681,-123 1118.7867,-122.174 1124.7112,-121.085 1130.5939,-119.8505"/>
<polygon fill="#000000" stroke="#000000" points="1131.4151,-123.2534 1140.4109,-117.6565 1129.8883,-116.422 1131.4151,-123.2534"/>
<text text-anchor="middle" x="777.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- follow_up -->
<g id="node19" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="809.0681" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="809.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M834.3901,-175.9666C854.3937,-164.152 883.4488,-148.8304 911.0681,-141 997.7839,-116.4152 1024.1874,-137.9759 1113.0681,-123 1118.468,-122.0902 1124.0593,-120.9863 1129.6297,-119.7779"/>
<polygon fill="#000000" stroke="#000000" points="1130.6153,-123.1432 1139.588,-117.5093 1129.0604,-116.318 1130.6153,-123.1432"/>
<text text-anchor="middle" x="956.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="273.0681" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="273.0681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M322.5996,-273.3161C420.4009,-262.3569 645.2938,-238.4642 835.0681,-228 936.6002,-222.4015 1649.909,-227.5577 1750.0681,-210 1753.7801,-209.3493 1757.5837,-208.4827 1761.366,-207.4804"/>
<polygon fill="#000000" stroke="#000000" points="1762.6487,-210.7513 1771.2507,-204.5661 1760.6691,-204.037 1762.6487,-210.7513"/>
<text text-anchor="middle" x="877.5681" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M223.5808,-273.1841C154.8365,-263.9711 35.9469,-243.5441 10.0681,-210 -9.1016,-185.1522 2.9777,-163.2913 25.0681,-141 101.1206,-64.2557 145.3201,-70.6899 252.0681,-54 418.8043,-27.931 1645.9437,-19.6908 1902.2328,-18.2458"/>
<polygon fill="#000000" stroke="#000000" points="1902.345,-21.7453 1912.3253,-18.1896 1902.3059,-14.7454 1902.345,-21.7453"/>
<text text-anchor="middle" x="67.5681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M268.5138,-260.7018C263.8971,-237.325 260.1939,-197.1299 282.0681,-174 353.6299,-98.3302 410.301,-149.9113 514.0681,-141 779.4337,-118.2111 849.2398,-159.5094 1113.0681,-123 1118.7915,-122.208 1124.7191,-121.1411 1130.6037,-119.92"/>
<polygon fill="#000000" stroke="#000000" points="1131.4188,-123.3243 1140.4228,-117.7406 1129.902,-116.4906 1131.4188,-123.3243"/>
<text text-anchor="middle" x="324.5681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node21" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1185.0681" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1185.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1185.0681,-173.9735C1185.0681,-162.1918 1185.0681,-146.5607 1185.0681,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1188.5682,-133.0033 1185.0681,-123.0034 1181.5682,-133.0034 1188.5682,-133.0033"/>
<text text-anchor="middle" x="1253.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1362.0681" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1362.0681" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1353.1251,-173.9096C1346.7566,-162.8323 1337.1872,-149.2454 1325.0681,-141 1312.1493,-132.2104 1278.6738,-123.454 1247.6966,-116.778"/>
<polygon fill="#000000" stroke="#000000" points="1248.2626,-113.3205 1237.7561,-114.6862 1246.8211,-120.1705 1248.2626,-113.3205"/>
<text text-anchor="middle" x="1399.0681" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_funding -->
<g id="node23" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2432.0681" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2432.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2401.5245,-88.3727C2378.6743,-76.7365 2346.2891,-61.9101 2316.0681,-54 2256.6875,-38.4576 2080.3579,-26.001 1995.5917,-20.7274"/>
<polygon fill="#000000" stroke="#000000" points="1995.6742,-17.226 1985.4782,-20.1054 1995.2444,-24.2128 1995.6742,-17.226"/>
<text text-anchor="middle" x="2420.0681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node24" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2590.0681" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2590.0681" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2563.8305,-88.5541C2543.4515,-76.6857 2514.042,-61.4846 2486.0681,-54 2394.1606,-29.4096 2108.6677,-21.1612 1995.7333,-18.8158"/>
<polygon fill="#000000" stroke="#000000" points="1995.7406,-15.3153 1985.6721,-18.6131 1995.5995,-22.3139 1995.7406,-15.3153"/>
<text text-anchor="middle" x="2575.0681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1243.1193,-98.3895C1389.4161,-81.73 1770.9438,-38.2838 1903.1616,-23.2276"/>
<polygon fill="#000000" stroke="#000000" points="1903.8056,-26.6769 1913.3454,-22.0679 1903.0135,-19.7219 1903.8056,-26.6769"/>
<text text-anchor="middle" x="1663.5681" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
