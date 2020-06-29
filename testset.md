---
title: TICO-19 Benchmark
layout: tico-default
---

<sup><sub>[back to main page](index.html) </sub></sup>


The benchmark includes 30 documents (3071 sentences, 69.7k words) translated from English into 36 languages:
Amharic, Arabic (Modern Standard), Bengali, Chinese (Simplified), Dari, Dinka, Farsi, French (European), Hausa, Hindi, Indonesian, Kanuri, Khmer (Central), Kinyarwanda, Kurdish Kurmanji, Kurdish Sorani, Lingala, Luganda, Malay, Marathi, Myanmar, Nepali, Nigerian Fulfulde, Nuer, Oromo, Pashto, Portuguese (Brazilian), Russian, Somali, Spanish (Latin American), Swahili, Congolese Swahili, Tagalog, Tamil, Tigrinya, Urdu, Zulu.

Download all data (with pre-defined dev/test splits) here: [zip](#).

The paper describing the dataset is here: [pdf](#).

We will maintain a matrix of the best reported results and systems on each language pair. If you evaluate your MT systems against the benchmark reach out to us!

|    | am | ar | bn | ckb | din | es-419 | fa | fr | fuv-Latn-NG | ha | hi | id | km | kr | ku | lg | ln | mr | ms | my | ne | nus | om | prs | pt-BR | pus | ru | rw | so | sw | ta | ti | tl | ur | zh | zu |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| am |  –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ar |   | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| bn |   |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ckb |   |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| din |   |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| es-419 |   |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| fa |   |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| fr |   |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| fuv-Latn-NG |   |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ha |   |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| hi |   |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| id |   |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| km |   |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| kr |   |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ku |   |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| lg |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ln |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| mr |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ms |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| my |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| ne |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| nus |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| om |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| prs |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |  |
| pt-BR |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |  |
| pus |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |  |
| ru |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |  |
| rw |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |  |
| so |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |  |
| sw |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |  |
| ta |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |  |
| ti |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |  |
| tl |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |  |
| ur |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |  |
| zh |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |  |
| zu |   |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | –– |  |

