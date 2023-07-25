# UZNER: A Benchmark for Named Entity Recognition in Uzbek

## 1. Environments
```text
- python (3.8)
- cuda (11.4)
- torch (1.8.1)
- pip install -r requirements.txt
```

## 2. Dataset
   Our data is in the `data/`, where `train_enhanced.json` is the training data containing the translated data 

## 5. Training
```text
python main.py --config ./config/multilingual.json
```
You can find it in `config/multilingual.json`