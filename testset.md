---
title: TICO-19 Benchmark
layout: tico-default
---

<sup><sub>[back to main page](index.html) </sub></sup>


The benchmark includes 30 documents (3071 sentences, 69.7k words) translated from English into 36 languages:
Amharic, Arabic (Modern Standard), Bengali, Chinese (Simplified), Dari, Dinka, Farsi, French (European), Hausa, Hindi, Indonesian, Kanuri, Khmer (Central), Kinyarwanda, Kurdish Kurmanji, Kurdish Sorani, Lingala, Luganda, Malay, Marathi, Myanmar, Nepali, Nigerian Fulfulde, Nuer, Oromo, Pashto, Portuguese (Brazilian), Russian, Somali, Spanish (Latin American), Swahili, Tagalog, Tamil, Ethiopian Tigrinya, Urdu, Zulu.

Download all data (with pre-defined dev/test splits) here: [zip](data/tico19-testset.zip).

The paper describing the dataset is here: [pdf](data/paper/ticopaper.pdf).
(Please use this [BibTeX](data/paper/ticopaper.bib) file if you end up using the dataset in an academic paper.)

We will maintain a matrix of the best reported results (BLEU scores) and systems on each language pair. If you evaluate your MT systems against the benchmark reach out to us!


|    | am | ar | bn | ckb | din | en | es-419 | fa | fr | fuv-Latn-NG | ha | hi | id | km | kr | ku | lg | ln | mr | ms | my | ne | nus | om | prs | pt-BR | pus | ru | rw | so | sw | ta | ti | tl | ur | zh | zu |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| am |  –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ar |   | –– |  |  |  | 28.56 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| bn |   |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ckb |   |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| din |   |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| en |   | 15.16 [source](https://arxiv.org/pdf/2007.01788.pdf)  |  |  |  | –– | 49.25 [source](https://arxiv.org/pdf/2007.01788.pdf) | 8.48 [source](https://arxiv.org/pdf/2007.01788.pdf) | 37.59 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 6.43 [source](https://arxiv.org/pdf/2007.01788.pdf) | 41.27 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  | 2.96 [source](https://arxiv.org/pdf/2007.01788.pdf) | 7.85 [source](https://arxiv.org/pdf/2007.01788.pdf) | 0.21 [source](https://arxiv.org/pdf/2007.01788.pdf) | 6.26 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  | 0.57 [source](https://arxiv.org/pdf/2007.01788.pdf) | 9.49 [source](https://arxiv.org/pdf/2007.01788.pdf) | 47.27 [source](https://arxiv.org/pdf/2007.01788.pdf) |  | 28.88 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 22.62 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  | 2.79 [source](https://arxiv.org/pdf/2007.01788.pdf) | 33.70 [source](https://arxiv.org/pdf/2007.01788.pdf) | 11.73 |
| es-419 |   |  |  |  |  | 46.82 [source](https://arxiv.org/pdf/2007.01788.pdf) | –– |  | 29.21 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| fa |   |  |  |  |  | 15.07 [source](https://arxiv.org/pdf/2007.01788.pdf) |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| fr |   |  |  |  |  | 39.4 [source](https://arxiv.org/pdf/2007.01788.pdf) | 34.95 [source](https://arxiv.org/pdf/2007.01788.pdf) |  | –– |  |  |  |  |  |  |  | 1.48 [source](https://arxiv.org/pdf/2007.01788.pdf) | 6.14 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  | 15.11 [source](https://arxiv.org/pdf/2007.01788.pdf) | 3.83 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |
| fuv-Latn-NG |   |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ha |   |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| hi |   |  |  |  |  | 18.92 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| id |   |  |  |  |  | 34.86 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 18.95 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| km |   |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| kr |   |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ku |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| lg |   |  |  |  |  | 5.62 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 2.91 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ln |   |  |  |  |  | 6.71 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 4.77 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| mr |   |  |  |  |  | 1.16 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ms |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| my |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ne |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| nus |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| om |   |  |  |  |  | 2.11 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |
| prs |   |  |  |  |  | 15. 16 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |
| pt-BR |   |  |  |  |  | 48.56 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |
| pus |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |
| ru |   |  |  |  |  | 28.53 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 17.62 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |
| rw |   |  |  |  |  | 8.29 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  | 5.62 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |
| so |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |
| sw |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |
| ta |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |
| ti |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |
| tl |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |
| ur |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |
| zh |   |  |  |  |  | 28.94 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |
| zu |   |  |  |  |  | 25.52 [source](https://arxiv.org/pdf/2007.01788.pdf) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |