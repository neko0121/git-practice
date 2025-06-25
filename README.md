# git-practice

Gitの練習用リポジトリ

## ファイル説明

- `hello.txt`: Gitの基本的な操作（add/commit）を試すために作成したファイルです。簡単な挨拶文が入っています。
- `info.txt`: リポジトリの目的や更新日を記録するためのファイルです。ブランチ操作の練習にも使用しました。
- `data_processor.py`: Pythonで書かれたデータ処理スクリプトです。`input_data.txt`からデータを読み込み、閾値以上のデータを抽出して`output_report.txt`に結果を出力します。

## 使い方（data_processor.py）

1.  `input_data.txt` を用意します（スクリプト実行時に自動生成されます）。
2.  以下のコマンドでスクリプトを実行します。
    ```bash
    python data_processor.py
    ```
3.  `output_report.txt` に処理結果が出力されます。