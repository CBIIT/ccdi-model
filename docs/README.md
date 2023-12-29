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
<svg width="2401pt" height="392pt"
 viewBox="0.00 0.00 2401.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2397,-388 2397,4 -4,4"/>
<!-- exposure -->
<g id="node1" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1976" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1976" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node25" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1220" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1220" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1955.8247,-175.1675C1940.2681,-163.2652 1917.648,-148.1949 1895,-141 1838.8422,-123.1595 1455.343,-111.1542 1292.687,-106.809"/>
<polygon fill="#000000" stroke="#000000" points="1292.3875,-103.2999 1282.2983,-106.5339 1292.2021,-110.2975 1292.3875,-103.2999"/>
<text text-anchor="middle" x="1968.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- molecular_test -->
<g id="node2" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="196" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="196" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M190.7457,-174.0069C188.7255,-162.9684 188.606,-149.3883 197,-141 215.6891,-122.3236 1121.8083,-126.4762 1148,-123 1153.8096,-122.2289 1159.8276,-121.1636 1165.7967,-119.933"/>
<polygon fill="#000000" stroke="#000000" points="1166.7438,-123.3082 1175.7504,-117.7286 1165.2302,-116.4737 1166.7438,-123.3082"/>
<text text-anchor="middle" x="261" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1346" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1346" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node5" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="429" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="429" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1329.9913,-348.1773C1318.2619,-336.4513 1301.2576,-322.0189 1283,-315 1213.2062,-288.1685 1019.781,-314.1474 947,-297 907.8622,-287.779 902.3876,-272.9659 864,-261 791.7703,-238.485 771.9141,-238.5798 697,-228 604.2449,-214.9005 578.9325,-227.9869 487,-210 482.9259,-209.2029 478.7329,-208.2251 474.554,-207.1412"/>
<polygon fill="#000000" stroke="#000000" points="475.4636,-203.7614 464.8914,-204.4543 473.5882,-210.5055 475.4636,-203.7614"/>
<text text-anchor="middle" x="1013.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2075" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2075" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge33" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1428.1116,-362.8209C1600.8418,-355.4192 1989.7282,-334.7315 2036,-297 2059.1052,-278.1593 2068.5235,-244.2265 2072.3618,-220.0355"/>
<polygon fill="#000000" stroke="#000000" points="2075.8447,-220.3971 2073.7254,-210.0165 2068.9087,-219.4531 2075.8447,-220.3971"/>
<text text-anchor="middle" x="2126.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1133" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1133" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1336.9859,-347.9527C1330.4561,-336.747 1320.5764,-323.002 1308,-315 1297.5247,-308.3349 1231.6981,-295.9249 1183.8551,-287.5633"/>
<polygon fill="#000000" stroke="#000000" points="1184.3964,-284.105 1173.9453,-285.844 1183.1998,-291.002 1184.3964,-284.105"/>
<text text-anchor="middle" x="1390.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="289" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="289" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M336.147,-358.3983C408.4307,-347.0476 551.0828,-325.8464 673,-315 848.4886,-299.3876 895.0629,-325.0334 1069,-297 1075.3564,-295.9755 1081.9813,-294.5429 1088.456,-292.9287"/>
<polygon fill="#000000" stroke="#000000" points="1089.6802,-296.2249 1098.4466,-290.275 1087.8832,-289.4595 1089.6802,-296.2249"/>
<text text-anchor="middle" x="715.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node20" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="636" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="636" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M238.66,-361.2713C155.8596,-352.0858 0,-328.2539 0,-279 0,-279 0,-279 0,-105 0,-50.7086 58.3907,-67.4097 111,-54 200.8364,-31.1013 478.1981,-21.8838 589.2873,-19.047"/>
<polygon fill="#000000" stroke="#000000" points="589.5973,-22.5405 599.5069,-18.7922 589.4228,-15.5426 589.5973,-22.5405"/>
<text text-anchor="middle" x="42.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M283.1282,-347.6555C275.3744,-319.8483 264.9978,-266.2247 286,-228 307.5523,-188.7742 329.8263,-191.5467 371,-174 427.8219,-149.7846 444.7862,-149.245 506,-141 788.8909,-102.8968 865.2098,-161.8437 1148,-123 1153.7242,-122.2137 1159.6523,-121.1506 1165.5372,-119.9317"/>
<polygon fill="#000000" stroke="#000000" points="1166.3513,-123.3363 1175.3567,-117.7548 1164.8362,-116.5022 1166.3513,-123.3363"/>
<text text-anchor="middle" x="328.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M464.527,-204.6591C471.8709,-206.8117 479.6191,-208.752 487,-210 602.7584,-229.5728 903.0519,-192.6343 1015,-228 1026.6371,-231.6763 1027.1196,-237.4723 1038,-243 1053.8867,-251.0712 1072.0303,-258.3788 1088.1751,-264.2684"/>
<polygon fill="#000000" stroke="#000000" points="1087.3364,-267.6851 1097.9311,-267.7464 1089.6871,-261.0916 1087.3364,-267.6851"/>
<text text-anchor="middle" x="1078.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M382.1076,-186.0683C312.6217,-177.1971 188.2955,-160.9824 168,-156 125.8129,-145.6433 100.999,-158.5255 76,-123 66.7922,-109.915 66.0786,-99.5526 76,-87 107.7191,-46.8688 460.492,-26.2899 589.2875,-20.0737"/>
<polygon fill="#000000" stroke="#000000" points="589.784,-23.5542 599.6066,-19.5834 589.4517,-16.5621 589.784,-23.5542"/>
<text text-anchor="middle" x="116.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M457.5846,-177.2491C482.9497,-164.9877 521.3997,-148.3947 557,-141 685.6482,-114.2778 1017.8497,-141.0376 1148,-123 1153.7233,-122.2068 1159.6508,-121.1392 1165.5353,-119.9176"/>
<polygon fill="#000000" stroke="#000000" points="1166.3506,-123.3219 1175.3543,-117.7377 1164.8334,-116.4883 1166.3506,-123.3219"/>
<text text-anchor="middle" x="597.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="832" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="832" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M834.1688,-173.9031C836.5494,-162.5268 841.5402,-148.6088 852,-141 878.6455,-121.6171 1115.4345,-128.017 1148,-123 1153.4917,-122.1539 1159.1764,-121.0821 1164.8332,-119.8847"/>
<polygon fill="#000000" stroke="#000000" points="1165.9478,-123.2216 1174.9376,-117.615 1164.4137,-116.3918 1165.9478,-123.2216"/>
<text text-anchor="middle" x="931.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1024" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1024" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1016.6804,-173.9227C1013.6129,-163.1309 1012.3091,-149.8481 1020,-141 1038.844,-119.3207 1119.8054,-128.4909 1148,-123 1153.296,-121.9686 1158.7858,-120.793 1164.2645,-119.548"/>
<polygon fill="#000000" stroke="#000000" points="1165.1331,-122.9393 1174.0696,-117.2481 1163.5345,-116.1243 1165.1331,-122.9393"/>
<text text-anchor="middle" x="1079" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2054.0655,-204.1018C2048.9653,-206.504 2043.4151,-208.6877 2038,-210 1867.1232,-251.4119 1418.5197,-189.3372 1247,-228 1218.8689,-234.3411 1189.1977,-247.859 1167.1796,-259.3849"/>
<polygon fill="#000000" stroke="#000000" points="1165.3999,-256.3677 1158.2387,-264.1759 1168.7061,-262.5378 1165.3999,-256.3677"/>
<text text-anchor="middle" x="1271" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge24" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2061.2486,-175.7678C2050.2812,-164.0112 2033.8437,-148.8566 2016,-141 1712.1153,-7.1995 1604.7943,-82.6993 1274,-54 1053.077,-34.833 788.1906,-23.6498 682.6801,-19.6681"/>
<polygon fill="#000000" stroke="#000000" points="682.5053,-16.1592 672.3815,-19.2833 682.2439,-23.1543 682.5053,-16.1592"/>
<text text-anchor="middle" x="1991" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="413" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="413" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M427.8977,-87.2843C438.2893,-76.0689 453.1003,-62.1871 469,-54 506.7566,-34.5584 554.5219,-25.6027 589.2877,-21.4851"/>
<polygon fill="#000000" stroke="#000000" points="590.0729,-24.9203 599.6343,-20.3563 589.3136,-17.9616 590.0729,-24.9203"/>
<text text-anchor="middle" x="517.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2093" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2093" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2028.5301,-350.9919C1973.8831,-338.9645 1893.2614,-322.8466 1822,-315 1792.1637,-311.7147 1307.4961,-312.8414 1282,-297 1252.4431,-278.6355 1274.6445,-246.2227 1245,-228 1209.1148,-205.9411 528.5692,-216.8079 487,-210 482.7861,-209.3099 478.4539,-208.3876 474.1463,-207.3239"/>
<polygon fill="#000000" stroke="#000000" points="474.7745,-203.8679 464.2069,-204.628 472.942,-210.6238 474.7745,-203.8679"/>
<text text-anchor="middle" x="1373.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2135.468,-349.2371C2175.8612,-330.6188 2227.3893,-298.2311 2205,-261 2184.947,-227.654 2142.7494,-209.5641 2111.8493,-200.3796"/>
<polygon fill="#000000" stroke="#000000" points="2112.4238,-196.9066 2101.8515,-197.5971 2110.5469,-203.6503 2112.4238,-196.9066"/>
<text text-anchor="middle" x="2301.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1990.1015,-357.6858C1865.0238,-347.5819 1647.5303,-330.0207 1461,-315 1361.4458,-306.9832 1336.0874,-309.5296 1237,-297 1219.386,-294.7727 1200.2075,-291.653 1183.1718,-288.6353"/>
<polygon fill="#000000" stroke="#000000" points="1183.3372,-285.1088 1172.8747,-286.7785 1182.0949,-291.9977 1183.3372,-285.1088"/>
<text text-anchor="middle" x="1726.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node11" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="739" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="739" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M607.7995,-360.4114C507.783,-353.0719 381.8057,-336.1193 349,-297 338.7189,-284.7403 341.5743,-275.1725 349,-261 355.5228,-248.5508 364.0821,-251.8504 375,-243 385.1738,-234.7528 395.7744,-225.0223 404.8619,-216.2835"/>
<polygon fill="#000000" stroke="#000000" points="407.3794,-218.7172 412.0968,-209.2305 402.4931,-213.7048 407.3794,-218.7172"/>
<text text-anchor="middle" x="457.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M834.5544,-353.0269C851.6581,-351.068 869.3365,-349.2784 886,-348 917.8665,-345.5553 1436.154,-350.1028 1461,-330 1485.5534,-310.1339 1454.2816,-281.8559 1478,-261 1575.4162,-175.3406 1638.8036,-239.651 1768,-228 1887.7803,-217.1982 1921.7657,-240.8802 2038,-210 2040.1877,-209.4188 2042.4007,-208.7057 2044.5992,-207.9022"/>
<polygon fill="#000000" stroke="#000000" points="2046.1667,-211.0398 2054.0219,-203.9302 2043.4476,-204.5895 2046.1667,-211.0398"/>
<text text-anchor="middle" x="1586.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M748.0479,-347.8337C754.8573,-336.2731 765.3534,-322.1713 779,-315 836.1569,-284.9638 1005.3414,-307.8015 1069,-297 1075.273,-295.9356 1081.812,-294.495 1088.2115,-292.8895"/>
<polygon fill="#000000" stroke="#000000" points="1089.3302,-296.2137 1098.0949,-290.2613 1087.5313,-289.4488 1089.3302,-296.2137"/>
<text text-anchor="middle" x="887.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1097.6695,-268.1259C1088.4035,-265.5325 1078.3787,-262.9535 1069,-261 1011.4656,-249.0159 992.0746,-266.0167 938,-243 928.1006,-238.7863 929.0881,-231.7393 919,-228 828.9067,-194.6054 581.6773,-226.3769 487,-210 482.8509,-209.2823 478.5848,-208.3505 474.3392,-207.2888"/>
<polygon fill="#000000" stroke="#000000" points="475.103,-203.8693 464.5345,-204.6154 473.2615,-210.6228 475.103,-203.8693"/>
<text text-anchor="middle" x="974.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1170.7223,-269.4794C1220.7095,-257.3403 1311.8207,-236.8641 1391,-228 1533.9405,-211.9978 1898.2993,-244.2309 2038,-210 2040.1985,-209.4613 2042.4197,-208.7802 2044.6242,-208.0001"/>
<polygon fill="#000000" stroke="#000000" points="2046.1673,-211.1492 2054.0606,-204.0819 2043.4829,-204.6843 2046.1673,-211.1492"/>
<text text-anchor="middle" x="1427.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1130.6329,-260.8199C1128.6411,-238.9718 1128.0241,-201.7864 1142,-174 1151.4593,-155.1933 1168.45,-139.2202 1184.164,-127.3936"/>
<polygon fill="#000000" stroke="#000000" points="1186.6262,-129.9344 1192.7068,-121.2582 1182.5428,-124.2488 1186.6262,-129.9344"/>
<text text-anchor="middle" x="1178.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node13" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="561" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="561" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge42" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M563.4132,-87.0049C565.5607,-76.5075 569.5706,-63.5044 577,-54 582.9153,-46.4325 590.8998,-40.0778 599.0812,-34.9172"/>
<polygon fill="#000000" stroke="#000000" points="601.0462,-37.8239 607.9476,-29.7852 597.5395,-31.7656 601.0462,-37.8239"/>
<text text-anchor="middle" x="633.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="971" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="971" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge31" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M916.7923,-353.2939C906.6072,-351.256 896.0131,-349.3701 886,-348 854.673,-343.7134 628.5067,-347.2379 602,-330 573.0028,-311.1425 590.6331,-285.2828 566,-261 540.782,-236.1406 504.8002,-218.4904 476.0398,-207.267"/>
<polygon fill="#000000" stroke="#000000" points="477.1809,-203.9569 466.589,-203.7061 474.7127,-210.5073 477.1809,-203.9569"/>
<text text-anchor="middle" x="644" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1024.7281,-353.2039C1035.0548,-351.1479 1045.8227,-349.2785 1056,-348 1248.4303,-323.8257 1299.0198,-349.2994 1492,-330 1584.6993,-320.7294 1617.293,-341.7558 1699,-297 1717.7751,-286.7157 1712.3108,-271.4396 1731,-261 1804.6797,-219.8434 1834.7067,-241.5941 1918,-228 1971.2258,-219.3132 1986.492,-225.9804 2038,-210 2039.9444,-209.3967 2041.9145,-208.7047 2043.8804,-207.9511"/>
<polygon fill="#000000" stroke="#000000" points="2045.7344,-210.9638 2053.5372,-203.7967 2042.968,-204.5336 2045.7344,-210.9638"/>
<text text-anchor="middle" x="1792" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M983.2125,-348.1562C991.5665,-337.1773 1003.5389,-323.6074 1017,-315 1023.2048,-311.0325 1057.1846,-300.6738 1086.7762,-292.0812"/>
<polygon fill="#000000" stroke="#000000" points="1087.9597,-295.3826 1096.5969,-289.2467 1086.0185,-288.6571 1087.9597,-295.3826"/>
<text text-anchor="middle" x="1078" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="712" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="712" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge6" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M706.9283,-86.6098C703.4044,-76.2298 697.9044,-63.4798 690,-54 684.4507,-47.3447 677.3621,-41.4392 670.16,-36.4335"/>
<polygon fill="#000000" stroke="#000000" points="672.0346,-33.4777 661.7385,-30.9797 668.2295,-39.3533 672.0346,-33.4777"/>
<text text-anchor="middle" x="751" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node16" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1155" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1155" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge11" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1091.8152,-353.1715C1079.9573,-351.1455 1067.6325,-349.2953 1056,-348 1032.2922,-345.3601 643.5102,-347.2175 627,-330 622.3858,-325.1882 622.8218,-320.1949 627,-315 650.3848,-285.9251 685.6152,-326.0749 709,-297 719.0278,-284.5323 718.967,-273.5163 709,-261 645.9358,-181.8053 584.7461,-236.3552 487,-210 483.3767,-209.023 479.6397,-207.9698 475.8907,-206.8803"/>
<polygon fill="#000000" stroke="#000000" points="476.5915,-203.4373 466.0086,-203.9395 474.5948,-210.1465 476.5915,-203.4373"/>
<text text-anchor="middle" x="788.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge10" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1217.9138,-353.1664C1229.8537,-351.1275 1242.2773,-349.2739 1254,-348 1387.6913,-333.4713 1743.4459,-369.041 1857,-297 1875.0764,-285.532 1871.1758,-272.8562 1889,-261 1947.2787,-222.2346 1973.296,-236.6938 2038,-210 2039.8325,-209.244 2041.7024,-208.4404 2043.5802,-207.6084"/>
<polygon fill="#000000" stroke="#000000" points="2045.2892,-210.6743 2052.8971,-203.3006 2042.3514,-204.3206 2045.2892,-210.6743"/>
<text text-anchor="middle" x="1960.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1150.4416,-347.9735C1147.4328,-336.0751 1143.4312,-320.2508 1140.0199,-306.7606"/>
<polygon fill="#000000" stroke="#000000" points="1143.3974,-305.8401 1137.5526,-297.0034 1136.611,-307.5563 1143.3974,-305.8401"/>
<text text-anchor="middle" x="1217.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- therapeutic_procedure -->
<g id="node17" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1342" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1342" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1317.3115,-174.3943C1298.4253,-160.9262 1272.2377,-142.2515 1251.7859,-127.667"/>
<polygon fill="#000000" stroke="#000000" points="1253.584,-124.6505 1243.41,-121.694 1249.5197,-130.3498 1253.584,-124.6505"/>
<text text-anchor="middle" x="1382" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1563" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1563" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1540.05,-174.5134C1523.8578,-163.0967 1501.1813,-148.8934 1479,-141 1445.1512,-128.9547 1354.148,-118.0422 1289.6062,-111.4664"/>
<polygon fill="#000000" stroke="#000000" points="1289.7877,-107.9671 1279.4876,-110.4488 1289.0871,-114.932 1289.7877,-107.9671"/>
<text text-anchor="middle" x="1579" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="880" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="880" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M859.3145,-87.4125C845.1607,-76.2513 825.4943,-62.3816 806,-54 765.8919,-36.7554 716.805,-27.5033 681.7073,-22.7181"/>
<polygon fill="#000000" stroke="#000000" points="682.1113,-19.2413 671.7446,-21.4282 681.2124,-26.1833 682.1113,-19.2413"/>
<text text-anchor="middle" x="902.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_funding -->
<g id="node21" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1062" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1062" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1039.2366,-87.7897C1022.6232,-76.1886 999.0653,-61.6534 976,-54 922.7574,-36.3334 762.7896,-25.1296 682.7189,-20.4759"/>
<polygon fill="#000000" stroke="#000000" points="682.6173,-16.9644 672.434,-19.8886 682.2182,-23.9531 682.6173,-16.9644"/>
<text text-anchor="middle" x="1071" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1721" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1721" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1703.3417,-174.8506C1690.0854,-163.1188 1670.868,-148.3989 1651,-141 1587.2429,-117.2568 1397.7822,-109.0889 1292.5301,-106.343"/>
<polygon fill="#000000" stroke="#000000" points="1292.388,-102.8384 1282.3034,-106.0863 1292.2124,-109.8362 1292.388,-102.8384"/>
<text text-anchor="middle" x="1723.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="605" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="605" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M528.0108,-179.2184C514.3766,-177.2515 500.2919,-175.4096 487,-174 453.7929,-170.4785 214.522,-174.9117 187,-156 161.1349,-138.2268 151.5058,-110.7672 172,-87 199.1408,-55.5247 478.0117,-30.3741 589.911,-21.474"/>
<polygon fill="#000000" stroke="#000000" points="590.1957,-24.9625 599.8901,-20.6882 589.6462,-17.9841 590.1957,-24.9625"/>
<text text-anchor="middle" x="258" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M620.044,-174.0948C631.1221,-162.3309 647.2889,-147.8872 665,-141 715.0527,-121.5362 1094.8299,-130.5533 1148,-123 1153.7206,-122.1873 1159.6463,-121.1071 1165.5297,-119.8779"/>
<polygon fill="#000000" stroke="#000000" points="1166.3486,-123.2813 1175.3476,-117.6896 1164.8256,-116.449 1166.3486,-123.2813"/>
<text text-anchor="middle" x="751" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- follow_up -->
<g id="node24" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1849" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1849" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1829.6272,-174.9929C1814.9077,-163.1679 1793.5764,-148.2716 1772,-141 1727.6904,-126.0669 1431.335,-113.0199 1292.0638,-107.6317"/>
<polygon fill="#000000" stroke="#000000" points="1292.0365,-104.1281 1281.9095,-107.2416 1291.7678,-111.123 1292.0365,-104.1281"/>
<text text-anchor="middle" x="1846" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1198.8818,-88.0438C1182.898,-76.2442 1159.8612,-61.3573 1137,-54 1053.2503,-27.0472 790.269,-20.2175 682.63,-18.5335"/>
<polygon fill="#000000" stroke="#000000" points="682.4569,-15.0306 672.4061,-18.3818 682.353,-22.0298 682.4569,-15.0306"/>
<text text-anchor="middle" x="1219.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
