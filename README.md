
# Belanosima

Belanosima is a DocRepair font, intended to improve compliance with the ISO/IEC 29500 standard by providing fallback that minimizes text reflow in Office Open XML documents. Belanosima is based on Josefin Sans, a geometric, elegant family with a vintage feeling, for use at larger sizes. Josefin Sans is inspired by geometric sans serif designs from the 1920s. 

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://docrepair-fonts.github.io/belanosima-fonts.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**30 March 2023**

- MAJOR Initial build

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
