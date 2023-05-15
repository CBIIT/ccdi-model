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
<svg width="2490pt" height="305pt"
 viewBox="0.00 0.00 2490.37 305.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 301)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-301 2486.372,-301 2486.372,4 -4,4"/>
<!-- single_cell_sequencing_file -->
<g id="node1" class="node">
<title>single_cell_sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2340.372" cy="-279" rx="137.5759" ry="18"/>
<text text-anchor="middle" x="2340.372" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">single_cell_sequencing_file</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1884.372" cy="-192" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1884.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- single_cell_sequencing_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>single_cell_sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2307.2577,-261.4725C2284.121,-250.0376 2252.1586,-235.8293 2222.372,-228 2170.1021,-214.261 2019.5976,-201.7529 1938.1892,-195.7476"/>
<polygon fill="#000000" stroke="#000000" points="1938.3644,-192.2512 1928.1359,-195.0132 1937.8543,-199.2326 1938.3644,-192.2512"/>
<text text-anchor="middle" x="2373.872" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_single_cell_sequencing_file</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="787.372" cy="-105" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="787.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1864.9636,-175.691C1849.213,-163.5575 1825.8425,-147.9463 1802.372,-141 1701.8838,-111.2596 963.2568,-136.7964 859.372,-123 853.5625,-122.2285 847.5445,-121.1629 841.5755,-119.9321"/>
<polygon fill="#000000" stroke="#000000" points="842.1421,-116.4728 831.6218,-117.7275 840.6283,-123.3072 842.1421,-116.4728"/>
<text text-anchor="middle" x="1870.872" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node3" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="93.372" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="93.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="465.372" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="465.372" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M96.0687,-86.7719C98.7394,-75.492 104.0128,-61.7322 114.372,-54 138.2775,-36.1568 329.0163,-24.6247 418.8651,-20.13"/>
<polygon fill="#000000" stroke="#000000" points="419.2304,-23.6163 429.0464,-19.6292 418.8865,-16.6248 419.2304,-23.6163"/>
<text text-anchor="middle" x="170.872" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1552.372" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1552.372" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1574.5142,-267.7928C1579.3691,-265.4581 1584.5113,-263.0776 1589.372,-261 1628.1642,-244.4192 1637.3552,-237.8677 1678.372,-228 1744.9417,-211.9849 1764.5872,-225.0926 1831.372,-210 1834.9472,-209.1921 1838.6195,-208.2314 1842.2825,-207.1807"/>
<polygon fill="#000000" stroke="#000000" points="1843.3527,-210.5134 1851.8844,-204.2316 1841.2975,-203.8219 1843.3527,-210.5134"/>
<text text-anchor="middle" x="1702.372" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="241.372" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="241.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M233.6174,-86.9772C230.3079,-76.2059 228.7401,-62.9255 236.372,-54 248.0785,-40.3095 355.4124,-28.1607 418.8944,-22.0931"/>
<polygon fill="#000000" stroke="#000000" points="419.4363,-25.5576 429.0648,-21.137 418.7811,-18.5884 419.4363,-25.5576"/>
<text text-anchor="middle" x="284.872" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="512.372" cy="-192" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="512.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M532.0461,-174.95C546.2227,-163.5785 566.3154,-149.2521 586.372,-141 610.1694,-131.2088 671.6152,-120.9454 720.3568,-113.8941"/>
<polygon fill="#000000" stroke="#000000" points="721.1418,-117.3176 730.5468,-112.4395 720.1525,-110.3878 721.1418,-117.3176"/>
<text text-anchor="middle" x="630.872" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="658.372" cy="-192" rx="73.387" ry="18"/>
<text text-anchor="middle" x="658.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M667.2165,-173.8714C673.2822,-163.0603 682.2398,-149.7752 693.372,-141 704.3052,-132.3817 717.5367,-125.6411 730.5772,-120.4441"/>
<polygon fill="#000000" stroke="#000000" points="731.8572,-123.7022 740.0033,-116.9279 729.4107,-117.1437 731.8572,-123.7022"/>
<text text-anchor="middle" x="752.372" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M750.3,-90.4982C721.0473,-79.4347 679.0336,-64.3791 641.372,-54 597.3129,-41.8578 546.0273,-31.8208 510.224,-25.4573"/>
<polygon fill="#000000" stroke="#000000" points="510.5499,-21.9612 500.0957,-23.6818 509.3411,-28.856 510.5499,-21.9612"/>
<text text-anchor="middle" x="740.872" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_measure_file -->
<g id="node9" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="208.372" cy="-192" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="208.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M215.005,-173.8356C220.2617,-162.2757 228.8309,-148.1741 241.372,-141 282.0128,-117.7516 615.7533,-127.3421 662.372,-123 682.1707,-121.1559 703.6292,-118.3594 723.0869,-115.5167"/>
<polygon fill="#000000" stroke="#000000" points="723.6852,-118.9662 733.0602,-114.0307 722.6535,-112.0427 723.6852,-118.9662"/>
<text text-anchor="middle" x="370.872" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M208.8158,-173.5242C210.0777,-162.5825 213.5233,-149.282 222.372,-141 251.5184,-113.7205 275.216,-141.9138 310.372,-123 330.2987,-112.2795 328.4333,-100.7914 346.372,-87 372.7295,-66.7363 405.6117,-48.1065 430.1276,-35.3262"/>
<polygon fill="#000000" stroke="#000000" points="431.789,-38.4075 439.0829,-30.7231 428.5889,-32.1818 431.789,-38.4075"/>
<text text-anchor="middle" x="432.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1674.372" cy="-279" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1674.372" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1698.3151,-261.7547C1714.5767,-250.7381 1736.9445,-236.9008 1758.372,-228 1789.2317,-215.1812 1799.2998,-219.3816 1831.372,-210 1834.5431,-209.0724 1837.8068,-208.0737 1841.0825,-207.0391"/>
<polygon fill="#000000" stroke="#000000" points="1842.4346,-210.2801 1850.8651,-203.8631 1840.273,-203.6222 1842.4346,-210.2801"/>
<text text-anchor="middle" x="1819.372" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="850.372" cy="-192" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="850.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M837.3184,-173.9735C828.3047,-161.5261 816.1797,-144.782 806.1335,-130.9087"/>
<polygon fill="#000000" stroke="#000000" points="808.8933,-128.7523 800.1934,-122.7057 803.2237,-132.8579 808.8933,-128.7523"/>
<text text-anchor="middle" x="902.872" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- follow_up -->
<g id="node12" class="node">
<title>follow_up</title>
<ellipse fill="none" stroke="#000000" cx="1023.372" cy="-192" rx="55.4913" ry="18"/>
<text text-anchor="middle" x="1023.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1015.0053,-173.9461C1008.7627,-162.5879 999.1169,-148.674 986.372,-141 937.5335,-111.5931 915.3234,-133.9281 859.372,-123 854.0766,-121.9657 848.5871,-120.7882 843.1087,-119.542"/>
<polygon fill="#000000" stroke="#000000" points="843.8391,-116.1183 833.3039,-117.2406 842.2395,-122.9331 843.8391,-116.1183"/>
<text text-anchor="middle" x="1048.372" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1884.372" cy="-279" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1884.372" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1884.372,-260.9735C1884.372,-249.1918 1884.372,-233.5607 1884.372,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1887.8721,-220.0033 1884.372,-210.0034 1880.8721,-220.0034 1887.8721,-220.0033"/>
<text text-anchor="middle" x="1975.872" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="590.372" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="590.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M566.2708,-88.2255C545.8532,-74.0149 516.5092,-53.5915 494.7251,-38.4297"/>
<polygon fill="#000000" stroke="#000000" points="496.6954,-35.5368 486.4882,-32.6968 492.6965,-41.2822 496.6954,-35.5368"/>
<text text-anchor="middle" x="586.372" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="354.372" cy="-279" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="354.372" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M405.986,-276.7867C663.1918,-265.733 1795.6072,-216.7686 1831.372,-210 1835.0242,-209.3088 1838.7682,-208.4223 1842.495,-207.4144"/>
<polygon fill="#000000" stroke="#000000" points="1843.6588,-210.7198 1852.2453,-204.5131 1841.6624,-204.0105 1843.6588,-210.7198"/>
<text text-anchor="middle" x="1537.872" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M349.8604,-261.0679C345.1663,-237.7132 341.2485,-197.1453 363.372,-174 384.5891,-151.8031 470.2549,-161.9852 500.372,-156 525.6441,-150.9776 531.162,-146.3248 556.372,-141 586.9979,-134.5313 664.5734,-122.7893 721.4072,-114.4764"/>
<polygon fill="#000000" stroke="#000000" points="722.0153,-117.9248 731.4054,-113.018 721.0049,-110.9981 722.0153,-117.9248"/>
<text text-anchor="middle" x="405.872" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M305.8715,-272.1905C194.7039,-254.4823 -63.1651,-200.2782 14.372,-87 37.2621,-53.5587 59.9533,-63.4038 99.372,-54 158.9164,-39.795 334.6034,-26.6722 419.0366,-20.9802"/>
<polygon fill="#000000" stroke="#000000" points="419.3658,-24.4661 429.1102,-20.3072 418.8991,-17.4816 419.3658,-24.4661"/>
<text text-anchor="middle" x="49.872" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node17" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1181.372" cy="-192" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1181.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1159.2696,-174.5716C1143.1044,-162.8677 1120.1144,-148.2993 1097.372,-141 996.3671,-108.5818 964.093,-139.9248 859.372,-123 853.8867,-122.1135 848.2062,-121.0148 842.5521,-119.8007"/>
<polygon fill="#000000" stroke="#000000" points="842.9771,-116.3083 832.4508,-117.5114 841.4298,-123.1352 842.9771,-116.3083"/>
<text text-anchor="middle" x="1197.372" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="945.372" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="945.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M906.8768,-89.2998C876.9645,-77.7437 834.1754,-62.6039 795.372,-54 695.9714,-31.9599 576.6055,-23.195 512.1684,-19.8792"/>
<polygon fill="#000000" stroke="#000000" points="512.0906,-16.3712 501.9304,-19.3747 511.746,-23.3627 512.0906,-16.3712"/>
<text text-anchor="middle" x="908.372" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node19" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2101.372" cy="-279" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2101.372" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2095.1947,-260.9494C2090.425,-249.7423 2082.7019,-235.9969 2071.372,-228 2050.234,-213.0801 1985.0431,-202.9473 1937.5676,-197.325"/>
<polygon fill="#000000" stroke="#000000" points="1937.7617,-193.8243 1927.4275,-196.1601 1936.9627,-200.7786 1937.7617,-193.8243"/>
<text text-anchor="middle" x="2151.872" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- molecular_test -->
<g id="node20" class="node">
<title>molecular_test</title>
<ellipse fill="none" stroke="#000000" cx="1364.372" cy="-192" rx="79.8859" ry="18"/>
<text text-anchor="middle" x="1364.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1339.8819,-174.8587C1321.4288,-162.967 1295.0028,-148.0461 1269.372,-141 1181.4355,-116.8256 949.6214,-136.1258 859.372,-123 853.6542,-122.1684 847.7303,-121.0758 841.8479,-119.8392"/>
<polygon fill="#000000" stroke="#000000" points="842.5541,-116.4108 832.0312,-117.6427 841.0256,-123.2419 842.5541,-116.4108"/>
<text text-anchor="middle" x="1369.372" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1515.372" cy="-192" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1515.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1496.0953,-175.0243C1481.1921,-163.0489 1459.44,-147.95 1437.372,-141 1376.0862,-121.6988 923.0141,-131.8424 859.372,-123 853.649,-122.2049 847.7217,-121.1359 841.8373,-119.9136"/>
<polygon fill="#000000" stroke="#000000" points="842.5394,-116.4843 832.0184,-117.7328 841.0216,-123.3178 842.5394,-116.4843"/>
<text text-anchor="middle" x="1510.872" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- therapeutic_procedure -->
<g id="node22" class="node">
<title>therapeutic_procedure</title>
<ellipse fill="none" stroke="#000000" cx="1704.372" cy="-192" rx="117.7793" ry="18"/>
<text text-anchor="middle" x="1704.372" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1665.9172,-174.8738C1636.9823,-162.9062 1596.0078,-147.8837 1558.372,-141 1405.5229,-113.0432 1013.3355,-143.969 859.372,-123 853.6469,-122.2203 847.7182,-121.1614 841.833,-119.9451"/>
<polygon fill="#000000" stroke="#000000" points="842.5333,-116.5154 832.0131,-117.771 841.0201,-123.3499 842.5333,-116.5154"/>
<text text-anchor="middle" x="1705.372" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_personnel -->
<g id="node23" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1127.372" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1127.372" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1088.1658,-88.8916C1057.6865,-77.1188 1014.055,-61.8864 974.372,-54 886.6038,-36.5573 620.3757,-24.2251 512.0099,-19.8001"/>
<polygon fill="#000000" stroke="#000000" points="511.855,-16.2911 501.7219,-19.3845 511.5724,-23.2854 511.855,-16.2911"/>
<text text-anchor="middle" x="1099.872" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
