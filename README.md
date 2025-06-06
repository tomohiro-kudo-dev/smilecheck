# 😊 smile check｜笑顔チェックツール

**smile check** は、美容部員や接客業の方向けに開発された笑顔チェックWebツールです。  
カメラで撮影した表情から口角の動きや唇の開き具合を検出し、スコア化してリアルタイムで表示します。

「出勤前30秒、あなたの笑顔を整える。」そんな日々のルーティンに。

---

## 🌟 デモページ

👉 [smile check を使ってみる](https://tomohiro-kudo-dev.github.io/smilecheck/)

---

## 🧠 概要

このツールは、**MediaPipe FaceMesh** を使って笑顔の「自然さ」を測定し、スコアとコメントを表示します。  
ユーザーのブラウザにローカル保存されるため、スコア履歴の確認も可能です（最大5件まで）。

---

## 🛠 使用技術

- HTML / CSS / JavaScript
- MediaPipe FaceMesh（顔のランドマーク検出）
- localStorage（履歴保存）
- GitHub Pages（ホスティング）

---

## 📐 スコア判定ロジック

- **口角の横幅** と **唇の上下の開き** を元にスコアを計算
- スコアが一定以上の場合、笑顔アニメーション表示（😊 Good Smile!）
- 3秒間笑顔をキープすると判定完了

---

## 📊 スコア履歴

- ユーザーのローカル環境に保存（localStorage）
- 過去5件までのスコア履歴を表示

---

## 📷 スクリーンショット

> ※ `sample-smile.jpg` などの画像を `images/` に入れたら貼れます

---

## 👤 制作

Tomohiro Kudo
経理とプログラミングのハイブリッド人材。  
煩雑で属人化しがちな業務を「仕組み化」して、人生の時間を取り戻す活動をしています。

---

## 📄 ライセンス

MIT License
