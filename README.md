# Gelasio

[![][Fontbakery]](https://SorkinType.github.io/Gelasio/fontbakery/fontbakery-report.html)
[![][Universal]](https://SorkinType.github.io/Gelasio/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://SorkinType.github.io/Gelasio/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://SorkinType.github.io/Gelasio/fontbakery/fontbakery-report.html)
[![][Shaping]](https://SorkinType.github.io/Gelasio/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FGelasio%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FGelasio%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FGelasio%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FGelasio%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FGelasio%2Fgh-pages%2Fbadges%2FUniversal.json

Gelasio is an original typeface which is metrics compatible with Georgia in its Regular, Bold, Italic and Bold Italic weights. Medium, Medium Italic, SemiBold and SemiBold Italic have now been added as well but these don't have equivalents in Georgia.

Gelasio supports Google Fonts Latin Pro glyph set, enabling the typesetting of English, Western, Eastern and Southern European languages as well as Vietnamese and 130+ other languages.

Notes:

• This design will retain the purpose of being metrics compatible with Georgia in Regular and Bold weights while expanding somewhat past what Georgia can do in some areas such as having case sensitive punctuation and a few more numbers styles.

• However to remain a fuctional match to Georgia, Gelasio will not include kerning.

• The new Georgia found in Windows 10 ( in 2018 ) has some features and glyphs not present in Gelasio such as support for Greek and Cyrillic, Small caps for all three scripts and some additional symbols, and box drawing glyphs. Later I hope to make Gelsio fully equivalent in these ways as well.

•  I also hope to make a font based on this work with a new name that is
 - not metrics compatible with Georgia
 - is a variable font
 - has kerning
 - is tuned to contemporary screen use rather than the relatively low resoution (72 dpi and 96 dpi) screens typical of mid-90s.

![Sample Image](documentation/image1.png)

## About

The project is being made by Eben Sorkin @ Sorkin Type
Viviana Monsalve was also a contributor.
To contribute ideas and feedback, see [https://github.com/EbenSorkin/Gelasio](https://github.com/EbenSorkin/Gelasio)

## Languages

==============================================
According to Hyperglot made by Rosetta Type the Pinyon Script has base support for 326 of the 459 languages of Latin script. These include:

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://SorkinType.github.io/Gelasio.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**10 May 2022. Version 1.007**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Language support.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
