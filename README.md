# GitLab Local

自宅サーバーで GitLab 運用するときの設定ファイル．

GitLab Agent をプライベートCA(認証局) が署名した証明書で運用するため，
プライベートCA(認証局) のルート証明書を組み込んだイメージを作成し，
それを利用します．
