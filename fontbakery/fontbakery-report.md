## FontBakery report

fontbakery version: 0.13.0







## Check results



<details><summary>[25] Galle-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 333, but got 184 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-trailing-spaces">name/trailing_spaces</a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 0) has trailing spaces that must be removed: 'Copyright [...]mail.com) '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (553) and hhea ascent (1016) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-glyphs">whitespace_glyphs</a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright (c) 2015–2018 mooniak (<a href="http://mooniak.com">http://mooniak.com</a>)  Copyright (c) 2016–2018 Janaka CB Attanayake (<a href="mailto:janakacb@gmail.com">janakacb@gmail.com</a>) &quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Galle</td>
<td align="left">Galle</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Galle Regular</td>
<td align="left">Galle Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>GalleALPHA</strong></td>
<td align="left"><strong>Galle-Regular</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0024 (DOLLAR SIGN)


- 0x0025 (PERCENT SIGN)


- 0x0026 (AMPERSAND)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x0060 (GRAVE ACCENT)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x00A0 (NO-BREAK SPACE)


- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B6 (PILCROW SIGN)


- 0x00B7 (MIDDLE DOT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2018 (LEFT SINGLE QUOTATION MARK)


- 0x2019 (RIGHT SINGLE QUOTATION MARK)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201C (LEFT DOUBLE QUOTATION MARK)


- 0x201D (RIGHT DOUBLE QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-version-format">googlefonts/name/version_format</a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. The &quot;Version &quot; prefix is a recommendation given by the OpenType spec. Current version string is: &quot;Version 0.050; DEV; pre; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-render-own-name">googlefonts/render_own_name</a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Galle</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;463&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-non-mark-chars">opentype/gdef_non_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+0D82, U+0D83, U+0DCF, U+0DD0, U+0DD1, U+0DD8, U+0DD9, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF, U+0DF2 and U+0DF3</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
anusvara (U+0D82), sinMatraAa (U+0DCF), sinMatraAae (U+0DD1), sinMatraAe (U+0DD0), sinMatraAi (U+0DDB), sinMatraAu (U+0DDE), sinMatraE (U+0DD9), sinMatraEe (U+0DDA), sinMatraI (U+0DD2), sinMatraIi (U+0DD3), sinMatraLl (U+0DF3), sinMatraLs (U+0DDF), sinMatraO (U+0DDC), sinMatraOo (U+0DDD), sinMatraR (U+0DD8), sinMatraRr (U+0DF2), sinMatraU (U+0DD4), sinMatraUu (U+0DD6), sinVirama (U+0DCA) and visarga (U+0D83)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 244 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 285:
less, greater</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* ArchaicEight (U+111E8): L&lt;&lt;199.0,-114.0&gt;--&lt;199.0,-114.0&gt;&gt; has the same coordinates as a previous segment.

* ArchaicSixty (U+111EF): B&lt;&lt;489.5,18.0&gt;-&lt;489.0,19.0&gt;-&lt;490.0,16.0&gt;&gt; has the same coordinates as a previous segment.

* sinGRI: L&lt;&lt;371.0,298.0&gt;--&lt;371.0,298.0&gt;&gt; has the same coordinates as a previous segment.

* sinRAae: B&lt;&lt;189.5,597.0&gt;-&lt;190.0,597.0&gt;-&lt;188.0,596.0&gt;&gt; has the same coordinates as a previous segment.

* sinNndda.reph: L&lt;&lt;238.0,512.0&gt;--&lt;238.0,512.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#stylisticset-description">stylisticset_description</a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NULL

- notdef

- null

- sinAnusvara

- sinBU.reph

- sinBUu.reph

- sinBa.reph

- sinBhAa

- sinBhAa.virama

- sinBhR.virama

- sinBhU.reph

- sinBhUu.reph

- sinBha.reph

- sinCU.reph

- sinCUu.reph

- sinCa.reph

- sinChR.virama

- sinChRI

- sinChRIi

- sinChRa

- sinChU.reph

- sinChUu.reph

- sinCha.reph

- sinDRa.alt

- sinDU.reph

- sinDUu.reph

- sinDa.reph

- sinDdU.reph

- sinDdUu.reph

- sinDda.reph

- sinDda.virama

- sinDdhR.virama

- sinDdhRI

- sinDdhRIi

- sinDdhRa

- sinDdhU.reph

- sinDdhUu.reph

- sinDdha.reph

- sinDhU.reph

- sinDhUu.reph

- sinDha.reph

- sinDrI

- sinDrIi

- sinDra

- sinFAa

- sinFAa.virama

- sinFRI

- sinFRIi

- sinFU.reph

- sinFUu.reph

- sinFa.reph

- sinGAa

- sinGAa.virama

- sinGU.reph

- sinGUu.reph

- sinGa.reph

- sinGhU.reph

- sinGhUu.reph

- sinGha.reph

- sinHAa

- sinHAa.virama

- sinHU.reph

- sinHUu.reph

- sinHa.reph

- sinJU.reph

- sinJUu.reph

- sinJa.reph

- sinJhU.reph

- sinJhUu.reph

- sinJha.reph

- sinJnya.reph

- sinKAa

- sinKAa.virama

- sinKR.virama

- sinKU.reph

- sinKUu.reph

- sinKa.reph

- sinKhU.reph

- sinKhUu.reph

- sinKha.reph

- sinKundaliya

- sinMa.reph

- sinMatraAea

- sinMatraI.alt

- sinMatraI.alt1

- sinMatraI.alt2

- sinMatraI.alt4

- sinMatraIi.alt

- sinMatraIi.alt1

- sinMatraIi.alt2

- sinMatraIi.alt3

- sinMatraU.alt

- sinMatraU.alt1

- sinMatraU.alt2

- sinMatraU.alt3

- sinMatraU.alt5

- sinMatraUu.alt

- sinMatraUu.alt1

- sinMatraUu.alt2

- sinMatraUu.alt3

- sinMatraUu.alt5

- sinMb

- sinMba.reph

- sinNAa

- sinNAa.virama

- sinNDRI

- sinNDRIi

- sinNa.reph

- sinNdRa

- sinNda.reph

- sinNdda

- sinNdja.reph

- sinNgU

- sinNgUu

- sinNga.reph

- sinNnAa

- sinNnAa.virama

- sinNna.reph

- sinNndda.reph

- sinNngAa

- sinNngAa.virama

- sinNnga.reph

- sinNyAa

- sinNya.reph

- sinPU.reph

- sinPUu.reph

- sinPa.reph

- sinPhR.virama

- sinPhRI

- sinPhRIi

- sinPhRa

- sinPhU.reph

- sinPhUu.reph

- sinPha.reph

- sinRakar.long

- sinRakar.medium

- sinRakar.short

- sinSU.reph

- sinSUu.reph

- sinSa.reph

- sinShU.reph

- sinShUu.reph

- sinSha.reph

- sinSsRI

- sinSsRIi

- sinSsU.reph

- sinSsUu.reph

- sinSsa.reph

- sinTAa

- sinTAa.virama

- sinTU.reph

- sinTUu.reph

- sinTa.reph

- sinThR.virama

- sinThRI

- sinThRIi

- sinThRa

- sinThU.reph

- sinThUu.reph

- sinTha.reph

- sinTtU.reph

- sinTtUu.reph

- sinTta.reph

- sinTthR.virama

- sinTthRI

- sinTthRIi

- sinTthRa

- sinTthU.reph

- sinTthUu.reph

- sinTtha.reph

- sinVU.reph

- sinVUu.reph

- sinVa.reph

- sinVirama.alt

- sinVisarga

- sinYU.post.reph

- sinYU.reph

- sinYUu.post.reph

- sinYUu.reph

- sinYa.post.reph

- sinYa.reph

- singNaa
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* ArchaicEight (U+111E8): L&lt;&lt;199.0,-114.0&gt;--&lt;199.0,-114.0&gt;&gt; -&gt; L&lt;&lt;199.0,-114.0&gt;--&lt;199.0,-114.0&gt;&gt;

* ArchaicSeven (U+111E7): L&lt;&lt;452.0,-7.0&gt;--&lt;451.0,-7.0&gt;&gt; -&gt; L&lt;&lt;451.0,-7.0&gt;--&lt;400.0,-7.0&gt;&gt;

* sinDhU.reph: L&lt;&lt;149.0,512.0&gt;--&lt;152.0,512.0&gt;&gt; -&gt; L&lt;&lt;152.0,512.0&gt;--&lt;153.0,512.0&gt;&gt;

* sinDhU.reph: L&lt;&lt;152.0,512.0&gt;--&lt;153.0,512.0&gt;&gt; -&gt; L&lt;&lt;153.0,512.0&gt;--&lt;158.0,512.0&gt;&gt;

* sinDhUu.reph: L&lt;&lt;149.0,512.0&gt;--&lt;152.0,512.0&gt;&gt; -&gt; L&lt;&lt;152.0,512.0&gt;--&lt;153.0,512.0&gt;&gt;

* sinDhUu.reph: L&lt;&lt;152.0,512.0&gt;--&lt;153.0,512.0&gt;&gt; -&gt; L&lt;&lt;153.0,512.0&gt;--&lt;158.0,512.0&gt;&gt;

* sinDha.reph: L&lt;&lt;149.0,512.0&gt;--&lt;152.0,512.0&gt;&gt; -&gt; L&lt;&lt;152.0,512.0&gt;--&lt;153.0,512.0&gt;&gt;

* sinDha.reph: L&lt;&lt;152.0,512.0&gt;--&lt;153.0,512.0&gt;&gt; -&gt; L&lt;&lt;153.0,512.0&gt;--&lt;158.0,512.0&gt;&gt;

* sinGRI: L&lt;&lt;371.0,298.0&gt;--&lt;371.0,298.0&gt;&gt; -&gt; L&lt;&lt;371.0,298.0&gt;--&lt;371.0,298.0&gt;&gt;

* sinKIi: L&lt;&lt;326.0,331.0&gt;--&lt;326.0,331.0&gt;&gt; -&gt; L&lt;&lt;326.0,331.0&gt;--&lt;328.0,331.0&gt;&gt;

* sinKhU.reph: L&lt;&lt;152.0,512.0&gt;--&lt;155.0,512.0&gt;&gt; -&gt; L&lt;&lt;155.0,512.0&gt;--&lt;159.0,512.0&gt;&gt;

* sinKhUu.reph: L&lt;&lt;152.0,512.0&gt;--&lt;155.0,512.0&gt;&gt; -&gt; L&lt;&lt;155.0,512.0&gt;--&lt;159.0,512.0&gt;&gt;

* sinKha.reph: L&lt;&lt;152.0,512.0&gt;--&lt;155.0,512.0&gt;&gt; -&gt; L&lt;&lt;155.0,512.0&gt;--&lt;159.0,512.0&gt;&gt;

* sinNI: L&lt;&lt;340.0,330.0&gt;--&lt;341.0,330.0&gt;&gt; -&gt; L&lt;&lt;341.0,330.0&gt;--&lt;341.0,330.0&gt;&gt;

* sinNndda.reph: L&lt;&lt;236.0,512.0&gt;--&lt;237.0,512.0&gt;&gt; -&gt; L&lt;&lt;237.0,512.0&gt;--&lt;238.0,512.0&gt;&gt;

* sinNndda.reph: L&lt;&lt;237.0,512.0&gt;--&lt;238.0,512.0&gt;&gt; -&gt; L&lt;&lt;238.0,512.0&gt;--&lt;238.0,512.0&gt;&gt;

* sinNndda.reph: L&lt;&lt;238.0,512.0&gt;--&lt;238.0,512.0&gt;&gt; -&gt; L&lt;&lt;238.0,512.0&gt;--&lt;238.0,512.0&gt;&gt;

* sinSI: L&lt;&lt;360.0,285.0&gt;--&lt;360.0,287.0&gt;&gt; -&gt; L&lt;&lt;360.0,287.0&gt;--&lt;360.0,290.0&gt;&gt;

* sinSI: L&lt;&lt;360.0,287.0&gt;--&lt;360.0,290.0&gt;&gt; -&gt; L&lt;&lt;360.0,290.0&gt;--&lt;360.0,291.0&gt;&gt;

* sinSRI: L&lt;&lt;381.0,285.0&gt;--&lt;381.0,287.0&gt;&gt; -&gt; L&lt;&lt;381.0,287.0&gt;--&lt;381.0,290.0&gt;&gt;

* sinSRI: L&lt;&lt;381.0,287.0&gt;--&lt;381.0,290.0&gt;&gt; -&gt; L&lt;&lt;381.0,290.0&gt;--&lt;381.0,291.0&gt;&gt;

* sinYI: L&lt;&lt;364.0,320.0&gt;--&lt;364.0,322.0&gt;&gt; -&gt; L&lt;&lt;364.0,322.0&gt;--&lt;364.0,324.0&gt;&gt;

* sinYIi: L&lt;&lt;364.0,316.0&gt;--&lt;364.0,318.0&gt;&gt; -&gt; L&lt;&lt;364.0,318.0&gt;--&lt;364.0,319.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* sinBhIi: B&lt;&lt;370.0,297.0&gt;-&lt;364.0,297.0&gt;-&lt;358.0,296.0&gt;&gt;/L&lt;&lt;358.0,296.0&gt;--&lt;358.0,296.0&gt;&gt; = 9.462322208025613

* sinBhIi: L&lt;&lt;358.0,296.0&gt;--&lt;358.0,296.0&gt;&gt;/B&lt;&lt;358.0,296.0&gt;-&lt;309.0,292.0&gt;-&lt;281.0,257.0&gt;&gt; = 4.666858371438958

* sinBhRIi: B&lt;&lt;370.0,297.0&gt;-&lt;364.0,297.0&gt;-&lt;358.0,296.0&gt;&gt;/L&lt;&lt;358.0,296.0&gt;--&lt;358.0,296.0&gt;&gt; = 9.462322208025613

* sinBhRIi: L&lt;&lt;358.0,296.0&gt;--&lt;358.0,296.0&gt;&gt;/B&lt;&lt;358.0,296.0&gt;-&lt;309.0,292.0&gt;-&lt;281.0,257.0&gt;&gt; = 4.666858371438958

* sinBhU.reph: B&lt;&lt;83.5,235.0&gt;-&lt;97.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;94.5,247.0&gt;&gt; = 9.462322208025613

* sinBhU: B&lt;&lt;83.5,235.0&gt;-&lt;97.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;94.5,247.0&gt;&gt; = 9.462322208025613

* sinBhUu.reph: B&lt;&lt;83.5,235.0&gt;-&lt;97.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;94.5,247.0&gt;&gt; = 9.462322208025613

* sinBhUu: B&lt;&lt;83.5,235.0&gt;-&lt;97.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;94.5,247.0&gt;&gt; = 9.462322208025613

* sinCh.virama: B&lt;&lt;334.0,293.0&gt;-&lt;334.0,276.0&gt;-&lt;308.0,267.0&gt;&gt;/B&lt;&lt;308.0,267.0&gt;-&lt;318.0,269.0&gt;-&lt;333.0,266.5&gt;&gt; = 7.7835595264653525

* sinChR.virama: B&lt;&lt;334.0,293.0&gt;-&lt;334.0,276.0&gt;-&lt;308.0,267.0&gt;&gt;/B&lt;&lt;308.0,267.0&gt;-&lt;318.0,269.0&gt;-&lt;333.0,266.5&gt;&gt; = 7.7835595264653525

* sinChU.reph: B&lt;&lt;326.5,295.5&gt;-&lt;319.0,286.0&gt;-&lt;302.0,279.0&gt;&gt;/B&lt;&lt;302.0,279.0&gt;-&lt;313.0,281.0&gt;-&lt;330.0,279.0&gt;&gt; = 12.075288583193531

* sinChU.reph: B&lt;&lt;362.5,221.0&gt;-&lt;349.0,246.0&gt;-&lt;326.0,254.0&gt;&gt;/B&lt;&lt;326.0,254.0&gt;-&lt;337.0,247.0&gt;-&lt;341.0,236.0&gt;&gt; = 13.292184265037774

* sinChUu.reph: B&lt;&lt;326.5,295.5&gt;-&lt;319.0,286.0&gt;-&lt;302.0,279.0&gt;&gt;/B&lt;&lt;302.0,279.0&gt;-&lt;313.0,281.0&gt;-&lt;330.0,279.0&gt;&gt; = 12.075288583193531

* sinChUu.reph: B&lt;&lt;362.5,221.0&gt;-&lt;349.0,246.0&gt;-&lt;326.0,254.0&gt;&gt;/B&lt;&lt;326.0,254.0&gt;-&lt;337.0,247.0&gt;-&lt;341.0,236.0&gt;&gt; = 13.292184265037774

* sinCha.reph: B&lt;&lt;326.5,295.5&gt;-&lt;319.0,286.0&gt;-&lt;302.0,279.0&gt;&gt;/B&lt;&lt;302.0,279.0&gt;-&lt;313.0,281.0&gt;-&lt;330.0,279.0&gt;&gt; = 12.075288583193531

* sinCha.reph: B&lt;&lt;362.5,221.0&gt;-&lt;349.0,246.0&gt;-&lt;326.0,254.0&gt;&gt;/B&lt;&lt;326.0,254.0&gt;-&lt;337.0,247.0&gt;-&lt;341.0,236.0&gt;&gt; = 13.292184265037774

* sinDR.virama: B&lt;&lt;211.5,298.5&gt;-&lt;224.0,292.0&gt;-&lt;227.0,289.0&gt;&gt;/B&lt;&lt;227.0,289.0&gt;-&lt;222.0,297.0&gt;-&lt;222.0,305.0&gt;&gt; = 12.994616791916455

* sinDRI: B&lt;&lt;211.5,298.5&gt;-&lt;224.0,292.0&gt;-&lt;227.0,289.0&gt;&gt;/B&lt;&lt;227.0,289.0&gt;-&lt;222.0,297.0&gt;-&lt;222.0,305.0&gt;&gt; = 12.994616791916455

* sinDRIi: B&lt;&lt;211.5,298.5&gt;-&lt;224.0,292.0&gt;-&lt;227.0,289.0&gt;&gt;/B&lt;&lt;227.0,289.0&gt;-&lt;222.0,297.0&gt;-&lt;222.0,305.0&gt;&gt; = 12.994616791916455

* sinDRa: B&lt;&lt;211.5,298.5&gt;-&lt;224.0,292.0&gt;-&lt;227.0,289.0&gt;&gt;/B&lt;&lt;227.0,289.0&gt;-&lt;222.0,297.0&gt;-&lt;222.0,305.0&gt;&gt; = 12.994616791916455

* sinDd.virama: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdI: B&lt;&lt;71.5,233.5&gt;-&lt;92.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;95.0,247.0&gt;&gt; = 9.462322208025613

* sinDdIi: B&lt;&lt;359.0,415.0&gt;-&lt;355.0,405.0&gt;-&lt;346.0,396.0&gt;&gt;/B&lt;&lt;346.0,396.0&gt;-&lt;383.0,419.0&gt;-&lt;383.0,465.0&gt;&gt; = 13.134022306396298

* sinDdIi: B&lt;&lt;71.5,233.5&gt;-&lt;92.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;95.0,247.0&gt;&gt; = 9.462322208025613

* sinDdR.virama: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdRI: B&lt;&lt;71.5,233.5&gt;-&lt;92.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;95.0,247.0&gt;&gt; = 9.462322208025613

* sinDdRIi: B&lt;&lt;359.0,415.0&gt;-&lt;355.0,405.0&gt;-&lt;346.0,396.0&gt;&gt;/B&lt;&lt;346.0,396.0&gt;-&lt;383.0,419.0&gt;-&lt;383.0,465.0&gt;&gt; = 13.134022306396298

* sinDdRIi: B&lt;&lt;71.5,233.5&gt;-&lt;92.0,246.0&gt;-&lt;106.0,246.0&gt;&gt;/B&lt;&lt;106.0,246.0&gt;-&lt;100.0,247.0&gt;-&lt;95.0,247.0&gt;&gt; = 9.462322208025613

* sinDdRa: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdU.reph: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdU: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdUu.reph: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdUu: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDda (U+0DA9): B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDda.reph: B&lt;&lt;71.5,230.5&gt;-&lt;92.0,243.0&gt;-&lt;106.0,243.0&gt;&gt;/B&lt;&lt;106.0,243.0&gt;-&lt;100.0,244.0&gt;-&lt;95.0,244.0&gt;&gt; = 9.462322208025613

* sinDdh.virama: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhI: B&lt;&lt;77.5,225.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhIi: B&lt;&lt;77.5,225.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhR.virama: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhRI: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhRIi: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhRa: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhU.reph: B&lt;&lt;77.5,225.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhU: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhUu.reph: B&lt;&lt;77.5,225.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdhUu: B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdha (U+0DAA): B&lt;&lt;77.5,224.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinDdha.reph: B&lt;&lt;77.5,225.0&gt;-&lt;99.0,237.0&gt;-&lt;114.0,237.0&gt;&gt;/B&lt;&lt;114.0,237.0&gt;-&lt;107.0,238.0&gt;-&lt;101.0,238.0&gt;&gt; = 8.13010235415596

* sinGRI: B&lt;&lt;447.5,255.5&gt;-&lt;417.0,292.0&gt;-&lt;371.0,298.0&gt;&gt;/L&lt;&lt;371.0,298.0&gt;--&lt;371.0,298.0&gt;&gt; = 7.431407971172489

* sinGRI: L&lt;&lt;371.0,298.0&gt;--&lt;371.0,298.0&gt;&gt;/B&lt;&lt;371.0,298.0&gt;-&lt;364.0,299.0&gt;-&lt;357.0,299.0&gt;&gt; = 8.13010235415596

* sinGUu.reph: B&lt;&lt;356.0,1.0&gt;-&lt;338.0,-2.0&gt;-&lt;323.0,0.0&gt;&gt;/B&lt;&lt;323.0,0.0&gt;-&lt;334.0,-4.0&gt;-&lt;346.0,-7.5&gt;&gt; = 12.388463153308525

* sinGUu: B&lt;&lt;356.0,1.0&gt;-&lt;338.0,-2.0&gt;-&lt;323.0,0.0&gt;&gt;/B&lt;&lt;323.0,0.0&gt;-&lt;334.0,-4.0&gt;-&lt;346.0,-7.5&gt;&gt; = 12.388463153308525

* sinGh.virama: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhI: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhIi: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhR.virama: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhRI: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhRIi: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhRa: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhU.reph: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhU: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhUu.reph: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGhUu: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGha (U+0D9D): B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinGha.reph: B&lt;&lt;71.5,236.0&gt;-&lt;92.0,250.0&gt;-&lt;106.0,250.0&gt;&gt;/B&lt;&lt;106.0,250.0&gt;-&lt;100.0,251.0&gt;-&lt;95.0,251.0&gt;&gt; = 9.462322208025613

* sinIi (U+0D8A): B&lt;&lt;144.5,377.5&gt;-&lt;113.0,338.0&gt;-&lt;96.0,312.0&gt;&gt;/B&lt;&lt;96.0,312.0&gt;-&lt;110.0,326.0&gt;-&lt;134.5,337.5&gt;&gt; = 11.821488340607257

* sinNd.virama: B&lt;&lt;285.0,298.5&gt;-&lt;297.0,292.0&gt;-&lt;300.0,289.0&gt;&gt;/B&lt;&lt;300.0,289.0&gt;-&lt;295.0,297.0&gt;-&lt;295.0,307.0&gt;&gt; = 12.994616791916455

* sinNdI: B&lt;&lt;285.0,298.5&gt;-&lt;297.0,292.0&gt;-&lt;300.0,289.0&gt;&gt;/B&lt;&lt;300.0,289.0&gt;-&lt;295.0,297.0&gt;-&lt;295.0,307.0&gt;&gt; = 12.994616791916455

* sinNdIi: B&lt;&lt;285.0,298.5&gt;-&lt;297.0,292.0&gt;-&lt;300.0,289.0&gt;&gt;/B&lt;&lt;300.0,289.0&gt;-&lt;295.0,297.0&gt;-&lt;295.0,307.0&gt;&gt; = 12.994616791916455

* sinNdU: B&lt;&lt;285.0,298.5&gt;-&lt;297.0,292.0&gt;-&lt;300.0,289.0&gt;&gt;/B&lt;&lt;300.0,289.0&gt;-&lt;292.0,301.0&gt;-&lt;298.0,317.0&gt;&gt; = 11.309932474020195

* sinNdUu: B&lt;&lt;285.0,298.5&gt;-&lt;297.0,292.0&gt;-&lt;300.0,289.0&gt;&gt;/B&lt;&lt;300.0,289.0&gt;-&lt;292.0,301.0&gt;-&lt;298.0,317.0&gt;&gt; = 11.309932474020195

* sinNda (U+0DB3): B&lt;&lt;285.0,298.5&gt;-&lt;297.0,292.0&gt;-&lt;300.0,289.0&gt;&gt;/B&lt;&lt;300.0,289.0&gt;-&lt;295.0,297.0&gt;-&lt;295.0,307.0&gt;&gt; = 12.994616791916455

* sinNda.reph: B&lt;&lt;324.0,298.5&gt;-&lt;336.0,292.0&gt;-&lt;339.0,289.0&gt;&gt;/B&lt;&lt;339.0,289.0&gt;-&lt;334.0,297.0&gt;-&lt;334.0,307.0&gt;&gt; = 12.994616791916455

* sinNnAa.virama: B&lt;&lt;615.5,318.5&gt;-&lt;632.0,302.0&gt;-&lt;635.0,279.0&gt;&gt;/B&lt;&lt;635.0,279.0&gt;-&lt;637.0,298.0&gt;-&lt;649.5,312.5&gt;&gt; = 13.440413928666997

* sinNnAa: B&lt;&lt;615.5,318.5&gt;-&lt;632.0,302.0&gt;-&lt;635.0,279.0&gt;&gt;/B&lt;&lt;635.0,279.0&gt;-&lt;637.0,302.0&gt;-&lt;654.5,317.5&gt;&gt; = 12.401148699282784

* sinNnI: B&lt;&lt;393.0,246.0&gt;-&lt;393.0,233.0&gt;-&lt;396.0,213.0&gt;&gt;/L&lt;&lt;396.0,213.0&gt;--&lt;396.0,214.0&gt;&gt; = 8.530765609948139

* sinNnI: L&lt;&lt;396.0,213.0&gt;--&lt;396.0,214.0&gt;&gt;/B&lt;&lt;396.0,214.0&gt;-&lt;398.0,205.0&gt;-&lt;399.0,195.5&gt;&gt; = 12.528807709151492

* sinNnIi: B&lt;&lt;393.0,246.0&gt;-&lt;393.0,233.0&gt;-&lt;396.0,213.0&gt;&gt;/L&lt;&lt;396.0,213.0&gt;--&lt;396.0,214.0&gt;&gt; = 8.530765609948139

* sinNnIi: L&lt;&lt;396.0,213.0&gt;--&lt;396.0,214.0&gt;&gt;/B&lt;&lt;396.0,214.0&gt;-&lt;398.0,205.0&gt;-&lt;399.0,195.5&gt;&gt; = 12.528807709151492

* sinNna.reph: B&lt;&lt;393.0,246.0&gt;-&lt;393.0,233.0&gt;-&lt;396.0,210.0&gt;&gt;/L&lt;&lt;396.0,210.0&gt;--&lt;396.0,212.0&gt;&gt; = 7.431407971172489

* sinNna.reph: L&lt;&lt;396.0,210.0&gt;--&lt;396.0,212.0&gt;&gt;/B&lt;&lt;396.0,212.0&gt;-&lt;399.0,193.0&gt;-&lt;399.0,173.0&gt;&gt; = 8.972626614896358

* sinNnddIi: B&lt;&lt;453.0,415.0&gt;-&lt;449.0,405.0&gt;-&lt;440.0,396.0&gt;&gt;/B&lt;&lt;440.0,396.0&gt;-&lt;477.0,419.0&gt;-&lt;477.0,465.0&gt;&gt; = 13.134022306396298

* sinNngUu: B&lt;&lt;406.5,-0.5&gt;-&lt;399.0,0.0&gt;-&lt;393.0,1.0&gt;&gt;/B&lt;&lt;393.0,1.0&gt;-&lt;404.0,-3.0&gt;-&lt;416.5,-6.5&gt;&gt; = 10.52078431387435

* sinNyAa: B&lt;&lt;559.5,451.5&gt;-&lt;490.0,423.0&gt;-&lt;421.0,361.0&gt;&gt;/B&lt;&lt;421.0,361.0&gt;-&lt;466.0,386.0&gt;-&lt;512.0,386.0&gt;&gt; = 12.886698326826988

* sinR.virama: B&lt;&lt;132.0,357.5&gt;-&lt;101.0,330.0&gt;-&lt;87.0,314.0&gt;&gt;/B&lt;&lt;87.0,314.0&gt;-&lt;108.0,334.0&gt;-&lt;136.0,346.0&gt;&gt; = 5.211255861586706

* sinRAae: B&lt;&lt;189.5,597.0&gt;-&lt;190.0,597.0&gt;-&lt;188.0,596.0&gt;&gt;/B&lt;&lt;188.0,596.0&gt;-&lt;197.0,602.0&gt;-&lt;204.0,599.0&gt;&gt; = 7.125016348901757

* sinRI: B&lt;&lt;132.0,357.5&gt;-&lt;101.0,330.0&gt;-&lt;87.0,314.0&gt;&gt;/B&lt;&lt;87.0,314.0&gt;-&lt;108.0,333.0&gt;-&lt;136.0,345.5&gt;&gt; = 6.676480060402135

* sinRIi: B&lt;&lt;135.0,357.5&gt;-&lt;104.0,330.0&gt;-&lt;90.0,314.0&gt;&gt;/B&lt;&lt;90.0,314.0&gt;-&lt;111.0,333.0&gt;-&lt;139.0,345.5&gt;&gt; = 6.676480060402135

* sinSs.virama: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsI: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsIi: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsR.virama: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsRI: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsRIi: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsRa: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsU.reph: B&lt;&lt;373.0,269.0&gt;-&lt;363.0,259.0&gt;-&lt;349.0,257.0&gt;&gt;/B&lt;&lt;349.0,257.0&gt;-&lt;395.0,257.0&gt;-&lt;421.5,224.5&gt;&gt; = 8.13010235415596

* sinSsU: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsUu.reph: B&lt;&lt;373.0,269.0&gt;-&lt;363.0,259.0&gt;-&lt;349.0,257.0&gt;&gt;/B&lt;&lt;349.0,257.0&gt;-&lt;395.0,257.0&gt;-&lt;421.5,224.5&gt;&gt; = 8.13010235415596

* sinSsUu: B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsa (U+0DC2): B&lt;&lt;344.0,269.0&gt;-&lt;334.0,259.0&gt;-&lt;320.0,257.0&gt;&gt;/B&lt;&lt;320.0,257.0&gt;-&lt;366.0,257.0&gt;-&lt;392.5,224.5&gt;&gt; = 8.13010235415596

* sinSsa.reph: B&lt;&lt;373.0,269.0&gt;-&lt;363.0,259.0&gt;-&lt;349.0,257.0&gt;&gt;/B&lt;&lt;349.0,257.0&gt;-&lt;395.0,257.0&gt;-&lt;421.5,224.5&gt;&gt; = 8.13010235415596
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* sinDhU.reph: L&lt;&lt;382.0,-208.0&gt;--&lt;383.0,19.0&gt;&gt;

* sinDhU.reph: L&lt;&lt;413.0,55.0&gt;--&lt;411.0,-235.0&gt;&gt;

* sinR.virama: L&lt;&lt;37.0,406.0&gt;--&lt;38.0,533.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'MNIK' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-use-typo-metrics">googlefonts/use_typo_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Galle-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 13 | 13 | 112 | 6 | 94 | 0 | 
| 0% | 0% | 5% | 5% | 47% | 3% | 39% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
