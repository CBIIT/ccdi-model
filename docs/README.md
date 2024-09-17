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
<svg width="2879pt" height="305pt"
 viewBox="0.00 0.00 2878.89 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2874.887,-301 2874.887,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node25" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2149.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2149.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8338,-87.0027C79.8119,-75.9626 79.6922,-62.3822 88.0923,-54 106.5264,-35.6053 1796.7287,-20.8881 2102.0852,-18.3782"/>
<polygon fill="#000000" stroke="#000000" points="2102.3875,-21.876 2112.3584,-18.2941 2102.3301,-14.8762 2102.3875,-21.876"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cell_line -->
<g id="node2" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2033.0923" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2033.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample -->
<g id="node22" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="466.0923" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="466.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1987.7671,-271.6935C1964.0778,-268.0726 1934.5761,-263.8722 1908.0923,-261 1708.2836,-239.3306 1657.8589,-237.2647 1457.0923,-228 1352.9617,-223.1947 621.7724,-227.9741 519.0923,-210 515.3801,-209.3502 511.5764,-208.4842 507.794,-207.4824"/>
<polygon fill="#000000" stroke="#000000" points="508.4908,-204.0389 497.9092,-204.5686 506.5115,-210.7533 508.4908,-204.0389"/>
<text text-anchor="middle" x="1761.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge29" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2075.8408,-269.8392C2127.8956,-257.7456 2211.2306,-235.0366 2230.0923,-210 2263.0134,-166.3012 2258.7579,-136.3287 2235.0923,-87 2224.4419,-64.8003 2202.7824,-47.4894 2183.8659,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2185.5303,-32.6774 2175.1394,-30.6086 2181.9722,-38.7057 2185.5303,-32.6774"/>
<text text-anchor="middle" x="2293.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1319.0923" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1319.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge21" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1377.787,-98.8477C1534.8502,-82.3844 1962.3665,-37.5725 2103.3274,-22.797"/>
<polygon fill="#000000" stroke="#000000" points="2103.7824,-26.2686 2113.363,-21.7451 2103.0526,-19.3068 2103.7824,-26.2686"/>
<text text-anchor="middle" x="1834.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- molecular_test -->
<g id="node4" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="826.0923" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="826.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M847.6288,-174.6491C863.3903,-162.9817 885.8268,-148.4252 908.0923,-141 968.94,-120.7083 1145.8122,-111.1888 1246.5842,-107.3007"/>
<polygon fill="#000000" stroke="#000000" points="1246.8287,-110.7941 1256.6897,-106.9198 1246.5649,-103.799 1246.8287,-110.7941"/>
<text text-anchor="middle" x="972.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="454.0923" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="454.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M456.5787,-260.9735C458.2038,-249.1918 460.3598,-233.5607 462.2084,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="465.7098,-220.3878 463.609,-210.0034 458.7754,-219.4313 465.7098,-220.3878"/>
<text text-anchor="middle" x="552.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2347.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2347.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2322.5924,-87.9652C2306.2806,-77.1751 2284.0681,-63.5127 2263.0923,-54 2240.1439,-43.5928 2213.3224,-34.96 2191.4626,-28.7593"/>
<polygon fill="#000000" stroke="#000000" points="2192.3712,-25.3793 2181.7998,-26.0839 2190.5033,-32.1255 2192.3712,-25.3793"/>
<text text-anchor="middle" x="2347.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_response -->
<g id="node7" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1029.0923" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1029.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1032.604,-173.842C1035.7582,-162.5908 1041.5793,-148.8367 1052.0923,-141 1081.9657,-118.7312 1178.0696,-110.2369 1246.3966,-106.9971"/>
<polygon fill="#000000" stroke="#000000" points="1246.8527,-110.4803 1256.687,-106.5385 1246.541,-103.4873 1246.8527,-110.4803"/>
<text text-anchor="middle" x="1135.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="466.0923" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="466.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M439.6987,-111.2009C424.0837,-116.3742 405.5597,-125.485 396.0923,-141 386.6019,-156.5527 401.7783,-168.8083 420.3969,-177.4037"/>
<polygon fill="#000000" stroke="#000000" points="419.1457,-180.6744 429.7204,-181.3276 421.8611,-174.2225 419.1457,-180.6744"/>
<text text-anchor="middle" x="420.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M494.2477,-103.5446C690.5806,-93.3954 1854.5198,-33.2275 2102.6016,-20.4033"/>
<polygon fill="#000000" stroke="#000000" points="2102.9132,-23.8919 2112.7192,-19.8802 2102.5518,-16.9013 2102.9132,-23.8919"/>
<text text-anchor="middle" x="1433.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="677.0923" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="677.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M671.5057,-261.0147C667.0229,-249.6855 659.5547,-235.7781 648.0923,-228 600.1908,-195.4952 575.4165,-223.3675 519.0923,-210 515.6796,-209.1901 512.1757,-208.2507 508.6741,-207.2345"/>
<polygon fill="#000000" stroke="#000000" points="509.4773,-203.8195 498.8897,-204.2109 507.4106,-210.5074 509.4773,-203.8195"/>
<text text-anchor="middle" x="734.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- publication -->
<g id="node10" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2498.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2498.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2474.4428,-88.293C2456.9412,-76.7753 2432.0744,-62.1296 2408.0923,-54 2369.7069,-40.9879 2258.8645,-28.6135 2195.317,-22.3176"/>
<polygon fill="#000000" stroke="#000000" points="2195.4578,-18.8148 2185.1643,-21.3236 2194.7756,-25.7815 2195.4578,-18.8148"/>
<text text-anchor="middle" x="2492.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2656.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2656.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2627.5364,-88.271C2606.1369,-76.5843 2575.7325,-61.7392 2547.0923,-54 2481.9413,-36.3948 2285.9589,-24.7569 2195.6219,-20.184"/>
<polygon fill="#000000" stroke="#000000" points="2195.5651,-16.6769 2185.403,-19.6741 2195.2161,-23.6682 2195.5651,-16.6769"/>
<text text-anchor="middle" x="2649.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- survival -->
<g id="node12" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1200.0923" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1200.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1209.4362,-174.0475C1215.7682,-163.3027 1224.9926,-150.0254 1236.0923,-141 1245.235,-133.5658 1256.1474,-127.3972 1267.007,-122.3907"/>
<polygon fill="#000000" stroke="#000000" points="1268.7028,-125.4707 1276.4909,-118.2877 1265.9233,-119.0461 1268.7028,-125.4707"/>
<text text-anchor="middle" x="1275.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node13" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1802.0923" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1802.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1782.6503,-174.89C1768.1271,-163.1772 1747.2173,-148.4638 1726.0923,-141 1666.2791,-119.8669 1491.376,-110.691 1391.3974,-107.0798"/>
<polygon fill="#000000" stroke="#000000" points="1391.4863,-103.5809 1381.3694,-106.7272 1391.2402,-110.5766 1391.4863,-103.5809"/>
<text text-anchor="middle" x="1803.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="861.0923" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="861.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M848.6151,-261.0093C839.4343,-249.3677 825.845,-235.1026 810.0923,-228 751.0282,-201.369 582.6598,-222.528 519.0923,-210 515.4455,-209.2813 511.7052,-208.3755 507.9809,-207.3546"/>
<polygon fill="#000000" stroke="#000000" points="508.8185,-203.9518 498.2345,-204.4327 506.8083,-210.657 508.8185,-203.9518"/>
<text text-anchor="middle" x="893.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- family_relationship -->
<g id="node15" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="628.0923" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="628.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M650.7509,-174.4613C667.315,-162.7054 690.8568,-148.1202 714.0923,-141 763.8171,-125.7624 1097.5826,-112.5888 1247.0051,-107.3795"/>
<polygon fill="#000000" stroke="#000000" points="1247.1345,-110.8772 1257.0074,-107.0331 1246.8922,-103.8814 1247.1345,-110.8772"/>
<text text-anchor="middle" x="793.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2811.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2811.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2787.0604,-88.5078C2768.3472,-76.6152 2741.2408,-61.4039 2715.0923,-54 2617.957,-26.4962 2313.2722,-19.9558 2195.8656,-18.4419"/>
<polygon fill="#000000" stroke="#000000" points="2195.8,-14.941 2185.7579,-18.3182 2195.7142,-21.9405 2195.8,-14.941"/>
<text text-anchor="middle" x="2798.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="268.0923" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="268.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M274.7036,-261.0219C283.7891,-238.3538 302.0259,-199.2952 328.0923,-174 350.494,-152.261 359.9575,-149.1433 390.0923,-141 471.7351,-118.9377 1042.3744,-108.8705 1246.6063,-105.9453"/>
<polygon fill="#000000" stroke="#000000" points="1246.683,-109.4447 1256.6324,-105.8033 1246.5837,-102.4454 1246.683,-109.4447"/>
<text text-anchor="middle" x="370.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M297.037,-263.7228C317.4851,-253.1643 345.666,-239.081 371.0923,-228 387.6956,-220.7641 406.2644,-213.5408 422.5505,-207.4842"/>
<polygon fill="#000000" stroke="#000000" points="424.1825,-210.6131 432.3579,-203.8742 421.7644,-204.044 424.1825,-210.6131"/>
<text text-anchor="middle" x="413.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M260.7747,-260.8591C250.5886,-232.3607 236.131,-176.6795 262.0923,-141 307.9878,-77.9243 352.3143,-100.787 429.0923,-87 763.6737,-26.9194 1861.8729,-19.1308 2102.3047,-18.1413"/>
<polygon fill="#000000" stroke="#000000" points="2102.4674,-21.6407 2112.4535,-18.1015 2102.4399,-14.6408 2102.4674,-21.6407"/>
<text text-anchor="middle" x="304.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1038.0923" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1038.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1017.2523,-261.3307C1001.9559,-249.5133 980.0927,-234.9083 958.0923,-228 864.9393,-198.7492 615.0783,-227.8823 519.0923,-210 515.4382,-209.3192 511.6928,-208.4401 507.9651,-207.437"/>
<polygon fill="#000000" stroke="#000000" points="508.7958,-204.0327 498.2133,-204.5434 506.8046,-210.7435 508.7958,-204.0327"/>
<text text-anchor="middle" x="1055.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2112.0923" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2112.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2033.1199,-179.6275C1992.3206,-172.6236 1947.1688,-163.7426 1928.0923,-156 1916.7842,-151.4104 1916.6782,-144.8347 1905.0923,-141 1857.5187,-125.2542 1537.2326,-112.4559 1391.2947,-107.3683"/>
<polygon fill="#000000" stroke="#000000" points="1391.2097,-103.8634 1381.0946,-107.0154 1390.9676,-110.8592 1391.2097,-103.8634"/>
<text text-anchor="middle" x="2014.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2111.6,-173.8091C2110.4565,-163.2422 2107.4774,-150.235 2100.0923,-141 2088.671,-126.718 2072.7908,-138.5035 2063.0923,-123 2054.6067,-109.4355 2056.1715,-101.4258 2063.0923,-87 2073.7427,-64.8003 2095.4021,-47.4894 2114.3187,-35.7591"/>
<polygon fill="#000000" stroke="#000000" points="2116.2123,-38.7057 2123.0452,-30.6086 2112.6543,-32.6774 2116.2123,-38.7057"/>
<text text-anchor="middle" x="2149.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1844.0923" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1844.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1853.4584,-260.9015C1868.1785,-229.7475 1891.4163,-166.8471 1854.0923,-141 1816.9936,-115.309 1529.1772,-107.8831 1391.7193,-105.7921"/>
<polygon fill="#000000" stroke="#000000" points="1391.7387,-102.2921 1381.6884,-105.645 1391.636,-109.2914 1391.7387,-102.2921"/>
<text text-anchor="middle" x="1919.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1790.9942,-274.4749C1672.0437,-264.5031 1375.0861,-240.5296 1126.0923,-228 991.3146,-221.2179 651.8957,-233.9636 519.0923,-210 515.3836,-209.3308 511.5822,-208.4513 507.8014,-207.4405"/>
<polygon fill="#000000" stroke="#000000" points="508.5014,-203.9975 497.9191,-204.5127 506.513,-210.7092 508.5014,-203.9975"/>
<text text-anchor="middle" x="1408.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1319.0923" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1319.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1319.0923,-173.9735C1319.0923,-162.1918 1319.0923,-146.5607 1319.0923,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1322.5924,-133.0033 1319.0923,-123.0034 1315.5924,-133.0034 1322.5924,-133.0033"/>
<text text-anchor="middle" x="1362.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M497.9026,-204.6068C504.7864,-206.8232 512.1004,-208.8017 519.0923,-210 559.9441,-217.0012 1976.6013,-205.016 2011.0923,-228 2019.0797,-233.3226 2024.1818,-242.2165 2027.4347,-251.0998"/>
<polygon fill="#000000" stroke="#000000" points="2024.1574,-252.3567 2030.3769,-260.9339 2030.8637,-250.3502 2024.1574,-252.3567"/>
<text text-anchor="middle" x="2059.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M495.1647,-178.3988C522.7792,-166.1934 565.7999,-149.0066 605.0923,-141 725.9834,-116.3661 1089.7165,-108.2818 1246.2058,-105.8991"/>
<polygon fill="#000000" stroke="#000000" points="1246.7122,-109.392 1256.6591,-105.7437 1246.6082,-102.3928 1246.7122,-109.392"/>
<text text-anchor="middle" x="641.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M466.0923,-173.9735C466.0923,-162.1918 466.0923,-146.5607 466.0923,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="469.5924,-133.0033 466.0923,-123.0034 462.5924,-133.0034 469.5924,-133.0033"/>
<text text-anchor="middle" x="502.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- radiology_file -->
<g id="node23" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1464.0923" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1464.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1448.465,-174.1276C1438.3606,-163.4129 1424.4524,-150.1392 1410.0923,-141 1398.2124,-133.4393 1384.4862,-127.0008 1371.3546,-121.7503"/>
<polygon fill="#000000" stroke="#000000" points="1372.523,-118.4499 1361.9327,-118.1381 1370.0171,-124.986 1372.523,-118.4499"/>
<text text-anchor="middle" x="1489.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- medical_history -->
<g id="node24" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1641.0923" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1641.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1616.5806,-174.6591C1599.3373,-163.3075 1575.287,-149.1221 1552.0923,-141 1499.726,-122.663 1437.4884,-113.6515 1390.5156,-109.231"/>
<polygon fill="#000000" stroke="#000000" points="1390.704,-105.734 1380.4322,-108.3302 1390.0811,-112.7062 1390.704,-105.734"/>
<text text-anchor="middle" x="1654.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
