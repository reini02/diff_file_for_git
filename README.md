# 納品ファイル作成ツール（Git）

## 事前準備

1. [Python 3系をインストール](https://www.python.org/downloads/)
2. `$ pip install gitpython`を実行し、インストール

## 使用方法

1. init.pyがあるディレクトリにて`$ python run.py {/path/to/} {/output_folder/path/}`を実行
  - 第一引数にGitディレクトリ(.gitがあるフォルダ）を指定。第二引数に出力したいフォルダを指定。
2. 指定したアプトプットフォルダに差分ファイルが作成される