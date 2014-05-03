
CHANGES
=======

2.0.0
-----

- removed SVGZ format from Web fonts because SVGZ is really only
  needed for very ancient mobile devices and hence not worth the
  distribution extra space.

- removed HTML specimen files from Web fonts and replace them with a
  generic specimen.html at the top-level because this further reduces the
  redundancy and this way the distribution size.

- migrated from a generated index.html to a generic one which
  now loads a manifest.js (similar to the new specimen.html).

- fixed manifest: use the regular 'condensed' stretch value for 
  H.H. Samuel and not 'ultra-condensed'.

1.4.2
-----

- added fonts

1.4.1
-----

- ignore .git
- split Chrome for mobile
- add browser support information and polish some texts
- update cloud image
- add Ostrich Sans (Rounded) Heavy and Comic Relief
- add Alegreya, Comic Neue and Cuprum font families
- add more font directory references

1.4.0
-----

- add Webly Sleek, Ostrich Sans, Delius, To Be Continued and Comme fonts
- regenerate everything to benefit from latest fontface(1) improvements
- fix ordering
- split kerning and hinting descriptions
- improve markup
- better describe why hinting is required
- move format description into feature section
- add logo
- reduce the description to just one Manifest section
- fix description of directory layout
- provide hint how to download particular version
- provide hint how to download particular version
- improve documentation
- add cloud image

1.3.0
-----

- add Dosis, Junction, Lobster Two and Raleway
- fix Small-Caps variants by using an explicit name
- apply auto-hinting via ttfautohint

1.2.0
-----

- reconvert all files and reindex all fonts
- add links to the specimen
- better describe the distribution
- cleanup README text
- fix indentations
- add Aileron, Crimson, LatinModern, TeX Gyre, Nautilus Pompelius and EB Garamond

1.1.0
-----

- fix font ordering
- fix information about Droid
- add Dancing Script and Pompiere fonts
- add Libre Baskerville and Merriweather fonts
- provide some more font descriptions

1.0.0
-----

- add Aleo, Bitter, Courier Prime, Crete Round, Ostrich Sans and Oxygen fonts

0.9.8
-----

- regenerated all fonts with latest fontface tool

0.9.7
-----

- add Cabin, Courgette and Poetsen fonts

0.9.6
-----

- provide new DTP formats
- update Web formats and mix blurb/license files together
- rename dtp/ to src/ and generate a new special DTP set of fonts
- use non-breaking spaces
- use the name with spaces
- regenerate all fonts after addition of Fira Sans and Fira Mono
- add excellent Fira Sans and Fira Mono fonts from Mozilla

0.9.5
-----

- add missing extractions
- rename Source Sans Pro italics
- regenerate all fonts with the updated fontface tool
- add my personal font recommendation to README
- force Neuton Regular variants to be of 'normal' weight
- improve documentation

0.9.4
-----

- regenerated all fonts
- add missing license file
- add Amble, Anonymous Pro, Ubuntu and Vollkorn fonts
- add missing OFL license information
- install license.txt and blurb.txt files also in web/ areas

0.9.3
-----

- major extension with more special purpose fonts
- bugfix weight handling in manifest

0.9.2
-----

- cleanup distribution

0.9.1
-----

- regenerate the fonts with the new parameter adjustments
- support font parameter overriding
- add a top-level convenience Makefile
- add index and corresponding generator

0.9.0
-----

- *genesis*
