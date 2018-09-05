# このプログラムについて

## 使用したライブラリと役割
- jupyter
- numpy==行列計算を効率的に実行する
- scipy==科学計算用のライブラリ
- pandas==データフレームを扱う
- tqdm==ループの進捗情報を表示する
- scikit-learn==機械学習用のライブラリ
- matplotlib==図を描くのに使う
- seaborn==matplotlibのラッパー

##仮想環境の作り方(仮想環境を作りたいフォルダにて実施)
python3 -m venv .venv
	現在のフォルダに仮想環境”.venv”を作成

source .venv/bin/activate
	仮想環境を有効にする。 (ターミナルを立ち上げるたびに実行すべし)

python3 -m pip install --upgrade pip
	pipのアップグレード

python3 -m pip install -r requirements.txt
	requirements.txt に書かれたライブラリを一括でダウンロードする

Memo
deactivate : 仮想環境を無効にする。 

Control + R : 過去の履歴の検索
