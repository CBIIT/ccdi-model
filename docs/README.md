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
<svg width="3242pt" height="1758pt"
 viewBox="0.00 0.00 3242.00 1758.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1754)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1754 3238,-1754 3238,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M1059,-333.5C1059,-333.5 1269,-333.5 1269,-333.5 1275,-333.5 1281,-339.5 1281,-345.5 1281,-345.5 1281,-357.5 1281,-357.5 1281,-363.5 1275,-369.5 1269,-369.5 1269,-369.5 1059,-369.5 1059,-369.5 1053,-369.5 1047,-363.5 1047,-357.5 1047,-357.5 1047,-345.5 1047,-345.5 1047,-339.5 1053,-333.5 1059,-333.5"/>
<text text-anchor="middle" x="1095.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="1144,-333.5 1144,-369.5 "/>
<text text-anchor="middle" x="1154.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1165,-333.5 1165,-369.5 "/>
<text text-anchor="middle" x="1212.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="1260,-333.5 1260,-369.5 "/>
<text text-anchor="middle" x="1270.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2032,-.5C2032,-.5 2422,-.5 2422,-.5 2428,-.5 2434,-6.5 2434,-12.5 2434,-12.5 2434,-195.5 2434,-195.5 2434,-201.5 2428,-207.5 2422,-207.5 2422,-207.5 2032,-207.5 2032,-207.5 2026,-207.5 2020,-201.5 2020,-195.5 2020,-195.5 2020,-12.5 2020,-12.5 2020,-6.5 2026,-.5 2032,-.5"/>
<text text-anchor="middle" x="2048" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2076,-.5 2076,-207.5 "/>
<text text-anchor="middle" x="2086.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2097,-.5 2097,-207.5 "/>
<text text-anchor="middle" x="2255" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2097,-184.5 2413,-184.5 "/>
<text text-anchor="middle" x="2255" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2097,-161.5 2413,-161.5 "/>
<text text-anchor="middle" x="2255" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2097,-138.5 2413,-138.5 "/>
<text text-anchor="middle" x="2255" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2097,-115.5 2413,-115.5 "/>
<text text-anchor="middle" x="2255" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2097,-92.5 2413,-92.5 "/>
<text text-anchor="middle" x="2255" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2097,-69.5 2413,-69.5 "/>
<text text-anchor="middle" x="2255" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2097,-46.5 2413,-46.5 "/>
<text text-anchor="middle" x="2255" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2097,-23.5 2413,-23.5 "/>
<text text-anchor="middle" x="2255" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2413,-.5 2413,-207.5 "/>
<text text-anchor="middle" x="2423.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1162.2943,-333.3668C1160.7983,-305.7047 1162.5209,-253.3079 1193,-226 1252.6022,-172.5991 1724.5306,-134.6992 2009.8125,-116.4079"/>
<polygon fill="#000000" stroke="#000000" points="2010.1243,-119.8953 2019.8811,-115.7655 2009.6785,-112.9095 2010.1243,-119.8953"/>
<text text-anchor="middle" x="1244" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1174,-812C1174,-812 1488,-812 1488,-812 1494,-812 1500,-818 1500,-824 1500,-824 1500,-961 1500,-961 1500,-967 1494,-973 1488,-973 1488,-973 1174,-973 1174,-973 1168,-973 1162,-967 1162,-961 1162,-961 1162,-824 1162,-824 1162,-818 1168,-812 1174,-812"/>
<text text-anchor="middle" x="1196" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1230,-812 1230,-973 "/>
<text text-anchor="middle" x="1240.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1251,-812 1251,-973 "/>
<text text-anchor="middle" x="1365" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1251,-950 1479,-950 "/>
<text text-anchor="middle" x="1365" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1251,-927 1479,-927 "/>
<text text-anchor="middle" x="1365" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1251,-904 1479,-904 "/>
<text text-anchor="middle" x="1365" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1251,-881 1479,-881 "/>
<text text-anchor="middle" x="1365" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1251,-858 1479,-858 "/>
<text text-anchor="middle" x="1365" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1251,-835 1479,-835 "/>
<text text-anchor="middle" x="1365" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1479,-812 1479,-973 "/>
<text text-anchor="middle" x="1489.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1324.9048,-811.8243C1313.5354,-650.5589 1293.2362,-300.2705 1328,-259 1371.611,-207.2264 1757.9301,-155.4746 2009.7612,-126.8068"/>
<polygon fill="#000000" stroke="#000000" points="2010.2395,-130.2751 2019.7812,-125.6702 2009.4505,-123.3197 2010.2395,-130.2751"/>
<text text-anchor="middle" x="1345.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2048,-495.5C2048,-495.5 2352,-495.5 2352,-495.5 2358,-495.5 2364,-501.5 2364,-507.5 2364,-507.5 2364,-598.5 2364,-598.5 2364,-604.5 2358,-610.5 2352,-610.5 2352,-610.5 2048,-610.5 2048,-610.5 2042,-610.5 2036,-604.5 2036,-598.5 2036,-598.5 2036,-507.5 2036,-507.5 2036,-501.5 2042,-495.5 2048,-495.5"/>
<text text-anchor="middle" x="2084" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2132,-495.5 2132,-610.5 "/>
<text text-anchor="middle" x="2142.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2153,-495.5 2153,-610.5 "/>
<text text-anchor="middle" x="2248" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="2153,-587.5 2343,-587.5 "/>
<text text-anchor="middle" x="2248" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2153,-564.5 2343,-564.5 "/>
<text text-anchor="middle" x="2248" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2153,-541.5 2343,-541.5 "/>
<text text-anchor="middle" x="2248" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2153,-518.5 2343,-518.5 "/>
<text text-anchor="middle" x="2248" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2343,-495.5 2343,-610.5 "/>
<text text-anchor="middle" x="2353.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1459.2735,-811.9083C1541.7646,-762.9393 1652.6721,-702.2986 1757,-662 1843.3493,-628.646 1943.1872,-603.0283 2026.2006,-585.035"/>
<polygon fill="#000000" stroke="#000000" points="2026.9385,-588.4564 2035.98,-582.9335 2025.4679,-581.6126 2026.9385,-588.4564"/>
<text text-anchor="middle" x="1888.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M1349.5,-294C1349.5,-294 1656.5,-294 1656.5,-294 1662.5,-294 1668.5,-300 1668.5,-306 1668.5,-306 1668.5,-397 1668.5,-397 1668.5,-403 1662.5,-409 1656.5,-409 1656.5,-409 1349.5,-409 1349.5,-409 1343.5,-409 1337.5,-403 1337.5,-397 1337.5,-397 1337.5,-306 1337.5,-306 1337.5,-300 1343.5,-294 1349.5,-294"/>
<text text-anchor="middle" x="1404.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="1471.5,-294 1471.5,-409 "/>
<text text-anchor="middle" x="1482" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1492.5,-294 1492.5,-409 "/>
<text text-anchor="middle" x="1570" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="1492.5,-386 1647.5,-386 "/>
<text text-anchor="middle" x="1570" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1492.5,-363 1647.5,-363 "/>
<text text-anchor="middle" x="1570" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="1492.5,-340 1647.5,-340 "/>
<text text-anchor="middle" x="1570" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="1492.5,-317 1647.5,-317 "/>
<text text-anchor="middle" x="1570" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="1647.5,-294 1647.5,-409 "/>
<text text-anchor="middle" x="1658" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1602.465,-293.9441C1626.4079,-281.4086 1652.2349,-268.939 1677,-259 1784.0286,-216.046 1907.2681,-180.1407 2009.9254,-153.7399"/>
<polygon fill="#000000" stroke="#000000" points="2010.9742,-157.0844 2019.7945,-151.2147 2009.239,-150.3028 2010.9742,-157.0844"/>
<text text-anchor="middle" x="1834.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M388.5,-1358.5C388.5,-1358.5 717.5,-1358.5 717.5,-1358.5 723.5,-1358.5 729.5,-1364.5 729.5,-1370.5 729.5,-1370.5 729.5,-1553.5 729.5,-1553.5 729.5,-1559.5 723.5,-1565.5 717.5,-1565.5 717.5,-1565.5 388.5,-1565.5 388.5,-1565.5 382.5,-1565.5 376.5,-1559.5 376.5,-1553.5 376.5,-1553.5 376.5,-1370.5 376.5,-1370.5 376.5,-1364.5 382.5,-1358.5 388.5,-1358.5"/>
<text text-anchor="middle" x="398" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="419.5,-1358.5 419.5,-1565.5 "/>
<text text-anchor="middle" x="430" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="440.5,-1358.5 440.5,-1565.5 "/>
<text text-anchor="middle" x="574.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="440.5,-1542.5 708.5,-1542.5 "/>
<text text-anchor="middle" x="574.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="440.5,-1519.5 708.5,-1519.5 "/>
<text text-anchor="middle" x="574.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="440.5,-1496.5 708.5,-1496.5 "/>
<text text-anchor="middle" x="574.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="440.5,-1473.5 708.5,-1473.5 "/>
<text text-anchor="middle" x="574.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="440.5,-1450.5 708.5,-1450.5 "/>
<text text-anchor="middle" x="574.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="440.5,-1427.5 708.5,-1427.5 "/>
<text text-anchor="middle" x="574.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="440.5,-1404.5 708.5,-1404.5 "/>
<text text-anchor="middle" x="574.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="440.5,-1381.5 708.5,-1381.5 "/>
<text text-anchor="middle" x="574.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="708.5,-1358.5 708.5,-1565.5 "/>
<text text-anchor="middle" x="719" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M601.1781,-1358.4594C633.1958,-1298.4987 679.9961,-1225.0284 738,-1174 858.5008,-1067.9906 1025.8831,-993.4259 1152.0983,-947.7911"/>
<polygon fill="#000000" stroke="#000000" points="1153.6465,-950.9543 1161.8775,-944.2834 1151.283,-944.3653 1153.6465,-950.9543"/>
<text text-anchor="middle" x="789" y="-1144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2154.5,-1439C2154.5,-1439 2455.5,-1439 2455.5,-1439 2461.5,-1439 2467.5,-1445 2467.5,-1451 2467.5,-1451 2467.5,-1473 2467.5,-1473 2467.5,-1479 2461.5,-1485 2455.5,-1485 2455.5,-1485 2154.5,-1485 2154.5,-1485 2148.5,-1485 2142.5,-1479 2142.5,-1473 2142.5,-1473 2142.5,-1451 2142.5,-1451 2142.5,-1445 2148.5,-1439 2154.5,-1439"/>
<text text-anchor="middle" x="2182.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2222.5,-1439 2222.5,-1485 "/>
<text text-anchor="middle" x="2233" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2243.5,-1439 2243.5,-1485 "/>
<text text-anchor="middle" x="2345" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2243.5,-1462 2446.5,-1462 "/>
<text text-anchor="middle" x="2345" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2446.5,-1439 2446.5,-1485 "/>
<text text-anchor="middle" x="2457" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2298.7436,-1438.8706C2282.2503,-1382.7736 2231.8974,-1239.3072 2133,-1174 2062.6366,-1127.5353 1837.1615,-1149.1554 1757,-1123 1651.7144,-1088.6471 1542.0108,-1028.6347 1460.3005,-978.4564"/>
<polygon fill="#000000" stroke="#000000" points="1461.8294,-975.2871 1451.4816,-973.0122 1458.1522,-981.2435 1461.8294,-975.2871"/>
<text text-anchor="middle" x="2123.5" y="-1144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2467.6498,-1441.8265C2655.2896,-1409.3752 2958.1752,-1326.9715 3116,-1123 3179.3309,-1041.1516 3149,-995.989 3149,-892.5 3149,-892.5 3149,-892.5 3149,-351.5 3149,-206.2557 2716.811,-143.8797 2444.2332,-118.9832"/>
<polygon fill="#000000" stroke="#000000" points="2444.4763,-115.491 2434.202,-118.0772 2443.8466,-122.4626 2444.4763,-115.491"/>
<text text-anchor="middle" x="3191.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2296.1938,-1438.6136C2276.2124,-1384.2154 2227.7983,-1244.5581 2210,-1123 2183.6774,-943.223 2189.9645,-728.1688 2195.6282,-620.8797"/>
<polygon fill="#000000" stroke="#000000" points="2199.1261,-621.0132 2196.1733,-610.8381 2192.1363,-620.6337 2199.1261,-621.0132"/>
<text text-anchor="middle" x="2252.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M2037.5,-317C2037.5,-317 2416.5,-317 2416.5,-317 2422.5,-317 2428.5,-323 2428.5,-329 2428.5,-329 2428.5,-374 2428.5,-374 2428.5,-380 2422.5,-386 2416.5,-386 2416.5,-386 2037.5,-386 2037.5,-386 2031.5,-386 2025.5,-380 2025.5,-374 2025.5,-374 2025.5,-329 2025.5,-329 2025.5,-323 2031.5,-317 2037.5,-317"/>
<text text-anchor="middle" x="2085" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="2144.5,-317 2144.5,-386 "/>
<text text-anchor="middle" x="2155" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2165.5,-317 2165.5,-386 "/>
<text text-anchor="middle" x="2286.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2165.5,-363 2407.5,-363 "/>
<text text-anchor="middle" x="2286.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2165.5,-340 2407.5,-340 "/>
<text text-anchor="middle" x="2286.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2407.5,-317 2407.5,-386 "/>
<text text-anchor="middle" x="2418" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2227,-316.8256C2227,-290.8629 2227,-253.7725 2227,-217.8091"/>
<polygon fill="#000000" stroke="#000000" points="2230.5001,-217.7056 2227,-207.7056 2223.5001,-217.7056 2230.5001,-217.7056"/>
<text text-anchor="middle" x="2289" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sample_diagnosis -->
<g id="node8" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M759.5,-1243.5C759.5,-1243.5 1192.5,-1243.5 1192.5,-1243.5 1198.5,-1243.5 1204.5,-1249.5 1204.5,-1255.5 1204.5,-1255.5 1204.5,-1668.5 1204.5,-1668.5 1204.5,-1674.5 1198.5,-1680.5 1192.5,-1680.5 1192.5,-1680.5 759.5,-1680.5 759.5,-1680.5 753.5,-1680.5 747.5,-1674.5 747.5,-1668.5 747.5,-1668.5 747.5,-1255.5 747.5,-1255.5 747.5,-1249.5 753.5,-1243.5 759.5,-1243.5"/>
<text text-anchor="middle" x="819" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="890.5,-1243.5 890.5,-1680.5 "/>
<text text-anchor="middle" x="901" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="911.5,-1243.5 911.5,-1680.5 "/>
<text text-anchor="middle" x="1047.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="911.5,-1657.5 1183.5,-1657.5 "/>
<text text-anchor="middle" x="1047.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="911.5,-1634.5 1183.5,-1634.5 "/>
<text text-anchor="middle" x="1047.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="911.5,-1611.5 1183.5,-1611.5 "/>
<text text-anchor="middle" x="1047.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="911.5,-1588.5 1183.5,-1588.5 "/>
<text text-anchor="middle" x="1047.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="911.5,-1565.5 1183.5,-1565.5 "/>
<text text-anchor="middle" x="1047.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="911.5,-1542.5 1183.5,-1542.5 "/>
<text text-anchor="middle" x="1047.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="911.5,-1519.5 1183.5,-1519.5 "/>
<text text-anchor="middle" x="1047.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="911.5,-1496.5 1183.5,-1496.5 "/>
<text text-anchor="middle" x="1047.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="911.5,-1473.5 1183.5,-1473.5 "/>
<text text-anchor="middle" x="1047.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="911.5,-1450.5 1183.5,-1450.5 "/>
<text text-anchor="middle" x="1047.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="911.5,-1427.5 1183.5,-1427.5 "/>
<text text-anchor="middle" x="1047.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="911.5,-1404.5 1183.5,-1404.5 "/>
<text text-anchor="middle" x="1047.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="911.5,-1381.5 1183.5,-1381.5 "/>
<text text-anchor="middle" x="1047.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="911.5,-1358.5 1183.5,-1358.5 "/>
<text text-anchor="middle" x="1047.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="911.5,-1335.5 1183.5,-1335.5 "/>
<text text-anchor="middle" x="1047.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="911.5,-1312.5 1183.5,-1312.5 "/>
<text text-anchor="middle" x="1047.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="911.5,-1289.5 1183.5,-1289.5 "/>
<text text-anchor="middle" x="1047.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="911.5,-1266.5 1183.5,-1266.5 "/>
<text text-anchor="middle" x="1047.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1183.5,-1243.5 1183.5,-1680.5 "/>
<text text-anchor="middle" x="1194" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1112.237,-1243.4452C1168.9591,-1152.4501 1231.6328,-1051.9074 1275.3048,-981.8477"/>
<polygon fill="#000000" stroke="#000000" points="1278.4823,-983.3665 1280.8021,-973.0288 1272.5419,-979.6635 1278.4823,-983.3665"/>
<text text-anchor="middle" x="1249" y="-1144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2459,-259.5C2459,-259.5 2785,-259.5 2785,-259.5 2791,-259.5 2797,-265.5 2797,-271.5 2797,-271.5 2797,-431.5 2797,-431.5 2797,-437.5 2791,-443.5 2785,-443.5 2785,-443.5 2459,-443.5 2459,-443.5 2453,-443.5 2447,-437.5 2447,-431.5 2447,-431.5 2447,-271.5 2447,-271.5 2447,-265.5 2453,-259.5 2459,-259.5"/>
<text text-anchor="middle" x="2501" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="2555,-259.5 2555,-443.5 "/>
<text text-anchor="middle" x="2565.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2576,-259.5 2576,-443.5 "/>
<text text-anchor="middle" x="2676" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2576,-420.5 2776,-420.5 "/>
<text text-anchor="middle" x="2676" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2576,-397.5 2776,-397.5 "/>
<text text-anchor="middle" x="2676" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2576,-374.5 2776,-374.5 "/>
<text text-anchor="middle" x="2676" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2576,-351.5 2776,-351.5 "/>
<text text-anchor="middle" x="2676" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="2576,-328.5 2776,-328.5 "/>
<text text-anchor="middle" x="2676" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="2576,-305.5 2776,-305.5 "/>
<text text-anchor="middle" x="2676" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="2576,-282.5 2776,-282.5 "/>
<text text-anchor="middle" x="2676" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="2776,-259.5 2776,-443.5 "/>
<text text-anchor="middle" x="2786.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2474.9166,-259.3401C2450.8809,-244.2798 2425.7775,-228.5504 2401.1644,-213.1283"/>
<polygon fill="#000000" stroke="#000000" points="2402.8138,-210.0315 2392.4815,-207.6878 2399.0971,-215.9633 2402.8138,-210.0315"/>
<text text-anchor="middle" x="2492.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1778,-662.5C1778,-662.5 2152,-662.5 2152,-662.5 2158,-662.5 2164,-668.5 2164,-674.5 2164,-674.5 2164,-1110.5 2164,-1110.5 2164,-1116.5 2158,-1122.5 2152,-1122.5 2152,-1122.5 1778,-1122.5 1778,-1122.5 1772,-1122.5 1766,-1116.5 1766,-1110.5 1766,-1110.5 1766,-674.5 1766,-674.5 1766,-668.5 1772,-662.5 1778,-662.5"/>
<text text-anchor="middle" x="1808" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1850,-662.5 1850,-1122.5 "/>
<text text-anchor="middle" x="1860.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1871,-662.5 1871,-1122.5 "/>
<text text-anchor="middle" x="2007" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1871,-1099.5 2143,-1099.5 "/>
<text text-anchor="middle" x="2007" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1871,-1076.5 2143,-1076.5 "/>
<text text-anchor="middle" x="2007" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1871,-1053.5 2143,-1053.5 "/>
<text text-anchor="middle" x="2007" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1871,-1030.5 2143,-1030.5 "/>
<text text-anchor="middle" x="2007" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1871,-1007.5 2143,-1007.5 "/>
<text text-anchor="middle" x="2007" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1871,-984.5 2143,-984.5 "/>
<text text-anchor="middle" x="2007" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1871,-961.5 2143,-961.5 "/>
<text text-anchor="middle" x="2007" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1871,-938.5 2143,-938.5 "/>
<text text-anchor="middle" x="2007" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1871,-915.5 2143,-915.5 "/>
<text text-anchor="middle" x="2007" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1871,-892.5 2143,-892.5 "/>
<text text-anchor="middle" x="2007" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1871,-869.5 2143,-869.5 "/>
<text text-anchor="middle" x="2007" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1871,-846.5 2143,-846.5 "/>
<text text-anchor="middle" x="2007" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1871,-823.5 2143,-823.5 "/>
<text text-anchor="middle" x="2007" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1871,-800.5 2143,-800.5 "/>
<text text-anchor="middle" x="2007" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1871,-777.5 2143,-777.5 "/>
<text text-anchor="middle" x="2007" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1871,-754.5 2143,-754.5 "/>
<text text-anchor="middle" x="2007" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1871,-731.5 2143,-731.5 "/>
<text text-anchor="middle" x="2007" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1871,-708.5 2143,-708.5 "/>
<text text-anchor="middle" x="2007" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1871,-685.5 2143,-685.5 "/>
<text text-anchor="middle" x="2007" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2143,-662.5 2143,-1122.5 "/>
<text text-anchor="middle" x="2153.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2071.7709,-662.2196C2079.7714,-650.6297 2088.1853,-639.4704 2097,-629 2100.2706,-625.1151 2103.778,-621.3182 2107.4538,-617.6246"/>
<polygon fill="#000000" stroke="#000000" points="2109.9249,-620.1041 2114.7125,-610.6527 2105.0759,-615.0556 2109.9249,-620.1041"/>
<text text-anchor="middle" x="2141.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M1234.5,-1347C1234.5,-1347 1601.5,-1347 1601.5,-1347 1607.5,-1347 1613.5,-1353 1613.5,-1359 1613.5,-1359 1613.5,-1565 1613.5,-1565 1613.5,-1571 1607.5,-1577 1601.5,-1577 1601.5,-1577 1234.5,-1577 1234.5,-1577 1228.5,-1577 1222.5,-1571 1222.5,-1565 1222.5,-1565 1222.5,-1359 1222.5,-1359 1222.5,-1353 1228.5,-1347 1234.5,-1347"/>
<text text-anchor="middle" x="1311.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1400.5,-1347 1400.5,-1577 "/>
<text text-anchor="middle" x="1411" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1421.5,-1347 1421.5,-1577 "/>
<text text-anchor="middle" x="1507" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1554 1592.5,-1554 "/>
<text text-anchor="middle" x="1507" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1531 1592.5,-1531 "/>
<text text-anchor="middle" x="1507" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1508 1592.5,-1508 "/>
<text text-anchor="middle" x="1507" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1485 1592.5,-1485 "/>
<text text-anchor="middle" x="1507" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1462 1592.5,-1462 "/>
<text text-anchor="middle" x="1507" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1439 1592.5,-1439 "/>
<text text-anchor="middle" x="1507" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1416 1592.5,-1416 "/>
<text text-anchor="middle" x="1507" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1393 1592.5,-1393 "/>
<text text-anchor="middle" x="1507" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1421.5,-1370 1592.5,-1370 "/>
<text text-anchor="middle" x="1507" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1592.5,-1347 1592.5,-1577 "/>
<text text-anchor="middle" x="1603" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1400.3943,-1346.7532C1384.0012,-1239.4446 1359.8942,-1081.6406 1344.8385,-983.0865"/>
<polygon fill="#000000" stroke="#000000" points="1348.2901,-982.5032 1343.32,-973.1465 1341.3704,-983.5604 1348.2901,-982.5032"/>
<text text-anchor="middle" x="1461.5" y="-1144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M1643.5,-1174.5C1643.5,-1174.5 2112.5,-1174.5 2112.5,-1174.5 2118.5,-1174.5 2124.5,-1180.5 2124.5,-1186.5 2124.5,-1186.5 2124.5,-1737.5 2124.5,-1737.5 2124.5,-1743.5 2118.5,-1749.5 2112.5,-1749.5 2112.5,-1749.5 1643.5,-1749.5 1643.5,-1749.5 1637.5,-1749.5 1631.5,-1743.5 1631.5,-1737.5 1631.5,-1737.5 1631.5,-1186.5 1631.5,-1186.5 1631.5,-1180.5 1637.5,-1174.5 1643.5,-1174.5"/>
<text text-anchor="middle" x="1695.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="1759.5,-1174.5 1759.5,-1749.5 "/>
<text text-anchor="middle" x="1770" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1780.5,-1174.5 1780.5,-1749.5 "/>
<text text-anchor="middle" x="1942" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1726.5 2103.5,-1726.5 "/>
<text text-anchor="middle" x="1942" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1703.5 2103.5,-1703.5 "/>
<text text-anchor="middle" x="1942" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1680.5 2103.5,-1680.5 "/>
<text text-anchor="middle" x="1942" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1657.5 2103.5,-1657.5 "/>
<text text-anchor="middle" x="1942" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1634.5 2103.5,-1634.5 "/>
<text text-anchor="middle" x="1942" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1611.5 2103.5,-1611.5 "/>
<text text-anchor="middle" x="1942" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1588.5 2103.5,-1588.5 "/>
<text text-anchor="middle" x="1942" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1565.5 2103.5,-1565.5 "/>
<text text-anchor="middle" x="1942" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1542.5 2103.5,-1542.5 "/>
<text text-anchor="middle" x="1942" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1519.5 2103.5,-1519.5 "/>
<text text-anchor="middle" x="1942" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1496.5 2103.5,-1496.5 "/>
<text text-anchor="middle" x="1942" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1473.5 2103.5,-1473.5 "/>
<text text-anchor="middle" x="1942" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1450.5 2103.5,-1450.5 "/>
<text text-anchor="middle" x="1942" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1427.5 2103.5,-1427.5 "/>
<text text-anchor="middle" x="1942" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1404.5 2103.5,-1404.5 "/>
<text text-anchor="middle" x="1942" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1381.5 2103.5,-1381.5 "/>
<text text-anchor="middle" x="1942" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1358.5 2103.5,-1358.5 "/>
<text text-anchor="middle" x="1942" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1335.5 2103.5,-1335.5 "/>
<text text-anchor="middle" x="1942" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1312.5 2103.5,-1312.5 "/>
<text text-anchor="middle" x="1942" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1289.5 2103.5,-1289.5 "/>
<text text-anchor="middle" x="1942" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1266.5 2103.5,-1266.5 "/>
<text text-anchor="middle" x="1942" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1243.5 2103.5,-1243.5 "/>
<text text-anchor="middle" x="1942" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1220.5 2103.5,-1220.5 "/>
<text text-anchor="middle" x="1942" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="1780.5,-1197.5 2103.5,-1197.5 "/>
<text text-anchor="middle" x="1942" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2103.5,-1174.5 2103.5,-1749.5 "/>
<text text-anchor="middle" x="2114" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1631.4117,-1183.8601C1628.2632,-1180.5476 1625.125,-1177.2596 1622,-1174 1557.9742,-1107.2161 1482.8614,-1034.6926 1424.987,-979.9853"/>
<polygon fill="#000000" stroke="#000000" points="1427.3319,-977.3857 1417.658,-973.0654 1422.5263,-982.4755 1427.3319,-977.3857"/>
<text text-anchor="middle" x="1666.5" y="-1144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- imaging_file -->
<g id="node13" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M12,-1301C12,-1301 346,-1301 346,-1301 352,-1301 358,-1307 358,-1313 358,-1313 358,-1611 358,-1611 358,-1617 352,-1623 346,-1623 346,-1623 12,-1623 12,-1623 6,-1623 0,-1617 0,-1611 0,-1611 0,-1313 0,-1313 0,-1307 6,-1301 12,-1301"/>
<text text-anchor="middle" x="52" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="104,-1301 104,-1623 "/>
<text text-anchor="middle" x="114.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="125,-1301 125,-1623 "/>
<text text-anchor="middle" x="231" y="-1607.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="125,-1600 337,-1600 "/>
<text text-anchor="middle" x="231" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="125,-1577 337,-1577 "/>
<text text-anchor="middle" x="231" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="125,-1554 337,-1554 "/>
<text text-anchor="middle" x="231" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="125,-1531 337,-1531 "/>
<text text-anchor="middle" x="231" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="125,-1508 337,-1508 "/>
<text text-anchor="middle" x="231" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="125,-1485 337,-1485 "/>
<text text-anchor="middle" x="231" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="125,-1462 337,-1462 "/>
<text text-anchor="middle" x="231" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="125,-1439 337,-1439 "/>
<text text-anchor="middle" x="231" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="125,-1416 337,-1416 "/>
<text text-anchor="middle" x="231" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="125,-1393 337,-1393 "/>
<text text-anchor="middle" x="231" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="125,-1370 337,-1370 "/>
<text text-anchor="middle" x="231" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="125,-1347 337,-1347 "/>
<text text-anchor="middle" x="231" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="125,-1324 337,-1324 "/>
<text text-anchor="middle" x="231" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="337,-1301 337,-1623 "/>
<text text-anchor="middle" x="347.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M256.3531,-1300.6502C285.3972,-1254.1417 322.4027,-1207.0864 367,-1174 602.5822,-999.2234 944.8826,-932.5899 1151.8772,-907.4443"/>
<polygon fill="#000000" stroke="#000000" points="1152.4232,-910.9041 1161.9372,-906.242 1151.5925,-903.9535 1152.4232,-910.9041"/>
<text text-anchor="middle" x="466.5" y="-1144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2364.1293,-546.4771C2523.9424,-536.2687 2750.6287,-510.2194 2806,-444 2858.7433,-380.9235 2856.0612,-324.2255 2806,-259 2761.175,-200.5968 2589.0119,-159.4019 2443.9723,-134.235"/>
<polygon fill="#000000" stroke="#000000" points="2444.4675,-130.7689 2434.0194,-132.5256 2443.2826,-137.6679 2444.4675,-130.7689"/>
<text text-anchor="middle" x="2894.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1698.5,-317C1698.5,-317 1995.5,-317 1995.5,-317 2001.5,-317 2007.5,-323 2007.5,-329 2007.5,-329 2007.5,-374 2007.5,-374 2007.5,-380 2001.5,-386 1995.5,-386 1995.5,-386 1698.5,-386 1698.5,-386 1692.5,-386 1686.5,-380 1686.5,-374 1686.5,-374 1686.5,-329 1686.5,-329 1686.5,-323 1692.5,-317 1698.5,-317"/>
<text text-anchor="middle" x="1732.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1778.5,-317 1778.5,-386 "/>
<text text-anchor="middle" x="1789" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1799.5,-317 1799.5,-386 "/>
<text text-anchor="middle" x="1893" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1799.5,-363 1986.5,-363 "/>
<text text-anchor="middle" x="1893" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1799.5,-340 1986.5,-340 "/>
<text text-anchor="middle" x="1893" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1986.5,-317 1986.5,-386 "/>
<text text-anchor="middle" x="1997" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2098.8444,-495.2582C2040.3932,-461.893 1968.3701,-420.7806 1916.3389,-391.0801"/>
<polygon fill="#000000" stroke="#000000" points="1917.9357,-387.9616 1907.5159,-386.0438 1914.4655,-394.0409 1917.9357,-387.9616"/>
<text text-anchor="middle" x="2115.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node15" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2315.5,-835C2315.5,-835 2672.5,-835 2672.5,-835 2678.5,-835 2684.5,-841 2684.5,-847 2684.5,-847 2684.5,-938 2684.5,-938 2684.5,-944 2678.5,-950 2672.5,-950 2672.5,-950 2315.5,-950 2315.5,-950 2309.5,-950 2303.5,-944 2303.5,-938 2303.5,-938 2303.5,-847 2303.5,-847 2303.5,-841 2309.5,-835 2315.5,-835"/>
<text text-anchor="middle" x="2394" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2484.5,-835 2484.5,-950 "/>
<text text-anchor="middle" x="2495" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2505.5,-835 2505.5,-950 "/>
<text text-anchor="middle" x="2584.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2505.5,-927 2663.5,-927 "/>
<text text-anchor="middle" x="2584.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2505.5,-904 2663.5,-904 "/>
<text text-anchor="middle" x="2584.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2505.5,-881 2663.5,-881 "/>
<text text-anchor="middle" x="2584.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2505.5,-858 2663.5,-858 "/>
<text text-anchor="middle" x="2584.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2663.5,-835 2663.5,-950 "/>
<text text-anchor="middle" x="2674" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2444.1269,-834.9085C2392.2028,-774.9485 2311.0145,-681.1953 2256.6903,-618.4638"/>
<polygon fill="#000000" stroke="#000000" points="2259.064,-615.8583 2249.8718,-610.59 2253.7723,-620.4408 2259.064,-615.8583"/>
<text text-anchor="middle" x="2364" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1900.2375,-316.8256C1941.8029,-289.7534 2001.9447,-250.582 2059.331,-213.2055"/>
<polygon fill="#000000" stroke="#000000" points="2061.306,-216.0961 2067.7752,-207.7056 2057.4856,-210.2305 2061.306,-216.0961"/>
<text text-anchor="middle" x="2085.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M2743,-766C2743,-766 3095,-766 3095,-766 3101,-766 3107,-772 3107,-778 3107,-778 3107,-1007 3107,-1007 3107,-1013 3101,-1019 3095,-1019 3095,-1019 2743,-1019 2743,-1019 2737,-1019 2731,-1013 2731,-1007 2731,-1007 2731,-778 2731,-778 2731,-772 2737,-766 2743,-766"/>
<text text-anchor="middle" x="2814.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="2898,-766 2898,-1019 "/>
<text text-anchor="middle" x="2908.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2919,-766 2919,-1019 "/>
<text text-anchor="middle" x="3002.5" y="-1003.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2919,-996 3086,-996 "/>
<text text-anchor="middle" x="3002.5" y="-980.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2919,-973 3086,-973 "/>
<text text-anchor="middle" x="3002.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2919,-950 3086,-950 "/>
<text text-anchor="middle" x="3002.5" y="-934.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2919,-927 3086,-927 "/>
<text text-anchor="middle" x="3002.5" y="-911.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2919,-904 3086,-904 "/>
<text text-anchor="middle" x="3002.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2919,-881 3086,-881 "/>
<text text-anchor="middle" x="3002.5" y="-865.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2919,-858 3086,-858 "/>
<text text-anchor="middle" x="3002.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2919,-835 3086,-835 "/>
<text text-anchor="middle" x="3002.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2919,-812 3086,-812 "/>
<text text-anchor="middle" x="3002.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2919,-789 3086,-789 "/>
<text text-anchor="middle" x="3002.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="3086,-766 3086,-1019 "/>
<text text-anchor="middle" x="3096.5" y="-888.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2933.6565,-765.8053C2952.4099,-592.1887 2978.9831,-297.3517 2948,-259 2885.4561,-181.5815 2632.9652,-141.0295 2444.303,-121.1189"/>
<polygon fill="#000000" stroke="#000000" points="2444.5478,-117.6256 2434.2388,-120.0699 2443.822,-124.5878 2444.5478,-117.6256"/>
<text text-anchor="middle" x="3045" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2820.46,-765.7973C2784.5208,-727.2197 2741.0456,-688.1501 2694,-662 2639.4939,-631.703 2493.449,-601.478 2374.194,-580.5678"/>
<polygon fill="#000000" stroke="#000000" points="2374.655,-577.0955 2364.2025,-578.8266 2373.4531,-583.9915 2374.655,-577.0955"/>
<text text-anchor="middle" x="2775.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
</g>
</svg>
</div>
