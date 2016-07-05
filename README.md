# ssh-key-switcher

SSHの複数の秘密鍵を切り替えるツールです。

複数のGitHubアカウントを利用する際などに便利です。

# 準備

コードをパスの通ったところにコピーし、実行権限をつけ、前半にある設定部分を書き換えます。

USERNAMEをつけて実行するとそのキーが有功になり、もう一方のキーは無効になります。

# 使い方

	ssh-key-switcher          現在有功な一覧を表示する
	ssh-key-switcher USERNAME USERNAMEのキーを有功にする


