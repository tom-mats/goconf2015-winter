
# ISUCIN

## Gunosy

+ ほとんどGo言語で書かれている

##

+ サーバリソースの効率化
  * パラメータの設定
  * text/templateの削除
  + UnixDomainSocket化
* プロセスキャッス
  * DBのデータをGolang上にダンプ
  * 長い本文データはRedisにコピー

再起動耐性にはgobを使用した．
* syncパッケージとgoroutineを使い，並列処理に安全に効率化
  * http2も使えた
  
