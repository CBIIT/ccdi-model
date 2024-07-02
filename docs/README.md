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
<svg width="2678pt" height="305pt"
 viewBox="0.00 0.00 2677.84 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2673.8379,-301 2673.8379,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="195.0433" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="195.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node25" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="840.0433" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="840.0433" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M217.9409,-87.7522C234.944,-75.9727 259.2202,-61.2362 283.0433,-54 331.2358,-39.3616 668.5233,-24.7558 793.5548,-19.7845"/>
<polygon fill="#000000" stroke="#000000" points="793.7312,-23.2803 803.5852,-19.3882 793.4548,-16.2858 793.7312,-23.2803"/>
<text text-anchor="middle" x="339.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="700.0433" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="700.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="617.0433" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="617.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M683.6892,-260.8957C674.7333,-251.0727 663.3831,-238.7705 653.0433,-228 649.3131,-224.1145 645.319,-220.039 641.3979,-216.0841"/>
<polygon fill="#000000" stroke="#000000" points="643.578,-213.3138 634.0362,-208.7089 638.6237,-218.2591 643.578,-213.3138"/>
<text text-anchor="middle" x="733.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="361.0433" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="361.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M377.4347,-87.3655C389.4094,-75.7258 406.7013,-61.3193 425.0433,-54 490.918,-27.7131 699.4768,-20.574 793.3983,-18.6727"/>
<polygon fill="#000000" stroke="#000000" points="793.5328,-22.1708 803.464,-18.4802 793.3989,-15.1721 793.5328,-22.1708"/>
<text text-anchor="middle" x="487.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2201.0433" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2201.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1340.0433" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1340.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2155.2313,-175.7196C2119.046,-163.6877 2066.9965,-148.1971 2020.0433,-141 1752.3845,-99.9729 1679.2195,-160.4963 1411.0433,-123 1405.6122,-122.2406 1399.9961,-121.2263 1394.4114,-120.0645"/>
<polygon fill="#000000" stroke="#000000" points="1394.9622,-116.6013 1384.4397,-117.837 1393.4362,-123.433 1394.9622,-116.6013"/>
<text text-anchor="middle" x="2168.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_personnel -->
<g id="node5" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="543.0433" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="543.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M546.1796,-86.8479C549.1053,-75.5992 554.6552,-61.8456 565.0433,-54 582.8965,-40.5162 719.7775,-27.6358 793.4445,-21.5899"/>
<polygon fill="#000000" stroke="#000000" points="794.1484,-25.0444 803.833,-20.7482 793.583,-18.0673 794.1484,-25.0444"/>
<text text-anchor="middle" x="634.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="790.0433" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="790.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M837.7128,-175.7332C852.5227,-170.1031 868.7143,-163.344 883.0433,-156 893.9039,-150.4336 894.499,-144.9584 906.0433,-141 939.3663,-129.5737 1154.1995,-115.7039 1268.5921,-109.0046"/>
<polygon fill="#000000" stroke="#000000" points="1268.8878,-112.4934 1278.6674,-108.4179 1268.4808,-105.5053 1268.8878,-112.4934"/>
<text text-anchor="middle" x="992.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M837.2438,-175.7108C845.5331,-170.692 853.0824,-164.2395 858.0433,-156 881.4265,-117.1627 868.4587,-98.1206 858.0433,-54 857.2887,-50.8036 856.2045,-47.5675 854.9371,-44.4139"/>
<polygon fill="#000000" stroke="#000000" points="858.1069,-42.9298 850.7319,-35.3233 851.7538,-45.8687 858.1069,-42.9298"/>
<text text-anchor="middle" x="958.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line -->
<g id="node7" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="697.0433" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="697.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M660.461,-117.311C653.4072,-119.4118 646.0367,-121.4217 639.0433,-123 611.6675,-129.1784 532.4192,-119.7884 514.0433,-141 495.0762,-162.894 530.742,-176.3571 565.1785,-183.9107"/>
<polygon fill="#000000" stroke="#000000" points="564.7884,-187.4033 575.2868,-185.9773 566.1905,-180.5452 564.7884,-187.4033"/>
<text text-anchor="middle" x="554.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M700.443,-86.6513C703.3648,-75.7573 708.6547,-62.4624 718.0433,-54 729.7227,-43.4727 766.1583,-33.5179 796.1945,-26.7561"/>
<polygon fill="#000000" stroke="#000000" points="797.0705,-30.1473 806.0903,-24.5892 795.5731,-23.3094 797.0705,-30.1473"/>
<text text-anchor="middle" x="758.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1286.5345,-95.6895C1187.3202,-78.4262 976.5701,-41.7557 884.5669,-25.7471"/>
<polygon fill="#000000" stroke="#000000" points="884.9239,-22.2567 874.4719,-23.9906 883.7238,-29.1531 884.9239,-22.2567"/>
<text text-anchor="middle" x="1170.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node9" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="76.0433" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="76.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M102.1604,-261.9082C121.4619,-250.2042 148.8325,-235.494 175.0433,-228 246.4306,-207.5895 461.1472,-197.4993 562.6957,-193.7641"/>
<polygon fill="#000000" stroke="#000000" points="562.8801,-197.2599 572.7474,-193.4016 562.6277,-190.2644 562.8801,-197.2599"/>
<text text-anchor="middle" x="236.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node10" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2409.0433" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2409.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2370.9384,-175.8338C2340.2612,-163.6931 2295.7049,-148.0034 2255.0433,-141 2070.1672,-109.1577 1596.9394,-148.213 1411.0433,-123 1405.5303,-122.2523 1399.8281,-121.2344 1394.1622,-120.0606"/>
<polygon fill="#000000" stroke="#000000" points="1394.5739,-116.5664 1384.0516,-117.8039 1393.049,-123.3983 1394.5739,-116.5664"/>
<text text-anchor="middle" x="2379.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="286.0433" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="286.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M291.579,-260.9389C296.0403,-249.5777 303.5036,-235.6631 315.0433,-228 335.238,-214.5892 481.8718,-201.8932 563.1462,-195.7879"/>
<polygon fill="#000000" stroke="#000000" points="563.4876,-199.2722 573.2008,-195.0411 562.9691,-192.2915 563.4876,-199.2722"/>
<text text-anchor="middle" x="406.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1775.0433" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1775.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1776.2045,-260.8684C1777.0404,-230.2475 1773.6229,-168.9025 1736.0433,-141 1707.0057,-119.44 1446.7938,-128.4693 1411.0433,-123 1405.6224,-122.1707 1400.0131,-121.11 1394.4326,-119.9194"/>
<polygon fill="#000000" stroke="#000000" points="1394.9926,-116.4575 1384.4659,-117.6579 1393.4436,-123.284 1394.9926,-116.4575"/>
<text text-anchor="middle" x="1814.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1723.589,-275.9586C1509.3725,-263.2745 698.2036,-215.0144 672.0433,-210 667.936,-209.2127 663.7103,-208.2056 659.5132,-207.0709"/>
<polygon fill="#000000" stroke="#000000" points="660.4222,-203.6901 649.8414,-204.2352 658.4528,-210.4074 660.4222,-203.6901"/>
<text text-anchor="middle" x="1212.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1827.0281,-278.0218C1986.0058,-274.4979 2457.6582,-259.8901 2503.0433,-210 2513.81,-198.1646 2510.7513,-188.0209 2503.0433,-174 2466.6338,-107.7717 2367.8967,-122.7258 1428.0433,-54 1226.5786,-39.2681 985.9768,-25.8392 886.5502,-20.4719"/>
<polygon fill="#000000" stroke="#000000" points="886.7064,-16.9754 876.5327,-19.9327 886.3301,-23.9652 886.7064,-16.9754"/>
<text text-anchor="middle" x="2530.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- molecular_test -->
<g id="node13" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1122.0433" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1122.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1127.1399,-173.9673C1131.2425,-162.7676 1138.1555,-149.0237 1149.0433,-141 1168.1502,-126.9192 1223.9349,-117.4427 1270.3171,-111.7623"/>
<polygon fill="#000000" stroke="#000000" points="1270.8382,-115.2251 1280.357,-110.5728 1270.0146,-108.2737 1270.8382,-115.2251"/>
<text text-anchor="middle" x="1213.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1483.0433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1483.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge32" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1436.2893,-92.8115C1427.9068,-90.7691 1419.2338,-88.7482 1411.0433,-87 1328.9351,-69.4748 1308.2436,-65.2511 1225.0433,-54 1103.3001,-37.5368 958.876,-26.2148 886.4086,-21.0964"/>
<polygon fill="#000000" stroke="#000000" points="886.4698,-17.5922 876.25,-20.3863 885.9816,-24.5752 886.4698,-17.5922"/>
<text text-anchor="middle" x="1373.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1278.0433" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1278.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1277.4061,-173.7474C1277.8604,-163.4132 1279.8604,-150.6632 1286.0433,-141 1289.5103,-135.5813 1294.1168,-130.789 1299.1821,-126.6132"/>
<polygon fill="#000000" stroke="#000000" points="1301.4367,-129.2998 1307.4215,-120.5572 1297.291,-123.6594 1301.4367,-129.2998"/>
<text text-anchor="middle" x="1333.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="792.0433" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="792.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M769.8056,-115.9925C764.9567,-118.3406 759.841,-120.7808 755.0433,-123 736.9809,-131.3546 731.548,-131.5325 714.0433,-141 703.3087,-146.8058 701.6623,-149.9855 691.0433,-156 679.9716,-162.2709 667.647,-168.5357 656.2814,-174.0397"/>
<polygon fill="#000000" stroke="#000000" points="654.5242,-171.0002 647.0084,-178.4676 657.5406,-177.317 654.5242,-171.0002"/>
<text text-anchor="middle" x="738.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M796.7302,-86.8586C799.7436,-76.7998 804.1955,-64.2844 810.0433,-54 812.3216,-49.9931 815.0609,-45.9965 817.9455,-42.2019"/>
<polygon fill="#000000" stroke="#000000" points="820.7822,-44.2608 824.3699,-34.2919 815.3486,-39.8476 820.7822,-44.2608"/>
<text text-anchor="middle" x="834.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- survival -->
<g id="node17" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1402.0433" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1402.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1396.4417,-174.0201C1392.7412,-163.7768 1387.2412,-151.0268 1380.0433,-141 1377.0552,-136.8375 1373.5115,-132.8063 1369.7875,-129.0411"/>
<polygon fill="#000000" stroke="#000000" points="1372.1768,-126.4834 1362.5025,-122.1638 1367.3715,-131.5736 1372.1768,-126.4834"/>
<text text-anchor="middle" x="1428.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_arm -->
<g id="node18" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2610.0433" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2610.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2591.6325,-87.717C2577.5895,-75.7549 2557.1273,-60.808 2536.0433,-54 2455.4929,-27.9906 1151.4965,-19.6615 886.7264,-18.2348"/>
<polygon fill="#000000" stroke="#000000" points="886.6951,-14.7347 876.6765,-18.1813 886.6577,-21.7346 886.6951,-14.7347"/>
<text text-anchor="middle" x="2612.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M572.6208,-190.3747C520.095,-187.41 437.344,-179.1056 418.0433,-156 413.7693,-150.8835 413.5246,-145.9017 418.0433,-141 434.7421,-122.8858 614.8548,-127.6794 639.0433,-123 643.1191,-122.2115 647.3132,-121.2397 651.4929,-120.1597"/>
<polygon fill="#000000" stroke="#000000" points="652.4563,-123.5247 661.1565,-117.4786 650.5848,-116.7795 652.4563,-123.5247"/>
<text text-anchor="middle" x="454.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M650.889,-180.2246C657.841,-178.0035 665.1439,-175.8121 672.0433,-174 711.4973,-163.6377 722.6535,-166.6041 762.0433,-156 781.9937,-150.6292 785.786,-145.0628 806.0433,-141 828.3189,-136.5324 1128.3142,-117.8745 1268.6231,-109.3196"/>
<polygon fill="#000000" stroke="#000000" points="1269.0812,-112.7983 1278.8499,-108.6967 1268.6556,-105.8113 1269.0812,-112.7983"/>
<text text-anchor="middle" x="842.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M612.0336,-173.8268C610.2265,-162.9989 610.2487,-149.7118 618.0433,-141 638.5175,-118.1162 725.6344,-131.8307 755.0433,-123 756.9931,-122.4145 758.9674,-121.7363 760.9365,-120.9932"/>
<polygon fill="#000000" stroke="#000000" points="762.7791,-124.0123 770.6019,-116.867 760.0307,-117.5744 762.7791,-124.0123"/>
<text text-anchor="middle" x="654.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1521.0433" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1521.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1508.302,-174.5074C1499.3335,-163.3863 1486.4018,-149.5256 1472.0433,-141 1468.5345,-138.9166 1430.7496,-128.6947 1396.5022,-119.673"/>
<polygon fill="#000000" stroke="#000000" points="1397.0612,-116.2011 1386.5,-117.0454 1395.2825,-122.9714 1397.0612,-116.2011"/>
<text text-anchor="middle" x="1534.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="896.0433" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="896.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M909.8175,-261.3128C913.7975,-255.669 917.908,-249.2592 921.0433,-243 935.5205,-214.0976 919.1388,-194.6085 944.0433,-174 967.1909,-154.8453 1048.5963,-161.9658 1078.0433,-156 1102.876,-150.969 1108.3124,-146.5101 1133.0433,-141 1179.9792,-130.5426 1233.4672,-121.3089 1274.3129,-114.8118"/>
<polygon fill="#000000" stroke="#000000" points="1275.0802,-118.2341 1284.4133,-113.2198 1273.9903,-111.3195 1275.0802,-118.2341"/>
<text text-anchor="middle" x="988.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M868.1586,-263.3823C841.7256,-248.6018 805.7871,-228.5795 804.0433,-228 747.8553,-209.3268 729.7484,-223.2624 672.0433,-210 668.1342,-209.1016 664.1069,-208.0456 660.0931,-206.9031"/>
<polygon fill="#000000" stroke="#000000" points="660.8039,-203.4619 650.2192,-203.9253 658.7827,-210.1637 660.8039,-203.4619"/>
<text text-anchor="middle" x="874.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1666.0433" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1666.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1643.8732,-174.7769C1627.6762,-163.1699 1604.6759,-148.6327 1582.0433,-141 1509.6304,-116.5792 1486.2748,-136.4245 1411.0433,-123 1405.9321,-122.088 1400.6454,-121.009 1395.3691,-119.8396"/>
<polygon fill="#000000" stroke="#000000" points="1395.8164,-116.3504 1385.2841,-117.4992 1394.234,-123.1692 1395.8164,-116.3504"/>
<text text-anchor="middle" x="1673.0433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="509.0433" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="509.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M502.6512,-260.8755C500.1429,-250.3322 499.2634,-237.3264 506.0433,-228 513.675,-217.5018 541.4739,-208.4941 567.3404,-202.1148"/>
<polygon fill="#000000" stroke="#000000" points="568.1888,-205.5108 577.1133,-199.801 566.576,-198.6991 568.1888,-205.5108"/>
<text text-anchor="middle" x="577.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1978.0433" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1978.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1930.4976,-176.102C1892.6437,-164.1953 1838.0637,-148.6884 1789.0433,-141 1622.8841,-114.9395 1577.3965,-147.7908 1411.0433,-123 1405.6192,-122.1917 1400.0078,-121.1449 1394.4261,-119.9629"/>
<polygon fill="#000000" stroke="#000000" points="1394.9832,-116.5007 1384.4578,-117.7117 1393.4411,-123.3287 1394.9832,-116.5007"/>
<text text-anchor="middle" x="1936.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
