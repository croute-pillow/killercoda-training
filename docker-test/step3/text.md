## コンテナの内部を確認しよう

起動したコンテナの内部でコマンドを実行してみましょう。

`docker exec -it web /bin/bash`

コンテナ内で以下を確認してください。

`hostname`

`cat /etc/os-release`

確認できたらコンテナから抜けます。

`exit`
