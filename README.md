# ACU Tracker

DevinのACU使用状況を表示するChrome拡張機能

# Features

## Core

- UIの表示/非表示を切り替えられる
- Content Scriptで、`Usage & Limits`ページを定期的にポーリングして、ACU使用状況を取得する

## Extra

- ユーザーとDevinのチャット履歴から、Devinの稼働時間を計算し、時間あたりのACU効率 (min / ACU) を表示する
- 同様に、ACUあたりのコスト効率 (USD / ACU) を表示する

# Security

- 動作に必要な最小限の権限を用いる
- ユーザーに対して、いかなる情報も外部に送信しないことを明示する

# Debug

```sh
$ npm install 
$ npm start # ./build/ に出力される
```

1. Chromeで `chrome://extensions/` にアクセスする
2. `Load unpacked` をクリックし、`./build/` を選択する
3. 拡張機能が表示される


