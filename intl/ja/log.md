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

[//]: # (## 日付)
[//]: # (### 今日の進捗)
[//]: # (### 思ったこと)
