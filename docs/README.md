<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Children's Cancer Data Initiative Draft Model

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
<svg width="2772pt" height="305pt"
 viewBox="0.00 0.00 2771.79 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2767.7947,-301 2767.7947,4 -4,4"/>
<!-- therapeutic_procedure -->
<g id="node1" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1934.7947" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1934.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1109.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1109.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1882.2054,-175.8156C1840.7152,-163.8359 1781.1409,-148.3687 1727.7947,-141 1487.2798,-107.7779 1422.2525,-156.6325 1181.7947,-123 1176.0724,-122.1996 1170.1456,-121.1273 1164.2614,-119.903"/>
<polygon fill="#000000" stroke="#000000" points="1164.9641,-116.4738 1154.4428,-117.7199 1163.4448,-123.3069 1164.9641,-116.4738"/>
<text text-anchor="middle" x="1894.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="540.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="540.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.6162,-86.6714C52.7455,-75.7851 52.7603,-62.4911 60.7947,-54 75.5694,-38.3855 376.7648,-24.6118 494.3472,-19.8094"/>
<polygon fill="#000000" stroke="#000000" points="494.6286,-23.301 504.4788,-19.3993 494.3454,-16.3067 494.6286,-23.301"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1063.989,-92.6819C1019.5231,-81.1403 949.9709,-64.1829 888.7947,-54 781.5906,-36.1556 654.242,-25.669 587.2788,-20.9721"/>
<polygon fill="#000000" stroke="#000000" points="587.2795,-17.4639 577.0624,-20.2677 586.798,-24.4473 587.2795,-17.4639"/>
<text text-anchor="middle" x="1013.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2128.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2128.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2100.2127,-178.144C2073.0465,-165.7584 2030.6792,-148.4498 1991.7947,-141 1814.9663,-107.1219 1360.2348,-146.9822 1181.7947,-123 1175.9864,-122.2194 1169.9692,-121.1479 1164.0006,-119.9136"/>
<polygon fill="#000000" stroke="#000000" points="1164.5681,-116.4545 1154.0474,-117.7052 1163.0518,-123.2883 1164.5681,-116.4545"/>
<text text-anchor="middle" x="2078.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pathology_file -->
<g id="node6" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2497.7947" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2497.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2490.1985,-260.8235C2484.4277,-249.4137 2475.3335,-235.4881 2462.7947,-228 2439.3441,-213.9954 2271.3623,-201.2096 2182.9335,-195.3581"/>
<polygon fill="#000000" stroke="#000000" points="2183.025,-191.8567 2172.8178,-194.696 2182.5678,-198.8417 2183.025,-191.8567"/>
<text text-anchor="middle" x="2538.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="276.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="276.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M265.4999,-87.0454C260.3107,-76.2997 256.8727,-63.0224 264.7947,-54 279.6775,-37.0499 419.6754,-25.6743 494.3617,-20.7586"/>
<polygon fill="#000000" stroke="#000000" points="494.6931,-24.2446 504.447,-20.1079 494.2423,-17.2591 494.6931,-24.2446"/>
<text text-anchor="middle" x="326.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1713.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1713.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1661.4409,-278.5198C1419.7035,-276.0268 417.7323,-262.5783 288.7947,-210 224.0725,-183.6075 154.0479,-146.4576 190.7947,-87 222.3178,-35.9945 406.3848,-22.6725 494.2047,-19.2087"/>
<polygon fill="#000000" stroke="#000000" points="494.5559,-22.6982 504.4206,-18.8332 494.2988,-15.7029 494.5559,-22.6982"/>
<text text-anchor="middle" x="239.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1715.0112,-260.7932C1715.9306,-230.0589 1712.6355,-168.5474 1674.7947,-141 1652.637,-124.8696 1208.9309,-126.8445 1181.7947,-123 1176.0738,-122.1895 1170.1479,-121.1106 1164.2643,-119.8823"/>
<polygon fill="#000000" stroke="#000000" points="1164.9682,-116.4533 1154.4463,-117.6949 1163.4459,-123.2858 1164.9682,-116.4533"/>
<text text-anchor="middle" x="1753.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1742.728,-263.6927C1766.695,-251.7851 1802.0147,-235.9874 1834.7947,-228 1933.1233,-204.0404 1962.0617,-227.2014 2061.7947,-210 2068.8939,-208.7756 2076.3333,-207.1407 2083.5662,-205.354"/>
<polygon fill="#000000" stroke="#000000" points="2084.446,-208.7417 2093.2501,-202.8478 2082.6921,-201.965 2084.446,-208.7417"/>
<text text-anchor="middle" x="1877.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="618.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="618.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M644.7757,-176.2618C665.6283,-164.4433 696.0654,-148.977 724.7947,-141 732.2849,-138.9203 930.5876,-120.9949 1039.5882,-111.2489"/>
<polygon fill="#000000" stroke="#000000" points="1040.1997,-114.7083 1049.8485,-110.3321 1039.5766,-107.7361 1040.1997,-114.7083"/>
<text text-anchor="middle" x="768.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="666.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="666.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M641.5995,-87.6033C621.1487,-73.4825 592.2638,-53.5382 570.6528,-38.6163"/>
<polygon fill="#000000" stroke="#000000" points="572.3932,-35.5648 562.1756,-32.763 568.4159,-41.3251 572.3932,-35.5648"/>
<text text-anchor="middle" x="681.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="834.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="834.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M813.329,-87.9282C797.9129,-76.5466 776.1641,-62.2172 754.7947,-54 699.6144,-32.7814 631.6754,-24.0492 587.3519,-20.4683"/>
<polygon fill="#000000" stroke="#000000" points="587.4002,-16.9621 577.1659,-19.7026 586.8754,-23.9425 587.4002,-16.9621"/>
<text text-anchor="middle" x="833.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2674.7947" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2674.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2656.2807,-261.3029C2642.8451,-249.6345 2623.6167,-235.2194 2603.7947,-228 2565.136,-213.9201 2299.5695,-199.9772 2183.2143,-194.4658"/>
<polygon fill="#000000" stroke="#000000" points="2183.2506,-190.9637 2173.0972,-193.99 2182.9217,-197.956 2183.2506,-190.9637"/>
<text text-anchor="middle" x="2697.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="789.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="789.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M800.5064,-173.8613C808.2518,-162.4673 819.7948,-148.5454 833.7947,-141 851.6308,-131.3871 964.5631,-118.9179 1040.3303,-111.4611"/>
<polygon fill="#000000" stroke="#000000" points="1040.6864,-114.9431 1050.2989,-110.4878 1040.0061,-107.9762 1040.6864,-114.9431"/>
<text text-anchor="middle" x="913.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="406.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="406.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M399.249,-173.7242C391.3501,-151.4466 382.2088,-113.4997 398.7947,-87 420.0119,-53.1008 463.1709,-35.4291 496.3682,-26.4992"/>
<polygon fill="#000000" stroke="#000000" points="497.4698,-29.8313 506.3157,-24.0002 495.7642,-23.0422 497.4698,-29.8313"/>
<text text-anchor="middle" x="484.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M407.433,-173.9352C408.8744,-162.5725 412.763,-148.6576 422.7947,-141 444.1829,-124.6735 879.9403,-124.6888 906.7947,-123 951.46,-120.1911 1001.5463,-115.7635 1040.7923,-112.0026"/>
<polygon fill="#000000" stroke="#000000" points="1041.1671,-115.4828 1050.784,-111.0371 1040.4937,-108.5152 1041.1671,-115.4828"/>
<text text-anchor="middle" x="552.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- follow_up -->
<g id="node15" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="962.7947" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="962.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M977.5921,-174.5432C987.5073,-163.7187 1001.3515,-150.1755 1015.7947,-141 1023.6355,-136.0189 1041.1752,-128.9664 1059.0061,-122.4219"/>
<polygon fill="#000000" stroke="#000000" points="1060.666,-125.5437 1068.8823,-118.8547 1058.288,-118.96 1060.666,-125.5437"/>
<text text-anchor="middle" x="1060.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1109.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1109.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1109.7947,-173.9735C1109.7947,-162.1918 1109.7947,-146.5607 1109.7947,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1113.2948,-133.0033 1109.7947,-123.0034 1106.2948,-133.0034 1113.2948,-133.0033"/>
<text text-anchor="middle" x="1168.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1260.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1260.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1216.8525,-90.8275C1178.067,-78.9369 1119.7728,-62.5629 1067.7947,-54 975.972,-38.873 698.5164,-25.1046 587.4736,-20.0481"/>
<polygon fill="#000000" stroke="#000000" points="587.4067,-16.5416 577.2588,-19.5862 587.0905,-23.5345 587.4067,-16.5416"/>
<text text-anchor="middle" x="1194.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1832.7947" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1832.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1854.8298,-267.5295C1859.6913,-265.2112 1864.8633,-262.9039 1869.7947,-261 1952.1613,-229.1992 1976.1014,-231.2652 2061.7947,-210 2068.3922,-208.3628 2075.337,-206.5726 2082.1555,-204.7765"/>
<polygon fill="#000000" stroke="#000000" points="2083.2355,-208.111 2091.9996,-202.1579 2081.4359,-201.3463 2083.2355,-208.111"/>
<text text-anchor="middle" x="2000.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node19" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1286.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1286.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1271.5602,-174.1713C1261.3193,-163.1983 1246.9609,-149.6295 1231.7947,-141 1220.349,-134.4875 1193.0892,-126.2296 1167.2341,-119.2661"/>
<polygon fill="#000000" stroke="#000000" points="1167.9925,-115.8463 1157.4295,-116.6669 1166.1988,-122.6126 1167.9925,-115.8463"/>
<text text-anchor="middle" x="1320.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node20" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2016.7947" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2016.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2024.9735,-260.5844C2030.4568,-249.9379 2038.5487,-236.9258 2048.7947,-228 2058.9526,-219.151 2071.6417,-212.1192 2083.9001,-206.7052"/>
<polygon fill="#000000" stroke="#000000" points="2085.242,-209.9378 2093.1412,-202.8772 2082.563,-203.4707 2085.242,-209.9378"/>
<text text-anchor="middle" x="2157.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node21" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1469.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1469.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1449.435,-174.3714C1434.735,-162.7344 1413.8431,-148.3286 1392.7947,-141 1303.9099,-110.0523 1274.6342,-138.4629 1181.7947,-123 1176.3137,-122.0871 1170.6361,-120.971 1164.9837,-119.746"/>
<polygon fill="#000000" stroke="#000000" points="1165.4123,-116.254 1154.8845,-117.4439 1163.8565,-123.0789 1165.4123,-116.254"/>
<text text-anchor="middle" x="1486.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2287.7947" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2287.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2284.1029,-260.5365C2280.993,-249.5993 2275.4454,-236.2993 2265.7947,-228 2252.7835,-216.8108 2213.2416,-207.1221 2179.9633,-200.6234"/>
<polygon fill="#000000" stroke="#000000" points="2180.3498,-197.1344 2169.8729,-198.7108 2179.0462,-204.012 2180.3498,-197.1344"/>
<text text-anchor="middle" x="2367.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1622.7947" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1622.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1605.8072,-174.6417C1593.0102,-162.8088 1574.3699,-148.0538 1554.7947,-141 1476.7234,-112.8674 1263.8899,-135.1221 1181.7947,-123 1176.0787,-122.156 1170.1559,-121.0553 1164.2742,-119.8139"/>
<polygon fill="#000000" stroke="#000000" points="1164.9819,-116.3857 1154.4583,-117.612 1163.4498,-123.216 1164.9819,-116.3857"/>
<text text-anchor="middle" x="1626.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
