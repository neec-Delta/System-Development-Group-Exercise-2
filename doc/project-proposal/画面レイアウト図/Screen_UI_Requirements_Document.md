# UI要件定義書
## 設計の前提条件
1. このシステムは会社の従業員データベースと連携します。
1. あらかじめ１つ以上の管理者権限をもつアカウントが設定されていて、その他のアカウントを追加する際はこのシステムを使って追加する。
1. アカウント登録は管理者が行い、パスワード登録はユーザー側で行う
## ログイン画面
ユーザIDとパスワードを入力・照合してログインするための画面。<br>
ユーザIDとパスワードの入力欄とログインボタンがある。
![ログイン画面](./image/[LO01]Login.png)

## パスワード設定画面
パスワードの設定は従業員本人が行う
パスワードは2回入力させる。
![パスワード設定画面](./image/[Pa01]Password_setting.png)

## サイドバー
機能ごとに分かれている画面に移動するためのメニュー画面。<br>
基本的には隠れていて左上のアイコンをクリックすると表示される。
![サイドバー](./image/[SB01]SideBer.png)

## 機能ごとの画面
### チェックイン・チェックアウト
チェックイン・チェックアウトのメニュー画面
![チェックイン・チェックアウト](./image/[CH01]CheckIN_or_OUT.png)
#### チェックイン
1. **入力画面**
   - お名前
   - 電話番号
   - メールアドレス

   ![チェックイン-入力](./image/[CH02]CheckIN_input.png)
1. **確認画面**
   - 氏名
   - 部屋番号
   - プラン料金
   - 領収書印刷

   ![チェックイン-出力](./image/[CH03]CheckIN_confirmation.png)

#### チェックアウト
1. **入力画面**
   - 部屋番号

   ![チェックアウト-入力](./image/[CH04]CheckOUT_input.png)
1. **確認画面**
   - 氏名
   - 領収書印刷

   ![チェックアウト-出力](./image/[CH05]CheckOUT_confirmation.png)

### 顧客情報
顧客情報のメニュー画面
![顧客情報](./image/[CI01]Customer_information.png)
#### 登録
1. **入力画面**
   - 名前
   - ふりがな
   - 電話番号
   - メールアドレス
   - 住所
   - 性別
   - 職業

   ![顧客情報-登録-入力](./image/[CI02]Customer_information_registration_input.png)
1. **確認画面**
   - 名前
   - ふりがな
   - 電話番号
   - メールアドレス
   - 住所
   - 性別
   - 職業

   ![顧客情報-登録-確認](./image/[CI03]Customer_information_registration_confirmation.png)
#### 更新
1. **検索画面**
   - 氏名
   - 電話番号
   - メールアドレス

   ![顧客情報-更新-検索](./image/[CI04]Customer_information_change_search.png)
1. **入力画面**
   - 名前
   - ふりがな
   - 電話番号
   - メールアドレス
   - 住所
   - 性別
   - 職業

   ![顧客情報-更新-入力](./image/[CI05]Customer_information_change_input.png)
1. **確認画面**
   - 名前
   - ふりがな
   - 電話番号
   - メールアドレス
   - 住所
   - 性別
   - 職業

   ![顧客情報-更新-確認](./image/[CI06]Customer_information_change_confirmation.png)
#### 削除
1. **検索画面**
   - 氏名
   - 電話番号
   - メールアドレス

   ![顧客情報-更新-検索](./image/[CI07]Customer_information_deletion_search.png)
1. **確認画面**
   - 名前
   - ふりがな
   - 電話番号
   - メールアドレス
   - 住所
   - 性別
   - 職業

   ![顧客情報-更新-確認](./image/[CI08]Customer_information_deletion_confirmation.png)

### 予約情報画面
予約情報のメニュー画面
![予約情報画面](./image/[ReI01]Reservation_information.png)
#### 予約情報編集
1. **予約情報検索画面**
   - 氏名
   - 電話番号
   - メールアドレス

   ![予約情報検索画面](./image/[ReI02]Reservation_information_search.png)

1. **予約情報表示画面**<br>
日付を選択するとその日の部屋の予約情報が表示される
![予約情報表示画面](./image/[ReI03]Reservation_information_show.png)

1. **予約情報登録入力画面**<br>
予約情報検索画面で顧客情報を入力していて、予約したい部屋の情報も予約情報表示画面で選択した部屋なので残りの情報を入力する。
   - 宿泊日数
   - 朝食の有無

   ![予約情報登録入力画面](./image/[ReI04]Reservation_information_input.png)
1. **予約情報登録確認画面**
   - 氏名
   - 日付
   - 宿泊日数
   - 部屋タイプ
   - 朝食
   - 料金

   ![予約情報登録確認画面](./image/[ReI05]Reservation_information_registration_confirmation.png)
1. **予約情報選択画面**<br>
予約情報表示画面ですでに自分が予約済みの部屋を選択した時に変更するか、削除するかを選択するための画面
![予約情報選択画面](./image/[ReI06]Reservation_information_select.png)
1. **予約情報変更画面**
   - 宿泊日数
   - 朝食の有無

   ![予約情報変更画面](./image/[ReI07]Reservation_information_change.png)
1. **予約情報変更確認画面**
   - 氏名
   - 日付
   - 宿泊日数
   - 部屋タイプ
   - 朝食の有無
   - 料金
![予約情報変更確認画面](./image/[ReI08]Reservation_information_change_confirmation.png)
1. **予約情報削除確認画面**
   - 氏名
   - 日付
   - 宿泊日数
   - 部屋タイプ
   - 朝食の有無
   - 料金
![予約情報削除確認画面](./image/[ReI09]Reservation_information_deletion_confirmation.png)


#### 予約検索(表示・印刷)

### 請求書・領収書
基本的にはチェックイン・アウトのときに発行する
- 請求書
- 領収書

### 従業員情報
氏名・フリガナは会社の従業員データベースから取ってくる
社員IDを入力し、ボタンを押すと氏名・フリガナが自動入力される機能がある。
![従業員情報](./image/[EI01]Employee_information.png)
#### 従業員情報登録
社員IDを入力し、ボタンを押すと氏名・フリガナが自動入力される<br>
管理者権限の付与もこの段階でできる(更新でもできる)。
![従業員情報登録](./image/[EI02]Employee_information_registration.png)
#### 従業員情報更新
管理者権限の付与とパスワードの削除ができる。
![従業員情報更新](./image/[EI03]Employee_information_change.png)
#### 従業員情報削除
従業員情報を削除するのみ。
![従業員情報削除](./image/[EI04]Employee_information_deletion.png)

### 部屋情報
部屋情報のメニュー画面
![部屋情報](./image/[RoI01]Room_information.png)
#### 登録
1. **入力画面**
   - 部屋番号
   - 部屋タイプ
   - 価格

   ![部屋情報-登録-入力](./image/[RoI02]Room_information_registration_input.png)
1. **確認画面**
   - 部屋番号
   - 部屋タイプ
   - 価格

   ![部屋情報-登録-確認](./image/[RoI03]Room_information_registration_confirmation.png)
#### 更新
1. **検索画面**
   - 部屋番号

   ![部屋情報-更新-検索](./image/[RoI04]Room_information_change_search.png)
1. **入力画面**
   - 部屋番号
   - 部屋タイプ
   - 価格

   ![部屋情報-更新-入力](./image/[RoI05]Room_information_change_input.png)
1. **確認画面**
   - 部屋番号
   - 部屋タイプ
   - 価格

   ![部屋情報-更新-確認](./image/[RoI06]Room_information_change_confirmation.png)
#### 削除

1. **検索画面**
   - 部屋番号

   ![部屋情報-更新-確認](./image/[RoI07]Room_information_deletion_search.png)
1. **確認画面**

   - 部屋番号
   - 部屋タイプ
   - 価格

   ![部屋情報-更新-確認](./image/[RoI08]Room_information_deletion_confirmation.png)

