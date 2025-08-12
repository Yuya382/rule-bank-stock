# RuleSync

## もしくは既存のrulesを取り込んで `.rulesync/*.md` を作成

## （Cursor Project Rulesの例）

`npx rulesync import --cursor`
ルールファイルの一括生成、rulesyncファイルの追加は以下のコマンドです。

## 対応ツール全てを対象にルールファイルを生成

`npx rulesync generate`

## 特定ツールのみ対象にルールファイルを生成（CursorとClaude Codeの例）

`npx rulesync --cursor --claudecode`

## rulesyncルールファイルを追加

`npx rulesync add new-rule.md`