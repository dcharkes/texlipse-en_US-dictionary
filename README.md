# Texlipse en_US dictionary

This is a en_US dictionary for Texlipse.
Texlipse only provides a en dictionary that also accepts en_GB, but I only want the US spelling to be accepted.

The en_US dictionary is extracted from Aspell with:

```
aspell -d en_US dump master | aspell -l en expand > en.dict
```

## Configure Spell Check for Texlipse

- get dictionaries from this repo
- settings Eclipse: General > Editors > Text Editors > Spelling > Enable spell checking & spelling engine: Latex
- settings Eclipse: Texlipse > Spell Checker > use build in spell checker & set directories for dictionaries
- settings Project: Latex Project Properties > two-letter language code: en
- (restart Eclipse!)
