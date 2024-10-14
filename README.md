# 本の感想共有サービス「ほんたんか」

■サービス概要

読んだ本の感想を31文字の短歌にして投稿・共有するサービスです。
本のタイトルと短歌を投稿し、他のユーザーの投稿も閲覧できます。
短歌のフォーマットを活用することで、気軽に読書の感想を共有するハードルを下げることを目指します。

■ このサービスへの思い・作りたい理由

私の趣味は読書ですが、既存の読書レビューサービスに、長文の感想文を投稿するハードルの高さを感じています。
一方で、読書体験を誰かと共有したいという思いもあります。
そこで、31音という短さと「五・七・五・七・七」の決まったフォーマットがある短歌の形式を活用することで、
もっと気軽かつ端的に本の感想を共有できるサービスを作ってみたいと考えました。

■ ユーザー層について

全年代を対象としつつ、特に20代半ば〜30代半ばの若手社会人をメインターゲットとします。
忙しい日々を送る中、簡潔な形で読書体験を共有できるプラットフォームにはニーズがあると考えます。

■サービスの利用イメージ

ユーザーは読んだ本のタイトルと、その本の感想を31文字の短歌にして投稿します。
投稿された短歌は一覧で表示され、他のユーザーからコメントやいいねをもらうことができます。
短歌のフォーマットのおかげで、長文を書くことなく気軽に感想を共有できます。
他のユーザーの投稿から、新しい本に興味関心をもってもらうことにも繋がります。

■ ユーザーの獲得について

SNSを活用し、読書関連のハッシュタグを使って宣伝することで、
ターゲットユーザーの獲得を目指します。

■ サービスの差別化ポイント・推しポイント

読書レビューサイトとの差別化ポイントは、短歌形式に特化している点です。
長文のレビューを書く必要がなく、31文字に凝縮することで投稿のハードルが下がります。
他の短歌投稿サイトとの差別化ポイントは、テーマを書籍の感想に特化している点です。

■ 機能候補

MVPリリース時の機能:
* 本のタイトルと短歌の投稿機能
* ユーザー登録・ログイン機能
* 投稿一覧の表示機能

本リリースまでに追加したい機能:
* いいね機能
* コメント機能
* タグ付け機能
* 短歌の検索機能
* 短歌投稿時の文字数カウント機能
* 短歌の自動フォーマット機能(改行挿入など)

■ 機能の実装方針予定

必要なGem（随時追加予定）：
* sorcery (ユーザー認証用)
* simple_form (フォーム作成の簡略化)
* kaminari (ページネーション)
* acts_as_votable (いいね機能)

使用予定のDB：
* MySQL

フレームワーク：
* Ruby on Rails

デプロイ先：
* Render (初期段階でのアプリケーションホスティング)
* 将来的にはスケーラビリティとコンテナ化の利点を活かすため、AWS Fargateへの移行を検討 

