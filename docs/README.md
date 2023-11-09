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
<svg width="2618pt" height="479pt"
 viewBox="0.00 0.00 2618.19 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 2614.1937,-475 2614.1937,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="763.8506" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="763.8506" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node2" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="594.8506" cy="-453" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="594.8506" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="673.8506" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="673.8506" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M728.9513,-448.7583C829.5354,-444.1527 952.5814,-434.9104 968.8506,-417 973.3331,-412.0653 973.3484,-406.9208 968.8506,-402 938.744,-369.0621 806.0746,-408.6106 768.8506,-384 739.8236,-364.8089 755.6654,-340.3716 731.8506,-315 725.9043,-308.665 718.607,-303.0059 711.2203,-298.1552"/>
<polygon fill="#000000" stroke="#000000" points="712.9344,-295.1004 702.5834,-292.8402 709.2657,-301.0621 712.9344,-295.1004"/>
<text text-anchor="middle" x="877.3506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="594.8506" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="594.8506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M594.8506,-434.9735C594.8506,-423.1918 594.8506,-407.5607 594.8506,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="598.3507,-394.0033 594.8506,-384.0034 591.3507,-394.0034 598.3507,-394.0033"/>
<text text-anchor="middle" x="703.3506" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="577.8506" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="577.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M585.0665,-434.7293C570.052,-407.4391 541.245,-358.1416 523.8506,-348 480.3267,-322.6239 332.0321,-367.0121 297.8506,-330 262.3663,-291.5771 439.5583,-232.6457 528.8981,-205.9729"/>
<polygon fill="#000000" stroke="#000000" points="529.9646,-209.3074 538.5592,-203.112 527.977,-202.5955 529.9646,-209.3074"/>
<text text-anchor="middle" x="406.3506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="202.8506" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="202.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M207.1968,-86.7945C210.9362,-75.3723 217.569,-61.444 228.8506,-54 269.0546,-27.4717 593.9382,-20.3076 716.9146,-18.5365"/>
<polygon fill="#000000" stroke="#000000" points="717.1901,-22.0331 727.1407,-18.395 717.0932,-15.0338 717.1901,-22.0331"/>
<text text-anchor="middle" x="285.3506" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node4" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1992.8506" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1992.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1521.8506" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1521.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1976.0716,-174.8809C1963.4427,-163.1637 1945.0696,-148.4488 1925.8506,-141 1867.2722,-118.2964 1694.0795,-109.7524 1594.5067,-106.6592"/>
<polygon fill="#000000" stroke="#000000" points="1594.3207,-103.1522 1584.2203,-106.3509 1594.1109,-110.149 1594.3207,-103.1522"/>
<text text-anchor="middle" x="1995.3506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2163.8506" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2163.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2131.4649,-174.8823C2107.6492,-163.1658 2074.1183,-148.4512 2042.8506,-141 1959.7457,-121.1958 1716.6627,-111.0405 1594.1695,-107.0601"/>
<polygon fill="#000000" stroke="#000000" points="1594.2377,-103.5606 1584.1309,-106.7389 1594.0138,-110.557 1594.2377,-103.5606"/>
<text text-anchor="middle" x="2166.3506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2336.8506" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2336.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2315.3376,-175.3935C2298.5181,-163.4409 2274.0108,-148.2048 2249.8506,-141 2188.2774,-122.6383 1766.1826,-110.7523 1594.371,-106.6241"/>
<polygon fill="#000000" stroke="#000000" points="1594.2405,-103.1201 1584.16,-106.3809 1594.0737,-110.1181 1594.2405,-103.1201"/>
<text text-anchor="middle" x="2326.3506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M665.7062,-296.6992C660.3966,-307.0918 652.8002,-320.0885 643.8506,-330 638.0805,-336.3902 631.0133,-342.3628 624.0611,-347.5353"/>
<polygon fill="#000000" stroke="#000000" points="621.5759,-345.0053 615.423,-353.6304 625.6116,-350.7248 621.5759,-345.0053"/>
<text text-anchor="middle" x="691.3506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M635.5503,-269.9106C610.9084,-263.1994 582.1688,-253.4483 574.8506,-243 570.2511,-236.4334 569.2737,-228.1457 569.934,-220.1711"/>
<polygon fill="#000000" stroke="#000000" points="573.4311,-220.4705 571.5784,-210.0389 566.5215,-219.3491 573.4311,-220.4705"/>
<text text-anchor="middle" x="611.3506" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M718.234,-277.6888C919.9214,-271.5478 1742.0483,-244.473 1783.8506,-210 1807.992,-190.0914 1818.4966,-164.5139 1797.8506,-141 1784.5011,-125.7962 1670.4894,-115.0775 1593.2397,-109.4827"/>
<polygon fill="#000000" stroke="#000000" points="1593.2923,-105.9777 1583.0694,-108.7602 1592.7962,-112.9601 1593.2923,-105.9777"/>
<text text-anchor="middle" x="1844.3506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- therapeutic_procedure -->
<g id="node8" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="997.8506" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="997.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1012.5922,-174.0662C1023.2794,-162.45 1038.8015,-148.1918 1055.8506,-141 1091.1297,-126.1182 1327.709,-113.6111 1449.5732,-108.0669"/>
<polygon fill="#000000" stroke="#000000" points="1450.0963,-111.5469 1459.9285,-107.6 1449.781,-104.554 1450.0963,-111.5469"/>
<text text-anchor="middle" x="1148.8506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- follow_up -->
<g id="node9" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1188.8506" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1188.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1212.1508,-175.602C1229.6818,-164.0798 1254.7353,-149.2955 1278.8506,-141 1334.4792,-121.8641 1400.71,-112.8981 1449.9669,-108.6981"/>
<polygon fill="#000000" stroke="#000000" points="1450.5239,-112.1646 1460.2103,-107.8722 1449.9613,-105.1873 1450.5239,-112.1646"/>
<text text-anchor="middle" x="1323.8506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="350.8506" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="350.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M345.7089,-86.7061C343.8521,-75.8328 343.8685,-62.5403 351.8506,-54 376.3797,-27.7553 614.3419,-20.5434 717.0459,-18.6455"/>
<polygon fill="#000000" stroke="#000000" points="717.1979,-22.1435 727.1348,-18.4682 717.0749,-15.1446 717.1979,-22.1435"/>
<text text-anchor="middle" x="400.3506" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge35" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M577.4664,-351.3904C548.8734,-326.0866 492.9834,-270.9343 471.8506,-210 453.1867,-156.1845 476.9575,-134.8546 507.8506,-87 518.7646,-70.0937 521.0731,-63.4286 538.8506,-54 569.0368,-37.9902 660.9378,-27.1945 717.5184,-21.866"/>
<polygon fill="#000000" stroke="#000000" points="718.0118,-25.3355 727.6494,-20.9347 717.371,-18.3649 718.0118,-25.3355"/>
<text text-anchor="middle" x="495.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M590.7607,-348.1007C589.3916,-337.6372 589.551,-324.6362 595.8506,-315 602.8052,-304.3617 613.7731,-296.8168 625.3116,-291.4847"/>
<polygon fill="#000000" stroke="#000000" points="626.698,-294.6991 634.6218,-287.666 624.0416,-288.2227 626.698,-294.6991"/>
<text text-anchor="middle" x="619.8506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node12" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1341.8506" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1341.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1354.9956,-174.0244C1363.9488,-162.9929 1376.7113,-149.4139 1390.8506,-141 1410.7125,-129.1806 1434.5632,-121.1349 1456.4389,-115.7057"/>
<polygon fill="#000000" stroke="#000000" points="1457.39,-119.0778 1466.3295,-113.3912 1455.795,-112.2619 1457.39,-119.0778"/>
<text text-anchor="middle" x="1454.8506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- medical_history -->
<g id="node13" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1524.8506" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1524.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1523.706,-173.6918C1523.3859,-168.0228 1523.0668,-161.7548 1522.8506,-156 1522.5781,-148.7461 1522.3775,-140.9088 1522.2308,-133.6054"/>
<polygon fill="#000000" stroke="#000000" points="1525.7271,-133.3544 1522.0523,-123.4173 1518.7281,-133.4771 1525.7271,-133.3544"/>
<text text-anchor="middle" x="1590.8506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="293.8506" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="293.8506" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M258.8349,-436.9339C242.663,-427.3286 229.163,-414.5786 239.8506,-402 255.8889,-383.124 326.041,-390.829 349.8506,-384 389.6806,-372.576 396.7771,-361.7914 435.8506,-348 500.8046,-325.0737 577.6078,-303.8346 626.0304,-291.1402"/>
<polygon fill="#000000" stroke="#000000" points="627.1238,-294.4723 635.918,-288.5636 625.3585,-287.6985 627.1238,-294.4723"/>
<text text-anchor="middle" x="496.8506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M341.7391,-438.9701C376.8997,-428.6871 425.8272,-414.4152 468.8506,-402 499.3969,-393.1853 534.1403,-383.2666 559.3961,-376.0759"/>
<polygon fill="#000000" stroke="#000000" points="560.599,-379.3726 569.2591,-373.2691 558.683,-372.6399 560.599,-379.3726"/>
<text text-anchor="middle" x="529.8506" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M238.3335,-440.5975C208.0446,-430.6934 173.0938,-413.4233 154.8506,-384 138.4063,-357.4781 145.7593,-337.0409 167.8506,-315 281.9154,-201.1953 357.9646,-246.7295 514.8506,-210 519.7775,-208.8465 524.8945,-207.5504 529.9866,-206.1961"/>
<polygon fill="#000000" stroke="#000000" points="530.9695,-209.5559 539.6921,-203.542 529.123,-202.8038 530.9695,-209.5559"/>
<text text-anchor="middle" x="228.8506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1701.8506" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1701.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1690.7993,-173.9407C1683.1356,-162.8758 1671.9691,-149.2912 1658.8506,-141 1638.0233,-127.8367 1612.5149,-119.4628 1589.1792,-114.1456"/>
<polygon fill="#000000" stroke="#000000" points="1589.8408,-110.708 1579.3312,-112.0488 1588.3831,-117.5546 1589.8408,-110.708"/>
<text text-anchor="middle" x="1734.8506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1284.8506" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1284.8506" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1282.9262,-434.5932C1280.952,-423.9499 1276.9526,-410.938 1268.8506,-402 1227.6574,-356.5567 1200.6994,-365.2855 1141.8506,-348 995.9389,-305.1418 816.2573,-288.1838 727.9969,-282.0808"/>
<polygon fill="#000000" stroke="#000000" points="728.1631,-278.5841 717.9509,-281.406 727.6939,-285.5684 728.1631,-278.5841"/>
<text text-anchor="middle" x="1341.3506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1209.6929,-439.2105C1131.8073,-424.9903 1018.5712,-404.5372 997.8506,-402 880.6766,-387.6522 850.3245,-395.6398 732.8506,-384 698.7388,-380.6201 660.0516,-375.458 632.3373,-371.5272"/>
<polygon fill="#000000" stroke="#000000" points="632.6805,-368.0407 622.2853,-370.0872 631.6879,-374.97 632.6805,-368.0407"/>
<text text-anchor="middle" x="1173.3506" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1343.8895,-437.5047C1399.3738,-420.0475 1469.3889,-388.7137 1436.8506,-348 1255.9008,-121.586 1083.0345,-267.1348 795.8506,-228 724.9462,-218.3378 705.8903,-224.6705 635.8506,-210 631.9567,-209.1844 627.9505,-208.2181 623.9498,-207.1634"/>
<polygon fill="#000000" stroke="#000000" points="624.6573,-203.7267 614.0835,-204.3946 622.7659,-210.4664 624.6573,-203.7267"/>
<text text-anchor="middle" x="1512.3506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M556.5331,-175.5431C531.4305,-154.1573 495.7806,-116.112 517.8506,-87 541.9652,-55.1909 653.7646,-34.0034 718.0361,-24.2249"/>
<polygon fill="#000000" stroke="#000000" points="718.9284,-27.6308 728.3049,-22.6981 717.8988,-20.7069 718.9284,-27.6308"/>
<text text-anchor="middle" x="558.3506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M615.0397,-203.9705C627.9908,-209.6085 641.7834,-217.4638 651.8506,-228 658.0073,-234.4436 662.586,-242.8818 665.9237,-251.0347"/>
<polygon fill="#000000" stroke="#000000" points="662.7183,-252.4638 669.402,-260.6845 669.3036,-250.0901 662.7183,-252.4638"/>
<text text-anchor="middle" x="703.3506" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M600.9369,-176.0679C619.8597,-163.9724 647.8328,-148.2294 674.8506,-141 774.3179,-114.3845 1034.9785,-127.4107 1137.8506,-123 1246.8122,-118.3282 1373.1341,-112.2863 1450.2547,-108.5271"/>
<polygon fill="#000000" stroke="#000000" points="1450.5214,-112.0183 1460.3388,-108.0349 1450.18,-105.0266 1450.5214,-112.0183"/>
<text text-anchor="middle" x="715.3506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="694.8506" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="694.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M684.6292,-86.802C680.3054,-76.486 677.5554,-63.736 683.8506,-54 692.1151,-41.2183 706.1187,-32.9297 720.1212,-27.5742"/>
<polygon fill="#000000" stroke="#000000" points="721.3951,-30.8381 729.7444,-24.3159 719.1501,-24.2078 721.3951,-30.8381"/>
<text text-anchor="middle" x="753.3506" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node19" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="862.8506" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="862.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge34" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M851.2641,-87.1616C843.9268,-76.7198 833.7827,-63.7201 822.8506,-54 815.3965,-47.3724 806.5626,-41.2531 798.0308,-36.011"/>
<polygon fill="#000000" stroke="#000000" points="799.7126,-32.9396 789.3197,-30.881 796.1605,-38.9714 799.7126,-32.9396"/>
<text text-anchor="middle" x="887.8506" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="109.8506" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="109.8506" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M119.6586,-435.0267C134.1888,-410.4247 163.9582,-367.1367 202.8506,-348 255.2145,-322.2347 408.7672,-346.1393 464.8506,-330 478.4177,-326.0958 479.5604,-319.7622 492.8506,-315 534.7559,-299.9843 584.4887,-290.6636 621.2094,-285.2791"/>
<polygon fill="#000000" stroke="#000000" points="621.7939,-288.7313 631.2042,-283.8633 620.8121,-281.8005 621.7939,-288.7313"/>
<text text-anchor="middle" x="274.3506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M155.6904,-437.4706C195.8185,-424.1128 251.1516,-406.33 273.8506,-402 378.0516,-382.1231 406.8766,-399.2777 511.8506,-384 527.3489,-381.7444 544.2752,-378.2618 558.7763,-374.9586"/>
<polygon fill="#000000" stroke="#000000" points="559.9098,-378.2882 568.8516,-372.6053 558.3176,-371.4716 559.9098,-378.2882"/>
<text text-anchor="middle" x="345.3506" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M81.1071,-435.807C41.1531,-409.7181 -22.8763,-358.5564 8.8506,-315 83.0806,-213.0931 155.1379,-252.2958 278.8506,-228 382.0724,-207.7284 411.3045,-228.5441 514.8506,-210 520.1692,-209.0475 525.683,-207.8288 531.1365,-206.4754"/>
<polygon fill="#000000" stroke="#000000" points="532.0534,-209.8533 540.8325,-203.9223 530.2709,-203.0841 532.0534,-209.8533"/>
<text text-anchor="middle" x="80.3506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node21" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="753.8506" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="753.8506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M749.1627,-173.6912C747.5548,-162.8122 747.8361,-149.5191 755.8506,-141 783.244,-111.8817 905.9271,-150.599 934.8506,-123 957.1858,-101.6875 962.4103,-77.8852 942.8506,-54 926.3853,-33.8936 857.5785,-24.7748 810.2347,-20.817"/>
<polygon fill="#000000" stroke="#000000" points="810.4326,-17.3218 800.1889,-20.0268 809.8837,-24.3003 810.4326,-17.3218"/>
<text text-anchor="middle" x="1040.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M754.5159,-173.9704C755.9687,-162.6226 759.8599,-148.711 769.8506,-141 770.6875,-140.3541 1262.1561,-117.2006 1450.0153,-108.3725"/>
<polygon fill="#000000" stroke="#000000" points="1450.2465,-111.8656 1460.0712,-107.9 1449.9179,-104.8733 1450.2465,-111.8656"/>
<text text-anchor="middle" x="899.3506" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1007.8506" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1007.8506" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1009.5391,-434.6749C1010.6125,-411.269 1008.6384,-371.0426 985.8506,-348 950.2449,-311.9963 806.7642,-292.2538 727.3659,-283.889"/>
<polygon fill="#000000" stroke="#000000" points="727.3802,-280.3721 717.0746,-282.8307 726.664,-287.3354 727.3802,-280.3721"/>
<text text-anchor="middle" x="1071.3506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M950.7412,-439.8942C923.432,-433.4029 890.3395,-425.2098 860.8506,-417 839.3187,-411.0054 834.5959,-407.1667 812.8506,-402 750.4453,-387.1726 676.5561,-376.356 632.8095,-370.6367"/>
<polygon fill="#000000" stroke="#000000" points="632.9915,-367.1313 622.6265,-369.3265 632.0981,-374.0741 632.9915,-367.1313"/>
<text text-anchor="middle" x="927.3506" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1083.3028,-445.2813C1142.1938,-438.4755 1215.5591,-427.9599 1224.8506,-417 1229.1616,-411.9148 1228.0292,-407.8601 1224.8506,-402 1162.3748,-286.8186 1019.0785,-290.7906 747.8506,-228 698.7331,-216.6291 684.9379,-221.5005 635.8506,-210 632.0332,-209.1056 628.101,-208.0913 624.1678,-207.0107"/>
<polygon fill="#000000" stroke="#000000" points="625.0318,-203.6174 614.4541,-204.2187 623.0981,-210.345 625.0318,-203.6174"/>
<text text-anchor="middle" x="1220.3506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge26" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1463.6302,-98.3177C1318.155,-81.6207 941.069,-38.3404 809.7514,-23.2683"/>
<polygon fill="#000000" stroke="#000000" points="809.9668,-19.7701 799.6329,-22.1069 809.1686,-26.7245 809.9668,-19.7701"/>
<text text-anchor="middle" x="1239.3506" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node24" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1911.8506" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1911.8506" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1963.2131,-362.6943C2093.7292,-353.6104 2427.8506,-325.7866 2427.8506,-279 2427.8506,-279 2427.8506,-279 2427.8506,-105 2427.8506,-63.3616 1081.2005,-26.2314 810.8002,-19.1956"/>
<polygon fill="#000000" stroke="#000000" points="810.6323,-15.6902 800.5449,-18.9298 810.4508,-22.6878 810.6323,-15.6902"/>
<text text-anchor="middle" x="2470.3506" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1872.4374,-353.9832C1853.9347,-347.7621 1831.8286,-339.4816 1812.8506,-330 1801.9333,-324.5456 1801.4911,-318.6657 1789.8506,-315 1738.7992,-298.9237 945.024,-283.7887 728.2085,-279.9389"/>
<polygon fill="#000000" stroke="#000000" points="728.0864,-276.4363 718.0261,-279.7589 727.9626,-283.4352 728.0864,-276.4363"/>
<text text-anchor="middle" x="1855.3506" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1914.5551,-347.7936C1918.9771,-311.0663 1923.7378,-227.0891 1884.8506,-174 1851.2478,-128.1252 1690.0889,-112.6975 1594.1653,-107.5473"/>
<polygon fill="#000000" stroke="#000000" points="1594.1148,-104.0402 1583.9489,-107.0243 1593.7568,-111.031 1594.1148,-104.0402"/>
<text text-anchor="middle" x="1954.3506" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node25" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2532.8506" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2532.8506" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2509.5463,-87.6907C2491.9471,-75.7155 2466.6622,-60.7637 2441.8506,-54 2361.1348,-31.9966 1074.4308,-20.4966 810.8169,-18.3653"/>
<polygon fill="#000000" stroke="#000000" points="810.4782,-14.8626 800.4504,-18.2821 810.422,-21.8624 810.4782,-14.8626"/>
<text text-anchor="middle" x="2537.8506" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
