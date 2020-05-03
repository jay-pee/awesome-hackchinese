# Awesome List: Hack Chinese [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->

> A curated list of awesome resources for hacking the Chinese language.
> APIs, packages, libraries, open source software, etc. are listed here which
> you can use for programming stuff around the topic of learning Chinese.

RIGHT NOW THE LIST IS WORK IN PROGRESS. PULL REQUESTS ARE HIGHLY APPRICHIATED!

## Contents (内容)<!-- omit in toc -->

- [Libraries/Packages](#librariespackages)
  - [Python](#python)
  - [Javascript](#javascript)
  - [Ruby](#ruby)
- [Datasets](#datasets)
  - [Dictionaries Basis](#dictionaries-basis)
  - [Dictionaries made on from Basis](#dictionaries-made-on-from-basis)
  - [Other Datasets](#other-datasets)
- [Miscellaneous](#miscellaneous)
- [Example Projects](#example-projects)
- [TODO List](#todo-list)
- [Contribute](#contribute)
- [License](#license)

## Libraries/Packages

### Python

- [wordfreq](https://github.com/LuminosoInsight/wordfreq) (wordfreq is a Python library for looking up the frequencies of words in many languages, based on many sources of data.)
- [xpinyin](https://github.com/lxneng/xpinyin) (translate chinese hanzi to pinyin by python)
- [hanziconv](https://github.com/berniey/hanziconv)
- [chinese_ocr](https://github.com/YCG09/chinese_ocr) (Optical character recognition for chinese characters based on Tensorflow and Keras)
- [jieba](https://github.com/fxsjy/jieba) (Chinese text segmentation: built to be the best Python Chinese word segmentation module.)

### Javascript

- [HanziJS](https://github.com/nieldlr/hanzi) (HanziJS is a Chinese character and NLP module for Chinese language processing for Node.js. It is primarily written to help provide a framework for Chinese language learners to explore Chinese.)
- [Hanzi Writer](https://hanziwriter.org/) (Hanzi Writer is a free and open-source javascript library for Chinese character stroke order animations and stroke order practice quizzes. Works with both simplified and traditional characters.)
  - [Visualisation](https://chanind.github.io/hanzi-writer-data/#25105)
  - Based on Hanzi Writer Data (see Datasets)
- [cn-grammar-matcher](https://github.com/chanind/cn-grammar-matcher)[A tool to find grammar patterns in Chinese text.]
- [HanziLookupJS](https://github.com/gugray/HanziLookupJS) (Free, open-source Chinese handwriting recognition in Javascript.)

### Ruby

- [chinese_pinyin](https://github.com/flyerhzm/chinese_pinyin) Translate chinese hanzi to pinyin.
  - https://www.skishore.me/makemeahanzi/
  - https://www.skishore.me/inkstone/
- ...

## Datasets

### Dictionaries Basis

- [CC-CEDICT](https://www.mdbg.net/chinese/dictionary?page=cc-cedict) (complete downloadable Chinese to English dictionary with pronunciation in pinyin for the Chinese characters.)
- [Unihan](https://unicode.org/charts/unihan.html)
- [CJK Decomposition Data](https://github.com/cburgmer/cjklib) (Han character library for CJKV languages)
- [HanDeDict](https://github.com/gugray/HanDeDict) (HanDeDict is a collaboratively edited, open-source Chinese-German dictionary.)

### Dictionaries made on from Basis

- [makemeahanzi dataset](https://github.com/skishore/makemeahanzi) (Free, open-source Chinese character data, based on Unihan and cjklib)
- [hanyu-shuping-kaoshi](https://github.com/gigacool/hanyu-shuiping-kaoshi) (Word list of all HSK levels)

<!-- https://github.com/sawcordwell/HSK-Vocab
https://github.com/clem109/hsk-vocabulary -->

### Other Datasets

- [Tatoeba](https://github.com/Tatoeba/tatoeba2) (a multilingual sentence/translation database.)
- [Recursive Radical Packing Language](https://github.com/LingDong-/rrpl)
- [Hanzi Writer Data](https://github.com/chanind/hanzi-writer-data) (Data For the Hanzi Writer)
- [C0S960](https://github.com/thunlp/COS960) (COS960 is a Chinese word similarity dataset of 960 word pairs.)
- [audio-cmn](https://github.com/hugolpz/audio-cmn) (Chinese (zh-cnm) opendata audio files for 8,596 hsk words and 1,707 syllabs. )
- [Chinese-Grammar](https://github.com/infinyte7/Chinese-Grammar) (Chinese Grammar List from [Chinese Grammar Wiki](https://resources.allsetlearning.com/chinese/grammar/))
- [Stanford CoreNLP](https://wordnet.princeton.edu/) (Stanford CoreNLP provides a set of human language technology tools.)
- [Chinese text computing](https://lingua.mtsu.edu/chinese-computing/) (provides character frequency lists generated from a large corpus of Chinese texts collected from online sources.)
<!-- - [Wordnet](https://wordnet.princeton.edu/) -->


## Miscellaneous

- [youtube-dl](https://github.com/ytdl-org/youtube-dl/) (Download (Chinese) Videos and scrape the subtitles)
  - ...
- [chinese-wordlist-extractor](https://github.com/stooone/chinese-wordlist-extractor) (Script to make word frequency list (CSV) from a text.)
- [文言 wenyan-lang](https://github.com/wenyan-lang/wenyan) (A programming language for the ancient Chinese. )
- [{Shan, Shui}*](https://github.com/LingDong-/shan-shui-inf) (Procedurally-generated vector-format infinitely-scrolling Chinese landscape for the browser.)
- [edges2calligraphy](https://github.com/LingDong-/edges2calligraphy) (Using pix2pix to convert scribbles to Chinese calligraphy)

## Example Projects

A short list of projects, that are utilizing this Libraries, Datasets, etc.

- [Chinese Character Web API](http://ccdb.hemiola.com/)
- [Inkstone](https://github.com/skishore/inkstone) (Learn Chinese on the go - no Internet connection required!)
- Anki Add-Ons and Decks
  - [Chinese Support Redux](https://github.com/luoliyan/chinese-support-redux) (Anki add-on providing support for Chinese study)
  - [Anki-Chinese-Grammar-Practice](https://github.com/infinyte7/Anki-Chinese-Grammar-Practice) (Practice Chinese language grammar)
  - [Anki-xiehanzi](https://github.com/infinyte7/Anki-xiehanzi) (Learn, read, write and practice Mandarin by drawing strokes in anki and ankidroid with audio of HSK1 to HSK6 characters.)
  - [Anki Chinese Radicals Deck+](https://github.com/jay-pee/Anki-Chinese-Radicals-Deck-Plus) Automatically generated Anki Flashcards Deck to learn the Chinese Radicals
- Dictionaries:
  - [Make Me a Hanzi Demo](https://makemeahanzi.herokuapp.com/#/codepoint/20320)
  - [mdbg](https://www.mdbg.net/chinese/dictionary)
  - [zdic](http://www.zdic.net/)

<!-- ## X-Callback URL Schemes
- [AwesomeTTS](https://github.com/AwesomeTTS/awesometts-anki-addon) (text-to-speech add-on for Anki )
- Anki 
- Pleco -->

## TODO List

- [ ] (Better) descriptions of the Titles and Subtitles
- [ ] More
- [ ] Add X-Callback

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Philip Janssen has waived all copyright and
related or neighboring rights to this work.
