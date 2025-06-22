# 🚀 Minimal Cyber Blog Template

このリポジトリは、GitHub と GitHub Pages を使って誰でも簡単に始められる「ミニマルなブログテンプレート」です。

## ✅ 特徴
- 投稿は GitHub の Issue を使ってフォームから作成
- GitHub Actions により自動で HTML を生成 & `index.html` を更新
- 最小限のスタイルで軽量・高速表示
- デザインは自由にカスタマイズ可能

---

## 🌱 ブログを始める方法（3分で完了！）

### 1. GitHub アカウントを作成
まだ GitHub アカウントを持っていない方は、以下から無料で作成できます：
👉 https://github.com/signup

### 2. テンプレートをコピー（Use this template）
- このページ右上の [Use this template] ボタンを押す
- 任意のリポジトリ名を入力 → [Create repository from template]

### 3. GitHub Pages を有効にする
- コピーされたリポジトリに移動
- [Settings] → [Pages] を開く
- "Branch: main / (root)" を選択して [Save]
- 数十秒後にあなたのブログが公開されます 🎉

### 4. 投稿してみる
- あなたのブログ URL に `/submit.html` をつけてアクセス（例：https://yourname.github.io/blog/submit.html）
- 投稿フォームに「タイトル」「日付（空欄でOK）」「本文」を入力して [投稿する]
- 自動で `postX.html` が作成され、`index.html` にも反映されます（1〜2分かかることがあります）

---

## 🛠 構成ファイル
- `index.html`：トップページ（最新3件を表示）
- `postX.html`：記事ページ（自動生成）
- `submit.html`：投稿フォーム
- `generate-from-issue.js`：Issueから投稿を作成
- `generate-index.js`：postX.html を読み込み index を自動更新
- `.github/workflows/`：上記スクリプトを動かすGitHub Actions

---

## 🖌 カスタマイズしたい？
- `style.css` を編集してデザイン変更できます
- 投稿フォーマットやファイル名ルールも調整可能

---

## 🔁 友達にもシェアしよう
このテンプレートは増殖型！

`index.html` にある「Start Your Blog」リンクから、誰でも自分のブログを始められます。  
拡散・再発酵、歓迎。

---

## 💬 お問い合わせ
バグ報告・改善提案などは Issue や Pull Request でどうぞ！

---

© 2025 cyber-nostalgia-template
