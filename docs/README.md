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
<svg width="3496pt" height="305pt"
 viewBox="0.00 0.00 3495.99 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3491.9885,-301 3491.9885,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1821.1938" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1821.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2732.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2732.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1880.6156,-99.3252C2050.1775,-83.1322 2533.8737,-36.9395 2685.8861,-22.4224"/>
<polygon fill="#000000" stroke="#000000" points="2686.627,-25.8676 2696.2489,-21.4327 2685.9614,-18.8993 2686.627,-25.8676"/>
<text text-anchor="middle" x="2381.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M64.9241,-86.9914C62.8977,-75.9468 62.7772,-62.3656 71.1938,-54 95.3344,-30.0056 2331.5219,-19.6747 2685.2923,-18.1899"/>
<polygon fill="#000000" stroke="#000000" points="2685.4564,-21.6893 2695.4417,-18.1475 2685.4271,-14.6894 2685.4564,-21.6893"/>
<text text-anchor="middle" x="127.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2489.1938" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2489.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2429.9226,-179.8271C2395.727,-172.3854 2356.3809,-162.9871 2340.1938,-156 2328.989,-151.1635 2328.7582,-144.8989 2317.1938,-141 2240.8776,-115.2703 2012.3727,-107.9229 1894.0279,-105.83"/>
<polygon fill="#000000" stroke="#000000" points="1894.0251,-102.3296 1883.9674,-105.6601 1893.9069,-109.3286 1894.0251,-102.3296"/>
<text text-anchor="middle" x="2404.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1219.1938" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1219.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1236.4644,-174.2515C1249.0512,-162.5595 1267.1689,-148.1373 1286.1938,-141 1328.3488,-125.1853 1612.322,-112.7139 1748.5538,-107.5643"/>
<polygon fill="#000000" stroke="#000000" points="1749.0316,-111.0489 1758.8934,-107.1768 1748.7693,-104.0538 1749.0316,-111.0489"/>
<text text-anchor="middle" x="1365.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cell_line -->
<g id="node6" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="219.1938" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="219.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M214.0349,-260.6826C212.2061,-250.0709 212.0952,-237.0609 219.1938,-228 380.6681,-21.8881 531.9153,-123.4791 791.1938,-87 1173.8437,-33.1632 2427.1654,-20.4187 2685.4049,-18.3402"/>
<polygon fill="#000000" stroke="#000000" points="2685.5931,-21.839 2695.5651,-18.2599 2685.5376,-14.8392 2685.5931,-21.839"/>
<text text-anchor="middle" x="349.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample -->
<g id="node18" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="793.1938" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="793.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M251.6498,-265.3985C287.2884,-250.4845 339.8269,-228.5701 342.1938,-228 416.0221,-210.2179 635.6163,-198.76 738.661,-194.2175"/>
<polygon fill="#000000" stroke="#000000" points="739.0163,-197.7054 748.8547,-193.7739 738.712,-190.712 739.0163,-197.7054"/>
<text text-anchor="middle" x="382.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1422.1938" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1422.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1433.657,-173.971C1442.0193,-162.47 1454.4426,-148.3831 1469.1938,-141 1516.6187,-117.2634 1660.1974,-109.1693 1748.6509,-106.4149"/>
<polygon fill="#000000" stroke="#000000" points="1748.9967,-109.9063 1758.8889,-106.1122 1748.7898,-102.9094 1748.9967,-109.9063"/>
<text text-anchor="middle" x="1537.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1578.1938" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1578.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1592.0412,-174.1404C1601.7698,-162.8643 1615.7634,-148.9688 1631.1938,-141 1652.2705,-130.1152 1707.9726,-120.2778 1753.6513,-113.6482"/>
<polygon fill="#000000" stroke="#000000" points="1754.4172,-117.0745 1763.8241,-112.2 1753.4306,-110.1444 1754.4172,-117.0745"/>
<text text-anchor="middle" x="1674.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2695.1938" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2695.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2616.0945,-179.5979C2563.8874,-171.1434 2503.005,-160.6668 2491.1938,-156 2479.8436,-151.5154 2479.7907,-144.8012 2468.1938,-141 2414.8115,-123.5024 2050.861,-111.3937 1893.4701,-106.9167"/>
<polygon fill="#000000" stroke="#000000" points="1893.502,-103.4163 1883.4073,-106.6328 1893.3046,-110.4135 1893.502,-103.4163"/>
<text text-anchor="middle" x="2577.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2685.0545,-173.9604C2679.1321,-163.9333 2671.2542,-151.4159 2663.1938,-141 2656.4593,-132.2975 2650.2592,-133.2254 2646.1938,-123 2640.2826,-108.132 2639.273,-101.4258 2646.1938,-87 2656.8442,-64.8003 2678.5036,-47.4894 2697.4202,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2699.3138,-38.7057 2706.1467,-30.6086 2695.7558,-32.6774 2699.3138,-38.7057"/>
<text text-anchor="middle" x="2732.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1697.1938" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1697.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1708.3398,-174.0949C1715.741,-163.3679 1726.269,-150.0927 1738.1938,-141 1747.7565,-133.7084 1759.0231,-127.5582 1770.1193,-122.5189"/>
<polygon fill="#000000" stroke="#000000" points="1771.5543,-125.7118 1779.3587,-118.5466 1768.7894,-119.281 1771.5543,-125.7118"/>
<text text-anchor="middle" x="1777.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2937.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2937.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2910.4613,-88.0966C2892.7119,-77.3604 2868.6327,-63.7087 2846.1938,-54 2823.0677,-43.994 2796.237,-35.3819 2774.4167,-29.092"/>
<polygon fill="#000000" stroke="#000000" points="2775.3499,-25.7188 2764.7751,-26.3689 2773.4472,-32.4552 2775.3499,-25.7188"/>
<text text-anchor="middle" x="2936.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2306.1938" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2306.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2307.2799,-260.9682C2308.0025,-230.498 2304.4187,-169.3741 2267.1938,-141 2238.2285,-118.9217 2012.3603,-109.8716 1893.6176,-106.61"/>
<polygon fill="#000000" stroke="#000000" points="1893.6058,-103.1085 1883.5156,-106.3394 1893.4183,-110.106 1893.6058,-103.1085"/>
<text text-anchor="middle" x="2345.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2357.5448,-275.6703C2480.2329,-267.2085 2782.5051,-243.176 2813.1938,-210 2850.3459,-169.8366 2841.8594,-136.3287 2818.1938,-87 2807.5434,-64.8003 2785.8839,-47.4894 2766.9674,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2768.6318,-32.6774 2758.2409,-30.6086 2765.0737,-38.7057 2768.6318,-32.6774"/>
<text text-anchor="middle" x="2880.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2254.4205,-277.0074C2077.6461,-270.0496 1481.6739,-245.3246 990.1938,-210 941.3496,-206.4894 885.8007,-201.3053 846.169,-197.4011"/>
<polygon fill="#000000" stroke="#000000" points="846.4925,-193.9161 836.196,-196.4125 845.802,-200.8819 846.4925,-193.9161"/>
<text text-anchor="middle" x="1538.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1176.1938" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1176.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1190.6127,-261.1748C1197.4469,-250.4779 1202.4919,-237.2063 1194.1938,-228 1168.3155,-199.2895 1047.072,-238.7105 1021.1938,-210 1010.4815,-198.1153 1010.6997,-186.0778 1021.1938,-174 1068.4128,-119.6546 1560.3367,-108.0867 1748.5273,-105.6456"/>
<polygon fill="#000000" stroke="#000000" points="1748.6461,-109.1445 1758.6016,-105.5199 1748.5587,-102.1451 1748.6461,-109.1445"/>
<text text-anchor="middle" x="1065.6938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1145.051,-264.1241C1132.5051,-257.8959 1118.0005,-250.3937 1105.1938,-243 1094.6247,-236.8981 1093.6541,-232.1952 1082.1938,-228 1040.2203,-212.6349 918.3746,-201.3218 847.004,-195.7928"/>
<polygon fill="#000000" stroke="#000000" points="847.0928,-192.2895 836.8557,-195.0192 846.5607,-199.2692 847.0928,-192.2895"/>
<text text-anchor="middle" x="1149.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node14" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="370.1938" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="370.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M394.5177,-261.5751C411.9412,-250.0316 436.4326,-235.6538 460.1938,-228 510.6482,-211.7479 658.1298,-200.3857 738.8502,-195.1913"/>
<polygon fill="#000000" stroke="#000000" points="739.5455,-198.6544 749.3042,-194.5291 739.1029,-191.6684 739.5455,-198.6544"/>
<text text-anchor="middle" x="526.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1821.1938" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1821.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1821.1938,-173.9735C1821.1938,-162.1918 1821.1938,-146.5607 1821.1938,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1824.6939,-133.0033 1821.1938,-123.0034 1817.6939,-133.0034 1824.6939,-133.0033"/>
<text text-anchor="middle" x="1868.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="587.1938" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="587.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M589.8172,-260.8464C592.3778,-249.7439 597.3984,-236.1527 607.1938,-228 626.9188,-211.5829 691.7092,-201.8038 739.2947,-196.6703"/>
<polygon fill="#000000" stroke="#000000" points="739.8818,-200.1283 749.467,-195.6145 739.1591,-193.1657 739.8818,-200.1283"/>
<text text-anchor="middle" x="698.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node17" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3095.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3095.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge29" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3070.6883,-88.2723C3052.5705,-76.7445 3026.8636,-62.0954 3002.1938,-54 2961.6756,-40.704 2844.2416,-28.2746 2778.3758,-22.0898"/>
<polygon fill="#000000" stroke="#000000" points="2778.5478,-18.5908 2768.2671,-21.1516 2777.9009,-25.5608 2778.5478,-18.5908"/>
<text text-anchor="middle" x="3087.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M826.571,-180.0749C845.35,-173.25 869.1765,-164.3979 890.1938,-156 905.9096,-149.7205 908.6871,-144.735 925.1938,-141 1004.3882,-123.0805 1549.5532,-110.4592 1748.6256,-106.4014"/>
<polygon fill="#000000" stroke="#000000" points="1748.7643,-109.8994 1758.6913,-106.1975 1748.6224,-102.9008 1748.7643,-109.8994"/>
<text text-anchor="middle" x="961.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M749.121,-193.4223C620.2657,-197.765 252.003,-211.5624 232.1938,-228 225.445,-233.6001 221.9293,-242.1695 220.1711,-250.6947"/>
<polygon fill="#000000" stroke="#000000" points="216.667,-250.4909 218.7989,-260.869 223.6042,-251.4266 216.667,-250.4909"/>
<text text-anchor="middle" x="268.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node23" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="828.1938" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="828.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M800.4458,-173.9735C805.3117,-161.8784 811.8096,-145.7263 817.2941,-132.0934"/>
<polygon fill="#000000" stroke="#000000" points="820.5855,-133.2894 821.0708,-122.7057 814.0914,-130.6768 820.5855,-133.2894"/>
<text text-anchor="middle" x="849.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pathology_file -->
<g id="node19" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="797.1938" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="797.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M795.4424,-260.701C794.9608,-255.0324 794.4901,-248.7623 794.1938,-243 793.821,-235.7505 793.5844,-227.9149 793.4351,-220.6116"/>
<polygon fill="#000000" stroke="#000000" points="796.9317,-220.3658 793.2729,-210.4228 789.9326,-220.4773 796.9317,-220.3658"/>
<text text-anchor="middle" x="855.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3263.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3263.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3231.0186,-88.1817C3207.1669,-76.5309 3173.5015,-61.769 3142.1938,-54 3074.4146,-37.1807 2871.1113,-25.058 2778.7557,-20.2654"/>
<polygon fill="#000000" stroke="#000000" points="2778.7522,-16.7607 2768.5861,-19.7441 2778.3938,-23.7515 2778.7522,-16.7607"/>
<text text-anchor="middle" x="3255.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- treatment_response -->
<g id="node21" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2001.1938" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2001.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1975.7506,-174.2887C1959.9386,-163.765 1938.9289,-150.6362 1919.1938,-141 1904.6303,-133.889 1888.2849,-127.3537 1873.179,-121.8594"/>
<polygon fill="#000000" stroke="#000000" points="1874.057,-118.4569 1863.4623,-118.4035 1871.7113,-125.0522 1874.057,-118.4569"/>
<text text-anchor="middle" x="2027.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3428.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3428.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3403.343,-88.4891C3384.0095,-76.5867 3356.0413,-61.3714 3329.1938,-54 3225.8201,-25.6172 2900.8212,-19.5998 2778.9598,-18.3339"/>
<polygon fill="#000000" stroke="#000000" points="2778.8666,-14.8329 2768.8328,-18.2349 2778.7981,-21.8326 2778.8666,-14.8329"/>
<text text-anchor="middle" x="3413.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M856.2137,-103.7197C1068.0691,-94.0393 2416.9555,-32.4043 2685.6694,-20.1259"/>
<polygon fill="#000000" stroke="#000000" points="2686.0257,-23.6133 2695.8555,-19.6604 2685.7062,-16.6206 2686.0257,-23.6133"/>
<text text-anchor="middle" x="1917.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M801.7915,-110.9833C785.8844,-116.0955 766.8856,-125.2193 757.1938,-141 751.4031,-150.4285 755.9568,-160.4481 763.5249,-169.0877"/>
<polygon fill="#000000" stroke="#000000" points="761.2041,-171.7155 770.7676,-176.2753 766.135,-166.7469 761.2041,-171.7155"/>
<text text-anchor="middle" x="781.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="981.1938" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="981.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M960.3462,-261.2327C945.0664,-248.486 925.4416,-232.756 916.1938,-228 893.4422,-216.2992 866.3144,-207.8467 843.3315,-202.085"/>
<polygon fill="#000000" stroke="#000000" points="843.9696,-198.6387 833.4283,-199.7021 842.332,-205.4445 843.9696,-198.6387"/>
<text text-anchor="middle" x="1009.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- radiology_file -->
<g id="node25" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2197.1938" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2197.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2174.9347,-174.6447C2158.9457,-163.1331 2136.3829,-148.7648 2114.1938,-141 2074.5185,-127.1162 1965.3898,-116.2441 1892.1033,-110.2245"/>
<polygon fill="#000000" stroke="#000000" points="1892.2609,-106.7259 1882.011,-109.4075 1891.696,-113.7031 1892.2609,-106.7259"/>
<text text-anchor="middle" x="2204.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
</g>
</svg>
</div>
