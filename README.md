# アプリケーション名
衣装交換アプリ　(SnowClothes)
## アプリケーション概要

ダンサーによるダンサーのための洋服交換アプリケーションです。


## URI
```


```

## テスト用アカウント
google-login-account:

password:

## 利用方法
まず、自分の既に持っているgoogle accountでログインします。その後、自分が使えそうな衣装（洋服）記事をクリックして、衣装の詳細画面へ移動します。詳細画面では「いいね！」や「コメント機能」が使えるようになっており、この衣装を実際に貸してほしくなった場合には「レンタルリクエストボタン」をクリックすることで、その記事の投稿者に一覧として表示されるようになります。投稿者側は「レンタルリクエスト」一覧の中から一人貸し出す人物を選び、「貸し出し許可ボタン」を押すことでその人物宛のメールフォームが表示されるので件名、本文を入力し送信します。レンタルリクエスト申請者は送られてきたgmailに投稿者のmailが書かれているので、そこ宛に返信することで両者のマッチングが成立します。

## 目指した課題解決

学生ダンサーの大きな悩みの１つである。毎回の衣装代の出費を抑え、友達間でしか行われていない衣装（洋服）の貸し出しをサークル全体で行えば新しい交流が生まれ、金銭にとらわれず気兼ねなくダンスができること。

## 実装した機能
コロナ禍で加入しているサークルにてGoole Accountを作成したので、Google Accountログイン機能を付けました。また、サークル内で利用するために作成したので、「LINEログイン機能」も追加しました。ログインしなくとも投稿一覧は見ることができますが、ログインすることで投稿、いいね！、コメント機能、レンタルリクエスト機能が使用可能になります。レンタルリクエストが承認され両者をアプリ外でもマッチングさせるためにメール機能も付けました。また、投稿の際、タグを選択することで利用者が自分が欲しい衣装（洋服）を見つけやすいようにしました。

## 実装予定の機能
bladeをすべhtmlで作成したことで、行数が多くわかりにくくなったため、Reactでシンプルかつ、効率的に書き直します。また、gmailで行っていたリクエスト承認後のメールもLINEチャットボットで行えるようにしたいと考えています。


## デモ
####  ログインページ
![alt](![スクリーンショット (49)](https://user-images.githubusercontent.com/87055309/144759867-6642c90c-0116-4439-8eb6-3a5aab1624fd.png)

#### ログイン後の投稿一覧ページ
![alt](![スクリーンショット (50)](https://user-images.githubusercontent.com/87055309/144759897-bd1e76fe-fe08-4996-9b4f-2137094261c7.png)

#### 投稿ページ
![alt](![スクリーンショット (51)](https://user-images.githubusercontent.com/87055309/144759923-4ef69b79-2924-48e3-bd7f-b02200c0e9ab.png)

#### 編集画面ページ
![alt](![スクリーンショット (56)](https://user-images.githubusercontent.com/87055309/144759934-8ccdc817-2d8a-44d4-8735-707f5084c17a.png)

#### 投稿詳細ページ（投稿者）
![alt](![スクリーンショット (52)](https://user-images.githubusercontent.com/87055309/144759949-e7a06e31-5393-490e-86b1-0fc57c6da641.png)

![alt](![スクリーンショット (54)](https://user-images.githubusercontent.com/87055309/144759967-5971749d-2f92-4ceb-8c56-df37597a8364.png)

![alt](![スクリーンショット (55)](https://user-images.githubusercontent.com/87055309/144759971-35e6d3c7-1b6d-4849-8f83-18a1a24ecbf0.png)

#### 投稿詳細ページ（閲覧者）
![alt](![スクリーンショット (57)](https://user-images.githubusercontent.com/87055309/144760031-bda8ffea-004a-49d1-b6af-91dd099d8328.png)

![alt](![スクリーンショット (58)](https://user-images.githubusercontent.com/87055309/144760050-2cb3dc34-be5c-4b1d-9811-e21e0237a1a4.png)


#### タグ検索ページ
![alt](画像URL)
#### 受信メール
![alt](![スクリーンショット (62)](https://user-images.githubusercontent.com/87055309/144760549-4f86c24a-a314-4564-99fa-d20e9935cca6.png)
)


