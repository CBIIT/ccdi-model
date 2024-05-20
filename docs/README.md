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
<svg width="2256pt" height="305pt"
 viewBox="0.00 0.00 2255.74 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2251.7422,-301 2251.7422,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1554.9475" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1554.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1026.9475" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1026.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1474.8777,-181.1775C1446.1333,-175.6845 1413.9259,-167.6281 1385.9475,-156 1374.678,-151.3163 1374.4435,-145.0966 1362.9475,-141 1315.8651,-124.2223 1182.6037,-113.8303 1098.7429,-108.7562"/>
<polygon fill="#000000" stroke="#000000" points="1098.7072,-105.248 1088.5173,-108.149 1098.2922,-112.2357 1098.7072,-105.248"/>
<text text-anchor="middle" x="1465.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx -->
<g id="node2" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="27.9475" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="27.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="799.9475" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="799.9475" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M22.5856,-261.2175C21.0974,-255.4607 19.6874,-249.0104 18.9475,-243 13.2036,-196.3418 18.2953,-178.2696 46.9475,-141 73.9979,-105.814 90.0796,-104.3086 130.9475,-87 190.2115,-61.9002 208.3004,-63.5536 271.9475,-54 448.4581,-27.5053 661.1249,-20.4909 753.4326,-18.6486"/>
<polygon fill="#000000" stroke="#000000" points="753.6276,-22.1456 763.5599,-18.4578 753.4957,-15.1469 753.6276,-22.1456"/>
<text text-anchor="middle" x="70.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node24" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="194.9475" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="194.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M51.0647,-268.8091C65.8884,-262.0186 85.3872,-252.6053 101.9475,-243 112.1844,-237.0624 113.7599,-234.0218 123.9475,-228 134.3456,-221.8538 145.9193,-215.7083 156.6538,-210.2793"/>
<polygon fill="#000000" stroke="#000000" points="158.4316,-213.3039 165.8206,-205.7109 155.3093,-207.0389 158.4316,-213.3039"/>
<text text-anchor="middle" x="147.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- molecular_test -->
<g id="node3" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1752.9475" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1752.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1693.6076,-179.8766C1683.7078,-177.8891 1673.5409,-175.8694 1663.9475,-174 1621.3388,-165.6971 1608.2348,-172.1672 1567.9475,-156 1556.6214,-151.4549 1556.5179,-144.8812 1544.9475,-141 1503.8195,-127.2041 1231.6895,-113.8018 1099.188,-108.0008"/>
<polygon fill="#000000" stroke="#000000" points="1099.2657,-104.5009 1089.123,-107.563 1098.9615,-111.4943 1099.2657,-104.5009"/>
<text text-anchor="middle" x="1631.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="330.9475" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="330.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M355.417,-174.783C373.8599,-162.8536 400.2821,-147.9188 425.9475,-141 539.7313,-110.3266 839.2733,-139.5752 955.9475,-123 961.3769,-122.2287 966.9919,-121.2064 972.5759,-120.0397"/>
<polygon fill="#000000" stroke="#000000" points="973.5535,-123.4075 982.5467,-117.8064 972.0235,-116.5767 973.5535,-123.4075"/>
<text text-anchor="middle" x="484.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="209.9475" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="209.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M237.0549,-88.1151C257.4039,-76.3509 286.3881,-61.4772 313.9475,-54 395.851,-31.7788 647.8339,-22.2772 753.0406,-19.2058"/>
<polygon fill="#000000" stroke="#000000" points="753.4517,-22.6956 763.3479,-18.9119 753.2521,-15.6985 753.4517,-22.6956"/>
<text text-anchor="middle" x="370.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="159.9475" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="159.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M167.1995,-260.9735C172.0332,-248.9585 178.4774,-232.9401 183.9388,-219.3646"/>
<polygon fill="#000000" stroke="#000000" points="187.2195,-220.5871 187.7048,-210.0034 180.7254,-217.9744 187.2195,-220.5871"/>
<text text-anchor="middle" x="246.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node7" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="347.9475" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="347.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M377.9394,-90.6203C403.8246,-78.8508 442.5286,-62.7652 477.9475,-54 573.8962,-30.2554 689.8346,-22.1461 753.1155,-19.3952"/>
<polygon fill="#000000" stroke="#000000" points="753.3333,-22.8893 763.182,-18.9838 753.0474,-15.8952 753.3333,-22.8893"/>
<text text-anchor="middle" x="518.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M311.728,-117.288C304.2636,-119.4693 296.4046,-121.5151 288.9475,-123 248.4376,-131.0665 131.7045,-110.4112 103.9475,-141 86.9995,-159.677 115.4179,-173.1258 144.8613,-181.5076"/>
<polygon fill="#000000" stroke="#000000" points="144.2581,-184.9688 154.8217,-184.1561 146.057,-178.2038 144.2581,-184.9688"/>
<text text-anchor="middle" x="144.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_funding -->
<g id="node8" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="533.9475" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="533.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M546.415,-87.0184C555.2679,-75.6907 568.1736,-61.7837 582.9475,-54 611.8315,-38.7824 698.9321,-27.8334 753.5999,-22.2393"/>
<polygon fill="#000000" stroke="#000000" points="754.1395,-25.7028 763.7413,-21.2247 753.4426,-18.7376 754.1395,-25.7028"/>
<text text-anchor="middle" x="644.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node9" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="526.9475" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="526.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M535.1479,-174.0378C541.4992,-162.4089 551.4902,-148.1473 564.9475,-141 603.3569,-120.6005 912.927,-129.3764 955.9475,-123 961.3722,-122.196 966.984,-121.152 972.566,-119.9718"/>
<polygon fill="#000000" stroke="#000000" points="973.5501,-123.3378 982.5346,-117.7227 972.0094,-116.5095 973.5501,-123.3378"/>
<text text-anchor="middle" x="647.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment -->
<g id="node10" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="706.9475" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="706.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M718.5221,-174.1583C727.0876,-162.5831 739.8569,-148.3362 754.9475,-141 795.2795,-121.3928 911.7395,-130.5341 955.9475,-123 961.0656,-122.1278 966.357,-121.0759 971.6364,-119.9239"/>
<polygon fill="#000000" stroke="#000000" points="972.763,-123.2564 981.7253,-117.606 971.1955,-116.4341 972.763,-123.2564"/>
<text text-anchor="middle" x="801.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="715.9475" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="715.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M711.2683,-86.5961C709.7086,-76.2115 709.7086,-63.4615 715.9475,-54 724.9035,-40.4179 740.1615,-31.9406 755.2362,-26.6577"/>
<polygon fill="#000000" stroke="#000000" points="756.5269,-29.9223 765.0479,-23.6259 754.4603,-23.2343 756.5269,-29.9223"/>
<text text-anchor="middle" x="785.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="883.9475" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="883.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge5" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M878.0178,-86.9813C873.8969,-76.4755 867.5851,-63.472 858.9475,-54 852.4162,-46.8377 844.132,-40.6109 835.8515,-35.4424"/>
<polygon fill="#000000" stroke="#000000" points="837.3531,-32.2665 826.9509,-30.2552 833.8284,-38.3144 837.3531,-32.2665"/>
<text text-anchor="middle" x="919.9475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="830.9475" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="830.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M839.4723,-174.1998C845.7817,-162.9488 855.4425,-149.0589 867.9475,-141 901.5038,-119.3746 917.0331,-131.9076 955.9475,-123 960.6579,-121.9218 965.5343,-120.767 970.4236,-119.5823"/>
<polygon fill="#000000" stroke="#000000" points="971.5532,-122.9089 980.4287,-117.1231 969.8823,-116.1112 971.5532,-122.9089"/>
<text text-anchor="middle" x="907.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="534.9475" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="534.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M520.8374,-261.0758C510.5737,-249.4638 495.6018,-235.2069 478.9475,-228 431.8965,-207.6395 299.1937,-220.1815 248.9475,-210 245.081,-209.2165 241.1072,-208.2396 237.1535,-207.1488"/>
<polygon fill="#000000" stroke="#000000" points="238.0236,-203.7559 227.4401,-204.2475 236.0201,-210.4631 238.0236,-203.7559"/>
<text text-anchor="middle" x="562.9475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1013.3878,-87.2154C1003.8541,-75.971 990.127,-62.0827 974.9475,-54 952.9129,-42.2671 889.4033,-31.0564 845.2853,-24.3497"/>
<polygon fill="#000000" stroke="#000000" points="845.7648,-20.8826 835.3573,-22.8663 844.7303,-27.8057 845.7648,-20.8826"/>
<text text-anchor="middle" x="1045.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation_array_file -->
<g id="node16" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="744.9475" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="744.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M713.2584,-261.418C690.3168,-249.6417 658.1576,-235.0499 627.9475,-228 463.7256,-189.6765 414.7166,-240.9541 248.9475,-210 245.0694,-209.2758 241.0877,-208.3398 237.1289,-207.2756"/>
<polygon fill="#000000" stroke="#000000" points="237.9891,-203.8804 227.4077,-204.4138 236.0123,-210.5955 237.9891,-203.8804"/>
<text text-anchor="middle" x="763.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- medical_history -->
<g id="node17" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="981.9475" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="981.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M961.8422,-174.3195C953.06,-164.4049 946.1412,-151.8802 952.9475,-141 957.6855,-133.4261 964.524,-127.4044 972.1542,-122.6284"/>
<polygon fill="#000000" stroke="#000000" points="974.3011,-125.4436 981.3966,-117.5757 970.9433,-119.3015 974.3011,-125.4436"/>
<text text-anchor="middle" x="1020.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- diagnosis -->
<g id="node19" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1050.9475" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1050.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1063.9899,-261.3497C1082.4694,-233.9948 1111.6367,-180.411 1088.9475,-141 1085.2758,-134.6222 1079.9929,-129.2701 1074.039,-124.8102"/>
<polygon fill="#000000" stroke="#000000" points="1075.8735,-121.8278 1065.5923,-119.2688 1072.0338,-127.6807 1075.8735,-121.8278"/>
<text text-anchor="middle" x="1141.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1012.5135,-265.9852C974.1363,-253.6604 913.2134,-235.9 858.9475,-228 590.5477,-188.9263 516.0045,-257.3901 248.9475,-210 245.0099,-209.3013 240.9677,-208.3736 236.9525,-207.3069"/>
<polygon fill="#000000" stroke="#000000" points="237.6828,-203.8738 227.1021,-204.42 235.7141,-210.5912 237.6828,-203.8738"/>
<text text-anchor="middle" x="973.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1958.9475" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1958.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1879.3447,-179.6732C1866.832,-177.7587 1854.0402,-175.815 1841.9475,-174 1787.3106,-165.7994 1770.6235,-175.5458 1718.9475,-156 1707.5327,-151.6825 1707.5479,-144.7906 1695.9475,-141 1640.5025,-122.8823 1261.1871,-111.0541 1099.599,-106.7829"/>
<polygon fill="#000000" stroke="#000000" points="1099.3643,-103.2756 1089.276,-106.5125 1099.1809,-110.2732 1099.3643,-103.2756"/>
<text text-anchor="middle" x="1804.9475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1940.7084,-174.0203C1927.8916,-162.5407 1909.7382,-148.4592 1890.9475,-141 1695.8705,-63.562 1029.0457,-28.3322 846.4823,-19.998"/>
<polygon fill="#000000" stroke="#000000" points="846.5525,-16.4977 836.4047,-19.5429 846.2366,-23.4906 846.5525,-16.4977"/>
<text text-anchor="middle" x="1912.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node21" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="350.9475" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="350.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M343.0448,-260.9429C337.3183,-249.8789 328.5465,-236.2943 316.9475,-228 291.5174,-209.8151 278.9029,-218.9476 248.9475,-210 245.5787,-208.9938 242.1033,-207.9195 238.616,-206.8157"/>
<polygon fill="#000000" stroke="#000000" points="239.4267,-203.3996 228.835,-203.6581 237.2761,-210.0611 239.4267,-203.3996"/>
<text text-anchor="middle" x="403.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1262.9475" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1262.9475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1226.8473,-178.6919C1186.3077,-163.7472 1120.3192,-139.4209 1075.3368,-122.8384"/>
<polygon fill="#000000" stroke="#000000" points="1076.386,-119.495 1065.7926,-119.32 1073.9647,-126.0629 1076.386,-119.495"/>
<text text-anchor="middle" x="1202.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1351.9475" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1351.9475" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1351.9199,-260.8724C1350.9447,-238.0464 1346.024,-198.8212 1324.9475,-174 1295.9169,-139.8114 1175.4555,-120.6992 1096.8597,-111.6526"/>
<polygon fill="#000000" stroke="#000000" points="1096.8665,-108.1315 1086.5385,-110.4945 1096.0859,-115.0878 1096.8665,-108.1315"/>
<text text-anchor="middle" x="1385.4475" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1403.9986,-277.9985C1562.5959,-274.4143 2031.784,-259.6659 2076.9475,-210 2087.7119,-198.1625 2082.4701,-189.0167 2076.9475,-174 2059.4263,-126.3576 2048.3832,-109.636 2002.9475,-87 1898.0464,-34.7383 1054.9946,-21.1006 846.4668,-18.5129"/>
<polygon fill="#000000" stroke="#000000" points="846.4968,-15.0131 836.4549,-18.3912 846.4116,-22.0126 846.4968,-15.0131"/>
<text text-anchor="middle" x="2111.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1306.5346,-270.0636C1243.1196,-258.0245 1124.3022,-237.0622 1021.9475,-228 850.7927,-212.8464 418.2213,-239.4957 248.9475,-210 245.0077,-209.3135 240.9641,-208.3942 236.9479,-207.3329"/>
<polygon fill="#000000" stroke="#000000" points="237.6764,-203.8995 227.0961,-204.454 235.7129,-210.6185 237.6764,-203.8995"/>
<text text-anchor="middle" x="1182.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M151.1874,-195.4529C107.3397,-199.9201 44.2167,-209.4399 28.9475,-228 23.7256,-234.3474 22.1587,-242.7958 22.2828,-250.9875"/>
<polygon fill="#000000" stroke="#000000" points="18.8064,-251.4066 23.1967,-261.0489 25.7777,-250.7733 18.8064,-251.4066"/>
<text text-anchor="middle" x="65.4475" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M189.7061,-174.0353C187.7335,-163.2858 187.5008,-150.008 194.9475,-141 222.05,-108.2153 247.6569,-133.2209 288.9475,-123 292.9822,-122.0013 297.1497,-120.8916 301.3169,-119.7277"/>
<polygon fill="#000000" stroke="#000000" points="302.34,-123.0753 310.9775,-116.9398 300.3991,-116.3498 302.34,-123.0753"/>
<text text-anchor="middle" x="231.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M223.5679,-178.256C252.7045,-164.5346 296.0562,-144.9344 313.9475,-141 453.3396,-110.3468 814.5848,-142.6559 955.9475,-123 961.3792,-122.2447 966.9957,-121.2332 972.5806,-120.073"/>
<polygon fill="#000000" stroke="#000000" points="973.555,-123.4417 982.5525,-117.8476 972.0302,-116.6098 973.555,-123.4417"/>
<text text-anchor="middle" x="350.4475" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node25" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2187.9475" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2187.9475" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2169.5242,-87.7557C2155.4749,-75.8128 2135.0105,-60.873 2113.9475,-54 2052.615,-33.9869 1074.1212,-21.2378 846.8443,-18.5376"/>
<polygon fill="#000000" stroke="#000000" points="846.6368,-15.035 836.5961,-18.4166 846.5541,-22.0345 846.6368,-15.035"/>
<text text-anchor="middle" x="2190.4475" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
