## コンテナを停止・削除しよう

まず現在の状態を確認します。

`docker ps`

コンテナを停止してください。

`docker stop web`

停止したコンテナも含めて確認します。

`docker ps -a`

最期にコンテナを削除します。

`docker rm web`

もう一度確認してください。

`docker ps -a`
