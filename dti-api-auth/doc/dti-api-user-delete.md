# ユーザー情報削除
* url
  ```
  /user/delete
  ```
* メソッド
  * post

* リクエストヘッダ
  * Set-Cookie: dtirest_session={認証トークン}
  
* リクエストBODY
  * json
  ```json
  {
      "user": {
          "id": ""
      }
  }
  ```

* レスポンス
  * ステータスのみ

* ステータス  
  |コード|ステータス|
  |---|---|
  |200|OK|
  |500|NG|

 

