# ユーザー情報更新
* url
  ```
  /user/update
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
          "id": "",
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

 

