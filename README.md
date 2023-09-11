# match_parens
|     key | description
|     ---:|:---
|  script | match_parens - find mismatches of various brackets and quotes
|    type | ruby
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 1.45
| license | GNU General Public License

Mismatches of parentheses, braces, (angle) brackets, especially in TeX
sources which may be rich in those, may be difficult to trace. This little
script helps you by writing your text to standard output, after adding a
left margin to your text, which will normally be almost empty, but will
clearly show up to 10 mismatches. (Just try me on myself to see that the
parenthesis starting this sentence will not appear to be matched at the end
of the file. If you look at me in the vim editor, then select this
paragraph and try the command: :!%.
