# quora_kaggle

tm_2017-03-24_featuresXGB.ipynb now generates good predictions (0.26 on PL)
- key feature added: for each word, if it is in both (2) only in 1 (1) or not present (0)
- param tuning and validation with xgb.cv!
