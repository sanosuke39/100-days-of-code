# 100 Days Of Code - 学習ログ

## 2022/06/12

### 今日の進捗

今日から100 Days Of Codeを始めた。
今まで放置していたEtch A Sketchのフロントエンド実装を始めた。
Storybookを導入してフロントエンドのヘッダー部分を設計。
Storybookの使い方を少し覚える１時間になった 。

I started #100daysofcode from today.
I have started the front-end implementation of Etch A Sketch, which has been neglected until now.
First, I introduced the storybook and designed a header on the front-end.
I cloud to learn about the storybook while an hour.

### 思ったこと 

Storybookはデザインをやればコードを自動生成してくれると勝手に思っていたがそんなことはなかった。

first, I thought that the storybook can be generated to component code, but couldn't.


## 2022/06/13

### 今日の進捗

react-router-domを導入して、ページ遷移をできるようにした。

まずはホーム画面とログイン画面を作成した。

introduced router and became able to page transition

first, I create home page and login page

### 思ったこと 

RecoilやStorybookに関して全く手をつけられない。
理解するのに１時間じゃ足りない。
まず質を求めるのではなく完成させるほうが大事だと思った。
この１００日間で優先して磨きたいことを考えるために、このプロダクトでやらないこととやることを決めよう。

やること

* 各種機能作成
* 全体的な状態管理

やらないこと

* デザイン
* Storybookや複雑なアーキテクチャの勉強

I cannot master recoil and storybook.
If I understand it, need to spend over 1 hour.
I thought that completing this project was more important than seeking quality.
I should create not-todo list in this project because of I want To think about what to learn in this 100 days.

todo

* create module
* react state management

not todo

* ui design
* component architecture

## 2022/06/14

### 今日の進捗
created part of the login request to the API server

APIサーバーへのログイン要求の一部を作成しました

### 思ったこと
効率的な書き方を考えることに時間を使ってしまって、先に進みませんでした。
雑でも実装をすることを優先すべきだと思った。

I spent a lot og time thinking about how to write efficiently, so I couldn't move on.
I thought that it should be prioritized to implement even if it is rough.

## 2022/06/15
### 今日の進捗
frontend: implement login module.
backend: change language from scala akka http to ts nestjs.

### 思ったこと

今日は筆が進んでいい感じだった。

機能だけに集中して取り組むことができた。

その結果ログイン機構の実装を完了することができた。

NestJS はTSなのでフロントエンド・バックエンド分ける必要がなく、単独リポジトリなので管理が楽になった。

It was a good feeling that the brush was advanced today.

I was able to concentrate on the functions.

As a result, we were able to complete the implementation of the login mechanism.

Since NestJS is a TS, there is no need to separate the front end and back end, and since it is a single repository, it is easier to manage.

## 2022/06/16
### 今日の進捗
day5:
when the user success logs in, move to the board page.

if a user is not logged in yet, redirect to the login page.

### 思ったこと
私は疲れていましたが、コードを書くことができました。

そして、私のコードの書き方が向上したと感じています。

I was tired but could write to code.

and I feel that my writing technic of code improve.
## 2022/06/17

### 今日の進捗
day6:
* backend: it gets info from the database with Prisma ORM.
* frontend:  create loader components.
### 思ったこと
コードの書き方を思い出し始めています。
また、コードの記述に集中できます。
それは良い点です。

I am beginning to remember how to write code.
And also, I can focus to write code.
it's a good point.
## 2022/06/18

### 今日の進捗
day7:
* backend: created get a board list from endpoint.
* frontend:  created a component of the board list and board edit.

### 思ったこと
私は1日目よりも速くコードを書くようになりました。
また、やりたいことが増えています。
たとえば、パスワード管理やフロントエンドUIなどです。
しかし、自分の時間は限られているので、学ぶ優先順位を考える必要があります。

I became to write code more than fast compared to day 1.
And Also, something you want to do is increasing.
for example, password management, and frontend UI.
But my time is limited. so I should get one's priorities right.

## 2022/06/19
### 今日の進捗
day8: apply formatter in all.
* frontend: edit EditBoard.tsx .

### 思ったこと
Canvas要素を学びました。
大変でした。 最近のコーディングと学習のバランスは良好です。

I learned the Canvas element.
It was difficult.
The balance between coding and learning these days is good.

## 2022/06/20
### 今日の進捗

day9: made drawing possible on board and store content.
* frontend: made drawing possible on board.
* backend: store content, get content.

### 思ったこと

キャンバスのコーディングは非常に教育的でした
画像の保存と描画は、私の未知のタイプのコーディングでした。
仕事を終えてコーディングしようとしたので疲れました。

coding of canvas was very educational.
storing images and drawing was my unknown type of coding.
I was tired because I try to code after I finished work.

## 2022/06/21
### 今日の進捗

day10: made login logic more practical.
* frontend: none.
* backend: became to made hashed password store to the users table. WIP, implement session based auth.

### 思ったこと
疲れましたが、集中できました。
今日は2時間くらいやりました。

tired, but I could concentrate.
Today, I did it for about 2 hours.

## 2022/06/22
### 今日の進捗
day11: made login logic more practical.
* frontend: none.
* backend: implement session based auth.

### 思ったこと
参考書に書かれている言葉を見落としていたので、しっかり読んでおくべきだと思いました。

I thought that I should read tight the reference manual because I overlooked the words in them.

## 2022/06/23
### 今日の進捗
day12: refactor, and session auth and board function.
* frontend: be able to session auth and create board.
* backend: create board.
### 思ったこと
リファクタ楽しかった。さほど学びはなかった。

I enjoyed refactor.
I could not so much get new knowledge.

## 2022/06/24
### 今日の進捗
day13: fix ui.
* frontend: fix ui with material-ui.
* backend: none.

### 思ったこと
午後から眠かったけど、すべてのタスクを終わらせた。よくやった！
フロントをmuiで修正した。
フロントエンドでもっとMaterial-UIを使うべきだと思いました。

I've been sleepy since the afternoon but I completed all tasks. I am great!
I fixed the UI of the front end with Material-UI.
I thought that  I should use more Material-UI on the front end.


## 2022/06/25
### 今日の進捗

day14: fix ui.
* frontend: add profile icon on header.
* backend: none.

### 思ったこと
UIの修正は好きだけど自分としてはキャンバス周りの理解を深めたり新しい機能を実装する必要があるのではと考える。

I like fixing UI but I should try to learn to canvas and implement new features.

## 2022/06/26
### 今日の進捗
day15: fix board.
* frontend: try fixing board component.
* backend: none.
### 思ったこと
キャンバスの問題解決できなかった
悲しい。。。

could not resolve the problem of a canvas.
I am sad

## 2022/06/27
### 今日の進捗
day16: try jwt auth.
* frontend: try jwt auth.
* backend: none.

### 思ったこと
認証周りについて知見が溜まった。

独自実装してもいいけど、手っ取り早く信頼性の高い認証基盤作りたいならAuth0, firebase Authあたり使ったほうがいいよ的な感じだった。

調べた資料

なんか英語書くのめんどくさくなってきた。1文だけかこう。

I am getting tired that writing a log in English. 

I try to write in only 1 sentence. 

* https://qiita.com/Hiro-mi/items/18e00060a0f8654f49d6
* https://coders-shelf.com/react-auth-problem/

## 2022/06/28
### 今日の進捗
day17: fixed jwt auth.
* frontend: fixed jwt auth and optimized import module and removed session auth.
* backend: none.

### 思ったこと

モジュール周りに関して知見が溜まった。

JWTの実装時にどのように、各クラスが関連しているかが理解できた。

I could understand better around modules.

I could understand how each class is related when implementing JWT.

調べた資料

* https://qiita.com/ekzemplaro/items/3644e60b55a38c9bdd93
* https://zenn.dev/mikakane/articles/nestjs-module
## 2022/06/29
### 今日の進捗
day18: fixing jwt auth.
* frontend: fixing jwt auth.
* backend: none.

### 思ったこと

調べていったらJWTをCookieで保管する方法でもセキュリティリスクあるみたいなことが書いてあって、これ素直にAuth0使ったほうがいいのではみたいな感じになった。

改めて自分の伸ばしたい領域を整理する必要が出てきた。

when I searched how to use JWT in SPA, I find that there is a security risk.

I thought that auth0 is better than implementation myself.

I need to think that What I should learn in this challenge again.

調べた資料
* https://tech.hicustomer.jp/posts/modern-authentication-in-hosting-spa/
* https://zenn.dev/yoneapp/scraps/a2a5f643cb845a

## 2022/06/30
### 今日の進捗

day19: implement login module with auth0.
* frontend: implement login module with auth0. environment variable call to env.
* backend: none.

### 思ったこと
auth0を利用してログイン機能を実装した。

すごく簡単だった。

I implemented a login module with auth0.

it was so easy.

## 2022/07/01
### 今日の進捗
day20: implement get board list with auth0.
* frontend: get board list with auth0
* backend: get board list with auth0

### 思ったこと
バックエンドの認証がだいぶきつかった。

I had felt hard on how to use the auth0 library in the backend.

## 2022/07/02
### 今日の進捗
day21: implement get board list with auth0.
* frontend: get board list with auth0
* backend: get board list with auth0

### 思ったこと
疲れてたけど、Auth0について1歩前進したので良しとしよう。

I was tired, but I'm glad I have taken a step forward with auth0.

## 2022/07/03
### 今日の進捗
day22: change authenticate tool from auth0 to firebase.

### 思ったこと
データ構造も単純なのでfirebase を使ってバックエンドを構築することにした。

I changed a backend-tools from nestjs + auth0 to firebase.
it doesn't need to create the backend, because the data structure of this web app is simple.

## 2022/07/04
### 今日の進捗
day23: implement create board module.

### 思ったこと
眠たい。疲れた。

## 2022/07/06
### 今日の進捗
day24: add signup.

### 思ったこと

何故かfirestoreが使えない。よくわからん。
サンプル用のコードで検証したけどそちらでは使えるから謎。

I am not knowing the reason that cannot use Firestore in React.
I inspected it to use a sample code.
I am confused because In sample code can use Firestore.

## 2022/07/06
### 今日の進捗
day25: refactor auth.

### 思ったこと
Firestoreのバグわからなくて、解決しない。。。
アプリの作成が進まない。別のアプリで違いを見て解決しようと思っている。

I cannot resolve it because I don't know the cause of the bug in Firestore.
Now, Creating App cannot move forward from its bug.
I am thinking that creating another app and trying to resolve the problem.

## 2022/07/07
### 今日の進捗
day26: fixed bug and can use firebase.

### 思ったこと
Recoil削除したら動いた。やっと別のタスクに取り掛かれる。。。

具体的な原因がわからないがそれはまた後ほど調べよう。

it became that can run result of removing Recoil.

at last, I can get started on another task.

But,  I better search for it because I don't know the cause of specific.

## 2022/07/08
### 今日の進捗
day27: boards store in firestore.

### 思ったこと
サブコレクション使ってうまいこと保存できた！

It was able to store in Firestore with a sub-collection!

## 2022/07/09
### 今日の進捗
day28: create firestore converter and refactor.

### 思ったこと
フロントを書くのが楽しくなってきた一方目標を見失いがち。

目標の再設定が必要。

I am enjoying writing code, but I cannot work on this challenge with a goal.

I need to reset a goal.

## 2022/07/10
### 今日の進捗
day29: fix Header.tsx.

### 思ったこと
なんかやることがつまらんくなっているから、プロジェクト立てた。

ここからタスクとってこう。

I created a project in the repository.

I will get a task from its project's task list.


https://github.com/sanosuke39/etch-a-sketch/projects/1

## 2022/07/11
### 今日の進捗
day30: could draw with keyboard.

### 思ったこと
タスクとった。なかなか実験的なことができた。

図らずも点線とかできて思わぬ収穫だった。

ただ線を一直線に書く必要がある。

## 2022/07/12
### 今日の進捗
day31: board button.

### 思ったこと
ボタンを利用してお絵描きできるようにした。

Stripeの登録なんかもしたので課金システムの構築やっていこう。

そう言いながら学ぶものを迷っている。もうちょっとReactに関して深入りしたほうがスキルがつくのでは？と思ったり。。。

the application became able to paint with a button.

I registered on Stripe, so I will try to implement a payment system.

I said that but I', wondering. Should I learn more about React?

## 2022/07/13
### 今日の進捗
day32: install stripe js.
### 思ったこと
stripeをマスターできると課金とかいい感じに実装できて給与上がるかも。

If I master Stripe, my pay is maybe up.

## 2022/07/14
### 今日の進捗
day33: create functions because it is implement stripe payment.

### 思ったこと
いい感じでfirebase活用している。

firebase many modules are frequently used by this application.

## 2022/07/15
### 今日の進捗
day34: became to use stripe elements #3.

### 思ったこと
functions に苦戦した. stripeの理解に関しては日々成長している

functions were hard. I am getting to grow in understanding of Stripe.

## 2022/07/16
### 今日の進捗
day35: became able to check out a board and after check out, redirect to thanks page.

### 思ったこと
仮設立てて結構あたったしいい感じで進んできた。

React力が上がっている。

関数の途中だとレンダリングが機能しない？

Firebaseのユーザーのカスタムプロファイルに関するやつ。
https://bigcodenerd.org/create-user-profile-firestore-authentication/

my  hypothesis was correct. sounds good.

I improved implement of React.

when in the middle of a function, can the variable of context be not refreshed?

it is the document of Firebase custom profile

## 2022/07/17
### 今日の進捗
day36
* feature: became able to find a checkout customer.

### 思ったこと
いろいろなものに手を出した結果より好奇心が旺盛になった。

インフラ作ったり、コードリファクタしたりしてどっぷりコードに浸かった感じがした。

By trying this challenge, I became able to be Full of curiosity about tech.

today, I wrote a code about infrastructure, front.

rarejob.com/englishlab/other/20201214_tofu/

## 2022/07/18
### 今日の進捗
github page
* create next page

### 思ったこと
ページ作成した。Chakra UIはちょっとおもしろそうな感じがする。

I created a page with next.js. I thought that Chakra UI is interesting. 

## 2022/07/19
### 今日の進捗
day38: fix ui with Chakra ui.

### 思ったこと
muiもちゃんと触っているわけじゃないけどchakra ui すごいいい感じ。

I cannot compare Chakra UI to MUI, but I thought that it is good.

## 2022/07/20
### 今日の進捗
day39: UI Framework replace complete.  MUI to Chakra UI.

### 思ったこと
UI 進化したなぁ。

my UI implementation is improving.

## 2022/07/21
### 今日の進捗
day40: draft gallery module.
* add shareable val in board
* if isShareable is true, post to gallery.

### 思ったこと

コーディングの速度上がってない?

新しい課題が見当たらないというか、ワクワクせん。。。

I look like my cording sped up.

I cannot find a new issue in the application Or say I am not excited about it.

## 2022/07/22
* day41: if the board's isShareable is true, can watch it at gallery view.

### 思ったこと

ざっくりとシェアシステム2日で作ってしまった。

他に何を課題にするべきだろうか？

I have created the Gallery system for about 2 days.

What do I create in it? 

## 2022/07/23
* specifies database URL in Firebase config file.
### 思ったこと
疲れていてちゃんとかけなかった。

明日頑張る。

I couldn't write a code because I was tired.

I retry it tomorrow.

## 2022/07/24
* rewrite vim config with lua

### 思ったこと

久々にコンフィグ書いたり別のことしてみて、リフレッシュできた。

これもまた楽しかった。

It's been a while since I wrote a config or did something else that refreshed me.
                                             
It was fun too.    

## 2022/07/25
* fix link

### 思ったこと
結構UI周りを考えるのって得意じゃないなと思った。

やってもらってもいいかもなって思った。


## 2022/07/26
* day45 create header with tailwind css

### 思ったこと
tailwind css なめてた。ちゃんと勉強せんと使いこなせない。

これやるぐらいならちゃんとプロダクト完成させるところまで持っていったほうが良さそう。

I was belittling Tailwind CSS.
I realized that I need to spend time mastering it.
completing the product is more valuable than it.


## 2022/07/27
* add all credential
### 思ったこと
すんなりfixできた。

Functionsお金が必要だって知らなかった。いくら必要化確認して、対応したい。

I resolved the problem that is easy.

there is a need to pay if using Cloud Functions. 
I didn't know it.

Today, I'll deal with it.

## 2022/07/28
### 学んだこと
* フロントエンドのテスト手法
    * テストがソフトウェアの使用方法に似ているほど、信頼性が高まります。
* 各種テスト手法のメリットデメリット
* Reactの推奨されているテストツール
* jestを使ったテストの記述方法
* testing-libraryを使ったテストの記述方法

### 思ったこと
フロントエンドのテストについての知識がまったくないので、何を書いていいのかわからなかった。

とりあえず調べることからはじめました。

https://zenn.dev/t_keshi/articles/react-test-rule
https://ja.reactjs.org/docs/testing.html

ロジックに関するユニットテストはバックエンドでも共通ですが、 コンポーネントのテストは初めてなので理解するのに苦戦しました。

I couldn't write a test code because I don't have knowledge about tests on FrontEnd.

For now, I started to research it.

First, I started to investigate for tests on FrontEnd.

Understanding A Unit test was easy because I already know the backend test.

but understanding a component test is hard.

## 2022/07/29
### 学んだこと
* コンポーネントテストの書き方
  * react router がある場合のテストの書き方
* テストの有効性
  * 自分のJSXの書き方の悪さに気づけた
  * テストしやすい形に修正できた。

### 思ったこと

テストでエラーが出ることで自分の悪い書き方を改善できてやはり有用だった。

コンポーネントの共通化と修正によりテストしやすいコンポーネント作れた。

when a test happened error, I could realize the bad part of my code.

testable of components was up because of user form is fixed and commonization.

## 2022/07/30
### 学んだこと
* テスト：https://ja.reactjs.org/docs/testing.html
  * コンポーネントツリーのレンダー をシンプルなテスト環境で行い、その結果を検証する
    * コンポーネントをレンダリングして、検証する
    * モジュールのモック
      * テストにとって本質的ではないモジュールに依存している場合に有用。
      * 方法：https://jestjs.io/docs/manual-mocks
    * ダミーデータ：https://ja.reactjs.org/docs/testing-recipes.html#data-fetching
  * E2Eテスト：アプリケーション全体の動作 をブラウザ同等の環境で検証する（end-to-end テストとして知られる）
    * リグレッションを防ぐのに有効 
    * テストは長いワークフロー、特にあなたの業務にとってとても重要なワークフロー（例えば支払いやサインアップ）をテストするのに有用です。
    * しかし実行速度に関しては考える必要がある
    * こちらではモックではなく本物のAPIエンドポイントを使うほうがいいだろう。
      * firebaseの場合はエミュレーターでもいいのでは？コード変わらないし。
* テストのTips
  * https://ja.reactjs.org/docs/testing-recipes.html

### 思ったこと
テストの書きどころについて勉強した。

Checkoutなどの処理はE2Eテストできる場所だと思うので頑張る。

I studied where and what to write a test.

The checkout process of a website is appropriate what e2e testing.

## 2022/07/31
### 学んだこと
* cypress を使ったe2eテストの書き方

### 思ったこと
e2eテストは普通のテストと考えることがちょっと違う

e2e test is different about thinking than a unit test.

## 2022/08/01
### 学んだこと
* cypress純正ではiframeに対応していないことがわかった。

### 思ったこと
iframeを利用しているので、テスト方法がだいぶきつい。

e2e test is hard because Stripe's payment system is implemented with a iframe.

## 2022/08/02
### 学んだこと
* iframeを内包した場合のテストの書き方
### 思ったこと
疲れた。

I'm tired.

## 2022/08/03
### 学んだこと
* iframeのテストについて
* cypressの各関数について
### 思ったこと
iframeのinput終わった。やった。

test of iframe is done. yes

## 2022/08/04
### 学んだこと
* rustの言語に関して
  * 明示的なキャスト
  * クロージャー
  * 並列実行
* マンデルブロ集合について
* timeコマンドの使い方
### 思ったこと
久々にRust書くと楽しい。

Writing Rust code is fun.

## 2022/08/05
### 学んだこと
* rustのポインタ
  * https://qiita.com/Kogia_sima/items/88920a2a14448ef4dbe3
* rustの文字列とファイル操作

### 思ったこと
ポインタ関連はやはりむずい。

けど学ぶことがあるのはいい。

React周りは題材を探さないでできる学ぶ題材としては頭打ち臭い。

## 2022/08/06
### 学んだこと
* Firestore のアクセスルール記載方法
* Firestoreのアクセスコントロール
### 思ったこと
アクセスコントロールが思ったよりシンプルでとっつきやすかった。

access control is easy and simple than expected.

## 2022/08/07
### 学んだこと
* 特になし
### 思ったこと
何も考えずに適切にコードを直していく作業に楽しみを感じる。

I feel fun that no thinking and fixing code.

## 2022/08/08
### 学んだこと
* Webブラウザに最適化しすぎるとスマホで扱いづらい
### 思ったこと
スマホに対応することがいかに大切かを感じた。

I feel important that the web app's UI adapt to smartphones.

## 2022/08/09
### 学んだこと
canvas は座標の管理をするとレスポンシブ対応がめんどくさい。

### 思ったこと
Canvasのレスポンシブ対応はざっくりだと結構すぐできるけど、厳密にやろうと思うときつそう。

2つぐらい選択肢を与えていい感じにするんなら結構簡単。

## 2022/08/10
### 学んだこと

* 自分はUI考えてるときのほうが利用用途とかのロジック考えつくな
  * よりアプリケーションのシステムに関しても考えている気がする

### 思ったこと

UIないがしろにしてたけど、UI考えることでシステムに関しての理解も深まっている気がしている。

## 2022/08/11
### 学んだこと
* chakra ui のダークモードとライトモードの切り替え
* FlexやTextのレイアウト

### 思ったこと
UIいじって、ユーザーの行動を想像しているときが楽しい。

my fun moment is to imagine a user's action and mess with UI in this web app.

## 2022/08/12
### 学んだこと
### 思ったこと
* 疲れた

## 2022/08/13
### 学んだこと
* shadow の使いどころ
* 指し色の概念
  * 濃い色と薄い色の使いどころ
### 思ったこと
濃い色を使いすぎるときたなくみえるなと感じた。

薄いと思っている配色でも量が多いとページがうるさくなる。


## 2022/08/14
### 学んだこと
### 思ったこと

配色を考えるとボタンなどの部品もコンポーネント化しないと、各種部品がバラバラで運用されてしまう。

## 2022/08/15
### 学んだこと
* 統計学
  * データ型
  * テーブルデータ
  * 位置の推定：平均値・中央値・パーセンタイルなど
  * 散らばりの推定：分散・標準偏差など
* R・Pythonでの記載方法

### 思ったこと
統計についてよくわからんかったし、まだわかってない

## 2022/08/16
### 学んだこと
### 思ったこと

ボード購入部分の修正が完了した。heightが100％でできない部分をもうちょっとどうにかしないと。

## 2022/08/17
### 学んだこと
### 思ったこと
UI修正に関して実装がテンプレ化してきて、実装が飽きてきた

I'm tired implementation of UI that I don't get new knowledge. 

## 2022/08/18
### 学んだこと
### 思ったこと
* 内部でwidthパーセンテージで指定
* declareってどういう意味？
* firebase auth の profile 更新用の関数分かれてて扱いがめんどくさい。

## 2022/08/19
### 学んだこと
### 思ったこと
* input file と refの使い方を学んだ
* ts上でrefを利用するとどのような型で取り扱ったらいいかわからない

## 2022/08/20
* 推定のスタンダードからデータ分布までどのように数値化するか大まかな目的に理解することができた。
* ただ詳細な言葉はやっていく中で覚えていこうと思う。 単語に関しては文脈の中で覚えることが多い。

## 2022/08/21
* 図の描画がちゃんとできるようになった。

## 2022/08/22 day72
* photoURLの登録ができた。
* ボタンクリックからファイルのアップロードまでは結構回りくどかった。
* 一旦別のプロジェクトに行きたいのでこのプロジェクトは一旦これでCloseしようと思う。

## 2022/08/23 day73
* 統計をやった
* 説明自体は分かり易いがサンプルコードとデータの整合性が取れてないので、進みが悪い

## 2022/08/24 day74
* [原本](https://github.com/gedeck/practical-statistics-for-data-scientists)のデータとコードをもとにして1章は完了した。
* やっぱりコードと結果が一致してない部分がある.

## 2022/08/25 day75
* program that run in spreadsheet and GAS until now is moving to airflow.
* As reason, GAS's code is not able to  management. I want to manage in Github.

## 2022/08/26 day76
* implement of Oauth 2 authentication is not remember.
* if end of implementation it, I will write doc about it.

## 2022/08/27 day77
* I am implementing auth process with fitbit API and Python.
* I found that don't understand about string and ascii when implement code.

## 2022/08/28 day78
* I learned statistics that sample and population.
* I could understand it with comparative ease.
* I hope It is not the Mt stupid. 

## 2022/08/28 day79
* PKCE周りの対応をできるようにした。
* ASCIIとSha256って書いてあってurandomが素でどこにあるのかわかんなかった。

## 2022/08/30 day80
* クライアント周りの実装は一旦完了。もうちょいリファクタと関数分割していこう

## 2022/08/31 day81
* やっぱりある程度解決している問題はモチベーションわかない。
* 管理だけがモチベーションの源泉としては弱いと感じた。
* 技術的にやってみたいみたいな感じでとりま自分の使いたいツールを作るというのは個人的なものとあっていると思った。

## 2022/09/01 day82
* eslint prettier周りを導入。時間があるときにテンプレ作る。
* Draft.JSとりあえず入れたけど、ちゃんとエディタ系のライブラリ選定するべきだった。
* やっっている途中でエディタからやらなくても、大枠のレイアウトだけ決めてしまうっていうのもありかもと思った。
