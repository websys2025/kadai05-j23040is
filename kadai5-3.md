## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  * https://zipcloud.ibsnet.co.jp/api/search
  * 日本の郵便番号を検索し、それに対応する住所情報を取得できるAPI。
* リクエストとレスポンスのフォーマット
  * 入力した値から、resultsを返す郵便番号APIを呼び出す。resultsをaddressに格納し、resultエリアにaddress.address1 + address.address2 + address.address3を表示する。
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  * PokeAPI https://pokeapi.co/
* エンドポイントと機能
  * https://pokeapi.co/api/v2/pokemon 指定したポケモンの詳細な情報を取得する。
* リクエストとレスポンスのフォーマット
  * 図鑑番号に入力したidから、該当するポケモンの図鑑idや名前などの情報をリクエストする。レスポンスされたデータの内、idとnameをpoke_idとpoke_nameに格納し、resultエリアに表示する。
### Q3-3. 感想
* 今回の課題で苦労したこと
  * 授業資料と教科書だけではうまく課題を解くことが出来なかった。
* 演習を通して理解できたこと
  * WebAPIの仕組み。
* Web APIの利便性や課題など
  * プログラムのコードを短くできる。
