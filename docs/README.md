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
<svg width="3281pt" height="479pt"
 viewBox="0.00 0.00 3281.19 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3277.1938,-475 3277.1938,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2414.1938" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2414.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2196.1938" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2196.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2391.9393,-355.0937C2385.6783,-352.405 2378.778,-349.7872 2372.1938,-348 2310.3737,-331.2195 2283.4374,-364.0725 2229.1938,-330 2220.1796,-324.3379 2213.1435,-315.2122 2207.927,-306.2344"/>
<polygon fill="#000000" stroke="#000000" points="2210.8778,-304.324 2203.1429,-297.0836 2204.6744,-307.5672 2210.8778,-304.324"/>
<text text-anchor="middle" x="2253.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2329.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2329.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2441.9274,-363.7021C2492.0461,-359.2603 2600.8871,-348.2885 2691.1938,-330 2774.3663,-313.1563 2875.1938,-363.861 2875.1938,-279 2875.1938,-279 2875.1938,-279 2875.1938,-105 2875.1938,-56.2933 2824.9762,-67.5554 2778.1938,-54 2703.6541,-32.4019 2474.8077,-22.6546 2375.7265,-19.3646"/>
<polygon fill="#000000" stroke="#000000" points="2375.8157,-15.8658 2365.7074,-19.0394 2375.5885,-22.8621 2375.8157,-15.8658"/>
<text text-anchor="middle" x="2899.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="787.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="787.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1451.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1451.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M775.6602,-173.8275C770.3812,-162.9999 766.9326,-149.7128 775.1938,-141 795.6986,-119.3742 1208.1725,-109.4165 1378.543,-106.2142"/>
<polygon fill="#000000" stroke="#000000" points="1378.7424,-109.7112 1388.6758,-106.0264 1378.6126,-102.7124 1378.7424,-109.7112"/>
<text text-anchor="middle" x="854.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2234.1938" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2234.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2227.3185,-434.8798C2224.4965,-424.0719 2223.4571,-410.7871 2231.1938,-402 2252.0675,-378.2921 2341.7165,-392.3015 2372.1938,-384 2375.5879,-383.0755 2379.0664,-381.9312 2382.4982,-380.671"/>
<polygon fill="#000000" stroke="#000000" points="2383.9502,-383.8599 2391.9372,-376.8987 2381.3524,-377.3598 2383.9502,-383.8599"/>
<text text-anchor="middle" x="2322.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2152.805,-440.117C2113.2888,-433.0335 2073.0395,-424.2402 2067.1938,-417 2063.0058,-411.813 2062.9902,-407.1744 2067.1938,-402 2091.8163,-371.6904 2123.1813,-408.9838 2153.1938,-384 2176.2725,-364.7881 2187.113,-331.2247 2192.1069,-307.214"/>
<polygon fill="#000000" stroke="#000000" points="2195.5707,-307.7314 2193.9606,-297.2596 2188.689,-306.4499 2195.5707,-307.7314"/>
<text text-anchor="middle" x="2270.6938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line -->
<g id="node20" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2292.1938" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2292.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2343.9295,-447.253C2464.8458,-440.3767 2643.7622,-428.3639 2654.1938,-417 2687.067,-381.1885 2645.0911,-408.3202 2594.1938,-384 2483.4088,-331.0638 2472.3533,-289.6904 2366.1938,-228 2355.5783,-221.8312 2343.7508,-215.7472 2332.7213,-210.3863"/>
<polygon fill="#000000" stroke="#000000" points="2334.22,-207.2234 2323.6884,-206.0671 2331.2003,-213.5386 2334.22,-207.2234"/>
<text text-anchor="middle" x="2595.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1016.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1016.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1033.2258,-174.4289C1045.6335,-162.8184 1063.4834,-148.4205 1082.1938,-141 1134.458,-120.272 1287.2344,-111.0693 1378.999,-107.3147"/>
<polygon fill="#000000" stroke="#000000" points="1379.2003,-110.8095 1389.0534,-106.9151 1378.9222,-103.8151 1379.2003,-110.8095"/>
<text text-anchor="middle" x="1141.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1811.1938" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1811.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge7" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1840.7661,-435.8485C1862.9352,-423.9518 1894.4495,-409.029 1924.1938,-402 2118.1241,-356.1715 2177.8354,-427.9778 2372.1938,-384 2375.6249,-383.2236 2379.1275,-382.1762 2382.5739,-380.9748"/>
<polygon fill="#000000" stroke="#000000" points="2383.9918,-384.1785 2392.0319,-377.2788 2381.4439,-377.6587 2383.9918,-384.1785"/>
<text text-anchor="middle" x="1995.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1816.1402,-434.6272C1823.5514,-410.7846 1839.8976,-369.6779 1869.1938,-348 1880.337,-339.7545 2057.1224,-305.3584 2145.996,-288.4569"/>
<polygon fill="#000000" stroke="#000000" points="2146.6935,-291.8871 2155.8652,-286.5832 2145.3878,-285.0099 2146.6935,-291.8871"/>
<text text-anchor="middle" x="1940.6938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1733.8694,-443.6918C1628.6331,-428.0008 1460.3949,-390.3402 1525.1938,-315 1626.9028,-196.7452 2066.2015,-240.3694 2219.1938,-210 2226.6718,-208.5156 2234.5373,-206.7716 2242.2244,-204.9637"/>
<polygon fill="#000000" stroke="#000000" points="2243.2767,-208.3104 2252.1795,-202.5667 2241.638,-201.5049 2243.2767,-208.3104"/>
<text text-anchor="middle" x="1596.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M74.3363,-86.8564C78.0076,-75.3055 84.6415,-61.2062 96.1938,-54 144.2479,-24.0244 1965.7965,-18.7759 2282.4902,-18.0894"/>
<polygon fill="#000000" stroke="#000000" points="2282.7015,-21.5891 2292.6941,-18.0678 2282.6866,-14.5891 2282.7015,-21.5891"/>
<text text-anchor="middle" x="152.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node7" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1187.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1187.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1193.5186,-174.0475C1198.4596,-162.7322 1206.4763,-148.8279 1218.1938,-141 1244.0402,-123.7332 1321.231,-114.2831 1379.7448,-109.4524"/>
<polygon fill="#000000" stroke="#000000" points="1380.3764,-112.9133 1390.0674,-108.6315 1379.8214,-105.9353 1380.3764,-112.9133"/>
<text text-anchor="middle" x="1282.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_arm -->
<g id="node8" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="218.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="218.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M212.9342,-87.0016C210.9118,-75.9609 210.792,-62.3805 219.1938,-54 238.0899,-35.1519 1972.1273,-20.7793 2282.0595,-18.3599"/>
<polygon fill="#000000" stroke="#000000" points="2282.5063,-21.8566 2292.4788,-18.2789 2282.4518,-14.8568 2282.5063,-21.8566"/>
<text text-anchor="middle" x="267.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="915.1938" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="915.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M910.9285,-347.8679C903.3016,-310.5336 891.8186,-224.3647 934.1938,-174 962.4608,-140.4034 1244.6385,-118.1091 1379.7738,-109.275"/>
<polygon fill="#000000" stroke="#000000" points="1380.2756,-112.7499 1390.029,-108.612 1379.824,-105.7645 1380.2756,-112.7499"/>
<text text-anchor="middle" x="951.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M967.2936,-365.1028C1127.4339,-362.1253 1605.6468,-351.5159 1672.1938,-330 1683.8059,-326.2456 1683.6279,-318.8947 1695.1938,-315 1776.6376,-287.5742 2029.646,-281.0398 2141.7637,-279.4847"/>
<polygon fill="#000000" stroke="#000000" points="2141.8893,-282.9835 2151.8427,-279.3532 2141.7978,-275.9841 2141.8893,-282.9835"/>
<text text-anchor="middle" x="1737.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M863.5355,-363.717C720.574,-356.7155 330.1938,-332.6821 330.1938,-279 330.1938,-279 330.1938,-279 330.1938,-105 330.1938,-54.4696 1982.4439,-23.9089 2282.6857,-18.7727"/>
<polygon fill="#000000" stroke="#000000" points="2282.852,-22.2705 2292.791,-18.6007 2282.7328,-15.2715 2282.852,-22.2705"/>
<text text-anchor="middle" x="372.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- therapeutic_procedure -->
<g id="node10" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="551.1938" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="551.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M556.7906,-173.8771C561.3814,-162.3352 569.1246,-148.2381 581.1938,-141 615.1216,-120.6528 1175.4265,-109.5086 1378.4621,-106.1233"/>
<polygon fill="#000000" stroke="#000000" points="1378.7832,-109.6185 1388.724,-105.9537 1378.6675,-102.6195 1378.7832,-109.6185"/>
<text text-anchor="middle" x="674.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2101.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2101.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2015.2663,-180.9287C1952.391,-172.5194 1875.6418,-161.4944 1861.1938,-156 1849.7867,-151.6621 1849.7181,-145.0161 1838.1938,-141 1781.9404,-121.3963 1619.1871,-111.7091 1523.6025,-107.5849"/>
<polygon fill="#000000" stroke="#000000" points="1523.5685,-104.0804 1513.4299,-107.156 1523.2736,-111.0742 1523.5685,-104.0804"/>
<text text-anchor="middle" x="1990.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2173.3824,-178.4815C2196.1964,-172.6553 2217.2902,-165.0759 2224.1938,-156 2228.8357,-149.8973 2221.5194,-93.7297 2225.1938,-87 2239.0655,-61.5931 2266.7814,-43.9128 2290.1147,-32.8138"/>
<polygon fill="#000000" stroke="#000000" points="2291.7851,-35.9 2299.4618,-28.598 2288.9071,-29.519 2291.7851,-35.9"/>
<text text-anchor="middle" x="2311.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1338.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1338.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1342.2473,-173.9325C1345.4933,-163.1443 1351.0569,-149.8619 1360.1938,-141 1369.3358,-132.133 1380.9265,-125.3721 1392.7479,-120.2442"/>
<polygon fill="#000000" stroke="#000000" points="1394.2357,-123.4192 1402.2355,-116.4728 1391.6499,-116.9143 1394.2357,-123.4192"/>
<text text-anchor="middle" x="1403.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2595.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2595.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge41" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2555.4354,-90.8679C2525.7129,-80.4083 2484.0279,-65.961 2447.1938,-54 2421.7294,-45.7311 2392.9987,-36.9541 2370.2629,-30.1367"/>
<polygon fill="#000000" stroke="#000000" points="2371.1767,-26.7569 2360.5932,-27.2469 2369.1723,-33.4638 2371.1767,-26.7569"/>
<text text-anchor="middle" x="2543.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1510.5082,-99.1226C1675.2837,-82.7952 2136.1268,-37.1308 2283.3558,-22.542"/>
<polygon fill="#000000" stroke="#000000" points="2283.7998,-26.0153 2293.4059,-21.5462 2283.1095,-19.0494 2283.7998,-26.0153"/>
<text text-anchor="middle" x="1993.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2916.1938" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2916.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2860.897,-439.5486C2813.8468,-428.4278 2744.3667,-412.7693 2683.1938,-402 2601.1427,-387.5551 2504.1068,-375.8901 2451.9294,-370.0559"/>
<polygon fill="#000000" stroke="#000000" points="2452.1283,-366.5566 2441.8037,-368.9341 2451.3575,-373.514 2452.1283,-366.5566"/>
<text text-anchor="middle" x="2820.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2909.49,-434.9843C2905.1721,-424.729 2898.9221,-411.979 2891.1938,-402 2868.6131,-372.8433 2861.7588,-363.2771 2828.1938,-348 2725.5133,-301.2651 2383.8228,-285.1708 2250.3115,-280.5827"/>
<polygon fill="#000000" stroke="#000000" points="2250.4202,-277.0845 2240.3085,-280.2472 2250.1855,-284.0805 2250.4202,-277.0845"/>
<text text-anchor="middle" x="2943.6938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2974.2573,-440.0475C3054.4717,-419.5778 3183.6823,-375.7445 3131.1938,-315 3079.9417,-255.6864 2533.2057,-209.9276 2350.9418,-196.2263"/>
<polygon fill="#000000" stroke="#000000" points="2350.9785,-192.7194 2340.7455,-195.4647 2350.457,-199.6999 2350.9785,-192.7194"/>
<text text-anchor="middle" x="3206.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node16" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2677.1938" cy="-453" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2677.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2570.5523,-441.5623C2526.5252,-435.5271 2481.3447,-427.2345 2462.1938,-417 2450.4647,-410.7318 2439.9962,-400.5103 2431.852,-390.8576"/>
<polygon fill="#000000" stroke="#000000" points="2434.5484,-388.625 2425.581,-382.9825 2429.0724,-392.9856 2434.5484,-388.625"/>
<text text-anchor="middle" x="2570.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2683.2767,-434.7315C2685.5946,-424.1371 2686.2201,-411.1282 2679.1938,-402 2660.1245,-377.2261 2634.6555,-404.6622 2611.1938,-384 2586.3569,-362.1267 2609.7587,-334.7387 2583.1938,-315 2557.1035,-295.614 2351.0527,-285.0162 2250.7199,-280.9597"/>
<polygon fill="#000000" stroke="#000000" points="2250.6085,-277.4526 2240.4776,-280.5535 2250.331,-284.4471 2250.6085,-277.4526"/>
<text text-anchor="middle" x="2719.6938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2693.8071,-435.0189C2705.7546,-423.3816 2722.925,-409.1176 2741.1938,-402 2849.5424,-359.7867 3070.1857,-438.5183 2997.1938,-348 2973.4997,-318.6167 2951.0635,-338.0879 2914.1938,-330 2702.7673,-283.6204 2451.1282,-227.511 2344.2933,-203.6471"/>
<polygon fill="#000000" stroke="#000000" points="2344.9352,-200.2043 2334.4127,-201.4397 2343.409,-207.0359 2344.9352,-200.2043"/>
<text text-anchor="middle" x="3022.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2227.2642,-292.0396C2242.465,-298.6133 2260.944,-306.8951 2277.1938,-315 2289.4781,-321.127 2291.4605,-324.8708 2304.1938,-330 2333.1926,-341.6813 2342.6361,-337.8153 2372.1938,-348 2375.3439,-349.0854 2378.5909,-350.2992 2381.8182,-351.57"/>
<polygon fill="#000000" stroke="#000000" points="2380.7447,-354.913 2391.3243,-355.4821 2383.4087,-348.4397 2380.7447,-354.913"/>
<text text-anchor="middle" x="2340.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2152.1541,-276.909C2016.4076,-270.0925 1610.8075,-246.8093 1565.1938,-210 1540.0377,-189.6996 1564.4147,-164.477 1542.1938,-141 1533.5312,-131.8477 1522.2492,-124.9769 1510.5929,-119.8337"/>
<polygon fill="#000000" stroke="#000000" points="1511.7916,-116.5435 1501.2074,-116.0688 1509.1855,-123.0403 1511.7916,-116.5435"/>
<text text-anchor="middle" x="1601.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2191.861,-260.9358C2190.4058,-250.4138 2190.56,-237.4093 2197.1938,-228 2202.9581,-219.8239 2222.2673,-211.8251 2241.9856,-205.4518"/>
<polygon fill="#000000" stroke="#000000" points="2243.1248,-208.763 2251.6408,-202.46 2241.0529,-202.0767 2243.1248,-208.763"/>
<text text-anchor="middle" x="2233.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2753.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2753.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2712.981,-89.4929C2682.0279,-78.1163 2637.9551,-63.1195 2598.1938,-54 2521.1254,-36.3239 2429.5062,-26.3525 2375.5293,-21.5801"/>
<polygon fill="#000000" stroke="#000000" points="2375.515,-18.066 2365.2513,-20.6942 2374.9138,-25.0401 2375.515,-18.066"/>
<text text-anchor="middle" x="2712.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- follow_up -->
<g id="node19" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1465.1938" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1465.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1457.3942,-174.0075C1455.2987,-168.3513 1453.3067,-162.0113 1452.1938,-156 1450.835,-148.6609 1450.2625,-140.6264 1450.1058,-133.1499"/>
<polygon fill="#000000" stroke="#000000" points="1453.6058,-133.0884 1450.1227,-123.0825 1446.6059,-133.0766 1453.6058,-133.0884"/>
<text text-anchor="middle" x="1497.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2257.5194,-179.0975C2223.1824,-166.9492 2168.8403,-149.4009 2120.1938,-141 2007.4233,-121.5253 1672.7452,-110.7192 1523.9325,-106.7618"/>
<polygon fill="#000000" stroke="#000000" points="1523.6334,-103.2528 1513.5448,-106.4886 1523.4493,-110.2504 1523.6334,-103.2528"/>
<text text-anchor="middle" x="2223.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2287.7452,-210.3155C2284.3917,-220.9265 2278.8538,-233.9365 2270.1938,-243 2262.0258,-251.5486 2251.4053,-258.3323 2240.7717,-263.5988"/>
<polygon fill="#000000" stroke="#000000" points="2239.1255,-260.5029 2231.4849,-267.8427 2242.035,-266.8696 2239.1255,-260.5029"/>
<text text-anchor="middle" x="2321.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2328.6639,-179.7121C2353.9973,-169.0431 2385.8567,-150.8605 2401.1938,-123 2418.1954,-92.1158 2386.0619,-58.9565 2359.4204,-38.346"/>
<polygon fill="#000000" stroke="#000000" points="2361.501,-35.5315 2351.3892,-32.3689 2357.3218,-41.147 2361.501,-35.5315"/>
<text text-anchor="middle" x="2446.6938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node21" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1732.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1732.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1667.4357,-180.3086C1642.6657,-174.6268 1614.5353,-166.6693 1590.1938,-156 1579.0163,-151.1007 1578.2384,-146.1917 1567.1938,-141 1548.8306,-132.3682 1527.8827,-125.1391 1508.8878,-119.4778"/>
<polygon fill="#000000" stroke="#000000" points="1509.7355,-116.0795 1499.1567,-116.661 1507.7892,-122.8035 1509.7355,-116.0795"/>
<text text-anchor="middle" x="1658.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2990.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2990.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge42" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2963.5391,-87.7776C2943.8428,-76.0103 2915.9176,-61.2782 2889.1938,-54 2792.93,-27.7828 2492.2378,-20.4727 2375.8519,-18.5977"/>
<polygon fill="#000000" stroke="#000000" points="2375.8813,-15.0978 2365.8282,-18.4424 2375.7728,-22.097 2375.8813,-15.0978"/>
<text text-anchor="middle" x="2996.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1890.1938" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1890.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1848.9535,-180.1101C1841.3985,-178.0149 1833.5712,-175.8987 1826.1938,-174 1792.1581,-165.2402 1781.5125,-169.8081 1749.1938,-156 1737.9711,-151.2052 1737.6409,-145.231 1726.1938,-141 1689.8935,-127.5831 1590.752,-116.8214 1522.0008,-110.6705"/>
<polygon fill="#000000" stroke="#000000" points="1521.9343,-107.1512 1511.6657,-109.76 1521.3199,-114.1242 1521.9343,-107.1512"/>
<text text-anchor="middle" x="1793.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- pathology_file -->
<g id="node25" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2024.1938" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2024.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2043.8959,-435.497C2058.3823,-423.758 2079.1378,-409.1782 2100.1938,-402 2214.8665,-362.9066 2254.3842,-412.267 2372.1938,-384 2375.6145,-383.1792 2379.1104,-382.1027 2382.5527,-380.8837"/>
<polygon fill="#000000" stroke="#000000" points="2383.981,-384.083 2392.0054,-377.1649 2381.4182,-377.569 2383.981,-384.083"/>
<text text-anchor="middle" x="2161.1938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2019.1812,-434.8322C2014.1171,-412.3194 2009.3311,-373.7839 2027.1938,-348 2053.3697,-310.2163 2104.1324,-293.0977 2143.2199,-285.3564"/>
<polygon fill="#000000" stroke="#000000" points="2144.185,-288.7381 2153.3931,-283.4977 2142.9269,-281.8521 2144.185,-288.7381"/>
<text text-anchor="middle" x="2088.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2016.2294,-434.8546C2010.2299,-423.4579 2000.8615,-409.5353 1988.1938,-402 1958.7713,-384.4981 1857.9431,-409.5826 1835.1938,-384 1824.5615,-372.0436 1826.2376,-361.2585 1835.1938,-348 1858.8528,-312.9757 2128.8273,-236.3267 2242.3665,-205.3668"/>
<polygon fill="#000000" stroke="#000000" points="2243.4768,-208.692 2252.2081,-202.6908 2241.6401,-201.9373 2243.4768,-208.692"/>
<text text-anchor="middle" x="1952.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
