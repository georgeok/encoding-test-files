Encoding test files
===================

These are example test files for testing encoding issues.

They are generated by running `generate.py` with Python 2.7.

Assuming your browser can read this README as UTF-8, the content should be equivalent to:

```
première is first
Кириллица is [Cyrillic](http://en.wikipedia.org/wiki/Cyrillic)
𐐀 am [Deseret](http://en.wikipedia.org/wiki/Deseret_alphabet)
```

These are written into different encodings, where some characters might be replaced with ?.  
Only UTF8 and UTF16 is able to do all encodings.


TODO: Add BOM test files
