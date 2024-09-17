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
<svg width="3443pt" height="305pt"
 viewBox="0.00 0.00 3442.78 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3438.7843,-301 3438.7843,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="685.692" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="685.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx -->
<g id="node5" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="689.692" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="689.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M657.8998,-177.9137C643.4358,-168.5303 630.1868,-155.3243 637.692,-141 642.1454,-132.5004 649.618,-125.6086 657.5296,-120.2174"/>
<polygon fill="#000000" stroke="#000000" points="659.4494,-123.1462 666.1646,-114.9513 655.8046,-117.1699 659.4494,-123.1462"/>
<text text-anchor="middle" x="674.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1822.692" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1822.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M729.1197,-188.2787C773.3208,-183.6798 843.4311,-174.1335 901.692,-156 916.6896,-151.3321 918.4328,-144.7246 933.692,-141 1011.9114,-121.9078 1552.4217,-110.035 1750.3095,-106.2864"/>
<polygon fill="#000000" stroke="#000000" points="1750.3841,-109.7857 1760.3165,-106.0982 1750.2525,-102.7869 1750.3841,-109.7857"/>
<text text-anchor="middle" x="970.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="836.692" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="836.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M726.321,-184.6269C758.9641,-177.9971 801.4692,-167.547 814.692,-156 821.583,-149.9824 826.388,-141.4203 829.7067,-133.0263"/>
<polygon fill="#000000" stroke="#000000" points="833.0699,-134.0064 832.9557,-123.4121 826.4383,-131.7652 833.0699,-134.0064"/>
<text text-anchor="middle" x="861.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2269.692" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2269.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2189.6716,-181.0418C2161.205,-175.5455 2129.3674,-167.5219 2101.692,-156 2090.4254,-151.3094 2090.1189,-145.2855 2078.692,-141 2045.5837,-128.5831 1956.2464,-117.813 1892.4421,-111.3666"/>
<polygon fill="#000000" stroke="#000000" points="1892.7314,-107.8781 1882.4337,-110.3695 1892.0374,-114.8437 1892.7314,-107.8781"/>
<text text-anchor="middle" x="2181.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="583.692" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="583.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2657.692" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2657.692" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M627.6736,-92.6442C635.9437,-90.5723 644.5501,-88.5844 652.692,-87 764.4338,-65.256 793.1734,-62.5159 906.692,-54 1251.951,-28.0996 2368.6628,-19.7911 2611.0096,-18.2724"/>
<polygon fill="#000000" stroke="#000000" points="2611.2547,-21.771 2621.2328,-18.2091 2611.2113,-14.7712 2611.2547,-21.771"/>
<text text-anchor="middle" x="955.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2066.692" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2066.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2015.1965,-276.2783C1853.0309,-267.6306 1338.4131,-239.6034 912.692,-210 853.2944,-205.8697 785.2174,-200.3691 739.232,-196.5402"/>
<polygon fill="#000000" stroke="#000000" points="739.4475,-193.0461 729.1908,-195.7014 738.8647,-200.0218 739.4475,-193.0461"/>
<text text-anchor="middle" x="1461.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2070.2634,-260.9007C2074.9259,-231.4329 2079.1506,-173.153 2047.692,-141 2036.7999,-129.8674 1954.1617,-118.8081 1892.1711,-111.9448"/>
<polygon fill="#000000" stroke="#000000" points="1892.3465,-108.4433 1882.0259,-110.8383 1891.5875,-115.402 1892.3465,-108.4433"/>
<text text-anchor="middle" x="2115.192" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2118.521,-277.4723C2268.6708,-272.5313 2696.016,-254.6371 2738.692,-210 2776.5007,-170.454 2767.3577,-136.3287 2743.692,-87 2733.0416,-64.8003 2711.3822,-47.4894 2692.4656,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2694.1301,-32.6774 2683.7392,-30.6086 2690.572,-38.7057 2694.1301,-32.6774"/>
<text text-anchor="middle" x="2806.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M668.1575,-116.5769C663.1767,-118.9429 657.8289,-121.2431 652.692,-123 615.743,-135.6374 591.3145,-110.6904 566.692,-141 545.0887,-167.5931 591.4029,-180.599 632.4129,-186.7698"/>
<polygon fill="#000000" stroke="#000000" points="632.0208,-190.2489 642.4078,-188.1606 632.9856,-183.3157 632.0208,-190.2489"/>
<text text-anchor="middle" x="590.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M715.9952,-98.5375C733.6195,-94.4905 757.4074,-89.5711 778.692,-87 1149.3008,-42.2324 2357.5006,-22.3817 2610.8368,-18.6587"/>
<polygon fill="#000000" stroke="#000000" points="2611.209,-22.1538 2621.1569,-18.5083 2611.1069,-15.1545 2611.209,-22.1538"/>
<text text-anchor="middle" x="1294.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node6" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="89.692" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="89.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M115.3213,-261.5747C133.9697,-249.8723 160.3002,-235.3044 185.692,-228 268.015,-204.3183 519.3833,-195.7704 631.1399,-193.0847"/>
<polygon fill="#000000" stroke="#000000" points="631.2734,-196.5826 641.1889,-192.85 631.1099,-189.5845 631.2734,-196.5826"/>
<text text-anchor="middle" x="257.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="312.692" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="312.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M320.9739,-260.8023C327.1806,-249.3834 336.8184,-235.4559 349.692,-228 373.4986,-214.2123 542.804,-201.3023 631.611,-195.3859"/>
<polygon fill="#000000" stroke="#000000" points="632.019,-198.8667 641.7671,-194.7164 631.5585,-191.8819 632.019,-198.8667"/>
<text text-anchor="middle" x="441.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1881.4076,-98.8823C2039.1262,-82.4494 2469.6388,-37.5936 2611.6006,-22.8023"/>
<polygon fill="#000000" stroke="#000000" points="2612.1241,-26.2668 2621.7075,-21.7493 2611.3986,-19.3045 2612.1241,-26.2668"/>
<text text-anchor="middle" x="2340.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2440.692" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2440.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2401.1518,-179.9115C2393.7227,-177.8138 2385.9954,-175.7479 2378.692,-174 2336.8988,-163.9979 2323.5587,-172.0426 2283.692,-156 2272.3703,-151.4441 2272.2377,-144.9541 2260.692,-141 2195.0484,-118.5187 2001.5874,-109.8103 1895.0681,-106.6522"/>
<polygon fill="#000000" stroke="#000000" points="1895.1349,-103.1528 1885.0384,-106.3636 1894.9335,-110.1499 1895.1349,-103.1528"/>
<text text-anchor="middle" x="2327.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="895.692" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="895.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M867.1061,-263.4454C855.9607,-257.2445 843.1375,-249.9411 831.692,-243 821.257,-236.6717 819.7784,-233.1021 808.692,-228 785.275,-217.2231 757.8615,-208.8274 734.8648,-202.8649"/>
<polygon fill="#000000" stroke="#000000" points="735.5246,-199.4219 724.973,-200.3779 733.8177,-206.2106 735.5246,-199.4219"/>
<text text-anchor="middle" x="876.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M909.4663,-261.3128C913.4463,-255.669 917.5568,-249.2592 920.692,-243 935.1693,-214.0976 918.9261,-194.7747 943.692,-174 962.8821,-157.9026 1141.7717,-143.5223 1166.692,-141 1377.8527,-119.6278 1628.6274,-110.3051 1749.8662,-106.8067"/>
<polygon fill="#000000" stroke="#000000" points="1750.2359,-110.2977 1760.1326,-106.5155 1750.0374,-103.3006 1750.2359,-110.2977"/>
<text text-anchor="middle" x="988.192" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2862.692" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2862.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2835.9596,-88.0966C2818.2102,-77.3604 2794.131,-63.7087 2771.692,-54 2748.566,-43.994 2721.7353,-35.3819 2699.915,-29.092"/>
<polygon fill="#000000" stroke="#000000" points="2700.8482,-25.7188 2690.2733,-26.3689 2698.9455,-32.4552 2700.8482,-25.7188"/>
<text text-anchor="middle" x="2861.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="529.692" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="529.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M531.4563,-260.6135C533.4498,-249.7053 537.6882,-236.4087 546.692,-228 559.5015,-216.0372 600.1782,-206.3545 634.2426,-200.0565"/>
<polygon fill="#000000" stroke="#000000" points="634.8771,-203.4987 644.1039,-198.2915 633.6437,-196.6082 634.8771,-203.4987"/>
<text text-anchor="middle" x="613.192" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node13" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3028.692" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3028.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3001.8773,-88.3278C2982.1036,-76.8269 2954.1515,-62.1871 2927.692,-54 2851.722,-30.4934 2759.0551,-22.3352 2704.4078,-19.5041"/>
<polygon fill="#000000" stroke="#000000" points="2704.4866,-16.0039 2694.3303,-19.0204 2704.151,-22.9959 2704.4866,-16.0039"/>
<text text-anchor="middle" x="3021.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2620.692" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2620.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2540.8065,-179.7264C2476.8539,-169.8392 2397.2353,-157.3645 2393.692,-156 2382.3033,-151.6143 2382.2698,-144.8593 2370.692,-141 2326.7085,-126.3388 2033.208,-113.1742 1894.7451,-107.6958"/>
<polygon fill="#000000" stroke="#000000" points="1894.7774,-104.1944 1884.6476,-107.299 1894.5025,-111.189 1894.7774,-104.1944"/>
<text text-anchor="middle" x="2479.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2602.1205,-174.1098C2582.7445,-153.1682 2557.0737,-117.4704 2571.692,-87 2582.3424,-64.8003 2604.0019,-47.4894 2622.9184,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2624.8121,-38.7057 2631.6449,-30.6086 2621.254,-32.6774 2624.8121,-38.7057"/>
<text text-anchor="middle" x="2657.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1099.692" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1099.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1127.7159,-176.0088C1150.1875,-164.0507 1182.9426,-148.5201 1213.692,-141 1313.4347,-116.6067 1611.4523,-108.5127 1750.173,-106.0213"/>
<polygon fill="#000000" stroke="#000000" points="1750.3453,-109.5189 1760.2826,-105.8446 1750.2229,-102.5199 1750.3453,-109.5189"/>
<text text-anchor="middle" x="1260.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1248.692" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1248.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1274.9548,-175.1216C1294.6857,-163.3606 1322.8223,-148.488 1349.692,-141 1422.9688,-120.5794 1636.7937,-110.8842 1750.1669,-107.0688"/>
<polygon fill="#000000" stroke="#000000" points="1750.6048,-110.5564 1760.4839,-106.7285 1750.374,-103.5602 1750.6048,-110.5564"/>
<text text-anchor="middle" x="1408.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="706.692" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="706.692" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M694.4827,-261.0569C691.3363,-255.5068 688.3671,-249.2129 686.692,-243 684.7491,-235.7935 683.9771,-227.8043 683.8156,-220.3289"/>
<polygon fill="#000000" stroke="#000000" points="687.3163,-220.279 683.9354,-210.2382 680.3168,-220.1959 687.3163,-220.279"/>
<text text-anchor="middle" x="747.692" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1425.692" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1425.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1445.8163,-174.2868C1460.1099,-162.769 1480.3118,-148.5379 1500.692,-141 1545.1517,-124.5561 1670.6392,-114.1604 1751.1919,-108.9765"/>
<polygon fill="#000000" stroke="#000000" points="1751.5117,-112.4634 1761.2711,-108.3399 1751.0704,-105.4773 1751.5117,-112.4634"/>
<text text-anchor="middle" x="1568.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node20" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1633.692" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1633.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1635.612,-173.941C1637.7406,-162.8762 1642.2288,-149.2916 1651.692,-141 1666.9956,-127.5913 1713.207,-118.3507 1753.7363,-112.5914"/>
<polygon fill="#000000" stroke="#000000" points="1754.4622,-116.0248 1763.8956,-111.2018 1753.5135,-109.0894 1754.4622,-116.0248"/>
<text text-anchor="middle" x="1734.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3179.692" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3179.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3154.6632,-88.4274C3135.5256,-76.6577 3108.0339,-61.6395 3081.692,-54 3011.9356,-33.7696 2799.1979,-23.3782 2704.2743,-19.6464"/>
<polygon fill="#000000" stroke="#000000" points="2704.2368,-16.1425 2694.1094,-19.2547 2703.9671,-23.1373 2704.2368,-16.1425"/>
<text text-anchor="middle" x="3168.692" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3347.692" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3347.692" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3315.2416,-88.214C3290.7725,-76.4178 3256.0126,-61.4607 3223.692,-54 3125.3247,-31.2935 2821.3817,-21.8649 2704.319,-19.0118"/>
<polygon fill="#000000" stroke="#000000" points="2704.322,-15.5109 2694.2413,-18.7712 2704.1549,-22.5089 2704.322,-15.5109"/>
<text text-anchor="middle" x="3338.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- molecular_test -->
<g id="node23" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1836.692" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1836.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1828.8924,-174.0075C1826.797,-168.3513 1824.805,-162.0113 1823.692,-156 1822.3332,-148.6609 1821.7608,-140.6264 1821.6041,-133.1499"/>
<polygon fill="#000000" stroke="#000000" points="1825.1041,-133.0884 1821.6209,-123.0825 1818.1041,-133.0766 1825.1041,-133.0884"/>
<text text-anchor="middle" x="1887.692" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M793.6688,-113.8585C773.1203,-119.4426 748.8871,-128.0991 729.692,-141 719.7347,-147.6923 710.6917,-157.2115 703.4293,-166.217"/>
<polygon fill="#000000" stroke="#000000" points="700.5822,-164.1783 697.2852,-174.2471 706.1415,-168.432 700.5822,-164.1783"/>
<text text-anchor="middle" x="770.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge31" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M885.8706,-102.6504C1145.7478,-90.2346 2356.7999,-32.3754 2610.8626,-20.2373"/>
<polygon fill="#000000" stroke="#000000" points="2611.3908,-23.7162 2621.2124,-19.7428 2611.0567,-16.7241 2611.3908,-23.7162"/>
<text text-anchor="middle" x="1896.192" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node25" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1982.692" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1982.692" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1975.8212,-174.0046C1970.7336,-162.9651 1962.7588,-149.3849 1951.692,-141 1934.0931,-127.6659 1911.8004,-119.2706 1890.7178,-113.9849"/>
<polygon fill="#000000" stroke="#000000" points="1891.3465,-110.5381 1880.8156,-111.7003 1889.7728,-117.3589 1891.3465,-110.5381"/>
<text text-anchor="middle" x="2004.192" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
</g>
</svg>
</div>
