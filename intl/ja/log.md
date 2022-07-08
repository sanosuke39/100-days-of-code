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

[//]: # (## 日付)
[//]: # (### 今日の進捗)
[//]: # (### 思ったこと)
