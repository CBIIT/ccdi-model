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
<svg width="2843pt" height="305pt"
 viewBox="0.00 0.00 2842.74 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2838.7422,-301 2838.7422,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1060.7947" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1060.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="608.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="608.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1033.4921,-88.6146C1012.6746,-76.9404 982.8925,-61.9598 954.7947,-54 899.7405,-38.4037 736.615,-26.1718 655.572,-20.8689"/>
<polygon fill="#000000" stroke="#000000" points="655.3745,-17.3489 645.1696,-20.1968 654.9231,-24.3344 655.3745,-17.3489"/>
<text text-anchor="middle" x="1045.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5886,-86.6452C52.7075,-75.7489 52.7211,-62.4538 60.7947,-54 78.0053,-35.979 432.6613,-23.3805 562.0658,-19.3682"/>
<polygon fill="#000000" stroke="#000000" points="562.1844,-22.8663 572.0723,-19.0612 561.9697,-15.8696 562.1844,-22.8663"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1788.7947" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1788.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1795.917,-260.8891C1800.9155,-247.1653 1807.1592,-227.711 1809.7947,-210 1814.5525,-178.0265 1815.243,-156.3503 1786.7947,-141 1754.8071,-123.74 1168.8049,-127.9369 1132.7947,-123 1127.0703,-122.2152 1121.142,-121.153 1115.257,-119.9347"/>
<polygon fill="#000000" stroke="#000000" points="1115.9579,-116.5052 1105.4375,-117.7584 1114.4432,-123.3394 1115.9579,-116.5052"/>
<text text-anchor="middle" x="1854.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2165.7947" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2165.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1819.651,-264.4431C1845.3644,-252.8918 1883.237,-237.205 1917.7947,-228 1983.4779,-210.5042 2061.3595,-200.955 2112.0855,-196.1694"/>
<polygon fill="#000000" stroke="#000000" points="2112.5304,-199.6434 2122.17,-195.2471 2111.8928,-192.6725 2112.5304,-199.6434"/>
<text text-anchor="middle" x="1960.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1736.7276,-278.7319C1467.7551,-277.1001 246.0019,-266.5844 190.7947,-210 106.9137,-124.0266 285.1633,-61.5429 303.7947,-54 349.5461,-35.4776 488.6505,-24.917 562.1481,-20.4901"/>
<polygon fill="#000000" stroke="#000000" points="562.7199,-23.9626 572.497,-19.8812 562.3087,-16.9747 562.7199,-23.9626"/>
<text text-anchor="middle" x="217.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2806.7947" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2806.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2794.6139,-262.4973C2784.7882,-250.5991 2769.8319,-235.3855 2752.7947,-228 2704.7483,-207.1722 2356.725,-196.6067 2220.3769,-193.2314"/>
<polygon fill="#000000" stroke="#000000" points="2220.2429,-189.7272 2210.1604,-192.9822 2220.0721,-196.7251 2220.2429,-189.7272"/>
<text text-anchor="middle" x="2797.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2126.235,-183.8251C2066.7622,-171.9384 1950.6367,-150.2908 1850.7947,-141 1532.9565,-111.4234 1449.1007,-165.9696 1132.7947,-123 1127.0693,-122.2222 1121.1404,-121.1646 1115.2551,-119.949"/>
<polygon fill="#000000" stroke="#000000" points="1115.9552,-116.5194 1105.4351,-117.7758 1114.4426,-123.354 1115.9552,-116.5194"/>
<text text-anchor="middle" x="2000.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="524.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="524.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge20" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M526.5823,-86.8336C528.4272,-76.2755 532.1763,-63.2688 539.7947,-54 547.4258,-44.7158 558.0836,-37.5373 568.7437,-32.1219"/>
<polygon fill="#000000" stroke="#000000" points="570.4395,-35.1935 578.0362,-27.8083 567.4921,-28.8442 570.4395,-35.1935"/>
<text text-anchor="middle" x="590.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- molecular_test -->
<g id="node7" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="515.7947" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="515.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M538.0793,-174.6466C554.6512,-162.8159 578.3601,-148.0618 601.7947,-141 678.2757,-117.9532 881.4361,-132.0939 960.7947,-123 973.4479,-121.55 986.918,-119.4862 999.7377,-117.2701"/>
<polygon fill="#000000" stroke="#000000" points="1000.62,-120.6681 1009.8515,-115.469 999.3927,-113.7766 1000.62,-120.6681"/>
<text text-anchor="middle" x="665.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- radiology_file -->
<g id="node8" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="686.7947" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="686.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M706.5596,-174.4005C720.8475,-162.7769 741.1877,-148.3752 761.7947,-141 845.4066,-111.0756 872.7871,-134.8775 960.7947,-123 973.2784,-121.3152 986.5786,-119.1697 999.2684,-116.9517"/>
<polygon fill="#000000" stroke="#000000" points="1000.0573,-120.3663 1009.2873,-115.1648 998.8281,-113.4751 1000.0573,-120.3663"/>
<text text-anchor="middle" x="820.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="878.7947" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="878.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M879.2657,-173.5532C880.5378,-162.6224 883.9847,-149.3231 892.7947,-141 896.7969,-137.2189 952.0786,-125.822 998.1504,-116.8532"/>
<polygon fill="#000000" stroke="#000000" points="998.9675,-120.26 1008.1193,-114.9221 997.6362,-113.3878 998.9675,-120.26"/>
<text text-anchor="middle" x="972.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="692.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="692.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M675.3898,-86.9735C662.8205,-73.9553 645.7134,-56.2373 631.9854,-42.0189"/>
<polygon fill="#000000" stroke="#000000" points="634.2205,-39.2949 624.7566,-34.532 629.1846,-44.1571 634.2205,-39.2949"/>
<text text-anchor="middle" x="726.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- follow_up -->
<g id="node11" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1051.7947" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1051.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1053.6595,-173.9735C1054.8783,-162.1918 1056.4953,-146.5607 1057.8818,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1061.3846,-133.3105 1058.9323,-123.0034 1054.4218,-132.5901 1061.3846,-133.3105"/>
<text text-anchor="middle" x="1102.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- pathology_file -->
<g id="node12" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1934.7947" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1934.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1965.4096,-262.3764C1986.0264,-251.6222 2014.0512,-237.8438 2039.7947,-228 2064.989,-218.3662 2093.8728,-209.9341 2117.6246,-203.657"/>
<polygon fill="#000000" stroke="#000000" points="2118.665,-207.003 2127.464,-201.1015 2116.9053,-200.2278 2118.665,-207.003"/>
<text text-anchor="middle" x="2100.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node14" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1242.7947" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1242.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1213.814,-174.4438C1196.1922,-164.102 1173.058,-151.1084 1151.7947,-141 1138.2054,-134.5398 1123.1276,-128.2409 1109.2176,-122.7648"/>
<polygon fill="#000000" stroke="#000000" points="1110.3957,-119.4678 1099.8068,-119.1133 1107.8635,-125.9937 1110.3957,-119.4678"/>
<text text-anchor="middle" x="1272.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node15" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2166.7947" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2166.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2166.5875,-260.9735C2166.4521,-249.1918 2166.2724,-233.5607 2166.1184,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="2169.6164,-219.9624 2166.0016,-210.0034 2162.6169,-220.043 2169.6164,-219.9624"/>
<text text-anchor="middle" x="2274.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sequencing_file -->
<g id="node16" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2405.7947" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2405.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2402.5693,-260.9638C2399.6071,-249.7626 2394.0499,-236.0184 2383.7947,-228 2358.9734,-208.5925 2276.2398,-199.2685 2220.1395,-195.0785"/>
<polygon fill="#000000" stroke="#000000" points="2220.2181,-191.5753 2209.9943,-194.3546 2219.7198,-198.5576 2220.2181,-191.5753"/>
<text text-anchor="middle" x="2461.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2622.7947" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2622.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2597.8134,-261.2573C2580.2188,-249.7263 2555.638,-235.4916 2531.7947,-228 2475.0909,-210.1836 2307.2789,-199.2406 2219.9625,-194.5969"/>
<polygon fill="#000000" stroke="#000000" points="2219.8951,-191.0887 2209.726,-194.0618 2219.5296,-198.0792 2219.8951,-191.0887"/>
<text text-anchor="middle" x="2657.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="874.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="874.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M854.1678,-87.524C839.8102,-76.263 819.7327,-62.2361 799.7947,-54 752.6999,-34.5458 694.7073,-25.5164 655.0598,-21.3823"/>
<polygon fill="#000000" stroke="#000000" points="655.1845,-17.8779 644.8912,-20.3873 654.5028,-24.8446 655.1845,-17.8779"/>
<text text-anchor="middle" x="888.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1431.7947" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1431.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1416.2938,-174.5568C1404.7454,-162.846 1387.9003,-148.2754 1369.7947,-141 1320.785,-121.3065 1184.9351,-131.4353 1132.7947,-123 1127.3095,-122.1126 1121.6291,-121.0134 1115.975,-119.7989"/>
<polygon fill="#000000" stroke="#000000" points="1116.4001,-116.3065 1105.8738,-117.5091 1114.8526,-123.1333 1116.4001,-116.3065"/>
<text text-anchor="middle" x="1437.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="308.7947" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="308.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M302.1008,-173.5958C299.4252,-162.681 298.6386,-149.3837 306.7947,-141 332.14,-114.9476 924.6395,-126.7301 960.7947,-123 973.5327,-121.6858 987.0877,-119.6696 999.9719,-117.4551"/>
<polygon fill="#000000" stroke="#000000" points="1000.9009,-120.8448 1010.1327,-115.6462 999.674,-113.9532 1000.9009,-120.8448"/>
<text text-anchor="middle" x="436.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M295.3876,-174.037C280.2456,-151.385 260.228,-112.3433 280.7947,-87 315.739,-43.9398 480.4652,-26.7505 562.3516,-20.778"/>
<polygon fill="#000000" stroke="#000000" points="562.6575,-24.2653 572.3872,-20.0721 562.1662,-17.2825 562.6575,-24.2653"/>
<text text-anchor="middle" x="366.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- medical_history -->
<g id="node21" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1587.7947" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1587.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1560.5936,-174.6748C1540.4983,-162.8579 1512.017,-148.1085 1484.7947,-141 1333.2281,-101.4217 1287.7302,-146.1049 1132.7947,-123 1127.0799,-122.1478 1121.1579,-121.0418 1115.2767,-119.7971"/>
<polygon fill="#000000" stroke="#000000" points="1115.9854,-116.3691 1105.4613,-117.5918 1114.4508,-123.1989 1115.9854,-116.3691"/>
<text text-anchor="middle" x="1590.7947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1745.7947" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1745.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1725.4262,-175.2883C1709.4614,-163.2807 1686.1147,-148.0217 1662.7947,-141 1549.9532,-107.0234 1249.4962,-139.382 1132.7947,-123 1127.0728,-122.1968 1121.1462,-121.1226 1115.2622,-119.8971"/>
<polygon fill="#000000" stroke="#000000" points="1115.9652,-116.468 1105.4438,-117.7129 1114.4451,-123.301 1115.9652,-116.468"/>
<text text-anchor="middle" x="1738.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1211.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1211.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1182.8957,-88.3844C1160.8738,-76.5928 1129.3956,-61.5661 1099.7947,-54 1016.5483,-32.722 761.2081,-22.6612 655.436,-19.3227"/>
<polygon fill="#000000" stroke="#000000" points="655.4824,-15.8225 645.3789,-19.0114 655.2657,-22.8192 655.4824,-15.8225"/>
<text text-anchor="middle" x="1197.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
