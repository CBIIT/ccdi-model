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
<svg width="2698pt" height="305pt"
 viewBox="0.00 0.00 2698.09 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2694.0877,-301 2694.0877,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1449.0433" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1449.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1537.0433" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1537.0433" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1449.9197,-86.7751C1451.2802,-76.1961 1454.5149,-63.1882 1462.0433,-54 1470.6507,-43.4949 1483.0537,-35.85 1495.3026,-30.3816"/>
<polygon fill="#000000" stroke="#000000" points="1496.6282,-33.6209 1504.574,-26.6127 1493.9921,-27.1362 1496.6282,-33.6209"/>
<text text-anchor="middle" x="1512.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1813.0433" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1813.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1774.0136,-176.6649C1743.4456,-165.2256 1699.6165,-150.0684 1660.0433,-141 1599.3235,-127.0858 1582.2523,-134.5737 1521.0433,-123 1515.7417,-121.9976 1510.2481,-120.8414 1504.7671,-119.6088"/>
<polygon fill="#000000" stroke="#000000" points="1505.4925,-116.1841 1494.9591,-117.3239 1503.9042,-123.0015 1505.4925,-116.1841"/>
<text text-anchor="middle" x="1770.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="330.0433" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="330.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M324.7317,-86.5426C322.8109,-75.6078 322.8198,-62.3081 331.0433,-54 351.7938,-33.0359 1270.1942,-21.0877 1490.0963,-18.5242"/>
<polygon fill="#000000" stroke="#000000" points="1490.3726,-22.0214 1500.3314,-18.4058 1490.2916,-15.0218 1490.3726,-22.0214"/>
<text text-anchor="middle" x="400.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2110.0433" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2110.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2067.4553,-176.373C2032.6354,-164.3655 1981.8503,-148.5914 1936.0433,-141 1753.9096,-110.816 1703.746,-149.5229 1521.0433,-123 1515.3252,-122.1699 1509.4011,-121.0783 1503.5186,-119.8423"/>
<polygon fill="#000000" stroke="#000000" points="1504.2247,-116.4138 1493.7018,-117.6465 1502.6967,-123.245 1504.2247,-116.4138"/>
<text text-anchor="middle" x="2067.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="706.0433" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="706.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="633.0433" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="633.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M700.8763,-260.6882C697.3206,-250.3343 691.8206,-237.5843 684.0433,-228 679.3952,-222.2721 673.6138,-217.0452 667.63,-212.4579"/>
<polygon fill="#000000" stroke="#000000" points="669.6065,-209.5685 659.4326,-206.6118 665.542,-215.2677 669.6065,-209.5685"/>
<text text-anchor="middle" x="759.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node6" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2293.0433" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2293.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2255.2369,-176.0444C2224.5418,-163.9356 2179.816,-148.1863 2139.0433,-141 1868.4312,-93.3042 1793.2499,-160.5408 1521.0433,-123 1515.3194,-122.2106 1509.3916,-121.1455 1503.5069,-119.9254"/>
<polygon fill="#000000" stroke="#000000" points="1504.2083,-116.4959 1493.6876,-117.7471 1502.6922,-123.3298 1504.2083,-116.4959"/>
<text text-anchor="middle" x="2259.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pdx -->
<g id="node7" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="539.0433" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="539.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M532.7937,-260.9769C530.3361,-250.4695 529.4596,-237.4659 536.0433,-228 542.2025,-219.1443 563.9334,-210.674 585.2689,-204.1768"/>
<polygon fill="#000000" stroke="#000000" points="586.3702,-207.5014 594.9865,-201.3361 584.4061,-200.7826 586.3702,-207.5014"/>
<text text-anchor="middle" x="560.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M526.9219,-262.6858C508.5432,-235.7851 478.0764,-181.1113 501.0433,-141 524.6018,-99.8552 548.5887,-103.4832 593.0433,-87 670.1231,-58.4198 693.3624,-63.2934 775.0433,-54 914.8143,-38.0973 1347.3296,-23.7977 1490.4928,-19.3913"/>
<polygon fill="#000000" stroke="#000000" points="1490.7998,-22.8836 1500.688,-19.0792 1490.5856,-15.8869 1490.7998,-22.8836"/>
<text text-anchor="middle" x="525.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M667.8223,-180.5135C686.3092,-174.0215 709.2442,-165.3458 729.0433,-156 741.1075,-150.3053 742.2452,-144.7663 755.0433,-141 833.1623,-118.0104 1039.7216,-127.2311 1121.0433,-123 1209.2977,-118.4082 1310.8894,-112.7801 1377.3351,-109.0527"/>
<polygon fill="#000000" stroke="#000000" points="1377.9021,-112.5265 1387.6901,-108.4713 1377.5096,-105.5375 1377.9021,-112.5265"/>
<text text-anchor="middle" x="791.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M619.3034,-209.3741C610.7989,-219.6514 599.3716,-232.6411 588.0433,-243 581.6894,-248.8101 574.4104,-254.5722 567.4407,-259.7272"/>
<polygon fill="#000000" stroke="#000000" points="564.946,-257.2101 558.8707,-265.8901 569.0329,-262.8932 564.946,-257.2101"/>
<text text-anchor="middle" x="639.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="651.0433" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="651.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M595.2434,-182.5139C569.6574,-174.1435 542.7422,-160.2644 556.0433,-141 561.7271,-132.7678 581.0272,-124.7626 600.7602,-118.3996"/>
<polygon fill="#000000" stroke="#000000" points="601.903,-121.7098 610.4244,-115.4141 599.8368,-115.0217 601.903,-121.7098"/>
<text text-anchor="middle" x="592.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1600.0433" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1600.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1589.2504,-87.1814C1583.0376,-77.2235 1574.9203,-64.7016 1567.0433,-54 1564.3109,-50.2878 1561.3185,-46.4555 1558.3151,-42.738"/>
<polygon fill="#000000" stroke="#000000" points="1560.8863,-40.355 1551.8191,-34.8745 1555.4896,-44.8132 1560.8863,-40.355"/>
<text text-anchor="middle" x="1632.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1766.0433" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1766.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1745.6255,-87.5175C1731.658,-76.4006 1712.2562,-62.5409 1693.0433,-54 1657.6345,-38.2595 1614.5272,-28.9865 1582.6073,-23.805"/>
<polygon fill="#000000" stroke="#000000" points="1583.0788,-20.3363 1572.6607,-22.2634 1582.0066,-27.2537 1583.0788,-20.3363"/>
<text text-anchor="middle" x="1780.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1167.0433" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1167.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1221.4361,-277.4269C1325.8901,-273.3141 1549.2587,-258.8922 1606.0433,-210 1629.9776,-189.3923 1643.3432,-165.1959 1623.0433,-141 1608.2495,-123.367 1543.5553,-127.7942 1521.0433,-123 1515.9748,-121.9206 1510.7219,-120.7361 1505.4675,-119.5062"/>
<polygon fill="#000000" stroke="#000000" points="1505.9491,-116.0227 1495.4092,-117.1006 1504.3208,-122.8307 1505.9491,-116.0227"/>
<text text-anchor="middle" x="1675.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1117.7061,-271.1252C1052.0943,-260.7465 932.4755,-242.1504 830.0433,-228 766.152,-219.1738 748.9029,-224.4451 686.0433,-210 682.6249,-209.2145 679.1169,-208.2926 675.6125,-207.2885"/>
<polygon fill="#000000" stroke="#000000" points="676.41,-203.8723 665.8232,-204.2859 674.3572,-210.5645 676.41,-203.8723"/>
<text text-anchor="middle" x="977.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment -->
<g id="node12" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2449.0433" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2449.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2419.9695,-176.1944C2395.8617,-163.9976 2360.2789,-148.0541 2327.0433,-141 2151.7914,-103.8036 1698.6012,-146.8736 1521.0433,-123 1515.235,-122.219 1509.2178,-121.1474 1503.2493,-119.913"/>
<polygon fill="#000000" stroke="#000000" points="1503.8168,-116.4538 1493.2961,-117.7045 1502.3004,-123.2876 1503.8168,-116.4538"/>
<text text-anchor="middle" x="2419.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="743.0433" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="743.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M773.4802,-177.9293C801.1498,-165.8464 843.4327,-149.13 882.0433,-141 905.8726,-135.9824 1230.4372,-117.2783 1377.5047,-108.9933"/>
<polygon fill="#000000" stroke="#000000" points="1377.9927,-112.4715 1387.7803,-108.4151 1377.5994,-105.4825 1377.9927,-112.4715"/>
<text text-anchor="middle" x="921.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1145.0433" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1145.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1155.7746,-173.8976C1163.5283,-162.519 1175.0732,-148.6005 1189.0433,-141 1220.58,-123.8422 1311.7958,-114.1673 1377.2769,-109.264"/>
<polygon fill="#000000" stroke="#000000" points="1377.8321,-112.733 1387.5522,-108.5176 1377.3249,-105.7514 1377.8321,-112.733"/>
<text text-anchor="middle" x="1268.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_arm -->
<g id="node15" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1921.0433" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1921.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1901.5258,-87.8153C1887.1948,-76.2264 1866.7011,-61.6951 1846.0433,-54 1799.0348,-36.4892 1657.5453,-25.4356 1583.4446,-20.6884"/>
<polygon fill="#000000" stroke="#000000" points="1583.6526,-17.1946 1573.4528,-20.0603 1583.2135,-24.1808 1583.6526,-17.1946"/>
<text text-anchor="middle" x="1922.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1922.0433" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1922.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1921.6963,-260.7218C1920.3694,-238.0951 1915.0629,-199.4421 1895.0433,-174 1875.74,-149.4683 1863.0998,-149.4277 1833.0433,-141 1699.3039,-103.5003 1658.3537,-143.9356 1521.0433,-123 1515.5502,-122.1625 1509.8646,-121.0963 1504.2073,-119.9024"/>
<polygon fill="#000000" stroke="#000000" points="1504.6257,-116.4094 1494.1023,-117.6369 1503.0944,-123.2398 1504.6257,-116.4094"/>
<text text-anchor="middle" x="1954.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1872.384,-273.3401C1839.1853,-269.632 1794.5208,-264.7887 1755.0433,-261 1581.0044,-244.2974 1537.6146,-237.6608 1363.0433,-228 1212.7756,-219.6842 834.1898,-236.4979 686.0433,-210 682.3335,-209.3365 678.5315,-208.4609 674.7502,-207.4527"/>
<polygon fill="#000000" stroke="#000000" points="675.4493,-204.0097 664.8672,-204.5291 673.4635,-210.7221 675.4493,-204.0097"/>
<text text-anchor="middle" x="1607.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1974.0686,-276.8393C2112.222,-270.5712 2480.2258,-250.2189 2516.0433,-210 2526.6842,-198.0514 2523.3499,-188.2342 2516.0433,-174 2439.4668,-24.8213 2766.2167,-155.8221 1975.0433,-54 1833.0955,-35.7317 1664.0083,-24.9067 1583.7635,-20.4253"/>
<polygon fill="#000000" stroke="#000000" points="1583.6802,-16.9155 1573.5027,-19.8599 1583.295,-23.9049 1583.6802,-16.9155"/>
<text text-anchor="middle" x="2549.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cytogenomic_file -->
<g id="node17" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1656.0433" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1656.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1574.044,-271.6277C1453.878,-260.9907 1222.8476,-241.1728 1026.0433,-228 875.0584,-217.894 834.6386,-238.6003 686.0433,-210 682.3933,-209.2975 678.6508,-208.4031 674.925,-207.3898"/>
<polygon fill="#000000" stroke="#000000" points="675.7596,-203.9864 665.1763,-204.48 673.7575,-210.6939 675.7596,-203.9864"/>
<text text-anchor="middle" x="1287.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node18" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="918.0433" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="918.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M938.3994,-174.0773C952.8673,-162.466 973.3341,-148.2092 994.0433,-141 1029.2195,-128.7546 1258.1619,-115.0774 1377.2713,-108.677"/>
<polygon fill="#000000" stroke="#000000" points="1377.5994,-112.1645 1387.3985,-108.1361 1377.226,-105.1745 1377.5994,-112.1645"/>
<text text-anchor="middle" x="1080.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M928.8133,-174.0096C936.4362,-162.8273 947.6624,-149.0869 961.0433,-141 1051.6059,-86.2675 1372.2199,-39.6386 1491.7134,-23.7846"/>
<polygon fill="#000000" stroke="#000000" points="1492.181,-27.2533 1501.6383,-22.4774 1491.2669,-20.3133 1492.181,-27.2533"/>
<text text-anchor="middle" x="1204.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment_response -->
<g id="node20" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1368.0433" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1368.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1357.1075,-173.7033C1352.4622,-163.3544 1349.4622,-150.6044 1356.0433,-141 1361.0182,-133.7395 1376.7106,-126.5678 1393.8228,-120.5595"/>
<polygon fill="#000000" stroke="#000000" points="1395.0448,-123.8414 1403.4166,-117.348 1392.8227,-117.2034 1395.0448,-123.8414"/>
<text text-anchor="middle" x="1439.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="76.0433" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="76.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M107.1749,-262.4969C130.8558,-250.7626 164.6162,-235.7585 196.0433,-228 267.1557,-210.4443 478.2949,-198.9396 578.7555,-194.309"/>
<polygon fill="#000000" stroke="#000000" points="579.1636,-197.7941 588.9942,-193.8432 578.8454,-190.8014 579.1636,-197.7941"/>
<text text-anchor="middle" x="257.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M647.3184,-123.0034C644.8819,-134.7801 641.648,-150.4102 638.8745,-163.8156"/>
<polygon fill="#000000" stroke="#000000" points="635.3716,-163.4718 636.7729,-173.9735 642.2264,-164.8901 635.3716,-163.4718"/>
<text text-anchor="middle" x="684.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M688.3627,-93.063C728.0114,-80.9435 792.7523,-62.7535 850.0433,-54 973.9033,-35.0754 1356.2211,-22.9892 1490.1297,-19.2444"/>
<polygon fill="#000000" stroke="#000000" points="1490.5531,-22.7341 1500.4523,-18.9585 1490.3592,-15.7368 1490.5531,-22.7341"/>
<text text-anchor="middle" x="890.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- publication -->
<g id="node23" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2627.0433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2627.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge13" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2607.7331,-87.8024C2593.0447,-75.8828 2571.7249,-60.9515 2550.0433,-54 2457.4789,-24.3224 1770.1083,-19.0564 1583.6108,-18.1708"/>
<polygon fill="#000000" stroke="#000000" points="1583.5937,-14.6708 1573.5778,-18.1251 1583.5617,-21.6707 1583.5937,-14.6708"/>
<text text-anchor="middle" x="2630.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node24" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1544.0433" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1544.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1539.577,-173.7014C1536.2172,-163.0963 1530.6789,-150.0868 1522.0433,-141 1515.3964,-134.0059 1507.1019,-128.1817 1498.5116,-123.4008"/>
<polygon fill="#000000" stroke="#000000" points="1500.0055,-120.2336 1489.5093,-118.7911 1496.815,-126.4643 1500.0055,-120.2336"/>
<text text-anchor="middle" x="1575.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node25" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="286.0433" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="286.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M301.6912,-260.8211C312.6194,-249.4102 328.2193,-235.4844 345.0433,-228 385.6879,-209.9186 507.2689,-199.6538 578.8058,-195.0246"/>
<polygon fill="#000000" stroke="#000000" points="579.2221,-198.5054 588.9817,-194.3822 578.781,-191.5193 579.2221,-198.5054"/>
<text text-anchor="middle" x="436.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
