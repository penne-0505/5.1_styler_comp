# 5.1_styler_comp

ChatGPT 5.1 (thinking) スタイラー比較プロジェクト

## 概要

このプロジェクトは、LLMの異なるスタイラー（ChatGPT 5.1 thinking styleを含む）による出力の差異を検証・比較するためのものです。複数のスタイラーと、それを検証するための複数の入力例（設問）を用いて、体系的な比較分析を行います。

## ディレクトリ構成

```
5.1_styler_comp/
├── inputs/              # テスト用の入力ファイル（設問）
│   ├── README.md       # 入力ファイルの説明
│   ├── input_001.txt   # サンプル入力1
│   ├── input_002.txt   # サンプル入力2
│   └── input_003.txt   # サンプル入力3
│
├── outputs/             # 各スタイラーの出力結果
│   ├── README.md       # 出力ディレクトリの説明
│   ├── styler_a/       # スタイラーAの出力
│   │   └── README.md
│   ├── styler_b/       # スタイラーBの出力
│   │   └── README.md
│   └── styler_c/       # スタイラーCの出力
│       └── README.md
│
├── comparisons/         # スタイラー間の比較結果
│   └── README.md       # 比較方法とテンプレート
│
├── docs/                # プロジェクトドキュメント
│   ├── README.md
│   ├── usage_guide.md            # 使用方法ガイド
│   └── styler_specifications.md  # スタイラー仕様書
│
└── README.md            # このファイル
```
