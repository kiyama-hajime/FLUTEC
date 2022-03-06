# FLUency extended TMU Evaluation Corpus (FLUTEC)

## Data
- The FLUTEC is an evaluation dataset for Japanese grammatical error correction on fluency edits.
- You can get the dataset from this [URL]()

## Scripts
- We provide scripts for preprocessing of the Lang-8 corpus.
- The FLUTEC is built from the [Lang-8 corpus](https://sites.google.com/site/naistlang8corpora/), so you need to remove documents with duplicate journal IDs.

### Requirements
- Python 3
- [langdetect](https://pypi.org/project/langdetect/)
- [python-Levenshtein](https://pypi.org/project/python-Levenshtein/)

## Usage

```
a
```

## Citation
- The following paper should be cited in any publications that use our dataset.

```
@inproceedings{,
    title = "日本語文法誤り訂正の流暢性評価に向けたデータ作成",
    author = "木山朔, 上坂奏人, 佐藤郁子, 佐藤京也, 米田悠人, 小山碧海, 三田雅人, 岡照晃, 小町守. ",
    booktitle = "言語処理学会 第28回年次大会発表論文集",
    month = march,
    year = "2022",
    address = "静岡, 日本",
    publisher = "言語処理学会",
    url = "https://www.anlp.jp/nlp2022/",
    pages = "",
}
```
