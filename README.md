# amomo0220 Portfolio

静的 HTML + CSS のミニマム構成。GitHub Pages で公開。

## 公開手順
1. GitHub でリポジトリ作成（例: `portfolio`）
2. 本リポジトリに `index.html` ほか一式を追加して `main` に push
3. Settings → Pages → Branch を `main` / Folder を `/ (root)` に設定 → Save
4. 公開 URL: `https://amomo0220.github.io/portfolio/`

## サーバー起動方法

以下コマンドを実行
```bash
bundle exec jekyll serve --livereload --host 0.0.0.0 --port 4000 --trace
```


## 今後の拡張（予定）
- About の内容を充実させる
- Projects に実績の掲載
    - 実績を列挙
    - 実績の詳細を掲載
- UI改善
    - Skills を見やすく
    - テーマカラーの変更
    - （各タイトル等をイラストにしたい！）
