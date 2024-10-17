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
<svg width="3106pt" height="305pt"
 viewBox="0.00 0.00 3106.14 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3102.1367,-301 3102.1367,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2437.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2437.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="780.0923" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="780.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node22" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1322.0923" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1322.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M796.0892,-174.0478C807.62,-162.4234 824.2419,-148.163 842.0923,-141 878.9142,-126.2241 1125.2612,-113.5591 1250.0008,-108.0047"/>
<polygon fill="#000000" stroke="#000000" points="1250.3895,-111.4911 1260.2253,-107.5533 1250.0806,-104.4979 1250.3895,-111.4911"/>
<text text-anchor="middle" x="925.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="610.0923" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="610.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node15" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="613.0923" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="613.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M610.7139,-260.9735C611.1201,-249.1918 611.6591,-233.5607 612.1213,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="615.6247,-220.1181 612.4715,-210.0034 608.6288,-219.8768 615.6247,-220.1181"/>
<text text-anchor="middle" x="703.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1234.0923" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1234.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1245.1187,-173.8773C1251.8775,-163.5863 1261.1275,-150.8363 1271.0923,-141 1275.9635,-136.1915 1281.5353,-131.5645 1287.1654,-127.3221"/>
<polygon fill="#000000" stroke="#000000" points="1289.3119,-130.0894 1295.3812,-121.4053 1285.2211,-124.4092 1289.3119,-130.0894"/>
<text text-anchor="middle" x="1330.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="833.0923" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="833.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M825.7734,-260.9441C820.193,-249.5851 811.3643,-235.671 799.0923,-228 748.511,-196.3826 724.1584,-223.6546 666.0923,-210 662.678,-209.1971 659.1729,-208.2628 655.6705,-207.2501"/>
<polygon fill="#000000" stroke="#000000" points="656.472,-203.8347 645.8846,-204.2325 654.4093,-210.5239 656.472,-203.8347"/>
<text text-anchor="middle" x="886.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8277,-86.9966C79.8034,-75.954 79.6832,-62.3732 88.0923,-54 109.2677,-32.915 2061.895,-20.2556 2390.4255,-18.274"/>
<polygon fill="#000000" stroke="#000000" points="2390.57,-21.7733 2400.5488,-18.2133 2390.528,-14.7734 2390.57,-21.7733"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1017.0923" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1017.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1003.5568,-261.2399C993.5189,-249.5426 978.7342,-235.1188 962.0923,-228 901.5035,-202.0824 730.7545,-222.7088 666.0923,-210 662.4451,-209.2832 658.7046,-208.3787 654.98,-207.3587"/>
<polygon fill="#000000" stroke="#000000" points="655.8173,-203.9559 645.2335,-204.4382 653.808,-210.6613 655.8173,-203.9559"/>
<text text-anchor="middle" x="1046.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1411.0923" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1411.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1406.5098,-173.8099C1403.1088,-163.2433 1397.5681,-150.2361 1389.0923,-141 1383.2527,-134.6366 1376.0235,-129.1749 1368.496,-124.5695"/>
<polygon fill="#000000" stroke="#000000" points="1370.0186,-121.4101 1359.5877,-119.5537 1366.5843,-127.5098 1370.0186,-121.4101"/>
<text text-anchor="middle" x="1468.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1594.0923" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1594.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1579.9777,-174.0223C1570.0631,-162.6963 1555.8049,-148.7896 1540.0923,-141 1514.5449,-128.3347 1445.1487,-118.2387 1391.4487,-111.9992"/>
<polygon fill="#000000" stroke="#000000" points="1391.6093,-108.4949 1381.2775,-110.8412 1390.8174,-115.45 1391.6093,-108.4949"/>
<text text-anchor="middle" x="1626.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1430.0923" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1430.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1479.4614,-277.0801C1671.2578,-269.4149 2358.0331,-239.9661 2393.0923,-210 2417.0224,-189.5462 2395.5569,-169.4219 2409.0923,-141 2413.4499,-131.8497 2419.1755,-132.3474 2423.0923,-123 2433.3676,-98.4779 2436.5022,-68.165 2437.2842,-46.4229"/>
<polygon fill="#000000" stroke="#000000" points="2440.788,-46.2786 2437.5022,-36.2061 2433.7896,-46.1292 2440.788,-46.2786"/>
<text text-anchor="middle" x="2449.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1427.3478,-260.9772C1424.5717,-249.4788 1419.0408,-235.3926 1408.0923,-228 1373.9186,-204.9255 706.6909,-217.2128 666.0923,-210 662.3818,-209.3408 658.5792,-208.4682 654.7976,-207.4621"/>
<polygon fill="#000000" stroke="#000000" points="655.4959,-204.0189 644.914,-204.5415 653.5122,-210.7319 655.4959,-204.0189"/>
<text text-anchor="middle" x="1461.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1740.0923" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1740.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1729.325,-174.4519C1721.1833,-162.8518 1708.8938,-148.4571 1694.0923,-141 1667.9718,-127.8404 1494.1057,-115.3594 1393.5741,-109.1292"/>
<polygon fill="#000000" stroke="#000000" points="1393.6805,-105.6292 1383.4848,-108.5097 1393.2514,-112.6161 1393.6805,-105.6292"/>
<text text-anchor="middle" x="1753.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1906.0923" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1906.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1876.6606,-174.6486C1855.3304,-162.9811 1825.3839,-148.4244 1797.0923,-141 1723.131,-121.5907 1508.1771,-111.4377 1394.5109,-107.2959"/>
<polygon fill="#000000" stroke="#000000" points="1394.6216,-103.7978 1384.5026,-106.9373 1394.3708,-110.7933 1394.6216,-103.7978"/>
<text text-anchor="middle" x="1917.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1194.0923" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1194.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1172.7029,-261.5785C1156.7661,-249.7149 1133.904,-234.9493 1111.0923,-228 1016.4181,-199.1588 763.3929,-228.0995 666.0923,-210 662.438,-209.3202 658.6925,-208.4418 654.9647,-207.4392"/>
<polygon fill="#000000" stroke="#000000" points="655.7952,-204.0349 645.2128,-204.5464 653.8045,-210.7458 655.7952,-204.0349"/>
<text text-anchor="middle" x="1209.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="297.0923" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="297.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M297.6228,-260.8006C299.2908,-237.5306 305.6492,-197.4509 329.0923,-174 411.3776,-91.6872 461.7776,-108.873 576.0923,-87 758.9212,-52.0175 2118.8826,-24.135 2390.1128,-18.889"/>
<polygon fill="#000000" stroke="#000000" points="2390.4644,-22.383 2400.3951,-18.6909 2390.3295,-15.3843 2390.4644,-22.383"/>
<text text-anchor="middle" x="409.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M323.0165,-263.1921C343.4692,-251.4987 373.1188,-236.2302 401.0923,-228 467.2008,-208.5499 487.6763,-224.2732 555.0923,-210 559.808,-209.0016 564.6892,-207.7857 569.5264,-206.4619"/>
<polygon fill="#000000" stroke="#000000" points="570.6923,-209.7682 579.3264,-203.628 568.7477,-203.0437 570.6923,-209.7682"/>
<text text-anchor="middle" x="443.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M304.3125,-260.8114C314.6411,-237.1727 335.898,-196.2912 367.0923,-174 378.7796,-165.6483 477.8904,-143.157 492.0923,-141 637.0601,-118.9822 1075.3248,-109.2298 1249.5442,-106.1487"/>
<polygon fill="#000000" stroke="#000000" points="1249.6997,-109.6466 1259.637,-105.9725 1249.5774,-102.6477 1249.6997,-109.6466"/>
<text text-anchor="middle" x="409.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M644.9188,-204.5145C651.8016,-206.7371 659.111,-208.7415 666.0923,-210 934.7677,-258.434 1011.425,-179.5206 1280.0923,-228 1290.7201,-229.9177 1344.7616,-248.6767 1384.9501,-262.8916"/>
<polygon fill="#000000" stroke="#000000" points="1383.9816,-266.2617 1394.5764,-266.3032 1386.32,-259.6637 1383.9816,-266.2617"/>
<text text-anchor="middle" x="1360.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="613.0923" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="613.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M579.2371,-180.303C561.0178,-173.2494 541.242,-164.0924 536.0923,-156 532.5131,-150.3756 532.5131,-146.6244 536.0923,-141 545.061,-126.9064 561.1544,-118.2377 576.3177,-112.952"/>
<polygon fill="#000000" stroke="#000000" points="577.5405,-116.2375 586.0636,-109.944 575.4761,-109.5489 577.5405,-116.2375"/>
<text text-anchor="middle" x="572.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M641.2369,-177.7636C666.6337,-165.6589 705.3792,-149.0057 741.0923,-141 835.881,-119.7515 1115.9435,-110.1149 1249.5663,-106.6328"/>
<polygon fill="#000000" stroke="#000000" points="1249.7986,-110.1281 1259.7057,-106.373 1249.6193,-103.1303 1249.7986,-110.1281"/>
<text text-anchor="middle" x="777.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2563.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2563.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2539.0961,-88.4312C2518.5468,-74.2424 2488.8701,-53.7513 2466.8197,-38.5261"/>
<polygon fill="#000000" stroke="#000000" points="2468.6986,-35.5702 2458.4809,-32.7684 2464.7212,-41.3305 2468.6986,-35.5702"/>
<text text-anchor="middle" x="2555.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M641.0131,-103.6683C846.8009,-93.8527 2127.8429,-32.7504 2390.1855,-20.2373"/>
<polygon fill="#000000" stroke="#000000" points="2390.6802,-23.7178 2400.5021,-19.7453 2390.3466,-16.7258 2390.6802,-23.7178"/>
<text text-anchor="middle" x="1659.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M613.0923,-123.0034C613.0923,-134.7801 613.0923,-150.4102 613.0923,-163.8156"/>
<polygon fill="#000000" stroke="#000000" points="609.5924,-163.9735 613.0923,-173.9735 616.5924,-163.9736 609.5924,-163.9735"/>
<text text-anchor="middle" x="637.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2718.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2718.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2687.0953,-88.3209C2665.4701,-77.2647 2635.6591,-63.1603 2608.0923,-54 2566.2973,-40.1117 2516.9155,-30.3982 2481.9913,-24.5908"/>
<polygon fill="#000000" stroke="#000000" points="2482.5243,-21.1316 2472.0928,-22.9849 2481.4032,-28.0412 2482.5243,-21.1316"/>
<text text-anchor="middle" x="2707.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2275.0923" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2275.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2266.958,-173.9899C2261.2482,-160.3176 2254.1137,-140.8834 2251.0923,-123 2248.4269,-107.2236 2241.9555,-100.1347 2251.0923,-87 2267.8366,-62.929 2344.5895,-40.3539 2394.1184,-27.9332"/>
<polygon fill="#000000" stroke="#000000" points="2395.0666,-31.3044 2403.9389,-25.5136 2393.3919,-24.5076 2395.0666,-31.3044"/>
<text text-anchor="middle" x="2337.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2192.0346,-180.348C2147.3064,-173.4074 2097.0947,-164.3506 2076.0923,-156 2064.7518,-151.491 2064.7013,-144.7642 2053.0923,-141 1991.6841,-121.0883 1567.1078,-110.1034 1394.6578,-106.4205"/>
<polygon fill="#000000" stroke="#000000" points="1394.4817,-102.916 1384.41,-106.2039 1394.3338,-109.9145 1394.4817,-102.916"/>
<text text-anchor="middle" x="2162.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node20" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2884.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2884.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2854.9341,-88.4233C2833.103,-76.8123 2802.1263,-61.9952 2773.0923,-54 2719.7052,-39.2986 2562.3504,-26.7035 2483.3892,-21.1023"/>
<polygon fill="#000000" stroke="#000000" points="2483.4646,-17.5991 2473.2442,-20.3906 2482.9747,-24.582 2483.4646,-17.5991"/>
<text text-anchor="middle" x="2869.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment -->
<g id="node21" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="960.0923" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="960.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M981.6798,-175.1811C997.7125,-163.6093 1020.6079,-148.9448 1043.0923,-141 1080.3442,-127.8372 1181.9501,-116.9328 1251.6865,-110.6898"/>
<polygon fill="#000000" stroke="#000000" points="1252.0794,-114.1688 1261.7328,-109.8028 1251.4637,-107.196 1252.0794,-114.1688"/>
<text text-anchor="middle" x="1090.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge31" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1382.4349,-100.2917C1581.4765,-84.7611 2214.5612,-35.3634 2391.0315,-21.594"/>
<polygon fill="#000000" stroke="#000000" points="2391.3295,-25.0815 2401.0269,-20.8141 2390.7849,-18.1027 2391.3295,-25.0815"/>
<text text-anchor="middle" x="1997.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node23" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3035.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3035.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3008.5678,-88.6051C2987.9748,-76.7635 2958.275,-61.5734 2930.0923,-54 2846.677,-31.5842 2589.6249,-22.1617 2483.5779,-19.1583"/>
<polygon fill="#000000" stroke="#000000" points="2483.5912,-15.6574 2473.4982,-18.8794 2483.3975,-22.6547 2483.5912,-15.6574"/>
<text text-anchor="middle" x="3020.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node24" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1089.0923" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1089.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1110.4241,-175.3353C1125.7093,-164.1404 1147.2046,-149.8668 1168.0923,-141 1196.0042,-129.1513 1228.4938,-120.8259 1256.4169,-115.189"/>
<polygon fill="#000000" stroke="#000000" points="1257.3327,-118.5765 1266.4809,-113.2323 1255.9967,-111.7052 1257.3327,-118.5765"/>
<text text-anchor="middle" x="1211.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node25" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="422.0923" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="422.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M449.673,-263.381C468.8528,-252.7979 495.171,-238.8235 519.0923,-228 535.3097,-220.6622 553.5033,-213.4643 569.533,-207.4567"/>
<polygon fill="#000000" stroke="#000000" points="571.0341,-210.6332 579.1971,-203.8793 568.604,-204.0685 571.0341,-210.6332"/>
<text text-anchor="middle" x="563.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M436.449,-261.3779C440.5894,-255.7368 444.8572,-249.3121 448.0923,-243 462.8362,-214.2328 447.262,-195.8416 471.0923,-174 517.5818,-131.39 546.6697,-149.9614 609.0923,-141 731.0451,-123.4925 1093.5877,-111.466 1249.4922,-106.9661"/>
<polygon fill="#000000" stroke="#000000" points="1250.0105,-110.4528 1259.9062,-106.6679 1249.81,-103.4557 1250.0105,-110.4528"/>
<text text-anchor="middle" x="515.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2042.0923" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2042.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2106.8082,-275.7254C2208.9531,-270.141 2398.811,-257.9189 2426.0923,-243 2473.8953,-216.8588 2505.8215,-194.2064 2494.0923,-141 2486.3093,-105.6947 2467.344,-68.4729 2453.4181,-44.3461"/>
<polygon fill="#000000" stroke="#000000" points="2456.2738,-42.2984 2448.1768,-35.4654 2450.2454,-45.8563 2456.2738,-42.2984"/>
<text text-anchor="middle" x="2549.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1981.5147,-271.7729C1882.3176,-260.268 1678.9636,-238.0629 1506.0923,-228 1319.6983,-217.15 849.9691,-242.3997 666.0923,-210 662.3809,-209.346 658.5776,-208.4771 654.7956,-207.4734"/>
<polygon fill="#000000" stroke="#000000" points="655.493,-204.0301 644.9113,-204.5567 653.5118,-210.7439 655.493,-204.0301"/>
<text text-anchor="middle" x="1751.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2043.0955,-260.6702C2043.6458,-229.7502 2039.5713,-167.9665 2001.0923,-141 1976.5793,-123.8211 1564.5656,-111.2629 1394.559,-106.7892"/>
<polygon fill="#000000" stroke="#000000" points="1394.5364,-103.2875 1384.4484,-106.5251 1394.3536,-110.2851 1394.5364,-103.2875"/>
<text text-anchor="middle" x="2092.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
</g>
</svg>
</div>
