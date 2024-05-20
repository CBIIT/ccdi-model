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
<svg width="3514pt" height="305pt"
 viewBox="0.00 0.00 3513.99 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 3509.9919,-301 3509.9919,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="27.9475" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="27.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2662.9475" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2662.9475" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M24.8595,-260.8911C24.0883,-250.0873 25.1748,-236.8031 32.9475,-228 221.4226,-14.541 377.6553,-137.238 657.9475,-87 766.9635,-67.4606 794.5195,-62.4805 904.9475,-54 1251.5396,-27.383 2372.7524,-19.6329 2616.0768,-18.2462"/>
<polygon fill="#000000" stroke="#000000" points="2616.3611,-21.7447 2626.3412,-18.1885 2616.3217,-14.7448 2616.3611,-21.7447"/>
<text text-anchor="middle" x="154.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node15" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="611.9475" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="611.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M49.9933,-267.5569C54.8541,-265.2368 60.0232,-262.922 64.9475,-261 90.8829,-250.8774 98.7296,-252.3665 124.9475,-243 141.2705,-237.1685 144.0996,-232.0734 160.9475,-228 234.7604,-210.1539 454.3625,-198.7287 557.412,-194.206"/>
<polygon fill="#000000" stroke="#000000" points="557.767,-197.694 567.6062,-193.7644 557.464,-190.7005 557.767,-197.694"/>
<text text-anchor="middle" x="184.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1127.9475" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1127.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1915.9475" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1915.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1180.0011,-277.4251C1392.0722,-270.7913 2181.6051,-243.8952 2221.9475,-210 2245.8401,-189.9258 2255.7396,-164.2705 2234.9475,-141 2218.7679,-122.8917 2076.7681,-112.7542 1987.7622,-108.1273"/>
<polygon fill="#000000" stroke="#000000" points="1987.8826,-104.629 1977.7178,-107.6168 1987.5272,-111.62 1987.8826,-104.629"/>
<text text-anchor="middle" x="2288.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1123.5844,-260.9041C1119.2972,-238.8077 1115.4193,-201.0435 1130.9475,-174 1144.7648,-149.9363 1157.6072,-149.7271 1183.9475,-141 1459.482,-49.7099 2395.6543,-23.8352 2616.1559,-18.9433"/>
<polygon fill="#000000" stroke="#000000" points="2616.4864,-22.4371 2626.4076,-18.7197 2616.3336,-15.4387 2616.4864,-22.4371"/>
<text text-anchor="middle" x="1226.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1091.8685,-265.8831C1051.3206,-251.1792 990.3983,-229.2155 984.9475,-228 925.6236,-214.7715 754.1878,-201.6751 665.903,-195.5653"/>
<polygon fill="#000000" stroke="#000000" points="666.0358,-192.0662 655.8195,-194.8728 665.5562,-199.0498 666.0358,-192.0662"/>
<text text-anchor="middle" x="1070.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1973.9418,-98.2456C2117.6238,-81.5116 2487.8187,-38.3965 2617.3629,-23.3091"/>
<polygon fill="#000000" stroke="#000000" points="2617.8208,-26.7795 2627.3487,-22.146 2617.011,-19.8265 2617.8208,-26.7795"/>
<text text-anchor="middle" x="2385.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node4" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2796.9475" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2796.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2770.7929,-88.019C2748.6408,-73.6367 2716.8557,-53.0001 2693.53,-37.8558"/>
<polygon fill="#000000" stroke="#000000" points="2695.3353,-34.8549 2685.042,-32.3449 2691.5234,-40.726 2695.3353,-34.8549"/>
<text text-anchor="middle" x="2799.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="962.9475" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="962.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M971.6756,-261.1572C988.8682,-228.5442 1030.6639,-160.8384 1089.9475,-141 1160.2446,-117.4761 1654.9313,-108.4756 1843.3285,-105.877"/>
<polygon fill="#000000" stroke="#000000" points="1843.4603,-109.3756 1853.4118,-105.74 1843.3651,-102.3763 1843.4603,-109.3756"/>
<text text-anchor="middle" x="1080.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M931.8048,-264.1241C919.2589,-257.8959 904.7542,-250.3937 891.9475,-243 881.3784,-236.8981 880.3755,-232.2825 868.9475,-228 832.7801,-214.4469 729.7787,-202.8999 665.6902,-196.7512"/>
<polygon fill="#000000" stroke="#000000" points="665.6519,-193.2321 655.3668,-195.7751 664.9929,-200.201 665.6519,-193.2321"/>
<text text-anchor="middle" x="936.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2951.9475" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2951.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2929.0104,-88.2841C2912.3151,-76.916 2888.7308,-62.4561 2865.9475,-54 2814.2867,-34.8259 2751.3449,-25.6939 2709.374,-21.4603"/>
<polygon fill="#000000" stroke="#000000" points="2709.4624,-17.9529 2699.1749,-20.4864 2708.7969,-24.9212 2709.4624,-17.9529"/>
<text text-anchor="middle" x="2943.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2409.9475" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2409.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2364.6681,-180.7005C2334.424,-172.8608 2297.601,-162.6683 2282.9475,-156 2271.8396,-150.9451 2271.4485,-145.0824 2259.9475,-141 2211.4146,-123.7728 2073.4838,-113.4692 1987.7416,-108.5452"/>
<polygon fill="#000000" stroke="#000000" points="1987.7346,-105.0394 1977.5535,-107.9713 1987.3408,-112.0283 1987.7346,-105.0394"/>
<text text-anchor="middle" x="2329.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sequencing_file -->
<g id="node9" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="156.9475" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="156.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M180.9494,-261.4991C198.1555,-249.9207 222.3676,-235.5325 245.9475,-228 302.5658,-209.9135 470.4167,-199.0933 557.7607,-194.5367"/>
<polygon fill="#000000" stroke="#000000" points="558.1926,-198.0192 568.0004,-194.012 557.8344,-191.0284 558.1926,-198.0192"/>
<text text-anchor="middle" x="312.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="715.9475" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="715.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M758.5534,-95.7598C816.6382,-83.6274 924.0838,-62.8351 1016.9475,-54 1339.5741,-23.3053 2382.1553,-18.7422 2616.0735,-18.1003"/>
<polygon fill="#000000" stroke="#000000" points="2616.2897,-21.5999 2626.2804,-18.0734 2616.2712,-14.5999 2616.2897,-21.5999"/>
<text text-anchor="middle" x="1057.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M673.9742,-114.5124C648.8928,-121.1313 620.4781,-130.608 612.9475,-141 608.2504,-147.4819 606.7456,-155.7447 606.7644,-163.7226"/>
<polygon fill="#000000" stroke="#000000" points="603.2875,-164.1626 607.5263,-173.8725 610.2678,-163.6386 603.2875,-164.1626"/>
<text text-anchor="middle" x="653.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3099.9475" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3099.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3072.7627,-88.3912C3052.3753,-76.7642 3023.3769,-61.9411 2995.9475,-54 2943.2938,-38.7561 2787.5824,-26.4397 2709.1685,-21.0068"/>
<polygon fill="#000000" stroke="#000000" points="2709.3061,-17.5081 2699.0904,-20.317 2708.8281,-24.4918 2709.3061,-17.5081"/>
<text text-anchor="middle" x="3090.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2538.9475" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2538.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2499.0114,-180.0689C2491.691,-177.9779 2484.1038,-175.8739 2476.9475,-174 2442.9489,-165.0975 2432.2662,-169.8081 2399.9475,-156 2388.7249,-151.2052 2388.5013,-144.9306 2376.9475,-141 2307.1168,-117.2436 2099.9979,-109.0433 1988.6704,-106.3069"/>
<polygon fill="#000000" stroke="#000000" points="1988.6113,-102.8047 1978.5311,-106.0663 1988.4452,-109.8027 1988.6113,-102.8047"/>
<text text-anchor="middle" x="2443.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="373.9475" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="373.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M376.1189,-260.7731C378.4235,-249.6414 383.171,-236.0452 392.9475,-228 417.4555,-207.8323 501.1171,-198.7129 557.6471,-194.774"/>
<polygon fill="#000000" stroke="#000000" points="558.1195,-198.2505 567.8664,-194.0973 557.657,-191.2658 558.1195,-198.2505"/>
<text text-anchor="middle" x="484.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1187.9475" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1187.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1217.4872,-177.7692C1244.1243,-165.6683 1284.7164,-149.0173 1321.9475,-141 1419.3978,-120.0151 1707.451,-110.2113 1843.3818,-106.6559"/>
<polygon fill="#000000" stroke="#000000" points="1843.7833,-110.1469 1853.6899,-106.3907 1843.6031,-103.1492 1843.7833,-110.1469"/>
<text text-anchor="middle" x="1361.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M567.7308,-193.532C438.4424,-198.181 68.8515,-212.7456 47.9475,-228 40.3562,-233.5397 35.6454,-242.4012 32.7225,-251.1947"/>
<polygon fill="#000000" stroke="#000000" points="29.3258,-250.3487 30.1239,-260.9135 36.0883,-252.1569 29.3258,-250.3487"/>
<text text-anchor="middle" x="84.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M650.9762,-183.5426C707.3789,-171.7165 815.1023,-150.6121 907.9475,-141 1089.5307,-122.201 1643.9715,-110.1438 1843.4703,-106.3167"/>
<polygon fill="#000000" stroke="#000000" points="1843.6192,-109.8145 1853.5507,-106.1245 1843.4857,-102.8158 1843.6192,-109.8145"/>
<text text-anchor="middle" x="944.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M649.3604,-182.2178C664.7519,-176.6364 681.7837,-168.2424 693.9475,-156 700.3957,-149.5102 705.0861,-140.8259 708.436,-132.4651"/>
<polygon fill="#000000" stroke="#000000" points="711.7664,-133.5445 711.7776,-122.9497 705.1618,-131.2251 711.7664,-133.5445"/>
<text text-anchor="middle" x="741.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- molecular_test -->
<g id="node16" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1333.9475" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1333.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1363.3172,-175.165C1385.3195,-163.4256 1416.5658,-148.561 1445.9475,-141 1519.0556,-122.1865 1730.8896,-111.7926 1843.53,-107.4538"/>
<polygon fill="#000000" stroke="#000000" points="1843.922,-110.9415 1853.7822,-107.065 1843.6567,-103.9465 1843.922,-110.9415"/>
<text text-anchor="middle" x="1509.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- cytogenomic_file -->
<g id="node17" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="596.9475" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="596.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M585.3786,-260.9093C580.5717,-251.0902 576.943,-238.7875 580.9475,-228 582.433,-223.9985 584.5846,-220.1437 587.0725,-216.5398"/>
<polygon fill="#000000" stroke="#000000" points="589.8679,-218.6476 593.3322,-208.6351 584.3802,-214.3018 589.8679,-218.6476"/>
<text text-anchor="middle" x="652.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment_response -->
<g id="node18" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1536.9475" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1536.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1554.5599,-174.0291C1566.9604,-162.5532 1584.5702,-148.4726 1602.9475,-141 1645.2573,-123.796 1765.5664,-113.7178 1844.1034,-108.7898"/>
<polygon fill="#000000" stroke="#000000" points="1844.6516,-112.2629 1854.4184,-108.157 1844.2229,-105.276 1844.6516,-112.2629"/>
<text text-anchor="middle" x="1685.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pathology_file -->
<g id="node19" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="780.9475" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="780.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M764.9681,-261.3202C754.2787,-250.4067 739.385,-236.8481 723.9475,-228 704.5317,-216.8717 681.2187,-208.6745 660.9014,-202.9379"/>
<polygon fill="#000000" stroke="#000000" points="661.765,-199.5458 651.1983,-200.3174 659.9398,-206.3037 661.765,-199.5458"/>
<text text-anchor="middle" x="805.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2718.9475" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2718.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2638.7614,-179.7839C2585.0877,-171.332 2522.1136,-160.7782 2509.9475,-156 2498.5882,-151.5386 2498.5304,-144.844 2486.9475,-141 2440.8008,-125.6853 2131.2148,-112.7377 1988.1663,-107.4953"/>
<polygon fill="#000000" stroke="#000000" points="1988.2812,-103.9972 1978.1605,-107.1312 1988.0266,-110.9926 1988.2812,-103.9972"/>
<text text-anchor="middle" x="2595.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2710.6199,-173.8805C2704.3939,-162.4946 2694.7518,-148.5745 2681.9475,-141 2654.3812,-124.6928 2560.1338,-147.0202 2538.9475,-123 2506.3902,-86.0876 2575.8135,-50.7162 2623.3292,-31.9319"/>
<polygon fill="#000000" stroke="#000000" points="2624.7201,-35.147 2632.7973,-28.2907 2622.2074,-28.6135 2624.7201,-35.147"/>
<text text-anchor="middle" x="2624.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_personnel -->
<g id="node21" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3274.9475" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3274.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3242.2165,-88.1866C3217.7502,-76.458 3183.1166,-61.5973 3150.9475,-54 3067.9173,-34.3909 2814.7797,-23.3913 2709.5702,-19.5621"/>
<polygon fill="#000000" stroke="#000000" points="2709.3857,-16.0534 2699.2667,-19.1929 2709.1349,-23.0489 2709.3857,-16.0534"/>
<text text-anchor="middle" x="3265.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1732.9475" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1732.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1749.9377,-174.4858C1761.4542,-163.4989 1777.5193,-149.7973 1793.9475,-141 1812.6001,-131.0115 1834.3799,-123.457 1854.3333,-117.9137"/>
<polygon fill="#000000" stroke="#000000" points="1855.5006,-121.2251 1864.2663,-115.2743 1853.7029,-114.4598 1855.5006,-121.2251"/>
<text text-anchor="middle" x="1852.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node23" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1924.9475" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1924.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1920.1665,-173.8072C1918.8777,-168.1428 1917.6476,-161.8485 1916.9475,-156 1916.0847,-148.7924 1915.6719,-140.9718 1915.5094,-133.6697"/>
<polygon fill="#000000" stroke="#000000" points="1919.0078,-133.4454 1915.4271,-123.474 1912.0081,-133.502 1919.0078,-133.4454"/>
<text text-anchor="middle" x="1996.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node24" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3442.9475" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3442.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge25" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3416.7391,-88.4437C3396.3754,-76.5175 3366.9722,-61.2923 3338.9475,-54 3278.542,-38.2819 2852.8938,-23.8605 2709.7693,-19.4073"/>
<polygon fill="#000000" stroke="#000000" points="2709.6686,-15.9026 2699.5652,-19.0918 2709.4522,-22.8993 2709.6686,-15.9026"/>
<text text-anchor="middle" x="3427.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2127.9475" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2127.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2113.9141,-173.8113C2104.3795,-162.6949 2090.8297,-149.1013 2075.9475,-141 2048.4328,-126.0221 2015.0137,-117.269 1985.8482,-112.1567"/>
<polygon fill="#000000" stroke="#000000" points="1986.1608,-108.6613 1975.7261,-110.496 1985.0275,-115.5689 1986.1608,-108.6613"/>
<text text-anchor="middle" x="2163.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
