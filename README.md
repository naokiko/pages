$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com

$ git config user.name "John Doe"
$ git config user.email johndoe@example.com

---

alias  $ ./node_modules/.bin/tsc test2.ts
entity $ ./node_modules/typescript/bin/tsc test.ts
$ node test.js

<a target="_blank" href="https://qiita.com/kurogelee/items/cf7954f6c23294600ef2">VSCodeでTypeScript/Node.jsの開発環境を作る（UT・カバレッジ・ログ出力・リリース手順含む） - Qiita</a>

mkdir tstest
cd tstest
npm init -y
mkdir .vscode src test config
npm i -DE typescript ts-node 
./node_modules/.bin/tsc --init 
[EDIT] tsconfig.json 
