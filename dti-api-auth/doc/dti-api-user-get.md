# ユーザー情報取得(個別)
* url
  ```
  /user/{user_id}
  ```
* メソッド
  * get

* リクエストヘッダ
  * Set-Cookie: dtirest_session={認証トークン}
  
* リクエストBODY
  * なし

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

 

