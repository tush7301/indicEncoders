# Cross-Lingual Transfer and Parameter Efficiency in Indic Encoders

● Conducted an empirical comparison of IndicBERT-v2 and MuRIL transformer encoders on Hindi hate speech detection, achieving 0.794 F1 score
in zero-shot cross-lingual transfer to Marathi and 0.824 F1 in few-shot settings (50 examples).
● Implemented LoRA fine-tuning, updating <1% of parameters, delivering 40+ F1 point improvement over full fine-tuning baselines and cutting
down memory overhead by 97.6%.
● Demonstrated distinct performance trade-offs between pre-training paradigms: monolingual scaling (IndicBERT-v2) accomplished superior
zero-shot transfer (0.794 F1), while translation-aware alignment (MuRIL) attained faster few-shot adaptation with minimal supervision.
