# ユーザー情報取得(一覧)
* url
  ```
  /users
  ```
* メソッド
  * get

* リクエストヘッダ
  * {@@トークン@@}

* リクエストBODY
  * json
  ```json
  {
      "search": {
          "id": "",
          "name": "",
          "email": "",
          "created_at_from": "",
          "created_at_to": "",
          "updated_at_from": "",
          "updated_at_to": ""
      }
  }
  ```
* レスポンス
  * json　(配列)
  ```json
    {
        "users": [
            {
                "id": "",
                "name": "",
                "email": "",
                "created_at": "",
                "updated_at": ""
            },
            {
                "id": "",
                "name": "",
                "email": "",
                "created_at": "",
                "updated_at": ""
            }
        ]
    }
  ```
* ステータス
  |コード|ステータス|
  |---|---|
  |200|OK|
  |500|NG|
