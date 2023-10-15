# HLSTM Report

<img src="https://github.com/a-emadi/HLSTM/assets/147874627/bd4fd9e9-c047-46eb-8ba2-1a43cbbf799e">


## Wikitext-2
|Model | Val. PPL|	Test PPL|	Last Epoch|	Last LR|	Seq_len|	Tokenizer|
|------|------|------|------|------|------|------|
|HLSTM|	1.826|	1.779|	64|	0.007813|	25|	moses|
|HLSTM|	1.952|	1.907|	143|	2.98E-08|	25|	Split|
|HLSTM|	2.38|	2.296|	155	|3.81E-06|	35|	moses|
|HLSTM| 2.847| 2.782 | 113| 0.00048828125| 35|Basic_English|
|HLSTM|	21.98|	20.39|	139	|2.98E-08|	50|	moses|
|HLSTM| 47.19| 45.49| 152| 2.38E-07| 50|Basic_English|
|HLSTM|	51.75|	49.58|	151	|2.33E-10|	50|	Split|
|HLSTM|	68.75|	63.34|	122	|3.81E-06|	70|	moses|

## Wikitext-103
|Model | Val. PPL|	Test PPL|	Last Epoch|	Last LR|	Seq_len|	Tokenizer|
|------|------|------|------|------|------|------|
|HLSTM|	1.885|	1.942|	12(24h)|	0.5|	25|	Split|

## Penn Dataset
|Model|	Val. PPL|	Test PPL|	Last Epoch|	Last LR|	Seq_len|	Tokenizer|
|------|------|------|------|------|------|------|
|HLSTM|	1.964|	1.782|	149|	2.91E-11|	25|	Split|
|H2HLSTM|	3.94|	3.44|	123|	1.19E-07|	21|	Moses|
|LSTM|	87.75|	74.87|	66|	1.90E-06|	21|	Moses|
