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
<svg width="2396pt" height="305pt"
 viewBox="0.00 0.00 2396.29 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2392.2864,-301 2392.2864,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="694.2864" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="694.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="357.2864" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="357.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M670.228,-261.2073C653.2578,-249.6541 629.4995,-235.4133 606.2864,-228 524.2197,-201.7914 497.6848,-227.2839 413.2864,-210 408.9485,-209.1116 404.4736,-208.0079 400.0325,-206.7871"/>
<polygon fill="#000000" stroke="#000000" points="401.0116,-203.4269 390.4305,-203.966 399.0384,-210.143 401.0116,-203.4269"/>
<text text-anchor="middle" x="730.7864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1309.2864" cy="-192" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1309.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node24" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1198.2864" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1198.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1288.4082,-175.636C1271.4495,-162.344 1247.3102,-143.424 1228.2821,-128.5101"/>
<polygon fill="#000000" stroke="#000000" points="1230.2399,-125.5977 1220.2102,-122.1835 1225.9217,-131.1071 1230.2399,-125.5977"/>
<text text-anchor="middle" x="1299.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="417.2864" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="417.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="726.2864" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="726.2864" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M428.3479,-86.8851C436.3143,-75.5012 448.1297,-61.5815 462.2864,-54 498.9616,-34.3591 614.4367,-24.5458 679.8683,-20.4464"/>
<polygon fill="#000000" stroke="#000000" points="680.1504,-23.9358 689.9202,-19.8369 679.7267,-16.9486 680.1504,-23.9358"/>
<text text-anchor="middle" x="531.7864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="911.2864" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="911.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M889.307,-261.6C872.9501,-249.7469 849.5246,-234.9849 826.2864,-228 738.3098,-201.5561 503.7116,-226.2004 413.2864,-210 408.8698,-209.2087 404.3196,-208.1588 399.8118,-206.9624"/>
<polygon fill="#000000" stroke="#000000" points="400.658,-203.5638 390.0796,-204.1527 398.7164,-210.2892 400.658,-203.5638"/>
<text text-anchor="middle" x="924.7864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node5" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1428.2864" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1428.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1405.1048,-175.5041C1388.5534,-164.3867 1365.394,-150.1363 1343.2864,-141 1317.4683,-130.3303 1287.7092,-122.2664 1261.8949,-116.5042"/>
<polygon fill="#000000" stroke="#000000" points="1262.3557,-113.023 1251.8419,-114.3305 1260.8763,-119.8649 1262.3557,-113.023"/>
<text text-anchor="middle" x="1415.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="585.2864" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="585.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge13" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M594.0138,-86.72C600.0356,-75.852 608.9879,-62.5601 620.2864,-54 638.1769,-40.4455 661.4982,-31.7941 681.7094,-26.3804"/>
<polygon fill="#000000" stroke="#000000" points="682.7882,-29.7187 691.6459,-23.9057 681.0964,-22.9262 682.7882,-29.7187"/>
<text text-anchor="middle" x="671.2864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_arm -->
<g id="node7" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="726.2864" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="726.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M726.2864,-86.9735C726.2864,-75.1918 726.2864,-59.5607 726.2864,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="729.7865,-46.0033 726.2864,-36.0034 722.7865,-46.0034 729.7865,-46.0033"/>
<text text-anchor="middle" x="774.7864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="163.2864" cy="-105" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="163.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M319.9491,-182.0477C309.4121,-179.3348 297.9211,-176.466 287.2864,-174 248.8214,-165.0807 233.4526,-177.427 200.2864,-156 190.9145,-149.9453 183.1369,-140.619 177.1711,-131.5895"/>
<polygon fill="#000000" stroke="#000000" points="180.0055,-129.5143 171.8172,-122.7909 174.0255,-133.1531 180.0055,-129.5143"/>
<text text-anchor="middle" x="236.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node10" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="284.2864" cy="-105" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="284.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M351.2553,-173.7541C347.2449,-163.4222 341.2449,-150.6722 333.2864,-141 327.6943,-134.2038 320.5473,-128.0159 313.4514,-122.761"/>
<polygon fill="#000000" stroke="#000000" points="315.4467,-119.8854 305.241,-117.0401 311.4448,-125.6287 315.4467,-119.8854"/>
<text text-anchor="middle" x="379.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M384.4137,-177.708C409.3435,-165.3879 447.7146,-148.4442 483.2864,-141 623.2003,-111.7198 984.6708,-142.449 1126.2864,-123 1132.0107,-122.2139 1137.9388,-121.1508 1143.8237,-119.932"/>
<polygon fill="#000000" stroke="#000000" points="1144.6377,-123.3366 1153.6432,-117.7551 1143.1226,-116.5025 1144.6377,-123.3366"/>
<text text-anchor="middle" x="519.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M128.0437,-117.942C107.1233,-127.5316 87.0399,-141.4172 100.2864,-156 128.3566,-186.9019 246.1679,-166.7797 287.2864,-174 295.1074,-175.3733 303.339,-177.1676 311.3005,-179.0908"/>
<polygon fill="#000000" stroke="#000000" points="310.6379,-182.533 321.1892,-181.5737 312.3427,-175.7437 310.6379,-182.533"/>
<text text-anchor="middle" x="140.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge28" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M188.286,-89.3794C208.7142,-77.4602 238.7734,-61.8022 267.2864,-54 343.983,-33.013 578.7075,-22.903 679.5007,-19.4396"/>
<polygon fill="#000000" stroke="#000000" points="679.809,-22.9313 689.6855,-19.0967 679.5734,-15.9352 679.809,-22.9313"/>
<text text-anchor="middle" x="307.7864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M278.3406,-122.8215C275.9905,-133.2574 275.1206,-146.2568 281.2864,-156 287.8128,-166.313 298.1806,-173.7294 309.1852,-179.0412"/>
<polygon fill="#000000" stroke="#000000" points="307.9376,-182.3142 318.5085,-183.0256 310.6885,-175.8774 307.9376,-182.3142"/>
<text text-anchor="middle" x="305.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M304.7687,-92.6191C325.715,-80.5988 359.587,-62.9026 391.2864,-54 444.374,-39.0907 600.965,-26.616 679.8123,-21.0765"/>
<polygon fill="#000000" stroke="#000000" points="680.2126,-24.5572 689.946,-20.3727 679.7275,-17.574 680.2126,-24.5572"/>
<text text-anchor="middle" x="415.2864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="874.2864" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="874.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M861.2186,-86.8657C852.6249,-76.0525 840.5433,-62.7671 827.2864,-54 809.7815,-42.4236 788.1066,-34.0615 769.3294,-28.3279"/>
<polygon fill="#000000" stroke="#000000" points="770.1061,-24.909 759.5271,-25.4877 768.158,-31.6325 770.1061,-24.909"/>
<text text-anchor="middle" x="900.7864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- molecular_test -->
<g id="node12" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1579.2864" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1579.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1547.6791,-175.2201C1524.8446,-163.8218 1492.9314,-149.3521 1463.2864,-141 1399.156,-122.932 1323.6544,-113.8082 1269.681,-109.2786"/>
<polygon fill="#000000" stroke="#000000" points="1269.7716,-105.7746 1259.5224,-108.4589 1269.2085,-112.7519 1269.7716,-105.7746"/>
<text text-anchor="middle" x="1566.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1108.2864" cy="-279" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1108.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1081.4913,-263.263C1059.2396,-251.1061 1026.321,-235.1827 995.2864,-228 869.2235,-198.8237 540.7953,-232.0136 413.2864,-210 408.8649,-209.2367 404.3115,-208.2051 399.8017,-207.0199"/>
<polygon fill="#000000" stroke="#000000" points="400.6446,-203.6206 390.067,-204.2243 398.7124,-210.3486 400.6446,-203.6206"/>
<text text-anchor="middle" x="1080.7864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1119.0048,-261.195C1122.3814,-255.437 1126.0677,-248.9917 1129.2864,-243 1145.465,-212.8828 1147.9978,-204.5786 1163.2864,-174 1170.2271,-160.118 1178.0326,-144.7106 1184.5083,-131.9829"/>
<polygon fill="#000000" stroke="#000000" points="1187.7443,-133.3412 1189.1647,-122.842 1181.507,-130.1638 1187.7443,-133.3412"/>
<text text-anchor="middle" x="1207.7864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1777.2864" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1777.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1738.9358,-175.2395C1710.5878,-163.6171 1670.7442,-148.8653 1634.2864,-141 1566.836,-126.4484 1375.4921,-114.4177 1270.1039,-108.6599"/>
<polygon fill="#000000" stroke="#000000" points="1270.0441,-105.1517 1259.8694,-108.1058 1269.6655,-112.1414 1270.0441,-105.1517"/>
<text text-anchor="middle" x="1765.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="287.2864" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="287.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M301.2263,-260.9594C308.8546,-251.155 318.5136,-238.8504 327.2864,-228 330.1845,-224.4156 333.2691,-220.6546 336.3159,-216.9705"/>
<polygon fill="#000000" stroke="#000000" points="339.1354,-219.054 342.838,-209.1272 333.7531,-214.5784 339.1354,-219.054"/>
<text text-anchor="middle" x="388.2864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1040.2864" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1040.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1018.8315,-87.576C1003.6607,-76.1873 982.3498,-61.9917 961.2864,-54 927.6122,-41.2236 830.6352,-29.1363 772.3156,-22.7363"/>
<polygon fill="#000000" stroke="#000000" points="772.5697,-19.2434 762.2509,-21.6461 771.8158,-26.2027 772.5697,-19.2434"/>
<text text-anchor="middle" x="1052.2864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node17" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="527.2864" cy="-192" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="527.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M541.0746,-174.0903C551.2981,-162.3245 566.3525,-147.8801 583.2864,-141 639.2131,-118.2774 1066.5026,-131.3674 1126.2864,-123 1132.0086,-122.1991 1137.9354,-121.1265 1143.8195,-119.9019"/>
<polygon fill="#000000" stroke="#000000" points="1144.6362,-123.3059 1153.6381,-117.7187 1143.1168,-116.4727 1144.6362,-123.3059"/>
<text text-anchor="middle" x="666.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cytogenomic_file -->
<g id="node18" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="471.2864" cy="-279" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="471.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M467.2445,-260.9205C464.0028,-250.1278 458.4397,-236.8449 449.2864,-228 445.3648,-224.2106 422.6336,-215.3013 400.7496,-207.2944"/>
<polygon fill="#000000" stroke="#000000" points="401.7479,-203.9335 391.1537,-203.8186 399.3639,-210.5151 401.7479,-203.9335"/>
<text text-anchor="middle" x="530.7864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- radiology_file -->
<g id="node20" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="723.2864" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="723.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M735.8571,-174.2043C745.2437,-162.4907 759.1909,-148.062 775.2864,-141 846.8076,-109.6197 1049.039,-134.5254 1126.2864,-123 1132.0011,-122.1474 1137.9231,-121.0411 1143.8042,-119.7963"/>
<polygon fill="#000000" stroke="#000000" points="1144.6302,-123.198 1153.6196,-117.5907 1143.0955,-116.3683 1144.6302,-123.198"/>
<text text-anchor="middle" x="834.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment -->
<g id="node21" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="872.2864" cy="-192" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="872.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M882.5533,-174.161C890.2518,-162.5871 901.9149,-148.3406 916.2864,-141 957.9981,-119.6949 1080.0866,-130.7044 1126.2864,-123 1131.6878,-122.0992 1137.2802,-121.0015 1142.8513,-119.7969"/>
<polygon fill="#000000" stroke="#000000" points="1143.835,-123.1627 1152.8103,-117.5329 1142.2832,-116.3368 1143.835,-123.1627"/>
<text text-anchor="middle" x="963.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- synonym -->
<g id="node22" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="141.2864" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="141.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M164.847,-262.7046C181.6419,-251.6792 205.0883,-237.4563 227.2864,-228 235.1548,-224.6481 276.3731,-213.3995 310.3186,-204.3577"/>
<polygon fill="#000000" stroke="#000000" points="311.3532,-207.7043 320.1195,-201.7543 309.5561,-200.939 311.3532,-207.7043"/>
<text text-anchor="middle" x="269.7864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M108.0334,-264.9467C58.9312,-242.0499 -23.9666,-193.9047 7.2864,-141 32.5803,-98.1829 59.2152,-105.7225 105.2864,-87 156.5299,-66.1755 170.771,-63.3607 225.2864,-54 311.8933,-39.1289 572.6455,-25.3606 679.6701,-20.1755"/>
<polygon fill="#000000" stroke="#000000" points="680.0181,-23.6629 689.8383,-19.6864 679.6816,-16.671 680.0181,-23.6629"/>
<text text-anchor="middle" x="49.7864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M150.3165,-261.05C168.2635,-227.9263 212.0366,-158.933 273.2864,-141 364.2659,-114.3626 1032.3252,-135.5748 1126.2864,-123 1132.0951,-122.2226 1138.1127,-121.1533 1144.0814,-119.9202"/>
<polygon fill="#000000" stroke="#000000" points="1145.0296,-123.2951 1154.0348,-117.7132 1143.5142,-116.461 1145.0296,-123.2951"/>
<text text-anchor="middle" x="257.7864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- generic_file -->
<g id="node23" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1913.2864" cy="-279" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1913.2864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1850.0733,-274.0305C1716.8796,-263.7485 1397.5491,-240.0926 1129.2864,-228 970.2865,-220.8327 570.2052,-236.6239 413.2864,-210 408.8627,-209.2494 404.3078,-208.2263 399.7972,-207.0462"/>
<polygon fill="#000000" stroke="#000000" points="400.6386,-203.6465 390.0614,-204.2571 398.7108,-210.3758 400.6386,-203.6465"/>
<text text-anchor="middle" x="1440.2864" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1977.9561,-275.8053C2069.233,-269.7886 2228.7302,-253.2263 2264.2864,-210 2278.7765,-192.3841 2296.7891,-121.891 2263.2864,-87 2210.3954,-31.9172 1025.1868,-20.1828 773.1423,-18.3072"/>
<polygon fill="#000000" stroke="#000000" points="772.8905,-14.8054 762.8653,-18.2324 772.8395,-21.8052 772.8905,-14.8054"/>
<text text-anchor="middle" x="2335.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1911.8279,-260.6645C1909.3763,-238.6635 1902.9316,-201.3275 1886.2864,-174 1874.8239,-155.1813 1869.6516,-149.4136 1849.2864,-141 1797.0141,-119.4043 1429.5708,-109.5863 1270.9314,-106.3188"/>
<polygon fill="#000000" stroke="#000000" points="1270.8586,-102.8167 1260.7896,-106.113 1270.7165,-109.8152 1270.8586,-102.8167"/>
<text text-anchor="middle" x="1954.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1177.6624,-87.9215C1162.2979,-76.224 1140.2609,-61.516 1118.2864,-54 1055.5408,-32.539 862.6552,-22.9277 772.9984,-19.5334"/>
<polygon fill="#000000" stroke="#000000" points="772.971,-16.0301 762.8488,-19.1591 772.713,-23.0253 772.971,-16.0301"/>
<text text-anchor="middle" x="1198.7864" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1033.2864" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1033.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1020.8484,-173.7207C1015.3087,-163.1226 1011.578,-150.1134 1019.2864,-141 1034.8578,-122.5904 1102.6834,-127.9278 1126.2864,-123 1131.3591,-121.9409 1136.615,-120.7704 1141.8713,-119.5495"/>
<polygon fill="#000000" stroke="#000000" points="1143.0138,-122.8754 1151.9321,-117.1557 1141.3935,-116.0655 1143.0138,-122.8754"/>
<text text-anchor="middle" x="1087.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- clinical_measure_file -->
<g id="node26" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2146.2864" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2146.2864" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2141.5033,-173.8994C2137.5062,-162.5216 2130.5928,-148.6032 2119.2864,-141 1798.2903,74.8612 1638.7434,-86.519 1253.2864,-54 1075.9855,-39.042 864.7218,-26.0785 772.8201,-20.6783"/>
<polygon fill="#000000" stroke="#000000" points="772.9227,-17.1784 762.7352,-20.0879 772.5135,-24.1664 772.9227,-17.1784"/>
<text text-anchor="middle" x="2173.2864" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2063.2287,-180.348C2018.5005,-173.4074 1968.2889,-164.3506 1947.2864,-156 1935.9459,-151.491 1935.8948,-144.7662 1924.2864,-141 1863.3741,-121.2377 1442.6432,-110.1819 1270.9764,-106.4499"/>
<polygon fill="#000000" stroke="#000000" points="1270.8457,-102.9464 1260.7727,-106.2304 1270.6951,-109.9448 1270.8457,-102.9464"/>
<text text-anchor="middle" x="2033.2864" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
</g>
</svg>
</div>
