# Python_environment_for_anaconda
anacondaの環境YAMLファイル置き場

# 導入方法
YAMLファイルをインストール

## anaconda navigater使用時(GUI操作)
[Enviroments]→[import]を選択。Nameに新しい環境名、Specification Fileにインストールしたymlファイルを選択。

## Anaconda Prompt使用時(CUI操作)
以下コマンドを打つ
```
conda env create -n 新たな環境名 -f hogehoge.yml
```
