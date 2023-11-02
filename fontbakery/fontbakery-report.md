## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[7] Gelasio-SemiBoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Oslash
	* greaterequal
	* Oslashacute
	* uni2105
	* lessequal
	* Eng
	* OSlash_part. and summation
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- Lslash_part 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2
	- Glyph name: uni01EB	Contours detected: 3	Expected: 2 
	- And 35 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1198.0,817.5>-<1116.0,763.0>-<1006.0,752.0>>/B<<1006.0,752.0>-<1100.0,746.0>-<1186.5,711.5>> = 9.362815917805918
	* Bmacronbelow (U+1E06): B<<1198.0,817.5>-<1116.0,763.0>-<1006.0,752.0>>/B<<1006.0,752.0>-<1100.0,746.0>-<1186.5,711.5>> = 9.362815917805918
	* a (U+0061): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* aacute (U+00E1): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* abreve (U+0103): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* acircumflex (U+00E2): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* adieresis (U+00E4): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* agrave (U+00E0): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* amacron (U+0101): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047
	* aogonek (U+0105): B<<814.5,326.5>-<823.0,368.0>-<827.0,389.0>>/B<<827.0,389.0>-<804.0,335.0>-<760.0,264.5>> = 12.286114382262047 and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Gelasio-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Lslash
	* uni028C
	* Aringacute
	* uni2105 and Eng
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- .null
	- OSlash_part. 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 
	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* M (U+004D): L<<636.0,1419.0>--<926.0,563.0>> -> L<<926.0,563.0>--<998.0,388.0>>
	* OE (U+0152): L<<998.0,141.0>--<999.0,1062.0>> -> L<<999.0,1062.0>--<999.0,1278.0>>
	* Z (U+005A): L<<107.0,123.0>--<815.0,1202.0>> -> L<<815.0,1202.0>--<908.0,1336.0>>
	* Z (U+005A): L<<1187.0,1340.0>--<466.0,242.0>> -> L<<466.0,242.0>--<358.0,83.0>>
	* Zacute (U+0179): L<<107.0,123.0>--<815.0,1202.0>> -> L<<815.0,1202.0>--<908.0,1336.0>>
	* Zacute (U+0179): L<<1187.0,1340.0>--<466.0,242.0>> -> L<<466.0,242.0>--<358.0,83.0>>
	* Zcaron (U+017D): L<<107.0,123.0>--<815.0,1202.0>> -> L<<815.0,1202.0>--<908.0,1336.0>>
	* Zcaron (U+017D): L<<1187.0,1340.0>--<466.0,242.0>> -> L<<466.0,242.0>--<358.0,83.0>>
	* Zdotaccent (U+017B): L<<107.0,123.0>--<815.0,1202.0>> -> L<<815.0,1202.0>--<908.0,1336.0>>
	* Zdotaccent (U+017B): L<<1187.0,1340.0>--<466.0,242.0>> -> L<<466.0,242.0>--<358.0,83.0>> and 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* three (U+0033): B<<822.5,523.0>-<745.0,471.0>-<672.0,456.0>>/B<<672.0,456.0>-<770.0,455.0>-<862.0,415.5>> = 12.196116944593669
	* threeeighths (U+215C): B<<656.0,1052.5>-<598.0,1022.0>-<536.0,1012.0>>/B<<536.0,1012.0>-<618.0,1011.0>-<687.5,989.0>> = 9.861041428705136
	* threequarters (U+00BE): B<<735.0,1052.5>-<677.0,1022.0>-<615.0,1012.0>>/B<<615.0,1012.0>-<697.0,1011.0>-<766.5,989.0>> = 9.861041428705136
	* trademark (U+2122): L<<1347.0,850.0>--<1348.0,855.0>>/L<<1348.0,855.0>--<1346.0,850.0>> = 10.491477012331565
	* uni00B3 (U+00B3): B<<716.0,1302.5>-<658.0,1272.0>-<596.0,1262.0>>/B<<596.0,1262.0>-<678.0,1261.0>-<747.5,1239.0>> = 9.861041428705136
	* uni0190 (U+0190): B<<320.0,724.0>-<412.0,759.0>-<509.0,760.0>>/B<<509.0,760.0>-<437.0,775.0>-<359.5,812.5>> = 12.358946146667314
	* uni025B (U+025B): B<<247.5,504.5>-<323.0,530.0>-<408.0,530.0>>/B<<408.0,530.0>-<338.0,541.0>-<276.0,571.0>> = 8.93059010041899
	* uni2083 (U+2083): B<<716.0,310.5>-<658.0,280.0>-<596.0,270.0>>/B<<596.0,270.0>-<678.0,269.0>-<747.5,247.0>> = 9.861041428705136
	* uni2153 (U+2153): B<<1831.0,546.5>-<1773.0,516.0>-<1711.0,506.0>>/B<<1711.0,506.0>-<1793.0,505.0>-<1862.5,483.0>> = 9.861041428705136 and uni2154 (U+2154): B<<1863.0,546.5>-<1805.0,516.0>-<1743.0,506.0>>/B<<1743.0,506.0>-<1825.0,505.0>-<1894.5,483.0>> = 9.861041428705136 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<1128.0,1320.0>--<1127.0,750.0>>
 * AE (U+00C6): L<<1870.0,1.0>--<741.0,0.0>>
 * AE (U+00C6): L<<465.0,1419.0>--<1784.0,1418.0>>
 * AEacute (U+01FC): L<<1128.0,1320.0>--<1127.0,750.0>>
 * AEacute (U+01FC): L<<1870.0,1.0>--<741.0,0.0>>
 * AEacute (U+01FC): L<<465.0,1419.0>--<1784.0,1418.0>>
 * B (U+0042): L<<282.0,152.0>--<283.0,1234.0>>
 * Bmacronbelow (U+1E06): L<<282.0,152.0>--<283.0,1234.0>>
 * D (U+0044): L<<521.0,1322.0>--<520.0,168.0>>
 * Dcaron (U+010E): L<<521.0,1322.0>--<520.0,168.0>> and 546 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Gelasio-MediumItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Oslash
	* greaterequal
	* Oslashacute
	* uni2105
	* lessequal
	* Eng
	* OSlash_part. and summation
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- Lslash_part 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2
	- Glyph name: uni01EB	Contours detected: 3	Expected: 2 
	- And 33 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1100.5,829.5>-<1019.0,774.0>-<921.0,762.0>>/B<<921.0,762.0>-<1002.0,753.0>-<1083.0,721.0>> = 13.321249152739702
	* Bmacronbelow (U+1E06): B<<1100.5,829.5>-<1019.0,774.0>-<921.0,762.0>>/B<<921.0,762.0>-<1002.0,753.0>-<1083.0,721.0>> = 13.321249152739702
	* a (U+0061): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* aacute (U+00E1): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* abreve (U+0103): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* acircumflex (U+00E2): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* adieresis (U+00E4): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* agrave (U+00E0): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* amacron (U+0101): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272
	* aogonek (U+0105): B<<747.5,273.0>-<758.0,330.0>-<764.0,364.0>>/B<<764.0,364.0>-<745.0,313.0>-<706.0,246.5>> = 10.424848877957272 and 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Gelasio-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1E20
	* Umacron
	* uni0218
	* Omacron
	* uni1E14
	* uni022C
	* uni0156
	* Lslash
	* uni0145
	* Emacron and 19 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- .null
	- OSlash_part. 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 
	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* M (U+004D): L<<700.0,1419.0>--<809.0,1095.0>> -> L<<809.0,1095.0>--<1046.0,447.0>>
	* OE (U+0152): L<<1026.0,142.0>--<1027.0,486.0>> -> L<<1027.0,486.0>--<1027.0,1285.0>>
	* Z (U+005A): L<<107.0,123.0>--<822.0,1204.0>> -> L<<822.0,1204.0>--<919.0,1336.0>>
	* Z (U+005A): L<<1271.0,1340.0>--<530.0,224.0>> -> L<<530.0,224.0>--<429.0,83.0>>
	* Zacute (U+0179): L<<107.0,123.0>--<822.0,1204.0>> -> L<<822.0,1204.0>--<919.0,1336.0>>
	* Zacute (U+0179): L<<1271.0,1340.0>--<530.0,224.0>> -> L<<530.0,224.0>--<429.0,83.0>>
	* Zcaron (U+017D): L<<107.0,123.0>--<822.0,1204.0>> -> L<<822.0,1204.0>--<919.0,1336.0>>
	* Zcaron (U+017D): L<<1271.0,1340.0>--<530.0,224.0>> -> L<<530.0,224.0>--<429.0,83.0>>
	* Zdotaccent (U+017B): L<<107.0,123.0>--<822.0,1204.0>> -> L<<822.0,1204.0>--<919.0,1336.0>>
	* Zdotaccent (U+017B): L<<1271.0,1340.0>--<530.0,224.0>> -> L<<530.0,224.0>--<429.0,83.0>> and 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1158.5,821.5>-<1087.0,780.0>-<1000.0,768.0>>/B<<1000.0,768.0>-<1115.0,761.0>-<1207.5,720.0>> = 11.33658477097587
	* Bmacronbelow (U+1E06): B<<1158.5,821.5>-<1087.0,780.0>-<1000.0,768.0>>/B<<1000.0,768.0>-<1115.0,761.0>-<1207.5,720.0>> = 11.33658477097587
	* three (U+0033): B<<897.5,523.0>-<818.0,471.0>-<728.0,456.0>>/B<<728.0,456.0>-<846.0,455.0>-<941.5,411.0>> = 9.947868038033734
	* threeeighths (U+215C): B<<758.5,1101.0>-<686.0,1037.0>-<578.0,1022.0>>/B<<578.0,1022.0>-<719.0,1021.0>-<801.5,964.5>> = 8.313508936267434
	* threequarters (U+00BE): B<<794.5,1101.0>-<722.0,1037.0>-<614.0,1022.0>>/B<<614.0,1022.0>-<755.0,1021.0>-<837.5,964.5>> = 8.313508936267434
	* trademark (U+2122): L<<1347.0,850.0>--<1348.0,855.0>>/L<<1348.0,855.0>--<1346.0,850.0>> = 10.491477012331565
	* underscore (U+005F): L<<1011.0,-190.0>--<1428.0,-264.0>>/L<<1428.0,-264.0>--<392.0,-296.0>> = 11.832029585676132
	* underscore (U+005F): L<<392.0,-296.0>--<-25.0,-222.0>>/L<<-25.0,-222.0>--<1011.0,-190.0>> = 11.83202958567607
	* uni00B3 (U+00B3): B<<824.5,1344.0>-<752.0,1280.0>-<644.0,1265.0>>/B<<644.0,1265.0>-<785.0,1264.0>-<867.5,1207.5>> = 8.313508936267434
	* uni0181 (U+0181): B<<1344.0,822.0>-<1273.0,780.0>-<1187.0,768.0>>/B<<1187.0,768.0>-<1301.0,760.0>-<1393.0,719.5>> = 11.957647506001463 and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * A (U+0041): L<<901.0,482.0>--<422.0,483.0>>
 * AE (U+00C6): L<<1260.0,1320.0>--<1259.0,767.0>>
 * AEacute (U+01FC): L<<1260.0,1320.0>--<1259.0,767.0>>
 * Aacute (U+00C1): L<<901.0,482.0>--<422.0,483.0>>
 * Abreve (U+0102): L<<901.0,482.0>--<422.0,483.0>>
 * Acircumflex (U+00C2): L<<901.0,482.0>--<422.0,483.0>>
 * Adieresis (U+00C4): L<<901.0,482.0>--<422.0,483.0>>
 * Agrave (U+00C0): L<<901.0,482.0>--<422.0,483.0>>
 * Amacron (U+0100): L<<901.0,482.0>--<422.0,483.0>>
 * Aogonek (U+0104): L<<901.0,482.0>--<422.0,483.0>> and 415 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Gelasio-BoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Oslash
	* greaterequal
	* Oslashacute
	* uni1EDB
	* uni2105
	* Eng
	* OSlash_part. and summation
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- Lslash_part 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2
	- Glyph name: uni01EB	Contours detected: 3	Expected: 2 
	- And 33 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1256.5,810.5>-<1175.0,756.0>-<1057.0,747.0>>/B<<1057.0,747.0>-<1159.0,742.0>-<1249.0,706.0>> = 7.16794289680882
	* Bmacronbelow (U+1E06): B<<1256.5,810.5>-<1175.0,756.0>-<1057.0,747.0>>/B<<1057.0,747.0>-<1159.0,742.0>-<1249.0,706.0>> = 7.16794289680882
	* a (U+0061): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* aacute (U+00E1): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* abreve (U+0103): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* acircumflex (U+00E2): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* adieresis (U+00E4): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* agrave (U+00E0): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* amacron (U+0101): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819
	* aogonek (U+0105): B<<851.5,343.0>-<861.0,386.0>-<864.0,404.0>>/B<<864.0,404.0>-<839.0,347.0>-<792.5,274.5>> = 14.219765516512819 and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Gelasio-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Lslash
	* uni028C
	* uni2105
	* Eng and v
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- .null
	- OSlash_part. 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 
	- And 39 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* OE (U+0152): L<<988.0,141.0>--<989.0,1274.0>> -> L<<989.0,1274.0>--<989.0,1275.0>>
	* Z (U+005A): L<<107.0,123.0>--<812.0,1201.0>> -> L<<812.0,1201.0>--<904.0,1336.0>>
	* Z (U+005A): L<<1156.0,1340.0>--<442.0,248.0>> -> L<<442.0,248.0>--<331.0,83.0>>
	* Zacute (U+0179): L<<107.0,123.0>--<812.0,1201.0>> -> L<<812.0,1201.0>--<904.0,1336.0>>
	* Zacute (U+0179): L<<1156.0,1340.0>--<442.0,248.0>> -> L<<442.0,248.0>--<331.0,83.0>>
	* Zcaron (U+017D): L<<107.0,123.0>--<812.0,1201.0>> -> L<<812.0,1201.0>--<904.0,1336.0>>
	* Zcaron (U+017D): L<<1156.0,1340.0>--<442.0,248.0>> -> L<<442.0,248.0>--<331.0,83.0>>
	* Zdotaccent (U+017B): L<<107.0,123.0>--<812.0,1201.0>> -> L<<812.0,1201.0>--<904.0,1336.0>>
	* Zdotaccent (U+017B): L<<1156.0,1340.0>--<442.0,248.0>> -> L<<442.0,248.0>--<331.0,83.0>>
	* Zmacronbelow (U+1E94): L<<107.0,123.0>--<812.0,1201.0>> -> L<<812.0,1201.0>--<904.0,1336.0>> and 76 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* three (U+0033): B<<758.0,499.5>-<701.0,467.0>-<652.0,456.0>>/B<<652.0,456.0>-<742.0,455.0>-<832.5,417.5>> = 13.289150076521446
	* threeeighths (U+215C): B<<637.0,1048.5>-<579.0,1019.0>-<521.0,1008.0>>/B<<521.0,1008.0>-<598.0,1008.0>-<667.5,986.5>> = 10.738897100905428
	* threequarters (U+00BE): B<<732.0,1048.5>-<674.0,1019.0>-<616.0,1008.0>>/B<<616.0,1008.0>-<693.0,1008.0>-<762.5,986.5>> = 10.738897100905428
	* trademark (U+2122): L<<1347.0,850.0>--<1348.0,855.0>>/L<<1348.0,855.0>--<1346.0,850.0>> = 10.491477012331565
	* uni00B3 (U+00B3): B<<695.0,1301.5>-<637.0,1272.0>-<579.0,1261.0>>/B<<579.0,1261.0>-<656.0,1261.0>-<725.5,1239.5>> = 10.738897100905428
	* uni0190 (U+0190): B<<325.5,725.0>-<416.0,760.0>-<506.0,761.0>>/B<<506.0,761.0>-<457.0,772.0>-<400.0,794.5>> = 13.289150076521446
	* uni0246 (U+0246): B<<804.0,860.0>-<824.0,907.0>-<831.0,937.0>>/L<<831.0,937.0>--<757.0,791.0>> = 13.744117445702306
	* uni025B (U+025B): B<<242.5,504.5>-<317.0,531.0>-<403.0,531.0>>/B<<403.0,531.0>-<340.0,542.0>-<278.0,570.5>> = 9.904183212973862
	* uni2083 (U+2083): B<<695.0,308.5>-<637.0,279.0>-<579.0,268.0>>/B<<579.0,268.0>-<656.0,268.0>-<725.5,246.5>> = 10.738897100905428
	* uni2153 (U+2153): B<<1806.0,544.5>-<1748.0,515.0>-<1690.0,504.0>>/B<<1690.0,504.0>-<1767.0,504.0>-<1836.5,482.5>> = 10.738897100905428 and uni2154 (U+2154): B<<1836.0,544.5>-<1778.0,515.0>-<1720.0,504.0>>/B<<1720.0,504.0>-<1797.0,504.0>-<1866.5,482.5>> = 10.738897100905428 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<1079.0,1320.0>--<1078.0,743.0>>
 * AE (U+00C6): L<<1812.0,1.0>--<717.0,0.0>>
 * AE (U+00C6): L<<451.0,1419.0>--<1732.0,1418.0>>
 * AEacute (U+01FC): L<<1079.0,1320.0>--<1078.0,743.0>>
 * AEacute (U+01FC): L<<1812.0,1.0>--<717.0,0.0>>
 * AEacute (U+01FC): L<<451.0,1419.0>--<1732.0,1418.0>>
 * B (U+0042): L<<274.0,152.0>--<275.0,1234.0>>
 * Bmacronbelow (U+1E06): L<<274.0,152.0>--<275.0,1234.0>>
 * D (U+0044): L<<497.0,1322.0>--<496.0,168.0>>
 * Dcaron (U+010E): L<<497.0,1322.0>--<496.0,168.0>> and 563 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] Gelasio-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1E20
	* Umacron
	* uni0218
	* Omacron
	* uni1E14
	* uni022C
	* uni0156
	* Lslash
	* uni0145
	* Emacron and 18 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- .null
	- OSlash_part. 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 
	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* Z (U+005A): L<<107.0,123.0>--<827.0,1205.0>> -> L<<827.0,1205.0>--<926.0,1336.0>>
	* Z (U+005A): L<<1321.0,1340.0>--<569.0,214.0>> -> L<<569.0,214.0>--<471.0,83.0>>
	* Zacute (U+0179): L<<107.0,123.0>--<827.0,1205.0>> -> L<<827.0,1205.0>--<926.0,1336.0>>
	* Zacute (U+0179): L<<1321.0,1340.0>--<569.0,214.0>> -> L<<569.0,214.0>--<471.0,83.0>>
	* Zcaron (U+017D): L<<107.0,123.0>--<827.0,1205.0>> -> L<<827.0,1205.0>--<926.0,1336.0>>
	* Zcaron (U+017D): L<<1321.0,1340.0>--<569.0,214.0>> -> L<<569.0,214.0>--<471.0,83.0>>
	* Zdotaccent (U+017B): L<<107.0,123.0>--<827.0,1205.0>> -> L<<827.0,1205.0>--<926.0,1336.0>>
	* Zdotaccent (U+017B): L<<1321.0,1340.0>--<569.0,214.0>> -> L<<569.0,214.0>--<471.0,83.0>>
	* Zmacronbelow (U+1E94): L<<107.0,123.0>--<827.0,1205.0>> -> L<<827.0,1205.0>--<926.0,1336.0>>
	* Zmacronbelow (U+1E94): L<<1321.0,1340.0>--<569.0,214.0>> -> L<<569.0,214.0>--<471.0,83.0>> and 69 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1285.0,867.0>-<1191.0,780.0>-<1056.0,765.0>>/B<<1056.0,765.0>-<1246.0,753.0>-<1361.0,663.0>> = 9.954072497913494
	* Bmacronbelow (U+1E06): B<<1285.0,867.0>-<1191.0,780.0>-<1056.0,765.0>>/B<<1056.0,765.0>-<1246.0,753.0>-<1361.0,663.0>> = 9.954072497913494
	* three (U+0033): B<<943.0,523.0>-<863.0,471.0>-<761.0,456.0>>/B<<761.0,456.0>-<956.0,455.0>-<1076.5,352.0>> = 8.65970805868328
	* threeeighths (U+215C): B<<788.0,1108.5>-<721.0,1042.0>-<602.0,1028.0>>/B<<602.0,1028.0>-<755.0,1027.0>-<832.5,967.5>> = 7.08431369447969
	* threequarters (U+00BE): B<<798.0,1108.5>-<731.0,1042.0>-<612.0,1028.0>>/B<<612.0,1028.0>-<765.0,1027.0>-<842.5,967.5>> = 7.08431369447969
	* trademark (U+2122): L<<1347.0,850.0>--<1348.0,855.0>>/L<<1348.0,855.0>--<1346.0,850.0>> = 10.491477012331565
	* uni00B3 (U+00B3): B<<858.0,1346.5>-<791.0,1280.0>-<672.0,1266.0>>/B<<672.0,1266.0>-<825.0,1265.0>-<902.5,1205.5>> = 7.08431369447969
	* uni0181 (U+0181): B<<1463.0,867.5>-<1369.0,780.0>-<1234.0,765.0>>/B<<1234.0,765.0>-<1425.0,753.0>-<1539.5,663.0>> = 9.935201406918946
	* uni0190 (U+0190): B<<207.5,673.0>-<328.0,756.0>-<523.0,757.0>>/B<<523.0,757.0>-<371.0,780.0>-<269.5,868.5>> = 8.898303527743279
	* uni025B (U+025B): B<<270.0,505.5>-<352.0,527.0>-<430.0,527.0>>/B<<430.0,527.0>-<282.0,543.0>-<215.0,612.0>> = 6.1701750950295855 and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * A (U+0041): L<<906.0,477.0>--<427.0,478.0>>
 * Aacute (U+00C1): L<<906.0,477.0>--<427.0,478.0>>
 * Abreve (U+0102): L<<906.0,477.0>--<427.0,478.0>>
 * Acircumflex (U+00C2): L<<906.0,477.0>--<427.0,478.0>>
 * Adieresis (U+00C4): L<<906.0,477.0>--<427.0,478.0>>
 * Agrave (U+00C0): L<<906.0,477.0>--<427.0,478.0>>
 * Amacron (U+0100): L<<906.0,477.0>--<427.0,478.0>>
 * Aogonek (U+0104): L<<906.0,477.0>--<427.0,478.0>>
 * Aring (U+00C5): L<<906.0,477.0>--<427.0,478.0>>
 * Aringacute (U+01FA): L<<906.0,477.0>--<427.0,478.0>> and 342 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Gelasio-Italic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Oslash
	* uni20A9
	* Oslashacute
	* uni2105
	* Eng
	* OSlash_part. and summation
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- Lslash_part 
	- And NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0198	Contours detected: 2	Expected: 1
	- Glyph name: uni01E4	Contours detected: 2	Expected: 1
	- Glyph name: uni01E5	Contours detected: 4	Expected: 2
	- Glyph name: uni01E8	Contours detected: 3	Expected: 2
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2
	- Glyph name: uni01EB	Contours detected: 3	Expected: 2 
	- And 33 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* a (U+0061): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* aacute (U+00E1): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* abreve (U+0103): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* acircumflex (U+00E2): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* adieresis (U+00E4): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* agrave (U+00E0): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* amacron (U+0101): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* aogonek (U+0105): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* aring (U+00E5): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754
	* aringacute (U+01FB): B<<725.5,263.5>-<735.0,319.0>-<741.0,355.0>>/B<<741.0,355.0>-<723.0,306.0>-<686.0,240.5>> = 10.708331203824754 and 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 8 | 0 | 56 | 823 | 49 | 752 | 0 |
| 0% | 0% | 3% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
