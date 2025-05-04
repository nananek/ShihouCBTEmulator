# CBT答案エディタ

司法試験・予備試験・旧司法試験・模試などに対応した、CBT形式の答案作成支援アプリケーションです。  
原稿用紙風の入力欄に、全角30文字×最大184行の答案を自動整形しながら入力できます。

📄 公開ページ: [https://nananek.github.io/ShihouCBTEmulator/](https://nananek.github.io/ShihouCBTEmulator/)

---

## ✨ 主な機能

- 全角文字を自動変換（半角→全角）
- 30文字単位で自動折り返し
- 行数・文字数のリアルタイムカウント
- 行番号の表示
- タイトル・年度・科目・行数制限などの設定
- JSONファイルへの保存・読み込み
- 印刷用スタイル対応
- フォント自動調整（游明朝／MS明朝／ヒラギノ明朝／Noto Serif）
- GitHub Pages上で完全クライアント動作

---

## 🚀 利用方法

1. [公開ページ](https://nananek.github.io/ShihouCBTEmulator/) にアクセス
2. 「新規答案作成」タブで試験情報を入力
3. エディタに答案を記入（30文字ごとに自動整形されます）
4. 「終了」ボタンでJSON保存（自動で初期画面へ戻ります）
5. 後日、同じJSONファイルを読み込んで再編集も可能

---

## 📦 開発構成

- HTML / CSS / JavaScript（Vanilla）
- Bootstrap 5.3
- GitHub Pages による静的公開

---

## 🖨 印刷対応

ブラウザの印刷機能でそのまま印刷できます（背景線を出力するには「背景グラフィックを印刷」を有効にしてください）。

---

## 📄 ライセンス

MIT License  
(C) 2025 Nekono Nana KAKKO KARI
