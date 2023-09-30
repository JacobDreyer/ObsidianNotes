Uses 32 bit namespace
- theoretical size of ~4 billion
- Only 1,114,112 are allowed
- As of May [[2020]] has 143,859 characters
- Covers 154 modern and historic scripts
- Code Point 0 through 127 coincide with [[ASCII]]
Assigns a unique number to each character
- Called a "[[Code Point]]" and depicted with U+xxxx in [[Hexadecimal Notation]]
- Fonts handle pictorial representation of each code point
### Unicode Character Encoding
- A character encoding interprets a sequence of bytes as a code point
- The bytes are first parsed into [[Code Unit]]s
- Code units have a fixed length
- One or more code units may be required to denote a code point
- Examples are [[UTF-8]], [[UTF-16]], [[UTF-32]]
##### [[UTF-8]]
![[UTF-8]]
##### [[UTF-16]]
![[UTF-16]]
##### [[Byte Order]]
![[Byte Order]]
### [[Unicode in Java]]
![[Unicode in Java]]
#### Subsets of Unicode
[[ASCII]] code is a subset of Unicode

#### How to Input Unicode
- Needs software support for
	- [[Localization]] ([[l10n]]) - Translating a product to one or more languages
	- Multilingualization ([[m17n]]) - libraries for handling multiple languages
	- Internationalization ([[i18n]]) - adding support for handling languages
- Input Methods
	- Allows entering characters not found on the input device 