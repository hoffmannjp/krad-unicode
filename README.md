# Krad Unicode

These files represent a decomposition of the 6,355 kanji from JIS X 0208-1997 into components intended to be used in kanji lookup tools.

They are a Unicode / JSON conversion of the EDRDG's [RADKFILE/KRADFILE](https://www.edrdg.org/krad/kradinf.html).

## Files
- krad_components.json - List of the 253 components with their respective stroke count.
- krad.json - List of the 6,355 kanji and their respective components.
- possible_groups.json - List of all possible combinations of components 

## Changes

Since JIS X 0208 doesn't contain all the components as separate characters (e.g. ⺅ does not exist as its own character in JIS X 0208), the original files used substitutes for these components. Since Unicode does contain all the components as separate characters these substitutes have been replaced as follows:

```
化 -> ⺅
个 -> 𠆢
并 -> 丷
刈 -> ⺉
込 -> ⻌
尚 -> ⺌
忙 -> ⺖
扎 -> ⺘
汁 -> ⺡
犯 -> ⺨
艾 -> ⺾
邦 -> ⻏
阡 -> ⻖
老 -> ⺹
杰 -> ⺣
礼 -> ⺭
疔 -> 疒
禹 -> 禸
初 -> ⻂
買 -> ⺲
滴 -> 啇
```

# Copyright Notice
These files are based on the EDRG's RADKFILE/KRADFILE project which is made available under a Creative Commons Attribution-ShareAlike Licence (V3.0).

[ELECTRONIC DICTIONARY RESEARCH AND DEVELOPMENT GROUP GENERAL DICTIONARY LICENCE STATEMENT](https://www.edrdg.org/edrdg/licence.html)
