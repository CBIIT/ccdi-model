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
<svg width="2611pt" height="392pt"
 viewBox="0.00 0.00 2610.57 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2606.5682,-388 2606.5682,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="674.5682" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="674.5682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1077.5682" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1077.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M694.3287,-266.1736C714.2172,-253.9919 746.2128,-236.3375 776.5682,-228 883.1339,-198.7306 916.2574,-231.9475 1024.5682,-210 1028.2112,-209.2618 1031.9487,-208.3424 1035.6712,-207.3123"/>
<polygon fill="#000000" stroke="#000000" points="1036.85,-210.6127 1045.4146,-204.3759 1034.83,-203.9104 1036.85,-210.6127"/>
<text text-anchor="middle" x="800.5682" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="540.5682" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="540.5682" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge8" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M646.6154,-276.9107C531.3482,-267.6582 95.2392,-226.1777 15.5682,-123 -44.9966,-44.5656 89.9236,-59.8946 119.5682,-54 190.2173,-39.9521 400.2312,-26.2714 494.2079,-20.6619"/>
<polygon fill="#000000" stroke="#000000" points="494.4986,-24.1509 504.274,-20.0654 494.0845,-17.1631 494.4986,-24.1509"/>
<text text-anchor="middle" x="76.5682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node2" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="160.5682" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="160.5682" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M155.3754,-347.6578C153.4993,-336.7664 153.5135,-323.4718 161.5682,-315 169.7513,-306.3933 518.8881,-287.2156 636.4163,-280.992"/>
<polygon fill="#000000" stroke="#000000" points="636.6075,-284.4868 646.4091,-280.4645 636.2385,-277.4966 636.6075,-284.4868"/>
<text text-anchor="middle" x="270.0682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M150.7907,-347.6686C146.5978,-337.052 144.1612,-324.0417 151.5682,-315 234.7176,-213.5001 604.8132,-238.9161 735.5682,-228 863.8154,-217.2932 898.309,-234.9114 1024.5682,-210 1028.2149,-209.2805 1031.9551,-208.3742 1035.6793,-207.3529"/>
<polygon fill="#000000" stroke="#000000" points="1036.8522,-210.6552 1045.4255,-204.4304 1034.8416,-203.9502 1036.8522,-210.6552"/>
<text text-anchor="middle" x="359.0682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node13" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1161.5682" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1161.5682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M261.6059,-353.6917C298.7412,-348.0251 340.9039,-340.2383 378.5682,-330 396.4891,-325.1286 399.3613,-318.6601 417.5682,-315 550.0873,-288.3598 890.8367,-307.8819 1025.5682,-297 1052.0529,-294.8609 1081.2822,-291.1678 1105.8343,-287.6813"/>
<polygon fill="#000000" stroke="#000000" points="1106.6522,-291.0995 1116.0486,-286.2049 1105.6507,-284.1715 1106.6522,-291.0995"/>
<text text-anchor="middle" x="526.0682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant -->
<g id="node20" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1539.5682" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1539.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1105.8991,-178.0326C1136.3456,-163.0331 1180.5561,-141.2889 1181.5682,-141 1233.6944,-126.1195 1379.694,-114.8689 1468.3201,-109.166"/>
<polygon fill="#000000" stroke="#000000" points="1468.5448,-112.6588 1478.3026,-108.5314 1468.1007,-105.6729 1468.5448,-112.6588"/>
<text text-anchor="middle" x="1218.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="84.5682" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="84.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M100.6621,-87.3929C112.4307,-75.7658 129.4467,-61.363 147.5682,-54 209.2367,-28.9435 403.6971,-21.1838 493.8416,-18.899"/>
<polygon fill="#000000" stroke="#000000" points="494.1313,-22.3931 504.0438,-18.6526 493.9622,-15.3951 494.1313,-22.3931"/>
<text text-anchor="middle" x="196.0682" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1233.5682" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1233.5682" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1162.0559,-356.7957C1133.8559,-351.4001 1101.7691,-342.988 1074.5682,-330 1064.8594,-325.3641 1065.5923,-318.9079 1055.5682,-315 1005.9445,-295.6539 869.5603,-302.3507 816.5682,-297 781.0058,-293.4092 740.5781,-288.1711 711.979,-284.2704"/>
<polygon fill="#000000" stroke="#000000" points="712.3921,-280.7943 702.0085,-282.8993 711.4385,-287.7291 712.3921,-280.7943"/>
<text text-anchor="middle" x="1141.0682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1316.2672,-363.8344C1407.3533,-359.7864 1537.8656,-348.1891 1512.5682,-315 1405.8315,-174.9659 1298.8917,-261.6672 1130.5682,-210 1127.4097,-209.0305 1124.1553,-208.001 1120.8862,-206.9446"/>
<polygon fill="#000000" stroke="#000000" points="1121.7089,-203.5306 1111.1159,-203.7274 1119.5195,-210.1795 1121.7089,-203.5306"/>
<text text-anchor="middle" x="1562.0682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1228.3675,-347.7154C1224.8006,-337.3706 1219.3006,-324.6206 1211.5682,-315 1207.2461,-309.6224 1201.9279,-304.6693 1196.3899,-300.2682"/>
<polygon fill="#000000" stroke="#000000" points="1198.3335,-297.3527 1188.2093,-294.2299 1194.1764,-302.9846 1198.3335,-297.3527"/>
<text text-anchor="middle" x="1287.0682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node6" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="2070.5682" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="2070.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2028.7849,-176.5152C1995.7869,-164.9165 1948.3333,-149.6204 1905.5682,-141 1804.8428,-120.6961 1686.1197,-111.6932 1611.8318,-107.8065"/>
<polygon fill="#000000" stroke="#000000" points="1611.815,-104.3013 1601.6509,-107.2914 1611.4612,-111.2923 1611.815,-104.3013"/>
<text text-anchor="middle" x="2024.5682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="838.5682" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="838.5682" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M732.7231,-358.7335C692.7778,-353.5959 653.9534,-344.8535 641.5682,-330 633.7107,-320.5764 639.811,-309.1847 648.8053,-299.5601"/>
<polygon fill="#000000" stroke="#000000" points="651.264,-302.0515 656.0641,-292.6064 646.4217,-296.9966 651.264,-302.0515"/>
<text text-anchor="middle" x="733.0682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M841.1445,-347.8659C843.2532,-337.5712 847.0032,-324.8212 853.5682,-315 874.8223,-283.2041 887.8878,-280.8672 920.5682,-261 956.9965,-238.8544 1001.791,-219.8957 1034.1964,-207.487"/>
<polygon fill="#000000" stroke="#000000" points="1035.7126,-210.6558 1043.8325,-203.85 1033.2407,-204.1067 1035.7126,-210.6558"/>
<text text-anchor="middle" x="1012.0682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M845.8434,-347.8735C851.4053,-336.4847 860.2299,-322.5639 872.5682,-315 901.7549,-297.1075 991.5981,-301.246 1025.5682,-297 1051.6238,-293.7432 1080.4611,-289.9531 1104.8515,-286.6931"/>
<polygon fill="#000000" stroke="#000000" points="1105.5648,-290.1289 1115.0113,-285.3315 1104.635,-283.1909 1105.5648,-290.1289"/>
<text text-anchor="middle" x="964.0682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2342.5682" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2342.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2310.625,-177.4967C2282.3368,-165.3941 2239.5934,-148.8949 2200.5682,-141 2089.9445,-118.6206 1759.9754,-109.3904 1612.356,-106.3059"/>
<polygon fill="#000000" stroke="#000000" points="1612.1178,-102.8004 1602.0481,-106.0943 1611.9741,-109.7989 1612.1178,-102.8004"/>
<text text-anchor="middle" x="2295.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- follow_up -->
<g id="node9" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="2469.5682" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="2469.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2439.9416,-176.7691C2414.7648,-164.6502 2377.2842,-148.5205 2342.5682,-141 2272.3777,-125.7947 1795.8279,-111.7649 1611.8404,-106.8523"/>
<polygon fill="#000000" stroke="#000000" points="1611.8131,-103.3504 1601.7237,-106.5835 1611.6272,-110.3479 1611.8131,-103.3504"/>
<text text-anchor="middle" x="2433.5682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="239.5682" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="239.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M241.9626,-86.8809C244.4348,-75.6457 249.4429,-61.8948 259.5682,-54 277.6968,-39.865 419.2144,-27.1754 494.2307,-21.3588"/>
<polygon fill="#000000" stroke="#000000" points="494.6508,-24.837 504.3547,-20.5842 494.1168,-17.8574 494.6508,-24.837"/>
<text text-anchor="middle" x="321.5682" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="397.5682" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="397.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge36" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M389.9331,-86.7062C386.8227,-76.1028 385.4216,-63.0934 392.5682,-54 405.1305,-38.0158 455.9932,-28.2456 494.6163,-22.9912"/>
<polygon fill="#000000" stroke="#000000" points="495.1752,-26.4481 504.6413,-21.6895 494.2738,-19.5063 495.1752,-26.4481"/>
<text text-anchor="middle" x="443.5682" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="915.5682" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="915.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M941.4533,-174.431C950.0801,-168.5722 959.7402,-162.0078 968.5682,-156 978.3519,-149.3419 979.38,-144.8566 990.5682,-141 1034.4797,-125.8635 1328.5949,-112.9459 1467.3573,-107.6135"/>
<polygon fill="#000000" stroke="#000000" points="1467.6174,-111.1062 1477.4767,-107.2275 1467.3505,-104.1113 1467.6174,-111.1062"/>
<text text-anchor="middle" x="1070.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1210.4473,-275.8111C1365.9437,-265.4577 1840.4182,-232.1738 1864.5682,-210 1887.3934,-189.0427 1895.2758,-164.052 1874.5682,-141 1857.3544,-121.8372 1705.2254,-112.0012 1611.994,-107.7295"/>
<polygon fill="#000000" stroke="#000000" points="1611.9139,-104.2225 1601.7675,-107.2724 1611.6012,-111.2155 1611.9139,-104.2225"/>
<text text-anchor="middle" x="1926.0682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1127.0793,-265.9555C1120.6736,-263.9777 1113.9791,-262.2001 1107.5682,-261 988.4397,-238.7001 665.228,-277.5018 564.5682,-210 526.1752,-184.2539 520.7869,-167.2962 507.5682,-123 499.4767,-95.8849 511.7888,-65.0051 523.6067,-43.7892"/>
<polygon fill="#000000" stroke="#000000" points="526.6952,-45.442 528.753,-35.0489 520.6631,-41.8902 526.6952,-45.442"/>
<text text-anchor="middle" x="559.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="603.5682" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="603.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M587.8697,-87.0281C583.1276,-81.3727 578.0052,-75.0279 573.5682,-69 567.6917,-61.0163 561.6815,-52.0194 556.428,-43.8299"/>
<polygon fill="#000000" stroke="#000000" points="559.3677,-41.93 551.0667,-35.3464 553.4504,-45.6696 559.3677,-41.93"/>
<text text-anchor="middle" x="643.0682" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2186.5682" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2186.5682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2137.6818,-272.526C2051.555,-261.3971 1867.0699,-238.7969 1710.5682,-228 1581.9231,-219.1249 1257.454,-232.9861 1130.5682,-210 1126.86,-209.3282 1123.059,-208.4469 1119.2784,-207.4349"/>
<polygon fill="#000000" stroke="#000000" points="1119.9788,-203.9921 1109.3964,-204.5053 1117.9891,-210.7034 1119.9788,-203.9921"/>
<text text-anchor="middle" x="1923.0682" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2186.3498,-260.6191C2185.1554,-237.8864 2179.9856,-199.1241 2159.5682,-174 2138.634,-148.2399 2124.635,-149.5763 2092.5682,-141 2003.9984,-117.312 1740.8006,-108.9414 1612.082,-106.2104"/>
<polygon fill="#000000" stroke="#000000" points="1611.9966,-102.7079 1601.9265,-106.0007 1611.8521,-109.7065 1611.9966,-102.7079"/>
<text text-anchor="middle" x="2219.0682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2238.2119,-276.4934C2325.6112,-271.0515 2496.7926,-254.8083 2533.5682,-210 2543.7189,-197.6322 2541.2144,-188.0548 2533.5682,-174 2391.9644,86.2884 1501.3296,-72.0796 1205.5682,-54 973.5408,-39.8164 695.7916,-25.7065 587.254,-20.3031"/>
<polygon fill="#000000" stroke="#000000" points="587.1435,-16.7934 576.982,-19.7926 586.7959,-23.7847 587.1435,-16.7934"/>
<text text-anchor="middle" x="2560.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="986.5682" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="986.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M932.8119,-93.3961C922.7647,-91.2513 912.3496,-89.0442 902.5682,-87 830.6435,-71.9685 812.7312,-67.8427 740.5682,-54 687.1794,-43.7586 625.6031,-32.8036 585.0374,-25.7043"/>
<polygon fill="#000000" stroke="#000000" points="585.3938,-22.2136 574.9407,-23.941 584.1894,-29.1092 585.3938,-22.2136"/>
<text text-anchor="middle" x="873.0682" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node17" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1224.5682" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1224.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1239.2729,-173.8918C1249.5831,-162.5107 1264.3758,-148.5916 1280.5682,-141 1312.9523,-125.8172 1403.5935,-115.686 1468.5075,-110.1399"/>
<polygon fill="#000000" stroke="#000000" points="1469.0182,-113.6095 1478.6921,-109.2891 1468.4354,-106.6338 1469.0182,-113.6095"/>
<text text-anchor="middle" x="1348.5682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1559.5682" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1559.5682" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1495.6714,-356.0587C1463.3911,-350.1379 1423.8924,-341.5085 1389.5682,-330 1374.6758,-325.0068 1372.8408,-318.6695 1357.5682,-315 1240.6081,-286.8983 936.4754,-306.5737 816.5682,-297 780.9383,-294.1552 740.519,-288.8248 711.9401,-284.7"/>
<polygon fill="#000000" stroke="#000000" points="712.3791,-281.227 701.9776,-283.2417 711.3652,-288.1532 712.3791,-281.227"/>
<text text-anchor="middle" x="1450.5682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1612.676,-353.0627C1633.7558,-346.7588 1654.4532,-338.6714 1660.5682,-330 1677.0286,-306.6582 1658.9159,-279.1596 1632.5682,-261 1540.2433,-197.3668 1240.3395,-232.8768 1130.5682,-210 1126.98,-209.2522 1123.2986,-208.334 1119.6293,-207.3118"/>
<polygon fill="#000000" stroke="#000000" points="1120.6022,-203.9496 1110.0173,-204.409 1118.5784,-210.6507 1120.6022,-203.9496"/>
<text text-anchor="middle" x="1724.5682" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1549.0957,-347.9821C1541.3796,-336.4858 1529.7775,-322.4001 1515.5682,-315 1490.0872,-301.7295 1314.7114,-288.7359 1220.7426,-282.6241"/>
<polygon fill="#000000" stroke="#000000" points="1220.7345,-279.1165 1210.5301,-281.9662 1220.2844,-286.102 1220.7345,-279.1165"/>
<text text-anchor="middle" x="1595.5682" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node19" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="682.5682" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="682.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M685.7811,-173.7691C688.8222,-162.3362 694.6297,-148.4055 705.5682,-141 709.4964,-138.3406 1265.4436,-115.9279 1467.3541,-107.8705"/>
<polygon fill="#000000" stroke="#000000" points="1467.7075,-111.3593 1477.5601,-107.4635 1467.4285,-104.3649 1467.7075,-111.3593"/>
<text text-anchor="middle" x="835.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M683.4371,-173.6906C684.3119,-163.8075 686.0638,-151.5134 689.5682,-141 692.4623,-132.318 696.2446,-131.5268 699.5682,-123 708.5334,-99.9998 709.6591,-93.5137 712.5682,-69 713.3539,-62.3798 716.7718,-59.1744 712.5682,-54 696.9974,-34.8328 632.3361,-25.5109 586.899,-21.2475"/>
<polygon fill="#000000" stroke="#000000" points="586.9331,-17.7369 576.6633,-20.341 586.3155,-24.7096 586.9331,-17.7369"/>
<text text-anchor="middle" x="796.5682" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1479.6975,-99.786C1297.0172,-83.8769 749.3208,-36.1796 586.6267,-22.0111"/>
<polygon fill="#000000" stroke="#000000" points="586.7411,-18.5079 576.4751,-21.127 586.1337,-25.4815 586.7411,-18.5079"/>
<text text-anchor="middle" x="1151.0682" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1382.5682" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1382.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1398.9995,-174.5333C1409.9448,-163.7048 1425.1115,-150.1609 1440.5682,-141 1454.1195,-132.9685 1469.759,-126.2662 1484.5475,-120.9078"/>
<polygon fill="#000000" stroke="#000000" points="1485.8176,-124.1718 1494.1123,-117.5802 1483.5175,-117.5605 1485.8176,-124.1718"/>
<text text-anchor="middle" x="1485.0682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node23" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1528.5682" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1528.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1530.8475,-173.9735C1532.3371,-162.1918 1534.3135,-146.5607 1536.008,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1539.5098,-133.3634 1537.292,-123.0034 1532.5651,-132.4853 1539.5098,-133.3634"/>
<text text-anchor="middle" x="1594.5682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node24" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1737.5682" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1737.5682" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1713.6895,-174.3431C1698.2797,-163.576 1677.4639,-150.1686 1657.5682,-141 1638.5978,-132.2578 1616.9564,-124.9519 1597.4321,-119.2566"/>
<polygon fill="#000000" stroke="#000000" points="1598.3161,-115.8693 1587.7406,-116.5087 1596.4066,-122.6038 1598.3161,-115.8693"/>
<text text-anchor="middle" x="1777.5682" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
