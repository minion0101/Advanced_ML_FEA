
![[]](https://img.shields.io/badge/Python-3.10.10-blue)

# Advanced_ML_FEA

### 機械学習特論の期末課題のプログラム

#### リポジトリの概要
| フォルダ | 概要 |
| :-- | :-- |
| [`main.ipynb`](/main.ipynb) | 課題で使用したスクリプト |
| [`fig`](/fig) | モデルの概要と学習曲線 |
| [`model`](/model) | 学習済みモデル(`.h5`形式) |
| [`tuner_dir`](/tuner_dir) | Keras Tunerにより生成されたチェックポイント |

#### 学習完了までに要した時間
【マシンスペック】
- OS: Windows 11
- CPU: Intel Core i7-12700
- RAM: 32GB
- Storage: 512GB SSD

| モデル名 | 使用したモデル | 備考 | 時間 |
| :--: | :-- | :-- | --: |
| rnn_model_1 | 多層パーセプトロン | 第6回課題で使用 | 2m 44.5s |
| rnn_model_2 | 多層パーセプトロン | Keras Tunerによりチューニング | 8h 20m 29.2s |
| cnn_model_1 | CNN | 第6回課題で使用 | 5m 21.1s |
| cnn_model_2 | CNN | Keras Tunerによりチューニング | 2d 20h 16m 13.1s |
