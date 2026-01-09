
# PDF Frame Erase & Slide Tool

本ツールは、スキャン由来の論文PDFなどに対して **枠消し（白塗り）** を行い、  
さらに **本文を左右方向へスライド** してレイアウトを整えるためのJupyter Notebookです。

以下のような用途を想定しています：

- 冊子を裁断・スキャンした PDF の左右余白が不均一  
- 本文周囲に黒筋が残ってしまう  
- 奇数／偶数ページで異なるレイアウト補正を行いたい  
- 画質劣化を避けつつ PDF の位置調整だけしたい

---

## 🚀 Google Colab で開く

以下のようなバッジを利用して Google Colab で実行できます：  
![Open In Colab](https://camo.githubusercontent.com/eff96fda6b2e0fff8cdf2978f89d61aa434bb98c00453ae23dd0aab8d1451633/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)

---

## 📘 Notebook の概要

Notebook では次の操作が可能です：

- **枠消し幅（mm）を奇数/偶数ページで個別設定**
- **本文の横方向スライド量（mm）を奇数/偶数ページで個別設定**
- **ラスタライズせず PDF を再配置するため画質劣化が起きない**
- **ページごとに逐次処理し RAM 消費を抑制**

処理後、入力ファイル名 *sample.pdf* なら *sample_rev.pdf*　として出力されます。

---

## 📝 使用方法

1. Notebook を Google Colab や GakuNin RDM、ローカルJupyterなどで開く  
2. Notebook の冒頭「設定ブロック」で以下を編集  
   - 入力ファイル名  
   - 枠消し幅（上下左右・奇数/偶数）  
   - スライド幅（奇数/偶数）  
3. PDF をアップロード（Colab などの場合）  
4. Notebook を実行

---

## 📄 ライセンス

CC0

---

## 🤝 貢献

バグ報告や改善案など歓迎します。
Issue / Pull Request をご利用ください。
