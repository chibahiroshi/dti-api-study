# ログイン
* url
  ```
  /login
  ```
  
* メソッド
  * post

* リクエストヘッダ
  * 不要？
  
* リクエストBODY
  * json
  ```json
  {
      "user": {
          "email": "",
          "password": ""
      }
  }
  ```

* レスポンス
  * Set-Cookie: dtirest_session={認証トークン} 

* ステータス  
  |コード|ステータス|
  |---|---|
  |200|OK|
  |500|NG|

 

