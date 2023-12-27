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
<svg width="3079pt" height="392pt"
 viewBox="0.00 0.00 3079.04 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3075.0444,-388 3075.0444,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="730.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="730.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge28" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M57.8039,-86.6121C55.9098,-75.7034 55.9219,-62.4068 64.0444,-54 85.5291,-31.7633 534.9144,-21.5701 683.1036,-18.8048"/>
<polygon fill="#000000" stroke="#000000" points="683.3087,-22.3017 693.2427,-18.6185 683.18,-15.3029 683.3087,-22.3017"/>
<text text-anchor="middle" x="115.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node2" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2295.0444" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2295.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node17" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2023.0444" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2023.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2213.8692,-358.3405C2160.5429,-352.2806 2096.3158,-342.7201 2072.0444,-330 2060.3192,-323.8551 2049.7792,-313.8405 2041.5058,-304.3055"/>
<polygon fill="#000000" stroke="#000000" points="2044.1586,-302.0206 2035.113,-296.5044 2038.7443,-306.4575 2044.1586,-302.0206"/>
<text text-anchor="middle" x="2143.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2386.0444" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2386.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- cytogenomic_file&#45;&gt;pdx -->
<g id="edge15" class="edge">
<title>cytogenomic_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2353.8207,-352.3892C2381.6852,-342.3631 2411.5675,-325.3629 2424.0444,-297 2435.9823,-269.8624 2420.0964,-237.677 2405.3693,-216.1592"/>
<polygon fill="#000000" stroke="#000000" points="2408.1116,-213.978 2399.4239,-207.9138 2402.4336,-218.0721 2408.1116,-213.978"/>
<text text-anchor="middle" x="2499.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node25" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2119.0444" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2119.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cytogenomic_file&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2337.7938,-350.1722C2356.754,-340.8372 2372.3085,-328.2751 2360.0444,-315 2325.7062,-277.8311 2169.7689,-331.8132 2133.0444,-297 2112.6985,-277.713 2111.6193,-244.1639 2114.0755,-220.1771"/>
<polygon fill="#000000" stroke="#000000" points="2117.5503,-220.5969 2115.3473,-210.2337 2110.6068,-219.7088 2117.5503,-220.5969"/>
<text text-anchor="middle" x="2204.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2479.0444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2479.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2423.3745,-353.6106C2413.6225,-351.6122 2403.5548,-349.6581 2394.0444,-348 2336.1485,-337.9058 2320.4008,-342.809 2263.0444,-330 2241.231,-325.1286 2236.8211,-320.033 2215.0444,-315 2163.3558,-303.0538 2149.0901,-307.2791 2097.0444,-297 2088.3739,-295.2876 2079.1862,-293.2422 2070.3424,-291.1545"/>
<polygon fill="#000000" stroke="#000000" points="2071.0913,-287.7348 2060.5496,-288.7949 2069.4515,-294.5401 2071.0913,-287.7348"/>
<text text-anchor="middle" x="2324.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>pathology_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2513.0605,-349.7134C2549.4691,-330.0086 2598.9703,-295.2053 2575.0444,-261 2557.1563,-235.4265 2472.1571,-211.9363 2422.45,-200.0808"/>
<polygon fill="#000000" stroke="#000000" points="2423.2473,-196.6728 2412.7125,-197.7992 2421.6504,-203.4883 2423.2473,-196.6728"/>
<text text-anchor="middle" x="2642.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>pathology_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2449.6541,-349.1494C2429.4748,-338.16 2401.7864,-324.2009 2376.0444,-315 2342.5424,-303.0254 2326.9066,-317.8027 2298.0444,-297 2282.8327,-286.036 2290.1643,-273.3383 2276.0444,-261 2245.3645,-234.1912 2202.6232,-216.3274 2169.4816,-205.506"/>
<polygon fill="#000000" stroke="#000000" points="2170.118,-202.037 2159.5285,-202.3716 2168.0154,-208.7138 2170.118,-202.037"/>
<text text-anchor="middle" x="2359.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2793.0444" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2793.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2723.85,-355.8958C2643.5133,-344.483 2506.9414,-326.0639 2389.0444,-315 2259.5891,-302.8514 2225.6068,-316.4418 2097.0444,-297 2088.1158,-295.6498 2078.6844,-293.7389 2069.6539,-291.6625"/>
<polygon fill="#000000" stroke="#000000" points="2070.2173,-288.1984 2059.6767,-289.269 2068.5843,-295.0053 2070.2173,-288.1984"/>
<text text-anchor="middle" x="2588.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2840.9001,-351.1905C2892.6786,-332.7845 2963.6255,-299.1095 2930.0444,-261 2896.5181,-222.9526 2541.9565,-200.4409 2423.9808,-193.9606"/>
<polygon fill="#000000" stroke="#000000" points="2424.1355,-190.4639 2413.9608,-193.4177 2423.7567,-197.4537 2424.1355,-190.4639"/>
<text text-anchor="middle" x="3004.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;cell_line -->
<g id="edge26" class="edge">
<title>sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2783.9824,-347.8935C2770.7375,-323.5507 2743.632,-281.0202 2707.0444,-261 2661.2469,-235.9402 2317.8025,-207.1981 2177.9906,-196.4017"/>
<polygon fill="#000000" stroke="#000000" points="2178.1234,-192.9017 2167.8846,-195.6252 2177.5871,-199.8811 2178.1234,-192.9017"/>
<text text-anchor="middle" x="2814.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file -->
<g id="node5" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1336.0444" cy="-366" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="1336.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1436.8462,-353.6645C1509.1537,-344.6122 1595.1725,-333.3389 1603.0444,-330 1612.9491,-325.7988 1611.9766,-318.7937 1622.0444,-315 1693.469,-288.0862 1889.9054,-310.4151 1965.0444,-297 1969.8512,-296.1418 1974.8171,-295.005 1979.7271,-293.7185"/>
<polygon fill="#000000" stroke="#000000" points="1980.9888,-296.999 1989.6583,-290.9089 1979.0831,-290.2634 1980.9888,-296.999"/>
<text text-anchor="middle" x="1730.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>single_cell_sequencing_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1399.8681,-350.0373C1433.3639,-339.2464 1473.4695,-322.2681 1503.0444,-297 1517.3008,-284.8197 1509.075,-270.8277 1525.0444,-261 1648.8157,-184.8297 2032.1717,-221.5383 2177.0444,-210 2236.9518,-205.2287 2306.4669,-199.1295 2348.312,-195.3968"/>
<polygon fill="#000000" stroke="#000000" points="2348.6832,-198.8777 2358.3318,-194.501 2348.0598,-191.9055 2348.6832,-198.8777"/>
<text text-anchor="middle" x="1633.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>single_cell_sequencing_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1228.4554,-354.7516C1143.1143,-341.6228 1045.3266,-314.491 1092.0444,-261 1163.7402,-178.9097 1226.4008,-236.6991 1335.0444,-228 1495.691,-215.137 1900.9542,-235.7504 2060.0444,-210 2064.5059,-209.2779 2069.0999,-208.3046 2073.6614,-207.1827"/>
<polygon fill="#000000" stroke="#000000" points="2074.7833,-210.5054 2083.5315,-204.5289 2072.9656,-203.7455 2074.7833,-210.5054"/>
<text text-anchor="middle" x="1200.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="831.0444" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="831.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node20" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1141.0444" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1141.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M835.5384,-174.0113C839.3401,-162.6808 845.9869,-148.773 857.0444,-141 874.1901,-128.9472 992.0374,-117.1484 1070.4394,-110.5014"/>
<polygon fill="#000000" stroke="#000000" points="1071.0755,-113.9605 1080.7484,-109.6377 1070.4911,-106.9849 1071.0755,-113.9605"/>
<text text-anchor="middle" x="916.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="392.0444" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="392.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M384.6099,-173.8209C381.4992,-162.9908 380.1902,-149.7035 388.0444,-141 414.2357,-111.9765 527.74,-139.7912 563.0444,-123 583.4784,-113.2814 580.829,-100.4238 599.0444,-87 628.5686,-65.2422 665.8746,-46.3042 693.1173,-33.8014"/>
<polygon fill="#000000" stroke="#000000" points="694.6307,-36.9583 702.3045,-29.6533 691.7501,-30.5785 694.6307,-36.9583"/>
<text text-anchor="middle" x="685.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M389.6484,-173.9688C389.2607,-162.7697 390.9903,-149.026 400.0444,-141 421.2184,-122.2305 880.7939,-124.5947 909.0444,-123 963.4174,-119.9307 1024.8575,-115.1027 1070.8449,-111.2192"/>
<polygon fill="#000000" stroke="#000000" points="1071.3366,-114.6902 1081.0042,-110.3555 1070.7436,-107.7153 1071.3366,-114.6902"/>
<text text-anchor="middle" x="529.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1015.0444" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1015.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1023.1703,-173.8782C1028.8093,-163.0696 1037.2455,-149.7848 1048.0444,-141 1058.5329,-132.4678 1071.2766,-125.791 1083.9236,-120.6317"/>
<polygon fill="#000000" stroke="#000000" points="1085.4338,-123.802 1093.5371,-116.9766 1082.946,-117.259 1085.4338,-123.802"/>
<text text-anchor="middle" x="1092.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="285.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="285.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M292.5922,-86.7415C298.3425,-75.297 307.4321,-61.3637 320.0444,-54 350.8118,-36.0364 582.4887,-24.2124 683.3558,-19.8647"/>
<polygon fill="#000000" stroke="#000000" points="683.7161,-23.3526 693.5585,-19.4312 683.4189,-16.3589 683.7161,-23.3526"/>
<text text-anchor="middle" x="382.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="467.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="467.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M454.2353,-87.1358C448.2416,-76.4242 444.0022,-63.1508 452.0444,-54 467.0603,-36.9142 608.4116,-25.5838 683.5645,-20.7149"/>
<polygon fill="#000000" stroke="#000000" points="683.9514,-24.1975 693.7096,-20.0708 683.5079,-17.2115 683.9514,-24.1975"/>
<text text-anchor="middle" x="521.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="932.0444" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="932.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M880.0597,-365.4517C709.8416,-362.9762 180.0444,-349.6006 180.0444,-279 180.0444,-279 180.0444,-279 180.0444,-105 180.0444,-65.0499 203.7413,-73.4877 300.0444,-54 372.3209,-39.3742 587.7332,-25.9533 683.3879,-20.5337"/>
<polygon fill="#000000" stroke="#000000" points="683.8388,-24.014 693.6266,-19.9583 683.446,-17.025 683.8388,-24.014"/>
<text text-anchor="middle" x="222.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M982.1965,-360.7963C1082.8932,-350.5273 1316.9117,-327.564 1514.0444,-315 1714.2422,-302.2406 1767.3459,-331.0188 1965.0444,-297 1969.8565,-296.172 1974.8257,-295.0544 1979.7377,-293.7792"/>
<polygon fill="#000000" stroke="#000000" points="1980.994,-297.0617 1989.6712,-290.9825 1979.0969,-290.3236 1980.994,-297.0617"/>
<text text-anchor="middle" x="1556.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M928.2329,-347.9871C921.5508,-311.2476 911.8845,-226.6949 951.0444,-174 967.1854,-152.2802 1032.8313,-131.6886 1082.4793,-118.7482"/>
<polygon fill="#000000" stroke="#000000" points="1083.3576,-122.1363 1092.1762,-116.264 1081.6204,-115.3553 1083.3576,-122.1363"/>
<text text-anchor="middle" x="970.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1141.0444" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1141.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1141.0444,-173.9735C1141.0444,-162.1918 1141.0444,-146.5607 1141.0444,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1144.5445,-133.0033 1141.0444,-123.0034 1137.5445,-133.0034 1144.5445,-133.0033"/>
<text text-anchor="middle" x="1184.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- therapeutic_procedure -->
<g id="node13" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1330.0444" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1330.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1298.6767,-174.6231C1279.6435,-164.3449 1254.7263,-151.3551 1232.0444,-141 1218.2311,-134.6937 1202.9712,-128.4029 1188.9585,-122.8853"/>
<polygon fill="#000000" stroke="#000000" points="1190.0782,-119.5654 1179.4897,-119.1983 1187.5382,-126.0883 1190.0782,-119.5654"/>
<text text-anchor="middle" x="1356.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- molecular_test -->
<g id="node15" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1546.0444" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1546.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1520.807,-174.645C1502.7557,-163.1335 1477.4338,-148.7653 1453.0444,-141 1409.6605,-127.1871 1290.1042,-116.0757 1212.2205,-110.0194"/>
<polygon fill="#000000" stroke="#000000" points="1212.2312,-106.51 1201.9927,-109.2344 1211.6955,-113.4895 1212.2312,-106.51"/>
<text text-anchor="middle" x="1552.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="840.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="840.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M818.5742,-88.019C801.1458,-74.2347 776.4536,-54.7055 757.573,-39.7726"/>
<polygon fill="#000000" stroke="#000000" points="759.6297,-36.9369 749.6151,-33.4786 755.2873,-42.4272 759.6297,-36.9369"/>
<text text-anchor="middle" x="840.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1991.4254,-266.4153C1985.6995,-264.4151 1979.7381,-262.511 1974.0444,-261 1842.0522,-225.9722 1787.4288,-281.4393 1671.0444,-210 1638.5444,-190.0508 1653.425,-159.438 1620.0444,-141 1585.3863,-121.8563 1338.5431,-111.304 1213.403,-107.1314"/>
<polygon fill="#000000" stroke="#000000" points="1213.2545,-103.6248 1203.145,-106.7946 1213.0247,-110.621 1213.2545,-103.6248"/>
<text text-anchor="middle" x="1707.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2061.063,-269.7195C2072.6158,-266.9082 2085.3474,-263.8189 2097.0444,-261 2187.9701,-239.0871 2295.0694,-213.6017 2349.8208,-200.5965"/>
<polygon fill="#000000" stroke="#000000" points="2350.8155,-203.9577 2359.7362,-198.2418 2349.1981,-197.1471 2350.8155,-203.9577"/>
<text text-anchor="middle" x="2267.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2022.1205,-260.7209C2022.5197,-250.1228 2024.7262,-237.1137 2032.0444,-228 2037.6143,-221.0636 2054.1749,-213.5178 2071.3735,-207.1347"/>
<polygon fill="#000000" stroke="#000000" points="2072.6897,-210.3811 2080.9281,-203.7193 2070.3335,-203.7896 2072.6897,-210.3811"/>
<text text-anchor="middle" x="2068.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- follow_up -->
<g id="node18" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1808.0444" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1808.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1777.1356,-176.9877C1750.8979,-165.0005 1711.9042,-148.9415 1676.0444,-141 1590.071,-121.9603 1338.9972,-111.4011 1213.7891,-107.186"/>
<polygon fill="#000000" stroke="#000000" points="1213.645,-103.6794 1203.5343,-106.8456 1213.4126,-110.6756 1213.645,-103.6794"/>
<text text-anchor="middle" x="1769.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- methylation_array_file -->
<g id="node19" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1607.0444" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1607.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1703.2148,-355.9022C1756.9176,-349.3681 1817.9407,-340.1963 1843.0444,-330 1853.6711,-325.6838 1853.4725,-319.4487 1864.0444,-315 1906.0713,-297.3151 1920.7404,-307.7782 1965.0444,-297 1969.4863,-295.9194 1974.0874,-294.6884 1978.6663,-293.3891"/>
<polygon fill="#000000" stroke="#000000" points="1979.9812,-296.6505 1988.5845,-290.4672 1978.003,-289.9359 1979.9812,-296.6505"/>
<text text-anchor="middle" x="1955.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>methylation_array_file&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1529.3788,-352.64C1502.0157,-344.672 1481.6816,-332.5935 1498.0444,-315 1535.6756,-274.5385 1695.0753,-318.3397 1746.0444,-297 1768.4128,-287.6349 1764.6244,-270.2409 1787.0444,-261 1847.3561,-236.1412 2015.2284,-250.3721 2080.0444,-243 2086.7101,-242.2418 2268.4628,-211.7532 2348.6441,-198.2853"/>
<polygon fill="#000000" stroke="#000000" points="2349.5228,-201.6868 2358.8047,-196.5784 2348.363,-194.7836 2349.5228,-201.6868"/>
<text text-anchor="middle" x="1878.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;cell_line -->
<g id="edge42" class="edge">
<title>methylation_array_file&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1530.0865,-352.5383C1449.6239,-337.6848 1333.1883,-313.6784 1320.0444,-297 1310.1409,-284.4333 1309.7387,-273.239 1320.0444,-261 1375.532,-195.1034 1425.345,-236.7658 1511.0444,-228 1753.9084,-203.1587 1819.2068,-249.9655 2060.0444,-210 2064.442,-209.2703 2068.9693,-208.3019 2073.4679,-207.1919"/>
<polygon fill="#000000" stroke="#000000" points="2074.4605,-210.5494 2083.2089,-204.5732 2072.6431,-203.7895 2074.4605,-210.5494"/>
<text text-anchor="middle" x="1411.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge37" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1090.6477,-94.3321C1009.2061,-77.0926 850.0614,-43.4051 773.3841,-27.1741"/>
<polygon fill="#000000" stroke="#000000" points="774.0774,-23.7434 763.5693,-25.0965 772.6277,-30.5916 774.0774,-23.7434"/>
<text text-anchor="middle" x="1011.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2383.5538,-174.0583C2379.5916,-151.4286 2369.933,-112.4106 2348.0444,-87 2327.9272,-63.6457 2316.8364,-61.9095 2287.0444,-54 2212.3314,-34.1643 1028.3292,-21.0367 776.7898,-18.4637"/>
<polygon fill="#000000" stroke="#000000" points="776.5691,-14.9614 766.534,-18.3594 776.4978,-21.961 776.5691,-14.9614"/>
<text text-anchor="middle" x="2392.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2369.0992,-206.6812C2354.1278,-218.7226 2331.1405,-235.0351 2308.0444,-243 2219.0683,-273.6843 2189.9327,-245.8328 2097.0444,-261 2088.1323,-262.4552 2078.7086,-264.4151 2069.6805,-266.5068"/>
<polygon fill="#000000" stroke="#000000" points="2068.6092,-263.1645 2059.704,-268.9045 2070.245,-269.9707 2068.6092,-263.1645"/>
<text text-anchor="middle" x="2361.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1966.0444" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1966.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1911.4798,-178.1286C1890.6773,-172.1946 1866.9524,-164.6343 1846.0444,-156 1832.9956,-150.6113 1831.6413,-144.7992 1818.0444,-141 1761.0922,-125.0866 1376.3608,-111.9729 1213.5666,-107.0698"/>
<polygon fill="#000000" stroke="#000000" points="1213.2707,-103.5595 1203.1705,-106.7588 1213.0613,-110.5563 1213.2707,-103.5595"/>
<text text-anchor="middle" x="1914.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- family_relationship -->
<g id="node23" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="639.0444" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="639.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M648.7978,-173.8888C656.0575,-162.3521 667.106,-148.2563 681.0444,-141 681.5788,-140.7218 941.5058,-120.4989 1070.3482,-110.4892"/>
<polygon fill="#000000" stroke="#000000" points="1070.8208,-113.9631 1080.5197,-109.699 1070.2786,-106.9841 1070.8208,-113.9631"/>
<text text-anchor="middle" x="760.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node24" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2269.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2269.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2232.2414,-89.504C2201.317,-77.3138 2155.6321,-61.2219 2114.0444,-54 1980.222,-30.7611 1003.733,-20.494 776.9847,-18.409"/>
<polygon fill="#000000" stroke="#000000" points="776.7917,-14.9072 766.7602,-18.3159 776.7279,-21.9069 776.7917,-14.9072"/>
<text text-anchor="middle" x="2226.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2112.1814,-173.7765C2106.8667,-162.3468 2098.3205,-148.4168 2086.0444,-141 1971.7124,-71.9247 1002.1246,-28.938 776.7248,-19.8217"/>
<polygon fill="#000000" stroke="#000000" points="776.6928,-16.3177 766.5603,-19.4132 776.4117,-23.312 776.6928,-16.3177"/>
<text text-anchor="middle" x="2067.5444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2082.1309,-204.1788C2074.8612,-206.3165 2067.2525,-208.3738 2060.0444,-210 2033.5261,-215.9828 1956.7965,-207.4118 1939.0444,-228 1934.691,-233.049 1935.3745,-237.4344 1939.0444,-243 1943.9451,-250.4321 1960.6903,-258.266 1977.9541,-264.7213"/>
<polygon fill="#000000" stroke="#000000" points="1976.9321,-268.073 1987.5266,-268.1544 1979.2953,-261.4839 1976.9321,-268.073"/>
<text text-anchor="middle" x="1979.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2081.2014,-180.3184C2049.4399,-170.4716 2008.6677,-157.7142 2005.0444,-156 1994.0126,-150.781 1993.6654,-144.7269 1982.0444,-141 1910.0067,-117.8973 1404.2916,-108.6153 1213.5876,-105.9109"/>
<polygon fill="#000000" stroke="#000000" points="1213.4339,-102.4085 1203.3859,-105.7682 1213.336,-109.4078 1213.4339,-102.4085"/>
<text text-anchor="middle" x="2045.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
</g>
</svg>
</div>
