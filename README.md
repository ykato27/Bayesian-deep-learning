# Time-Series-deep-learning
* 時系列予測（ディープラーニング）のプログラム

## リポジトリ構成
```
.
├── Dockerfile
├── README.md
├── data
│   └── AirPassengers.csv
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── Bayesian
│   │   └── Bayesian-deep-learning.ipynb
│   ├── GRU
│   │   ├── 14_gru.ipynb
│   │   ├── GRU_torch.ipynb
│   │   └── gru_torch_scratch.ipynb
│   ├── LSTM
│   │   ├── 13_lstm.ipynb
│   │   ├── 4_2_LSTM_TF2.ipynb
│   │   ├── LSTM_Keras.ipynb
│   │   ├── LSTM_pytorch_wave.ipynb
│   │   ├── LSTM_torch.ipynb
│   │   ├── LSTM_torch_example2.ipynb
│   │   └── lstm_torch_scratch.ipynb
│   ├── Pyro
│   │   └── Pyro.ipynb
│   ├── RNN
│   │   ├── 01_03_RNN.ipynb
│   │   ├── 12_rnn.ipynb
│   │   ├── 4_1_3_RNN�\203��\203\207�\203�_.ipynb
│   │   ├── RNN_torch.ipynb
│   │   └── rnn_torch_scratch.ipynb
│   └── Transformer
│       ├── Informer_Beyond_Efficient_Transformer_for_Long_Sequence_Time_Series_Forecasting.ipynb
│       └── transformers_torch_scratch.ipynb
├── pyproject.toml
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Time-Series-deep-learning）
```
cd Desktop/Time-Series-deep-learning
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Time-Series-deep-learning）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている


## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/Time-Series-Deep-Learning/tree/main/notebooks/)


## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
