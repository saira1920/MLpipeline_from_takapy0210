# 概要

takapy0210さんのリポジトリを参考に、適宜自分ように修正しています。  
https://github.com/takapy0210/ml_pipeline  
タイタニックのデータを用いて、LightGBMとxgboostによる学習・推論の一連の流れが行えるようにしています。

## 動作検証済み環境
OS: MacOS Catalina  
python: 3.6.5

# 手順

## クローン
```sh
git clone https://github.com/takapy0210/ml_pipeline.git
```


## 特徴量生成
```sh
python 10_titanic_fe.py
```

### 生成された特徴量の確認（確認したい場合）
```sh
python 15_show_all_features.py
```

## 学習
```sh
python 20_run.py
```
