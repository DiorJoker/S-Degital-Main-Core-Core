# S-Degital-Main-Core-Core

## S-Degital-Main-Core-Coreを略して、SDMCC

S-Degitalの最もコアのみに焦点を当てたアプリケーション






# アプリ概要

### エレベータービッチ

#### 管制の高橋さん

伊藤：あ、お疲れ様です。

高橋さん：お、お疲れ。

伊藤：管制の人って、残業多いですか？

高橋さん：う〜ん、そこそこかな

伊藤：255個もある現場を6人で回すって、大変そうですね

高橋さん：まあ、仕事だからね

伊藤：もし、案件を自動保存して、ボタンクリックだけで送信できたら、楽になります？

高橋さん：あー、それはだいぶ楽になるね！





#### 警備の坂井さん

坂井さん：おはようございます。

伊藤：おはようございます。

坂井さん：今日、電車が遅れて遅刻しそうでした。

伊藤：いやぁ〜、遅延勘弁してほしいっすよね〜

坂井さん：ですね...毎回、通勤経路調べんの、マジだるいっすよね

伊藤：そうっすよね...



**じゃあ、ここを繋げて課題解決しよう**



### どんなアプリか（一言で）


「無駄な情報処理作業の手間を無く」 したい

「'自分'や'他の警備員'と'いつも私たちの現場を配慮しながら決めてくれている管制の方々'」 向けの
「S-Digital（略して、S-Degi(エスデジ)）」 は

「業務系アプリケーション」 です。


これは 「ユーザーの作業量と作業時間の短縮をする」 ことができ、

「システムを使っていないとき」 とは違って、

「大いに、時間が削減され、非常に利用価値」 がある。



### アプリ機能

#### 管制アカウントの機能

- 管制から、警備員に現場の指示依頼
- 警備員の返信を確認
- 明日の現場一覧を閲覧
- 現場の確定具合の確認
- 新規案件の追加
- 会社が保有してる警備員の一覧を閲覧
- 個々の案件の詳細を確認/変更/案件自体の削除



#### 警備員アカウントの機能

- 送られてきた明日の現場の確認/返信
- 過去、自分が行った現場の一覧を閲覧
- 過去、自分が行った個々の現場を閲覧
- 決まった明日の現場の詳細を確認



#### アプリの自動機能

- 住所から、マップ上に、ピンを立てる
- 住所から、`NAVITIME API`を使用し、電車の経路を出してくれる
- 明日の天気予報を、取得し、表示



# ペルソナ（ユーザー像）

・管制の人

・警備の人

# 簡単なワイヤーフレーム

## 警備員アカウント





### 明日の現場ページ

![スクリーンショット 2024-02-29 20.29.58.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/352ec76d-6329-f9ed-47f5-050534194ac0.png)


### 明日の現場ページ

![スクリーンショット 2024-02-29 20.30.02.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/a36a56c6-bb58-97c0-7ac4-c4ab4567b2fa.png)


### 過去の現場履歴ページ

![スクリーンショット 2024-02-29 20.30.06.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/b471a8e8-4414-f90e-beab-d9253e0846de.png)


### 許諾後の明日の現場ページ

![スクリーンショット 2024-02-29 20.30.10.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/dafeb7a6-f32a-9625-dfeb-64096d3fc025.png)




## 管制アカウント



### 未定現場一覧ページ

![スクリーンショット 2024-02-29 20.30.59.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/4711aa3f-a6a0-5db8-7372-4b3dd349e246.png)


### 現場案件一覧

![スクリーンショット 2024-02-29 20.31.04.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/546c5eda-8642-e203-23c1-4fe424c709c2.png)


### 案件登録ページ

![スクリーンショット 2024-02-29 20.31.09.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/9f13c863-c0fd-f4c5-52ce-ea05705a73f6.png)


### 隊員一覧

![スクリーンショット 2024-02-29 20.31.13.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/97f24139-d061-9584-fb6c-f30757053ed2.png)


### 通知一覧

![スクリーンショット 2024-02-29 20.31.17.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/3880ff2b-22d4-2dd9-fe39-9aa002cde294.png)


### 個別の案件ページ

![スクリーンショット 2024-02-29 20.31.22.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/ec014f0c-c2bb-ff30-c8db-575227cc4fc6.png)


### 依頼ページ

![スクリーンショット 2024-02-29 20.31.26.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/e59728f0-b108-4ec7-162a-9867fab6da39.png)



### 既定現場一覧ページ

![スクリーンショット 2024-02-29 20.38.46.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3586858/1a5a2a15-fe72-559d-283b-6deeabfe48f6.png)




# 最後に

背景がわからなければ、[こちら](https://qiita.com/delsan/items/0cb9563f1f2490aa808d)をご覧いただけますでしょうか。
