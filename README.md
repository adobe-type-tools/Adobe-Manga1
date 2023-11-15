[English](https://github.com/adobe-type-tools/Adobe-Manga1/)

# The Adobe-Manga1-0 Character Collection

## Introduction

The purpose of this document is to define and describe the *Adobe-Manga1-0* character collection, which enumerates 18,032 glyphs, and whose designation is derived from the following three /CIDSystemInfo dictionary entries:

* /Registry (Adobe)
* /Ordering (Manga1)
* /Supplement 0

CIDFont resources that reference this character collection must include a /CIDSystemInfo dictionary that matches the /Registry and /Ordering strings shown above.

This document is designed for font developers, for the purpose of developing OpenType/CFF Japanese fonts meant for use in manga. It is also useful for application developers and end users who need to know more about the glyphs in this character collection. This document expects that its readers are familiar with the CID-keyed font file format, which is described in [Adobe Technical Note #5014](https://adobe-type-tools.github.io/font-tech-notes/pdfs/5014.CIDFont_Spec.pdf), entitled *Adobe CMap and CIDFont Files Specification*.

A character collection contains the glyphs that are required to develop font products for a specific language, script, or market. Specific encodings are defined through the use of CMap resources that are instantiated as files, and generally reference a subset of the character collection.

The character collection that results from each Supplement includes the glyphs associated with all earlier Supplements. 

The Adobe-Manga1-0 character collection enumerates 18,032 glyphs, specifically CIDs 0 through 18031. Adobe-Manga1-0 is based on a subset of [Source Han Sans JP 2.004](https://github.com/adobe-fonts/source-han-sans/releases/tag/2.004R) with additional manga-specific glyphs. The additional glyphs are a mix of both Sans and Serif styles. The following table summarizes, and also provides the pages on which their glyphs are shown in the [*Adobe-Manga1-0.pdf*](https://github.com/adobe-type-tools/Adobe-Manga1/raw/main/Adobe-Manga1-0.pdf) file:

**Supplement** | **Additional CIDs** | **CID Range** | **Total CIDs** | **Date of Establishment** | **Pages**
--- | --- | --- | --- | --- | ---
0 | 18,032 | 0-18031 | 18,032 | 2023 | 1–37

Each CID (*Character ID*) in a character collection is associated with a glyph in which a set of character shape variations is abstracted. Specific shapes included in the set are dependent on the typeface style and possibly other factors. Glyphs for all CIDs are illustrated in this document, providing a specific example or instance of the correspondence between a CID and its glyph. Font developers should design glyphs for each CID of the character collection, and may use this document as a reference when proofing or otherwise validating CIDFont resources.

The following sections detail the history and contents of each Supplement of the Adobe-Manga1-0 character collection.

---
## Supplement 0—Adobe-Manga1-0

Supplement 0, which enumerates 18,032 glyphs, specifically CIDs 0 through 18031, was designed to be used in Japanese manga production. 

---
## Special Glyphs & Other Notes

The following sections detail special glyphs and other notes that are of interest to font developers. Several glyph classes are complex, and deserve some amount of explanation and clarification.

### Dakuten and Handakuten Kana Glyphs

Adobe-Mang1-0 specifies a set of dakuten and handakuten precomposed glyphs:


### Dakuten (濁点)
**Horizontal CID** | **Vertical CID** | **Unicode Code Points** | **Characters** 
--- | --- | --- | ---
1418 | | <3042 3099> | あ゙
1419 | 1882 | <3041 3099> | ぁ゙
1420 | | <3044 3099> | い゙
1421 | 1883 | <3043 3099> | ぃ゙
1422 | 1884 | <3045 3099> | ぅ゙
1423 | | <3048 3099> | え゙
1424 | 1885 | <3047 3099> | ぇ゙
1425 | | <304A 3099> | お゙
1426 | 1886 | <3049 3099> | ぉ゙
1427 | 1887 | <3095 3099> | ゕ゙
1428 | 1888 | <3096 3099> | ゖ゙
1429 | 1889 | <1B132 3099> | 𛄲゙
1430 | 1890 | <3063 3099> | っ゙
1431 | | <306A 3099> | な゙
1432 | | <306B 3099> | に゙
1433 | | <306C 3099> | ぬ゙
1434 | | <306D 3099> | ね゙
1435 | | <306E 3099> | の゙
1436 | | <307E 3099> | ま゙
1437 | | <307F 3099> | み゙
1438 | | <3080 3099> | む゙
1439 | | <3081 3099> | め゙
1440 | | <3082 3099> | も゙
1441 | | <3084 3099> | や゙
1442 | 1891 | <3083 3099> | ゃ゙
1443 | | <3086 3099> | ゆ゙
1444 | 1892 | <3085 3099> | ゅ゙
1445 | | <3088 3099> | よ゙
1446 | 1893 | <3087 3099> | ょ゙
1447 | | <3089 3099> | ら゙
1448 | | <308A 3099> | り゙
1449 | | <308B 3099> | る゙
1450 | | <308C 3099> | れ゙
1451 | | <308D 3099> | ろ゙
1452 | | <308F 3099> | わ゙
1453 | 1894 | <308E 3099> | ゎ゙
1454 | | <3090 3099> | ゐ゙
1455 | | <3091 3099> | ゑ゙
1456 | | <3092 3099> | を゙
1457 | | <3093 3099> | ん゙
1458 | | <309F 3099> | ゟ゙
1459 | | <30A2 3099> | ア゙
1460 | 1895 | <30A1 3099> | ァ゙
1461 | | <30A4 3099> | イ゙
1462 | 1896 | <30A3 3099> | ィ゙
1463 | 1897 | <30A5 3099> | ゥ゙
1464 | | <30A8 3099> | エ゙
1465 | 1898 | <30A7 3099> | ェ゙
1466 | | <30AA 3099> | オ゙
1467 | 1899 | <30A9 3099> | ォ゙
1468 | 1900 | <30F5 3099> | ヵ゙
1469 | 1901 | <30F6 3099> | ヶ゙
1470 | 1902 | <1B155 3099> | 𛅕゙
1471 | 1903 | <30C3 3099> | ッ゙
1472 | | <30CA 3099> | ナ゙
1473 | | <30CB 3099> | ニ゙
1474 | | <30CC 3099> | ヌ゙
1475 | | <30CD 3099> | ネ゙
1476 | | <30CE 3099> | ノ゙
1477 | | <30DE 3099> | マ゙
1478 | | <30DF 3099> | ミ゙
1479 | | <30E0 3099> | ム゙
1480 | | <30E1 3099> | メ゙
1481 | | <30E2 3099> | モ゙
1482 | | <30E4 3099> | ヤ゙
1483 | 1904 | <30E3 3099> | ャ゙
1484 | | <30E6 3099> | ユ゙
1485 | 1905 | <30E5 3099> | ュ゙
1486 | | <30E8 3099> | ヨ゙
1487 | 1906 | <30E7 3099> | ョ゙
1488 | | <30E9 3099> | ラ゙
1489 | | <30EA 3099> | リ゙
1490 | | <30EB 3099> | ル゙
1491 | | <30EC 3099> | レ゙
1492 | | <30ED 3099> | ロ゙
1493 | 1907 | <30EE 3099> | ヮ゙
1494 | | <30F3 3099> | ン゙

### Handakuten (半濁点)
**Horizontal CID** | **Vertical CID** | **Unicode Code Points** | **Characters** 
--- | --- | --- | ---
1401 | | <304B 309A> | か゚
1402 | | <304D 309A> | き゚
1403 | | <304F 309A> | く゚
1404 | | <3051 309A> | け゚
1405 | | <3053 309A> | こ゚
1406 | | <30AB 309A> | カ゚
1407 | | <30AD 309A> | キ゚
1408 | | <30AF 309A> | ク゚
1409 | | <30B1 309A> | ケ゚
1410 | | <30B3 309A> | コ゚
1411 | | <30BB 309A> | セ゚
1412 | | <30C4 309A> | ツ゚
1413 | | <30C8 309A> | ト゚
1414 | 1869 | <31F7 309A> | ㇷ゚
1495 | | <3042 309A> | あ゚
1496 | 1908 | <3041 309A> | ぁ゚
1497 | | <3044 309A> | い゚
1498 | 1909 | <3043 309A> | ぃ゚
1499 | | <3046 309A> | う゚
1500 | 1910 | <3045 309A> | ぅ゚
1501 | | <3048 309A> | え゚
1502 | 1911 | <3047 309A> | ぇ゚
1503 | | <304A 309A> | お゚
1504 | 1912 | <3049 309A> | ぉ゚
1505 | 1913 | <3095 309A> | ゕ゚
1506 | 1914 | <3096 309A> | ゖ゚
1507 | 1915 | <1B132 309A> | 𛄲゚
1508 | | <3055 309A> | さ゚
1509 | | <3057 309A> | し゚
1510 | | <3059 309A> | す゚
1511 | | <305B 309A> | せ゚
1512 | | <305D 309A> | そ゚
1513 | | <305F 309A> | た゚
1514 | | <3061 309A> | ち゚
1515 | | <3064 309A> | つ゚
1516 | 1916 | <3063 309A> | っ゚
1517 | | <3066 309A> | て゚
1518 | | <3068 309A> | と゚
1519 | | <306A 309A> | な゚
1520 | | <306B 309A> | に゚
1521 | | <306C 309A> | ぬ゚
1522 | | <306D 309A> | ね゚
1523 | | <306E 309A> | の゚
1524 | | <307E 309A> | ま゚
1525 | | <307F 309A> | み゚
1526 | | <3080 309A> | む゚
1527 | | <3081 309A> | め゚
1528 | | <3082 309A> | も゚
1529 | | <3084 309A> | や゚
1530 | 1917 | <3083 309A> | ゃ゚
1531 | | <3086 309A> | ゆ゚
1532 | 1918 | <3085 309A> | ゅ゚
1533 | | <3088 309A> | よ゚
1534 | 1919 | <3087 309A> | ょ゚
1535 | | <3089 309A> | ら゚
1536 | | <308A 309A> | り゚
1537 | | <308B 309A> | る゚
1538 | | <308C 309A> | れ゚
1539 | | <308D 309A> | ろ゚
1540 | | <308F 309A> | わ゚
1541 | 1920 | <308E 309A> | ゎ゚
1542 | | <3090 309A> | ゐ゚
1543 | | <3091 309A> | ゑ゚
1544 | | <3092 309A> | を゚
1545 | | <3093 309A> | ん゚
1546 | | <309F 309A> | ゟ゚
1547 | | <30A2 309A> | ア゚
1548 | 1921 | <30A1 309A> | ァ゚
1549 | | <30A4 309A> | イ゚
1550 | 1922 | <30A3 309A> | ィ゚
1551 | | <30A6 309A> | ウ゚
1552 | 1923 | <30A5 309A> | ゥ゚
1553 | | <30A8 309A> | エ゚
1554 | 1924 | <30A7 309A> | ェ゚
1555 | | <30AA 309A> | オ゚
1556 | 1925 | <30A9 309A> | ォ゚
1557 | 1926 | <30F5 309A> | ヵ゚
1558 | 1927 | <30F6 309A> | ヶ゚
1559 | 1928 | <1B155 309A> | 𛅕゚
1560 | | <30B5 309A> | サ゚
1561 | | <30B7 309A> | シ゚
1562 | | <30B9 309A> | ス゚
1563 | | <30BD 309A> | ソ゚
1564 | | <30BF 309A> | タ゚
1565 | | <30C1 309A> | チ゚
1566 | 1929 | <30C3 309A> | ッ゚
1567 | | <30C6 309A> | テ゚
1568 | | <30CA 309A> | ナ゚
1569 | | <30CB 309A> | ニ゚
1570 | | <30CC 309A> | ヌ゚
1571 | | <30CD 309A> | ネ゚
1572 | | <30CE 309A> | ノ゚
1573 | | <30DE 309A> | マ゚
1574 | | <30DF 309A> | ミ゚
1575 | | <30E0 309A> | ム゚
1576 | | <30E1 309A> | メ゚
1577 | | <30E2 309A> | モ゚
1578 | | <30E4 309A> | ヤ゚
1579 | 1930 | <30E3 309A> | ャ゚
1580 | | <30E6 309A> | ユ゚
1581 | 1931 | <30E5 309A> | ュ゚
1582 | | <30E8 309A> | ヨ゚
1583 | 1932 | <30E7 309A> | ョ゚
1584 | | <30E9 309A> | ラ゚
1585 | | <30EA 309A> | リ゚
1586 | | <30EB 309A> | ル゚
1587 | | <30EC 309A> | レ゚
1588 | | <30ED 309A> | ロ゚
1589 | | <30EF 309A> | ワ゚
1590 | 1933 | <30EE 309A> | ヮ゚
1591 | | <30F0 309A> | ヰ゚
1592 | | <30F1 309A> | ヱ゚
1593 | | <30F2 309A> | ヲ゚
1594 | | <30F3 309A> | ン゚

### Handakuten Ruby (半濁点のルビ)
**Horizontal CID** | **Vertical CID** | **Unicode Code Points** | **Characters** 
--- | --- | --- | ---
1748 | 1959 | <31F7 309A> | ㇷ゚
1790 | | <304B 309A> | か゚
1791 | | <304D 309A> | き゚
1792 | | <304F 309A> | く゚
1793 | | <3051 309A> | け゚
1794 | | <3053 309A> | こ゚
1795 | | <30AB 309A> | カ゚
1796 | | <30AD 309A> | キ゚
1797 | | <30AF 309A> | ク゚
1798 | | <30B1 309A> | ケ゚
1799 | | <30B3 309A> | コ゚
1800 | | <30BB 309A> | セ゚
1801 | | <30C4 309A> | ツ゚
1802 | | <30C8 309A> | ト゚


### Punctuation Glyphs

Adobe-Mang1-0 specifies a set of punctuation glyphs in both sans and serif styles. Precomposed ligatures containing full-width question mark and/or full-width exclamation mark have additional slanted variants. With the exception of U+301C the default style for the following CIDs should be serif. The following table lists the default and alternate CIDs:


**Default CID** | **Alternate CIDs** | **Vertical CIDs** | **Description** | **Unicode** | **Characters**
--- | --- | --- | --- | --- | ---
1143 | 17864 | 15527, 17873 | IDEOGRAPHIC COMMA | U+3001 | 、
17865 | 1170 | 17885, 17756 | WAVE DASH / FULLWIDTH TILDE | U+301C / U+FF5E | 〜 / ～
1171 | 17866 | 17746, 17882 | REVERSED DOUBLE PRIME QUOTATION MARK | U+301D | 〝
1172 | 17867 | 17747, 17884 | DOUBLE PRIME QUOTATION MARK | U+301E | 〞
1173 | 17868 | 17747, 17884 | LOW DOUBLE PRIME QUOTATION MARK | U+301F | 〟
15527 | 17873 | | VERTICAL IDEOGRAPHIC COMMA | U+FE11 | ︑
15528 | 17874 | | VERTICAL IDEOGRAPHIC FULL STOP | U+FE12 | ︒
15541 | 17875 | | VERTICAL OPENING PARENTHESIS | U+FE35 | ︵
15542 | 17876 | | VERTICAL CLOSING PARENTHESIS | U+FE36 | ︶
15543 | 17890 | | VERTICAL OPENING CURLY BRACKET | U+FE37 | ︷
15544 | 17891 | | VERTICAL CLOSING CURLY BRACKET | U+FE38 | ︸
15604 | 17869 | 15541, 17875 | FULLWIDTH OPENING PARENTHESIS | U+FF08 | （
15605 | 17870 | 15542, 17876 | FULLWIDTH CLOSING PARENTHESIS | U+FF09 | ）
15608 | 17898 | 15526 | FULLWIDTH COMMA | U+FF0C | ，
15690 | 17888 | 15543, 17890 | FULLWIDTH OPENING CURLY BRACKET | U+FF5B | ｛
15692 | 17889 | 15544, 17891 | FULLWIDTH CLOSING CURLY BRACKET | U+FF5D | ｝
15693 | 17871 | 17859, 17886 | FULLWIDTH LEFT WHITE PARENTHESIS | U+FF5F | ｟
15694 | 17872 | 17860, 17887 | FULLWIDTH RIGHT WHITE PARENTHESIS | U+FF60 | ｠
15627 | 15628-15630 || FULLWIDTH QUESTION MARK | U+FF1F | ？
15594 | 15595-15597 || FULLWIDTH EXCLAMATION MARK | U+FF01 | ！
17901 | 17902-17904 | 17965-17968 | DOUBLE QUESTION MARK |  | ？？
17905 | 17906-17908 | 17969-17972 | TRIPLE QUESTION MARK　| | ？？？
17909 | 17910-17912 | 17973-17976 | DOUBLE EXCLAMATION　| | ！！
17913 | 17914-17916 | 17977-17980 | TRIPLE EXCLAMATION　| | ！！！
17917 | 17918-17920 | 17981-17984 | QUADRUPLE EXCLAMATION | | ！！！！
17921 | 17922-17924 | 17985-17988 | QUINTUPLE EXCLAMATION  | | ！！！！！
17925 | 17926-17928 | 17989-17992 | QUESTION EXCLAMATION | | ？！
17929 | 17930-17932 | 17993-17996 | EXCLAMATION QUESTION | | ！？
17933 | 17934-17936 | 17997-18000 | DOUBLE QUESTION EXCLAMATION | | ？？！
17937 | 17938-17940 | 18001-18004 | QUESTION EXCLAMATION QUESTION | | ？！？
17941 | 17942-17944 | 18005-18008 | EXCLAMATION DOUBLE QUESTION | | ！？？
17945 | 17946-17948 | 18009-18012 | DOUBLE EXCLAMATION QUESTION | | ！！？
17949 | 17950-17952 | 18013-18016 | EXCLAMATION QUESTION EXCLAMATION | | ！？！
17953 | 17954-17956 | 18017-18020 | QUESTION DOUBLE EXCLAMATION | | ？！！
17957 | 17958-17960 | 18021-18024 | DOUBLE EXCLAMATION DOUBLE QUESTION | | ！！？？
17961 | 17962-17964 | 18025-18028 | DOUBLE QUESTION DOUBLE EXCLAMATION | | ？？！！

### Kanji Glyphs

Adobe-Manga1-0 includes 14,722 glyphs classified as kanji (aka ideographs) which is a superset of the 14,664 kanji glyphs included in Adobe-Japan1-7. The mapping file [aj17-to-manga10.txt](https://github.com/adobe-type-tools/Adobe-Manga1/raw/main/aj17-to-manga10.txt) provides CID mappings from Adobe-Japan1-7 to Adobe-Manga1-0. The CID ranges for kanji in Adobe-Manga1-0 are shown in the table below:

**Supplement** | **CIDs & CID Ranges**
--- | ---
0 | 1103-1129, 2447-15512, 15993-17621

The [*aj17-kanji.txt*](https://github.com/adobe-type-tools/Adobe-Japan1/raw/master/aj17-kanji.txt) datafile from [Adobe-Japan1]((https://github.com/adobe-type-tools/Adobe-Japan1) provides detailed information for each of the 14,664 kanji included in Adobe-Japan1-7.

### Ruby Glyphs

Adobe-Manga1-0 includes glyphs that are suitable for typesetting ruby (aka *furigana*), and the vast majority of the glyphs are for kana, though glyphs for some symbols are also included. Although these ruby glyphs are unencoded, they can be used by applications that support the OpenType '[ruby](https://docs.microsoft.com/en-us/typography/opentype/spec/features_pt#tag-ruby)' (*Ruby Notation Forms*) GSUB feature. The following table details the CID ranges for the ruby glyphs in Supplement 0:

**Supplement** | **CID Ranges**
--- | ---
0 | 1595-1834, 1934-1983

### Duplicate Kanji Glyphs

This section was copied from Adobe-Japan1 and edited to reflect Adobe-Manga1-0 CIDs. For historical reasons and for JIS90-compliance, the following three Supplement 0 kanji glyph pairs represent genuine duplicate glyphs, and their JIS83 (aka JIS X 0208-1983) forms in Supplement 4 are shown for the sake of comparison:

**Primary Glyph** | **Duplicate Glyph** | **AJ17 Primary Glyph** | **AJ17 Duplicate Glyph** | **JIS83 Form**
--- | --- | --- | --- | ---
3590—&#x5315;&#xE0100; | 16651—&#x5315;&#xE0101; | 4301—&#x5315;&#xE0100; | 7983—&#x5315;&#xE0101; | 13523—&#x2090E;&#xE0100;
4027—&#x55A9;&#xE0100; | 16685—&#x55A9;&#xE0101; | 4411—&#x55A9;&#xE0100; | 7984—&#x55A9;&#xE0101; | 13526—&#x55A9;&#xE0102;
8015—&#x6E23;&#xE0100; | 16981—&#x6E23;&#xE0101; | 5459—&#x6E23;&#xE0100; | 7994—&#x6E23;&#xE0101; | 13558—&#x6E23;&#xE0102;

For the purposes of full compliance and character collection integrity, the duplicate glyphs shown above shall be maintained.

---
## CMap Resources

The CMap resources associated with the Adobe-Manga1-0 character collection, along with more complete descriptions and the [*cid2code.txt*](https://raw.githubusercontent.com/adobe-type-tools/cmap-resources/master/Adobe-Manga1-0/cid2code.txt) datafile that provides additional details for font developers, are available as part of the open source [*CMap Resources*](https://github.com/adobe-type-tools/cmap-resources/) project.


---
## Unicode Variation Sequences

The Ideographic Variation Sequences (IVSes) that are specified in the [*Adobe-Manga1_sequences.txt*](https://github.com/adobe-type-tools/Adobe-Manga1/raw/main/Adobe-Manga1_sequences.txt) datafile are registered by The Unicode Consortium in the [IVD](http://www.unicode.org/ivd/) (*Ideographic Variation Database*) per [UTS #37](http://www.unicode.org/reports/tr37/) (*Unicode Ideographic Variation Database*). This datafile also includes a small number of [Standardized Variation Sequences](http://www.unicode.org/Public/UCD/latest/ucd/StandardizedVariants.txt).


---
## Glyph Tables

Representative glyphs for CIDs 0 through 18031 are provided in the [*Adobe-Manga1-0.pdf*](https://github.com/adobe-type-tools/Adobe-Manga1/raw/main/Adobe-Manga1-0.pdf) file that is included in this project, with 500 glyphs shown per page. The typeface used to exemplify each glyph is [*Ten Mincho Antique Regular*](https://fonts.adobe.com/fonts/ten-mincho-antique) (aka TenMinchoAntique-Regular or 貂明朝アンチック Regular), designed by Adobe. The specific font instance is Version 1.011.
