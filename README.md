# Polish GEC test datasets


Polish test datsets for grammatical error correction. 



## Dataset statistics


### Humman annotated test sets


| dataset nam                              | lines | errors fleks | errors orth | errors punct | errors syntax | errors lex |
|------------------------------------------|-------|--------------|-------------|--------------|---------------|------------|
| human_expert_gec_dataset.jsonl           | 1804  | 299          | 599         | 300          | 300           | 299        |
| human_annotators_common_errors_10k.jsonl | 10000 | 2442         | 4925        | 2423         | 2459          |            |
|                                          |       |              |             |              |               |            |

### Synthetic rule-based test sets


| dataset name                           | lines | errors fleks | errors orth | errors punct | errors syntax | errors lex |
|----------------------------------------|-------|--------------|-------------|--------------|---------------|------------|
| synthetic_syntax_10k.jsonl             | 10000 |              |             |              | 10336         |            |
| synthetic_nie_bez_jednostkowe_10k.json | 10000 |              | 10831       |              |               |            |
| synthetic_simple_fleks_10k.json        | 10000 | 10000        |             |              |               |            |
| synthetic_ fleks_morf_regex_10K.jsonl  | 10000 | 15158        |             |              |               |            |
| synthetic_orth_phonteic_10k.jsonl      | 10000 |              | 10000       |              |               |            |



# Acknowledge

This work was supported by NCBiR grant number POIR.01.01.01-00-1128/18-00 
“Technologia kontekstowego rozumienia języka pisanego na potrzeby poprawy błędów oraz automatycznej oceny zrozumiałości tekstu.”

