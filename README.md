# scaffold

[![Greenkeeper badge](https://badges.greenkeeper.io/wilf312/scaffold.svg)](https://greenkeeper.io/)
scaffold

todo

scaf add <name> [dirname]

* 名前の入力
* 指定ディレクトリを丸っとローカルの~/.scaffold/以下にコピーする
コピーするときに gitignoreに指定したディレクトリ、ファイルを除外する

scaf [dirname] <name or なし> <--no>

* scaf [diname] に <name>で指定した登録したデータをコピー
* --noを指定すると自動で yarn を実行しない（node_modulesを落としてこない）