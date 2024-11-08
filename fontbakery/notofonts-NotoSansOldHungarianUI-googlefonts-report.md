## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[16] NotoSansOldHungarianUI-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 399, but got 206 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1396) and hhea ascent (1703) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>&quot;NotoSansOldHungarianUI&quot; is a CamelCased name. To solve this, simply use spaces instead in the font name.</p>
 [code: camelcase]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;200&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;385&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 2294 when it should be at least 2457</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansOldHungarianUI/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0009 : try adding symbols</li>
<li>U+000A : try adding symbols</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, tifinagh, math, duployan, tai-le, hebrew, canadian-aboriginal, old-permic, todhri, malayalam, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>old-hungarian</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSansOldHungarianUI-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Vute (Latn, 21,000 speakers), Kaska (Latn, 125 speakers), Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Aghem (Latn, 38,843 speakers), Sar (Latn, 500,000 speakers), Cicipu (Latn, 44,000 speakers), Ma’di (Latn, 584,000 speakers), Avokaya (Latn, 100,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Navajo (Latn, 166,319 speakers), Ngbaka (Latn, 1,020,000 speakers), Ebira (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Kom (Latn, 360,685 speakers), Dii (Latn, 71,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mango (Latn, 77,000 speakers), Ekpeye (Latn, 226,000 speakers), Heiltsuk (Latn, 300 speakers), Teke-Ebo (Latn, 260,000 speakers), Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* u10C89 (U+10C89) contains a short segment B&lt;&lt;273.0,1.0&gt;-&lt;273.0,1.0&gt;-&lt;269.0,6.0&gt;&gt;

* u10C89 (U+10C89) contains a short segment B&lt;&lt;269.0,6.0&gt;-&lt;265.0,11.0&gt;-&lt;244.0,35.0&gt;&gt;

* u10C8A (U+10C8A) contains a short segment B&lt;&lt;299.0,2.0&gt;-&lt;299.0,2.0&gt;-&lt;294.5,7.0&gt;&gt;

* u10C8B (U+10C8B) contains a short segment B&lt;&lt;176.0,1204.0&gt;-&lt;176.0,1204.0&gt;-&lt;183.0,1209.0&gt;&gt;

* u10C8D (U+10C8D) contains a short segment B&lt;&lt;733.0,1082.0&gt;-&lt;733.0,1082.0&gt;-&lt;729.5,1074.0&gt;&gt;

* u10C99 (U+10C99) contains a short segment B&lt;&lt;236.0,0.0&gt;-&lt;236.0,0.0&gt;-&lt;232.0,5.0&gt;&gt;

* u10C9B (U+10C9B) contains a short segment B&lt;&lt;580.0,7.0&gt;-&lt;580.0,7.0&gt;-&lt;575.5,10.5&gt;&gt;

* u10C9B (U+10C9B) contains a short segment B&lt;&lt;575.5,10.5&gt;-&lt;571.0,14.0&gt;-&lt;549.5,30.0&gt;&gt;

* u10C9C (U+10C9C) contains a short segment B&lt;&lt;620.0,4.0&gt;-&lt;620.0,4.0&gt;-&lt;615.0,8.0&gt;&gt;

* u10C9F (U+10C9F) contains a short segment B&lt;&lt;621.0,7.0&gt;-&lt;621.0,7.0&gt;-&lt;616.0,11.0&gt;&gt;

* u10C9F (U+10C9F) contains a short segment B&lt;&lt;616.0,11.0&gt;-&lt;611.0,15.0&gt;-&lt;586.0,35.0&gt;&gt;

* u10C9F (U+10C9F) contains a short segment L&lt;&lt;85.0,441.0&gt;--&lt;75.0,445.0&gt;&gt;

* u10CA1 (U+10CA1) contains a short segment B&lt;&lt;706.0,181.0&gt;-&lt;706.0,181.0&gt;-&lt;701.5,177.0&gt;&gt;

* u10CA1 (U+10CA1) contains a short segment B&lt;&lt;701.5,177.0&gt;-&lt;697.0,173.0&gt;-&lt;676.0,152.5&gt;&gt;

* u10CA1 (U+10CA1) contains a short segment L&lt;&lt;1466.0,1176.0&gt;--&lt;1460.0,1170.0&gt;&gt;

* u10CAC (U+10CAC) contains a short segment B&lt;&lt;435.0,188.0&gt;-&lt;435.0,188.0&gt;-&lt;431.0,184.0&gt;&gt;

* u10CAC (U+10CAC) contains a short segment B&lt;&lt;431.0,184.0&gt;-&lt;427.0,180.0&gt;-&lt;407.0,161.0&gt;&gt;

* u10CC3 (U+10CC3) contains a short segment B&lt;&lt;512.0,141.0&gt;-&lt;512.0,141.0&gt;-&lt;506.5,135.5&gt;&gt;

* u10CCA (U+10CCA) contains a short segment B&lt;&lt;182.0,4.0&gt;-&lt;182.0,4.0&gt;-&lt;179.0,9.0&gt;&gt;

* u10CD9 (U+10CD9) contains a short segment B&lt;&lt;146.0,4.0&gt;-&lt;146.0,4.0&gt;-&lt;143.0,9.0&gt;&gt;

* u10CDB (U+10CDB) contains a short segment B&lt;&lt;421.0,3.0&gt;-&lt;421.0,3.0&gt;-&lt;414.5,8.0&gt;&gt;

* u10CDC (U+10CDC) contains a short segment B&lt;&lt;481.0,3.0&gt;-&lt;481.0,3.0&gt;-&lt;473.5,9.5&gt;&gt;

* u10CDF (U+10CDF) contains a short segment B&lt;&lt;481.0,4.0&gt;-&lt;481.0,4.0&gt;-&lt;473.5,10.5&gt;&gt;

* u10CE1 (U+10CE1) contains a short segment B&lt;&lt;509.0,129.0&gt;-&lt;509.0,129.0&gt;-&lt;502.0,122.5&gt;&gt;

* u10CEB (U+10CEB) contains a short segment L&lt;&lt;1071.0,231.0&gt;--&lt;1077.0,231.0&gt;&gt;

* u10CEB (U+10CEB) contains a short segment L&lt;&lt;1077.0,862.0&gt;--&lt;1071.0,862.0&gt;&gt;

* u10CEB (U+10CEB) contains a short segment L&lt;&lt;349.0,239.0&gt;--&lt;355.0,239.0&gt;&gt;

* u10CEB (U+10CEB) contains a short segment L&lt;&lt;355.0,852.0&gt;--&lt;349.0,852.0&gt;&gt;

* u10CEC (U+10CEC) contains a short segment B&lt;&lt;351.0,133.0&gt;-&lt;351.0,133.0&gt;-&lt;344.5,126.5&gt;&gt;

* u10CEC (U+10CEC) contains a short segment B&lt;&lt;821.0,968.0&gt;-&lt;821.0,968.0&gt;-&lt;827.5,974.5&gt;&gt;

* uni10C9F.ltr contains a short segment L&lt;&lt;1252.0,446.0&gt;--&lt;1242.0,441.0&gt;&gt;

* uni10C9F.ltr contains a short segment L&lt;&lt;1242.0,441.0&gt;--&lt;1248.0,440.0&gt;&gt;

* uni10CA1.ltr contains a short segment L&lt;&lt;1454.0,1176.0&gt;--&lt;1450.0,1171.0&gt;&gt;

* uni10CCD.ltr contains a short segment B&lt;&lt;481.0,681.0&gt;-&lt;481.0,681.0&gt;-&lt;477.0,671.5&gt;&gt;

* uni10CDF.ltr contains a short segment B&lt;&lt;413.0,798.0&gt;-&lt;413.0,798.0&gt;-&lt;424.0,790.0&gt;&gt;

* uni10CE1.ltr contains a short segment B&lt;&lt;411.0,850.0&gt;-&lt;411.0,850.0&gt;-&lt;406.5,848.0&gt;&gt;

* uni10CE1.ltr contains a short segment B&lt;&lt;406.5,848.0&gt;-&lt;402.0,846.0&gt;-&lt;380.0,836.5&gt;&gt;

* uni10CEB.ltr contains a short segment L&lt;&lt;346.0,862.0&gt;--&lt;340.0,862.0&gt;&gt;

* uni10CEB.ltr contains a short segment L&lt;&lt;340.0,231.0&gt;--&lt;346.0,231.0&gt;&gt;

* uni10CEB.ltr contains a short segment L&lt;&lt;1068.0,852.0&gt;--&lt;1062.0,852.0&gt;&gt;

* uni10CEB.ltr contains a short segment L&lt;&lt;1062.0,239.0&gt;--&lt;1068.0,239.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;177.0,626.0&gt;--&lt;173.0,626.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;450.0,129.0&gt;--&lt;454.0,129.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;416.0,-9.0&gt;-&lt;410.0,-9.0&gt;-&lt;403.5,-9.5&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;403.5,-9.5&gt;-&lt;397.0,-10.0&gt;-&lt;391.0,-10.0&gt;&gt;

* Uogonek (U+0172) contains a short segment B&lt;&lt;539.5,-158.5&gt;-&lt;551.0,-156.0&gt;-&lt;559.0,-155.0&gt;&gt;

* a (U+0061) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aacute (U+00E1) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* abreve (U+0103) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* acircumflex (U+00E2) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* adieresis (U+00E4) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* agrave (U+00E0) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* amacron (U+0101) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aogonek (U+0105) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aring (U+00E5) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;613.0,293.0&gt;-&lt;612.0,275.0&gt;-&lt;612.0,267.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;612.0,267.5&gt;-&lt;612.0,260.0&gt;-&lt;612.0,257.0&gt;&gt;

* atilde (U+00E3) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* d (U+0064) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcaron (U+010F) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcroat (U+0111) contains a short segment L&lt;&lt;445.0,72.0&gt;--&lt;441.0,72.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;184.0,390.0&gt;-&lt;183.0,380.0&gt;-&lt;183.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,371.0&gt;-&lt;183.0,362.0&gt;-&lt;183.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,352.0&gt;-&lt;183.0,343.0&gt;-&lt;183.0,332.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,332.5&gt;-&lt;183.0,322.0&gt;-&lt;184.0,311.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;95.0,311.0&gt;-&lt;94.0,323.0&gt;-&lt;94.0,331.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,331.0&gt;-&lt;94.0,339.0&gt;-&lt;94.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,352.0&gt;-&lt;94.0,363.0&gt;-&lt;94.5,373.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.5,373.5&gt;-&lt;95.0,384.0&gt;-&lt;95.0,390.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* n (U+006E) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* nacute (U+0144) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ncaron (U+0148) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* uni0146 (U+0146) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ntilde (U+00F1) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* p (U+0070) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;173.0,463.0&gt;&gt;

* r (U+0072) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* racute (U+0155) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* rcaron (U+0159) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;386.0,633.0&gt;--&lt;382.0,633.0&gt;&gt;

* two (U+0032) contains a short segment L&lt;&lt;159.0,84.0&gt;--&lt;159.0,80.0&gt;&gt;

* u (U+0075) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uacute (U+00FA) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ucircumflex (U+00FB) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* udieresis (U+00FC) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ugrave (U+00F9) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uhungarumlaut (U+0171) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* umacron (U+016B) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uring (U+016F) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uni10C8D.ltr: L&lt;&lt;1362.0,3.0&gt;--&lt;963.0,891.0&gt;&gt; -&gt; L&lt;&lt;963.0,891.0&gt;--&lt;876.0,1082.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wacute (U+1E82): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wcircumflex (U+0174): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wdieresis (U+1E84): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wgrave (U+1E80): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* u10CFD (U+10CFD): B&lt;&lt;459.0,580.0&gt;-&lt;473.0,528.0&gt;-&lt;485.0,479.0&gt;&gt;/L&lt;&lt;485.0,479.0&gt;--&lt;479.0,1461.0&gt;&gt; = 13.410713422117814

* u10CFD (U+10CFD): L&lt;&lt;652.0,1461.0&gt;--&lt;646.0,477.0&gt;&gt;/B&lt;&lt;646.0,477.0&gt;-&lt;657.0,523.0&gt;-&lt;672.0,578.0&gt;&gt; = 13.099254872183751
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u10CAB (U+10CAB): L&lt;&lt;1495.0,235.0&gt;--&lt;1498.0,1246.0&gt;&gt;

* u10CAB (U+10CAB): L&lt;&lt;407.0,1221.0&gt;--&lt;399.0,230.0&gt;&gt;

* u10CFD (U+10CFD): L&lt;&lt;485.0,479.0&gt;--&lt;479.0,1461.0&gt;&gt;

* u10CFD (U+10CFD): L&lt;&lt;652.0,1461.0&gt;--&lt;646.0,477.0&gt;&gt;

* u10CFF (U+10CFF): L&lt;&lt;895.0,890.0&gt;--&lt;1322.0,893.0&gt;&gt;

* uni10CAB.ltr: L&lt;&lt;1515.0,230.0&gt;--&lt;1507.0,1221.0&gt;&gt;

* uni10CAB.ltr: L&lt;&lt;416.0,1246.0&gt;--&lt;419.0,235.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[2] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Does font file include unacceptable control character glyphs? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following unacceptable control characters were identified:
fonts/NotoSansOldHungarianUI/googlefonts/ttf/NotoSansOldHungarianUI-Regular.ttf: uni0009, uni000A</p>
 [code: unacceptable]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansOldHungarianUI/googlefonts/ttf/NotoSansOldHungarianUI-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 7 | 11 | 117 | 7 | 109 | 0 | 
| 0% | 0% | 3% | 4% | 47% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
