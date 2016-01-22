# memo

* Laravel+Rocketeer+CircleCIの構成でAWSにデプロイする
http://webmake.info/laravelrocketeercircleci%E3%81%AE%E6%A7%8B%E6%88%90%E3%81%A7aws%E3%81%AB%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4%E3%81%99%E3%82%8B/

* CircleCI + DockerでサーバCI始めました
http://tech.feedforce.jp/serverci-by-docker.html

* laravel環境
http://php-archive.net/php/windows-homestead-laravel5-1/
http://php-archive.net/php/windows-homestead-laravel5-2/

* AWS OpsWorksで使うCustom Cookbookをローカルでデバッグしてみる
http://blog.interfirm.co.jp/entry/2014/08/28/182748

ln -s ci_test/Laravel ./Laravel
serve test.homestead.app /home/vagrant/Code/test/public

* CircleCI + DockerでサーバCI始めました
http://tech.feedforce.jp/serverci-by-docker.html

* AWS OpsWorksを使ってPHP 5.6の環境構築とLaravel 5.1のデプロイ作業を自動化する。
http://www.s-arcana.co.jp/blog/2015/09/27/2851

既存のディレクトリ（フォルダ）にgit cloneして上書きしたい
http://se-suganuma.blogspot.jp/2015/05/git-clone.html

まずは開発ディレクトリをgitローカルリポジトリにする
# cd /path/to/project/
# git init

「origin」という名前でリモートリポジトリを追加
# git remote add origin git@gitlab.hoge.jp:suganuma/project-api.git

ローカルリポジトリを最新にする
# git fetch origin

確認
# git branch -a
