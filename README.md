# db-training
DB課題の環境用リポジトリです。

DB操作で日本語を打っても解決できない場合は以下を試してください。
1. MySQLのコンテナに入っている状態で以下のコマンドを打つ。
  ```bash
  echo $LANG
  ```
  
2. `ja_JP.UTF-8 `と表示されているか確認する。異なる場合は以下のコマンドを打ちましょう。
```bash
  export LANG=ja_JP.UTF-8
  export LC_ALL=ja_JP.UTF-8
```

3. 日本語が打てるか確認してみてください。
