# UI要件定義書
## ログイン
ユーザIDとパスワードを入力・照合してログインするための画面。<br>
ユーザIDとパスワードの入力欄とログインボタンがある。
![ログイン](./image/[LO01]Login.png)

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
1. **出力画面**
   - 氏名
   - 部屋番号
   - プラン料金
   - 領収書印刷

   ![チェックイン-出力](./image/[CH03]CheckIN_output.png)

#### チェックアウト
1. **入力画面**
   - 部屋番号

   ![チェックアウト-入力](./image/[CH04]CheckOUT_input.png)
1. **出力画面**
   - 氏名
   - 領収書印刷

   ![チェックアウト-出力](./image/[CH05]CheckOUT_output.png)

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

### 予約情報
#### 予約登録
#### 予約変更
#### 予約削除
#### 予約検索(表示・印刷)

### 請求書・領収書
基本的にはチェックイン・アウトのときに発行する
- 請求書
- 領収書

### 従業員情報
#### 登録
#### 更新
#### 削除

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