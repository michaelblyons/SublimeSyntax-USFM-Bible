# USFM Bible Format in Sublime Text

This project is a simple syntax definition
for [United Scripture Format Markup][usfm-intro]
(specifically USFM-FM)
for use in [Sublime Text][st].

It is not comprehensive by any means,
but there are GOTO references
for chapters and section headings,
as well as some citation markers.

Help is joyfully welcomed.

## Building

This syntax project is in [SBNF][] format,
which compiles to ST's `sublime-syntax` YAML.
To build, you will need the SBNF compiler,
available as

- The SBNF package in ST Package Control.
- Compiled executables on GitHub.
- `cargo install sbnfc`.


[usfm-intro]: https://docs.usfm.bible/usfm/3.1.1/introduction.html
[st]: https://www.sublimetext.com
[sbnf]: https://github.com/BenjaminSchaaf/sbnf
