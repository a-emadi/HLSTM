# HLSTM
  Report of observations and investigations on LSTM based Language Modeling

## Wikitext-2

### HLSTM

<img src="https://github.com/a-emadi/HLSTM/assets/147874627/bd4fd9e9-c047-46eb-8ba2-1a43cbbf799e">

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

### H2HLSTM

<img  src="https://github.com/a-emadi/HLSTM/assets/147874627/a11f53bd-6c9d-4c70-8496-156a0b41cbd0">

|Model | Val. PPL|	Test PPL|	Last Epoch|	Last LR|	Seq_len|	Tokenizer|
|------|------|------|------|------|------|------|
|H2HLSTM| 3.069| 2.987| 145| 4.66E-10| 25| Split|
|H2HLSTM| 4.085| 3.855| 117| 1.91E-06| 35| moses|
|H2HLSTM-NTASGD| 32.32| 31.01| 108| 9.53E-07| 50| Basic_English|
|H2HLSTM| 34.8| 33.59| 97| 6.10E-05| 50| Basic_English|
|H2HLSTM| 38.15| 35.18| 88| 2.98E-08| 50| moses|
|H2HLSTM| 67.48| 64.29| 99| 2.29E-05| 50| Split|


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
