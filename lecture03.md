#  第3回課題

##  アプリケーションの起動確認
<img width="1396" alt="アプリ稼働確認 2023-11-23 11 30 13" src="https://github.com/hachi8888888/lecture03/assets/148927545/df1f831b-30ab-4d0a-b131-4ad8d857fc25">

## 調べた事
1. APサーバーの名　Puma >rails s　実行時に確認
2. APサーバーのバージョン　5.6.5　
3. APサーバー終了時の挙動
<img width="1434" alt="APサーバー停止時の挙動 2023-11-25 13 34 57" src="https://github.com/hachi8888888/lecture03/assets/148927545/f92d904f-93c1-4592-8839-a8519f59c722">

5. DBサーバー名　MySQL　＞MySQL　サインイン時に確認
6. DBサーバーバージョン　8.0.35 for Linux on x86_64 (MySQL Community Server - GPL)
7. DBサーバー終了時の挙動
<img width="1434" alt="DBサーバー停止時の挙動 2023-11-25 13 39 12" src="https://github.com/hachi8888888/lecture03/assets/148927545/497c41ed-448c-438e-b928-08564810be56">

8. Railsの構成管理ツール名 bundler 2.3.14　＞bin/setup　実行時に確認

## 学んだ事
- APとDBでそれぞれサーバーがあって、両方が稼働していないとアプリケーションは動かない事が分かった。
- アプリケーションを動かすにあたり、色んな言語(?)を扱うし、各々のバージョンを揃える必要があるので大変。でもちゃんとエラーで示してくれるので賢い。
- エラーが出る原因について調べたら、どういった対処ができるのか判断するためにはそれぞれのコンテンツ(?)を動かすにあたりどういう要素が必要なのかを把握しておく必要がある。今は親切な人のまとめサイトに頼りっきりだけど、いつかは自分の頭の中で原因の候補を出せるようになりたい。
