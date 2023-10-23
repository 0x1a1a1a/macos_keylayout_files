## Custom .keylayout files for English and Ukrainian (to use with 42–keys keyboards)

### Release notes

#### v2.1

* Fixed a small bug with a letter `Й`
* Initiated a `readme.md` file

#### v2

* Organized the file as a table with `keycodes`, keycode names and an their aliases in QMK

#### v1

* Initiated custom .keylayout files with comments to each `keycode`

----

### Resources

* [Technical Note TN2056: Installable Keyboard Layouts by Apple](https://developer.apple.com/library/archive/technotes/tn2056/_index.html): a very old but only existing document from Apple regarding Keyboard Layouts structure

* [Compart: Unicode](https://www.compart.com/en/unicode/): a good place to find correct names and codes of Unicode symbols

----

### Insights

* `rightShift`, `rightOption`, `rightControl` modifiers are actually not functioning, every such modifier is a `left` modifier. Because of that, `anyShift`, `anyOption` and `anyControl` modifiers also make no sense