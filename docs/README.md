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
<svg width="2987pt" height="392pt"
 viewBox="0.00 0.00 2987.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2983,-388 2983,4 -4,4"/>
<!-- exposure -->
<g id="node1" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2158" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2158" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1663" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1663" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2125.3977,-264.7181C2097.0455,-252.9264 2054.5725,-236.756 2016,-228 1920.5219,-206.3262 1807.5373,-197.6884 1735.5841,-194.2541"/>
<polygon fill="#000000" stroke="#000000" points="1735.4218,-190.7431 1725.2728,-193.7842 1735.103,-197.7359 1735.4218,-190.7431"/>
<text text-anchor="middle" x="2110.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="33" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="33" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2033" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2033" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M22.3769,-349.0566C12.73,-332.0255 0,-304.6852 0,-279 0,-279 0,-279 0,-105 0,-80.2524 42.9867,-78.1131 438,-54 750.7976,-34.9057 1756.8131,-21.4398 1986.1573,-18.5708"/>
<polygon fill="#000000" stroke="#000000" points="1986.5299,-22.0665 1996.4855,-18.4422 1986.4426,-15.0671 1986.5299,-22.0665"/>
<text text-anchor="middle" x="24" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node15" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="729" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="729" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M56.1701,-355.4419C84.4732,-343.1291 134.1347,-323.3931 179,-315 273.0226,-297.4109 555.6266,-285.3384 674.9242,-280.8935"/>
<polygon fill="#000000" stroke="#000000" points="675.0662,-284.3907 684.9303,-280.5243 674.8081,-277.3955 675.0662,-284.3907"/>
<text text-anchor="middle" x="203" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- genetic_analysis -->
<g id="node3" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1720" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1720" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1639.7619,-358.6272C1544.3797,-349.7283 1394.8021,-335.2988 1369,-330 1347.1062,-325.5038 1343.0356,-318.7402 1321,-315 1084.6908,-274.8898 1017.7998,-340.0038 782,-297 778.2926,-296.3239 774.4921,-295.4395 770.7119,-294.4255"/>
<polygon fill="#000000" stroke="#000000" points="771.4131,-290.9828 760.8305,-291.4927 769.4213,-297.6934 771.4131,-290.9828"/>
<text text-anchor="middle" x="1439" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1771.71,-351.3993C1789.7478,-345.182 1806.8029,-337.6144 1812,-330 1815.7583,-324.4936 1813.0679,-321.5806 1812,-315 1807.9477,-290.0284 1810.3725,-280.2858 1794,-261 1773.4796,-236.8281 1742.3199,-219.9305 1715.538,-208.909"/>
<polygon fill="#000000" stroke="#000000" points="1716.4839,-205.5199 1705.8969,-205.1117 1713.9186,-212.0329 1716.4839,-205.5199"/>
<text text-anchor="middle" x="1879" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2314" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2314" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2274.312,-263.0492C2243.2021,-251.2789 2198.5389,-235.9767 2158,-228 2079.2161,-212.4979 1852.7841,-200.4869 1735.445,-195.1002"/>
<polygon fill="#000000" stroke="#000000" points="1735.2747,-191.5889 1725.1259,-194.6306 1734.9565,-198.5817 1735.2747,-191.5889"/>
<text text-anchor="middle" x="2282" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment -->
<g id="node6" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2475" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2445.6361,-263.2107C2421.7115,-251.1959 2386.6629,-235.4919 2354,-228 2238.1118,-201.4185 1888.2862,-194.4203 1735.5978,-192.6134"/>
<polygon fill="#000000" stroke="#000000" points="1735.4296,-189.1113 1725.3903,-192.4969 1735.3497,-196.1109 1735.4296,-189.1113"/>
<text text-anchor="middle" x="2445" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- generic_file -->
<g id="node7" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="149" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="149" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M139.5205,-347.8767C131.3975,-330.6445 121,-303.7527 121,-279 121,-279 121,-279 121,-105 121,-56.791 1693.0833,-24.4772 1986.2357,-18.8706"/>
<polygon fill="#000000" stroke="#000000" points="1986.581,-22.3648 1996.5126,-18.675 1986.4478,-15.366 1986.581,-22.3648"/>
<text text-anchor="middle" x="174" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M183.1063,-350.4485C215.9571,-335.4726 260.7381,-315.0674 261,-315 337.8496,-295.2103 568.6502,-284.6952 674.6688,-280.7971"/>
<polygon fill="#000000" stroke="#000000" points="674.9675,-284.2887 684.8345,-280.4296 674.7146,-277.2933 674.9675,-284.2887"/>
<text text-anchor="middle" x="314" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M173.9777,-349.2827C193.6149,-336.3657 219.5078,-319.8914 231,-315 375.7092,-253.4073 418.2829,-250.0592 574,-228 771.0621,-200.0838 1379.9564,-193.7372 1590.4935,-192.3623"/>
<polygon fill="#000000" stroke="#000000" points="1590.5359,-195.8622 1600.5134,-192.2987 1590.4914,-188.8624 1590.5359,-195.8622"/>
<text text-anchor="middle" x="433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- survival -->
<g id="node8" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="839" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="839" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M851.3587,-261.4335C860.7418,-249.6646 874.7722,-235.0752 891,-228 953.9641,-200.5481 1410.1564,-193.9795 1590.2021,-192.4499"/>
<polygon fill="#000000" stroke="#000000" points="1590.3996,-195.9485 1600.3705,-192.3664 1590.3421,-188.9488 1590.3996,-195.9485"/>
<text text-anchor="middle" x="930.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="685" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="685" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M731.7927,-185.96C940.0871,-159.0733 1781.7494,-50.4315 1987.4677,-23.8773"/>
<polygon fill="#000000" stroke="#000000" points="1988.1451,-27.319 1997.6148,-22.5675 1987.2489,-20.3766 1988.1451,-27.319"/>
<text text-anchor="middle" x="1533.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M638.8943,-198.5288C603.3618,-205.5444 563.2155,-219.0602 582,-243 593.6753,-257.8796 638.7081,-267.4088 675.8881,-272.8996"/>
<polygon fill="#000000" stroke="#000000" points="675.7418,-276.4135 686.1322,-274.3423 676.7181,-269.4819 675.7418,-276.4135"/>
<text text-anchor="middle" x="622.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="755" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="755" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M749.6128,-347.9735C746.0569,-336.0751 741.3278,-320.2508 737.2963,-306.7606"/>
<polygon fill="#000000" stroke="#000000" points="740.5972,-305.5825 734.3803,-297.0034 733.8903,-307.5869 740.5972,-305.5825"/>
<text text-anchor="middle" x="805" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="979" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="979" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M973.7555,-260.6083C971.86,-249.6982 971.8718,-236.4014 980,-228 1000.9609,-206.3345 1418.5599,-196.3869 1590.2476,-193.2009"/>
<polygon fill="#000000" stroke="#000000" points="1590.5219,-196.6966 1600.4562,-193.0141 1590.3938,-189.6978 1590.5219,-196.6966"/>
<text text-anchor="middle" x="1039" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2002" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2002" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2053.9878,-365.0504C2213.56,-361.6032 2688.328,-347.1796 2734,-297 2852.0807,-167.2653 2076.5728,-257.5418 1964,-123 1941.1954,-95.745 1975.3616,-60.6547 2003.2223,-38.7403"/>
<polygon fill="#000000" stroke="#000000" points="2005.384,-41.4935 2011.2277,-32.656 2001.1483,-35.9205 2005.384,-41.4935"/>
<text text-anchor="middle" x="2443.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1952.1808,-360.6907C1914.9667,-356.8372 1862.8372,-351.6763 1817,-348 1753.7436,-342.9266 1592.2283,-349.9916 1532,-330 1520.4174,-326.1554 1520.6542,-318.622 1509,-315 1431.8382,-291.0187 861.5532,-311.1541 782,-297 778.2897,-296.3399 774.4872,-295.4666 770.7056,-294.4601"/>
<polygon fill="#000000" stroke="#000000" points="771.4041,-291.0169 760.8222,-291.5388 769.42,-297.7298 771.4041,-291.0169"/>
<text text-anchor="middle" x="1574.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1998.5832,-347.7966C1993.1655,-324.1415 1980.2874,-283.2419 1953,-261 1919.2846,-233.5187 1804.8134,-212.3777 1730.1737,-201.0992"/>
<polygon fill="#000000" stroke="#000000" points="1730.3248,-197.5832 1719.9186,-199.5736 1729.2947,-204.507 1730.3248,-197.5832"/>
<text text-anchor="middle" x="2022.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- consent_group -->
<g id="node13" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1702" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1702" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge28" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1730.018,-88.0362C1749.9713,-76.7042 1777.7901,-62.3896 1804,-54 1865.2912,-34.381 1939.3616,-25.2254 1986.3328,-21.1162"/>
<polygon fill="#000000" stroke="#000000" points="1986.8331,-24.5868 1996.5078,-20.2682 1986.2516,-17.611 1986.8331,-24.5868"/>
<text text-anchor="middle" x="1867.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_response -->
<g id="node14" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1300" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1300" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1300.8427,-260.9023C1302.3802,-249.6759 1306.2991,-235.9267 1316,-228 1336.8158,-210.9913 1495.6389,-200.26 1591.0476,-195.2794"/>
<polygon fill="#000000" stroke="#000000" points="1591.4071,-198.7657 1601.2146,-194.7578 1591.0484,-191.7749 1591.4071,-198.7657"/>
<text text-anchor="middle" x="1399" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M684.8451,-281.0038C535.0718,-287.8425 55.3048,-310.1084 49,-315 41.8332,-320.5604 37.8067,-329.3102 35.5673,-338.0031"/>
<polygon fill="#000000" stroke="#000000" points="32.0984,-337.5107 33.6782,-347.9871 38.9764,-338.8121 32.0984,-337.5107"/>
<text text-anchor="middle" x="85.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M703.8846,-263.9128C696.8012,-258.3002 689.9535,-251.254 686,-243 682.6861,-236.0813 681.5004,-228.0054 681.3821,-220.3476"/>
<polygon fill="#000000" stroke="#000000" points="684.8809,-220.4439 681.7827,-210.3122 677.8865,-220.1646 684.8809,-220.4439"/>
<text text-anchor="middle" x="722.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M744.526,-261.8623C756.474,-249.9724 774.098,-235.0521 793,-228 866.6163,-200.5346 1394.4723,-193.9362 1590.2117,-192.4263"/>
<polygon fill="#000000" stroke="#000000" points="1590.4216,-195.9249 1600.3951,-192.35 1590.3691,-188.9251 1590.4216,-195.9249"/>
<text text-anchor="middle" x="829.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge34" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1671.0808,-173.9735C1676.4669,-161.9585 1683.6475,-145.9401 1689.7331,-132.3646"/>
<polygon fill="#000000" stroke="#000000" points="1693.0327,-133.5602 1693.9295,-123.0034 1686.6451,-130.6967 1693.0327,-133.5602"/>
<text text-anchor="middle" x="1734.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2033" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2033" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2033,-86.9735C2033,-75.1918 2033,-59.5607 2033,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="2036.5001,-46.0033 2033,-36.0034 2029.5001,-46.0034 2036.5001,-46.0033"/>
<text text-anchor="middle" x="2081.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1523" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1523" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1500.1118,-261.3544C1489.7324,-251.2225 1481.4824,-238.4725 1490,-228 1503.082,-211.9154 1550.5767,-202.78 1592.4984,-197.7396"/>
<polygon fill="#000000" stroke="#000000" points="1592.9136,-201.215 1602.4528,-196.6048 1592.1207,-194.26 1592.9136,-201.215"/>
<text text-anchor="middle" x="1569.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node19" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2174" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2174" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2163.4214,-86.8039C2156.312,-75.9673 2146.0539,-62.6792 2134,-54 2116.969,-41.7371 2095.3506,-33.2932 2076.4882,-27.6829"/>
<polygon fill="#000000" stroke="#000000" points="2077.2009,-24.248 2066.6278,-24.9268 2075.3165,-30.9896 2077.2009,-24.248"/>
<text text-anchor="middle" x="2200" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="932" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="932" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M915.1801,-348.2667C903.5374,-337.044 887.1087,-323.1604 870,-315 833.968,-297.8135 820.5317,-307.4395 782,-297 778.663,-296.0959 775.2298,-295.0954 771.7917,-294.0428"/>
<polygon fill="#000000" stroke="#000000" points="772.7555,-290.6766 762.1649,-290.9752 770.6302,-297.3462 772.7555,-290.6766"/>
<text text-anchor="middle" x="959.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1199" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1199" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1149.6612,-358.1184C1120.7197,-352.4551 1083.8884,-343.4187 1053,-330 1041.8066,-325.1373 1041.5645,-318.8989 1030,-315 925.2793,-279.6939 890.3109,-318.9475 782,-297 778.3571,-296.2618 774.6195,-295.3424 770.897,-294.3123"/>
<polygon fill="#000000" stroke="#000000" points="771.7382,-290.9104 761.1536,-291.3759 769.7183,-297.6127 771.7382,-290.9104"/>
<text text-anchor="middle" x="1097.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1247.0405,-357.3659C1280.081,-349.3993 1314.8648,-335.6482 1296,-315 1266.0501,-282.2188 1126.9499,-329.7812 1097,-297 1086.2079,-285.1877 1086.6289,-273.1836 1097,-261 1128.5659,-223.9176 1446.0205,-203.0748 1591.2102,-195.4159"/>
<polygon fill="#000000" stroke="#000000" points="1591.5555,-198.9028 1601.3598,-194.8872 1591.1912,-191.9122 1591.5555,-198.9028"/>
<text text-anchor="middle" x="1141.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cytogenomic_file -->
<g id="node22" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="322" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="322" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M343.0415,-348.2822C357.957,-336.7624 378.9808,-322.5308 400,-315 449.1794,-297.38 594.4824,-286.6281 674.5444,-281.8772"/>
<polygon fill="#000000" stroke="#000000" points="675.1393,-285.3486 684.9191,-281.2735 674.7326,-278.3604 675.1393,-285.3486"/>
<text text-anchor="middle" x="471.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2342" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2342" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2317.7102,-87.4507C2300.898,-76.1579 2277.5687,-62.123 2255,-54 2196.718,-33.0228 2125.4168,-24.2198 2079.6142,-20.558"/>
<polygon fill="#000000" stroke="#000000" points="2079.6266,-17.0493 2069.3932,-19.7926 2079.1038,-24.0297 2079.6266,-17.0493"/>
<text text-anchor="middle" x="2354.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node24" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="545" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="545" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M543.4663,-347.6844C543.5929,-336.8029 545.7272,-323.5095 554,-315 570.6338,-297.8901 630.489,-288.3428 675.6023,-283.4482"/>
<polygon fill="#000000" stroke="#000000" points="675.9741,-286.9285 685.56,-282.4162 675.2525,-279.9658 675.9741,-286.9285"/>
<text text-anchor="middle" x="645.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- laboratory_test -->
<g id="node25" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1426" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1426" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1352.8961,-357.752C1306.0041,-351.7488 1244.0105,-342.4828 1190,-330 1168.2233,-324.967 1164.0038,-318.9227 1142,-315 984.2867,-286.8837 939.3568,-327.0474 782,-297 778.349,-296.3028 774.6058,-295.4122 770.8795,-294.4014"/>
<polygon fill="#000000" stroke="#000000" points="771.7132,-290.9978 761.1301,-291.4956 769.7137,-297.7062 771.7132,-290.9978"/>
<text text-anchor="middle" x="1255.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1453.5249,-348.9574C1476.2481,-335.0091 1505.7451,-317.2273 1512,-315 1562.8052,-296.9092 1591.0084,-332.0448 1632,-297 1654.0233,-278.1717 1660.8102,-244.5351 1662.6973,-220.4023"/>
<polygon fill="#000000" stroke="#000000" points="1666.1934,-220.5687 1663.2467,-210.3919 1659.2039,-220.185 1666.1934,-220.5687"/>
<text text-anchor="middle" x="1719.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_admin -->
<g id="node26" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2517" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2517" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2493.7529,-87.9453C2476.5133,-76.2593 2451.9464,-61.5552 2428,-54 2364.1998,-33.8706 2169.6914,-23.5586 2079.6477,-19.7574"/>
<polygon fill="#000000" stroke="#000000" points="2079.594,-16.2523 2069.458,-19.3363 2079.305,-23.2463 2079.594,-16.2523"/>
<text text-anchor="middle" x="2517.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node27" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2683" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2683" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2655.6276,-88.0525C2635.0808,-76.2571 2605.8171,-61.3718 2578,-54 2484.4482,-29.2077 2193.5749,-21.0639 2079.5382,-18.7815"/>
<polygon fill="#000000" stroke="#000000" points="2079.4525,-15.2793 2069.3865,-18.5845 2079.3167,-22.2779 2079.4525,-15.2793"/>
<text text-anchor="middle" x="2679" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node28" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2569" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2569" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2645.2867,-353.1237C2714.9008,-339.1442 2807,-314.0299 2807,-279 2807,-279 2807,-279 2807,-105 2807,-69.3197 2778.273,-66.8839 2745,-54 2683.36,-30.1319 2228.8045,-21.03 2080.0039,-18.6707"/>
<polygon fill="#000000" stroke="#000000" points="2079.8816,-15.1685 2069.8283,-18.5124 2079.7726,-22.1676 2079.8816,-15.1685"/>
<text text-anchor="middle" x="2893" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2467.6052,-359.5012C2293.6561,-348.5912 1927.1216,-326.6465 1617,-315 1524.266,-311.5174 873.3904,-313.1093 782,-297 778.2886,-296.3458 774.4854,-295.4767 770.7034,-294.4729"/>
<polygon fill="#000000" stroke="#000000" points="771.4009,-291.0296 760.8191,-291.556 769.4196,-297.7433 771.4009,-291.0296"/>
<text text-anchor="middle" x="2017" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2568.0583,-347.745C2566.1169,-325.4883 2560.176,-287.5626 2542,-261 2527.791,-240.2349 2519.7811,-236.2187 2496,-228 2460.3818,-215.6905 1931.3623,-199.5821 1735.3481,-194.0037"/>
<polygon fill="#000000" stroke="#000000" points="1735.2463,-190.4995 1725.151,-193.7144 1735.0477,-197.4967 1735.2463,-190.4995"/>
<text text-anchor="middle" x="2644" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
</g>
</svg>
</div>
