>https://docs.docker.com/introduction/understanding-docker/

# Docker を理解する 
>Understanding Docker

What is Docker?
>Docker とは何ですか？

Docker is an open platform for developing, shipping, and running applications.
>Docker はアプリケーションを開発、出荷及び実行するためのオープンプラットフォームです。

Docker is designed to deliver your application faster.
>Docker はあなたのアプリケーションをより早く届けるために設計されました。

<!-- サイトが更新される前の翻訳内容。(途中) -->
*Docker とは何ですか？ 何が素晴らしいのですか？*
>What is Docker? What makes it gread?

ライフサイクルとパイプラインとデプロイツールの構築は難しい。
ポータブルなアプリケーションやサービスの作成は簡単ではない。
開発環境から本番環境へしばしばコードの不整合が発生します。
また、アプリケーションやサービスの、一貫性のあるアップデートと管理は難しい。
>Building development lifecycle, pipelines and deployment tooling is hard.
>It's not easy to create portable applications and services.
>There's often high friction getting code from your development environment to production.
>It's also hard to ensure those applications and services are consistent, up-to-date and managed.

Docker は開発者とシステム管理者双方のために、これらの問題を解決するように設計された。
コンテナの中へビルドと展開を行うためのライフサイクルを提供する軽量なフレームワーク(パワフルなAPIを含む)です。
>Docker is designed to solve these problem for both developers and sysadmins.
>It is a lightweight framework(with a powerful API) that provides a lifecycle for building and deploying applications into containers.

Dockerはほとんどのアプリケーションをコンテナの中で安全に孤立して実行する方法を提供します。
>Docker provides a way to run almost any application securely isolated into a container.

隔離とセキュリティを可能にするとホスト上でいくつものコンテナを同時に実行できます。
>The isolation and security allows you to run many containers simultaneously on your host.

