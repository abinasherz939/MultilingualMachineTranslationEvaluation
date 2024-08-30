Learnings:

1. All models performed better in English-to-Hindi and Hindi-to-English translation compared to Hindi-to-Bangla and Bangla-to-Hindi tasks. This highlights the potential impact of factors like the size and quality of training data on different language pairs.

# IndicTrans
==========================================================
Hindi to English
Scores
BLUE Score(Sentence BLEU) : 0.4381767179595883


BLUE Score with Tokenizer

bleu : 0.39825033494705087
precisions : [0.6847119726842164, 0.45704627578971907, 0.32968189132318354, 0.2438155551157728]
brevity_penalty : 1.0
length_ratio : 1.0058719255484156
translation_length : 18158
reference_length : 18052

ROUGE Score
rouge1 : 0.710477203501947
rouge2 : 0.501047244567161
rougeL : 0.6622810299232798
rougeLsum : 0.6624845473122015
==========================================================
English to Hindi
Scores
BLUE Score(Sentence BLEU) : 0.41951860706645017


BLUE Score with Tokenizer

bleu : 0.34882455158383746
precisions : [0.6316470017779214, 0.4124480382666135, 0.28428235009963165, 0.19991003727027373]
brevity_penalty : 1.0
length_ratio : 1.0137637227592986
translation_length : 18561
reference_length : 18309

ROUGE Score
rouge1 : 0.12013809523809527
rouge2 : 0.017047619047619048
rougeL : 0.11931785714285714
rougeLsum : 0.11951904761904764
==========================================================
Hindi to Bangla
Scores
BLUE Score(Sentence BLEU) : 0.40468429658451016


BLUE Score with Tokenizer

bleu : 0.07602988558001342
precisions : [0.31994827957761657, 0.11810231406237907, 0.049156949920308696, 0.021148036253776436]
brevity_penalty : 0.9603643868078502
length_ratio : 0.9611295222314278
translation_length : 13921
reference_length : 14484

ROUGE Score
rouge1 : 0.004
rouge2 : 0.0
rougeL : 0.004
rougeLsum : 0.004
==========================================================
Bangla to Hindi
Scores
BLUE Score(Sentence BLEU) : 0.3533827524598416


BLUE Score with Tokenizer

bleu : 0.1864813631840226
precisions : [0.4722964638157895, 0.24040962288686607, 0.13565536205316223, 0.07851239669421488]
brevity_penalty : 1.0
length_ratio : 1.0626467857337922
translation_length : 19456
reference_length : 18309

ROUGE Score
rouge1 : 0.10939166666666668
rouge2 : 0.01307142857142857
rougeL : 0.1085095238095238
rougeLsum : 0.10954404761904762
==========================================================


# NLLB

==========================================================

### Hindi to English
Scores

BLUE Score : 0.4006749182856718

ROUGE Score
rouge1 : 0.6632913008000563
rouge2 : 0.4363122996990892
rougeL : 0.6154112365033515
rougeLsum : 0.6156424321620952

### English to Hindi
Scores

BLUE Score : 0.39649608439150036

ROUGE Score
rouge1 : 0.12606428571428574
rouge2 : 0.022523809523809526
rougeL : 0.1260547619047619
rougeLsum : 0.12648214285714288

### Hindi to Bangla
BLUE Score : 0.4042740409800657

ROUGE Score
rouge1 : 0.003
rouge2 : 0.0
rougeL : 0.003
rougeLsum : 0.003

### Bangla to Hindi
Scores

BLUE Score : 0.3530685342038333

ROUGE Score
rouge1 : 0.10510238095238096
rouge2 : 0.0141
rougeL : 0.10499880952380954
rougeLsum : 0.10570714285714287

==========================================================
# ChatGPT
==========================================================
### Hindi to English
Scores

BLUE Score : 0.28848213936156814

ROUGE Score
rouge1 : 0.7097276204584894
rouge2 : 0.4803168776899588
rougeL : 0.6637167545614855
rougeLsum : 0.6642904263741766

### English to Hindi

Scores

BLUE Score : 0.2208810512015695

ROUGE Score
rouge1 : 0.11333333333333333
rouge2 : 0.01142857142857143
rougeL : 0.11333333333333333
rougeLsum : 0.10666666666666666

### Hindi to Bangla

Scores

BLUE Score : 0.033679238096458446

ROUGE Score
rouge1 : 0.0
rouge2 : 0.0
rougeL : 0.0
rougeLsum : 0.0

### Bangla to Hindi

Scores

BLUE Score : 0.11855009028220033

ROUGE Score
rouge1 : 0.14
rouge2 : 0.0
rougeL : 0.14
rougeLsum : 0.14

