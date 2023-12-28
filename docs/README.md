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
<svg width="3527pt" height="392pt"
 viewBox="0.00 0.00 3527.14 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3523.1355,-388 3523.1355,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2910.0433" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2910.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2299.0433" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2299.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2872.2436,-174.9048C2844.7578,-163.2792 2806.3358,-148.666 2771.0433,-141 2696.864,-124.8873 2483.9599,-113.2828 2371.1692,-108.0704"/>
<polygon fill="#000000" stroke="#000000" points="2371.0552,-104.5616 2360.9057,-107.601 2370.7353,-111.5543 2371.0552,-104.5616"/>
<text text-anchor="middle" x="2914.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- cytogenomic_file -->
<g id="node2" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="901.0433" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="901.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1022.0433" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1022.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M896.4716,-347.7609C894.9317,-337.177 895.0808,-324.1687 902.0433,-315 903.2167,-313.4547 940.3859,-302.4413 973.0467,-292.9982"/>
<polygon fill="#000000" stroke="#000000" points="974.3544,-296.2638 982.9933,-290.1302 972.415,-289.5378 974.3544,-296.2638"/>
<text text-anchor="middle" x="973.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="845.0433" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="845.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M824.439,-356.4828C749.789,-347.0275 647.046,-333.4527 644.0433,-330 639.6684,-324.9696 639.6493,-320.0138 644.0433,-315 684.2288,-269.1453 728.8445,-330.1092 780.0433,-297 808.0498,-278.8887 826.0212,-244.0151 835.8117,-219.4396"/>
<polygon fill="#000000" stroke="#000000" points="839.1408,-220.5307 839.3973,-209.939 832.5917,-218.059 839.1408,-220.5307"/>
<text text-anchor="middle" x="886.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="845.0433" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="845.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M986.0821,-360.0972C1086.8227,-352.687 1242.2318,-339.7642 1251.0433,-330 1253.4084,-327.3791 1259.0822,-166.7653 1233.0433,-141 1208.5024,-116.717 976.3943,-108.2701 883.3486,-105.8441"/>
<polygon fill="#000000" stroke="#000000" points="883.315,-102.3423 873.2303,-105.5899 883.1392,-109.34 883.315,-102.3423"/>
<text text-anchor="middle" x="1324.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M984.2534,-267.4047C975.9925,-265.0942 967.2614,-262.8216 959.0433,-261 934.2181,-255.4973 862.7375,-262.18 846.0433,-243 840.6469,-236.8002 839.032,-228.3923 839.166,-220.1924"/>
<polygon fill="#000000" stroke="#000000" points="842.6634,-220.3833 840.1179,-210.0988 835.6943,-219.726 842.6634,-220.3833"/>
<text text-anchor="middle" x="886.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2789.0433" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2789.0433" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1025.4213,-260.7641C1032.0454,-230.5531 1049.762,-170.5299 1090.0433,-141 1217.6914,-47.4221 1285.2547,-108.6385 1442.0433,-87 1561.3641,-70.5324 1590.9551,-63.3527 1711.0433,-54 1916.0542,-38.0334 2562.7218,-22.9663 2742.3525,-19.0068"/>
<polygon fill="#000000" stroke="#000000" points="2742.6035,-22.5023 2752.5243,-18.7835 2742.4498,-15.504 2742.6035,-22.5023"/>
<text text-anchor="middle" x="1130.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1044.9911,-262.8485C1063.4938,-250.802 1090.6868,-235.2308 1117.0433,-228 1207.1334,-203.2841 1451.5207,-247.5899 1537.0433,-210 1557.758,-200.8952 1552.8368,-184.1833 1573.0433,-174 1661.7289,-129.3058 1695.329,-151.8722 1794.0433,-141 1947.8287,-124.0623 2128.8819,-113.397 2227.0005,-108.3862"/>
<polygon fill="#000000" stroke="#000000" points="2227.2906,-111.8761 2237.1011,-107.8754 2226.937,-104.885 2227.2906,-111.8761"/>
<text text-anchor="middle" x="1613.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1748.0433" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1748.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1769.5553,-174.5752C1785.3053,-162.8731 1807.7382,-148.3053 1830.0433,-141 1901.6318,-117.5536 2113.6171,-109.2043 2226.4606,-106.3693"/>
<polygon fill="#000000" stroke="#000000" points="2226.8199,-109.8617 2236.7318,-106.1196 2226.6497,-102.8637 2226.8199,-109.8617"/>
<text text-anchor="middle" x="1898.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node5" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="603.0433" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="603.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M622.4393,-347.9744C636.2662,-336.3172 655.9059,-322.0478 676.0433,-315 735.5217,-294.1834 896.9454,-307.7177 959.0433,-297 964.3677,-296.081 969.8853,-294.8834 975.3409,-293.5421"/>
<polygon fill="#000000" stroke="#000000" points="976.2524,-296.9215 985.0392,-291.0019 974.4787,-290.15 976.2524,-296.9215"/>
<text text-anchor="middle" x="784.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M601.3716,-347.5216C599.6477,-337.1121 596.1477,-324.3621 589.0433,-315 579.6437,-302.6135 566.7043,-310.5309 559.0433,-297 551.1601,-283.0768 549.1448,-273.5706 559.0433,-261 587.45,-224.9248 717.0253,-205.4879 791.6525,-197.1126"/>
<polygon fill="#000000" stroke="#000000" points="792.2412,-200.5692 801.8018,-196.0036 791.4808,-193.6106 792.2412,-200.5692"/>
<text text-anchor="middle" x="667.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M475.437,-359.2088C394.8763,-353.5767 303.6728,-344.1706 291.0433,-330 270.6392,-307.1063 274.3487,-286.7242 291.0433,-261 348.8035,-171.9988 691.9873,-123.3059 807.2867,-109.2937"/>
<polygon fill="#000000" stroke="#000000" points="807.8902,-112.7465 817.4032,-108.0826 807.058,-105.7961 807.8902,-112.7465"/>
<text text-anchor="middle" x="435.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1925.0433" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1925.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1944.5732,-174.5847C1958.6836,-163.0456 1978.7566,-148.6691 1999.0433,-141 2039.5217,-125.6976 2152.4348,-115.1665 2227.6021,-109.6126"/>
<polygon fill="#000000" stroke="#000000" points="2228.2261,-113.0766 2237.9465,-108.862 2227.7194,-106.095 2228.2261,-113.0766"/>
<text text-anchor="middle" x="2058.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3064.0433" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3064.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3012.0449,-278.5083C2723.7849,-275.7187 1328.0397,-261.353 1137.0433,-243 1136.6672,-242.9639 979.5125,-215.5018 895.943,-200.8963"/>
<polygon fill="#000000" stroke="#000000" points="896.3403,-197.4127 885.887,-199.1388 895.1351,-204.3082 896.3403,-197.4127"/>
<text text-anchor="middle" x="1179.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3091.0238,-263.4659C3122.9681,-243.0779 3168.9961,-206.1101 3145.0433,-174 3114.2696,-132.7463 3084.5033,-151.1328 3034.0433,-141 2997.4477,-133.6513 2897.508,-144.567 2867.0433,-123 2839.2985,-103.3586 2855.1815,-80.622 2834.0433,-54 2829.6961,-48.5251 2824.3695,-43.3568 2818.9219,-38.7358"/>
<polygon fill="#000000" stroke="#000000" points="2820.9556,-35.881 2810.9542,-32.3849 2816.5925,-41.3549 2820.9556,-35.881"/>
<text text-anchor="middle" x="3168.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3063.9399,-260.9292C3062.6174,-228.9033 3054.4767,-163.4468 3011.0433,-141 3010.16,-140.5436 2551.3008,-117.5926 2370.7779,-108.5792"/>
<polygon fill="#000000" stroke="#000000" points="2370.7468,-105.0734 2360.5847,-108.0703 2370.3977,-112.0647 2370.7468,-105.0734"/>
<text text-anchor="middle" x="3098.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2731.0433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2731.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge42" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2727.3667,-86.905C2726.2245,-76.6233 2726.4745,-63.8733 2732.0433,-54 2736.5066,-46.0865 2743.504,-39.6621 2751.0883,-34.5514"/>
<polygon fill="#000000" stroke="#000000" points="2753.3524,-37.276 2760.1445,-29.1448 2749.7641,-31.2657 2753.3524,-37.276"/>
<text text-anchor="middle" x="2783.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1419.0433" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1419.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1409.1158,-173.8585C1404.6758,-163.0425 1402.0327,-149.7569 1410.0433,-141 1501.9662,-40.513 2511.9729,-21.546 2742.4211,-18.5172"/>
<polygon fill="#000000" stroke="#000000" points="2742.5336,-22.0162 2752.4881,-18.3886 2742.4441,-15.0167 2742.5336,-22.0162"/>
<text text-anchor="middle" x="1663.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1413.7642,-173.5746C1411.8556,-162.6518 1411.866,-149.3536 1420.0433,-141 1434.0877,-126.6528 2018.3736,-111.5806 2226.4237,-106.6589"/>
<polygon fill="#000000" stroke="#000000" points="2226.7195,-110.153 2236.6342,-106.4184 2226.5546,-103.155 2226.7195,-110.153"/>
<text text-anchor="middle" x="1506.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2936.0433" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2936.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2913.6043,-88.2685C2899.2141,-77.8601 2879.9397,-64.5049 2862.0433,-54 2850.4079,-47.1703 2837.2975,-40.4274 2825.4307,-34.6567"/>
<polygon fill="#000000" stroke="#000000" points="2826.7635,-31.4144 2816.2324,-30.254 2823.7413,-37.7284 2826.7635,-31.4144"/>
<text text-anchor="middle" x="2933.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M877.1639,-204.6607C892.5398,-211.0828 911.0428,-219.3461 927.0433,-228 937.7778,-233.8058 939.4571,-236.9279 950.0433,-243 960.3571,-248.9159 971.7678,-254.8758 982.4072,-260.197"/>
<polygon fill="#000000" stroke="#000000" points="980.9953,-263.4032 991.5115,-264.6917 984.0941,-257.1264 980.9953,-263.4032"/>
<text text-anchor="middle" x="986.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M816.0579,-178.3909C807.3732,-172.7632 798.8798,-165.3341 794.0433,-156 786.8396,-142.0975 798.8419,-129.6083 813.006,-120.4688"/>
<polygon fill="#000000" stroke="#000000" points="815.0926,-123.3028 821.9522,-115.2283 811.5545,-117.2628 815.0926,-123.3028"/>
<text text-anchor="middle" x="830.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M887.4092,-186.6574C972.4796,-176.1402 1170.2166,-152.7552 1337.0433,-141 1668.6164,-117.6362 2065.6189,-108.8466 2226.2657,-106.0874"/>
<polygon fill="#000000" stroke="#000000" points="2226.5628,-109.583 2236.5022,-105.9143 2226.4444,-102.584 2226.5628,-109.583"/>
<text text-anchor="middle" x="1373.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2117.0433" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2117.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2117.1178,-173.5775C2118.1625,-162.6557 2121.3471,-149.3576 2130.0433,-141 2144.4993,-127.1069 2189.936,-117.9072 2230.0585,-112.2875"/>
<polygon fill="#000000" stroke="#000000" points="2230.6778,-115.7358 2240.1226,-110.9352 2229.7455,-108.7982 2230.6778,-115.7358"/>
<text text-anchor="middle" x="2209.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node13" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2290.0433" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2290.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2291.9081,-173.9735C2293.1269,-162.1918 2294.7439,-146.5607 2296.1303,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="2299.6332,-133.3105 2297.1808,-123.0034 2292.6703,-132.5901 2299.6332,-133.3105"/>
<text text-anchor="middle" x="2340.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3084.0433" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3084.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3057.1472,-88.1971C3037.9869,-76.9389 3011.2623,-62.6464 2986.0433,-54 2935.9715,-36.8328 2875.7805,-27.3521 2835.216,-22.4871"/>
<polygon fill="#000000" stroke="#000000" points="2835.4236,-18.9879 2825.0885,-21.3195 2834.6218,-25.9419 2835.4236,-18.9879"/>
<text text-anchor="middle" x="3075.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3250.0433" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3250.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3219.5731,-88.1655C3197.1554,-76.5861 3165.5713,-61.919 3136.0433,-54 3080.5476,-39.1169 2916.7095,-26.5204 2835.6055,-20.9962"/>
<polygon fill="#000000" stroke="#000000" points="2835.4116,-17.4753 2825.199,-20.2953 2834.9411,-24.4594 2835.4116,-17.4753"/>
<text text-anchor="middle" x="3240.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- molecular_test -->
<g id="node17" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2443.0433" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2443.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2427.4037,-174.1468C2417.2948,-163.4393 2403.386,-150.1664 2389.0433,-141 2377.5175,-133.6339 2364.2378,-127.3163 2351.48,-122.1238"/>
<polygon fill="#000000" stroke="#000000" points="2352.4516,-118.7461 2341.8633,-118.3737 2349.9084,-125.2677 2352.4516,-118.7461"/>
<text text-anchor="middle" x="2472.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2594.0433" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2594.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2580.4017,-174.442C2570.4887,-162.9934 2556.0472,-148.7814 2540.0433,-141 2510.7766,-126.7702 2429.6448,-116.6417 2369.5574,-110.8244"/>
<polygon fill="#000000" stroke="#000000" points="2369.6399,-107.3166 2359.3545,-109.8581 2368.9799,-114.2855 2369.6399,-107.3166"/>
<text text-anchor="middle" x="2604.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M859.5984,-120.6401C864.1851,-126.5666 868.6713,-133.6644 871.0433,-141 873.8425,-149.657 871.3148,-158.6443 866.912,-166.6187"/>
<polygon fill="#000000" stroke="#000000" points="863.8928,-164.8402 861.3285,-175.12 869.7437,-168.683 863.8928,-164.8402"/>
<text text-anchor="middle" x="897.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge25" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M868.024,-94.5566C896.6237,-82.1572 947.2877,-62.1346 993.0433,-54 1169.5438,-22.6209 2477.8023,-18.5678 2742.4453,-18.0677"/>
<polygon fill="#000000" stroke="#000000" points="2742.4944,-21.5677 2752.488,-18.0495 2742.4816,-14.5678 2742.4944,-21.5677"/>
<text text-anchor="middle" x="1017.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2720.0433" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2720.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2702.6632,-174.7077C2689.8186,-163.0679 2671.2856,-148.5203 2652.0433,-141 2602.5092,-121.6412 2459.2115,-112.0195 2371.1646,-107.8067"/>
<polygon fill="#000000" stroke="#000000" points="2371.1275,-104.3012 2360.9753,-107.3314 2370.8013,-111.2936 2371.1275,-104.3012"/>
<text text-anchor="middle" x="2722.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node21" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="253.0433" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="253.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M314.3024,-353.7695C389.0319,-338.8671 506.1193,-315.582 511.0433,-315 708.9373,-291.6082 762.2923,-328.5958 959.0433,-297 964.3781,-296.1433 969.9022,-294.9848 975.3616,-293.666"/>
<polygon fill="#000000" stroke="#000000" points="976.2628,-297.0482 985.0638,-291.1496 974.5053,-290.2723 976.2628,-297.0482"/>
<text text-anchor="middle" x="577.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M253.5306,-347.9788C254.7307,-337.2082 257.9336,-323.9278 266.0433,-315 313.6845,-262.5524 347.5418,-279.1105 416.0433,-261 461.3945,-249.01 474.1101,-252.5206 520.0433,-243 547.8038,-237.2461 554.1854,-233.2625 582.0433,-228 654.2156,-214.3662 738.4582,-203.7553 791.7697,-197.6875"/>
<polygon fill="#000000" stroke="#000000" points="792.4613,-201.1319 802.0069,-196.535 791.6781,-194.1758 792.4613,-201.1319"/>
<text text-anchor="middle" x="482.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M250.2645,-347.7828C245.8928,-324.8622 235.3696,-285.5371 212.0433,-261 198.6113,-246.8708 182.6284,-259.3708 172.0433,-243 168.4234,-237.4017 168.0399,-233.3309 172.0433,-228 249.0484,-125.4589 674.9559,-108.3912 806.3994,-105.5604"/>
<polygon fill="#000000" stroke="#000000" points="806.8442,-109.0523 816.7725,-105.3538 806.7048,-102.0537 806.8442,-109.0523"/>
<text text-anchor="middle" x="238.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2352.4146,-95.5239C2449.7406,-78.2435 2654.3299,-41.9185 2744.6165,-25.888"/>
<polygon fill="#000000" stroke="#000000" points="2745.2992,-29.3216 2754.5333,-24.1273 2744.0754,-22.4294 2745.2992,-29.3216"/>
<text text-anchor="middle" x="2623.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1290.0433" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1290.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1191.1217,-356.6465C1158.9602,-351.3364 1123.6817,-343.0198 1093.0433,-330 1077.0019,-323.1832 1061.0644,-312.2189 1048.3659,-302.2001"/>
<polygon fill="#000000" stroke="#000000" points="1050.4832,-299.4105 1040.5204,-295.8059 1046.0609,-304.8366 1050.4832,-299.4105"/>
<text text-anchor="middle" x="1184.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1289.2598,-347.8672C1287.8701,-337.0545 1284.4094,-323.7692 1276.0433,-315 1204.7347,-240.2558 1151.1056,-280.995 1055.0433,-243 1040.4371,-237.2229 1037.9583,-232.9252 1023.0433,-228 981.7616,-214.368 933.3095,-204.9768 897.388,-199.2129"/>
<polygon fill="#000000" stroke="#000000" points="897.5559,-195.6968 887.1356,-197.6115 896.4756,-202.6129 897.5559,-195.6968"/>
<text text-anchor="middle" x="1347.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1353.0096,-350.7784C1404.3802,-334.8311 1465.1272,-305.7859 1443.0433,-261 1413.3864,-200.8563 1357.7947,-245.722 1301.0433,-210 1268.9922,-189.8256 1283.9826,-159.6888 1251.0433,-141 1219.491,-123.0982 977.98,-110.7769 883.1205,-106.5824"/>
<polygon fill="#000000" stroke="#000000" points="883.2324,-103.084 873.0895,-106.145 882.9275,-110.0774 883.2324,-103.084"/>
<text text-anchor="middle" x="1522.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_personnel -->
<g id="node24" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3432.0433" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3432.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3399.0244,-88.2787C3374.1379,-76.515 3338.8086,-61.5703 3306.0433,-54 3217.2963,-33.4953 2945.5381,-22.9062 2835.7658,-19.3743"/>
<polygon fill="#000000" stroke="#000000" points="2835.7657,-15.8726 2825.66,-19.0544 2835.5442,-22.8691 2835.7657,-15.8726"/>
<text text-anchor="middle" x="3421.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node25" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="76.0433" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="76.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M126.4411,-352.3289C174.1101,-340.0741 247.8578,-322.8539 313.0433,-315 598.2035,-280.6424 675.1794,-340.796 959.0433,-297 964.4535,-296.1653 970.0561,-295.0083 975.5874,-293.6797"/>
<polygon fill="#000000" stroke="#000000" points="976.6071,-297.0311 985.4099,-291.1354 974.8517,-290.2548 976.6071,-297.0311"/>
<text text-anchor="middle" x="374.0433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M84.3932,-347.9884C96.9127,-323.3409 123.0874,-279.9992 160.0433,-261 226.3462,-226.9134 423.2472,-263.0824 495.0433,-243 508.6391,-239.197 509.5627,-232.1933 523.0433,-228 571.6848,-212.8695 712.6751,-201.1288 790.9946,-195.5549"/>
<polygon fill="#000000" stroke="#000000" points="791.4206,-199.0337 801.1508,-194.8416 790.9301,-192.0509 791.4206,-199.0337"/>
<text text-anchor="middle" x="221.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M63.7667,-348.2257C46.0996,-320.2296 18.3101,-265.2242 44.0433,-228 82.6751,-172.1172 122.1496,-194.1028 187.0433,-174 246.0437,-155.7228 261.0099,-150.4888 322.0433,-141 502.046,-113.0152 720.2797,-106.7838 806.9313,-105.3968"/>
<polygon fill="#000000" stroke="#000000" points="807.1274,-108.8944 817.0747,-105.2473 807.0242,-101.8952 807.1274,-108.8944"/>
<text text-anchor="middle" x="105.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
