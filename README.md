# MTPEdocs

## Introduction

This repository contains document-level machine translation post-editing (MTPE) datasets for multiple language directions (Ja->En/Zh) and MT systems (TexTra/Google Translate/DeepL).

## Contents

- [SD](SD): 18 source language (Japanese) documents
  - pdf: PDF versions
  - txt: text data (one sentence per line)
- [MT](MT): raw machine translation outputs of SD
  - JaEn_01_TexTra: [TexTra](https://mt-auto-minhon-mlt.ucri.jgn-x.jp/) (Ja->En; GPMT-3.9_220930_nmt; obtained 2023-01-31)
  - JaEn_02_Google: [Google Translate](https://translate.google.com/) (Ja->En; obtained 2023-03-05)
  - JaEn_03_DeepL: [DeepL](https://www.deepl.com/) (Ja->En; obtained 2023-03-05)
  - JaZh_01_TexTra: TexTra (Ja->Zh; obtained 2023-03-05)
- [PE](PE): post-edited data of MT
- [document-list.xlsx](/document-list.xlsx): source information of SD and HT

## Source of original documents

The original Japanese documents were selected from the parallel documents in the following dataset:

- Nagoya City and Rei Miyata (2023) Translation Resources of Nagoya City [名古屋市翻訳資源]. https://github.com/tr4lg/nagoya-dataset/ (accessed 2024-03-23).

Document No. 015 was originally published by the Ministry of Health, Labour and Welfare and later edited by Nagoya City.

- Source: [子育て世帯生活支援特別給付金（ひとり親世帯以外分）　リーフレット](https://web.archive.org/web/20210803082408/https://www.mhlw.go.jp/stf/newpage_18013.html) [Guide to the Special Benefit for Supporting Families with Children]

## License

![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

- Use and/or redistribution of this dataset, except for [SD](SD), is permitted under the conditions of [Creative Commons Attribution-NonCommercial-ShareAlike License 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Citation

Rei Miyata (2024) MTPEdocs. https://github.com/tntc-project/MTPEdocs

## Acknowledgments

I am grateful to Dr. Atsushi Fujita for his helpful advice on the post-editing data creation.
Construction of the datasets was supported by JSPS KAKENHI Grant Numbers [JP19H05660](https://kaken.nii.ac.jp/en/grant/KAKENHI-PROJECT-19H05660/) and [JP23K28378](https://kaken.nii.ac.jp/en/grant/KAKENHI-PROJECT-23K28378/).
