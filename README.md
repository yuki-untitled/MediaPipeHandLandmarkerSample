# MediaPipe Hand Landmarker サンプルの使い方

このプロジェクトは、MediaPipe Hands を使ってWebカメラから手のランドマーク（関節）をリアルタイムで検出・描画するサンプルです。  
VSCodeの「Live Server」拡張機能を使って簡単に動作確認できます。

---

## 必要なもの

- Visual Studio Code（VSCode）
- Google Chrome などのモダンなWebブラウザ
- PCのWebカメラ

---

## セットアップ手順

### 1. このリポジトリをクローンまたはダウンロード

```
git clone <このリポジトリのURL>
```
またはZIPでダウンロードして展開してください。

---

### 2. VSCodeでフォルダを開く

VSCodeを起動し、`index.html` があるフォルダを開きます。

---

### 3. Live Server 拡張機能をインストール

1. VSCode左側の拡張機能アイコン（四角いアイコン）をクリック
2. 検索ボックスに `Live Server` と入力
3. 「Live Server」by Ritwick Dey を選択し、「インストール」ボタンをクリック

---

### 4. サンプルを起動

1. `index.html` をエディタで開く
2. 右下に「Go Live」ボタンが表示されるのでクリック  
   （または、右クリック→「Open with Live Server」でもOK）

---

### 5. ブラウザで動作確認

- ブラウザが自動で開きます（例: http://127.0.0.1:5500/index.html）
- 「Start」ボタンを押すとカメラが起動し、手のランドマークがリアルタイムで描画されます
- 各関節の横に番号（0〜20）が表示されます

---

## 注意事項

- 初回アクセス時にカメラ使用許可を求められます。「許可」してください
- カメラが認識されない場合は、他のアプリでカメラが使われていないか確認してください
- `modelComplexity: 2` は一部環境で動作しません。`1` のままご利用ください

---

## 参考

- [MediaPipe Hands 公式ドキュメント](https://google.github.io/mediapipe/solutions/hands.html)
- [Live Server 拡張機能ページ](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

---