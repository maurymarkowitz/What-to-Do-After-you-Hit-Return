# What To Do After You Hit Return

"What to Do After you Hit Return" is a collection of computer games first published by the People's Computer Company (PCC) in 1975. Many of these games would re-appear in MS-BASIC versions in the much more famous "101 BASIC Games" and "BASIC Computer Games".

The versions in this repository were written in HP-BASIC, for the then-popular HP2000 systems. This makes the source somewhat harder to convert to "modern vintage" systems based on MS-derived BASICs like those found on the Apple II or Commodore line. A 1978 edition was published for MS-BASIC, but I have not found a copy of that release.

HP-BASIC had a few quirks, like using `#` for not-equals, in addition to `<>`, and that all arrays can be defined using either square or round brakets. However the main difference and point of interest is its handling of strings, which was more like FORTRAN's "array of characters". All strings must be DIMmed, and the MS-style `LEFT/MID/RIGHT` are replaced by a "slicing" system using array notation - to get the first five characters of a string you would use `A$[1,6]`. Be careful of off-by-ones when converting to and from MS-style, `A$[1,6]` is the equivalent of `LEFT(A$,5)`.

These listings have been hand-converted from a [copy of the book on Archive.org](https://archive.org/details/Whattodoafteryouhitreturn). The listings were originally printed on a dot-matrix printer and the scanning quality is highly variable, so in some cases best-guesses have been made in the case of variable names and a few numeric constants. The difference betweem round and square braketting is almost indistinguishable in the listings, so for clarity, in these conversions all slicing commands use square and everything else uses round.
