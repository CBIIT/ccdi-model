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
<svg width="2921pt" height="392pt"
 viewBox="0.00 0.00 2920.84 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2916.8413,-388 2916.8413,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1344.8413" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1344.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1787.8413" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1787.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1365.1559,-175.2178C1380.5418,-163.5046 1402.7386,-148.6497 1424.8413,-141 1476.8488,-123.0003 1625.5542,-112.8478 1715.6871,-108.1839"/>
<polygon fill="#000000" stroke="#000000" points="1716.0284,-111.6712 1725.8383,-107.669 1715.6738,-104.6802 1716.0284,-111.6712"/>
<text text-anchor="middle" x="1469.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1517.8413" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1517.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1516.1126,-173.9859C1516.1043,-162.939 1518.1634,-149.3575 1526.8413,-141 1540.4309,-127.9121 1644.915,-116.741 1717.4875,-110.4523"/>
<polygon fill="#000000" stroke="#000000" points="1717.837,-113.9352 1727.5032,-109.5976 1717.2418,-106.9606 1717.837,-113.9352"/>
<text text-anchor="middle" x="1606.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node3" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1927.8413" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1927.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1902.1631,-176.0429C1879.9467,-162.2369 1847.6118,-142.1431 1822.995,-126.8455"/>
<polygon fill="#000000" stroke="#000000" points="1824.6489,-123.7526 1814.3079,-121.4471 1820.9541,-129.6981 1824.6489,-123.7526"/>
<text text-anchor="middle" x="1910.8413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="782.8413" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="782.8413" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1727.9836,-99.8183C1544.4951,-83.9342 992.4502,-36.1452 828.9503,-21.9915"/>
<polygon fill="#000000" stroke="#000000" points="829.0154,-18.4842 818.7508,-21.1086 828.4117,-25.4581 829.0154,-18.4842"/>
<text text-anchor="middle" x="1395.3413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="230.8413" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="230.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M249.9634,-87.3004C263.8172,-75.6308 283.5992,-61.2153 303.8413,-54 382.5391,-25.948 631.4821,-19.7543 735.9613,-18.3871"/>
<polygon fill="#000000" stroke="#000000" points="736.2452,-21.884 746.2019,-18.2627 736.16,-14.8845 736.2452,-21.884"/>
<text text-anchor="middle" x="365.8413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="388.8413" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="388.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M406.8242,-87.5122C419.877,-75.9398 438.5624,-61.5534 457.8413,-54 507.3769,-34.5921 658.5971,-24.3054 736.0479,-20.1874"/>
<polygon fill="#000000" stroke="#000000" points="736.6635,-23.6603 746.4687,-19.6469 736.3008,-16.6697 736.6635,-23.6603"/>
<text text-anchor="middle" x="508.8413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="556.8413" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="556.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M558.281,-86.8447C560.1422,-75.7416 564.3554,-62.1503 573.8413,-54 597.6503,-33.5433 682.4622,-24.3665 736.4516,-20.5187"/>
<polygon fill="#000000" stroke="#000000" points="736.741,-24.0073 746.4817,-19.8396 736.2681,-17.0232 736.741,-24.0073"/>
<text text-anchor="middle" x="643.3413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2054.8413" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2054.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2029.5656,-175.8431C2010.9405,-164.5917 1984.6399,-150.0383 1959.8413,-141 1926.0881,-128.6981 1886.9941,-120.0964 1854.6143,-114.3939"/>
<polygon fill="#000000" stroke="#000000" points="1854.7988,-110.8749 1844.3526,-112.6433 1853.6216,-117.7752 1854.7988,-110.8749"/>
<text text-anchor="middle" x="2035.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="89.8413" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="89.8413" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1679.8413" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1679.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M60.8053,-349.2761C27.9046,-328.2531 -17.9915,-291.2543 7.8413,-261 68.6207,-189.8175 122.5789,-235.9511 215.8413,-228 372.0651,-214.6811 1472.313,-236.5383 1626.8413,-210 1630.5555,-209.3621 1634.3607,-208.5044 1638.144,-207.5082"/>
<polygon fill="#000000" stroke="#000000" points="1639.4227,-210.7805 1648.0303,-204.6031 1637.4492,-204.0644 1639.4227,-210.7805"/>
<text text-anchor="middle" x="68.8413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="439.8413" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="439.8413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M105.2789,-348.2169C116.4184,-336.6679 132.4988,-322.4282 149.8413,-315 220.0884,-284.9112 245.0417,-306.7171 320.8413,-297 348.2826,-293.4822 379.1715,-288.7881 402.6008,-285.0756"/>
<polygon fill="#000000" stroke="#000000" points="403.1537,-288.5317 412.4768,-283.4989 402.0501,-281.6193 403.1537,-288.5317"/>
<text text-anchor="middle" x="210.8413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1108.8413" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1108.8413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M143.5621,-353.1453C153.8895,-351.0946 164.6595,-349.2423 174.8413,-348 232.9997,-340.904 646.8282,-350.1572 701.8413,-330 711.9434,-326.2985 710.8515,-318.9947 720.8413,-315 778.9642,-291.7577 955.8159,-283.3061 1049.3641,-280.4068"/>
<polygon fill="#000000" stroke="#000000" points="1049.6317,-283.9005 1059.5229,-280.1037 1049.4229,-276.9036 1049.6317,-283.9005"/>
<text text-anchor="middle" x="781.8413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1108.8413" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1108.8413" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1220.7564,-361.3153C1313.7204,-356.2664 1433.2163,-346.6257 1448.8413,-330 1469.8628,-307.6322 1432.8921,-285.1485 1451.8413,-261 1501.8527,-197.2661 1549.5788,-234.3654 1626.8413,-210 1629.9459,-209.0209 1633.1456,-207.9898 1636.3623,-206.9371"/>
<polygon fill="#000000" stroke="#000000" points="1637.5962,-210.2155 1645.9853,-203.7446 1635.3919,-203.5716 1637.5962,-210.2155"/>
<text text-anchor="middle" x="1543.3413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M995.6404,-362.2116C836.9409,-356.4245 562.7153,-344.5112 518.8413,-330 507.2546,-326.1677 506.0853,-321.6331 495.8413,-315 486.8915,-309.205 477.1201,-302.9117 468.2813,-297.2318"/>
<polygon fill="#000000" stroke="#000000" points="470.1242,-294.2557 459.8184,-291.7975 466.3418,-300.1459 470.1242,-294.2557"/>
<text text-anchor="middle" x="610.3413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1108.8413,-347.9735C1108.8413,-336.1918 1108.8413,-320.5607 1108.8413,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="1112.3414,-307.0033 1108.8413,-297.0034 1105.3414,-307.0034 1112.3414,-307.0033"/>
<text text-anchor="middle" x="1200.3413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node12" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="731.8413" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="731.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M721.4584,-87.0525C716.9974,-76.82 713.9974,-64.07 719.8413,-54 725.2078,-44.7524 733.9409,-37.6797 743.2183,-32.3561"/>
<polygon fill="#000000" stroke="#000000" points="744.8747,-35.4402 752.1878,-27.7741 741.6902,-29.2065 744.8747,-35.4402"/>
<text text-anchor="middle" x="776.3413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node13" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="321.8413" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="321.8413" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M221.8372,-353.614C175.7844,-346.8849 129.7485,-338.2689 122.8413,-330 118.5674,-324.8835 120.0556,-321.0568 122.8413,-315 190.0133,-168.9531 490.7771,-244.804 974.8413,-228 1119.6981,-222.9714 1484.1745,-235.5927 1626.8413,-210 1630.5506,-209.3346 1634.3525,-208.4577 1638.1336,-207.4487"/>
<polygon fill="#000000" stroke="#000000" points="1639.4209,-210.7178 1648.0164,-204.5236 1637.4342,-204.0056 1639.4209,-210.7178"/>
<text text-anchor="middle" x="280.3413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M292.1724,-348.2446C279.6707,-338.5238 269.8627,-326.2079 278.8413,-315 286.5871,-305.3309 357.4072,-292.2871 402.5034,-284.8472"/>
<polygon fill="#000000" stroke="#000000" points="403.2237,-288.2761 412.5315,-283.2148 402.099,-281.367 403.2237,-288.2761"/>
<text text-anchor="middle" x="387.3413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M454.7508,-361.1542C585.2147,-355.6278 774.7944,-345.3258 846.8413,-330 865.8201,-325.9628 869.0707,-319.9151 887.8413,-315 942.4414,-300.7028 1006.1953,-291.0432 1051.1572,-285.3596"/>
<polygon fill="#000000" stroke="#000000" points="1051.8143,-288.805 1061.3088,-284.1035 1050.9547,-281.858 1051.8143,-288.805"/>
<text text-anchor="middle" x="996.3413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node14" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2199.8413" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2199.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2168.9599,-175.5921C2145.8756,-164.065 2113.1975,-149.2789 2082.8413,-141 2008.4943,-120.7238 1920.4836,-111.853 1860.0605,-107.981"/>
<polygon fill="#000000" stroke="#000000" points="1860.0536,-104.4741 1849.8588,-107.3579 1859.6268,-111.4611 1860.0536,-104.4741"/>
<text text-anchor="middle" x="2183.8413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- medical_history -->
<g id="node15" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2496.8413" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2496.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2453.4918,-176.4256C2418.6653,-164.6155 2368.2446,-149.0817 2322.8413,-141 2236.036,-125.5488 1984.7732,-113.2531 1859.9575,-107.9029"/>
<polygon fill="#000000" stroke="#000000" points="1859.8768,-104.3964 1849.7371,-107.4682 1859.5793,-111.39 1859.8768,-104.3964"/>
<text text-anchor="middle" x="2453.8413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- clinical_measure_file -->
<g id="node16" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="968.8413" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="968.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M964.4681,-173.9755C962.9507,-162.9245 963.3758,-149.3422 971.8413,-141 985.0045,-128.0284 1518.1034,-112.3039 1715.401,-106.9172"/>
<polygon fill="#000000" stroke="#000000" points="1715.763,-110.4087 1725.6641,-106.638 1715.5726,-103.4113 1715.763,-110.4087"/>
<text text-anchor="middle" x="1101.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M960.693,-173.6408C957.4564,-163.5138 955.6003,-151.0028 960.8413,-141 967.3641,-128.5508 980.3184,-135.4492 986.8413,-123 1001.1276,-95.7336 1002.6077,-75.7664 980.8413,-54 960.0974,-33.2561 881.3675,-24.2362 829.6531,-20.4852"/>
<polygon fill="#000000" stroke="#000000" points="829.5926,-16.973 819.3772,-19.7829 829.1152,-23.9567 829.5926,-16.973"/>
<text text-anchor="middle" x="1083.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node17" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="2717.8413" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="2717.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2667.9275,-175.6361C2629.5322,-163.8106 2574.9166,-148.6273 2525.8413,-141 2399.1733,-121.3133 2020.47,-110.4235 1860.4697,-106.5942"/>
<polygon fill="#000000" stroke="#000000" points="1860.3322,-103.09 1850.2521,-106.3521 1860.1664,-110.0881 1860.3322,-103.09"/>
<text text-anchor="middle" x="2687.8413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm -->
<g id="node18" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="917.8413" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="917.8413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M900.9885,-87.4679C890.1883,-76.8812 875.4916,-63.6226 860.8413,-54 848.6033,-45.9618 834.2807,-38.7945 821.2722,-33.0123"/>
<polygon fill="#000000" stroke="#000000" points="822.6497,-29.7948 812.0807,-29.054 819.8809,-36.2239 822.6497,-29.7948"/>
<text text-anchor="middle" x="928.3413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1683.564,-173.9911C1686.6073,-163.225 1691.9115,-149.9452 1700.8413,-141 1709.3222,-132.5044 1720.0967,-125.9204 1731.151,-120.8505"/>
<polygon fill="#000000" stroke="#000000" points="1732.5953,-124.0402 1740.4583,-116.9392 1729.8832,-117.5869 1732.5953,-124.0402"/>
<text text-anchor="middle" x="1737.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M416.6881,-268.4428C349.8892,-237.7583 160.5735,-149.116 144.8413,-123 136.5852,-109.2946 135.0531,-99.6567 144.8413,-87 180.9965,-40.2494 595.535,-23.5945 736.3586,-19.2632"/>
<polygon fill="#000000" stroke="#000000" points="736.5163,-22.7601 746.4065,-18.9609 736.3057,-15.7633 736.5163,-22.7601"/>
<text text-anchor="middle" x="214.8413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M467.8695,-276.9184C568.467,-269.4961 920.8023,-243.923 1211.8413,-228 1304.0123,-222.9572 1536.1138,-227.0138 1626.8413,-210 1630.4946,-209.3149 1634.2393,-208.4327 1637.9667,-207.4276"/>
<polygon fill="#000000" stroke="#000000" points="1639.1286,-210.7337 1647.7179,-204.5308 1637.1352,-204.0235 1639.1286,-210.7337"/>
<text text-anchor="middle" x="1235.8413" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1157.9278,-276.3272C1222.882,-272.7949 1340.955,-266.3893 1441.8413,-261 1460.7851,-259.988 1769.7852,-256.7634 1782.8413,-243 1782.8413,-243 1782.8413,-174 1782.8413,-174 1783.325,-160.632 1784.3342,-145.8356 1785.3201,-133.3841"/>
<polygon fill="#000000" stroke="#000000" points="1788.8311,-133.3945 1786.1667,-123.1402 1781.8549,-132.8179 1788.8311,-133.3945"/>
<text text-anchor="middle" x="1823.3413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1062.168,-272.8411C995.5558,-263.0443 878.2242,-241.7183 850.8413,-210 805.2327,-157.1704 868.1738,-114.1891 832.8413,-54 828.9695,-47.4045 823.3602,-41.6849 817.2858,-36.8665"/>
<polygon fill="#000000" stroke="#000000" points="819.0121,-33.7994 808.834,-30.8569 814.9556,-39.5043 819.0121,-33.7994"/>
<text text-anchor="middle" x="877.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1149.6355,-268.5415C1197.4893,-256.708 1279.3777,-237.8096 1350.8413,-228 1472.6265,-211.2829 1506.2739,-233.9714 1626.8413,-210 1630.4869,-209.2752 1634.2263,-208.3651 1637.9501,-207.3413"/>
<polygon fill="#000000" stroke="#000000" points="1639.1246,-210.6431 1647.6955,-204.4149 1637.1113,-203.9388 1639.1246,-210.6431"/>
<text text-anchor="middle" x="1391.3413" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- molecular_test -->
<g id="node22" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1191.8413" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1191.8413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1210.0334,-174.2574C1223.2517,-162.5682 1242.2009,-148.1468 1261.8413,-141 1303.3378,-125.9001 1581.1545,-113.1091 1715.4365,-107.7261"/>
<polygon fill="#000000" stroke="#000000" points="1715.7796,-111.2153 1725.6325,-107.3205 1715.5013,-104.2208 1715.7796,-111.2153"/>
<text text-anchor="middle" x="1325.8413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sequencing_file -->
<g id="node23" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1495.8413" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1495.8413" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1556.1719,-353.4581C1573.5192,-348.0512 1591.7983,-340.4815 1606.8413,-330 1644.3654,-303.8543 1664.1381,-252.2205 1673.2578,-220.0579"/>
<polygon fill="#000000" stroke="#000000" points="1676.6498,-220.9216 1675.8535,-210.3567 1669.8877,-219.1123 1676.6498,-220.9216"/>
<text text-anchor="middle" x="1724.3413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1421.1976,-358.036C1387.7493,-352.7437 1348.3722,-344.073 1314.8413,-330 1303.9291,-325.4201 1304.0736,-318.726 1292.8413,-315 1253.7759,-302.0412 640.1984,-284.4645 478.5987,-280.0423"/>
<polygon fill="#000000" stroke="#000000" points="478.2794,-276.5324 468.1877,-279.7586 478.0886,-283.5298 478.2794,-276.5324"/>
<text text-anchor="middle" x="1381.3413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1485.1913,-347.7449C1477.472,-336.3019 1465.9349,-322.3689 1451.8413,-315 1403.9763,-289.9737 1253.2183,-282.3418 1168.3682,-280.0167"/>
<polygon fill="#000000" stroke="#000000" points="1168.4456,-276.5176 1158.3587,-279.7587 1168.2652,-283.5153 1168.4456,-276.5176"/>
<text text-anchor="middle" x="1536.3413" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node24" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2308.8413" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2308.8413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2307.7504,-260.7588C2304.6448,-228.1396 2292.7063,-161.3246 2246.8413,-141 2212.4464,-125.7583 1980.405,-113.4648 1860.0177,-108.0262"/>
<polygon fill="#000000" stroke="#000000" points="1859.9301,-104.5189 1849.7836,-107.5682 1859.6171,-111.5119 1859.9301,-104.5189"/>
<text text-anchor="middle" x="2340.3413" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2360.4028,-276.1746C2488.4781,-268.6324 2813.0851,-246.1063 2844.8413,-210 2855.4081,-197.9857 2852.9846,-187.7726 2844.8413,-174 2686.4809,93.8304 1760.4355,-72.5018 1449.8413,-54 1217.0962,-40.1356 938.523,-25.8435 829.6647,-20.3472"/>
<polygon fill="#000000" stroke="#000000" points="829.526,-16.8359 819.3624,-19.8277 829.1734,-23.827 829.526,-16.8359"/>
<text text-anchor="middle" x="2870.3413" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2258.2173,-274.8091C2159.9995,-266.2198 1936.9625,-244.4739 1751.8413,-210 1743.5563,-208.4571 1734.8049,-206.5277 1726.3662,-204.5099"/>
<polygon fill="#000000" stroke="#000000" points="1727.1971,-201.11 1716.6503,-202.1185 1725.524,-207.9071 1727.1971,-201.11"/>
<text text-anchor="middle" x="1992.3413" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
