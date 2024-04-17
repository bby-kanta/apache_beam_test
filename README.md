# 説明
Apache Beamの動作確認をするために簡単にApache Beamをローカルで動かす環境です。
input.txtの行毎に文字数を計算して、output.txtに出力します。

# 必須ツール
rye

# 使い方
```
rye fetch 3.8.13
```
Python3.8系が必要なので、Python3.8.13をryeでダウンロードする。


```
rye sync
```
.venvが作成される。


```
rye run python pipeline.py
```
output.txtが作成される。