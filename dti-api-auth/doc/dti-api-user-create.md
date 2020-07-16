# ユーザー情報登録
* url
  ```
  /user/create
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
          "name": "",
          "email": "",
          "password": "",
          "created_at": "",
          "updated_at": ""
      }
  }
  ```

* レスポンス
  * json
  ```json
  {
      "user": {
          "id": "",
          "name": "",
          "email": "",
          "created_at": "",
          "updated_at": ""
      }
  }
  ```

* ステータス  
  |コード|ステータス|
  |---|---|
  |200|OK|
  |500|NG|

 

