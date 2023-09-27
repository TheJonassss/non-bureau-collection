## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present,  otherwise uses Font Family name (nameID 1) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.adobe.fonts/check/family/consistent_family_name">com.adobe.fonts/check/family/consistent_family_name</a>)</summary><div>


* 🔥 **FAIL** 2 different Font Family names were found:

* 'Non Bureau Extended' was found in:
  - NonBureauExtended-BlackItalic.ttf (nameID 16)
  - NonBureauExtended-ThinItalic.ttf (nameID 16)
  - NonBureauExtended-Medium.ttf (nameID 16)
  - NonBureauExtended-Bold.ttf (nameID 1)
  - NonBureauExtended-Thin.ttf (nameID 16)
  - NonBureauExtended-MediumItalic.ttf (nameID 16)
  - NonBureauExtended-LightItalic.ttf (nameID 16)
  - NonBureauExtended-Black.ttf (nameID 16)
  - NonBureauExtended-SemiBold.ttf (nameID 16)
  - NonBureauExtended-Regular.ttf (nameID 1)
  - NonBureauExtended-SemiBoldItalic.ttf (nameID 16)
  - NonBureauExtended-Light.ttf (nameID 16)
  - NonBureauExtended-BoldItalic.ttf (nameID 1)
  - NonBureauExtended-RegularItalic.ttf (nameID 16)

* 'Non Bureau' was found in:
  - NonBureau-Thin.ttf (nameID 16)
  - NonBureau-BlackItalic.ttf (nameID 16)
  - NonBureau-SemiBoldItalic.ttf (nameID 16)
  - NonBureau-BoldItalic.ttf (nameID 1)
  - NonBureau-ThinItalic.ttf (nameID 16)
  - NonBureau-SemiBold.ttf (nameID 16)
  - NonBureau-Medium.ttf (nameID 16)
  - NonBureau-Regular.ttf (nameID 1)
  - NonBureau-Light.ttf (nameID 16)
  - NonBureau-Black.ttf (nameID 16)
  - NonBureau-MediumItalic.ttf (nameID 16)
  - NonBureau-RegularItalic.ttf (nameID 16)
  - NonBureau-Bold.ttf (nameID 1)
  - NonBureau-LightItalic.ttf (nameID 16) [code: inconsistent-family-name]
</div></details><br></div></details><details><summary><b>[13] NonBureauExtended-BlackItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Black' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<230.0,497.0>>

	* d (U+0064): L<<516.0,486.0>--<515.0,549.0>> -> L<<515.0,549.0>--<528.0,736.0>>

	* dcaron (U+010F): L<<516.0,486.0>--<515.0,549.0>> -> L<<515.0,549.0>--<528.0,736.0>>

	* dcroat (U+0111): L<<516.0,487.0>--<517.0,549.0>> -> L<<517.0,549.0>--<518.0,587.0>>

	* dmacronbelow (U+1E0F): L<<516.0,486.0>--<515.0,549.0>> -> L<<515.0,549.0>--<528.0,736.0>>

	* f_f (U+FB00): L<<309.0,520.0>--<443.0,520.0>> -> L<<443.0,520.0>--<516.0,518.0>>

	* f_f_i (U+FB03): L<<309.0,520.0>--<443.0,520.0>> -> L<<443.0,520.0>--<516.0,518.0>>

	* f_t (U+FB05): L<<309.0,520.0>--<410.0,520.0>> -> L<<410.0,520.0>--<483.0,518.0>>

	* p (U+0070): L<<196.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* rho (U+03C1): L<<196.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* slash (U+002F): L<<384.0,714.0>--<383.0,710.0>> -> L<<383.0,710.0>--<121.0,-130.0>>

	* tau (U+03C4): L<<101.0,518.0>--<299.0,520.0>> -> L<<299.0,520.0>--<443.0,520.0>>

	* tau (U+03C4): L<<28.0,523.0>--<101.0,518.0>> -> L<<101.0,518.0>--<299.0,520.0>>

	* thorn (U+00FE): L<<196.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* uni0335 (U+0335): L<<122.0,317.0>--<310.0,319.0>> -> L<<310.0,319.0>--<398.0,319.0>>

	* uni0335 (U+0335): L<<34.0,322.0>--<122.0,317.0>> -> L<<122.0,317.0>--<310.0,319.0>>

	* uni03BC (U+03BC): L<<197.0,25.0>--<198.0,-41.0>> -> L<<198.0,-41.0>--<185.0,-217.0>>

	* uni0440 (U+0440): L<<196.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* uni0447 (U+0447): L<<431.0,0.0>--<442.0,160.0>> -> L<<442.0,160.0>--<454.0,239.0>>

	* uni0463 (U+0463): L<<275.0,500.0>--<271.0,473.0>> -> L<<271.0,473.0>--<262.0,435.0>>

	* uni048F (U+048F): L<<196.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* uni04B7 (U+04B7): L<<431.0,0.0>--<442.0,160.0>> -> L<<442.0,160.0>--<454.0,239.0>>

	* uni04B9 (U+04B9): L<<431.0,0.0>--<442.0,160.0>> -> L<<442.0,160.0>--<454.0,239.0>>

	* uni04F5 (U+04F5): L<<431.0,0.0>--<442.0,160.0>> -> L<<442.0,160.0>--<454.0,239.0>>

	* uni04FC (U+04FC): L<<544.0,36.0>--<529.0,57.0>> -> L<<529.0,57.0>--<425.0,200.0>>

	* uni04FC (U+04FC): L<<559.0,356.0>--<701.0,159.0>> -> L<<701.0,159.0>--<724.0,126.0>>

	* uni04FD (U+04FD): L<<368.0,3.0>--<363.0,11.0>> -> L<<363.0,11.0>--<297.0,111.0>>

	* uni04FD (U+04FD): L<<413.0,258.0>--<506.0,115.0>> -> L<<506.0,115.0>--<520.0,93.0>>

	* uni1E0D (U+1E0D): L<<516.0,486.0>--<515.0,549.0>> -> L<<515.0,549.0>--<528.0,736.0>>

	* uni2206 (U+2206): L<<530.0,720.0>--<959.0,2.0>> -> L<<959.0,2.0>--<960.0,0.0>>

	* uniA78B (U+A78B): L<<20.0,196.0>--<30.0,409.0>> -> L<<30.0,409.0>--<53.0,731.0>>

	* uniA78B (U+A78B): L<<223.0,731.0>--<200.0,409.0>> -> L<<200.0,409.0>--<180.0,196.0>>

	* uniA78C (U+A78C): L<<203.0,730.0>--<188.0,520.0>> -> L<<188.0,520.0>--<175.0,409.0>> 

	* uniA78C (U+A78C): L<<35.0,409.0>--<38.0,520.0>> -> L<<38.0,520.0>--<53.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NonBureauExtended-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Thin' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<121.0,736.0>--<106.0,520.0>> -> L<<106.0,520.0>--<93.0,411.0>>

	* beta (U+03B2): L<<74.0,112.0>--<72.0,-1.0>> -> L<<72.0,-1.0>--<55.0,-217.0>>

	* d (U+0064): L<<575.0,411.0>--<578.0,520.0>> -> L<<578.0,520.0>--<593.0,736.0>>

	* dcaron (U+010F): L<<575.0,411.0>--<578.0,520.0>> -> L<<578.0,520.0>--<593.0,736.0>>

	* dcroat (U+0111): L<<575.0,412.0>--<579.0,520.0>> -> L<<579.0,520.0>--<585.0,619.0>>

	* dmacronbelow (U+1E0F): L<<575.0,411.0>--<578.0,520.0>> -> L<<578.0,520.0>--<593.0,736.0>>

	* dong (U+20AB): L<<458.0,429.0>--<458.0,508.0>> -> L<<458.0,508.0>--<463.0,570.0>>

	* f_f (U+FB00): L<<199.0,520.0>--<343.0,520.0>> -> L<<343.0,520.0>--<436.0,518.0>>

	* f_f_i (U+FB03): L<<199.0,520.0>--<343.0,520.0>> -> L<<343.0,520.0>--<436.0,518.0>>

	* f_t (U+FB05): L<<199.0,520.0>--<321.0,520.0>> -> L<<321.0,520.0>--<436.0,518.0>>

	* p (U+0070): L<<72.0,108.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* q (U+0071): L<<527.0,-216.0>--<542.0,0.0>> -> L<<542.0,0.0>--<554.0,108.0>>

	* rho (U+03C1): L<<72.0,108.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* slash (U+002F): L<<284.0,714.0>--<283.0,710.0>> -> L<<283.0,710.0>--<21.0,-130.0>>

	* tau (U+03C4): L<<151.0,518.0>--<199.0,520.0>> -> L<<199.0,520.0>--<373.0,520.0>>

	* tau (U+03C4): L<<58.0,523.0>--<151.0,518.0>> -> L<<151.0,518.0>--<199.0,520.0>>

	* thorn (U+00FE): L<<121.0,736.0>--<106.0,520.0>> -> L<<106.0,520.0>--<96.0,418.0>>

	* thorn (U+00FE): L<<72.0,108.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* uni019B (U+019B): L<<2.0,0.0>--<291.0,501.0>> -> L<<291.0,501.0>--<292.0,503.0>>

	* uni0335 (U+0335): L<<131.0,278.0>--<173.0,280.0>> -> L<<173.0,280.0>--<252.0,280.0>>

	* uni03BC (U+03BC): L<<72.0,88.0>--<73.0,28.0>> -> L<<73.0,28.0>--<55.0,-217.0>>

	* uni0440 (U+0440): L<<72.0,108.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* uni0447 (U+0447): L<<462.0,0.0>--<474.0,181.0>> -> L<<474.0,181.0>--<484.0,252.0>>

	* uni0463 (U+0463): L<<203.0,582.0>--<195.0,460.0>> -> L<<195.0,460.0>--<184.0,382.0>>

	* uni048F (U+048F): L<<72.0,108.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* uni04B7 (U+04B7): L<<462.0,0.0>--<474.0,181.0>> -> L<<474.0,181.0>--<484.0,252.0>>

	* uni04B9 (U+04B9): L<<462.0,0.0>--<474.0,181.0>> -> L<<474.0,181.0>--<484.0,252.0>>

	* uni04CC (U+04CC): L<<465.0,42.0>--<474.0,181.0>> -> L<<474.0,181.0>--<484.0,252.0>>

	* uni04F5 (U+04F5): L<<462.0,0.0>--<474.0,181.0>> -> L<<474.0,181.0>--<484.0,252.0>>

	* uni04FC (U+04FC): L<<402.0,356.0>--<682.0,0.0>> -> L<<682.0,0.0>--<707.0,-30.0>>

	* uni04FC (U+04FC): L<<649.0,-45.0>--<614.0,0.0>> -> L<<614.0,0.0>--<365.0,317.0>>

	* uni04FD (U+04FD): L<<262.0,260.0>--<431.0,0.0>> -> L<<431.0,0.0>--<436.0,-8.0>>

	* uni04FD (U+04FD): L<<405.0,-45.0>--<377.0,0.0>> -> L<<377.0,0.0>--<232.0,222.0>>

	* uni051B (U+051B): L<<527.0,-216.0>--<542.0,0.0>> -> L<<542.0,0.0>--<554.0,108.0>>

	* uni1E0D (U+1E0D): L<<575.0,411.0>--<578.0,520.0>> -> L<<578.0,520.0>--<593.0,736.0>>

	* uniA78B (U+A78B): L<<123.0,731.0>--<100.0,409.0>> -> L<<100.0,409.0>--<80.0,196.0>>

	* uniA78B (U+A78B): L<<40.0,196.0>--<50.0,409.0>> -> L<<50.0,409.0>--<73.0,731.0>>

	* uniA78C (U+A78C): L<<113.0,730.0>--<98.0,520.0>> -> L<<98.0,520.0>--<85.0,409.0>> 

	* uniA78C (U+A78C): L<<55.0,409.0>--<58.0,520.0>> -> L<<58.0,520.0>--<73.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[15] NonBureauExtended-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: ij	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=113.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=414.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=108.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=408.0,Y=-1.0 (should be at baseline 0?)

	* bar (U+007C): X=30.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=150.0,Y=715.0 (should be at cap-height 714?)

	* uni00B5 (U+00B5): X=616.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=354.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=597.0,Y=1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=478.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=192.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=480.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=194.0,Y=713.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=263.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=373.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=456.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=170.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=359.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=73.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=441.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=155.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=408.0,Y=-1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=408.0,Y=-1.0 (should be at baseline 0?)

	* tbar (U+0167): X=408.0,Y=-1.0 (should be at baseline 0?)

	* uring (U+016F): X=314.0,Y=713.0 (should be at cap-height 714?)

	* uni0186 (U+0186): X=119.0,Y=714.5 (should be at cap-height 714?)

	* uni0186 (U+0186): X=113.5,Y=-1.5 (should be at baseline 0?)

	* florin (U+0192): X=10.0,Y=-1.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=450.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=164.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=482.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=196.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=497.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=211.0,Y=713.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=408.0,Y=-1.0 (should be at baseline 0?)

	* uni023C (U+023C): X=220.0,Y=2.0 (should be at baseline 0?)

	* ring (U+02DA): X=120.0,Y=713.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=122.0,Y=713.0 (should be at cap-height 714?)

	* alphatonos (U+03AC): X=727.0,Y=-1.0 (should be at baseline 0?)

	* alpha (U+03B1): X=727.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=328.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=328.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=154.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=286.5,Y=713.5 (should be at cap-height 714?)

	* lambda (U+03BB): X=213.0,Y=715.5 (should be at cap-height 714?)

	* lambda (U+03BB): X=541.0,Y=-0.5 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=343.5,Y=-1.0 (should be at baseline 0?)

	* tau (U+03C4): X=408.0,Y=-1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=5.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=152.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=15.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=5.0,Y=2.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=595.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=473.0,Y=1.0 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=5.0,Y=2.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=5.0,Y=2.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=408.0,Y=-1.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=408.0,Y=-1.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=30.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=150.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=300.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=420.0,Y=715.0 (should be at cap-height 714?)

	* uni2116 (U+2116): X=1312.0,Y=1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=101.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=908.0,Y=2.0 (should be at baseline 0?)

	* integral (U+222B): X=90.0,Y=1.0 (should be at baseline 0?)

	* circle (U+25CB): X=430.0,Y=2.0 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=408.0,Y=-1.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=702.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<153.0,736.0>--<153.0,535.0>> -> L<<153.0,535.0>--<148.0,455.0>>

	* beta (U+03B2): L<<149.0,72.0>--<154.0,-1.0>> -> L<<154.0,-1.0>--<153.0,-217.0>>

	* d (U+0064): L<<532.0,455.0>--<527.0,535.0>> -> L<<527.0,535.0>--<527.0,736.0>>

	* dcaron (U+010F): L<<532.0,455.0>--<527.0,535.0>> -> L<<527.0,535.0>--<527.0,736.0>>

	* dcroat (U+0111): L<<532.0,450.0>--<527.0,535.0>> -> L<<527.0,535.0>--<527.0,603.0>>

	* dmacronbelow (U+1E0F): L<<532.0,455.0>--<527.0,535.0>> -> L<<527.0,535.0>--<527.0,736.0>>

	* f_f (U+FB00): L<<236.0,520.0>--<375.0,520.0>> -> L<<375.0,520.0>--<458.0,518.0>>

	* f_f_i (U+FB03): L<<236.0,520.0>--<375.0,520.0>> -> L<<375.0,520.0>--<458.0,518.0>>

	* f_t (U+FB05): L<<236.0,520.0>--<351.0,520.0>> -> L<<351.0,520.0>--<442.0,518.0>>

	* p (U+0070): L<<148.0,66.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* q (U+0071): L<<527.0,-216.0>--<527.0,-14.0>> -> L<<527.0,-14.0>--<532.0,66.0>>

	* rho (U+03C1): L<<148.0,66.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* tau (U+03C4): L<<108.0,518.0>--<231.0,520.0>> -> L<<231.0,520.0>--<390.0,520.0>>

	* tau (U+03C4): L<<25.0,523.0>--<108.0,518.0>> -> L<<108.0,518.0>--<231.0,520.0>>

	* thorn (U+00FE): L<<148.0,66.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* uni0335 (U+0335): L<<114.0,298.0>--<229.0,300.0>> -> L<<229.0,300.0>--<312.0,300.0>>

	* uni0335 (U+0335): L<<30.0,303.0>--<114.0,298.0>> -> L<<114.0,298.0>--<229.0,300.0>>

	* uni03BC (U+03BC): L<<148.0,57.0>--<153.0,-6.0>> -> L<<153.0,-6.0>--<153.0,-217.0>>

	* uni0440 (U+0440): L<<148.0,66.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* uni0447 (U+0447): L<<464.0,0.0>--<464.0,171.0>> -> L<<464.0,171.0>--<471.0,247.0>>

	* uni0463 (U+0463): L<<219.0,541.0>--<219.0,463.0>> -> L<<219.0,463.0>--<214.0,410.0>>

	* uni048F (U+048F): L<<148.0,66.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* uni04B7 (U+04B7): L<<464.0,0.0>--<464.0,171.0>> -> L<<464.0,171.0>--<471.0,247.0>>

	* uni04B9 (U+04B9): L<<464.0,0.0>--<464.0,171.0>> -> L<<464.0,171.0>--<471.0,247.0>>

	* uni04CD (U+04CD): L<<139.0,714.0>--<285.0,487.0>> -> L<<285.0,487.0>--<452.0,164.0>>

	* uni04CD (U+04CD): L<<846.0,714.0>--<874.0,441.0>> -> L<<874.0,441.0>--<939.0,108.0>>

	* uni04F5 (U+04F5): L<<464.0,0.0>--<464.0,171.0>> -> L<<464.0,171.0>--<471.0,247.0>>

	* uni04FC (U+04FC): L<<474.0,357.0>--<705.0,80.0>> -> L<<705.0,80.0>--<731.0,49.0>>

	* uni04FC (U+04FC): L<<613.0,-6.0>--<586.0,29.0>> -> L<<586.0,29.0>--<394.0,259.0>>

	* uni04FD (U+04FD): L<<338.0,260.0>--<484.0,58.0>> -> L<<484.0,58.0>--<494.0,44.0>>

	* uni04FD (U+04FD): L<<405.0,-22.0>--<386.0,6.0>> -> L<<386.0,6.0>--<271.0,166.0>>

	* uni051B (U+051B): L<<527.0,-216.0>--<527.0,-14.0>> -> L<<527.0,-14.0>--<532.0,66.0>>

	* uni1E0D (U+1E0D): L<<532.0,455.0>--<527.0,535.0>> -> L<<527.0,535.0>--<527.0,736.0>>

	* uniA78B (U+A78B): L<<140.0,731.0>--<140.0,409.0>> -> L<<140.0,409.0>--<135.0,196.0>>

	* uniA78B (U+A78B): L<<35.0,196.0>--<30.0,409.0>> -> L<<30.0,409.0>--<30.0,731.0>>

	* uniA78C (U+A78C): L<<125.0,730.0>--<125.0,520.0>> -> L<<125.0,520.0>--<120.0,409.0>> 

	* uniA78C (U+A78C): L<<35.0,409.0>--<30.0,520.0>> -> L<<30.0,520.0>--<30.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<255.0,619.0>--<689.0,620.0>>

	* ae (U+00E6): L<<641.0,306.0>--<1001.0,307.0>>

	* aeacute (U+01FD): L<<641.0,306.0>--<1001.0,307.0>>

	* arrowleft (U+2190): L<<449.0,250.0>--<450.0,31.0>>

	* arrowleft (U+2190): L<<449.0,339.0>--<624.0,338.0>>

	* arrowleft (U+2190): L<<450.0,558.0>--<449.0,339.0>>

	* arrowleft (U+2190): L<<624.0,251.0>--<449.0,250.0>>

	* arrowright (U+2192): L<<15.0,338.0>--<190.0,339.0>>

	* arrowright (U+2192): L<<190.0,250.0>--<15.0,251.0>>

	* beta (U+03B2): L<<154.0,-1.0>--<153.0,-217.0>>

	* e (U+0065): L<<157.0,306.0>--<517.0,307.0>>

	* eacute (U+00E9): L<<157.0,306.0>--<517.0,307.0>>

	* ebreve (U+0115): L<<157.0,306.0>--<517.0,307.0>>

	* ecaron (U+011B): L<<157.0,306.0>--<517.0,307.0>>

	* ecircumflex (U+00EA): L<<157.0,306.0>--<517.0,307.0>>

	* edieresis (U+00EB): L<<157.0,306.0>--<517.0,307.0>>

	* edotaccent (U+0117): L<<157.0,306.0>--<517.0,307.0>>

	* egrave (U+00E8): L<<157.0,306.0>--<517.0,307.0>>

	* emacron (U+0113): L<<157.0,306.0>--<517.0,307.0>>

	* eogonek (U+0119): L<<157.0,306.0>--<517.0,307.0>>

	* oe (U+0153): L<<720.0,306.0>--<1080.0,307.0>>

	* psi (U+03C8): L<<276.0,82.0>--<277.0,520.0>>

	* psi (U+03C8): L<<361.0,520.0>--<360.0,82.0>>

	* raisedmcsign (U+1F16A): L<<96.0,594.0>--<95.0,442.0>>

	* raisedmdsign (U+1F16B): L<<96.0,594.0>--<95.0,442.0>>

	* sterling (U+00A3): L<<323.0,420.0>--<470.0,421.0>>

	* uni0435 (U+0435): L<<157.0,306.0>--<517.0,307.0>>

	* uni0450 (U+0450): L<<157.0,306.0>--<517.0,307.0>>

	* uni0451 (U+0451): L<<157.0,306.0>--<517.0,307.0>>

	* uni046A (U+046A): L<<356.0,0.0>--<357.0,300.0>>

	* uni046A (U+046A): L<<487.0,300.0>--<486.0,0.0>>

	* uni046B (U+046B): L<<260.0,0.0>--<261.0,212.0>>

	* uni04CD (U+04CD): L<<161.0,468.0>--<160.0,307.0>>

	* uni04CD (U+04CD): L<<744.0,162.0>--<743.0,468.0>>

	* uni04D5 (U+04D5): L<<641.0,306.0>--<1001.0,307.0>>

	* uni04D7 (U+04D7): L<<157.0,306.0>--<517.0,307.0>>

	* uni04E9 (U+04E9): L<<158.0,311.0>--<520.0,312.0>>

	* uni04EB (U+04EB): L<<158.0,311.0>--<520.0,312.0>>

	* uni1E15 (U+1E15): L<<157.0,306.0>--<517.0,307.0>>

	* uni1E17 (U+1E17): L<<157.0,306.0>--<517.0,307.0>>

	* uni1EB9 (U+1EB9): L<<157.0,306.0>--<517.0,307.0>>

	* uni1EBD (U+1EBD): L<<157.0,306.0>--<517.0,307.0>>

	* uni20B4 (U+20B4): L<<26.0,315.0>--<773.0,316.0>>

	* uni20B4 (U+20B4): L<<51.0,455.0>--<521.0,456.0>>

	* uni2116 (U+2116): L<<1312.0,1.0>--<825.0,0.0>> 

	* uni2116 (U+2116): L<<825.0,85.0>--<1312.0,86.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NonBureauExtended-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=540.0,Y=-2.0 (should be at baseline 0?)

	* b (U+0062): X=272.0,Y=519.0 (should be at x-height 520?)

	* d (U+0064): X=430.0,Y=519.0 (should be at x-height 520?)

	* f (U+0066): X=100.0,Y=518.0 (should be at x-height 520?)

	* p (U+0070): X=272.0,Y=0.5 (should be at baseline 0?)

	* q (U+0071): X=430.0,Y=0.5 (should be at baseline 0?)

	* r (U+0072): X=451.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=91.0,Y=518.0 (should be at x-height 520?)

	* bar (U+007C): X=23.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=190.0,Y=715.0 (should be at cap-height 714?)

	* sterling (U+00A3): X=349.0,Y=713.0 (should be at cap-height 714?)

	* ordfeminine (U+00AA): X=164.0,Y=713.0 (should be at cap-height 714?)

	* uni00B5 (U+00B5): X=242.5,Y=-1.5 (should be at baseline 0?)

	* ordmasculine (U+00BA): X=187.0,Y=713.0 (should be at cap-height 714?)

	* ordmasculine (U+00BA): X=187.0,Y=713.0 (should be at cap-height 714?)

	* thorn (U+00FE): X=272.0,Y=0.5 (should be at baseline 0?)

	* ccaron (U+010D): X=513.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=180.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=517.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=184.0,Y=713.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=307.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=447.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=481.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=148.0,Y=713.0 (should be at cap-height 714?)

	* Eng (U+014A): X=763.0,Y=-1.0 (should be at baseline 0?)

	* rcaron (U+0159): X=397.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=64.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=479.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=146.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=494.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=161.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=517.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=184.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=540.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=207.0,Y=713.0 (should be at cap-height 714?)

	* uni023C (U+023C): X=230.0,Y=1.0 (should be at baseline 0?)

	* uni0263 (U+0263): X=25.0,Y=-2.0 (should be at baseline 0?)

	* uni0263 (U+0263): X=589.0,Y=-2.0 (should be at baseline 0?)

	* beta (U+03B2): X=351.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=351.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=269.0,Y=-0.5 (should be at baseline 0?)

	* beta (U+03B2): X=197.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=281.0,Y=712.5 (should be at cap-height 714?)

	* zeta (U+03B6): X=159.5,Y=-1.5 (should be at baseline 0?)

	* uni03BC (U+03BC): X=525.5,Y=1.5 (should be at baseline 0?)

	* uni03BC (U+03BC): X=422.5,Y=1.5 (should be at baseline 0?)

	* uni03BC (U+03BC): X=252.5,Y=0.5 (should be at baseline 0?)

	* rho (U+03C1): X=265.5,Y=1.5 (should be at baseline 0?)

	* uni0409 (U+0409): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni0440 (U+0440): X=272.0,Y=0.5 (should be at baseline 0?)

	* yacy (U+044F): X=205.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=12.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni048F (U+048F): X=484.0,Y=-1.0 (should be at baseline 0?)

	* uni048F (U+048F): X=272.0,Y=0.5 (should be at baseline 0?)

	* uni04C3 (U+04C3): X=498.0,Y=1.5 (should be at baseline 0?)

	* uni04C4 (U+04C4): X=349.0,Y=0.5 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni051A (U+051A): X=540.0,Y=-2.0 (should be at baseline 0?)

	* uni051B (U+051B): X=430.0,Y=0.5 (should be at baseline 0?)

	* uni2016 (U+2016): X=23.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=190.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=340.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=507.0,Y=715.0 (should be at cap-height 714?)

	* uni2116 (U+2116): X=1360.0,Y=1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=114.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=955.0,Y=2.0 (should be at baseline 0?)

	* triagup (U+25B2): X=402.0,Y=715.0 (should be at cap-height 714?)

	* triagup (U+25B2): X=404.0,Y=715.0 (should be at cap-height 714?)

	* uni25B3 (U+25B3): X=402.0,Y=715.0 (should be at cap-height 714?)

	* uni25B3 (U+25B3): X=404.0,Y=715.0 (should be at cap-height 714?)

	* uni25B6 (U+25B6): X=23.0,Y=1.0 (should be at baseline 0?)

	* uni25B7 (U+25B7): X=23.0,Y=1.0 (should be at baseline 0?)

	* triagdn (U+25BC): X=20.0,Y=715.0 (should be at cap-height 714?)

	* triagdn (U+25BC): X=787.0,Y=715.0 (should be at cap-height 714?)

	* uni25BD (U+25BD): X=787.0,Y=715.0 (should be at cap-height 714?)

	* uni25BD (U+25BD): X=20.0,Y=715.0 (should be at cap-height 714?)

	* uni25C0 (U+25C0): X=683.0,Y=1.0 (should be at baseline 0?)

	* uni25C1 (U+25C1): X=683.0,Y=1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=553.5,Y=1.0 (should be at baseline 0?) 

	* uni25CC (U+25CC): X=336.5,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<196.0,736.0>--<196.0,544.0>> -> L<<196.0,544.0>--<191.0,483.0>>

	* d (U+0064): L<<510.0,483.0>--<505.0,544.0>> -> L<<505.0,544.0>--<505.0,736.0>>

	* dcaron (U+010F): L<<510.0,483.0>--<505.0,544.0>> -> L<<505.0,544.0>--<505.0,736.0>>

	* dcroat (U+0111): L<<510.0,475.0>--<505.0,544.0>> -> L<<505.0,544.0>--<505.0,592.0>>

	* dmacronbelow (U+1E0F): L<<510.0,483.0>--<505.0,544.0>> -> L<<505.0,544.0>--<505.0,736.0>>

	* f_f (U+FB00): L<<273.0,520.0>--<408.0,520.0>> -> L<<408.0,520.0>--<485.0,518.0>>

	* f_f_i (U+FB03): L<<273.0,520.0>--<408.0,520.0>> -> L<<408.0,520.0>--<485.0,518.0>>

	* f_t (U+FB05): L<<273.0,520.0>--<378.0,520.0>> -> L<<378.0,520.0>--<457.0,518.0>>

	* p (U+0070): L<<191.0,37.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* q (U+0071): L<<505.0,-216.0>--<505.0,-24.0>> -> L<<505.0,-24.0>--<510.0,37.0>>

	* raisedmcsign (U+1F16A): L<<116.0,547.0>--<115.0,497.0>> -> L<<115.0,497.0>--<108.0,359.0>>

	* raisedmcsign (U+1F16A): L<<241.0,497.0>--<264.0,543.0>> -> L<<264.0,543.0>--<356.0,714.0>>

	* raisedmcsign (U+1F16A): L<<368.0,547.0>--<344.0,497.0>> -> L<<344.0,497.0>--<275.0,359.0>>

	* raisedmdsign (U+1F16B): L<<116.0,547.0>--<115.0,497.0>> -> L<<115.0,497.0>--<108.0,359.0>>

	* raisedmdsign (U+1F16B): L<<241.0,497.0>--<264.0,543.0>> -> L<<264.0,543.0>--<356.0,714.0>>

	* raisedmdsign (U+1F16B): L<<368.0,547.0>--<344.0,497.0>> -> L<<344.0,497.0>--<275.0,359.0>>

	* rho (U+03C1): L<<191.0,37.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* tau (U+03C4): L<<15.0,523.0>--<91.0,518.0>> -> L<<91.0,518.0>--<264.0,520.0>>

	* tau (U+03C4): L<<91.0,518.0>--<264.0,520.0>> -> L<<264.0,520.0>--<413.0,520.0>>

	* thorn (U+00FE): L<<191.0,37.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* trademark (U+2122): L<<479.0,547.0>--<478.0,497.0>> -> L<<478.0,497.0>--<471.0,359.0>>

	* trademark (U+2122): L<<604.0,497.0>--<627.0,543.0>> -> L<<627.0,543.0>--<720.0,714.0>>

	* trademark (U+2122): L<<731.0,547.0>--<707.0,497.0>> -> L<<707.0,497.0>--<638.0,359.0>>

	* uni0335 (U+0335): L<<110.0,311.0>--<274.0,313.0>> -> L<<274.0,313.0>--<360.0,313.0>>

	* uni0335 (U+0335): L<<23.0,316.0>--<110.0,311.0>> -> L<<110.0,311.0>--<274.0,313.0>>

	* uni03BC (U+03BC): L<<191.0,36.0>--<196.0,-29.0>> -> L<<196.0,-29.0>--<196.0,-217.0>>

	* uni0440 (U+0440): L<<191.0,37.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* uni0447 (U+0447): L<<454.0,0.0>--<454.0,164.0>> -> L<<454.0,164.0>--<462.0,244.0>>

	* uni048F (U+048F): L<<191.0,37.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* uni04B7 (U+04B7): L<<454.0,0.0>--<454.0,164.0>> -> L<<454.0,164.0>--<462.0,244.0>>

	* uni04B9 (U+04B9): L<<454.0,0.0>--<454.0,164.0>> -> L<<454.0,164.0>--<462.0,244.0>>

	* uni04CD (U+04CD): L<<204.0,714.0>--<410.0,335.0>> -> L<<410.0,335.0>--<467.0,227.0>>

	* uni04CD (U+04CD): L<<417.0,0.0>--<261.0,269.0>> -> L<<261.0,269.0>--<207.0,371.0>>

	* uni04CD (U+04CD): L<<732.0,0.0>--<727.0,269.0>> -> L<<727.0,269.0>--<725.0,371.0>>

	* uni04F5 (U+04F5): L<<454.0,0.0>--<454.0,164.0>> -> L<<454.0,164.0>--<462.0,244.0>>

	* uni04FC (U+04FC): L<<526.0,357.0>--<708.0,133.0>> -> L<<708.0,133.0>--<733.0,102.0>>

	* uni04FC (U+04FC): L<<576.0,21.0>--<556.0,48.0>> -> L<<556.0,48.0>--<417.0,220.0>>

	* uni04FD (U+04FD): L<<388.0,260.0>--<507.0,96.0>> -> L<<507.0,96.0>--<520.0,78.0>>

	* uni04FD (U+04FD): L<<391.0,-7.0>--<380.0,9.0>> -> L<<380.0,9.0>--<294.0,129.0>>

	* uni051B (U+051B): L<<505.0,-216.0>--<505.0,-24.0>> -> L<<505.0,-24.0>--<510.0,37.0>>

	* uni0526 (U+0526): L<<838.0,148.0>--<847.0,24.0>> -> L<<847.0,24.0>--<847.0,-100.0>>

	* uni1E0D (U+1E0D): L<<510.0,483.0>--<505.0,544.0>> -> L<<505.0,544.0>--<505.0,736.0>>

	* uniA78B (U+A78B): L<<173.0,731.0>--<173.0,409.0>> -> L<<173.0,409.0>--<168.0,196.0>>

	* uniA78B (U+A78B): L<<28.0,196.0>--<23.0,409.0>> -> L<<23.0,409.0>--<23.0,731.0>>

	* uniA78C (U+A78C): L<<155.0,730.0>--<155.0,520.0>> -> L<<155.0,520.0>--<150.0,409.0>> 

	* uniA78C (U+A78C): L<<28.0,409.0>--<23.0,520.0>> -> L<<23.0,520.0>--<23.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<764.0,714.0>--<763.0,-1.0>>

	* Hbar (U+0126): L<<298.0,631.0>--<672.0,632.0>>

	* ae (U+00E6): L<<724.0,311.0>--<1010.0,312.0>>

	* aeacute (U+01FD): L<<724.0,311.0>--<1010.0,312.0>>

	* ampersand (U+0026): L<<557.0,349.0>--<704.0,350.0>>

	* arrowleft (U+2190): L<<456.0,352.0>--<617.0,351.0>>

	* arrowleft (U+2190): L<<617.0,237.0>--<456.0,236.0>>

	* arrowright (U+2192): L<<12.0,351.0>--<173.0,352.0>>

	* arrowright (U+2192): L<<173.0,236.0>--<12.0,237.0>>

	* beta (U+03B2): L<<197.0,-1.0>--<196.0,-217.0>>

	* chi (U+03C7): L<<12.0,380.0>--<13.0,522.0>>

	* e (U+0065): L<<207.0,311.0>--<492.0,312.0>>

	* eacute (U+00E9): L<<207.0,311.0>--<492.0,312.0>>

	* ebreve (U+0115): L<<207.0,311.0>--<492.0,312.0>>

	* ecaron (U+011B): L<<207.0,311.0>--<492.0,312.0>>

	* ecircumflex (U+00EA): L<<207.0,311.0>--<492.0,312.0>>

	* edieresis (U+00EB): L<<207.0,311.0>--<492.0,312.0>>

	* edotaccent (U+0117): L<<207.0,311.0>--<492.0,312.0>>

	* egrave (U+00E8): L<<207.0,311.0>--<492.0,312.0>>

	* emacron (U+0113): L<<207.0,311.0>--<492.0,312.0>>

	* eogonek (U+0119): L<<207.0,311.0>--<492.0,312.0>>

	* franc (U+20A3): L<<278.0,203.0>--<493.0,204.0>>

	* oe (U+0153): L<<788.0,311.0>--<1073.0,312.0>>

	* psi (U+03C8): L<<291.0,117.0>--<292.0,520.0>>

	* psi (U+03C8): L<<400.0,520.0>--<399.0,117.0>>

	* sterling (U+00A3): L<<372.0,415.0>--<505.0,416.0>>

	* uni0259 (U+0259): L<<488.0,208.0>--<202.0,207.0>>

	* uni0416 (U+0416): L<<492.0,0.0>--<491.0,305.0>>

	* uni0435 (U+0435): L<<207.0,311.0>--<492.0,312.0>>

	* uni0450 (U+0450): L<<207.0,311.0>--<492.0,312.0>>

	* uni0451 (U+0451): L<<207.0,311.0>--<492.0,312.0>>

	* uni046A (U+046A): L<<383.0,0.0>--<384.0,253.0>>

	* uni046A (U+046A): L<<567.0,253.0>--<566.0,0.0>>

	* uni046B (U+046B): L<<275.0,0.0>--<276.0,183.0>>

	* uni0496 (U+0496): L<<492.0,0.0>--<491.0,305.0>>

	* uni04BC (U+04BC): L<<402.0,438.0>--<801.0,439.0>>

	* uni04BE (U+04BE): L<<402.0,438.0>--<801.0,439.0>>

	* uni04C1 (U+04C1): L<<492.0,0.0>--<491.0,305.0>>

	* uni04D5 (U+04D5): L<<724.0,311.0>--<1010.0,312.0>>

	* uni04D7 (U+04D7): L<<207.0,311.0>--<492.0,312.0>>

	* uni04D9 (U+04D9): L<<488.0,208.0>--<202.0,207.0>>

	* uni04DB (U+04DB): L<<488.0,208.0>--<202.0,207.0>>

	* uni04DC (U+04DC): L<<492.0,0.0>--<491.0,305.0>>

	* uni04E9 (U+04E9): L<<209.0,320.0>--<491.0,321.0>>

	* uni04EB (U+04EB): L<<209.0,320.0>--<491.0,321.0>>

	* uni1E15 (U+1E15): L<<207.0,311.0>--<492.0,312.0>>

	* uni1E17 (U+1E17): L<<207.0,311.0>--<492.0,312.0>>

	* uni1EB9 (U+1EB9): L<<207.0,311.0>--<492.0,312.0>>

	* uni1EBD (U+1EBD): L<<207.0,311.0>--<492.0,312.0>>

	* uni20B4 (U+20B4): L<<26.0,321.0>--<765.0,323.0>>

	* uni20B4 (U+20B4): L<<52.0,450.0>--<472.0,451.0>>

	* uni20BD (U+20BD): L<<320.0,198.0>--<497.0,199.0>>

	* uni2116 (U+2116): L<<1360.0,1.0>--<872.0,0.0>>

	* uni2116 (U+2116): L<<872.0,114.0>--<1360.0,115.0>> 

	* uniAB53 (U+AB53): L<<12.0,380.0>--<13.0,522.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NonBureau-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=133.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=319.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=133.0,Y=518.0 (should be at x-height 520?)

	* bar (U+007C): X=40.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=90.0,Y=715.0 (should be at cap-height 714?)

	* onehalf (U+00BD): X=344.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=538.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=247.0,Y=2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=354.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=138.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=356.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=140.0,Y=713.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=243.0,Y=716.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=259.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=197.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=261.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=348.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=132.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=286.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=70.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=334.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=118.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=338.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=122.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=370.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=154.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=359.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=359.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=143.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=143.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=188.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=314.0,Y=716.0 (should be at cap-height 714?)

	* Oslashacute (U+01FE): X=247.0,Y=2.0 (should be at baseline 0?)

	* uni023B (U+023B): X=416.0,Y=715.0 (should be at cap-height 714?)

	* uni023C (U+023C): X=174.0,Y=-1.0 (should be at baseline 0?)

	* uni0254 (U+0254): X=92.5,Y=-0.5 (should be at baseline 0?)

	* uni0269 (U+0269): X=189.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresistonos (U+0390): X=189.0,Y=-1.0 (should be at baseline 0?)

	* iotatonos (U+03AF): X=189.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=273.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=89.0,Y=-1.0 (should be at baseline 0?)

	* iota (U+03B9): X=189.0,Y=-1.0 (should be at baseline 0?)

	* tau (U+03C4): X=282.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresis (U+03CA): X=189.0,Y=-1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=10.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=72.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=20.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=10.0,Y=2.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=436.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=388.0,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=10.0,Y=2.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=535.0,Y=1.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=80.0,Y=1.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=21.0,Y=1.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=594.0,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=10.0,Y=2.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=40.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=90.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=240.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=290.0,Y=715.0 (should be at cap-height 714?)

	* colonmonetary (U+20A1): X=244.0,Y=-1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=58.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=738.0,Y=2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=468.0,Y=1.0 (should be at baseline 0?) 

	* uni2C65 (U+2C65): X=114.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<88.0,736.0>--<88.0,520.0>> -> L<<88.0,520.0>--<83.0,427.0>>

	* beta (U+03B2): L<<84.0,92.0>--<89.0,-1.0>> -> L<<89.0,-1.0>--<88.0,-217.0>>

	* d (U+0064): L<<425.0,427.0>--<420.0,520.0>> -> L<<420.0,520.0>--<420.0,736.0>>

	* dcaron (U+010F): L<<425.0,427.0>--<420.0,520.0>> -> L<<420.0,520.0>--<420.0,736.0>>

	* dcroat (U+0111): L<<422.0,427.0>--<420.0,520.0>> -> L<<420.0,520.0>--<420.0,619.0>>

	* dmacronbelow (U+1E0F): L<<425.0,427.0>--<420.0,520.0>> -> L<<420.0,520.0>--<420.0,736.0>>

	* dong (U+20AB): L<<365.0,435.0>--<360.0,508.0>> -> L<<360.0,508.0>--<360.0,570.0>>

	* f_f (U+FB00): L<<181.0,520.0>--<305.0,520.0>> -> L<<305.0,520.0>--<398.0,518.0>>

	* f_f_i (U+FB03): L<<181.0,520.0>--<265.0,520.0>> -> L<<265.0,520.0>--<358.0,518.0>>

	* f_t (U+FB05): L<<181.0,520.0>--<315.0,520.0>> -> L<<315.0,520.0>--<398.0,518.0>>

	* p (U+0070): L<<83.0,93.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* q (U+0071): L<<420.0,-216.0>--<420.0,0.0>> -> L<<420.0,0.0>--<425.0,93.0>>

	* rho (U+03C1): L<<83.0,93.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* tau (U+03C4): L<<133.0,518.0>--<181.0,520.0>> -> L<<181.0,520.0>--<315.0,520.0>>

	* tau (U+03C4): L<<40.0,523.0>--<133.0,518.0>> -> L<<133.0,518.0>--<181.0,520.0>>

	* thorn (U+00FE): L<<83.0,93.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* thorn (U+00FE): L<<88.0,736.0>--<88.0,520.0>> -> L<<88.0,520.0>--<83.0,432.0>>

	* uni0335 (U+0335): L<<119.0,278.0>--<161.0,280.0>> -> L<<161.0,280.0>--<240.0,280.0>>

	* uni03BC (U+03BC): L<<83.0,78.0>--<88.0,28.0>> -> L<<88.0,28.0>--<88.0,-217.0>>

	* uni0440 (U+0440): L<<83.0,93.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* uni0447 (U+0447): L<<339.0,0.0>--<339.0,181.0>> -> L<<339.0,181.0>--<344.0,252.0>>

	* uni0452 (U+0452): L<<181.0,592.0>--<181.0,480.0>> -> L<<181.0,480.0>--<176.0,387.0>>

	* uni045B (U+045B): L<<181.0,592.0>--<181.0,480.0>> -> L<<181.0,480.0>--<176.0,387.0>>

	* uni0463 (U+0463): L<<180.0,582.0>--<180.0,460.0>> -> L<<180.0,460.0>--<175.0,382.0>>

	* uni048F (U+048F): L<<83.0,93.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* uni04B7 (U+04B7): L<<339.0,0.0>--<339.0,181.0>> -> L<<339.0,181.0>--<344.0,252.0>>

	* uni04B9 (U+04B9): L<<339.0,0.0>--<339.0,181.0>> -> L<<339.0,181.0>--<344.0,252.0>>

	* uni04CC (U+04CC): L<<339.0,42.0>--<339.0,181.0>> -> L<<339.0,181.0>--<344.0,252.0>>

	* uni04F5 (U+04F5): L<<339.0,0.0>--<339.0,181.0>> -> L<<339.0,181.0>--<344.0,252.0>>

	* uni04FC (U+04FC): L<<336.0,358.0>--<594.0,1.0>> -> L<<594.0,1.0>--<616.0,-30.0>>

	* uni04FC (U+04FC): L<<567.0,-46.0>--<535.0,1.0>> -> L<<535.0,1.0>--<307.0,317.0>>

	* uni04FD (U+04FD): L<<263.0,260.0>--<450.0,0.0>> -> L<<450.0,0.0>--<455.0,-7.0>>

	* uni04FD (U+04FD): L<<426.0,-46.0>--<395.0,0.0>> -> L<<395.0,0.0>--<235.0,222.0>>

	* uni051B (U+051B): L<<420.0,-216.0>--<420.0,0.0>> -> L<<420.0,0.0>--<425.0,93.0>>

	* uni1E0D (U+1E0D): L<<425.0,427.0>--<420.0,520.0>> -> L<<420.0,520.0>--<420.0,736.0>>

	* uniA78B (U+A78B): L<<45.0,196.0>--<40.0,409.0>> -> L<<40.0,409.0>--<40.0,731.0>>

	* uniA78B (U+A78B): L<<90.0,731.0>--<90.0,409.0>> -> L<<90.0,409.0>--<85.0,196.0>>

	* uniA78C (U+A78C): L<<45.0,409.0>--<40.0,520.0>> -> L<<40.0,520.0>--<40.0,730.0>> 

	* uniA78C (U+A78C): L<<80.0,730.0>--<80.0,520.0>> -> L<<80.0,520.0>--<75.0,409.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<190.0,600.0>--<614.0,602.0>>

	* arrowleft (U+2190): L<<439.0,271.0>--<440.0,61.0>>

	* arrowleft (U+2190): L<<440.0,529.0>--<439.0,319.0>>

	* arrowright (U+2192): L<<214.0,61.0>--<215.0,271.0>>

	* arrowright (U+2192): L<<215.0,319.0>--<214.0,529.0>>

	* beta (U+03B2): L<<89.0,-1.0>--<88.0,-217.0>>

	* estimated (U+212E): L<<536.0,347.0>--<535.0,509.0>>

	* oe (U+0153): L<<884.0,255.0>--<495.0,254.0>>

	* uni046A (U+046A): L<<316.0,0.0>--<317.0,370.0>>

	* uni046A (U+046A): L<<367.0,370.0>--<366.0,0.0>> 

	* uni046B (U+046B): L<<237.0,0.0>--<238.0,256.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NonBureau-BlackItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<230.0,498.0>>

	* f_f (U+FB00): L<<309.0,520.0>--<413.0,520.0>> -> L<<413.0,520.0>--<456.0,518.0>>

	* f_f_i (U+FB03): L<<309.0,520.0>--<413.0,520.0>> -> L<<413.0,520.0>--<456.0,518.0>>

	* f_t (U+FB05): L<<309.0,520.0>--<380.0,520.0>> -> L<<380.0,520.0>--<453.0,518.0>>

	* h (U+0068): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<226.0,478.0>>

	* hbar (U+0127): L<<317.0,587.0>--<314.0,549.0>> -> L<<314.0,549.0>--<302.0,477.0>>

	* hcircumflex (U+0125): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<226.0,478.0>>

	* p (U+0070): L<<197.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* rho (U+03C1): L<<196.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* slash (U+002F): L<<366.0,714.0>--<365.0,710.0>> -> L<<365.0,710.0>--<103.0,-130.0>>

	* tau (U+03C4): L<<101.0,518.0>--<299.0,520.0>> -> L<<299.0,520.0>--<403.0,520.0>>

	* tau (U+03C4): L<<28.0,523.0>--<101.0,518.0>> -> L<<101.0,518.0>--<299.0,520.0>>

	* thorn (U+00FE): L<<197.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* uni0335 (U+0335): L<<112.0,317.0>--<300.0,319.0>> -> L<<300.0,319.0>--<388.0,319.0>>

	* uni0335 (U+0335): L<<24.0,322.0>--<112.0,317.0>> -> L<<112.0,317.0>--<300.0,319.0>>

	* uni03BC (U+03BC): L<<197.0,21.0>--<198.0,-41.0>> -> L<<198.0,-41.0>--<185.0,-217.0>>

	* uni0440 (U+0440): L<<197.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* uni0447 (U+0447): L<<311.0,0.0>--<322.0,160.0>> -> L<<322.0,160.0>--<334.0,239.0>>

	* uni0463 (U+0463): L<<275.0,500.0>--<272.0,472.0>> -> L<<272.0,472.0>--<265.0,437.0>>

	* uni048F (U+048F): L<<197.0,23.0>--<197.0,-29.0>> -> L<<197.0,-29.0>--<185.0,-216.0>>

	* uni04B7 (U+04B7): L<<311.0,0.0>--<322.0,160.0>> -> L<<322.0,160.0>--<334.0,239.0>>

	* uni04B9 (U+04B9): L<<351.0,0.0>--<362.0,160.0>> -> L<<362.0,160.0>--<374.0,239.0>>

	* uni04BB (U+04BB): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<226.0,478.0>>

	* uni04CC (U+04CC): L<<331.0,150.0>--<332.0,160.0>> -> L<<332.0,160.0>--<344.0,239.0>>

	* uni04F5 (U+04F5): L<<311.0,0.0>--<322.0,160.0>> -> L<<322.0,160.0>--<334.0,239.0>>

	* uni04FC (U+04FC): L<<486.0,38.0>--<471.0,59.0>> -> L<<471.0,59.0>--<384.0,195.0>>

	* uni04FC (U+04FC): L<<510.0,356.0>--<635.0,158.0>> -> L<<635.0,158.0>--<654.0,126.0>>

	* uni04FD (U+04FD): L<<413.0,259.0>--<506.0,115.0>> -> L<<506.0,115.0>--<520.0,93.0>>

	* uni0527 (U+0527): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<226.0,477.0>>

	* uni1E25 (U+1E25): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<226.0,478.0>>

	* uni1E2B (U+1E2B): L<<251.0,736.0>--<238.0,549.0>> -> L<<238.0,549.0>--<226.0,478.0>>

	* uni20B1 (U+20B1): L<<667.0,480.0>--<667.0,466.0>> -> L<<667.0,466.0>--<666.0,453.0>>

	* uni2206 (U+2206): L<<481.0,720.0>--<859.0,2.0>> -> L<<859.0,2.0>--<860.0,0.0>>

	* uniA78B (U+A78B): L<<20.0,196.0>--<30.0,409.0>> -> L<<30.0,409.0>--<53.0,731.0>>

	* uniA78B (U+A78B): L<<223.0,731.0>--<200.0,409.0>> -> L<<200.0,409.0>--<180.0,196.0>>

	* uniA78C (U+A78C): L<<203.0,730.0>--<188.0,520.0>> -> L<<188.0,520.0>--<175.0,409.0>>

	* uniA78C (U+A78C): L<<35.0,409.0>--<38.0,520.0>> -> L<<38.0,520.0>--<53.0,730.0>> 

	* zeta (U+03B6): L<<496.0,564.0>--<487.0,438.0>> -> L<<487.0,438.0>--<487.0,401.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] NonBureau-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<208.0,736.0>--<194.0,539.0>> -> L<<194.0,539.0>--<185.0,475.0>>

	* d (U+0064): L<<420.0,474.0>--<419.0,539.0>> -> L<<419.0,539.0>--<433.0,736.0>>

	* dcaron (U+010F): L<<420.0,474.0>--<419.0,539.0>> -> L<<419.0,539.0>--<433.0,736.0>>

	* dcroat (U+0111): L<<420.0,474.0>--<419.0,539.0>> -> L<<419.0,539.0>--<424.0,598.0>>

	* dmacronbelow (U+1E0F): L<<420.0,474.0>--<419.0,539.0>> -> L<<419.0,539.0>--<433.0,736.0>>

	* f_f (U+FB00): L<<272.0,520.0>--<383.0,520.0>> -> L<<383.0,520.0>--<443.0,518.0>>

	* f_f_i (U+FB03): L<<272.0,520.0>--<370.0,520.0>> -> L<<370.0,520.0>--<429.0,518.0>>

	* hbar (U+0127): L<<282.0,598.0>--<277.0,539.0>> -> L<<277.0,539.0>--<264.0,460.0>>

	* p (U+0070): L<<155.0,46.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* q (U+0071): L<<367.0,-216.0>--<380.0,-19.0>> -> L<<380.0,-19.0>--<390.0,46.0>>

	* raisedmcsign (U+1F16A): L<<359.0,560.0>--<310.0,462.0>> -> L<<310.0,462.0>--<253.0,359.0>>

	* rho (U+03C1): L<<154.0,46.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* slash (U+002F): L<<333.0,714.0>--<332.0,710.0>> -> L<<332.0,710.0>--<70.0,-130.0>>

	* tau (U+03C4): L<<118.0,518.0>--<266.0,520.0>> -> L<<266.0,520.0>--<380.0,520.0>>

	* tau (U+03C4): L<<38.0,523.0>--<118.0,518.0>> -> L<<118.0,518.0>--<266.0,520.0>>

	* thorn (U+00FE): L<<155.0,46.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* trademark (U+2122): L<<688.0,560.0>--<638.0,462.0>> -> L<<638.0,462.0>--<582.0,359.0>>

	* uni0335 (U+0335): L<<115.0,304.0>--<254.0,306.0>> -> L<<254.0,306.0>--<339.0,306.0>>

	* uni0335 (U+0335): L<<30.0,309.0>--<115.0,304.0>> -> L<<115.0,304.0>--<254.0,306.0>>

	* uni03BC (U+03BC): L<<155.0,40.0>--<156.0,-18.0>> -> L<<156.0,-18.0>--<142.0,-217.0>>

	* uni0440 (U+0440): L<<155.0,46.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* uni0447 (U+0447): L<<314.0,0.0>--<326.0,167.0>> -> L<<326.0,167.0>--<337.0,243.0>>

	* uni0463 (U+0463): L<<251.0,527.0>--<246.0,468.0>> -> L<<246.0,468.0>--<238.0,419.0>>

	* uni048F (U+048F): L<<155.0,46.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* uni04B7 (U+04B7): L<<314.0,0.0>--<326.0,167.0>> -> L<<326.0,167.0>--<337.0,243.0>>

	* uni04B9 (U+04B9): L<<341.0,0.0>--<352.0,167.0>> -> L<<352.0,167.0>--<364.0,243.0>>

	* uni04CD (U+04CD): L<<203.0,714.0>--<324.0,411.0>> -> L<<324.0,411.0>--<401.0,199.0>>

	* uni04CD (U+04CD): L<<353.0,0.0>--<267.0,215.0>> -> L<<267.0,215.0>--<195.0,413.0>>

	* uni04CD (U+04CD): L<<622.0,0.0>--<626.0,215.0>> -> L<<626.0,215.0>--<639.0,413.0>>

	* uni04F5 (U+04F5): L<<314.0,0.0>--<326.0,167.0>> -> L<<326.0,167.0>--<337.0,243.0>>

	* uni04FC (U+04FC): L<<454.0,356.0>--<615.0,106.0>> -> L<<615.0,106.0>--<634.0,74.0>>

	* uni04FC (U+04FC): L<<506.0,10.0>--<486.0,40.0>> -> L<<486.0,40.0>--<360.0,236.0>>

	* uni04FD (U+04FD): L<<363.0,259.0>--<481.0,77.0>> -> L<<481.0,77.0>--<492.0,59.0>>

	* uni04FD (U+04FD): L<<380.0,-13.0>--<366.0,7.0>> -> L<<366.0,7.0>--<275.0,147.0>>

	* uni051B (U+051B): L<<367.0,-216.0>--<380.0,-19.0>> -> L<<380.0,-19.0>--<390.0,46.0>>

	* uni1E0D (U+1E0D): L<<420.0,474.0>--<419.0,539.0>> -> L<<419.0,539.0>--<433.0,736.0>>

	* uniA78B (U+A78B): L<<190.0,731.0>--<167.0,409.0>> -> L<<167.0,409.0>--<147.0,196.0>>

	* uniA78B (U+A78B): L<<27.0,196.0>--<37.0,409.0>> -> L<<37.0,409.0>--<60.0,731.0>>

	* uniA78C (U+A78C): L<<173.0,730.0>--<158.0,520.0>> -> L<<158.0,520.0>--<145.0,409.0>>

	* uniA78C (U+A78C): L<<42.0,409.0>--<45.0,520.0>> -> L<<45.0,520.0>--<60.0,730.0>> 

	* zeta (U+03B6): L<<462.0,563.0>--<456.0,474.0>> -> L<<456.0,474.0>--<455.0,441.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[15] NonBureauExtended-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* a (U+0061): X=313.5,Y=-1.0 (should be at baseline 0?)

	* f (U+0066): X=133.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=359.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=133.0,Y=518.0 (should be at x-height 520?)

	* bar (U+007C): X=40.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=90.0,Y=715.0 (should be at cap-height 714?)

	* onehalf (U+00BD): X=334.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=568.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=518.0,Y=716.0 (should be at cap-height 714?)

	* agrave (U+00E0): X=313.5,Y=-1.0 (should be at baseline 0?)

	* aacute (U+00E1): X=313.5,Y=-1.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=313.5,Y=-1.0 (should be at baseline 0?)

	* atilde (U+00E3): X=313.5,Y=-1.0 (should be at baseline 0?)

	* adieresis (U+00E4): X=313.5,Y=-1.0 (should be at baseline 0?)

	* aring (U+00E5): X=313.5,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=313.5,Y=-1.0 (should be at baseline 0?)

	* amacron (U+0101): X=313.5,Y=-1.0 (should be at baseline 0?)

	* abreve (U+0103): X=313.5,Y=-1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=313.5,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=424.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=208.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=423.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=207.0,Y=713.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=317.0,Y=716.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=333.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=197.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=261.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=418.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=202.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=301.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=85.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=384.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=168.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=313.5,Y=-1.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=384.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=168.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=430.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=214.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=433.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=433.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=217.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=217.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=262.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=388.0,Y=716.0 (should be at cap-height 714?)

	* aeacute (U+01FD): X=313.5,Y=-1.0 (should be at baseline 0?)

	* Oslashacute (U+01FE): X=518.0,Y=716.0 (should be at cap-height 714?)

	* uni023B (U+023B): X=528.0,Y=712.0 (should be at cap-height 714?)

	* uni0254 (U+0254): X=103.5,Y=-0.5 (should be at baseline 0?)

	* uni0269 (U+0269): X=189.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresistonos (U+0390): X=189.0,Y=-1.0 (should be at baseline 0?)

	* iotatonos (U+03AF): X=189.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=293.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=293.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=89.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=293.5,Y=714.5 (should be at cap-height 714?)

	* iota (U+03B9): X=189.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresis (U+03CA): X=189.0,Y=-1.0 (should be at baseline 0?)

	* uni0402 (U+0402): X=710.0,Y=-1.0 (should be at baseline 0?)

	* uni0430 (U+0430): X=313.5,Y=-1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=10.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=72.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=20.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=10.0,Y=2.0 (should be at baseline 0?)

	* Gemiddlehookcy (U+0494): X=496.0,Y=-1.0 (should be at baseline 0?)

	* uni04A6 (U+04A6): X=1070.0,Y=-1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=529.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=481.0,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=10.0,Y=2.0 (should be at baseline 0?)

	* uni04D1 (U+04D1): X=313.5,Y=-1.0 (should be at baseline 0?)

	* uni04D3 (U+04D3): X=313.5,Y=-1.0 (should be at baseline 0?)

	* uni04D5 (U+04D5): X=313.5,Y=-1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=30.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=10.0,Y=2.0 (should be at baseline 0?)

	* uni1EA1 (U+1EA1): X=313.5,Y=-1.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=40.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=90.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=240.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=290.0,Y=715.0 (should be at cap-height 714?)

	* emptyset (U+2205): X=81.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=838.0,Y=2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=304.0,Y=-1.5 (should be at baseline 0?) 

	* uni2C65 (U+2C65): X=313.5,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<88.0,736.0>--<88.0,520.0>> -> L<<88.0,520.0>--<83.0,412.0>>

	* beta (U+03B2): L<<84.0,112.0>--<89.0,-1.0>> -> L<<89.0,-1.0>--<88.0,-217.0>>

	* d (U+0064): L<<565.0,412.0>--<560.0,520.0>> -> L<<560.0,520.0>--<560.0,736.0>>

	* dcaron (U+010F): L<<565.0,412.0>--<560.0,520.0>> -> L<<560.0,520.0>--<560.0,736.0>>

	* dcroat (U+0111): L<<565.0,412.0>--<560.0,520.0>> -> L<<560.0,520.0>--<560.0,619.0>>

	* dmacronbelow (U+1E0F): L<<565.0,412.0>--<560.0,520.0>> -> L<<560.0,520.0>--<560.0,736.0>>

	* dong (U+20AB): L<<445.0,430.0>--<440.0,508.0>> -> L<<440.0,508.0>--<440.0,570.0>>

	* f_f (U+FB00): L<<181.0,520.0>--<325.0,520.0>> -> L<<325.0,520.0>--<418.0,518.0>>

	* f_f_i (U+FB03): L<<181.0,520.0>--<325.0,520.0>> -> L<<325.0,520.0>--<418.0,518.0>>

	* f_t (U+FB05): L<<181.0,520.0>--<310.0,520.0>> -> L<<310.0,520.0>--<418.0,518.0>>

	* p (U+0070): L<<83.0,108.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* q (U+0071): L<<560.0,-216.0>--<560.0,0.0>> -> L<<560.0,0.0>--<565.0,108.0>>

	* rho (U+03C1): L<<83.0,108.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* tau (U+03C4): L<<133.0,518.0>--<181.0,520.0>> -> L<<181.0,520.0>--<355.0,520.0>>

	* tau (U+03C4): L<<40.0,523.0>--<133.0,518.0>> -> L<<133.0,518.0>--<181.0,520.0>>

	* thorn (U+00FE): L<<83.0,108.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* thorn (U+00FE): L<<88.0,736.0>--<88.0,520.0>> -> L<<88.0,520.0>--<83.0,422.0>>

	* uni0335 (U+0335): L<<119.0,278.0>--<161.0,280.0>> -> L<<161.0,280.0>--<240.0,280.0>>

	* uni03BC (U+03BC): L<<83.0,88.0>--<88.0,28.0>> -> L<<88.0,28.0>--<88.0,-217.0>>

	* uni0440 (U+0440): L<<83.0,108.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* uni0447 (U+0447): L<<479.0,0.0>--<479.0,181.0>> -> L<<479.0,181.0>--<484.0,252.0>>

	* uni0463 (U+0463): L<<180.0,582.0>--<180.0,460.0>> -> L<<180.0,460.0>--<175.0,382.0>>

	* uni048F (U+048F): L<<83.0,108.0>--<88.0,0.0>> -> L<<88.0,0.0>--<88.0,-216.0>>

	* uni04B7 (U+04B7): L<<479.0,0.0>--<479.0,181.0>> -> L<<479.0,181.0>--<484.0,252.0>>

	* uni04B9 (U+04B9): L<<479.0,0.0>--<479.0,181.0>> -> L<<479.0,181.0>--<484.0,252.0>>

	* uni04CC (U+04CC): L<<479.0,42.0>--<479.0,181.0>> -> L<<479.0,181.0>--<484.0,252.0>>

	* uni04F5 (U+04F5): L<<479.0,0.0>--<479.0,181.0>> -> L<<479.0,181.0>--<484.0,252.0>>

	* uni04FC (U+04FC): L<<395.0,357.0>--<700.0,0.0>> -> L<<700.0,0.0>--<727.0,-30.0>>

	* uni04FC (U+04FC): L<<669.0,-46.0>--<631.0,0.0>> -> L<<631.0,0.0>--<360.0,317.0>>

	* uni04FD (U+04FD): L<<263.0,260.0>--<450.0,0.0>> -> L<<450.0,0.0>--<455.0,-7.0>>

	* uni04FD (U+04FD): L<<426.0,-46.0>--<395.0,0.0>> -> L<<395.0,0.0>--<235.0,222.0>>

	* uni051B (U+051B): L<<560.0,-216.0>--<560.0,0.0>> -> L<<560.0,0.0>--<565.0,108.0>>

	* uni1E0D (U+1E0D): L<<565.0,412.0>--<560.0,520.0>> -> L<<560.0,520.0>--<560.0,736.0>>

	* uniA78B (U+A78B): L<<45.0,196.0>--<40.0,409.0>> -> L<<40.0,409.0>--<40.0,731.0>>

	* uniA78B (U+A78B): L<<90.0,731.0>--<90.0,409.0>> -> L<<90.0,409.0>--<85.0,196.0>>

	* uniA78C (U+A78C): L<<45.0,409.0>--<40.0,520.0>> -> L<<40.0,520.0>--<40.0,730.0>> 

	* uniA78C (U+A78C): L<<80.0,730.0>--<80.0,520.0>> -> L<<80.0,520.0>--<75.0,409.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<190.0,600.0>--<714.0,602.0>>

	* arrowleft (U+2190): L<<439.0,271.0>--<440.0,61.0>>

	* arrowleft (U+2190): L<<440.0,529.0>--<439.0,319.0>>

	* arrowright (U+2192): L<<214.0,61.0>--<215.0,271.0>>

	* arrowright (U+2192): L<<215.0,319.0>--<214.0,529.0>>

	* beta (U+03B2): L<<89.0,-1.0>--<88.0,-217.0>>

	* estimated (U+212E): L<<616.0,347.0>--<615.0,499.0>>

	* uni046A (U+046A): L<<316.0,0.0>--<317.0,370.0>>

	* uni046A (U+046A): L<<367.0,370.0>--<366.0,0.0>>

	* uni046B (U+046B): L<<237.0,0.0>--<238.0,256.0>> 

	* uni25B5 (U+25B5): L<<502.0,133.0>--<20.0,134.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NonBureauExtended-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Medium' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ae (U+00E6): L<<1131.0,258.0>--<868.0,235.0>> -> L<<868.0,235.0>--<635.0,228.0>>

	* aeacute (U+01FD): L<<1131.0,258.0>--<868.0,235.0>> -> L<<868.0,235.0>--<635.0,228.0>>

	* b (U+0062): L<<186.0,736.0>--<172.0,535.0>> -> L<<172.0,535.0>--<162.0,454.0>>

	* beta (U+03B2): L<<137.0,73.0>--<137.0,-1.0>> -> L<<137.0,-1.0>--<120.0,-217.0>>

	* d (U+0064): L<<546.0,449.0>--<547.0,535.0>> -> L<<547.0,535.0>--<561.0,736.0>>

	* dcaron (U+010F): L<<546.0,449.0>--<547.0,535.0>> -> L<<547.0,535.0>--<561.0,736.0>>

	* dcroat (U+0111): L<<546.0,450.0>--<548.0,535.0>> -> L<<548.0,535.0>--<552.0,603.0>>

	* dmacronbelow (U+1E0F): L<<546.0,449.0>--<547.0,535.0>> -> L<<547.0,535.0>--<561.0,736.0>>

	* f_f (U+FB00): L<<254.0,520.0>--<393.0,520.0>> -> L<<393.0,520.0>--<476.0,518.0>>

	* f_f_i (U+FB03): L<<254.0,520.0>--<393.0,520.0>> -> L<<393.0,520.0>--<476.0,518.0>>

	* f_t (U+FB05): L<<254.0,520.0>--<366.0,520.0>> -> L<<366.0,520.0>--<460.0,518.0>>

	* oe (U+0153): L<<1215.0,258.0>--<952.0,235.0>> -> L<<952.0,235.0>--<719.0,228.0>>

	* p (U+0070): L<<134.0,66.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* q (U+0071): L<<494.0,-216.0>--<508.0,-14.0>> -> L<<508.0,-14.0>--<518.0,65.0>>

	* rho (U+03C1): L<<134.0,66.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* slash (U+002F): L<<334.0,714.0>--<333.0,710.0>> -> L<<333.0,710.0>--<71.0,-130.0>>

	* tau (U+03C4): L<<126.0,518.0>--<249.0,520.0>> -> L<<249.0,520.0>--<408.0,520.0>>

	* tau (U+03C4): L<<43.0,523.0>--<126.0,518.0>> -> L<<126.0,518.0>--<249.0,520.0>>

	* thorn (U+00FE): L<<134.0,66.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* trademark (U+2122): L<<747.0,594.0>--<665.0,442.0>> -> L<<665.0,442.0>--<609.0,359.0>>

	* uni0335 (U+0335): L<<127.0,298.0>--<242.0,300.0>> -> L<<242.0,300.0>--<325.0,300.0>>

	* uni0335 (U+0335): L<<43.0,303.0>--<127.0,298.0>> -> L<<127.0,298.0>--<242.0,300.0>>

	* uni03BC (U+03BC): L<<135.0,57.0>--<136.0,-6.0>> -> L<<136.0,-6.0>--<120.0,-217.0>>

	* uni0440 (U+0440): L<<134.0,66.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* uni0447 (U+0447): L<<447.0,0.0>--<458.0,171.0>> -> L<<458.0,171.0>--<469.0,246.0>>

	* uni0463 (U+0463): L<<239.0,541.0>--<233.0,467.0>> -> L<<233.0,467.0>--<223.0,409.0>>

	* uni048F (U+048F): L<<134.0,66.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* uni04B7 (U+04B7): L<<447.0,0.0>--<458.0,171.0>> -> L<<458.0,171.0>--<469.0,246.0>>

	* uni04B9 (U+04B9): L<<447.0,0.0>--<458.0,171.0>> -> L<<458.0,171.0>--<469.0,246.0>>

	* uni04CC (U+04CC): L<<458.0,96.0>--<464.0,184.0>> -> L<<464.0,184.0>--<474.0,245.0>>

	* uni04CD (U+04CD): L<<170.0,714.0>--<300.0,487.0>> -> L<<300.0,487.0>--<445.0,164.0>>

	* uni04CD (U+04CD): L<<743.0,0.0>--<738.0,162.0>> -> L<<738.0,162.0>--<758.0,468.0>>

	* uni04CD (U+04CD): L<<877.0,714.0>--<887.0,441.0>> -> L<<887.0,441.0>--<929.0,108.0>>

	* uni04D5 (U+04D5): L<<1131.0,258.0>--<868.0,235.0>> -> L<<868.0,235.0>--<635.0,228.0>>

	* uni04F5 (U+04F5): L<<447.0,0.0>--<458.0,171.0>> -> L<<458.0,171.0>--<469.0,246.0>>

	* uni04FC (U+04FC): L<<481.0,356.0>--<692.0,80.0>> -> L<<692.0,80.0>--<716.0,48.0>>

	* uni04FC (U+04FC): L<<597.0,-4.0>--<572.0,29.0>> -> L<<572.0,29.0>--<395.0,259.0>>

	* uni04FD (U+04FD): L<<338.0,259.0>--<469.0,58.0>> -> L<<469.0,58.0>--<478.0,43.0>>

	* uni04FD (U+04FD): L<<387.0,-21.0>--<370.0,6.0>> -> L<<370.0,6.0>--<265.0,167.0>>

	* uni051B (U+051B): L<<494.0,-216.0>--<508.0,-14.0>> -> L<<508.0,-14.0>--<518.0,66.0>>

	* uni1E0D (U+1E0D): L<<546.0,449.0>--<547.0,535.0>> -> L<<547.0,535.0>--<561.0,736.0>>

	* uniA78B (U+A78B): L<<173.0,731.0>--<150.0,409.0>> -> L<<150.0,409.0>--<130.0,196.0>>

	* uniA78B (U+A78B): L<<30.0,196.0>--<40.0,409.0>> -> L<<40.0,409.0>--<63.0,731.0>>

	* uniA78C (U+A78C): L<<158.0,730.0>--<143.0,520.0>> -> L<<143.0,520.0>--<130.0,409.0>> 

	* uniA78C (U+A78C): L<<45.0,409.0>--<48.0,520.0>> -> L<<48.0,520.0>--<63.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] NonBureau-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<229.0,736.0>--<216.0,544.0>> -> L<<216.0,544.0>--<207.0,487.0>>

	* d (U+0064): L<<416.0,485.0>--<415.0,544.0>> -> L<<415.0,544.0>--<428.0,736.0>>

	* dcaron (U+010F): L<<416.0,485.0>--<415.0,544.0>> -> L<<415.0,544.0>--<428.0,736.0>>

	* dcroat (U+0111): L<<416.0,485.0>--<415.0,544.0>> -> L<<415.0,544.0>--<418.0,592.0>>

	* dmacronbelow (U+1E0F): L<<416.0,485.0>--<415.0,544.0>> -> L<<415.0,544.0>--<428.0,736.0>>

	* f_f (U+FB00): L<<291.0,520.0>--<398.0,520.0>> -> L<<398.0,520.0>--<449.0,518.0>>

	* f_f_i (U+FB03): L<<291.0,520.0>--<391.0,520.0>> -> L<<391.0,520.0>--<443.0,518.0>>

	* p (U+0070): L<<176.0,35.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* q (U+0071): L<<362.0,-216.0>--<375.0,-24.0>> -> L<<375.0,-24.0>--<384.0,34.0>>

	* raisedmcsign (U+1F16A): L<<136.0,537.0>--<131.0,488.0>> -> L<<131.0,488.0>--<115.0,359.0>>

	* raisedmcsign (U+1F16A): L<<243.0,515.0>--<267.0,560.0>> -> L<<267.0,560.0>--<358.0,714.0>>

	* raisedmcsign (U+1F16A): L<<357.0,537.0>--<331.0,488.0>> -> L<<331.0,488.0>--<267.0,359.0>>

	* rho (U+03C1): L<<175.0,35.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* slash (U+002F): L<<349.0,714.0>--<348.0,710.0>> -> L<<348.0,710.0>--<86.0,-130.0>>

	* tau (U+03C4): L<<109.0,518.0>--<282.0,520.0>> -> L<<282.0,520.0>--<391.0,520.0>>

	* tau (U+03C4): L<<33.0,523.0>--<109.0,518.0>> -> L<<109.0,518.0>--<282.0,520.0>>

	* thorn (U+00FE): L<<176.0,35.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* trademark (U+2122): L<<470.0,537.0>--<465.0,488.0>> -> L<<465.0,488.0>--<448.0,359.0>>

	* trademark (U+2122): L<<576.0,515.0>--<600.0,560.0>> -> L<<600.0,560.0>--<691.0,714.0>>

	* trademark (U+2122): L<<691.0,537.0>--<665.0,488.0>> -> L<<665.0,488.0>--<600.0,359.0>>

	* uni023E (U+023E): L<<273.0,0.0>--<256.0,-12.0>> -> L<<256.0,-12.0>--<194.0,-53.0>>

	* uni0335 (U+0335): L<<114.0,311.0>--<277.0,313.0>> -> L<<277.0,313.0>--<364.0,313.0>>

	* uni0335 (U+0335): L<<27.0,316.0>--<114.0,311.0>> -> L<<114.0,311.0>--<277.0,313.0>>

	* uni03BC (U+03BC): L<<176.0,31.0>--<177.0,-29.0>> -> L<<177.0,-29.0>--<163.0,-217.0>>

	* uni0440 (U+0440): L<<176.0,35.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* uni0447 (U+0447): L<<313.0,0.0>--<324.0,164.0>> -> L<<324.0,164.0>--<336.0,241.0>>

	* uni0463 (U+0463): L<<263.0,514.0>--<259.0,470.0>> -> L<<259.0,470.0>--<252.0,428.0>>

	* uni048F (U+048F): L<<176.0,35.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* uni04B7 (U+04B7): L<<313.0,0.0>--<324.0,164.0>> -> L<<324.0,164.0>--<336.0,241.0>>

	* uni04B9 (U+04B9): L<<346.0,0.0>--<357.0,164.0>> -> L<<357.0,164.0>--<369.0,241.0>>

	* uni04CC (U+04CC): L<<330.0,132.0>--<332.0,164.0>> -> L<<332.0,164.0>--<344.0,241.0>>

	* uni04CD (U+04CD): L<<235.0,714.0>--<373.0,335.0>> -> L<<373.0,335.0>--<413.0,229.0>>

	* uni04CD (U+04CD): L<<348.0,0.0>--<252.0,269.0>> -> L<<252.0,269.0>--<215.0,368.0>>

	* uni04CD (U+04CD): L<<611.0,0.0>--<625.0,269.0>> -> L<<625.0,269.0>--<630.0,368.0>>

	* uni04F5 (U+04F5): L<<313.0,0.0>--<324.0,164.0>> -> L<<324.0,164.0>--<336.0,241.0>>

	* uni04FC (U+04FC): L<<482.0,356.0>--<625.0,132.0>> -> L<<625.0,132.0>--<644.0,100.0>>

	* uni04FC (U+04FC): L<<496.0,24.0>--<479.0,49.0>> -> L<<479.0,49.0>--<372.0,215.0>>

	* uni04FD (U+04FD): L<<374.0,-5.0>--<364.0,9.0>> -> L<<364.0,9.0>--<285.0,129.0>>

	* uni04FD (U+04FD): L<<388.0,259.0>--<494.0,96.0>> -> L<<494.0,96.0>--<506.0,76.0>>

	* uni051B (U+051B): L<<362.0,-216.0>--<375.0,-24.0>> -> L<<375.0,-24.0>--<384.0,35.0>>

	* uni1E0D (U+1E0D): L<<416.0,485.0>--<415.0,544.0>> -> L<<415.0,544.0>--<428.0,736.0>>

	* uni2206 (U+2206): L<<469.0,720.0>--<836.0,2.0>> -> L<<836.0,2.0>--<837.0,0.0>>

	* uniA78B (U+A78B): L<<206.0,731.0>--<183.0,409.0>> -> L<<183.0,409.0>--<163.0,196.0>>

	* uniA78B (U+A78B): L<<23.0,196.0>--<33.0,409.0>> -> L<<33.0,409.0>--<56.0,731.0>>

	* uniA78C (U+A78C): L<<188.0,730.0>--<173.0,520.0>> -> L<<173.0,520.0>--<160.0,409.0>>

	* uniA78C (U+A78C): L<<38.0,409.0>--<41.0,520.0>> -> L<<41.0,520.0>--<56.0,730.0>> 

	* zeta (U+03B6): L<<479.0,564.0>--<471.0,456.0>> -> L<<471.0,456.0>--<471.0,421.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] NonBureau-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<121.0,736.0>--<106.0,520.0>> -> L<<106.0,520.0>--<94.0,429.0>>

	* beta (U+03B2): L<<73.0,93.0>--<72.0,-1.0>> -> L<<72.0,-1.0>--<55.0,-217.0>>

	* d (U+0064): L<<437.0,427.0>--<438.0,520.0>> -> L<<438.0,520.0>--<453.0,736.0>>

	* dcaron (U+010F): L<<437.0,427.0>--<438.0,520.0>> -> L<<438.0,520.0>--<453.0,736.0>>

	* dcroat (U+0111): L<<437.0,427.0>--<438.0,520.0>> -> L<<438.0,520.0>--<445.0,619.0>>

	* dmacronbelow (U+1E0F): L<<437.0,427.0>--<438.0,520.0>> -> L<<438.0,520.0>--<453.0,736.0>>

	* dong (U+20AB): L<<377.0,435.0>--<377.0,508.0>> -> L<<377.0,508.0>--<382.0,570.0>>

	* f_f (U+FB00): L<<199.0,520.0>--<323.0,520.0>> -> L<<323.0,520.0>--<416.0,518.0>>

	* f_f_i (U+FB03): L<<199.0,520.0>--<283.0,520.0>> -> L<<283.0,520.0>--<376.0,518.0>>

	* p (U+0070): L<<71.0,93.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* q (U+0071): L<<387.0,-216.0>--<402.0,0.0>> -> L<<402.0,0.0>--<413.0,93.0>>

	* rho (U+03C1): L<<71.0,93.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* slash (U+002F): L<<266.0,714.0>--<265.0,710.0>> -> L<<265.0,710.0>--<3.0,-130.0>>

	* tau (U+03C4): L<<151.0,518.0>--<199.0,520.0>> -> L<<199.0,520.0>--<333.0,520.0>>

	* tau (U+03C4): L<<58.0,523.0>--<151.0,518.0>> -> L<<151.0,518.0>--<199.0,520.0>>

	* thorn (U+00FE): L<<71.0,93.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* uni0335 (U+0335): L<<121.0,278.0>--<163.0,280.0>> -> L<<163.0,280.0>--<242.0,280.0>>

	* uni0440 (U+0440): L<<71.0,93.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* uni0447 (U+0447): L<<321.0,0.0>--<333.0,181.0>> -> L<<333.0,181.0>--<343.0,252.0>>

	* uni0452 (U+0452): L<<204.0,592.0>--<196.0,480.0>> -> L<<196.0,480.0>--<185.0,387.0>>

	* uni045B (U+045B): L<<204.0,592.0>--<196.0,480.0>> -> L<<196.0,480.0>--<185.0,387.0>>

	* uni0463 (U+0463): L<<203.0,582.0>--<195.0,460.0>> -> L<<195.0,460.0>--<184.0,382.0>>

	* uni048F (U+048F): L<<71.0,93.0>--<70.0,0.0>> -> L<<70.0,0.0>--<55.0,-216.0>>

	* uni04B7 (U+04B7): L<<321.0,0.0>--<333.0,181.0>> -> L<<333.0,181.0>--<343.0,252.0>>

	* uni04B9 (U+04B9): L<<321.0,0.0>--<333.0,181.0>> -> L<<333.0,181.0>--<343.0,252.0>>

	* uni04CC (U+04CC): L<<324.0,42.0>--<333.0,181.0>> -> L<<333.0,181.0>--<343.0,252.0>>

	* uni04F5 (U+04F5): L<<321.0,0.0>--<333.0,181.0>> -> L<<333.0,181.0>--<343.0,252.0>>

	* uni04FC (U+04FC): L<<343.0,357.0>--<575.0,1.0>> -> L<<575.0,1.0>--<595.0,-31.0>>

	* uni04FC (U+04FC): L<<546.0,-45.0>--<517.0,1.0>> -> L<<517.0,1.0>--<311.0,317.0>>

	* uni04FD (U+04FD): L<<262.0,260.0>--<431.0,0.0>> -> L<<431.0,0.0>--<436.0,-8.0>>

	* uni04FD (U+04FD): L<<405.0,-45.0>--<377.0,0.0>> -> L<<377.0,0.0>--<232.0,222.0>>

	* uni051B (U+051B): L<<387.0,-216.0>--<402.0,0.0>> -> L<<402.0,0.0>--<413.0,93.0>>

	* uni1E0D (U+1E0D): L<<437.0,427.0>--<438.0,520.0>> -> L<<438.0,520.0>--<453.0,736.0>>

	* uniA78B (U+A78B): L<<123.0,731.0>--<100.0,409.0>> -> L<<100.0,409.0>--<80.0,196.0>>

	* uniA78B (U+A78B): L<<40.0,196.0>--<50.0,409.0>> -> L<<50.0,409.0>--<73.0,731.0>>

	* uniA78C (U+A78C): L<<113.0,730.0>--<98.0,520.0>> -> L<<98.0,520.0>--<85.0,409.0>>

	* uniA78C (U+A78C): L<<55.0,409.0>--<58.0,520.0>> -> L<<58.0,520.0>--<73.0,730.0>> 

	* zeta (U+03B6): L<<394.0,562.0>--<393.0,545.0>> -> L<<393.0,545.0>--<392.0,520.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NonBureau-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=106.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=392.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=100.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=380.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=243.0,Y=1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=302.0,Y=1.0 (should be at baseline 0?)

	* bar (U+007C): X=27.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=170.0,Y=715.0 (should be at cap-height 714?)

	* braceright (U+007D): X=23.0,Y=1.0 (should be at baseline 0?)

	* braceright (U+007D): X=82.0,Y=1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=143.0,Y=713.0 (should be at cap-height 714?)

	* ordmasculine (U+00BA): X=155.0,Y=713.0 (should be at cap-height 714?)

	* ordmasculine (U+00BA): X=155.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=431.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=122.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=439.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=130.0,Y=713.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=285.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=410.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=439.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=130.0,Y=713.0 (should be at cap-height 714?)

	* Eng (U+014A): X=508.0,Y=1.0 (should be at baseline 0?)

	* rcaron (U+0159): X=373.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=64.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=413.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=104.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=380.0,Y=-1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=380.0,Y=-1.0 (should be at baseline 0?)

	* tbar (U+0167): X=380.0,Y=-1.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=419.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=110.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=442.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=133.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=453.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=144.0,Y=713.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=380.0,Y=-1.0 (should be at baseline 0?)

	* uni023B (U+023B): X=460.0,Y=715.0 (should be at cap-height 714?)

	* dieresistonos (U+0385): X=253.0,Y=713.0 (should be at cap-height 714?)

	* dieresistonos (U+0385): X=401.0,Y=713.0 (should be at cap-height 714?)

	* iotadieresistonos (U+0390): X=74.0,Y=713.0 (should be at cap-height 714?)

	* iotadieresistonos (U+0390): X=222.0,Y=713.0 (should be at cap-height 714?)

	* alphatonos (U+03AC): X=620.0,Y=-1.0 (should be at baseline 0?)

	* upsilondieresistonos (U+03B0): X=241.0,Y=713.0 (should be at cap-height 714?)

	* upsilondieresistonos (U+03B0): X=389.0,Y=713.0 (should be at cap-height 714?)

	* alpha (U+03B1): X=620.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=313.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=245.5,Y=-0.5 (should be at baseline 0?)

	* beta (U+03B2): X=176.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=251.0,Y=713.0 (should be at cap-height 714?)

	* uni03BC (U+03BC): X=217.5,Y=1.0 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=361.5,Y=1.5 (should be at baseline 0?)

	* uni0409 (U+0409): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=3.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=179.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=13.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=3.0,Y=2.0 (should be at baseline 0?)

	* uni048F (U+048F): X=388.0,Y=-1.0 (should be at baseline 0?)

	* gemiddlehookcy (U+0495): X=364.5,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=732.5,Y=1.0 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=3.0,Y=2.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=3.0,Y=2.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=380.0,Y=-1.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=380.0,Y=-1.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=27.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=170.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=320.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=463.0,Y=715.0 (should be at cap-height 714?)

	* uni20BF (U+20BF): X=389.0,Y=1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=73.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=831.0,Y=2.0 (should be at baseline 0?)

	* summation (U+2211): X=181.0,Y=-2.0 (should be at baseline 0?)

	* summation (U+2211): X=464.0,Y=-2.0 (should be at baseline 0?)

	* summation (U+2211): X=27.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=367.0,Y=-1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=380.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=393.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=406.5,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=420.0,Y=-1.0 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=380.0,Y=-1.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=703.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<175.0,736.0>--<175.0,539.0>> -> L<<175.0,539.0>--<170.0,474.0>>

	* d (U+0064): L<<405.0,474.0>--<400.0,539.0>> -> L<<400.0,539.0>--<400.0,736.0>>

	* dcaron (U+010F): L<<405.0,474.0>--<400.0,539.0>> -> L<<400.0,539.0>--<400.0,736.0>>

	* dcroat (U+0111): L<<402.0,460.0>--<400.0,520.0>> -> L<<400.0,520.0>--<400.0,598.0>>

	* dmacronbelow (U+1E0F): L<<405.0,474.0>--<400.0,539.0>> -> L<<400.0,539.0>--<400.0,736.0>>

	* f_f (U+FB00): L<<254.0,520.0>--<365.0,520.0>> -> L<<365.0,520.0>--<425.0,518.0>>

	* f_f_i (U+FB03): L<<254.0,520.0>--<352.0,520.0>> -> L<<352.0,520.0>--<411.0,518.0>>

	* f_t (U+FB05): L<<254.0,520.0>--<346.0,520.0>> -> L<<346.0,520.0>--<423.0,518.0>>

	* p (U+0070): L<<170.0,46.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* q (U+0071): L<<400.0,-216.0>--<400.0,-19.0>> -> L<<400.0,-19.0>--<405.0,46.0>>

	* raisedmcsign (U+1F16A): L<<339.0,560.0>--<296.0,462.0>> -> L<<296.0,462.0>--<246.0,359.0>>

	* raisedmdsign (U+1F16B): L<<339.0,560.0>--<296.0,462.0>> -> L<<296.0,462.0>--<246.0,359.0>>

	* raisedmrsign (U+1F16C): L<<339.0,560.0>--<296.0,462.0>> -> L<<296.0,462.0>--<246.0,359.0>>

	* rho (U+03C1): L<<170.0,46.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* tau (U+03C4): L<<100.0,518.0>--<248.0,520.0>> -> L<<248.0,520.0>--<362.0,520.0>>

	* tau (U+03C4): L<<20.0,523.0>--<100.0,518.0>> -> L<<100.0,518.0>--<248.0,520.0>>

	* thorn (U+00FE): L<<170.0,46.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* trademark (U+2122): L<<667.0,560.0>--<624.0,462.0>> -> L<<624.0,462.0>--<574.0,359.0>>

	* uni0335 (U+0335): L<<112.0,304.0>--<251.0,306.0>> -> L<<251.0,306.0>--<336.0,306.0>>

	* uni0335 (U+0335): L<<27.0,309.0>--<112.0,304.0>> -> L<<112.0,304.0>--<251.0,306.0>>

	* uni03BC (U+03BC): L<<170.0,40.0>--<175.0,-18.0>> -> L<<175.0,-18.0>--<175.0,-217.0>>

	* uni0440 (U+0440): L<<170.0,46.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* uni0447 (U+0447): L<<332.0,0.0>--<332.0,167.0>> -> L<<332.0,167.0>--<339.0,245.0>>

	* uni0463 (U+0463): L<<232.0,527.0>--<232.0,473.0>> -> L<<232.0,473.0>--<227.0,419.0>>

	* uni048F (U+048F): L<<170.0,46.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* uni04B7 (U+04B7): L<<332.0,0.0>--<332.0,167.0>> -> L<<332.0,167.0>--<339.0,245.0>>

	* uni04B9 (U+04B9): L<<359.0,0.0>--<359.0,167.0>> -> L<<359.0,167.0>--<366.0,245.0>>

	* uni04F5 (U+04F5): L<<332.0,0.0>--<332.0,167.0>> -> L<<332.0,167.0>--<339.0,245.0>>

	* uni04FC (U+04FC): L<<447.0,357.0>--<627.0,106.0>> -> L<<627.0,106.0>--<648.0,75.0>>

	* uni04FC (U+04FC): L<<522.0,9.0>--<500.0,40.0>> -> L<<500.0,40.0>--<360.0,236.0>>

	* uni04FD (U+04FD): L<<363.0,260.0>--<495.0,77.0>> -> L<<495.0,77.0>--<507.0,61.0>>

	* uni04FD (U+04FD): L<<398.0,-15.0>--<383.0,7.0>> -> L<<383.0,7.0>--<282.0,147.0>>

	* uni051B (U+051B): L<<400.0,-216.0>--<400.0,-19.0>> -> L<<400.0,-19.0>--<405.0,46.0>>

	* uni1E0D (U+1E0D): L<<405.0,474.0>--<400.0,539.0>> -> L<<400.0,539.0>--<400.0,736.0>>

	* uniA78B (U+A78B): L<<157.0,731.0>--<157.0,409.0>> -> L<<157.0,409.0>--<152.0,196.0>>

	* uniA78B (U+A78B): L<<32.0,196.0>--<27.0,409.0>> -> L<<27.0,409.0>--<27.0,731.0>>

	* uniA78C (U+A78C): L<<140.0,730.0>--<140.0,520.0>> -> L<<140.0,520.0>--<135.0,409.0>> 

	* uniA78C (U+A78C): L<<32.0,409.0>--<27.0,520.0>> -> L<<27.0,520.0>--<27.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<250.0,624.0>--<594.0,626.0>>

	* ampersand (U+0026): L<<526.0,337.0>--<656.0,338.0>>

	* arrowleft (U+2190): L<<452.0,243.0>--<453.0,20.0>>

	* arrowleft (U+2190): L<<452.0,345.0>--<621.0,344.0>>

	* arrowleft (U+2190): L<<453.0,568.0>--<452.0,345.0>>

	* arrowleft (U+2190): L<<621.0,244.0>--<452.0,243.0>>

	* arrowright (U+2192): L<<13.0,344.0>--<182.0,345.0>>

	* arrowright (U+2192): L<<181.0,20.0>--<182.0,243.0>>

	* arrowright (U+2192): L<<182.0,243.0>--<13.0,244.0>>

	* arrowright (U+2192): L<<182.0,345.0>--<181.0,568.0>>

	* beta (U+03B2): L<<176.0,-1.0>--<175.0,-217.0>>

	* chi (U+03C7): L<<13.0,399.0>--<14.0,522.0>>

	* franc (U+20A3): L<<254.0,203.0>--<455.0,204.0>>

	* oe (U+0153): L<<983.0,228.0>--<613.0,227.0>>

	* psi (U+03C8): L<<253.0,101.0>--<254.0,520.0>>

	* psi (U+03C8): L<<350.0,520.0>--<349.0,101.0>>

	* uni018F (U+018F): L<<196.0,391.0>--<528.0,393.0>>

	* uni046A (U+046A): L<<369.0,0.0>--<370.0,277.0>>

	* uni046A (U+046A): L<<527.0,277.0>--<526.0,0.0>>

	* uni046B (U+046B): L<<268.0,0.0>--<269.0,197.0>>

	* uni046B (U+046B): L<<416.0,197.0>--<415.0,0.0>>

	* uni04BC (U+04BC): L<<361.0,432.0>--<712.0,433.0>>

	* uni04BE (U+04BE): L<<361.0,432.0>--<712.0,433.0>>

	* uni04D8 (U+04D8): L<<545.0,281.0>--<187.0,280.0>>

	* uni04DA (U+04DA): L<<545.0,281.0>--<187.0,280.0>>

	* uni04E9 (U+04E9): L<<179.0,315.0>--<397.0,316.0>>

	* uni04EB (U+04EB): L<<179.0,315.0>--<397.0,316.0>>

	* uni20B4 (U+20B4): L<<26.0,318.0>--<729.0,319.0>> 

	* uniAB53 (U+AB53): L<<13.0,399.0>--<14.0,522.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NonBureauExtended-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Light' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* N (U+004E): X=145.0,Y=713.0 (should be at cap-height 714?)

	* W (U+0057): X=585.0,Y=713.0 (should be at cap-height 714?)

	* f (U+0066): X=144.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=395.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=143.0,Y=518.0 (should be at x-height 520?)

	* bar (U+007C): X=69.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=142.0,Y=715.0 (should be at cap-height 714?)

	* registered (U+00AE): X=337.0,Y=715.0 (should be at cap-height 714?)

	* onehalf (U+00BD): X=300.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=537.0,Y=1.0 (should be at baseline 0?)

	* Ntilde (U+00D1): X=145.0,Y=713.0 (should be at cap-height 714?)

	* germandbls (U+00DF): X=167.5,Y=714.5 (should be at cap-height 714?)

	* germandbls (U+00DF): X=392.5,Y=712.5 (should be at cap-height 714?)

	* aring (U+00E5): X=316.0,Y=712.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=483.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=243.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=483.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=243.0,Y=713.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=349.0,Y=716.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=372.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=251.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=331.0,Y=716.0 (should be at cap-height 714?)

	* Nacute (U+0143): X=145.0,Y=713.0 (should be at cap-height 714?)

	* uni0145 (U+0145): X=145.0,Y=713.0 (should be at cap-height 714?)

	* Ncaron (U+0147): X=145.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=458.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=218.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=353.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=113.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=430.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=190.0,Y=713.0 (should be at cap-height 714?)

	* Wcircumflex (U+0174): X=585.0,Y=713.0 (should be at cap-height 714?)

	* uni0186 (U+0186): X=106.0,Y=2.0 (should be at baseline 0?)

	* florin (U+0192): X=-8.0,Y=-2.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=438.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=198.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=478.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=238.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=480.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=480.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=240.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=240.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=299.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=420.0,Y=716.0 (should be at cap-height 714?)

	* uni0241 (U+0241): X=299.0,Y=-2.0 (should be at baseline 0?)

	* uni0241 (U+0241): X=223.0,Y=2.0 (should be at baseline 0?)

	* uni0241 (U+0241): X=299.0,Y=-2.0 (should be at baseline 0?)

	* uni0254 (U+0254): X=83.5,Y=-2.0 (should be at baseline 0?)

	* uni0269 (U+0269): X=193.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresistonos (U+0390): X=193.0,Y=-1.0 (should be at baseline 0?)

	* uni0394 (U+0394): X=464.0,Y=713.0 (should be at cap-height 714?)

	* Nu (U+039D): X=145.0,Y=713.0 (should be at cap-height 714?)

	* Psi (U+03A8): X=646.0,Y=715.0 (should be at cap-height 714?)

	* Psi (U+03A8): X=59.0,Y=715.0 (should be at cap-height 714?)

	* iotatonos (U+03AF): X=193.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=335.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=94.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=343.0,Y=715.0 (should be at cap-height 714?)

	* iota (U+03B9): X=193.0,Y=-1.0 (should be at baseline 0?)

	* nu (U+03BD): X=328.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresis (U+03CA): X=193.0,Y=-1.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=590.0,Y=-1.0 (should be at baseline 0?)

	* uni03D7 (U+03D7): X=517.0,Y=1.0 (should be at baseline 0?)

	* uni0402 (U+0402): X=683.5,Y=-1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=39.5,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=17.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=82.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=0.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=43.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=17.0,Y=2.0 (should be at baseline 0?)

	* uni0475 (U+0475): X=333.0,Y=1.0 (should be at baseline 0?)

	* Gemiddlehookcy (U+0494): X=474.5,Y=-1.0 (should be at baseline 0?)

	* uni04A6 (U+04A6): X=1044.5,Y=-1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=533.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=460.0,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=39.5,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=17.0,Y=2.0 (should be at baseline 0?)

	* uni04FD (U+04FD): X=375.0,Y=2.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=39.5,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=17.0,Y=2.0 (should be at baseline 0?)

	* uni051C (U+051C): X=585.0,Y=713.0 (should be at cap-height 714?)

	* uni1E44 (U+1E44): X=145.0,Y=713.0 (should be at cap-height 714?)

	* uni1E46 (U+1E46): X=145.0,Y=713.0 (should be at cap-height 714?)

	* Nmacronbelow (U+1E48): X=145.0,Y=713.0 (should be at cap-height 714?)

	* Wgrave (U+1E80): X=585.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=585.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=585.0,Y=713.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=69.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=142.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=292.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=365.0,Y=715.0 (should be at cap-height 714?)

	* uni20A6 (U+20A6): X=255.0,Y=713.0 (should be at cap-height 714?)

	* uni20A9 (U+20A9): X=615.0,Y=713.0 (should be at cap-height 714?)

	* uni2116 (U+2116): X=145.0,Y=713.0 (should be at cap-height 714?)

	* soundreccopyright (U+2117): X=337.0,Y=715.0 (should be at cap-height 714?)

	* emptyset (U+2205): X=72.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=2.0,Y=2.0 (should be at baseline 0?) 

	* uni2206 (U+2206): X=843.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<143.0,736.0>--<128.0,525.0>> -> L<<128.0,525.0>--<116.0,425.0>>

	* beta (U+03B2): L<<95.0,99.0>--<94.0,-1.0>> -> L<<94.0,-1.0>--<77.0,-217.0>>

	* d (U+0064): L<<565.0,424.0>--<568.0,525.0>> -> L<<568.0,525.0>--<582.0,736.0>>

	* dcaron (U+010F): L<<565.0,424.0>--<568.0,525.0>> -> L<<568.0,525.0>--<582.0,736.0>>

	* dcroat (U+0111): L<<565.0,425.0>--<569.0,525.0>> -> L<<569.0,525.0>--<574.0,614.0>>

	* dmacronbelow (U+1E0F): L<<565.0,424.0>--<568.0,525.0>> -> L<<568.0,525.0>--<582.0,736.0>>

	* f_f (U+FB00): L<<217.0,520.0>--<360.0,520.0>> -> L<<360.0,520.0>--<449.0,518.0>>

	* f_f_i (U+FB03): L<<217.0,520.0>--<360.0,520.0>> -> L<<360.0,520.0>--<449.0,518.0>>

	* f_t (U+FB05): L<<217.0,520.0>--<336.0,520.0>> -> L<<336.0,520.0>--<444.0,518.0>>

	* p (U+0070): L<<93.0,94.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* q (U+0071): L<<516.0,-216.0>--<531.0,-5.0>> -> L<<531.0,-5.0>--<542.0,94.0>>

	* rho (U+03C1): L<<93.0,94.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* slash (U+002F): L<<301.0,714.0>--<300.0,710.0>> -> L<<300.0,710.0>--<38.0,-130.0>>

	* tau (U+03C4): L<<143.0,518.0>--<216.0,520.0>> -> L<<216.0,520.0>--<385.0,520.0>>

	* tau (U+03C4): L<<53.0,523.0>--<143.0,518.0>> -> L<<143.0,518.0>--<216.0,520.0>>

	* thorn (U+00FE): L<<144.0,736.0>--<129.0,520.0>> -> L<<129.0,520.0>--<117.0,429.0>>

	* thorn (U+00FE): L<<93.0,94.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* trademark (U+2122): L<<453.0,714.0>--<566.0,483.0>> -> L<<566.0,483.0>--<582.0,449.0>>

	* trademark (U+2122): L<<572.0,359.0>--<459.0,612.0>> -> L<<459.0,612.0>--<446.0,640.0>>

	* trademark (U+2122): L<<741.0,359.0>--<741.0,612.0>> -> L<<741.0,612.0>--<742.0,640.0>>

	* uni0335 (U+0335): L<<130.0,285.0>--<196.0,287.0>> -> L<<196.0,287.0>--<276.0,287.0>>

	* uni0335 (U+0335): L<<49.0,290.0>--<130.0,285.0>> -> L<<130.0,285.0>--<196.0,287.0>>

	* uni03BC (U+03BC): L<<93.0,78.0>--<94.0,17.0>> -> L<<94.0,17.0>--<77.0,-217.0>>

	* uni0440 (U+0440): L<<93.0,94.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* uni0447 (U+0447): L<<457.0,0.0>--<469.0,178.0>> -> L<<469.0,178.0>--<479.0,250.0>>

	* uni0463 (U+0463): L<<215.0,568.0>--<208.0,462.0>> -> L<<208.0,462.0>--<197.0,391.0>>

	* uni048F (U+048F): L<<93.0,94.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* uni04B7 (U+04B7): L<<457.0,0.0>--<469.0,178.0>> -> L<<469.0,178.0>--<479.0,250.0>>

	* uni04B9 (U+04B9): L<<457.0,0.0>--<469.0,178.0>> -> L<<469.0,178.0>--<479.0,250.0>>

	* uni04CC (U+04CC): L<<463.0,60.0>--<471.0,182.0>> -> L<<471.0,182.0>--<481.0,250.0>>

	* uni04CD (U+04CD): L<<137.0,565.0>--<131.0,511.0>> -> L<<131.0,511.0>--<60.0,0.0>>

	* uni04CD (U+04CD): L<<425.0,101.0>--<471.0,177.0>> -> L<<471.0,177.0>--<822.0,714.0>>

	* uni04CD (U+04CD): L<<783.0,565.0>--<748.0,511.0>> -> L<<748.0,511.0>--<429.0,0.0>>

	* uni04F5 (U+04F5): L<<457.0,0.0>--<469.0,178.0>> -> L<<469.0,178.0>--<479.0,250.0>>

	* uni04FC (U+04FC): L<<428.0,356.0>--<685.0,27.0>> -> L<<685.0,27.0>--<710.0,-4.0>>

	* uni04FC (U+04FC): L<<632.0,-31.0>--<600.0,10.0>> -> L<<600.0,10.0>--<375.0,298.0>>

	* uni04FD (U+04FD): L<<287.0,260.0>--<444.0,19.0>> -> L<<444.0,19.0>--<450.0,9.0>>

	* uni04FD (U+04FD): L<<399.0,-37.0>--<375.0,2.0>> -> L<<375.0,2.0>--<243.0,204.0>>

	* uni051B (U+051B): L<<516.0,-216.0>--<531.0,-5.0>> -> L<<531.0,-5.0>--<542.0,94.0>>

	* uni1E0D (U+1E0D): L<<565.0,424.0>--<568.0,525.0>> -> L<<568.0,525.0>--<582.0,736.0>>

	* uniA78B (U+A78B): L<<140.0,731.0>--<117.0,409.0>> -> L<<117.0,409.0>--<97.0,196.0>>

	* uniA78B (U+A78B): L<<37.0,196.0>--<47.0,409.0>> -> L<<47.0,409.0>--<70.0,731.0>>

	* uniA78C (U+A78C): L<<128.0,730.0>--<113.0,520.0>> -> L<<113.0,520.0>--<100.0,409.0>> 

	* uniA78C (U+A78C): L<<52.0,409.0>--<55.0,520.0>> -> L<<55.0,520.0>--<70.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NonBureauExtended-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<213.0,497.0>>

	* d (U+0064): L<<499.0,497.0>--<494.0,549.0>> -> L<<494.0,549.0>--<494.0,736.0>>

	* dcaron (U+010F): L<<499.0,497.0>--<494.0,549.0>> -> L<<494.0,549.0>--<494.0,736.0>>

	* dcroat (U+0111): L<<499.0,487.0>--<494.0,549.0>> -> L<<494.0,549.0>--<494.0,587.0>>

	* dmacronbelow (U+1E0F): L<<499.0,497.0>--<494.0,549.0>> -> L<<494.0,549.0>--<494.0,736.0>>

	* f_f (U+FB00): L<<291.0,520.0>--<425.0,520.0>> -> L<<425.0,520.0>--<498.0,518.0>>

	* f_f_i (U+FB03): L<<291.0,520.0>--<425.0,520.0>> -> L<<425.0,520.0>--<498.0,518.0>>

	* f_t (U+FB05): L<<291.0,520.0>--<392.0,520.0>> -> L<<392.0,520.0>--<465.0,518.0>>

	* p (U+0070): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* q (U+0071): L<<494.0,-216.0>--<494.0,-29.0>> -> L<<494.0,-29.0>--<499.0,23.0>>

	* rho (U+03C1): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* tau (U+03C4): L<<10.0,523.0>--<83.0,518.0>> -> L<<83.0,518.0>--<281.0,520.0>>

	* tau (U+03C4): L<<83.0,518.0>--<281.0,520.0>> -> L<<281.0,520.0>--<425.0,520.0>>

	* thorn (U+00FE): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* uni0335 (U+0335): L<<108.0,317.0>--<296.0,319.0>> -> L<<296.0,319.0>--<384.0,319.0>>

	* uni0335 (U+0335): L<<20.0,322.0>--<108.0,317.0>> -> L<<108.0,317.0>--<296.0,319.0>>

	* uni03BC (U+03BC): L<<213.0,25.0>--<218.0,-41.0>> -> L<<218.0,-41.0>--<218.0,-217.0>>

	* uni0440 (U+0440): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* uni0447 (U+0447): L<<449.0,0.0>--<449.0,160.0>> -> L<<449.0,160.0>--<457.0,242.0>>

	* uni048F (U+048F): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* uni04B7 (U+04B7): L<<449.0,0.0>--<449.0,160.0>> -> L<<449.0,160.0>--<457.0,242.0>>

	* uni04B9 (U+04B9): L<<449.0,0.0>--<449.0,160.0>> -> L<<449.0,160.0>--<457.0,242.0>>

	* uni04F5 (U+04F5): L<<449.0,0.0>--<449.0,160.0>> -> L<<449.0,160.0>--<457.0,242.0>>

	* uni04FC (U+04FC): L<<552.0,357.0>--<709.0,159.0>> -> L<<709.0,159.0>--<734.0,128.0>>

	* uni04FC (U+04FC): L<<557.0,34.0>--<541.0,57.0>> -> L<<541.0,57.0>--<428.0,200.0>>

	* uni04FD (U+04FD): L<<384.0,1.0>--<377.0,11.0>> -> L<<377.0,11.0>--<306.0,110.0>>

	* uni04FD (U+04FD): L<<413.0,260.0>--<518.0,115.0>> -> L<<518.0,115.0>--<533.0,95.0>>

	* uni051B (U+051B): L<<494.0,-216.0>--<494.0,-29.0>> -> L<<494.0,-29.0>--<499.0,23.0>>

	* uni1E0D (U+1E0D): L<<499.0,497.0>--<494.0,549.0>> -> L<<494.0,549.0>--<494.0,736.0>>

	* uniA78B (U+A78B): L<<190.0,731.0>--<190.0,409.0>> -> L<<190.0,409.0>--<185.0,196.0>>

	* uniA78B (U+A78B): L<<25.0,196.0>--<20.0,409.0>> -> L<<20.0,409.0>--<20.0,731.0>>

	* uniA78C (U+A78C): L<<170.0,730.0>--<170.0,520.0>> -> L<<170.0,520.0>--<165.0,409.0>> 

	* uniA78C (U+A78C): L<<25.0,409.0>--<20.0,520.0>> -> L<<20.0,520.0>--<20.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<784.0,714.0>--<783.0,0.0>>

	* Hbar (U+0126): L<<320.0,637.0>--<664.0,638.0>>

	* ae (U+00E6): L<<766.0,314.0>--<1014.0,315.0>>

	* aeacute (U+01FD): L<<766.0,314.0>--<1014.0,315.0>>

	* ampersand (U+0026): L<<543.0,351.0>--<710.0,352.0>>

	* arrowleft (U+2190): L<<459.0,358.0>--<614.0,357.0>>

	* arrowleft (U+2190): L<<614.0,230.0>--<459.0,229.0>>

	* arrowright (U+2192): L<<10.0,357.0>--<165.0,358.0>>

	* arrowright (U+2192): L<<165.0,229.0>--<10.0,230.0>>

	* beta (U+03B2): L<<219.0,-1.0>--<218.0,-217.0>>

	* chi (U+03C7): L<<10.0,361.0>--<11.0,521.0>>

	* e (U+0065): L<<232.0,314.0>--<480.0,315.0>>

	* eacute (U+00E9): L<<232.0,314.0>--<480.0,315.0>>

	* ebreve (U+0115): L<<232.0,314.0>--<480.0,315.0>>

	* ecaron (U+011B): L<<232.0,314.0>--<480.0,315.0>>

	* ecircumflex (U+00EA): L<<232.0,314.0>--<480.0,315.0>>

	* edieresis (U+00EB): L<<232.0,314.0>--<480.0,315.0>>

	* edotaccent (U+0117): L<<232.0,314.0>--<480.0,315.0>>

	* egrave (U+00E8): L<<232.0,314.0>--<480.0,315.0>>

	* emacron (U+0113): L<<232.0,314.0>--<480.0,315.0>>

	* eogonek (U+0119): L<<232.0,314.0>--<480.0,315.0>>

	* franc (U+20A3): L<<301.0,203.0>--<502.0,204.0>>

	* oe (U+0153): L<<822.0,314.0>--<1070.0,315.0>>

	* psi (U+03C8): L<<298.0,134.0>--<299.0,520.0>>

	* psi (U+03C8): L<<419.0,520.0>--<418.0,134.0>>

	* sterling (U+00A3): L<<397.0,413.0>--<522.0,414.0>>

	* uni0259 (U+0259): L<<475.0,205.0>--<227.0,204.0>>

	* uni0416 (U+0416): L<<512.0,0.0>--<511.0,299.0>>

	* uni0435 (U+0435): L<<232.0,314.0>--<480.0,315.0>>

	* uni0450 (U+0450): L<<232.0,314.0>--<480.0,315.0>>

	* uni0451 (U+0451): L<<232.0,314.0>--<480.0,315.0>>

	* uni046A (U+046A): L<<396.0,0.0>--<397.0,230.0>>

	* uni046A (U+046A): L<<607.0,230.0>--<606.0,0.0>>

	* uni046B (U+046B): L<<283.0,0.0>--<284.0,168.0>>

	* uni046B (U+046B): L<<481.0,168.0>--<480.0,0.0>>

	* uni0496 (U+0496): L<<512.0,0.0>--<511.0,299.0>>

	* uni04BC (U+04BC): L<<438.0,444.0>--<792.0,445.0>>

	* uni04BE (U+04BE): L<<438.0,444.0>--<792.0,445.0>>

	* uni04C1 (U+04C1): L<<512.0,0.0>--<511.0,299.0>>

	* uni04D5 (U+04D5): L<<766.0,314.0>--<1014.0,315.0>>

	* uni04D7 (U+04D7): L<<232.0,314.0>--<480.0,315.0>>

	* uni04D9 (U+04D9): L<<475.0,205.0>--<227.0,204.0>>

	* uni04DB (U+04DB): L<<475.0,205.0>--<227.0,204.0>>

	* uni04DC (U+04DC): L<<512.0,0.0>--<511.0,299.0>>

	* uni04E9 (U+04E9): L<<234.0,324.0>--<476.0,325.0>>

	* uni04EB (U+04EB): L<<234.0,324.0>--<476.0,325.0>>

	* uni1E15 (U+1E15): L<<232.0,314.0>--<480.0,315.0>>

	* uni1E17 (U+1E17): L<<232.0,314.0>--<480.0,315.0>>

	* uni1EB9 (U+1EB9): L<<232.0,314.0>--<480.0,315.0>>

	* uni1EBD (U+1EBD): L<<232.0,314.0>--<480.0,315.0>>

	* uni20B4 (U+20B4): L<<26.0,324.0>--<761.0,326.0>>

	* uni20B4 (U+20B4): L<<52.0,448.0>--<448.0,449.0>>

	* uni20BD (U+20BD): L<<348.0,198.0>--<527.0,199.0>>

	* uni2116 (U+2116): L<<1384.0,1.0>--<895.0,0.0>>

	* uni2116 (U+2116): L<<895.0,128.0>--<1384.0,129.0>> 

	* uniAB53 (U+AB53): L<<10.0,361.0>--<11.0,521.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NonBureau-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=113.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=374.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=108.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=368.0,Y=-1.0 (should be at baseline 0?)

	* bar (U+007C): X=30.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=150.0,Y=715.0 (should be at cap-height 714?)

	* uni00B5 (U+00B5): X=546.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=364.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=572.0,Y=1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=412.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=126.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=418.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=132.0,Y=713.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=263.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=373.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=416.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=130.0,Y=713.0 (should be at cap-height 714?)

	* Eng (U+014A): X=510.0,Y=1.0 (should be at baseline 0?)

	* rcaron (U+0159): X=351.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=65.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=394.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=108.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=368.0,Y=-1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=368.0,Y=-1.0 (should be at baseline 0?)

	* tbar (U+0167): X=368.0,Y=-1.0 (should be at baseline 0?)

	* uring (U+016F): X=262.0,Y=713.0 (should be at cap-height 714?)

	* uni0186 (U+0186): X=103.5,Y=714.5 (should be at cap-height 714?)

	* uni0186 (U+0186): X=101.0,Y=-1.5 (should be at baseline 0?)

	* florin (U+0192): X=10.0,Y=-1.0 (should be at baseline 0?)

	* uni019B (U+019B): X=469.0,Y=-1.5 (should be at baseline 0?)

	* uni01CE (U+01CE): X=399.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=113.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=424.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=138.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=430.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=144.0,Y=713.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=368.0,Y=-1.0 (should be at baseline 0?)

	* uni023B (U+023B): X=449.0,Y=715.0 (should be at cap-height 714?)

	* ring (U+02DA): X=122.0,Y=713.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=122.0,Y=713.0 (should be at cap-height 714?)

	* alphatonos (U+03AC): X=606.0,Y=-1.0 (should be at baseline 0?)

	* alpha (U+03B1): X=606.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=303.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=154.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=251.0,Y=712.5 (should be at cap-height 714?)

	* lambda (U+03BB): X=469.0,Y=-1.5 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=343.5,Y=-1.0 (should be at baseline 0?)

	* uni0402 (U+0402): X=744.0,Y=1.5 (should be at baseline 0?)

	* uni0409 (U+0409): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=5.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=152.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=15.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=5.0,Y=2.0 (should be at baseline 0?)

	* uni048F (U+048F): X=381.0,Y=2.0 (should be at baseline 0?)

	* Gemiddlehookcy (U+0494): X=549.0,Y=1.5 (should be at baseline 0?)

	* uni04A6 (U+04A6): X=1028.0,Y=1.5 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=515.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=393.0,Y=1.0 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=5.0,Y=2.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=165.0,Y=1.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=21.0,Y=1.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=50.5,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=33.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=5.0,Y=2.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=368.0,Y=-1.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=368.0,Y=-1.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=30.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=150.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=300.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=420.0,Y=715.0 (should be at cap-height 714?)

	* lira (U+20A4): X=322.0,Y=714.5 (should be at cap-height 714?)

	* uni20BF (U+20BF): X=376.0,Y=712.0 (should be at cap-height 714?)

	* uni20BF (U+20BF): X=376.0,Y=1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=69.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=808.0,Y=2.0 (should be at baseline 0?)

	* integral (U+222B): X=83.0,Y=1.0 (should be at baseline 0?)

	* circle (U+25CB): X=390.0,Y=2.0 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=368.0,Y=-1.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=677.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<153.0,736.0>--<153.0,535.0>> -> L<<153.0,535.0>--<148.0,462.0>>

	* beta (U+03B2): L<<149.0,57.0>--<154.0,-1.0>> -> L<<154.0,-1.0>--<153.0,-217.0>>

	* d (U+0064): L<<410.0,462.0>--<405.0,535.0>> -> L<<405.0,535.0>--<405.0,736.0>>

	* dcaron (U+010F): L<<410.0,462.0>--<405.0,535.0>> -> L<<405.0,535.0>--<405.0,736.0>>

	* dcroat (U+0111): L<<407.0,452.0>--<405.0,520.0>> -> L<<405.0,520.0>--<405.0,603.0>>

	* dmacronbelow (U+1E0F): L<<410.0,462.0>--<405.0,535.0>> -> L<<405.0,535.0>--<405.0,736.0>>

	* f_f (U+FB00): L<<236.0,520.0>--<350.0,520.0>> -> L<<350.0,520.0>--<418.0,518.0>>

	* f_f_i (U+FB03): L<<236.0,520.0>--<330.0,520.0>> -> L<<330.0,520.0>--<398.0,518.0>>

	* f_t (U+FB05): L<<236.0,520.0>--<339.0,520.0>> -> L<<339.0,520.0>--<417.0,518.0>>

	* hbar (U+0127): L<<240.0,603.0>--<240.0,535.0>> -> L<<240.0,535.0>--<232.0,452.0>>

	* p (U+0070): L<<148.0,58.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* q (U+0071): L<<405.0,-216.0>--<405.0,-14.0>> -> L<<405.0,-14.0>--<410.0,58.0>>

	* raisedmcsign (U+1F16A): L<<340.0,584.0>--<276.0,437.0>> -> L<<276.0,437.0>--<233.0,359.0>>

	* raisedmdsign (U+1F16B): L<<340.0,584.0>--<276.0,437.0>> -> L<<276.0,437.0>--<233.0,359.0>>

	* raisedmrsign (U+1F16C): L<<340.0,584.0>--<276.0,437.0>> -> L<<276.0,437.0>--<233.0,359.0>>

	* rho (U+03C1): L<<148.0,58.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* tau (U+03C4): L<<108.0,518.0>--<231.0,520.0>> -> L<<231.0,520.0>--<350.0,520.0>>

	* tau (U+03C4): L<<25.0,523.0>--<108.0,518.0>> -> L<<108.0,518.0>--<231.0,520.0>>

	* thorn (U+00FE): L<<148.0,58.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* uni0335 (U+0335): L<<114.0,298.0>--<229.0,300.0>> -> L<<229.0,300.0>--<312.0,300.0>>

	* uni0335 (U+0335): L<<30.0,303.0>--<114.0,298.0>> -> L<<114.0,298.0>--<229.0,300.0>>

	* uni03BC (U+03BC): L<<148.0,50.0>--<153.0,-6.0>> -> L<<153.0,-6.0>--<153.0,-217.0>>

	* uni0440 (U+0440): L<<148.0,58.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* uni0447 (U+0447): L<<334.0,0.0>--<334.0,171.0>> -> L<<334.0,171.0>--<341.0,247.0>>

	* uni0463 (U+0463): L<<219.0,541.0>--<219.0,470.0>> -> L<<219.0,470.0>--<214.0,410.0>>

	* uni048F (U+048F): L<<148.0,58.0>--<153.0,-14.0>> -> L<<153.0,-14.0>--<153.0,-216.0>>

	* uni04B7 (U+04B7): L<<334.0,0.0>--<334.0,171.0>> -> L<<334.0,171.0>--<341.0,247.0>>

	* uni04B9 (U+04B9): L<<354.0,0.0>--<354.0,171.0>> -> L<<354.0,171.0>--<361.0,247.0>>

	* uni04F5 (U+04F5): L<<334.0,0.0>--<334.0,171.0>> -> L<<334.0,171.0>--<341.0,247.0>>

	* uni04FC (U+04FC): L<<419.0,358.0>--<619.0,80.0>> -> L<<619.0,80.0>--<640.0,49.0>>

	* uni04FC (U+04FC): L<<533.0,-5.0>--<509.0,30.0>> -> L<<509.0,30.0>--<347.0,256.0>>

	* uni04FD (U+04FD): L<<338.0,260.0>--<484.0,58.0>> -> L<<484.0,58.0>--<494.0,44.0>>

	* uni04FD (U+04FD): L<<405.0,-22.0>--<386.0,6.0>> -> L<<386.0,6.0>--<271.0,166.0>>

	* uni051B (U+051B): L<<405.0,-216.0>--<405.0,-14.0>> -> L<<405.0,-14.0>--<410.0,58.0>>

	* uni1E0D (U+1E0D): L<<410.0,462.0>--<405.0,535.0>> -> L<<405.0,535.0>--<405.0,736.0>>

	* uniA78B (U+A78B): L<<140.0,731.0>--<140.0,409.0>> -> L<<140.0,409.0>--<135.0,196.0>>

	* uniA78B (U+A78B): L<<35.0,196.0>--<30.0,409.0>> -> L<<30.0,409.0>--<30.0,731.0>>

	* uniA78C (U+A78C): L<<125.0,730.0>--<125.0,520.0>> -> L<<125.0,520.0>--<120.0,409.0>> 

	* uniA78C (U+A78C): L<<35.0,409.0>--<30.0,520.0>> -> L<<30.0,520.0>--<30.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<235.0,618.0>--<599.0,620.0>>

	* arrowleft (U+2190): L<<449.0,250.0>--<450.0,31.0>>

	* arrowleft (U+2190): L<<449.0,339.0>--<624.0,338.0>>

	* arrowleft (U+2190): L<<450.0,558.0>--<449.0,339.0>>

	* arrowleft (U+2190): L<<624.0,251.0>--<449.0,250.0>>

	* arrowright (U+2192): L<<15.0,338.0>--<190.0,339.0>>

	* arrowright (U+2192): L<<190.0,250.0>--<15.0,251.0>>

	* beta (U+03B2): L<<154.0,-1.0>--<153.0,-217.0>>

	* estimated (U+212E): L<<499.0,354.0>--<498.0,474.0>>

	* oe (U+0153): L<<958.0,235.0>--<584.0,234.0>>

	* psi (U+03C8): L<<246.0,84.0>--<247.0,520.0>>

	* psi (U+03C8): L<<331.0,520.0>--<330.0,84.0>>

	* raisedmcsign (U+1F16A): L<<96.0,584.0>--<95.0,437.0>>

	* raisedmdsign (U+1F16B): L<<96.0,584.0>--<95.0,437.0>>

	* raisedmrsign (U+1F16C): L<<96.0,584.0>--<95.0,437.0>>

	* sterling (U+00A3): L<<269.0,420.0>--<415.0,421.0>>

	* uni046A (U+046A): L<<356.0,0.0>--<357.0,300.0>>

	* uni046A (U+046A): L<<487.0,300.0>--<486.0,0.0>>

	* uni046B (U+046B): L<<260.0,0.0>--<261.0,212.0>>

	* uni04D8 (U+04D8): L<<551.0,287.0>--<161.0,286.0>>

	* uni04DA (U+04DA): L<<551.0,287.0>--<161.0,286.0>>

	* uni04E9 (U+04E9): L<<155.0,311.0>--<409.0,312.0>>

	* uni04EB (U+04EB): L<<155.0,311.0>--<409.0,312.0>>

	* uni20B4 (U+20B4): L<<26.0,315.0>--<723.0,316.0>> 

	* uni20B4 (U+20B4): L<<51.0,455.0>--<468.0,456.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NonBureau-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=120.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=356.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=116.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=356.0,Y=-2.0 (should be at baseline 0?)

	* bar (U+007C): X=33.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=130.0,Y=715.0 (should be at cap-height 714?)

	* section (U+00A7): X=141.0,Y=-2.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=357.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=560.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=269.0,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=433.0,Y=715.0 (should be at cap-height 714?)

	* eth (U+00F0): X=204.0,Y=714.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=392.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=129.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=397.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=134.0,Y=713.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=260.0,Y=716.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=289.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=241.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=335.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=393.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=130.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=329.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=66.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=374.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=111.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=356.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=356.0,Y=-2.0 (should be at baseline 0?)

	* tbar (U+0167): X=356.0,Y=-2.0 (should be at baseline 0?)

	* uni0186 (U+0186): X=109.0,Y=713.0 (should be at cap-height 714?)

	* uni0186 (U+0186): X=105.5,Y=0.5 (should be at baseline 0?)

	* florin (U+0192): X=10.0,Y=-2.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=379.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=116.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=406.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=143.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=406.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=406.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=143.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=143.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=217.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=333.0,Y=716.0 (should be at cap-height 714?)

	* Oslashacute (U+01FE): X=269.0,Y=-2.0 (should be at baseline 0?)

	* Oslashacute (U+01FE): X=433.0,Y=715.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=356.0,Y=-2.0 (should be at baseline 0?)

	* uni023B (U+023B): X=438.0,Y=715.0 (should be at cap-height 714?)

	* uni0269 (U+0269): X=233.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresistonos (U+0390): X=233.0,Y=-1.0 (should be at baseline 0?)

	* alphatonos (U+03AC): X=591.0,Y=-2.0 (should be at baseline 0?)

	* iotatonos (U+03AF): X=233.0,Y=-1.0 (should be at baseline 0?)

	* alpha (U+03B1): X=591.0,Y=-2.0 (should be at baseline 0?)

	* beta (U+03B2): X=293.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=132.0,Y=-1.0 (should be at baseline 0?)

	* iota (U+03B9): X=233.0,Y=-1.0 (should be at baseline 0?)

	* lambda (U+03BB): X=168.5,Y=715.5 (should be at cap-height 714?)

	* uni03C2 (U+03C2): X=188.5,Y=0.5 (should be at baseline 0?)

	* tau (U+03C4): X=316.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresis (U+03CA): X=233.0,Y=-1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=7.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=125.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=17.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=7.0,Y=2.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=489.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=391.0,Y=1.0 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=7.0,Y=2.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=136.0,Y=1.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=21.0,Y=1.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=7.0,Y=2.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=356.0,Y=-2.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=356.0,Y=-2.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=33.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=130.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=280.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=377.0,Y=715.0 (should be at cap-height 714?)

	* colonmonetary (U+20A1): X=256.0,Y=-2.0 (should be at baseline 0?)

	* uni20BF (U+20BF): X=362.0,Y=713.0 (should be at cap-height 714?)

	* uni20BF (U+20BF): X=362.0,Y=1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=65.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=785.0,Y=2.0 (should be at baseline 0?)

	* radical (U+221A): X=226.0,Y=-2.0 (should be at baseline 0?)

	* circle (U+25CB): X=244.5,Y=-1.5 (should be at baseline 0?)

	* circle (U+25CB): X=524.5,Y=-1.5 (should be at baseline 0?)

	* uni25CC (U+25CC): X=529.0,Y=2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=236.0,Y=1.0 (should be at baseline 0?)

	* uni25CF (U+25CF): X=244.5,Y=-1.5 (should be at baseline 0?)

	* uni25CF (U+25CF): X=524.5,Y=-1.5 (should be at baseline 0?)

	* uni2C65 (U+2C65): X=128.0,Y=-1.0 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=356.0,Y=-2.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=650.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<131.0,736.0>--<131.0,530.0>> -> L<<131.0,530.0>--<126.0,450.0>>

	* beta (U+03B2): L<<127.0,69.0>--<132.0,-1.0>> -> L<<132.0,-1.0>--<131.0,-217.0>>

	* d (U+0064): L<<415.0,450.0>--<410.0,530.0>> -> L<<410.0,530.0>--<410.0,736.0>>

	* dcaron (U+010F): L<<415.0,450.0>--<410.0,530.0>> -> L<<410.0,530.0>--<410.0,736.0>>

	* dcroat (U+0111): L<<412.0,444.0>--<410.0,520.0>> -> L<<410.0,520.0>--<410.0,608.0>>

	* dmacronbelow (U+1E0F): L<<415.0,450.0>--<410.0,530.0>> -> L<<410.0,530.0>--<410.0,736.0>>

	* f_f (U+FB00): L<<218.0,520.0>--<335.0,520.0>> -> L<<335.0,520.0>--<411.0,518.0>>

	* f_f_i (U+FB03): L<<218.0,520.0>--<308.0,520.0>> -> L<<308.0,520.0>--<385.0,518.0>>

	* f_t (U+FB05): L<<218.0,520.0>--<331.0,520.0>> -> L<<331.0,520.0>--<410.0,518.0>>

	* p (U+0070): L<<126.0,70.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* q (U+0071): L<<410.0,-216.0>--<410.0,-10.0>> -> L<<410.0,-10.0>--<415.0,70.0>>

	* rho (U+03C1): L<<126.0,70.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* tau (U+03C4): L<<116.0,518.0>--<214.0,520.0>> -> L<<214.0,520.0>--<338.0,520.0>>

	* tau (U+03C4): L<<30.0,523.0>--<116.0,518.0>> -> L<<116.0,518.0>--<214.0,520.0>>

	* thorn (U+00FE): L<<126.0,70.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* uni018F (U+018F): L<<24.0,347.0>--<378.0,373.0>> -> L<<378.0,373.0>--<544.0,379.0>>

	* uni0335 (U+0335): L<<115.0,291.0>--<206.0,293.0>> -> L<<206.0,293.0>--<288.0,293.0>>

	* uni0335 (U+0335): L<<33.0,296.0>--<115.0,291.0>> -> L<<115.0,291.0>--<206.0,293.0>>

	* uni03BC (U+03BC): L<<126.0,59.0>--<131.0,5.0>> -> L<<131.0,5.0>--<131.0,-217.0>>

	* uni0440 (U+0440): L<<126.0,70.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* uni0447 (U+0447): L<<336.0,0.0>--<336.0,174.0>> -> L<<336.0,174.0>--<342.0,249.0>>

	* uni0463 (U+0463): L<<206.0,555.0>--<206.0,466.0>> -> L<<206.0,466.0>--<201.0,400.0>>

	* uni048F (U+048F): L<<126.0,70.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* uni04B7 (U+04B7): L<<336.0,0.0>--<336.0,174.0>> -> L<<336.0,174.0>--<342.0,249.0>>

	* uni04B9 (U+04B9): L<<349.0,0.0>--<349.0,174.0>> -> L<<349.0,174.0>--<355.0,249.0>>

	* uni04CC (U+04CC): L<<339.0,78.0>--<339.0,181.0>> -> L<<339.0,181.0>--<345.0,249.0>>

	* uni04F5 (U+04F5): L<<336.0,0.0>--<336.0,174.0>> -> L<<336.0,174.0>--<342.0,249.0>>

	* uni04FC (U+04FC): L<<391.0,358.0>--<610.0,53.0>> -> L<<610.0,53.0>--<632.0,23.0>>

	* uni04FC (U+04FC): L<<544.0,-19.0>--<518.0,20.0>> -> L<<518.0,20.0>--<334.0,276.0>>

	* uni04FD (U+04FD): L<<313.0,260.0>--<473.0,38.0>> -> L<<473.0,38.0>--<481.0,27.0>>

	* uni04FD (U+04FD): L<<412.0,-30.0>--<389.0,4.0>> -> L<<389.0,4.0>--<259.0,185.0>>

	* uni051B (U+051B): L<<410.0,-216.0>--<410.0,-10.0>> -> L<<410.0,-10.0>--<415.0,70.0>>

	* uni1E0D (U+1E0D): L<<415.0,450.0>--<410.0,530.0>> -> L<<410.0,530.0>--<410.0,736.0>>

	* uniA78B (U+A78B): L<<123.0,731.0>--<123.0,409.0>> -> L<<123.0,409.0>--<118.0,196.0>>

	* uniA78B (U+A78B): L<<38.0,196.0>--<33.0,409.0>> -> L<<33.0,409.0>--<33.0,731.0>>

	* uniA78C (U+A78C): L<<110.0,730.0>--<110.0,520.0>> -> L<<110.0,520.0>--<105.0,409.0>> 

	* uniA78C (U+A78C): L<<38.0,409.0>--<33.0,520.0>> -> L<<33.0,520.0>--<33.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<220.0,612.0>--<604.0,614.0>>

	* beta (U+03B2): L<<132.0,-1.0>--<131.0,-217.0>>

	* estimated (U+212E): L<<511.0,351.0>--<510.0,486.0>>

	* sterling (U+00A3): L<<242.0,422.0>--<396.0,423.0>>

	* uni046A (U+046A): L<<343.0,0.0>--<344.0,323.0>>

	* uni046A (U+046A): L<<447.0,323.0>--<446.0,0.0>>

	* uni046B (U+046B): L<<252.0,0.0>--<253.0,227.0>>

	* uni20B4 (U+20B4): L<<26.0,311.0>--<717.0,312.0>>

	* uni20B4 (U+20B4): L<<51.0,457.0>--<481.0,458.0>> 

	* uni20BD (U+20BD): L<<239.0,197.0>--<410.0,198.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NonBureauExtended-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: ij	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=546.0,Y=1.0 (should be at baseline 0?)

	* f (U+0066): X=106.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=432.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=100.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=420.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=243.0,Y=1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=302.0,Y=1.0 (should be at baseline 0?)

	* bar (U+007C): X=27.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=170.0,Y=715.0 (should be at cap-height 714?)

	* braceright (U+007D): X=23.0,Y=1.0 (should be at baseline 0?)

	* braceright (U+007D): X=82.0,Y=1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=344.0,Y=713.5 (should be at cap-height 714?)

	* section (U+00A7): X=248.0,Y=2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=166.0,Y=713.0 (should be at cap-height 714?)

	* uni00B5 (U+00B5): X=225.5,Y=0.5 (should be at baseline 0?)

	* ordmasculine (U+00BA): X=185.0,Y=713.0 (should be at cap-height 714?)

	* ordmasculine (U+00BA): X=185.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=495.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=186.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=498.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=189.0,Y=713.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=285.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=410.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=469.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=160.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=378.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=69.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=460.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=151.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=420.0,Y=-1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=420.0,Y=-1.0 (should be at baseline 0?)

	* tbar (U+0167): X=420.0,Y=-1.0 (should be at baseline 0?)

	* florin (U+0192): X=319.5,Y=715.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=472.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=163.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=499.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=190.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=518.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=209.0,Y=713.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=420.0,Y=-1.0 (should be at baseline 0?)

	* uni023C (U+023C): X=225.0,Y=1.0 (should be at baseline 0?)

	* dieresistonos (U+0385): X=253.0,Y=713.0 (should be at cap-height 714?)

	* dieresistonos (U+0385): X=401.0,Y=713.0 (should be at cap-height 714?)

	* iotadieresistonos (U+0390): X=74.0,Y=713.0 (should be at cap-height 714?)

	* iotadieresistonos (U+0390): X=222.0,Y=713.0 (should be at cap-height 714?)

	* alphatonos (U+03AC): X=735.0,Y=-1.0 (should be at baseline 0?)

	* upsilondieresistonos (U+03B0): X=294.0,Y=713.0 (should be at cap-height 714?)

	* upsilondieresistonos (U+03B0): X=442.0,Y=713.0 (should be at cap-height 714?)

	* alpha (U+03B1): X=735.0,Y=-1.0 (should be at baseline 0?)

	* beta (U+03B2): X=339.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=340.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=176.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=284.0,Y=713.0 (should be at cap-height 714?)

	* lambda (U+03BB): X=231.5,Y=716.0 (should be at cap-height 714?)

	* lambda (U+03BB): X=550.0,Y=-1.5 (should be at baseline 0?)

	* uni03C2 (U+03C2): X=361.5,Y=1.5 (should be at baseline 0?)

	* tau (U+03C4): X=420.0,Y=-1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=3.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=179.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=13.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=3.0,Y=2.0 (should be at baseline 0?)

	* uni048F (U+048F): X=480.0,Y=2.0 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=3.0,Y=2.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=49.0,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=34.5,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=3.0,Y=2.0 (should be at baseline 0?)

	* uni051A (U+051A): X=546.0,Y=1.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=420.0,Y=-1.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=420.0,Y=-1.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=27.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=170.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=320.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=463.0,Y=715.0 (should be at cap-height 714?)

	* uni2116 (U+2116): X=1336.0,Y=1.0 (should be at baseline 0?)

	* emptyset (U+2205): X=107.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=931.0,Y=2.0 (should be at baseline 0?)

	* summation (U+2211): X=181.0,Y=-2.0 (should be at baseline 0?)

	* summation (U+2211): X=590.0,Y=-2.0 (should be at baseline 0?)

	* summation (U+2211): X=27.0,Y=-2.0 (should be at baseline 0?)

	* circle (U+25CB): X=215.5,Y=1.0 (should be at baseline 0?)

	* circle (U+25CB): X=654.0,Y=1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=656.0,Y=-1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=413.0,Y=-1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=426.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=439.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=452.5,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=466.0,Y=-1.0 (should be at baseline 0?)

	* uni25CF (U+25CF): X=215.5,Y=1.0 (should be at baseline 0?)

	* uni25CF (U+25CF): X=654.0,Y=1.0 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=420.0,Y=-1.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=730.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<175.0,736.0>--<175.0,539.0>> -> L<<175.0,539.0>--<170.0,469.0>>

	* beta (U+03B2): L<<171.0,59.0>--<176.0,-1.0>> -> L<<176.0,-1.0>--<175.0,-217.0>>

	* d (U+0064): L<<521.0,469.0>--<516.0,539.0>> -> L<<516.0,539.0>--<516.0,736.0>>

	* dcaron (U+010F): L<<521.0,469.0>--<516.0,539.0>> -> L<<516.0,539.0>--<516.0,736.0>>

	* dcroat (U+0111): L<<521.0,462.0>--<516.0,539.0>> -> L<<516.0,539.0>--<516.0,598.0>>

	* dmacronbelow (U+1E0F): L<<521.0,469.0>--<516.0,539.0>> -> L<<516.0,539.0>--<516.0,736.0>>

	* f_f (U+FB00): L<<254.0,520.0>--<392.0,520.0>> -> L<<392.0,520.0>--<471.0,518.0>>

	* f_f_i (U+FB03): L<<254.0,520.0>--<392.0,520.0>> -> L<<392.0,520.0>--<471.0,518.0>>

	* f_t (U+FB05): L<<254.0,520.0>--<365.0,520.0>> -> L<<365.0,520.0>--<449.0,518.0>>

	* p (U+0070): L<<170.0,51.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* q (U+0071): L<<516.0,-216.0>--<516.0,-19.0>> -> L<<516.0,-19.0>--<521.0,51.0>>

	* raisedmcsign (U+1F16A): L<<369.0,570.0>--<321.0,469.0>> -> L<<321.0,469.0>--<261.0,359.0>>

	* raisedmdsign (U+1F16B): L<<369.0,570.0>--<321.0,469.0>> -> L<<321.0,469.0>--<261.0,359.0>>

	* rho (U+03C1): L<<170.0,51.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* tau (U+03C4): L<<100.0,518.0>--<248.0,520.0>> -> L<<248.0,520.0>--<402.0,520.0>>

	* tau (U+03C4): L<<20.0,523.0>--<100.0,518.0>> -> L<<100.0,518.0>--<248.0,520.0>>

	* thorn (U+00FE): L<<170.0,51.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* trademark (U+2122): L<<727.0,570.0>--<679.0,469.0>> -> L<<679.0,469.0>--<619.0,359.0>>

	* uni0335 (U+0335): L<<112.0,304.0>--<251.0,306.0>> -> L<<251.0,306.0>--<336.0,306.0>>

	* uni0335 (U+0335): L<<27.0,309.0>--<112.0,304.0>> -> L<<112.0,304.0>--<251.0,306.0>>

	* uni03BC (U+03BC): L<<170.0,46.0>--<175.0,-18.0>> -> L<<175.0,-18.0>--<175.0,-217.0>>

	* uni0440 (U+0440): L<<170.0,51.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* uni0447 (U+0447): L<<459.0,0.0>--<459.0,167.0>> -> L<<459.0,167.0>--<466.0,245.0>>

	* uni048F (U+048F): L<<170.0,51.0>--<175.0,-19.0>> -> L<<175.0,-19.0>--<175.0,-216.0>>

	* uni04B7 (U+04B7): L<<459.0,0.0>--<459.0,167.0>> -> L<<459.0,167.0>--<466.0,245.0>>

	* uni04B9 (U+04B9): L<<459.0,0.0>--<459.0,167.0>> -> L<<459.0,167.0>--<466.0,245.0>>

	* uni04CD (U+04CD): L<<171.0,714.0>--<348.0,411.0>> -> L<<348.0,411.0>--<460.0,196.0>>

	* uni04CD (U+04CD): L<<425.0,0.0>--<290.0,215.0>> -> L<<290.0,215.0>--<184.0,420.0>>

	* uni04CD (U+04CD): L<<747.0,0.0>--<735.0,215.0>> -> L<<735.0,215.0>--<734.0,420.0>>

	* uni04F5 (U+04F5): L<<459.0,0.0>--<459.0,167.0>> -> L<<459.0,167.0>--<466.0,245.0>>

	* uni04FC (U+04FC): L<<500.0,357.0>--<706.0,106.0>> -> L<<706.0,106.0>--<732.0,75.0>>

	* uni04FC (U+04FC): L<<594.0,7.0>--<571.0,38.0>> -> L<<571.0,38.0>--<405.0,239.0>>

	* uni04FD (U+04FD): L<<363.0,260.0>--<495.0,77.0>> -> L<<495.0,77.0>--<507.0,61.0>>

	* uni04FD (U+04FD): L<<398.0,-15.0>--<383.0,7.0>> -> L<<383.0,7.0>--<282.0,147.0>>

	* uni051B (U+051B): L<<516.0,-216.0>--<516.0,-19.0>> -> L<<516.0,-19.0>--<521.0,51.0>>

	* uni1E0D (U+1E0D): L<<521.0,469.0>--<516.0,539.0>> -> L<<516.0,539.0>--<516.0,736.0>>

	* uniA78B (U+A78B): L<<157.0,731.0>--<157.0,409.0>> -> L<<157.0,409.0>--<152.0,196.0>>

	* uniA78B (U+A78B): L<<32.0,196.0>--<27.0,409.0>> -> L<<27.0,409.0>--<27.0,731.0>>

	* uniA78C (U+A78C): L<<140.0,730.0>--<140.0,520.0>> -> L<<140.0,520.0>--<135.0,409.0>> 

	* uniA78C (U+A78C): L<<32.0,409.0>--<27.0,520.0>> -> L<<27.0,520.0>--<27.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<744.0,714.0>--<743.0,-3.0>>

	* Hbar (U+0126): L<<277.0,625.0>--<681.0,626.0>>

	* ampersand (U+0026): L<<571.0,346.0>--<699.0,347.0>>

	* arrowleft (U+2190): L<<452.0,243.0>--<453.0,20.0>>

	* arrowleft (U+2190): L<<452.0,345.0>--<621.0,344.0>>

	* arrowleft (U+2190): L<<453.0,568.0>--<452.0,345.0>>

	* arrowleft (U+2190): L<<621.0,244.0>--<452.0,243.0>>

	* arrowright (U+2192): L<<13.0,344.0>--<182.0,345.0>>

	* arrowright (U+2192): L<<181.0,20.0>--<182.0,243.0>>

	* arrowright (U+2192): L<<182.0,243.0>--<13.0,244.0>>

	* arrowright (U+2192): L<<182.0,345.0>--<181.0,568.0>>

	* beta (U+03B2): L<<176.0,-1.0>--<175.0,-217.0>>

	* chi (U+03C7): L<<13.0,399.0>--<14.0,522.0>>

	* franc (U+20A3): L<<254.0,203.0>--<485.0,204.0>>

	* psi (U+03C8): L<<283.0,99.0>--<284.0,520.0>>

	* psi (U+03C8): L<<380.0,520.0>--<379.0,99.0>>

	* uni046A (U+046A): L<<369.0,0.0>--<370.0,277.0>>

	* uni046A (U+046A): L<<527.0,277.0>--<526.0,0.0>>

	* uni046B (U+046B): L<<268.0,0.0>--<269.0,197.0>>

	* uni046B (U+046B): L<<416.0,197.0>--<415.0,0.0>>

	* uni04BC (U+04BC): L<<365.0,432.0>--<811.0,433.0>>

	* uni04BE (U+04BE): L<<365.0,432.0>--<811.0,433.0>>

	* uni04CD (U+04CD): L<<184.0,420.0>--<183.0,204.0>>

	* uni04CD (U+04CD): L<<735.0,215.0>--<734.0,420.0>>

	* uni04E9 (U+04E9): L<<183.0,315.0>--<505.0,316.0>>

	* uni04EB (U+04EB): L<<183.0,315.0>--<505.0,316.0>>

	* uni20B4 (U+20B4): L<<26.0,318.0>--<769.0,319.0>>

	* uni2116 (U+2116): L<<1336.0,1.0>--<848.0,0.0>>

	* uni2116 (U+2116): L<<848.0,99.0>--<1336.0,100.0>> 

	* uniAB53 (U+AB53): L<<13.0,399.0>--<14.0,522.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NonBureauExtended-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=120.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=396.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=116.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=396.0,Y=-2.0 (should be at baseline 0?)

	* bar (U+007C): X=33.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=130.0,Y=715.0 (should be at cap-height 714?)

	* sterling (U+00A3): X=333.0,Y=714.5 (should be at cap-height 714?)

	* onehalf (U+00BD): X=347.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=587.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=141.0,Y=713.0 (should be at cap-height 714?)

	* eth (U+00F0): X=317.5,Y=714.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=460.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=197.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=461.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=198.0,Y=713.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=330.0,Y=716.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=359.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=241.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=335.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=443.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=180.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=339.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=76.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=422.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=159.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=396.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=396.0,Y=-2.0 (should be at baseline 0?)

	* tbar (U+0167): X=396.0,Y=-2.0 (should be at baseline 0?)

	* uni0186 (U+0186): X=123.0,Y=713.0 (should be at cap-height 714?)

	* uni0186 (U+0186): X=117.5,Y=0.5 (should be at baseline 0?)

	* florin (U+0192): X=10.0,Y=-2.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=428.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=165.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=465.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=202.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=476.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=476.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=213.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=213.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=287.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=403.0,Y=716.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=396.0,Y=-2.0 (should be at baseline 0?)

	* uni0269 (U+0269): X=233.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresistonos (U+0390): X=233.0,Y=-1.0 (should be at baseline 0?)

	* alphatonos (U+03AC): X=718.0,Y=-2.0 (should be at baseline 0?)

	* iotatonos (U+03AF): X=233.0,Y=-1.0 (should be at baseline 0?)

	* alpha (U+03B1): X=718.0,Y=-2.0 (should be at baseline 0?)

	* beta (U+03B2): X=316.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=316.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=132.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=289.0,Y=713.5 (should be at cap-height 714?)

	* iota (U+03B9): X=233.0,Y=-1.0 (should be at baseline 0?)

	* lambda (U+03BB): X=195.0,Y=715.0 (should be at cap-height 714?)

	* uni03C2 (U+03C2): X=188.5,Y=0.5 (should be at baseline 0?)

	* tau (U+03C4): X=396.0,Y=-2.0 (should be at baseline 0?)

	* iotadieresis (U+03CA): X=233.0,Y=-1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=7.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=125.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=17.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=7.0,Y=2.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=573.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=476.0,Y=1.0 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=7.0,Y=2.0 (should be at baseline 0?)

	* uni04CD (U+04CD): X=916.0,Y=-1.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=51.5,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=32.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=7.0,Y=2.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=396.0,Y=-2.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=396.0,Y=-2.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=33.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=130.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=280.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=377.0,Y=715.0 (should be at cap-height 714?)

	* colonmonetary (U+20A1): X=309.0,Y=-2.0 (should be at baseline 0?)

	* emptyset (U+2205): X=94.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=885.0,Y=2.0 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=396.0,Y=-2.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=673.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<131.0,736.0>--<131.0,530.0>> -> L<<131.0,530.0>--<126.0,440.0>>

	* beta (U+03B2): L<<127.0,85.0>--<132.0,-1.0>> -> L<<132.0,-1.0>--<131.0,-217.0>>

	* d (U+0064): L<<543.0,440.0>--<538.0,530.0>> -> L<<538.0,530.0>--<538.0,736.0>>

	* dcaron (U+010F): L<<543.0,440.0>--<538.0,530.0>> -> L<<538.0,530.0>--<538.0,736.0>>

	* dcroat (U+0111): L<<543.0,437.0>--<538.0,530.0>> -> L<<538.0,530.0>--<538.0,608.0>>

	* dmacronbelow (U+1E0F): L<<543.0,440.0>--<538.0,530.0>> -> L<<538.0,530.0>--<538.0,736.0>>

	* f_f (U+FB00): L<<218.0,520.0>--<358.0,520.0>> -> L<<358.0,520.0>--<445.0,518.0>>

	* f_f_i (U+FB03): L<<218.0,520.0>--<358.0,520.0>> -> L<<358.0,520.0>--<445.0,518.0>>

	* f_t (U+FB05): L<<218.0,520.0>--<337.0,520.0>> -> L<<337.0,520.0>--<434.0,518.0>>

	* p (U+0070): L<<126.0,80.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* q (U+0071): L<<538.0,-216.0>--<538.0,-10.0>> -> L<<538.0,-10.0>--<543.0,80.0>>

	* raisedmcsign (U+1F16A): L<<234.0,359.0>--<112.0,562.0>> -> L<<112.0,562.0>--<85.0,617.0>>

	* raisedmdsign (U+1F16B): L<<234.0,359.0>--<112.0,562.0>> -> L<<112.0,562.0>--<85.0,617.0>>

	* rho (U+03C1): L<<126.0,80.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* tau (U+03C4): L<<116.0,518.0>--<214.0,520.0>> -> L<<214.0,520.0>--<378.0,520.0>>

	* tau (U+03C4): L<<30.0,523.0>--<116.0,518.0>> -> L<<116.0,518.0>--<214.0,520.0>>

	* thorn (U+00FE): L<<126.0,80.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* trademark (U+2122): L<<583.0,359.0>--<461.0,562.0>> -> L<<461.0,562.0>--<434.0,617.0>>

	* uni0335 (U+0335): L<<115.0,291.0>--<206.0,293.0>> -> L<<206.0,293.0>--<288.0,293.0>>

	* uni0335 (U+0335): L<<33.0,296.0>--<115.0,291.0>> -> L<<115.0,291.0>--<206.0,293.0>>

	* uni03BC (U+03BC): L<<126.0,67.0>--<131.0,5.0>> -> L<<131.0,5.0>--<131.0,-217.0>>

	* uni0440 (U+0440): L<<126.0,80.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* uni0447 (U+0447): L<<469.0,0.0>--<469.0,174.0>> -> L<<469.0,174.0>--<475.0,249.0>>

	* uni0463 (U+0463): L<<206.0,555.0>--<206.0,462.0>> -> L<<206.0,462.0>--<201.0,400.0>>

	* uni048F (U+048F): L<<126.0,80.0>--<131.0,-10.0>> -> L<<131.0,-10.0>--<131.0,-216.0>>

	* uni04B7 (U+04B7): L<<469.0,0.0>--<469.0,174.0>> -> L<<469.0,174.0>--<475.0,249.0>>

	* uni04B9 (U+04B9): L<<469.0,0.0>--<469.0,174.0>> -> L<<469.0,174.0>--<475.0,249.0>>

	* uni04CC (U+04CC): L<<472.0,78.0>--<472.0,184.0>> -> L<<472.0,184.0>--<478.0,249.0>>

	* uni04CD (U+04CD): L<<752.0,516.0>--<691.0,409.0>> -> L<<691.0,409.0>--<439.0,0.0>>

	* uni04CD (U+04CD): L<<786.0,-67.0>--<775.0,0.0>> -> L<<775.0,0.0>--<753.0,108.0>>

	* uni04CD (U+04CD): L<<856.0,532.0>--<899.0,88.0>> -> L<<899.0,88.0>--<916.0,-1.0>>

	* uni04F5 (U+04F5): L<<469.0,0.0>--<469.0,174.0>> -> L<<469.0,174.0>--<475.0,249.0>>

	* uni04FC (U+04FC): L<<447.0,357.0>--<703.0,53.0>> -> L<<703.0,53.0>--<729.0,23.0>>

	* uni04FC (U+04FC): L<<632.0,-19.0>--<601.0,19.0>> -> L<<601.0,19.0>--<383.0,278.0>>

	* uni04FD (U+04FD): L<<313.0,260.0>--<473.0,38.0>> -> L<<473.0,38.0>--<481.0,27.0>>

	* uni04FD (U+04FD): L<<412.0,-30.0>--<389.0,4.0>> -> L<<389.0,4.0>--<259.0,185.0>>

	* uni051B (U+051B): L<<538.0,-216.0>--<538.0,-10.0>> -> L<<538.0,-10.0>--<543.0,80.0>>

	* uni1E0D (U+1E0D): L<<543.0,440.0>--<538.0,530.0>> -> L<<538.0,530.0>--<538.0,736.0>>

	* uniA78B (U+A78B): L<<123.0,731.0>--<123.0,409.0>> -> L<<123.0,409.0>--<118.0,196.0>>

	* uniA78B (U+A78B): L<<38.0,196.0>--<33.0,409.0>> -> L<<33.0,409.0>--<33.0,731.0>>

	* uniA78C (U+A78C): L<<110.0,730.0>--<110.0,520.0>> -> L<<110.0,520.0>--<105.0,409.0>> 

	* uniA78C (U+A78C): L<<38.0,409.0>--<33.0,520.0>> -> L<<33.0,520.0>--<33.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<233.0,612.0>--<697.0,614.0>>

	* ae (U+00E6): L<<599.0,303.0>--<997.0,304.0>>

	* aeacute (U+01FD): L<<599.0,303.0>--<997.0,304.0>>

	* beta (U+03B2): L<<132.0,-1.0>--<131.0,-217.0>>

	* e (U+0065): L<<131.0,303.0>--<529.0,304.0>>

	* eacute (U+00E9): L<<131.0,303.0>--<529.0,304.0>>

	* ebreve (U+0115): L<<131.0,303.0>--<529.0,304.0>>

	* ecaron (U+011B): L<<131.0,303.0>--<529.0,304.0>>

	* ecircumflex (U+00EA): L<<131.0,303.0>--<529.0,304.0>>

	* edieresis (U+00EB): L<<131.0,303.0>--<529.0,304.0>>

	* edotaccent (U+0117): L<<131.0,303.0>--<529.0,304.0>>

	* egrave (U+00E8): L<<131.0,303.0>--<529.0,304.0>>

	* emacron (U+0113): L<<131.0,303.0>--<529.0,304.0>>

	* eogonek (U+0119): L<<131.0,303.0>--<529.0,304.0>>

	* estimated (U+212E): L<<591.0,351.0>--<590.0,476.0>>

	* oe (U+0153): L<<686.0,303.0>--<1083.0,304.0>>

	* sterling (U+00A3): L<<298.0,422.0>--<453.0,423.0>>

	* uni0259 (U+0259): L<<525.0,216.0>--<128.0,215.0>>

	* uni0416 (U+0416): L<<431.0,0.0>--<430.0,322.0>>

	* uni0435 (U+0435): L<<131.0,303.0>--<529.0,304.0>>

	* uni0450 (U+0450): L<<131.0,303.0>--<529.0,304.0>>

	* uni0451 (U+0451): L<<131.0,303.0>--<529.0,304.0>>

	* uni046A (U+046A): L<<343.0,0.0>--<344.0,323.0>>

	* uni046A (U+046A): L<<447.0,323.0>--<446.0,0.0>>

	* uni046B (U+046B): L<<252.0,0.0>--<253.0,227.0>>

	* uni0496 (U+0496): L<<431.0,0.0>--<430.0,322.0>>

	* uni04C1 (U+04C1): L<<431.0,0.0>--<430.0,322.0>>

	* uni04CD (U+04CD): L<<753.0,108.0>--<752.0,516.0>>

	* uni04D5 (U+04D5): L<<599.0,303.0>--<997.0,304.0>>

	* uni04D7 (U+04D7): L<<131.0,303.0>--<529.0,304.0>>

	* uni04D9 (U+04D9): L<<525.0,216.0>--<128.0,215.0>>

	* uni04DB (U+04DB): L<<525.0,216.0>--<128.0,215.0>>

	* uni04DC (U+04DC): L<<431.0,0.0>--<430.0,322.0>>

	* uni1E15 (U+1E15): L<<131.0,303.0>--<529.0,304.0>>

	* uni1E17 (U+1E17): L<<131.0,303.0>--<529.0,304.0>>

	* uni1EB9 (U+1EB9): L<<131.0,303.0>--<529.0,304.0>>

	* uni1EBD (U+1EBD): L<<131.0,303.0>--<529.0,304.0>>

	* uni20B4 (U+20B4): L<<26.0,311.0>--<777.0,312.0>>

	* uni20B4 (U+20B4): L<<51.0,457.0>--<545.0,458.0>>

	* uni20BD (U+20BD): L<<235.0,197.0>--<406.0,198.0>> 

	* uni25B5 (U+25B5): L<<546.0,112.0>--<20.0,113.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NonBureauExtended-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended SemiBold' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<208.0,736.0>--<194.0,539.0>> -> L<<194.0,539.0>--<184.0,468.0>>

	* beta (U+03B2): L<<157.0,59.0>--<158.0,-1.0>> -> L<<158.0,-1.0>--<142.0,-217.0>>

	* d (U+0064): L<<536.0,461.0>--<536.0,539.0>> -> L<<536.0,539.0>--<550.0,736.0>>

	* dcaron (U+010F): L<<536.0,461.0>--<536.0,539.0>> -> L<<536.0,539.0>--<550.0,736.0>>

	* dcroat (U+0111): L<<536.0,462.0>--<538.0,539.0>> -> L<<538.0,539.0>--<540.0,598.0>>

	* dmacronbelow (U+1E0F): L<<536.0,461.0>--<536.0,539.0>> -> L<<536.0,539.0>--<550.0,736.0>>

	* f_f (U+FB00): L<<272.0,520.0>--<410.0,520.0>> -> L<<410.0,520.0>--<489.0,518.0>>

	* f_f_i (U+FB03): L<<272.0,520.0>--<410.0,520.0>> -> L<<410.0,520.0>--<489.0,518.0>>

	* f_t (U+FB05): L<<272.0,520.0>--<380.0,520.0>> -> L<<380.0,520.0>--<467.0,518.0>>

	* p (U+0070): L<<155.0,51.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* q (U+0071): L<<483.0,-216.0>--<496.0,-19.0>> -> L<<496.0,-19.0>--<506.0,51.0>>

	* rho (U+03C1): L<<155.0,51.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* slash (U+002F): L<<351.0,714.0>--<350.0,710.0>> -> L<<350.0,710.0>--<88.0,-130.0>>

	* tau (U+03C4): L<<118.0,518.0>--<266.0,520.0>> -> L<<266.0,520.0>--<420.0,520.0>>

	* tau (U+03C4): L<<38.0,523.0>--<118.0,518.0>> -> L<<118.0,518.0>--<266.0,520.0>>

	* thorn (U+00FE): L<<155.0,51.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* trademark (U+2122): L<<749.0,570.0>--<694.0,469.0>> -> L<<694.0,469.0>--<627.0,359.0>>

	* uni0335 (U+0335): L<<125.0,304.0>--<264.0,306.0>> -> L<<264.0,306.0>--<349.0,306.0>>

	* uni0335 (U+0335): L<<40.0,309.0>--<125.0,304.0>> -> L<<125.0,304.0>--<264.0,306.0>>

	* uni03BC (U+03BC): L<<155.0,46.0>--<156.0,-18.0>> -> L<<156.0,-18.0>--<142.0,-217.0>>

	* uni0440 (U+0440): L<<155.0,51.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* uni0447 (U+0447): L<<441.0,0.0>--<453.0,167.0>> -> L<<453.0,167.0>--<464.0,243.0>>

	* uni048F (U+048F): L<<155.0,51.0>--<155.0,-19.0>> -> L<<155.0,-19.0>--<142.0,-216.0>>

	* uni0497 (U+0497): L<<517.0,318.0>--<593.0,397.0>> -> L<<593.0,397.0>--<731.0,520.0>>

	* uni04B7 (U+04B7): L<<441.0,0.0>--<453.0,167.0>> -> L<<453.0,167.0>--<464.0,243.0>>

	* uni04B9 (U+04B9): L<<441.0,0.0>--<453.0,167.0>> -> L<<453.0,167.0>--<464.0,243.0>>

	* uni04CD (U+04CD): L<<203.0,714.0>--<357.0,411.0>> -> L<<357.0,411.0>--<454.0,196.0>>

	* uni04CD (U+04CD): L<<407.0,0.0>--<287.0,215.0>> -> L<<287.0,215.0>--<196.0,420.0>>

	* uni04CD (U+04CD): L<<728.0,0.0>--<733.0,215.0>> -> L<<733.0,215.0>--<746.0,420.0>>

	* uni04F5 (U+04F5): L<<441.0,0.0>--<453.0,167.0>> -> L<<453.0,167.0>--<464.0,243.0>>

	* uni04FC (U+04FC): L<<507.0,356.0>--<695.0,106.0>> -> L<<695.0,106.0>--<718.0,74.0>>

	* uni04FC (U+04FC): L<<579.0,9.0>--<557.0,38.0>> -> L<<557.0,38.0>--<405.0,239.0>>

	* uni04FD (U+04FD): L<<363.0,259.0>--<481.0,77.0>> -> L<<481.0,77.0>--<492.0,59.0>>

	* uni04FD (U+04FD): L<<380.0,-13.0>--<368.0,7.0>> -> L<<368.0,7.0>--<275.0,148.0>>

	* uni051B (U+051B): L<<483.0,-216.0>--<496.0,-19.0>> -> L<<496.0,-19.0>--<506.0,51.0>>

	* uni1E0D (U+1E0D): L<<536.0,461.0>--<536.0,539.0>> -> L<<536.0,539.0>--<550.0,736.0>>

	* uniA78B (U+A78B): L<<190.0,731.0>--<167.0,409.0>> -> L<<167.0,409.0>--<147.0,196.0>>

	* uniA78B (U+A78B): L<<27.0,196.0>--<37.0,409.0>> -> L<<37.0,409.0>--<60.0,731.0>>

	* uniA78C (U+A78C): L<<173.0,730.0>--<158.0,520.0>> -> L<<158.0,520.0>--<145.0,409.0>> 

	* uniA78C (U+A78C): L<<42.0,409.0>--<45.0,520.0>> -> L<<45.0,520.0>--<60.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NonBureau-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* f (U+0066): X=126.0,Y=518.0 (should be at x-height 520?)

	* r (U+0072): X=337.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=125.0,Y=518.0 (should be at x-height 520?)

	* t (U+0074): X=344.0,Y=-2.0 (should be at baseline 0?)

	* bar (U+007C): X=37.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=110.0,Y=715.0 (should be at cap-height 714?)

	* registered (U+00AE): X=276.0,Y=715.0 (should be at cap-height 714?)

	* onehalf (U+00BD): X=351.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=550.0,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=440.0,Y=713.0 (should be at cap-height 714?)

	* aring (U+00E5): X=239.0,Y=712.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=373.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=134.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=377.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=138.0,Y=713.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=252.0,Y=716.0 (should be at cap-height 714?)

	* gcircumflex (U+011D): X=275.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=219.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=299.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=371.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=132.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=308.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=69.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=354.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=115.0,Y=713.0 (should be at cap-height 714?)

	* uni0163 (U+0163): X=344.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=344.0,Y=-2.0 (should be at baseline 0?)

	* tbar (U+0167): X=344.0,Y=-2.0 (should be at baseline 0?)

	* uni0186 (U+0186): X=110.5,Y=2.0 (should be at baseline 0?)

	* florin (U+0192): X=10.0,Y=-2.0 (should be at baseline 0?)

	* uni01CE (U+01CE): X=358.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=119.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=388.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=149.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=383.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=383.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=144.0,Y=712.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=144.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=203.0,Y=716.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=324.0,Y=716.0 (should be at cap-height 714?)

	* Oslashacute (U+01FE): X=440.0,Y=713.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=344.0,Y=-2.0 (should be at baseline 0?)

	* uni023B (U+023B): X=427.0,Y=715.0 (should be at cap-height 714?)

	* uni023C (U+023C): X=181.0,Y=-2.0 (should be at baseline 0?)

	* uni0254 (U+0254): X=89.0,Y=-2.0 (should be at baseline 0?)

	* uni0269 (U+0269): X=211.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresistonos (U+0390): X=211.0,Y=-1.0 (should be at baseline 0?)

	* alphatonos (U+03AC): X=576.0,Y=-2.0 (should be at baseline 0?)

	* iotatonos (U+03AF): X=211.0,Y=-1.0 (should be at baseline 0?)

	* alpha (U+03B1): X=576.0,Y=-2.0 (should be at baseline 0?)

	* beta (U+03B2): X=283.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=111.0,Y=-1.0 (should be at baseline 0?)

	* gamma (U+03B3): X=294.0,Y=1.0 (should be at baseline 0?)

	* gamma (U+03B3): X=221.0,Y=1.0 (should be at baseline 0?)

	* iota (U+03B9): X=211.0,Y=-1.0 (should be at baseline 0?)

	* tau (U+03C4): X=299.0,Y=-1.0 (should be at baseline 0?)

	* iotadieresis (U+03CA): X=211.0,Y=-1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=31.0,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=8.0,Y=2.0 (should be at baseline 0?)

	* yacy (U+044F): X=99.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=18.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=31.0,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=8.0,Y=2.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=462.0,Y=1.0 (should be at baseline 0?)

	* uni04A7 (U+04A7): X=390.0,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=31.0,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=8.0,Y=2.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=108.0,Y=1.0 (should be at baseline 0?)

	* uni04FC (U+04FC): X=21.0,Y=1.0 (should be at baseline 0?)

	* uni04FD (U+04FD): X=392.0,Y=2.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=31.0,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=8.0,Y=2.0 (should be at baseline 0?)

	* uni1E6D (U+1E6D): X=344.0,Y=-2.0 (should be at baseline 0?)

	* tmacronbelow (U+1E6F): X=344.0,Y=-2.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=37.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=110.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=260.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=333.0,Y=715.0 (should be at cap-height 714?)

	* colonmonetary (U+20A1): X=250.0,Y=-2.0 (should be at baseline 0?)

	* uni20BF (U+20BF): X=348.0,Y=713.0 (should be at cap-height 714?)

	* soundreccopyright (U+2117): X=276.0,Y=715.0 (should be at cap-height 714?)

	* emptyset (U+2205): X=62.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=761.0,Y=2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=498.5,Y=0.5 (should be at baseline 0?)

	* uni25CC (U+25CC): X=257.5,Y=-0.5 (should be at baseline 0?)

	* uni2C66 (U+2C66): X=344.0,Y=-2.0 (should be at baseline 0?) 

	* f_t (U+FB05): X=624.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<110.0,736.0>--<110.0,525.0>> -> L<<110.0,525.0>--<105.0,439.0>>

	* beta (U+03B2): L<<106.0,80.0>--<111.0,-1.0>> -> L<<111.0,-1.0>--<110.0,-217.0>>

	* d (U+0064): L<<420.0,439.0>--<415.0,525.0>> -> L<<415.0,525.0>--<415.0,736.0>>

	* dcaron (U+010F): L<<420.0,439.0>--<415.0,525.0>> -> L<<415.0,525.0>--<415.0,736.0>>

	* dcroat (U+0111): L<<417.0,435.0>--<415.0,520.0>> -> L<<415.0,520.0>--<415.0,614.0>>

	* dmacronbelow (U+1E0F): L<<420.0,439.0>--<415.0,525.0>> -> L<<415.0,525.0>--<415.0,736.0>>

	* dong (U+20AB): L<<353.0,446.0>--<347.0,513.0>> -> L<<347.0,513.0>--<347.0,576.0>>

	* f_f (U+FB00): L<<199.0,520.0>--<320.0,520.0>> -> L<<320.0,520.0>--<405.0,518.0>>

	* f_f_i (U+FB03): L<<199.0,520.0>--<287.0,520.0>> -> L<<287.0,520.0>--<371.0,518.0>>

	* f_t (U+FB05): L<<199.0,520.0>--<323.0,520.0>> -> L<<323.0,520.0>--<404.0,518.0>>

	* hbar (U+0127): L<<204.0,614.0>--<204.0,525.0>> -> L<<204.0,525.0>--<195.0,435.0>>

	* p (U+0070): L<<105.0,81.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* q (U+0071): L<<415.0,-216.0>--<415.0,-5.0>> -> L<<415.0,-5.0>--<420.0,81.0>>

	* raisedmcsign (U+1F16A): L<<206.0,359.0>--<87.0,604.0>> -> L<<87.0,604.0>--<75.0,630.0>>

	* raisedmcsign (U+1F16A): L<<360.0,359.0>--<342.0,604.0>> -> L<<342.0,604.0>--<341.0,630.0>>

	* raisedmcsign (U+1F16A): L<<77.0,714.0>--<194.0,492.0>> -> L<<194.0,492.0>--<209.0,461.0>>

	* raisedmdsign (U+1F16B): L<<206.0,359.0>--<87.0,604.0>> -> L<<87.0,604.0>--<75.0,630.0>>

	* raisedmdsign (U+1F16B): L<<360.0,359.0>--<342.0,604.0>> -> L<<342.0,604.0>--<341.0,630.0>>

	* raisedmdsign (U+1F16B): L<<77.0,714.0>--<194.0,492.0>> -> L<<194.0,492.0>--<209.0,461.0>>

	* raisedmrsign (U+1F16C): L<<206.0,359.0>--<87.0,604.0>> -> L<<87.0,604.0>--<75.0,630.0>>

	* raisedmrsign (U+1F16C): L<<360.0,359.0>--<342.0,604.0>> -> L<<342.0,604.0>--<341.0,630.0>>

	* raisedmrsign (U+1F16C): L<<77.0,714.0>--<194.0,492.0>> -> L<<194.0,492.0>--<209.0,461.0>>

	* rho (U+03C1): L<<105.0,81.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* tau (U+03C4): L<<125.0,518.0>--<198.0,520.0>> -> L<<198.0,520.0>--<327.0,520.0>>

	* tau (U+03C4): L<<35.0,523.0>--<125.0,518.0>> -> L<<125.0,518.0>--<198.0,520.0>>

	* thorn (U+00FE): L<<105.0,81.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* thorn (U+00FE): L<<111.0,736.0>--<111.0,520.0>> -> L<<111.0,520.0>--<104.0,441.0>>

	* trademark (U+2122): L<<391.0,714.0>--<508.0,492.0>> -> L<<508.0,492.0>--<523.0,461.0>>

	* trademark (U+2122): L<<519.0,359.0>--<400.0,604.0>> -> L<<400.0,604.0>--<389.0,630.0>>

	* trademark (U+2122): L<<673.0,359.0>--<656.0,604.0>> -> L<<656.0,604.0>--<655.0,630.0>>

	* uni018F (U+018F): L<<27.0,351.0>--<470.0,365.0>> -> L<<470.0,365.0>--<553.0,371.0>>

	* uni0335 (U+0335): L<<117.0,285.0>--<184.0,287.0>> -> L<<184.0,287.0>--<264.0,287.0>>

	* uni0335 (U+0335): L<<37.0,290.0>--<117.0,285.0>> -> L<<117.0,285.0>--<184.0,287.0>>

	* uni03BC (U+03BC): L<<105.0,69.0>--<110.0,17.0>> -> L<<110.0,17.0>--<110.0,-217.0>>

	* uni0440 (U+0440): L<<105.0,81.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* uni0447 (U+0447): L<<337.0,0.0>--<337.0,178.0>> -> L<<337.0,178.0>--<343.0,250.0>>

	* uni0452 (U+0452): L<<197.0,583.0>--<197.0,483.0>> -> L<<197.0,483.0>--<190.0,395.0>>

	* uni045B (U+045B): L<<198.0,583.0>--<198.0,483.0>> -> L<<198.0,483.0>--<191.0,395.0>>

	* uni0463 (U+0463): L<<193.0,568.0>--<193.0,463.0>> -> L<<193.0,463.0>--<188.0,391.0>>

	* uni048F (U+048F): L<<105.0,81.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* uni04B7 (U+04B7): L<<337.0,0.0>--<337.0,178.0>> -> L<<337.0,178.0>--<343.0,250.0>>

	* uni04B9 (U+04B9): L<<344.0,0.0>--<344.0,178.0>> -> L<<344.0,178.0>--<350.0,250.0>>

	* uni04CC (U+04CC): L<<339.0,60.0>--<339.0,181.0>> -> L<<339.0,181.0>--<345.0,250.0>>

	* uni04F5 (U+04F5): L<<337.0,0.0>--<337.0,178.0>> -> L<<337.0,178.0>--<343.0,250.0>>

	* uni04FC (U+04FC): L<<364.0,358.0>--<602.0,27.0>> -> L<<602.0,27.0>--<624.0,-4.0>>

	* uni04FC (U+04FC): L<<556.0,-32.0>--<526.0,11.0>> -> L<<526.0,11.0>--<320.0,297.0>>

	* uni04FD (U+04FD): L<<288.0,260.0>--<461.0,19.0>> -> L<<461.0,19.0>--<468.0,10.0>>

	* uni04FD (U+04FD): L<<419.0,-38.0>--<392.0,2.0>> -> L<<392.0,2.0>--<247.0,203.0>>

	* uni051B (U+051B): L<<415.0,-216.0>--<415.0,-5.0>> -> L<<415.0,-5.0>--<420.0,81.0>>

	* uni1E0D (U+1E0D): L<<420.0,439.0>--<415.0,525.0>> -> L<<415.0,525.0>--<415.0,736.0>>

	* uniA78B (U+A78B): L<<107.0,731.0>--<107.0,409.0>> -> L<<107.0,409.0>--<102.0,196.0>>

	* uniA78B (U+A78B): L<<42.0,196.0>--<37.0,409.0>> -> L<<37.0,409.0>--<37.0,731.0>>

	* uniA78C (U+A78C): L<<42.0,409.0>--<37.0,520.0>> -> L<<37.0,520.0>--<37.0,730.0>> 

	* uniA78C (U+A78C): L<<95.0,730.0>--<95.0,520.0>> -> L<<95.0,520.0>--<90.0,409.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<205.0,606.0>--<609.0,608.0>>

	* arrowleft (U+2190): L<<442.0,264.0>--<443.0,51.0>>

	* arrowleft (U+2190): L<<442.0,326.0>--<631.0,325.0>>

	* arrowleft (U+2190): L<<443.0,539.0>--<442.0,326.0>>

	* arrowright (U+2192): L<<18.0,325.0>--<207.0,326.0>>

	* arrowright (U+2192): L<<206.0,51.0>--<207.0,264.0>>

	* arrowright (U+2192): L<<207.0,326.0>--<206.0,539.0>>

	* beta (U+03B2): L<<111.0,-1.0>--<110.0,-217.0>>

	* estimated (U+212E): L<<524.0,349.0>--<523.0,497.0>>

	* oe (U+0153): L<<909.0,248.0>--<525.0,247.0>>

	* psi (U+03C8): L<<231.0,48.0>--<232.0,520.0>>

	* psi (U+03C8): L<<292.0,520.0>--<291.0,48.0>>

	* uni046A (U+046A): L<<329.0,0.0>--<330.0,347.0>>

	* uni046A (U+046A): L<<407.0,347.0>--<406.0,0.0>>

	* uni046B (U+046B): L<<245.0,0.0>--<246.0,241.0>>

	* uni04E9 (U+04E9): L<<105.0,302.0>--<433.0,303.0>>

	* uni04EB (U+04EB): L<<105.0,302.0>--<433.0,303.0>> 

	* uni20B4 (U+20B4): L<<26.0,308.0>--<711.0,309.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NonBureauExtended-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 256) has trailing spaces that must be removed: 'Name: ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<110.0,736.0>--<110.0,525.0>> -> L<<110.0,525.0>--<105.0,426.0>>

	* beta (U+03B2): L<<106.0,99.0>--<111.0,-1.0>> -> L<<111.0,-1.0>--<110.0,-217.0>>

	* d (U+0064): L<<554.0,426.0>--<549.0,525.0>> -> L<<549.0,525.0>--<549.0,736.0>>

	* dcaron (U+010F): L<<554.0,426.0>--<549.0,525.0>> -> L<<549.0,525.0>--<549.0,736.0>>

	* dcroat (U+0111): L<<554.0,425.0>--<549.0,525.0>> -> L<<549.0,525.0>--<549.0,614.0>>

	* dmacronbelow (U+1E0F): L<<554.0,426.0>--<549.0,525.0>> -> L<<549.0,525.0>--<549.0,736.0>>

	* dong (U+20AB): L<<433.0,441.0>--<427.0,513.0>> -> L<<427.0,513.0>--<427.0,576.0>>

	* f_f (U+FB00): L<<199.0,520.0>--<342.0,520.0>> -> L<<342.0,520.0>--<431.0,518.0>>

	* f_f_i (U+FB03): L<<199.0,520.0>--<342.0,520.0>> -> L<<342.0,520.0>--<431.0,518.0>>

	* f_t (U+FB05): L<<199.0,520.0>--<324.0,520.0>> -> L<<324.0,520.0>--<426.0,518.0>>

	* p (U+0070): L<<105.0,94.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* q (U+0071): L<<549.0,-216.0>--<549.0,-5.0>> -> L<<549.0,-5.0>--<554.0,94.0>>

	* raisedmcsign (U+1F16A): L<<221.0,359.0>--<89.0,612.0>> -> L<<89.0,612.0>--<75.0,640.0>>

	* raisedmcsign (U+1F16A): L<<390.0,359.0>--<372.0,612.0>> -> L<<372.0,612.0>--<371.0,640.0>>

	* raisedmcsign (U+1F16A): L<<77.0,714.0>--<206.0,483.0>> -> L<<206.0,483.0>--<224.0,449.0>>

	* raisedmdsign (U+1F16B): L<<221.0,359.0>--<89.0,612.0>> -> L<<89.0,612.0>--<75.0,640.0>>

	* raisedmdsign (U+1F16B): L<<390.0,359.0>--<372.0,612.0>> -> L<<372.0,612.0>--<371.0,640.0>>

	* raisedmdsign (U+1F16B): L<<77.0,714.0>--<206.0,483.0>> -> L<<206.0,483.0>--<224.0,449.0>>

	* rho (U+03C1): L<<105.0,94.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* tau (U+03C4): L<<125.0,518.0>--<198.0,520.0>> -> L<<198.0,520.0>--<367.0,520.0>>

	* tau (U+03C4): L<<35.0,523.0>--<125.0,518.0>> -> L<<125.0,518.0>--<198.0,520.0>>

	* thorn (U+00FE): L<<105.0,94.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* thorn (U+00FE): L<<111.0,736.0>--<111.0,520.0>> -> L<<111.0,520.0>--<104.0,432.0>>

	* trademark (U+2122): L<<421.0,714.0>--<550.0,483.0>> -> L<<550.0,483.0>--<568.0,449.0>>

	* trademark (U+2122): L<<564.0,359.0>--<433.0,612.0>> -> L<<433.0,612.0>--<419.0,640.0>>

	* trademark (U+2122): L<<733.0,359.0>--<716.0,612.0>> -> L<<716.0,612.0>--<715.0,640.0>>

	* uni0335 (U+0335): L<<117.0,285.0>--<184.0,287.0>> -> L<<184.0,287.0>--<264.0,287.0>>

	* uni0335 (U+0335): L<<37.0,290.0>--<117.0,285.0>> -> L<<117.0,285.0>--<184.0,287.0>>

	* uni03BC (U+03BC): L<<105.0,78.0>--<110.0,17.0>> -> L<<110.0,17.0>--<110.0,-217.0>>

	* uni0440 (U+0440): L<<105.0,94.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* uni0447 (U+0447): L<<474.0,0.0>--<474.0,178.0>> -> L<<474.0,178.0>--<480.0,250.0>>

	* uni0463 (U+0463): L<<193.0,568.0>--<193.0,461.0>> -> L<<193.0,461.0>--<188.0,391.0>>

	* uni048F (U+048F): L<<105.0,94.0>--<110.0,-5.0>> -> L<<110.0,-5.0>--<110.0,-216.0>>

	* uni04B7 (U+04B7): L<<474.0,0.0>--<474.0,178.0>> -> L<<474.0,178.0>--<480.0,250.0>>

	* uni04B9 (U+04B9): L<<474.0,0.0>--<474.0,178.0>> -> L<<474.0,178.0>--<480.0,250.0>>

	* uni04CC (U+04CC): L<<476.0,60.0>--<476.0,183.0>> -> L<<476.0,183.0>--<481.0,250.0>>

	* uni04CD (U+04CD): L<<115.0,565.0>--<113.0,511.0>> -> L<<113.0,511.0>--<78.0,0.0>>

	* uni04CD (U+04CD): L<<437.0,101.0>--<478.0,177.0>> -> L<<478.0,177.0>--<791.0,714.0>>

	* uni04CD (U+04CD): L<<761.0,565.0>--<730.0,511.0>> -> L<<730.0,511.0>--<447.0,0.0>>

	* uni04F5 (U+04F5): L<<474.0,0.0>--<474.0,178.0>> -> L<<474.0,178.0>--<480.0,250.0>>

	* uni04FC (U+04FC): L<<421.0,357.0>--<702.0,27.0>> -> L<<702.0,27.0>--<728.0,-4.0>>

	* uni04FC (U+04FC): L<<650.0,-33.0>--<616.0,10.0>> -> L<<616.0,10.0>--<371.0,298.0>>

	* uni04FD (U+04FD): L<<288.0,260.0>--<461.0,19.0>> -> L<<461.0,19.0>--<468.0,10.0>>

	* uni04FD (U+04FD): L<<419.0,-38.0>--<392.0,2.0>> -> L<<392.0,2.0>--<247.0,203.0>>

	* uni051B (U+051B): L<<549.0,-216.0>--<549.0,-5.0>> -> L<<549.0,-5.0>--<554.0,94.0>>

	* uni1E0D (U+1E0D): L<<554.0,426.0>--<549.0,525.0>> -> L<<549.0,525.0>--<549.0,736.0>>

	* uniA78B (U+A78B): L<<107.0,731.0>--<107.0,409.0>> -> L<<107.0,409.0>--<102.0,196.0>>

	* uniA78B (U+A78B): L<<42.0,196.0>--<37.0,409.0>> -> L<<37.0,409.0>--<37.0,731.0>>

	* uniA78C (U+A78C): L<<42.0,409.0>--<37.0,520.0>> -> L<<37.0,520.0>--<37.0,730.0>> 

	* uniA78C (U+A78C): L<<95.0,730.0>--<95.0,520.0>> -> L<<95.0,520.0>--<90.0,409.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<212.0,606.0>--<706.0,608.0>>

	* arrowleft (U+2190): L<<442.0,264.0>--<443.0,51.0>>

	* arrowleft (U+2190): L<<442.0,326.0>--<631.0,325.0>>

	* arrowleft (U+2190): L<<443.0,539.0>--<442.0,326.0>>

	* arrowright (U+2192): L<<18.0,325.0>--<207.0,326.0>>

	* arrowright (U+2192): L<<206.0,51.0>--<207.0,264.0>>

	* arrowright (U+2192): L<<207.0,326.0>--<206.0,539.0>>

	* beta (U+03B2): L<<111.0,-1.0>--<110.0,-217.0>>

	* estimated (U+212E): L<<604.0,349.0>--<603.0,488.0>>

	* psi (U+03C8): L<<261.0,47.0>--<262.0,520.0>>

	* psi (U+03C8): L<<322.0,520.0>--<321.0,47.0>>

	* uni046A (U+046A): L<<329.0,0.0>--<330.0,347.0>>

	* uni046A (U+046A): L<<407.0,347.0>--<406.0,0.0>>

	* uni046B (U+046B): L<<245.0,0.0>--<246.0,241.0>>

	* uni04E9 (U+04E9): L<<107.0,302.0>--<549.0,303.0>>

	* uni04EB (U+04EB): L<<107.0,302.0>--<549.0,303.0>>

	* uni20B4 (U+20B4): L<<26.0,308.0>--<781.0,309.0>> 

	* uni2116 (U+2116): L<<778.0,56.0>--<1263.0,57.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NonBureau-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<213.0,497.0>>

	* d (U+0064): L<<395.0,497.0>--<390.0,549.0>> -> L<<390.0,549.0>--<390.0,736.0>>

	* dcaron (U+010F): L<<395.0,497.0>--<390.0,549.0>> -> L<<390.0,549.0>--<390.0,736.0>>

	* dcroat (U+0111): L<<392.0,477.0>--<390.0,520.0>> -> L<<390.0,520.0>--<390.0,587.0>>

	* dmacronbelow (U+1E0F): L<<395.0,497.0>--<390.0,549.0>> -> L<<390.0,549.0>--<390.0,736.0>>

	* f_f (U+FB00): L<<291.0,520.0>--<395.0,520.0>> -> L<<395.0,520.0>--<438.0,518.0>>

	* f_f_i (U+FB03): L<<291.0,520.0>--<395.0,520.0>> -> L<<395.0,520.0>--<438.0,518.0>>

	* f_t (U+FB05): L<<291.0,520.0>--<362.0,520.0>> -> L<<362.0,520.0>--<435.0,518.0>>

	* h (U+0068): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<211.0,477.0>>

	* hbar (U+0127): L<<294.0,587.0>--<294.0,549.0>> -> L<<294.0,549.0>--<287.0,477.0>>

	* hcircumflex (U+0125): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<211.0,477.0>>

	* p (U+0070): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* q (U+0071): L<<390.0,-216.0>--<390.0,-29.0>> -> L<<390.0,-29.0>--<395.0,23.0>>

	* rho (U+03C1): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* tau (U+03C4): L<<10.0,523.0>--<83.0,518.0>> -> L<<83.0,518.0>--<281.0,520.0>>

	* tau (U+03C4): L<<83.0,518.0>--<281.0,520.0>> -> L<<281.0,520.0>--<385.0,520.0>>

	* thorn (U+00FE): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* uni0335 (U+0335): L<<108.0,317.0>--<296.0,319.0>> -> L<<296.0,319.0>--<384.0,319.0>>

	* uni0335 (U+0335): L<<20.0,322.0>--<108.0,317.0>> -> L<<108.0,317.0>--<296.0,319.0>>

	* uni03BC (U+03BC): L<<213.0,21.0>--<218.0,-41.0>> -> L<<218.0,-41.0>--<218.0,-217.0>>

	* uni0440 (U+0440): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* uni0447 (U+0447): L<<329.0,0.0>--<329.0,160.0>> -> L<<329.0,160.0>--<337.0,242.0>>

	* uni048F (U+048F): L<<213.0,23.0>--<218.0,-29.0>> -> L<<218.0,-29.0>--<218.0,-216.0>>

	* uni04B7 (U+04B7): L<<329.0,0.0>--<329.0,160.0>> -> L<<329.0,160.0>--<337.0,242.0>>

	* uni04B9 (U+04B9): L<<369.0,0.0>--<369.0,160.0>> -> L<<369.0,160.0>--<377.0,242.0>>

	* uni04BB (U+04BB): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<211.0,477.0>>

	* uni04F5 (U+04F5): L<<329.0,0.0>--<329.0,160.0>> -> L<<329.0,160.0>--<337.0,242.0>>

	* uni04FC (U+04FC): L<<499.0,36.0>--<483.0,59.0>> -> L<<483.0,59.0>--<387.0,195.0>>

	* uni04FC (U+04FC): L<<502.0,357.0>--<643.0,158.0>> -> L<<643.0,158.0>--<664.0,128.0>>

	* uni04FD (U+04FD): L<<384.0,1.0>--<377.0,11.0>> -> L<<377.0,11.0>--<306.0,110.0>>

	* uni04FD (U+04FD): L<<413.0,260.0>--<518.0,115.0>> -> L<<518.0,115.0>--<533.0,95.0>>

	* uni051B (U+051B): L<<390.0,-216.0>--<390.0,-29.0>> -> L<<390.0,-29.0>--<395.0,23.0>>

	* uni0527 (U+0527): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<211.0,477.0>>

	* uni1E0D (U+1E0D): L<<395.0,497.0>--<390.0,549.0>> -> L<<390.0,549.0>--<390.0,736.0>>

	* uni1E25 (U+1E25): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<211.0,477.0>>

	* uni1E2B (U+1E2B): L<<218.0,736.0>--<218.0,549.0>> -> L<<218.0,549.0>--<211.0,477.0>>

	* uniA78B (U+A78B): L<<190.0,731.0>--<190.0,409.0>> -> L<<190.0,409.0>--<185.0,196.0>>

	* uniA78B (U+A78B): L<<25.0,196.0>--<20.0,409.0>> -> L<<20.0,409.0>--<20.0,731.0>>

	* uniA78C (U+A78C): L<<170.0,730.0>--<170.0,520.0>> -> L<<170.0,520.0>--<165.0,409.0>> 

	* uniA78C (U+A78C): L<<25.0,409.0>--<20.0,520.0>> -> L<<20.0,520.0>--<20.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<280.0,636.0>--<584.0,638.0>>

	* ampersand (U+0026): L<<496.0,337.0>--<666.0,338.0>>

	* arrowleft (U+2190): L<<459.0,358.0>--<614.0,357.0>>

	* arrowleft (U+2190): L<<614.0,230.0>--<459.0,229.0>>

	* arrowright (U+2192): L<<10.0,357.0>--<165.0,358.0>>

	* arrowright (U+2192): L<<165.0,229.0>--<10.0,230.0>>

	* beta (U+03B2): L<<219.0,-1.0>--<218.0,-217.0>>

	* chi (U+03C7): L<<10.0,361.0>--<11.0,521.0>>

	* franc (U+20A3): L<<301.0,203.0>--<502.0,204.0>>

	* psi (U+03C8): L<<268.0,137.0>--<269.0,520.0>>

	* psi (U+03C8): L<<389.0,520.0>--<388.0,137.0>>

	* sterling (U+00A3): L<<347.0,413.0>--<472.0,414.0>>

	* uni046A (U+046A): L<<396.0,0.0>--<397.0,230.0>>

	* uni046A (U+046A): L<<607.0,230.0>--<606.0,0.0>>

	* uni046B (U+046B): L<<283.0,0.0>--<284.0,168.0>>

	* uni046B (U+046B): L<<481.0,168.0>--<480.0,0.0>>

	* uni04BC (U+04BC): L<<433.0,444.0>--<714.0,445.0>>

	* uni04BE (U+04BE): L<<433.0,444.0>--<714.0,445.0>>

	* uni04D8 (U+04D8): L<<532.0,269.0>--<241.0,268.0>>

	* uni04DA (U+04DA): L<<532.0,269.0>--<241.0,268.0>>

	* uni04E9 (U+04E9): L<<229.0,324.0>--<373.0,325.0>>

	* uni04EB (U+04EB): L<<229.0,324.0>--<373.0,325.0>>

	* uni20B4 (U+20B4): L<<26.0,324.0>--<741.0,326.0>>

	* uni20B4 (U+20B4): L<<52.0,448.0>--<428.0,449.0>>

	* uni20BD (U+20BD): L<<360.0,198.0>--<539.0,199.0>> 

	* uniAB53 (U+AB53): L<<10.0,361.0>--<11.0,521.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NonBureau-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<186.0,736.0>--<172.0,535.0>> -> L<<172.0,535.0>--<162.0,464.0>>

	* beta (U+03B2): L<<136.0,58.0>--<137.0,-1.0>> -> L<<137.0,-1.0>--<120.0,-217.0>>

	* d (U+0064): L<<425.0,462.0>--<424.0,535.0>> -> L<<424.0,535.0>--<438.0,736.0>>

	* dcaron (U+010F): L<<425.0,462.0>--<424.0,535.0>> -> L<<424.0,535.0>--<438.0,736.0>>

	* dcroat (U+0111): L<<425.0,462.0>--<424.0,535.0>> -> L<<424.0,535.0>--<429.0,603.0>>

	* dmacronbelow (U+1E0F): L<<425.0,462.0>--<424.0,535.0>> -> L<<424.0,535.0>--<438.0,736.0>>

	* f_f (U+FB00): L<<254.0,520.0>--<368.0,520.0>> -> L<<368.0,520.0>--<436.0,518.0>>

	* f_f_i (U+FB03): L<<254.0,520.0>--<348.0,520.0>> -> L<<348.0,520.0>--<416.0,518.0>>

	* hbar (U+0127): L<<264.0,603.0>--<259.0,535.0>> -> L<<259.0,535.0>--<245.0,452.0>>

	* p (U+0070): L<<134.0,58.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* q (U+0071): L<<372.0,-216.0>--<386.0,-14.0>> -> L<<386.0,-14.0>--<396.0,58.0>>

	* raisedmcsign (U+1F16A): L<<362.0,584.0>--<288.0,437.0>> -> L<<288.0,437.0>--<240.0,359.0>>

	* rho (U+03C1): L<<134.0,58.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* slash (U+002F): L<<316.0,714.0>--<315.0,710.0>> -> L<<315.0,710.0>--<53.0,-130.0>>

	* tau (U+03C4): L<<126.0,518.0>--<249.0,520.0>> -> L<<249.0,520.0>--<368.0,520.0>>

	* tau (U+03C4): L<<43.0,523.0>--<126.0,518.0>> -> L<<126.0,518.0>--<249.0,520.0>>

	* thorn (U+00FE): L<<134.0,58.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* trademark (U+2122): L<<686.0,584.0>--<612.0,437.0>> -> L<<612.0,437.0>--<564.0,359.0>>

	* uni0335 (U+0335): L<<117.0,298.0>--<232.0,300.0>> -> L<<232.0,300.0>--<315.0,300.0>>

	* uni0335 (U+0335): L<<33.0,303.0>--<117.0,298.0>> -> L<<117.0,298.0>--<232.0,300.0>>

	* uni0440 (U+0440): L<<134.0,58.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* uni0447 (U+0447): L<<316.0,0.0>--<328.0,171.0>> -> L<<328.0,171.0>--<339.0,246.0>>

	* uni0463 (U+0463): L<<239.0,541.0>--<234.0,466.0>> -> L<<234.0,466.0>--<225.0,410.0>>

	* uni048F (U+048F): L<<134.0,58.0>--<134.0,-14.0>> -> L<<134.0,-14.0>--<120.0,-216.0>>

	* uni04B7 (U+04B7): L<<316.0,0.0>--<328.0,171.0>> -> L<<328.0,171.0>--<339.0,246.0>>

	* uni04B9 (U+04B9): L<<336.0,0.0>--<348.0,171.0>> -> L<<348.0,171.0>--<359.0,246.0>>

	* uni04CC (U+04CC): L<<328.0,96.0>--<333.0,171.0>> -> L<<333.0,171.0>--<344.0,246.0>>

	* uni04CD (U+04CD): L<<170.0,714.0>--<275.0,487.0>> -> L<<275.0,487.0>--<390.0,169.0>>

	* uni04CD (U+04CD): L<<359.0,0.0>--<283.0,162.0>> -> L<<283.0,162.0>--<175.0,458.0>>

	* uni04CD (U+04CD): L<<633.0,0.0>--<628.0,162.0>> -> L<<628.0,162.0>--<648.0,458.0>>

	* uni04CD (U+04CD): L<<767.0,714.0>--<777.0,441.0>> -> L<<777.0,441.0>--<819.0,108.0>>

	* uni04F5 (U+04F5): L<<316.0,0.0>--<328.0,171.0>> -> L<<328.0,171.0>--<339.0,246.0>>

	* uni04FC (U+04FC): L<<427.0,357.0>--<605.0,80.0>> -> L<<605.0,80.0>--<625.0,48.0>>

	* uni04FC (U+04FC): L<<516.0,-3.0>--<494.0,30.0>> -> L<<494.0,30.0>--<348.0,256.0>>

	* uni04FD (U+04FD): L<<338.0,260.0>--<469.0,58.0>> -> L<<469.0,58.0>--<478.0,43.0>>

	* uni04FD (U+04FD): L<<387.0,-21.0>--<369.0,6.0>> -> L<<369.0,6.0>--<264.0,166.0>>

	* uni051B (U+051B): L<<372.0,-216.0>--<386.0,-14.0>> -> L<<386.0,-14.0>--<396.0,58.0>>

	* uni1E0D (U+1E0D): L<<425.0,462.0>--<424.0,535.0>> -> L<<424.0,535.0>--<438.0,736.0>>

	* uniA78B (U+A78B): L<<173.0,731.0>--<150.0,409.0>> -> L<<150.0,409.0>--<130.0,196.0>>

	* uniA78B (U+A78B): L<<30.0,196.0>--<40.0,409.0>> -> L<<40.0,409.0>--<63.0,731.0>>

	* uniA78C (U+A78C): L<<158.0,730.0>--<143.0,520.0>> -> L<<143.0,520.0>--<130.0,409.0>>

	* uniA78C (U+A78C): L<<45.0,409.0>--<48.0,520.0>> -> L<<48.0,520.0>--<63.0,730.0>> 

	* zeta (U+03B6): L<<445.0,563.0>--<440.0,492.0>> -> L<<440.0,492.0>--<440.0,461.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NonBureau-RegularItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Non Bureau Regular | Non Bureau |
| Subfamily Name | Italic | Italic |
| Full Name | Non Bureau Regular Italic | Non Bureau Italic |
| Poscript Name | NonBureau-RegularItalic | NonBureau-Italic |
| Typographic Family Name | Non Bureau | N/A |
| Typographic Subfamily Name | Regular Italic | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<164.0,736.0>--<150.0,530.0>> -> L<<150.0,530.0>--<139.0,452.0>>

	* beta (U+03B2): L<<115.0,69.0>--<115.0,-1.0>> -> L<<115.0,-1.0>--<98.0,-217.0>>

	* d (U+0064): L<<429.0,450.0>--<429.0,530.0>> -> L<<429.0,530.0>--<443.0,736.0>>

	* dcaron (U+010F): L<<429.0,450.0>--<429.0,530.0>> -> L<<429.0,530.0>--<443.0,736.0>>

	* dcroat (U+0111): L<<429.0,450.0>--<429.0,530.0>> -> L<<429.0,530.0>--<434.0,608.0>>

	* dmacronbelow (U+1E0F): L<<429.0,450.0>--<429.0,530.0>> -> L<<429.0,530.0>--<443.0,736.0>>

	* f_f (U+FB00): L<<236.0,520.0>--<353.0,520.0>> -> L<<353.0,520.0>--<429.0,518.0>>

	* f_f_i (U+FB03): L<<236.0,520.0>--<326.0,520.0>> -> L<<326.0,520.0>--<403.0,518.0>>

	* franc (U+20A3): L<<101.0,68.0>--<106.0,138.0>> -> L<<106.0,138.0>--<107.0,164.0>>

	* franc (U+20A3): L<<108.0,164.0>--<106.0,138.0>> -> L<<106.0,138.0>--<103.0,69.0>>

	* h (U+0068): L<<168.0,736.0>--<153.0,530.0>> -> L<<153.0,530.0>--<138.0,444.0>>

	* hcircumflex (U+0125): L<<168.0,736.0>--<153.0,530.0>> -> L<<153.0,530.0>--<138.0,444.0>>

	* p (U+0070): L<<113.0,70.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* q (U+0071): L<<377.0,-216.0>--<391.0,-10.0>> -> L<<391.0,-10.0>--<401.0,69.0>>

	* rho (U+03C1): L<<113.0,70.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* slash (U+002F): L<<299.0,714.0>--<298.0,710.0>> -> L<<298.0,710.0>--<36.0,-130.0>>

	* tau (U+03C4): L<<134.0,518.0>--<232.0,520.0>> -> L<<232.0,520.0>--<356.0,520.0>>

	* tau (U+03C4): L<<48.0,523.0>--<134.0,518.0>> -> L<<134.0,518.0>--<232.0,520.0>>

	* thorn (U+00FE): L<<113.0,70.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* uni0335 (U+0335): L<<118.0,291.0>--<209.0,293.0>> -> L<<209.0,293.0>--<291.0,293.0>>

	* uni0335 (U+0335): L<<36.0,296.0>--<118.0,291.0>> -> L<<118.0,291.0>--<209.0,293.0>>

	* uni0440 (U+0440): L<<113.0,70.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* uni0447 (U+0447): L<<318.0,0.0>--<329.0,174.0>> -> L<<329.0,174.0>--<340.0,248.0>>

	* uni0463 (U+0463): L<<227.0,555.0>--<221.0,464.0>> -> L<<221.0,464.0>--<211.0,400.0>>

	* uni048F (U+048F): L<<113.0,70.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* uni04B7 (U+04B7): L<<318.0,0.0>--<329.0,174.0>> -> L<<329.0,174.0>--<340.0,248.0>>

	* uni04B9 (U+04B9): L<<331.0,0.0>--<343.0,174.0>> -> L<<343.0,174.0>--<353.0,248.0>>

	* uni04BB (U+04BB): L<<168.0,736.0>--<153.0,530.0>> -> L<<153.0,530.0>--<138.0,444.0>>

	* uni04CC (U+04CC): L<<326.0,78.0>--<333.0,174.0>> -> L<<333.0,174.0>--<343.0,248.0>>

	* uni04CD (U+04CD): L<<649.0,-67.0>--<643.0,0.0>> -> L<<643.0,0.0>--<629.0,108.0>>

	* uni04CD (U+04CD): L<<656.0,503.0>--<604.0,395.0>> -> L<<604.0,395.0>--<365.0,0.0>>

	* uni04CD (U+04CD): L<<762.0,532.0>--<774.0,88.0>> -> L<<774.0,88.0>--<784.0,-1.0>>

	* uni04F5 (U+04F5): L<<318.0,0.0>--<329.0,174.0>> -> L<<329.0,174.0>--<340.0,248.0>>

	* uni04FC (U+04FC): L<<399.0,357.0>--<595.0,53.0>> -> L<<595.0,53.0>--<615.0,21.0>>

	* uni04FC (U+04FC): L<<526.0,-17.0>--<502.0,20.0>> -> L<<502.0,20.0>--<335.0,276.0>>

	* uni04FD (U+04FD): L<<312.0,260.0>--<456.0,38.0>> -> L<<456.0,38.0>--<464.0,26.0>>

	* uni04FD (U+04FD): L<<393.0,-29.0>--<372.0,4.0>> -> L<<372.0,4.0>--<253.0,185.0>>

	* uni051B (U+051B): L<<377.0,-216.0>--<391.0,-10.0>> -> L<<391.0,-10.0>--<401.0,70.0>>

	* uni0527 (U+0527): L<<168.0,736.0>--<153.0,530.0>> -> L<<153.0,530.0>--<138.0,444.0>>

	* uni1E0D (U+1E0D): L<<429.0,450.0>--<429.0,530.0>> -> L<<429.0,530.0>--<443.0,736.0>>

	* uni1E25 (U+1E25): L<<168.0,736.0>--<153.0,530.0>> -> L<<153.0,530.0>--<138.0,444.0>>

	* uni1E2B (U+1E2B): L<<168.0,736.0>--<153.0,530.0>> -> L<<153.0,530.0>--<138.0,444.0>>

	* uni2206 (U+2206): L<<434.0,720.0>--<766.0,2.0>> -> L<<766.0,2.0>--<767.0,0.0>>

	* uniA78B (U+A78B): L<<156.0,731.0>--<133.0,409.0>> -> L<<133.0,409.0>--<113.0,196.0>>

	* uniA78B (U+A78B): L<<33.0,196.0>--<43.0,409.0>> -> L<<43.0,409.0>--<66.0,731.0>>

	* uniA78C (U+A78C): L<<143.0,730.0>--<128.0,520.0>> -> L<<128.0,520.0>--<115.0,409.0>>

	* uniA78C (U+A78C): L<<48.0,409.0>--<51.0,520.0>> -> L<<51.0,520.0>--<66.0,730.0>> 

	* zeta (U+03B6): L<<428.0,563.0>--<424.0,509.0>> -> L<<424.0,509.0>--<424.0,480.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NonBureau-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=485.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=242.0,Y=2.0 (should be at baseline 0?)

	* b (U+0062): X=249.0,Y=519.5 (should be at x-height 520?)

	* d (U+0064): X=343.0,Y=519.5 (should be at x-height 520?)

	* d (U+0064): X=349.0,Y=2.0 (should be at baseline 0?)

	* f (U+0066): X=100.0,Y=518.0 (should be at x-height 520?)

	* p (U+0070): X=249.0,Y=0.5 (should be at baseline 0?)

	* p (U+0070): X=242.0,Y=518.0 (should be at x-height 520?)

	* q (U+0071): X=349.0,Y=518.0 (should be at x-height 520?)

	* q (U+0071): X=343.0,Y=0.5 (should be at baseline 0?)

	* r (U+0072): X=411.0,Y=521.0 (should be at x-height 520?)

	* t (U+0074): X=91.0,Y=518.0 (should be at x-height 520?)

	* bar (U+007C): X=23.0,Y=715.0 (should be at cap-height 714?)

	* bar (U+007C): X=190.0,Y=715.0 (should be at cap-height 714?)

	* ordfeminine (U+00AA): X=142.0,Y=713.0 (should be at cap-height 714?)

	* ordmasculine (U+00BA): X=157.0,Y=713.0 (should be at cap-height 714?)

	* ordmasculine (U+00BA): X=157.0,Y=713.0 (should be at cap-height 714?)

	* germandbls (U+00DF): X=380.5,Y=714.5 (should be at cap-height 714?)

	* thorn (U+00FE): X=249.0,Y=0.5 (should be at baseline 0?)

	* ccaron (U+010D): X=450.0,Y=713.0 (should be at cap-height 714?)

	* ccaron (U+010D): X=117.0,Y=713.0 (should be at cap-height 714?)

	* dcaron (U+010F): X=349.0,Y=2.0 (should be at baseline 0?)

	* ecaron (U+011B): X=459.0,Y=713.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=126.0,Y=713.0 (should be at cap-height 714?)

	* ij (U+0133): X=332.0,Y=2.0 (should be at baseline 0?)

	* lcaron (U+013E): X=307.0,Y=716.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=447.0,Y=716.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=461.0,Y=713.0 (should be at cap-height 714?)

	* ncaron (U+0148): X=128.0,Y=713.0 (should be at cap-height 714?)

	* Eng (U+014A): X=507.0,Y=1.0 (should be at baseline 0?)

	* rcaron (U+0159): X=394.0,Y=713.0 (should be at cap-height 714?)

	* rcaron (U+0159): X=61.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=433.0,Y=713.0 (should be at cap-height 714?)

	* scaron (U+0161): X=100.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=440.0,Y=713.0 (should be at cap-height 714?)

	* uni01CE (U+01CE): X=107.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=460.0,Y=713.0 (should be at cap-height 714?)

	* uni01D2 (U+01D2): X=127.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=477.0,Y=713.0 (should be at cap-height 714?)

	* gcaron (U+01E7): X=144.0,Y=713.0 (should be at cap-height 714?)

	* uni023B (U+023B): X=471.0,Y=715.0 (should be at cap-height 714?)

	* uni0263 (U+0263): X=28.0,Y=-2.0 (should be at baseline 0?)

	* uni0263 (U+0263): X=512.0,Y=-2.0 (should be at baseline 0?)

	* beta (U+03B2): X=323.0,Y=715.0 (should be at cap-height 714?)

	* beta (U+03B2): X=197.0,Y=-1.0 (should be at baseline 0?)

	* delta (U+03B4): X=250.5,Y=713.5 (should be at cap-height 714?)

	* uni03BC (U+03BC): X=236.5,Y=-1.5 (should be at baseline 0?)

	* rho (U+03C1): X=249.0,Y=0.5 (should be at baseline 0?)

	* uni0409 (U+0409): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni043B (U+043B): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni043B (U+043B): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni0440 (U+0440): X=249.0,Y=0.5 (should be at baseline 0?)

	* yacy (U+044F): X=205.0,Y=1.0 (should be at baseline 0?)

	* yacy (U+044F): X=12.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni0459 (U+0459): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni048F (U+048F): X=249.0,Y=0.5 (should be at baseline 0?)

	* uni04BE (U+04BE): X=660.0,Y=-2.0 (should be at baseline 0?)

	* uni04BF (U+04BF): X=572.0,Y=-2.0 (should be at baseline 0?)

	* uni04C3 (U+04C3): X=425.0,Y=1.5 (should be at baseline 0?)

	* uni04C4 (U+04C4): X=349.0,Y=0.5 (should be at baseline 0?)

	* uni04C5 (U+04C5): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni04C6 (U+04C6): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=47.5,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=35.5,Y=0.5 (should be at baseline 0?)

	* uni0513 (U+0513): X=2.0,Y=2.0 (should be at baseline 0?)

	* uni051A (U+051A): X=485.0,Y=1.0 (should be at baseline 0?)

	* uni051B (U+051B): X=343.0,Y=0.5 (should be at baseline 0?)

	* uni1E0D (U+1E0D): X=349.0,Y=2.0 (should be at baseline 0?)

	* dmacronbelow (U+1E0F): X=349.0,Y=2.0 (should be at baseline 0?)

	* uni2016 (U+2016): X=23.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=190.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=340.0,Y=715.0 (should be at cap-height 714?)

	* uni2016 (U+2016): X=507.0,Y=715.0 (should be at cap-height 714?)

	* lira (U+20A4): X=332.0,Y=713.0 (should be at cap-height 714?)

	* uni20BF (U+20BF): X=403.0,Y=2.0 (should be at baseline 0?)

	* emptyset (U+2205): X=76.0,Y=1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=855.0,Y=2.0 (should be at baseline 0?)

	* triagup (U+25B2): X=402.0,Y=715.0 (should be at cap-height 714?)

	* triagup (U+25B2): X=404.0,Y=715.0 (should be at cap-height 714?)

	* uni25B3 (U+25B3): X=402.0,Y=715.0 (should be at cap-height 714?)

	* uni25B3 (U+25B3): X=404.0,Y=715.0 (should be at cap-height 714?)

	* uni25B6 (U+25B6): X=23.0,Y=1.0 (should be at baseline 0?)

	* uni25B7 (U+25B7): X=23.0,Y=1.0 (should be at baseline 0?)

	* triagdn (U+25BC): X=20.0,Y=715.0 (should be at cap-height 714?)

	* triagdn (U+25BC): X=787.0,Y=715.0 (should be at cap-height 714?)

	* uni25BD (U+25BD): X=787.0,Y=715.0 (should be at cap-height 714?)

	* uni25BD (U+25BD): X=20.0,Y=715.0 (should be at cap-height 714?)

	* uni25C0 (U+25C0): X=683.0,Y=1.0 (should be at baseline 0?)

	* uni25C1 (U+25C1): X=683.0,Y=1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=490.0,Y=2.0 (should be at baseline 0?) 

	* uni25CC (U+25CC): X=307.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<196.0,736.0>--<196.0,544.0>> -> L<<196.0,544.0>--<191.0,485.0>>

	* d (U+0064): L<<400.0,485.0>--<395.0,544.0>> -> L<<395.0,544.0>--<395.0,736.0>>

	* dcaron (U+010F): L<<400.0,485.0>--<395.0,544.0>> -> L<<395.0,544.0>--<395.0,736.0>>

	* dcroat (U+0111): L<<397.0,469.0>--<395.0,520.0>> -> L<<395.0,520.0>--<395.0,592.0>>

	* dmacronbelow (U+1E0F): L<<400.0,485.0>--<395.0,544.0>> -> L<<395.0,544.0>--<395.0,736.0>>

	* f_f (U+FB00): L<<273.0,520.0>--<380.0,520.0>> -> L<<380.0,520.0>--<431.0,518.0>>

	* f_f_i (U+FB03): L<<273.0,520.0>--<373.0,520.0>> -> L<<373.0,520.0>--<425.0,518.0>>

	* f_t (U+FB05): L<<273.0,520.0>--<354.0,520.0>> -> L<<354.0,520.0>--<429.0,518.0>>

	* h (U+0068): L<<197.0,736.0>--<197.0,544.0>> -> L<<197.0,544.0>--<190.0,469.0>>

	* hbar (U+0127): L<<276.0,592.0>--<276.0,544.0>> -> L<<276.0,544.0>--<269.0,469.0>>

	* hcircumflex (U+0125): L<<197.0,736.0>--<197.0,544.0>> -> L<<197.0,544.0>--<190.0,469.0>>

	* p (U+0070): L<<191.0,35.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* q (U+0071): L<<395.0,-216.0>--<395.0,-24.0>> -> L<<395.0,-24.0>--<400.0,35.0>>

	* raisedmcsign (U+1F16A): L<<116.0,537.0>--<115.0,488.0>> -> L<<115.0,488.0>--<108.0,359.0>>

	* raisedmcsign (U+1F16A): L<<226.0,515.0>--<247.0,560.0>> -> L<<247.0,560.0>--<326.0,714.0>>

	* raisedmcsign (U+1F16A): L<<338.0,537.0>--<316.0,488.0>> -> L<<316.0,488.0>--<260.0,359.0>>

	* raisedmdsign (U+1F16B): L<<116.0,537.0>--<115.0,488.0>> -> L<<115.0,488.0>--<108.0,359.0>>

	* raisedmdsign (U+1F16B): L<<226.0,515.0>--<247.0,560.0>> -> L<<247.0,560.0>--<326.0,714.0>>

	* raisedmdsign (U+1F16B): L<<338.0,537.0>--<316.0,488.0>> -> L<<316.0,488.0>--<260.0,359.0>>

	* raisedmrsign (U+1F16C): L<<116.0,537.0>--<115.0,488.0>> -> L<<115.0,488.0>--<108.0,359.0>>

	* raisedmrsign (U+1F16C): L<<226.0,515.0>--<247.0,560.0>> -> L<<247.0,560.0>--<326.0,714.0>>

	* raisedmrsign (U+1F16C): L<<338.0,537.0>--<316.0,488.0>> -> L<<316.0,488.0>--<260.0,359.0>>

	* rho (U+03C1): L<<191.0,35.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* tau (U+03C4): L<<15.0,523.0>--<91.0,518.0>> -> L<<91.0,518.0>--<264.0,520.0>>

	* tau (U+03C4): L<<91.0,518.0>--<264.0,520.0>> -> L<<264.0,520.0>--<373.0,520.0>>

	* thorn (U+00FE): L<<191.0,35.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* trademark (U+2122): L<<449.0,537.0>--<448.0,488.0>> -> L<<448.0,488.0>--<441.0,359.0>>

	* trademark (U+2122): L<<559.0,515.0>--<580.0,560.0>> -> L<<580.0,560.0>--<660.0,714.0>>

	* trademark (U+2122): L<<671.0,537.0>--<649.0,488.0>> -> L<<649.0,488.0>--<593.0,359.0>>

	* uni023E (U+023E): L<<291.0,0.0>--<274.0,-12.0>> -> L<<274.0,-12.0>--<217.0,-53.0>>

	* uni0335 (U+0335): L<<110.0,311.0>--<274.0,313.0>> -> L<<274.0,313.0>--<360.0,313.0>>

	* uni0335 (U+0335): L<<23.0,316.0>--<110.0,311.0>> -> L<<110.0,311.0>--<274.0,313.0>>

	* uni03BC (U+03BC): L<<191.0,31.0>--<196.0,-29.0>> -> L<<196.0,-29.0>--<196.0,-217.0>>

	* uni0440 (U+0440): L<<191.0,35.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* uni0447 (U+0447): L<<331.0,0.0>--<331.0,164.0>> -> L<<331.0,164.0>--<338.0,244.0>>

	* uni048F (U+048F): L<<191.0,35.0>--<196.0,-24.0>> -> L<<196.0,-24.0>--<196.0,-216.0>>

	* uni04B7 (U+04B7): L<<331.0,0.0>--<331.0,164.0>> -> L<<331.0,164.0>--<338.0,244.0>>

	* uni04B9 (U+04B9): L<<364.0,0.0>--<364.0,164.0>> -> L<<364.0,164.0>--<372.0,244.0>>

	* uni04BB (U+04BB): L<<197.0,736.0>--<197.0,544.0>> -> L<<197.0,544.0>--<190.0,469.0>>

	* uni04F5 (U+04F5): L<<331.0,0.0>--<331.0,164.0>> -> L<<331.0,164.0>--<338.0,244.0>>

	* uni04FC (U+04FC): L<<474.0,357.0>--<635.0,132.0>> -> L<<635.0,132.0>--<656.0,102.0>>

	* uni04FC (U+04FC): L<<510.0,22.0>--<492.0,49.0>> -> L<<492.0,49.0>--<374.0,215.0>>

	* uni04FD (U+04FD): L<<388.0,260.0>--<507.0,96.0>> -> L<<507.0,96.0>--<520.0,78.0>>

	* uni04FD (U+04FD): L<<391.0,-7.0>--<380.0,9.0>> -> L<<380.0,9.0>--<294.0,129.0>>

	* uni051B (U+051B): L<<395.0,-216.0>--<395.0,-24.0>> -> L<<395.0,-24.0>--<400.0,35.0>>

	* uni0527 (U+0527): L<<197.0,736.0>--<197.0,544.0>> -> L<<197.0,544.0>--<190.0,469.0>>

	* uni1E0D (U+1E0D): L<<400.0,485.0>--<395.0,544.0>> -> L<<395.0,544.0>--<395.0,736.0>>

	* uni1E25 (U+1E25): L<<197.0,736.0>--<197.0,544.0>> -> L<<197.0,544.0>--<190.0,469.0>>

	* uni1E2B (U+1E2B): L<<197.0,736.0>--<197.0,544.0>> -> L<<197.0,544.0>--<190.0,469.0>>

	* uniA78B (U+A78B): L<<173.0,731.0>--<173.0,409.0>> -> L<<173.0,409.0>--<168.0,196.0>>

	* uniA78B (U+A78B): L<<28.0,196.0>--<23.0,409.0>> -> L<<23.0,409.0>--<23.0,731.0>>

	* uniA78C (U+A78C): L<<155.0,730.0>--<155.0,520.0>> -> L<<155.0,520.0>--<150.0,409.0>> 

	* uniA78C (U+A78C): L<<28.0,409.0>--<23.0,520.0>> -> L<<23.0,520.0>--<23.0,730.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Hbar (U+0126): L<<265.0,630.0>--<589.0,632.0>>

	* ampersand (U+0026): L<<511.0,337.0>--<661.0,338.0>>

	* arrowleft (U+2190): L<<456.0,352.0>--<617.0,351.0>>

	* arrowleft (U+2190): L<<617.0,237.0>--<456.0,236.0>>

	* arrowright (U+2192): L<<12.0,351.0>--<173.0,352.0>>

	* arrowright (U+2192): L<<173.0,236.0>--<12.0,237.0>>

	* beta (U+03B2): L<<197.0,-1.0>--<196.0,-217.0>>

	* chi (U+03C7): L<<12.0,380.0>--<13.0,522.0>>

	* franc (U+20A3): L<<278.0,203.0>--<478.0,204.0>>

	* psi (U+03C8): L<<261.0,119.0>--<262.0,520.0>>

	* psi (U+03C8): L<<370.0,520.0>--<369.0,119.0>>

	* sterling (U+00A3): L<<321.0,415.0>--<453.0,416.0>>

	* uni018F (U+018F): L<<104.0,399.0>--<519.0,401.0>>

	* uni046A (U+046A): L<<383.0,0.0>--<384.0,253.0>>

	* uni046A (U+046A): L<<567.0,253.0>--<566.0,0.0>>

	* uni046B (U+046B): L<<275.0,0.0>--<276.0,183.0>>

	* uni04BC (U+04BC): L<<397.0,438.0>--<713.0,439.0>>

	* uni04BE (U+04BE): L<<397.0,438.0>--<713.0,439.0>>

	* uni04D8 (U+04D8): L<<538.0,275.0>--<214.0,274.0>>

	* uni04DA (U+04DA): L<<538.0,275.0>--<214.0,274.0>>

	* uni04E9 (U+04E9): L<<204.0,320.0>--<385.0,321.0>>

	* uni04EB (U+04EB): L<<204.0,320.0>--<385.0,321.0>>

	* uni20B4 (U+20B4): L<<26.0,321.0>--<735.0,323.0>>

	* uni20B4 (U+20B4): L<<52.0,450.0>--<441.0,451.0>>

	* uni20BD (U+20BD): L<<330.0,198.0>--<507.0,199.0>> 

	* uniAB53 (U+AB53): L<<12.0,380.0>--<13.0,522.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NonBureauExtended-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended' / SUBFAMILY_NAME = 'Bold Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<229.0,736.0>--<216.0,544.0>> -> L<<216.0,544.0>--<207.0,483.0>>

	* d (U+0064): L<<526.0,474.0>--<526.0,544.0>> -> L<<526.0,544.0>--<539.0,736.0>>

	* dcaron (U+010F): L<<526.0,474.0>--<526.0,544.0>> -> L<<526.0,544.0>--<539.0,736.0>>

	* dcroat (U+0111): L<<526.0,475.0>--<527.0,544.0>> -> L<<527.0,544.0>--<529.0,592.0>>

	* dmacronbelow (U+1E0F): L<<526.0,474.0>--<526.0,544.0>> -> L<<526.0,544.0>--<539.0,736.0>>

	* f_f (U+FB00): L<<291.0,520.0>--<426.0,520.0>> -> L<<426.0,520.0>--<503.0,518.0>>

	* f_f_i (U+FB03): L<<291.0,520.0>--<426.0,520.0>> -> L<<426.0,520.0>--<503.0,518.0>>

	* f_t (U+FB05): L<<291.0,520.0>--<395.0,520.0>> -> L<<395.0,520.0>--<475.0,518.0>>

	* p (U+0070): L<<175.0,37.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* q (U+0071): L<<472.0,-216.0>--<485.0,-24.0>> -> L<<485.0,-24.0>--<494.0,36.0>>

	* rho (U+03C1): L<<175.0,37.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* slash (U+002F): L<<367.0,714.0>--<366.0,710.0>> -> L<<366.0,710.0>--<104.0,-130.0>>

	* tau (U+03C4): L<<109.0,518.0>--<282.0,520.0>> -> L<<282.0,520.0>--<431.0,520.0>>

	* tau (U+03C4): L<<33.0,523.0>--<109.0,518.0>> -> L<<109.0,518.0>--<282.0,520.0>>

	* thorn (U+00FE): L<<175.0,37.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* trademark (U+2122): L<<500.0,547.0>--<495.0,497.0>> -> L<<495.0,497.0>--<478.0,359.0>>

	* trademark (U+2122): L<<620.0,497.0>--<646.0,543.0>> -> L<<646.0,543.0>--<751.0,714.0>>

	* trademark (U+2122): L<<752.0,547.0>--<723.0,497.0>> -> L<<723.0,497.0>--<646.0,359.0>>

	* uni0335 (U+0335): L<<124.0,311.0>--<287.0,313.0>> -> L<<287.0,313.0>--<374.0,313.0>>

	* uni0335 (U+0335): L<<37.0,316.0>--<124.0,311.0>> -> L<<124.0,311.0>--<287.0,313.0>>

	* uni03BC (U+03BC): L<<176.0,36.0>--<177.0,-29.0>> -> L<<177.0,-29.0>--<163.0,-217.0>>

	* uni0440 (U+0440): L<<175.0,37.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* uni0447 (U+0447): L<<436.0,0.0>--<447.0,164.0>> -> L<<447.0,164.0>--<459.0,241.0>>

	* uni0463 (U+0463): L<<263.0,514.0>--<258.0,471.0>> -> L<<258.0,471.0>--<249.0,426.0>>

	* uni048F (U+048F): L<<175.0,37.0>--<176.0,-24.0>> -> L<<176.0,-24.0>--<163.0,-216.0>>

	* uni0497 (U+0497): L<<564.0,326.0>--<602.0,366.0>> -> L<<602.0,366.0>--<762.0,520.0>>

	* uni04B7 (U+04B7): L<<436.0,0.0>--<447.0,164.0>> -> L<<447.0,164.0>--<459.0,241.0>>

	* uni04B9 (U+04B9): L<<436.0,0.0>--<447.0,164.0>> -> L<<447.0,164.0>--<459.0,241.0>>

	* uni04CD (U+04CD): L<<235.0,714.0>--<415.0,335.0>> -> L<<415.0,335.0>--<464.0,227.0>>

	* uni04CD (U+04CD): L<<399.0,0.0>--<262.0,269.0>> -> L<<262.0,269.0>--<215.0,371.0>>

	* uni04CD (U+04CD): L<<714.0,0.0>--<728.0,269.0>> -> L<<728.0,269.0>--<733.0,371.0>>

	* uni04F5 (U+04F5): L<<436.0,0.0>--<447.0,164.0>> -> L<<447.0,164.0>--<459.0,241.0>>

	* uni04FC (U+04FC): L<<533.0,356.0>--<698.0,133.0>> -> L<<698.0,133.0>--<721.0,100.0>>

	* uni04FC (U+04FC): L<<562.0,23.0>--<543.0,48.0>> -> L<<543.0,48.0>--<415.0,220.0>>

	* uni04FD (U+04FD): L<<374.0,-5.0>--<365.0,9.0>> -> L<<365.0,9.0>--<286.0,130.0>>

	* uni04FD (U+04FD): L<<388.0,258.0>--<494.0,96.0>> -> L<<494.0,96.0>--<506.0,76.0>>

	* uni051B (U+051B): L<<472.0,-216.0>--<485.0,-24.0>> -> L<<485.0,-24.0>--<494.0,37.0>>

	* uni1E0D (U+1E0D): L<<526.0,474.0>--<526.0,544.0>> -> L<<526.0,544.0>--<539.0,736.0>>

	* uni2206 (U+2206): L<<519.0,720.0>--<936.0,2.0>> -> L<<936.0,2.0>--<937.0,0.0>>

	* uniA78B (U+A78B): L<<206.0,731.0>--<183.0,409.0>> -> L<<183.0,409.0>--<163.0,196.0>>

	* uniA78B (U+A78B): L<<23.0,196.0>--<33.0,409.0>> -> L<<33.0,409.0>--<56.0,731.0>>

	* uniA78C (U+A78C): L<<188.0,730.0>--<173.0,520.0>> -> L<<173.0,520.0>--<160.0,409.0>> 

	* uniA78C (U+A78C): L<<38.0,409.0>--<41.0,520.0>> -> L<<41.0,520.0>--<56.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] NonBureau-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni042A	Contours detected: 3	Expected: 2

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<143.0,736.0>--<128.0,525.0>> -> L<<128.0,525.0>--<117.0,441.0>>

	* beta (U+03B2): L<<94.0,81.0>--<94.0,-1.0>> -> L<<94.0,-1.0>--<77.0,-217.0>>

	* d (U+0064): L<<433.0,439.0>--<433.0,525.0>> -> L<<433.0,525.0>--<448.0,736.0>>

	* dcaron (U+010F): L<<433.0,439.0>--<433.0,525.0>> -> L<<433.0,525.0>--<448.0,736.0>>

	* dcroat (U+0111): L<<433.0,439.0>--<433.0,525.0>> -> L<<433.0,525.0>--<440.0,614.0>>

	* dmacronbelow (U+1E0F): L<<433.0,439.0>--<433.0,525.0>> -> L<<433.0,525.0>--<448.0,736.0>>

	* f_f (U+FB00): L<<217.0,520.0>--<338.0,520.0>> -> L<<338.0,520.0>--<423.0,518.0>>

	* f_f_i (U+FB03): L<<217.0,520.0>--<305.0,520.0>> -> L<<305.0,520.0>--<389.0,518.0>>

	* hbar (U+0127): L<<229.0,614.0>--<222.0,525.0>> -> L<<222.0,525.0>--<206.0,435.0>>

	* p (U+0070): L<<92.0,81.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* q (U+0071): L<<382.0,-216.0>--<397.0,-5.0>> -> L<<397.0,-5.0>--<407.0,81.0>>

	* raisedmcsign (U+1F16A): L<<108.0,714.0>--<210.0,492.0>> -> L<<210.0,492.0>--<223.0,461.0>>

	* raisedmcsign (U+1F16A): L<<213.0,359.0>--<112.0,604.0>> -> L<<112.0,604.0>--<102.0,630.0>>

	* raisedmcsign (U+1F16A): L<<367.0,359.0>--<367.0,604.0>> -> L<<367.0,604.0>--<366.0,630.0>>

	* rho (U+03C1): L<<92.0,81.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* slash (U+002F): L<<283.0,714.0>--<282.0,710.0>> -> L<<282.0,710.0>--<20.0,-130.0>>

	* tau (U+03C4): L<<143.0,518.0>--<216.0,520.0>> -> L<<216.0,520.0>--<345.0,520.0>>

	* tau (U+03C4): L<<53.0,523.0>--<143.0,518.0>> -> L<<143.0,518.0>--<216.0,520.0>>

	* thorn (U+00FE): L<<92.0,81.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* trademark (U+2122): L<<423.0,714.0>--<525.0,492.0>> -> L<<525.0,492.0>--<538.0,461.0>>

	* trademark (U+2122): L<<527.0,359.0>--<427.0,604.0>> -> L<<427.0,604.0>--<416.0,630.0>>

	* trademark (U+2122): L<<681.0,359.0>--<681.0,604.0>> -> L<<681.0,604.0>--<681.0,630.0>>

	* uni0335 (U+0335): L<<120.0,285.0>--<186.0,287.0>> -> L<<186.0,287.0>--<266.0,287.0>>

	* uni0335 (U+0335): L<<39.0,290.0>--<120.0,285.0>> -> L<<120.0,285.0>--<186.0,287.0>>

	* uni0440 (U+0440): L<<92.0,81.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* uni0447 (U+0447): L<<319.0,0.0>--<331.0,178.0>> -> L<<331.0,178.0>--<342.0,250.0>>

	* uni0452 (U+0452): L<<220.0,583.0>--<213.0,483.0>> -> L<<213.0,483.0>--<200.0,395.0>>

	* uni045B (U+045B): L<<220.0,583.0>--<213.0,483.0>> -> L<<213.0,483.0>--<200.0,395.0>>

	* uni0463 (U+0463): L<<215.0,568.0>--<208.0,462.0>> -> L<<208.0,462.0>--<198.0,391.0>>

	* uni048F (U+048F): L<<92.0,81.0>--<91.0,-5.0>> -> L<<91.0,-5.0>--<77.0,-216.0>>

	* uni04B7 (U+04B7): L<<319.0,0.0>--<331.0,178.0>> -> L<<331.0,178.0>--<342.0,250.0>>

	* uni04B9 (U+04B9): L<<326.0,0.0>--<338.0,178.0>> -> L<<338.0,178.0>--<348.0,250.0>>

	* uni04CC (U+04CC): L<<325.0,60.0>--<333.0,178.0>> -> L<<333.0,178.0>--<343.0,250.0>>

	* uni04CD (U+04CD): L<<135.0,548.0>--<130.0,494.0>> -> L<<130.0,494.0>--<60.0,0.0>>

	* uni04CD (U+04CD): L<<367.0,109.0>--<405.0,185.0>> -> L<<405.0,185.0>--<705.0,714.0>>

	* uni04CD (U+04CD): L<<665.0,548.0>--<638.0,494.0>> -> L<<638.0,494.0>--<370.0,0.0>>

	* uni04F5 (U+04F5): L<<319.0,0.0>--<331.0,178.0>> -> L<<331.0,178.0>--<342.0,250.0>>

	* uni04FC (U+04FC): L<<371.0,357.0>--<585.0,27.0>> -> L<<585.0,27.0>--<605.0,-5.0>>

	* uni04FC (U+04FC): L<<536.0,-31.0>--<509.0,11.0>> -> L<<509.0,11.0>--<323.0,297.0>>

	* uni04FD (U+04FD): L<<287.0,260.0>--<444.0,19.0>> -> L<<444.0,19.0>--<450.0,9.0>>

	* uni04FD (U+04FD): L<<399.0,-37.0>--<374.0,2.0>> -> L<<374.0,2.0>--<243.0,203.0>>

	* uni051B (U+051B): L<<382.0,-216.0>--<397.0,-5.0>> -> L<<397.0,-5.0>--<407.0,81.0>>

	* uni1E0D (U+1E0D): L<<433.0,439.0>--<433.0,525.0>> -> L<<433.0,525.0>--<448.0,736.0>>

	* uniA78B (U+A78B): L<<140.0,731.0>--<117.0,409.0>> -> L<<117.0,409.0>--<97.0,196.0>>

	* uniA78B (U+A78B): L<<37.0,196.0>--<47.0,409.0>> -> L<<47.0,409.0>--<70.0,731.0>>

	* uniA78C (U+A78C): L<<128.0,730.0>--<113.0,520.0>> -> L<<113.0,520.0>--<100.0,409.0>>

	* uniA78C (U+A78C): L<<52.0,409.0>--<55.0,520.0>> -> L<<55.0,520.0>--<70.0,730.0>> 

	* zeta (U+03B6): L<<411.0,562.0>--<409.0,527.0>> -> L<<409.0,527.0>--<408.0,500.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NonBureauExtended-RegularItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Non Bureau Extended Regular | Non Bureau Extended |
| Subfamily Name | Italic | Italic |
| Full Name | Non Bureau Extended Regular Italic | Non Bureau Extended Italic |
| Poscript Name | NonBureauExtended-RegularItalic | NonBureauExtended-Italic |
| Typographic Family Name | Non Bureau Extended | N/A |
| Typographic Subfamily Name | Regular Italic | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0313

	- uni0315

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni0331 

	- uni0332 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ j̦̒ j̦̓ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Non Bureau Extended Regular' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- FaceHeathEyes

	- FaceTongue

	- GrinningFace

	- SlightlySmilingFace

	- SmilingFaceWithSunglasses

	- StarStruck

	- WinkFace

	- dotlessi_ogonek 

	- i.loclTRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20A8	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni20AD	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 18	Expected: 16 or 12 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ae (U+00E6): L<<1099.0,257.0>--<749.0,242.0>> -> L<<749.0,242.0>--<594.0,232.0>>

	* aeacute (U+01FD): L<<1099.0,257.0>--<749.0,242.0>> -> L<<749.0,242.0>--<594.0,232.0>>

	* b (U+0062): L<<164.0,736.0>--<150.0,530.0>> -> L<<150.0,530.0>--<139.0,440.0>>

	* beta (U+03B2): L<<116.0,86.0>--<115.0,-1.0>> -> L<<115.0,-1.0>--<98.0,-217.0>>

	* d (U+0064): L<<555.0,436.0>--<557.0,530.0>> -> L<<557.0,530.0>--<571.0,736.0>>

	* dcaron (U+010F): L<<555.0,436.0>--<557.0,530.0>> -> L<<557.0,530.0>--<571.0,736.0>>

	* dcroat (U+0111): L<<555.0,437.0>--<558.0,530.0>> -> L<<558.0,530.0>--<563.0,608.0>>

	* dmacronbelow (U+1E0F): L<<555.0,436.0>--<557.0,530.0>> -> L<<557.0,530.0>--<571.0,736.0>>

	* f_f (U+FB00): L<<236.0,520.0>--<376.0,520.0>> -> L<<376.0,520.0>--<463.0,518.0>>

	* f_f_i (U+FB03): L<<236.0,520.0>--<376.0,520.0>> -> L<<376.0,520.0>--<463.0,518.0>>

	* f_t (U+FB05): L<<236.0,520.0>--<351.0,520.0>> -> L<<351.0,520.0>--<452.0,518.0>>

	* oe (U+0153): L<<1192.0,257.0>--<842.0,242.0>> -> L<<842.0,242.0>--<687.0,232.0>>

	* p (U+0070): L<<113.0,80.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* q (U+0071): L<<505.0,-216.0>--<519.0,-10.0>> -> L<<519.0,-10.0>--<530.0,79.0>>

	* rho (U+03C1): L<<113.0,80.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* slash (U+002F): L<<317.0,714.0>--<316.0,710.0>> -> L<<316.0,710.0>--<54.0,-130.0>>

	* tau (U+03C4): L<<134.0,518.0>--<232.0,520.0>> -> L<<232.0,520.0>--<396.0,520.0>>

	* tau (U+03C4): L<<48.0,523.0>--<134.0,518.0>> -> L<<134.0,518.0>--<232.0,520.0>>

	* thorn (U+00FE): L<<113.0,80.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* trademark (U+2122): L<<591.0,359.0>--<483.0,562.0>> -> L<<483.0,562.0>--<460.0,617.0>>

	* uni0335 (U+0335): L<<128.0,291.0>--<219.0,293.0>> -> L<<219.0,293.0>--<301.0,293.0>>

	* uni0335 (U+0335): L<<46.0,296.0>--<128.0,291.0>> -> L<<128.0,291.0>--<219.0,293.0>>

	* uni03BC (U+03BC): L<<114.0,67.0>--<115.0,5.0>> -> L<<115.0,5.0>--<98.0,-217.0>>

	* uni0440 (U+0440): L<<113.0,80.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* uni0447 (U+0447): L<<452.0,0.0>--<463.0,174.0>> -> L<<463.0,174.0>--<474.0,248.0>>

	* uni0463 (U+0463): L<<227.0,555.0>--<220.0,464.0>> -> L<<220.0,464.0>--<210.0,400.0>>

	* uni048F (U+048F): L<<113.0,80.0>--<112.0,-10.0>> -> L<<112.0,-10.0>--<98.0,-216.0>>

	* uni04B7 (U+04B7): L<<452.0,0.0>--<463.0,174.0>> -> L<<463.0,174.0>--<474.0,248.0>>

	* uni04B9 (U+04B9): L<<452.0,0.0>--<463.0,174.0>> -> L<<463.0,174.0>--<474.0,248.0>>

	* uni04CC (U+04CC): L<<460.0,78.0>--<467.0,183.0>> -> L<<467.0,183.0>--<477.0,247.0>>

	* uni04CD (U+04CD): L<<762.0,-67.0>--<757.0,0.0>> -> L<<757.0,0.0>--<742.0,108.0>>

	* uni04CD (U+04CD): L<<770.0,516.0>--<702.0,409.0>> -> L<<702.0,409.0>--<421.0,0.0>>

	* uni04CD (U+04CD): L<<875.0,532.0>--<887.0,88.0>> -> L<<887.0,88.0>--<898.0,-1.0>>

	* uni04D5 (U+04D5): L<<1099.0,257.0>--<749.0,242.0>> -> L<<749.0,242.0>--<594.0,232.0>>

	* uni04F5 (U+04F5): L<<452.0,0.0>--<463.0,174.0>> -> L<<463.0,174.0>--<474.0,248.0>>

	* uni04FC (U+04FC): L<<454.0,356.0>--<688.0,53.0>> -> L<<688.0,53.0>--<713.0,22.0>>

	* uni04FC (U+04FC): L<<614.0,-18.0>--<586.0,19.0>> -> L<<586.0,19.0>--<385.0,278.0>>

	* uni04FD (U+04FD): L<<312.0,259.0>--<456.0,38.0>> -> L<<456.0,38.0>--<464.0,26.0>>

	* uni04FD (U+04FD): L<<393.0,-29.0>--<372.0,4.0>> -> L<<372.0,4.0>--<254.0,185.0>>

	* uni051B (U+051B): L<<505.0,-216.0>--<519.0,-10.0>> -> L<<519.0,-10.0>--<530.0,80.0>>

	* uni1E0D (U+1E0D): L<<555.0,436.0>--<557.0,530.0>> -> L<<557.0,530.0>--<571.0,736.0>>

	* uni2206 (U+2206): L<<484.0,720.0>--<866.0,2.0>> -> L<<866.0,2.0>--<867.0,0.0>>

	* uniA78B (U+A78B): L<<156.0,731.0>--<133.0,409.0>> -> L<<133.0,409.0>--<113.0,196.0>>

	* uniA78B (U+A78B): L<<33.0,196.0>--<43.0,409.0>> -> L<<43.0,409.0>--<66.0,731.0>>

	* uniA78C (U+A78C): L<<143.0,730.0>--<128.0,520.0>> -> L<<128.0,520.0>--<115.0,409.0>> 

	* uniA78C (U+A78C): L<<48.0,409.0>--<51.0,520.0>> -> L<<51.0,520.0>--<66.0,730.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 80 | 283 | 3290 | 169 | 2607 | 0 |
| 0% | 1% | 4% | 51% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
