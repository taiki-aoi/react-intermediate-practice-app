# 実践アプリの作成(Chakra UI)
[コミット履歴](https://github.com/reachscript-jak/react-intermediate-practice-app/commits/main)からある程度レクチャー毎のコミットが確認できます

# 新しいリアクトアプリを作る
npx create-react-app react_test
cd react_test

その後 githubのsrcとpublicとpackage.jsonとtsconfig.jsonを上書きする
上書き後に以下を実施する
レガシィを指定しないとエラーとなるため

npm i --legacy-peer-deps

# 上記だと実行時にエラーになるのでこちらで修正
npm audit fix --force
# 実行
npm start lint -s