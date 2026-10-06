# LuzCity rule docs

## ルール変更の反映

- ルールを変更したら、その都度 `main` に直接コミットして push する（ブランチ・PR は作らない）。push で GitHub Pages が自動デプロイされる。
- `index.html`（サーバールール）や `pages/crime-rules.html`（犯罪共通ルール）を変更したら、`rule.txt` の該当セクションにも同じ内容を反映する。
- コミットメッセージは `docs: 〜を追加` / `docs: 〜に変更` の形式。

## 作業環境

- リポジトリは root 所有。ファイル編集・git 操作は `sudo` で行う（例: `sudo git -c safe.directory=/home/docs commit`）。
- コミットに含めるのは今回変更したファイルだけにする。
