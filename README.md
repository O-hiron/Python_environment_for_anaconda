# Python_environment_foranaconda
anacondaの環境YAMLファイル置き場

# 導入方法
YAMLファイルをインストール

## anaconda navigater使用時
[Enviroments]→[import]を選択。Nameに新しい環境名、Specification Fileにインストールしたymlファイルを選択。

## Anaconda Prompt使用時
以下コマンドを打つ
```
conda env create -n 新たな環境名 -f hogehoge.yml
```
