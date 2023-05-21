# Seat-Reservation.ver1
Google Apps Script で書き、Slack API と連携させた座席予約用のアプリケーション (ver1) です。

座席の取り合いになることを回避する目的で作成しました。

## プレビュー

### images
<div>
  <p align="center">
    <img width="80%"src="https://github.com/Fuyuki006/Seat-Reservation/assets/125243602/55e8ebad-a11e-4940-9c5c-6c8196a1314d">
  </p>
</div>
                                                                                                                           
<div display="flex">
  <p align="center">
    <img width="40%" src="https://github.com/Fuyuki006/Seat-Reservation/assets/125243602/edac7444-c6fa-45b4-a2c7-a48f39659284">  
    <img width="40%" src="https://github.com/Fuyuki006/Seat-Reservation/assets/125243602/90136db1-58fb-4df1-ac55-98d93a61e1e8">
  </p>
</div>

### gifs

#### 座席の予約
![Videotogif](https://github.com/Fuyuki006/Seat-Reservation/assets/125243602/fac33e2a-7b3d-4c1b-89bd-040fc5ec8d6a)

#### 予約の確認
Slack に埋め込んだ、座席を確認するためのスプレッドシート上での確認

![download](https://github.com/Fuyuki006/Seat-Reservation/assets/125243602/fb1e7889-8449-42da-890e-0b9357a635c7)

## 実装手順
- ソース(Google Apps Script) のダウンロード
- スプレッドシートの作成
  - 座席確認用シート
  - ソース管理用シート (無くても良い)
  - 座席予約のデータ管理用シート

## 注意



## 使い方
-

## 使用している技術

### Google Apps Script
- サーバーレスでアプリケーションが作成できること
- 見やすさの面も考慮して、座席の予約状況を管理するだけなら Google スプレッドシートで十分

という点から使用。

### Slack API
- コミュニケーションツールとして、Slack が使用されていた
- Slack で既に備わっている便利な機能も使えたから (メンション，DMなど)

という点から使用。

## 主な機能
- 座席の予約
- 予約の確認
- スプレッドシートの自動更新 (予約確認のためのシート)


## 改善点
- 座席予約のためのSlack 上にある UI
- 座席予約状況の表示 (配色)
- 機能の追加 (削除機能など)
- プログラムの可読性
