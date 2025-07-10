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
<svg width="3604pt" height="392pt"
 viewBox="0.00 0.00 3603.74 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3599.7388,-388 3599.7388,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1841.3956" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1841.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node12" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2126.3956" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2126.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1884.3716,-178.881C1933.559,-163.8659 2014.345,-139.2049 2068.9129,-122.5474"/>
<polygon fill="#000000" stroke="#000000" points="2070.2409,-125.8015 2078.7833,-119.5343 2068.1971,-119.1065 2070.2409,-125.8015"/>
<text text-anchor="middle" x="2050.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="627.3956" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="627.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="672.3956" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="672.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M621.994,-347.6353C620.0464,-337.5066 619.3978,-324.9957 624.3956,-315 627.3305,-309.1303 631.7278,-303.9694 636.69,-299.5238"/>
<polygon fill="#000000" stroke="#000000" points="639.1266,-302.0604 644.8239,-293.1278 634.7997,-296.5579 639.1266,-302.0604"/>
<text text-anchor="middle" x="685.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node3" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1649.3956" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1649.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1669.3267,-261.6086C1682.7206,-250.6721 1701.1914,-236.9805 1719.3956,-228 1738.7129,-218.4703 1761.0207,-210.9764 1781.2359,-205.3503"/>
<polygon fill="#000000" stroke="#000000" points="1782.2185,-208.7105 1790.9693,-202.7377 1780.4038,-201.9498 1782.2185,-208.7105"/>
<text text-anchor="middle" x="1778.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="811.3956" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="811.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M791.1458,-348.2849C778.7185,-337.8867 762.2038,-324.8896 746.3956,-315 735.7031,-308.3107 723.585,-301.9538 712.2962,-296.4956"/>
<polygon fill="#000000" stroke="#000000" points="713.5953,-293.2386 703.0581,-292.1346 710.6069,-299.5687 713.5953,-293.2386"/>
<text text-anchor="middle" x="838.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment_response -->
<g id="node5" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1845.3956" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1845.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1843.6443,-260.701C1843.1627,-255.0324 1842.6919,-248.7623 1842.3956,-243 1842.0229,-235.7505 1841.7863,-227.9149 1841.6369,-220.6116"/>
<polygon fill="#000000" stroke="#000000" points="1845.1335,-220.3658 1841.4747,-210.4228 1838.1344,-220.4773 1845.1335,-220.3658"/>
<text text-anchor="middle" x="1925.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cell_line -->
<g id="node6" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="49.3956" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="49.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2781.3956" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2781.3956" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M42.4029,-347.975C36.294,-330.5896 28.3956,-303.3946 28.3956,-279 28.3956,-279 28.3956,-279 28.3956,-105 28.3956,-34.3974 2372.6602,-20.0136 2734.6882,-18.2132"/>
<polygon fill="#000000" stroke="#000000" points="2734.8338,-21.7126 2744.8165,-18.1636 2734.7995,-14.7127 2734.8338,-21.7126"/>
<text text-anchor="middle" x="68.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M82.0929,-352.389C98.1631,-345.68 117.8089,-337.4494 135.3956,-330 150.9792,-323.3991 153.9497,-318.9939 170.3956,-315 254.0717,-294.679 506.4678,-284.3093 618.1856,-280.6131"/>
<polygon fill="#000000" stroke="#000000" points="618.347,-284.1098 628.2279,-280.2864 618.1193,-277.1135 618.347,-284.1098"/>
<text text-anchor="middle" x="210.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node7" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2068.3956" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2068.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2049.6392,-261.2896C2035.6021,-248.3834 2017.3453,-232.4164 2008.3956,-228 1978.287,-213.1424 1942.1511,-204.3854 1911.206,-199.2389"/>
<polygon fill="#000000" stroke="#000000" points="1911.348,-195.7185 1900.9267,-197.6284 1910.2644,-202.6341 1911.348,-195.7185"/>
<text text-anchor="middle" x="2106.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="847.3956" cy="-279" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="847.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M856.2397,-260.9798C863.02,-249.325 873.5628,-235.0563 887.3956,-228 926.4353,-208.0853 1552.3388,-196.5016 1768.5861,-193.0785"/>
<polygon fill="#000000" stroke="#000000" points="1768.9329,-196.5736 1778.8766,-192.9169 1768.8229,-189.5745 1768.9329,-196.5736"/>
<text text-anchor="middle" x="973.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M849.77,-260.8551C852.234,-249.6093 857.2404,-235.8563 867.3956,-228 1282.0097,92.7564 1517.1462,-142.5747 2038.3956,-87 2301.9259,-58.9028 2618.7485,-31.6486 2735.3989,-21.8329"/>
<polygon fill="#000000" stroke="#000000" points="2735.7349,-25.3171 2745.4069,-20.9922 2735.149,-18.3416 2735.7349,-25.3171"/>
<text text-anchor="middle" x="1081.3956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- genetic_analysis -->
<g id="node9" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1042.3956" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1042.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1065.1516,-348.4601C1075.4869,-338.3635 1083.7369,-325.6135 1075.3956,-315 1054.4804,-288.3874 1022.3109,-323.6126 1001.3956,-297 991.5089,-284.4201 991.0953,-273.2435 1001.3956,-261 1015.1898,-244.6035 1170.1067,-230.4299 1191.3956,-228 1400.0703,-204.1818 1648.303,-195.9733 1768.7012,-193.2629"/>
<polygon fill="#000000" stroke="#000000" points="1768.9776,-196.7578 1778.8986,-193.0397 1768.8244,-189.7595 1768.9776,-196.7578"/>
<text text-anchor="middle" x="1071.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M990.4561,-351.4472C972.6138,-345.6884 952.769,-338.4186 935.3956,-330 924.4131,-324.6782 923.9092,-319.0466 912.3956,-315 835.2931,-287.9017 809.4604,-313.3935 729.3956,-297 724.9287,-296.0854 720.316,-294.9545 715.7392,-293.7085"/>
<polygon fill="#000000" stroke="#000000" points="716.427,-290.2637 705.8476,-290.8362 714.4749,-296.986 716.427,-290.2637"/>
<text text-anchor="middle" x="1005.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- exposure -->
<g id="node10" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2360.3956" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2360.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2327.8074,-264.6555C2299.464,-252.8246 2256.996,-236.632 2218.3956,-228 2161.9612,-215.3799 2005.0819,-203.1057 1912.4411,-196.6607"/>
<polygon fill="#000000" stroke="#000000" points="1912.5193,-193.1578 1902.302,-195.9607 1912.0371,-200.1412 1912.5193,-193.1578"/>
<text text-anchor="middle" x="2312.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1427.3956" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1427.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1430.9261,-347.9978C1436.5875,-324.1774 1450.0713,-282.6775 1478.3956,-261 1523.3234,-226.6153 1678.6703,-206.8566 1770.9466,-197.8927"/>
<polygon fill="#000000" stroke="#000000" points="1771.4263,-201.3629 1781.0491,-196.9299 1770.7621,-194.3945 1771.4263,-201.3629"/>
<text text-anchor="middle" x="1522.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1395.0705,-351.41C1366.1927,-339.163 1322.3935,-322.5007 1282.3956,-315 1040.7007,-269.6757 971.7916,-338.4115 729.3956,-297 724.7189,-296.201 719.8946,-295.1133 715.1247,-293.8655"/>
<polygon fill="#000000" stroke="#000000" points="716.0508,-290.4902 705.4747,-291.1206 714.1356,-297.2231 716.0508,-290.4902"/>
<text text-anchor="middle" x="1378.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge38" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2194.946,-95.8948C2329.1954,-78.0632 2623.4827,-38.9747 2736.2198,-24.0005"/>
<polygon fill="#000000" stroke="#000000" points="2736.785,-27.4562 2746.237,-22.6699 2735.8632,-20.5172 2736.785,-27.4562"/>
<text text-anchor="middle" x="2555.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2872.3956" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2872.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2853.9804,-87.3943C2840.0936,-74.1179 2820.9146,-55.7818 2805.7585,-41.292"/>
<polygon fill="#000000" stroke="#000000" points="2807.8957,-38.4931 2798.2489,-34.1125 2803.0584,-43.5528 2807.8957,-38.4931"/>
<text text-anchor="middle" x="2882.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2479.3956" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2479.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2451.9408,-264.0823C2428.3909,-252.0669 2393.1682,-235.9184 2360.3956,-228 2277.7772,-208.0381 2036.1167,-197.9696 1913.9226,-194.0369"/>
<polygon fill="#000000" stroke="#000000" points="1914.0123,-190.5381 1903.9065,-193.7197 1913.7907,-197.5346 1914.0123,-190.5381"/>
<text text-anchor="middle" x="2442.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="200.3956" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="200.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M223.7871,-348.4562C240.574,-336.8581 264.2323,-322.4639 287.3956,-315 347.4597,-295.6455 526.9454,-285.3026 618.0536,-281.1738"/>
<polygon fill="#000000" stroke="#000000" points="618.3469,-284.6643 628.1817,-280.7239 618.0362,-277.6712 618.3469,-284.6643"/>
<text text-anchor="middle" x="353.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="669.3956" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="669.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M682.123,-175.6014C707.7539,-144.1617 769.1728,-76.5262 839.3956,-54 932.3676,-24.1763 2447.0536,-18.8495 2734.5054,-18.1058"/>
<polygon fill="#000000" stroke="#000000" points="2734.604,-21.6056 2744.595,-18.0802 2734.5862,-14.6056 2734.604,-21.6056"/>
<text text-anchor="middle" x="799.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M643.2692,-199.0614C618.3709,-207.202 586.4533,-222.1869 599.3956,-243 605.5133,-252.8381 615.1996,-260.0671 625.5413,-265.3491"/>
<polygon fill="#000000" stroke="#000000" points="624.1715,-268.5709 634.7249,-269.5063 627.0582,-262.1938 624.1715,-268.5709"/>
<text text-anchor="middle" x="623.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="417.3956" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="417.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M418.7789,-347.7783C420.6176,-336.6487 424.8269,-323.0528 434.3956,-315 461.4092,-292.266 556.4525,-283.8591 617.9494,-280.7706"/>
<polygon fill="#000000" stroke="#000000" points="618.4411,-284.2515 628.2659,-280.2863 618.1127,-277.2592 618.4411,-284.2515"/>
<text text-anchor="middle" x="525.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M698.8536,-264.5162C722.7646,-252.2491 759.3318,-235.4963 793.3956,-228 887.7966,-207.2254 1546.8469,-196.1434 1768.7036,-192.97"/>
<polygon fill="#000000" stroke="#000000" points="1768.9844,-196.4664 1778.9338,-192.8248 1768.8851,-189.4671 1768.9844,-196.4664"/>
<text text-anchor="middle" x="829.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M628.0432,-280.1059C490.587,-283.7279 79.6314,-296.0971 58.3956,-315 51.9501,-320.7375 49.0725,-329.3413 47.9935,-337.8557"/>
<polygon fill="#000000" stroke="#000000" points="44.4902,-337.8257 47.4505,-347.9985 51.4802,-338.2 44.4902,-337.8257"/>
<text text-anchor="middle" x="94.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M671.2511,-260.6918C670.9309,-255.0228 670.6118,-248.7548 670.3956,-243 670.1231,-235.7461 669.9226,-227.9088 669.7759,-220.6054"/>
<polygon fill="#000000" stroke="#000000" points="673.2721,-220.3544 669.5973,-210.4173 666.2732,-220.4771 673.2721,-220.3544"/>
<text text-anchor="middle" x="706.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node20" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3023.3956" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3023.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2999.2335,-87.9179C2982.5487,-76.828 2959.4712,-62.8438 2937.3956,-54 2901.425,-39.5896 2858.3678,-30.198 2826.61,-24.6326"/>
<polygon fill="#000000" stroke="#000000" points="2827.1633,-21.1766 2816.7194,-22.9586 2825.9951,-28.0784 2827.1633,-21.1766"/>
<text text-anchor="middle" x="3022.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- laboratory_test -->
<g id="node21" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1267.3956" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1267.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1274.9932,-347.8503C1287.3259,-318.5653 1310.7017,-263.8547 1314.3956,-261 1349.8411,-233.6069 1634.7531,-208.069 1770.2661,-197.334"/>
<polygon fill="#000000" stroke="#000000" points="1770.8513,-200.7989 1780.546,-196.5254 1770.3023,-193.8204 1770.8513,-200.7989"/>
<text text-anchor="middle" x="1379.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1222.4002,-350.8781C1184.6795,-338.9104 1129.1565,-322.9356 1079.3956,-315 925.5781,-290.4701 882.6783,-324.676 729.3956,-297 724.7266,-296.157 719.9074,-295.041 715.1404,-293.7764"/>
<polygon fill="#000000" stroke="#000000" points="716.0711,-290.4023 705.4938,-291.0118 714.1426,-297.1314 716.0711,-290.4023"/>
<text text-anchor="middle" x="1212.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2630.3956" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2630.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2593.6241,-262.6951C2565.0059,-250.8181 2523.9701,-235.5412 2486.3956,-228 2378.7437,-206.3942 2058.4473,-196.779 1913.7626,-193.4516"/>
<polygon fill="#000000" stroke="#000000" points="1913.7308,-189.9501 1903.6542,-193.2229 1913.5724,-196.9483 1913.7308,-189.9501"/>
<text text-anchor="middle" x="2606.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2204.3956" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2204.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2205.2615,-347.7677C2206.4356,-314.1674 2206.7713,-244.4033 2190.3956,-228 2171.2502,-208.8223 2010.0847,-198.9112 1913.594,-194.6505"/>
<polygon fill="#000000" stroke="#000000" points="1913.7436,-191.1538 1903.6019,-194.2192 1913.4417,-198.1473 1913.7436,-191.1538"/>
<text text-anchor="middle" x="2246.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2254.5681,-360.8154C2381.4774,-347.505 2706.5048,-312.1163 2724.3956,-297 2746.2479,-278.5366 2743.3956,-264.108 2743.3956,-235.5 2743.3956,-235.5 2743.3956,-235.5 2743.3956,-105 2743.3956,-83.0273 2753.7006,-60.3464 2763.5778,-43.6535"/>
<polygon fill="#000000" stroke="#000000" points="2766.629,-45.375 2768.953,-35.0382 2760.6901,-41.6696 2766.629,-45.375"/>
<text text-anchor="middle" x="2785.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2153.525,-361.958C2029.4846,-352.2556 1701.5374,-327.5267 1427.3956,-315 1272.3947,-307.9173 882.4297,-322.6129 729.3956,-297 724.7162,-296.2168 719.8903,-295.1393 715.1193,-293.8975"/>
<polygon fill="#000000" stroke="#000000" points="716.0437,-290.5217 705.4681,-291.1596 714.1333,-297.256 716.0437,-290.5217"/>
<text text-anchor="middle" x="1725.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node24" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3198.3956" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3198.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3167.1196,-88.0634C3144.5097,-76.5913 3112.8806,-62.0977 3083.3956,-54 2995.256,-29.7934 2888.2287,-21.8629 2828.1584,-19.2651"/>
<polygon fill="#000000" stroke="#000000" points="2827.9925,-15.7558 2817.8604,-18.8525 2827.7122,-22.7502 2827.9925,-15.7558"/>
<text text-anchor="middle" x="3194.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node25" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3363.3956" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3363.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3339.2304,-88.3346C3320.7284,-76.5176 3294.0978,-61.4809 3268.3956,-54 3186.6475,-30.2063 2933.3957,-21.5883 2828.0775,-18.9796"/>
<polygon fill="#000000" stroke="#000000" points="2827.8442,-15.473 2817.763,-18.7317 2827.6759,-22.471 2827.8442,-15.473"/>
<text text-anchor="middle" x="3351.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2789.3956" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2789.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2782.514,-348.052C2768.732,-315.2635 2734.1934,-247.2771 2678.3956,-228 2607.2727,-203.4284 2104.1903,-195.058 1913.9899,-192.7524"/>
<polygon fill="#000000" stroke="#000000" points="1913.8549,-189.2506 1903.8139,-192.6312 1913.7715,-196.2501 1913.8549,-189.2506"/>
<text text-anchor="middle" x="2807.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2816.633,-349.5212C2833.8608,-337.3967 2854.6554,-319.1963 2864.3956,-297 2870.825,-282.3486 2867.2007,-276.7522 2864.3956,-261 2857.1726,-220.4388 2850.5533,-210.9822 2832.3956,-174 2820.6022,-149.9799 2810.0643,-147.9513 2800.3956,-123 2790.7184,-98.0268 2785.9117,-67.7723 2783.5607,-46.1665"/>
<polygon fill="#000000" stroke="#000000" points="2787.0255,-45.6348 2782.5678,-36.0234 2780.0588,-46.3169 2787.0255,-45.6348"/>
<text text-anchor="middle" x="2902.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2725.1733,-362.0453C2564.6275,-352.3191 2132.8312,-327.1444 1772.3956,-315 1656.5552,-311.0969 843.7922,-315.6453 729.3956,-297 724.6521,-296.2269 719.7594,-295.1444 714.9267,-293.8897"/>
<polygon fill="#000000" stroke="#000000" points="715.734,-290.4807 705.1583,-291.1166 713.8224,-297.2146 715.734,-290.4807"/>
<text text-anchor="middle" x="2160.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment -->
<g id="node27" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1208.3956" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1208.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1199.3554,-260.729C1195.4058,-249.8643 1193.2915,-236.5728 1201.3956,-228 1220.6235,-207.6602 1604.9816,-197.0544 1768.6322,-193.4462"/>
<polygon fill="#000000" stroke="#000000" points="1769.1648,-196.9356 1779.0862,-193.2187 1769.0124,-189.9372 1769.1648,-196.9356"/>
<text text-anchor="middle" x="1248.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study_funding -->
<g id="node28" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3518.3956" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3518.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3488.9764,-88.2556C3466.5592,-76.3982 3434.5181,-61.3457 3404.3956,-54 3295.1075,-27.349 2953.1819,-20.247 2827.9536,-18.5153"/>
<polygon fill="#000000" stroke="#000000" points="2827.9617,-15.0151 2817.9159,-18.3816 2827.8684,-22.0145 2827.9617,-15.0151"/>
<text text-anchor="middle" x="3508.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
