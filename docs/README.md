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
<svg width="2418pt" height="392pt"
 viewBox="0.00 0.00 2418.48 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2414.4805,-388 2414.4805,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="465.4805" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="465.4805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="612.4805" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="612.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M473.5259,-261.1373C479.3093,-250.1508 488.0909,-236.5797 499.4805,-228 500.9598,-226.8856 536.4918,-215.6457 567.32,-206.0176"/>
<polygon fill="#000000" stroke="#000000" points="568.6102,-209.2816 577.1147,-202.9632 566.5262,-202.599 568.6102,-209.2816"/>
<text text-anchor="middle" x="541.9805" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="898.4805" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="898.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M461.0493,-260.8162C456.5657,-237.5631 453.0061,-197.5016 474.4805,-174 498.0732,-148.18 714.7558,-123.1507 828.8804,-111.6173"/>
<polygon fill="#000000" stroke="#000000" points="829.3242,-115.0904 838.9252,-110.6103 828.6259,-108.1253 829.3242,-115.0904"/>
<text text-anchor="middle" x="516.9805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1459.4805" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1459.4805" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M414.683,-275.0632C300.7923,-265.7224 32.8995,-240.6873 6.4805,-210 -3.9585,-197.8745 .3575,-188.7821 6.4805,-174 87.4893,21.5727 740.5216,-71.5345 951.4805,-54 1121.4162,-39.8753 1323.6284,-26.6003 1413.0337,-20.9116"/>
<polygon fill="#000000" stroke="#000000" points="1413.3557,-24.3983 1423.1139,-20.272 1412.9123,-17.4123 1413.3557,-24.3983"/>
<text text-anchor="middle" x="70.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="757.4805" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="757.4805" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M699.6408,-354.2415C668.0694,-344.5553 631.6104,-327.2886 612.4805,-297 598.0265,-274.1148 600.3396,-242.4532 604.832,-219.8951"/>
<polygon fill="#000000" stroke="#000000" points="608.2929,-220.4577 607.0725,-209.9334 601.4634,-218.9217 608.2929,-220.4577"/>
<text text-anchor="middle" x="673.4805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1062.4805" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1062.4805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M769.5284,-347.8503C778.1309,-336.4518 790.7576,-322.5288 805.4805,-315 860.5508,-286.839 882.232,-305.6258 943.4805,-297 970.876,-293.1418 1001.7665,-288.4595 1025.208,-284.8376"/>
<polygon fill="#000000" stroke="#000000" points="1025.7443,-288.2964 1035.09,-283.3055 1024.6718,-281.379 1025.7443,-288.2964"/>
<text text-anchor="middle" x="866.4805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node23" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1839.4805" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1839.4805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge18" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M811.209,-353.2071C821.5357,-351.1507 832.3034,-349.2805 842.4805,-348 937.8121,-336.0054 1184.3872,-363.3946 1274.4805,-330 1284.5686,-326.2607 1283.3841,-318.7172 1293.4805,-315 1394.2741,-277.8908 1670.4067,-313.876 1776.4805,-297 1781.8868,-296.1399 1787.4868,-294.967 1793.0167,-293.6294"/>
<polygon fill="#000000" stroke="#000000" points="1794.0404,-296.9797 1802.8378,-291.0758 1792.2788,-290.205 1794.0404,-296.9797"/>
<text text-anchor="middle" x="1354.4805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M632.6469,-175.944C648.134,-164.4379 670.523,-149.5234 692.4805,-141 735.6941,-124.2254 787.0449,-115.2284 827.6665,-110.4236"/>
<polygon fill="#000000" stroke="#000000" points="828.2049,-113.8852 837.7514,-109.2901 827.423,-106.929 828.2049,-113.8852"/>
<text text-anchor="middle" x="728.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- follow_up -->
<g id="node4" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="729.4805" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="729.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M746.9125,-174.7069C758.6848,-163.8107 775.0266,-150.1272 791.4805,-141 807.0256,-132.3769 824.9868,-125.3451 841.7007,-119.8595"/>
<polygon fill="#000000" stroke="#000000" points="842.8868,-123.1554 851.3697,-116.808 840.78,-116.48 842.8868,-123.1554"/>
<text text-anchor="middle" x="836.4805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node5" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2068.4805" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2068.4805" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2172.5051,-354.1489C2221.5878,-347.4869 2271.0888,-338.7666 2278.4805,-330 2282.7778,-324.9032 2282.8513,-320.034 2278.4805,-315 2264.4645,-298.8575 1918.7678,-262.9691 1897.4805,-261 1563.0323,-230.0635 1478.0783,-241.6662 1142.4805,-228 1036.4929,-223.684 769.7932,-229.2576 665.4805,-210 661.8253,-209.3252 658.0791,-208.4502 654.3509,-207.4499"/>
<polygon fill="#000000" stroke="#000000" points="655.1806,-204.0454 644.5983,-204.5608 653.1923,-210.7571 655.1806,-204.0454"/>
<text text-anchor="middle" x="2301.9805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1958.0747,-355.2135C1905.6712,-348.9742 1849.3635,-340.3146 1825.4805,-330 1815.6034,-325.7343 1816.556,-318.7731 1806.4805,-315 1773.2145,-302.5424 1248.8411,-284.9453 1101.007,-280.2117"/>
<polygon fill="#000000" stroke="#000000" points="1100.7358,-276.7013 1090.6293,-279.8807 1100.5127,-283.6978 1100.7358,-276.7013"/>
<text text-anchor="middle" x="1933.9805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2065.2321,-347.993C2062.2604,-336.8039 2056.7014,-323.0621 2046.4805,-315 2024.0142,-297.279 1951.3395,-287.7576 1898.4343,-283.0413"/>
<polygon fill="#000000" stroke="#000000" points="1898.7325,-279.5541 1888.4704,-282.1883 1898.1354,-286.5286 1898.7325,-279.5541"/>
<text text-anchor="middle" x="2165.9805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="876.4805" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="876.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M881.0389,-173.9735C884.0477,-162.0751 888.0492,-146.2508 891.4605,-132.7606"/>
<polygon fill="#000000" stroke="#000000" points="894.8694,-133.5563 893.9279,-123.0034 888.0831,-131.8401 894.8694,-133.5563"/>
<text text-anchor="middle" x="947.4805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1038.4805" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1038.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1062.2603,-88.3376C1080.162,-76.684 1105.7652,-61.8511 1130.4805,-54 1181.9726,-37.6428 1335.3517,-25.8908 1413.1394,-20.8048"/>
<polygon fill="#000000" stroke="#000000" points="1413.3895,-24.2961 1423.1437,-20.1603 1412.9394,-17.3106 1413.3895,-24.2961"/>
<text text-anchor="middle" x="1178.9805" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1203.4805" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1203.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1215.968,-87.0562C1224.8294,-75.7446 1237.737,-61.8412 1252.4805,-54 1279.7293,-39.508 1361.4002,-28.4451 1413.64,-22.61"/>
<polygon fill="#000000" stroke="#000000" points="1414.1104,-26.0795 1423.6707,-21.5132 1413.3495,-19.121 1414.1104,-26.0795"/>
<text text-anchor="middle" x="1321.9805" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1068.4805" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1068.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1051.6744,-173.8431C1040.8135,-163.0213 1025.8742,-149.735 1010.4805,-141 1000.222,-135.1789 976.4219,-127.2825 953.3875,-120.3682"/>
<polygon fill="#000000" stroke="#000000" points="954.1864,-116.9547 943.6043,-117.474 952.2006,-123.6671 954.1864,-116.9547"/>
<text text-anchor="middle" x="1109.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1241.4805" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1241.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1230.1124,-174.3659C1221.556,-162.7265 1208.714,-148.32 1193.4805,-141 1148.469,-119.3713 1018.7467,-131.1649 969.4805,-123 964.1487,-122.1164 958.6305,-121.03 953.1345,-119.8326"/>
<polygon fill="#000000" stroke="#000000" points="953.8408,-116.4038 943.3111,-117.5772 952.2743,-123.2263 953.8408,-116.4038"/>
<text text-anchor="middle" x="1257.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node11" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1367.4805" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1367.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1352.5759,-174.6857C1341.258,-162.874 1324.5926,-148.1264 1306.4805,-141 1236.6925,-113.5413 1043.6247,-134.2684 969.4805,-123 964.0588,-122.176 958.4489,-121.1188 952.8682,-119.9304"/>
<polygon fill="#000000" stroke="#000000" points="953.4274,-116.4685 942.9011,-117.6716 951.8801,-123.2954 953.4274,-116.4685"/>
<text text-anchor="middle" x="1373.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1639.4805" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1639.4805" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1639.3223,-347.7642C1638.1993,-336.629 1634.8004,-323.0322 1625.4805,-315 1502.8975,-209.3545 1063.5332,-243.7981 902.4805,-228 797.3484,-217.6873 768.9777,-231.1526 665.4805,-210 661.8388,-209.2557 658.1021,-208.332 654.3802,-207.2991"/>
<polygon fill="#000000" stroke="#000000" points="655.2225,-203.8974 644.6377,-204.3581 653.1995,-210.5988 655.2225,-203.8974"/>
<text text-anchor="middle" x="1662.9805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1556.1905,-365.0058C1434.8913,-362.7065 1215.9759,-355.1038 1141.4805,-330 1129.9154,-326.1028 1128.7245,-321.6331 1118.4805,-315 1109.5307,-309.205 1099.7593,-302.9117 1090.9205,-297.2318"/>
<polygon fill="#000000" stroke="#000000" points="1092.7634,-294.2557 1082.4576,-291.7975 1088.981,-300.1459 1092.7634,-294.2557"/>
<text text-anchor="middle" x="1207.9805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1647.0227,-347.8493C1652.6504,-336.6011 1661.4475,-322.8476 1673.4805,-315 1712.4055,-289.6141 1731.1871,-307.3978 1776.4805,-297 1781.4124,-295.8678 1786.5325,-294.5856 1791.6266,-293.2397"/>
<polygon fill="#000000" stroke="#000000" points="1792.6057,-296.6006 1801.3344,-290.5955 1790.7661,-289.8466 1792.6057,-296.6006"/>
<text text-anchor="middle" x="1739.9805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node13" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1378.4805" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1378.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1385.9556,-86.6731C1390.7806,-76.3141 1397.7806,-63.5641 1406.4805,-54 1412.1116,-47.8094 1419.0104,-42.1483 1425.9455,-37.24"/>
<polygon fill="#000000" stroke="#000000" points="1428.271,-39.8966 1434.6566,-31.4423 1424.3926,-34.0692 1428.271,-39.8966"/>
<text text-anchor="middle" x="1462.9805" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M922.1866,-88.099C940.0517,-76.3267 965.6413,-61.45 990.4805,-54 1068.6562,-30.5528 1310.6789,-21.7734 1413.0247,-19.0511"/>
<polygon fill="#000000" stroke="#000000" points="1413.1566,-22.549 1423.0629,-18.7917 1412.9757,-15.5513 1413.1566,-22.549"/>
<text text-anchor="middle" x="1040.9805" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node15" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1544.4805" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1544.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1538.5763,-86.9579C1534.4645,-76.4438 1528.1532,-63.4398 1519.4805,-54 1512.7097,-46.6304 1504.0831,-40.2758 1495.4962,-35.0462"/>
<polygon fill="#000000" stroke="#000000" points="1497.0642,-31.9115 1486.6417,-30.0082 1493.6025,-37.9956 1497.0642,-31.9115"/>
<text text-anchor="middle" x="1590.4805" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node16" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1523.4805" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1523.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1497.0124,-174.8327C1477.1135,-162.9282 1448.7083,-148.0025 1421.4805,-141 1324.1245,-115.962 1068.9634,-137.4301 969.4805,-123 964.0533,-122.2128 958.4399,-121.18 952.8568,-120.0067"/>
<polygon fill="#000000" stroke="#000000" points="953.4112,-116.5441 942.8871,-117.7658 951.8761,-123.3737 953.4112,-116.5441"/>
<text text-anchor="middle" x="1527.4805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- publication -->
<g id="node18" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1702.4805" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1702.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1690.9692,-87.0948C1682.7397,-75.7995 1670.6424,-61.8997 1656.4805,-54 1631.1807,-39.8875 1555.3401,-28.8933 1505.4799,-22.9379"/>
<polygon fill="#000000" stroke="#000000" points="1505.6008,-19.4283 1495.2622,-21.7442 1504.7885,-26.381 1505.6008,-19.4283"/>
<text text-anchor="middle" x="1726.4805" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- molecular_test -->
<g id="node19" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="95.4805" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="95.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M109.3013,-174.1699C119.5398,-162.4405 134.5987,-148.0071 151.4805,-141 212.5834,-115.6381 649.8839,-107.8412 825.6304,-105.7163"/>
<polygon fill="#000000" stroke="#000000" points="825.8589,-109.2139 835.8168,-105.5959 825.7761,-102.2144 825.8589,-109.2139"/>
<text text-anchor="middle" x="215.4805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1035.513,-274.2608C984.0124,-265.2168 868.0939,-244.8913 770.4805,-228 723.8264,-219.9269 711.3724,-221.6492 665.4805,-210 662.0808,-209.137 658.5863,-208.1596 655.0912,-207.1171"/>
<polygon fill="#000000" stroke="#000000" points="655.9072,-203.7049 645.3179,-204.0481 653.8099,-210.3834 655.9072,-203.7049"/>
<text text-anchor="middle" x="874.4805" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1090.4722,-277.7953C1239.6914,-271.258 1936.0865,-239.2587 1970.4805,-210 1981.0407,-201.0165 2000.406,-97.6093 1991.4805,-87 1960.3846,-50.0377 1630.3263,-27.6696 1506.2638,-20.5153"/>
<polygon fill="#000000" stroke="#000000" points="1506.1364,-17.0024 1495.9536,-19.9285 1505.7386,-23.9911 1506.1364,-17.0024"/>
<text text-anchor="middle" x="2013.4805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node21" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="967.4805" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="967.4805" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M885.9956,-353.174C840.2758,-345.4581 790.599,-336.0004 781.4805,-330 750.4843,-309.6033 761.7868,-286.1228 734.4805,-261 710.5828,-239.0133 678.4474,-221.1991 653.1569,-209.1821"/>
<polygon fill="#000000" stroke="#000000" points="654.3758,-205.8895 643.8307,-204.8636 651.4345,-212.2415 654.3758,-205.8895"/>
<text text-anchor="middle" x="846.9805" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M944.9613,-348.0304C935.1662,-338.0252 927.5383,-325.5064 935.4805,-315 946.3452,-300.6275 991.7729,-290.3295 1025.2081,-284.5228"/>
<polygon fill="#000000" stroke="#000000" points="1025.8599,-287.9625 1035.148,-282.8654 1024.7085,-281.0579 1025.8599,-287.9625"/>
<text text-anchor="middle" x="1026.9805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1076.5708,-359.9083C1188.8671,-353.1719 1356.1013,-341.7142 1419.4805,-330 1442.7137,-325.7059 1447.204,-319.0532 1470.4805,-315 1604.6959,-291.6288 1642.1754,-319.8509 1776.4805,-297 1781.8071,-296.0937 1787.326,-294.904 1792.7825,-293.5674"/>
<polygon fill="#000000" stroke="#000000" points="1793.6918,-296.9473 1802.4816,-291.032 1791.9214,-290.1749 1793.6918,-296.9473"/>
<text text-anchor="middle" x="1561.9805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1852.4805" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1852.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1769.999,-180.2609C1725.7853,-173.3098 1676.2308,-164.2717 1655.4805,-156 1644.144,-151.4809 1644.1303,-144.6359 1632.4805,-141 1562.1332,-119.0445 1042.4765,-133.1168 969.4805,-123 963.9697,-122.2362 958.2689,-121.2078 952.6039,-120.0275"/>
<polygon fill="#000000" stroke="#000000" points="953.0176,-116.5335 942.4944,-117.7633 951.4877,-123.3643 953.0176,-116.5335"/>
<text text-anchor="middle" x="1784.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1894.996,-175.2456C1911.9757,-166.0915 1925.2384,-153.9877 1914.4805,-141 1887.0676,-107.9054 1854.2718,-148.2246 1819.4805,-123 1791.1366,-102.45 1810.5838,-73.4596 1781.4805,-54 1759.0641,-39.0115 1589.5711,-26.279 1505.9084,-20.8321"/>
<polygon fill="#000000" stroke="#000000" points="1506.1087,-17.3379 1495.9048,-20.1889 1505.6596,-24.3234 1506.1087,-17.3379"/>
<text text-anchor="middle" x="1905.4805" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1801.089,-267.4864C1754.0216,-252.9078 1677.5361,-227.5758 1653.4805,-210 1622.0374,-187.0266 1634.2407,-158.5547 1599.4805,-141 1536.9711,-109.4314 1038.8392,-132.6629 969.4805,-123 964.049,-122.2433 958.4326,-121.2307 952.8478,-120.07"/>
<polygon fill="#000000" stroke="#000000" points="953.3983,-116.6068 942.876,-117.8439 951.8732,-123.4387 953.3983,-116.6068"/>
<text text-anchor="middle" x="1693.9805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1875.7534,-266.5772C1917.6333,-251.7514 1983.3478,-226.8541 2003.4805,-210 2056.9228,-165.2607 2072.3365,-99.4303 2019.4805,-54 2000.1256,-37.3643 1637.1551,-23.8395 1506.1424,-19.4811"/>
<polygon fill="#000000" stroke="#000000" points="1506.1301,-15.9789 1496.0202,-19.1473 1505.8994,-22.9751 1506.1301,-15.9789"/>
<text text-anchor="middle" x="2089.9805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- therapeutic_procedure -->
<g id="node24" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="311.4805" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="311.4805" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M293.9553,-173.7748C285.8854,-163.1957 279.819,-150.1877 288.4805,-141 306.6608,-121.7151 668.2541,-110.5997 825.9673,-106.6521"/>
<polygon fill="#000000" stroke="#000000" points="826.1447,-110.1489 836.055,-106.4025 825.9714,-103.1511 826.1447,-110.1489"/>
<text text-anchor="middle" x="381.4805" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
</g>
</svg>
</div>
