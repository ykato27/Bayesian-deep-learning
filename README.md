# Time-Series-deep-learning
* 時系列予測（ディープラーニング）のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
└── notebook                  jupyter notebook
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

## jupyter notebook説明
* Bayesian-deep-learning.ipynb : ベイジアンディープラーニング（LSTM）のnotebook


## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
