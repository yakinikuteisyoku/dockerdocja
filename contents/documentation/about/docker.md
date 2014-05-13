[Original page](http://docs.docker.io)

# Docker について
>About Docker

セキュアでポータルなコンテナが容易になる
>Secure And potable Containers Made Easy


## はじめに
>Introduction

Docker はコンテナベースの仮想化フレームワークです。  
Docker は従来の仮想化とは異なり速く、軽量で、使いやすい。  
Docker はアプリケーションの依存関係を全て保持してコンテナを作成することができます。  
各コンテナは孤立に保管され、他と何も共有しません。
>Docker is a container based virtulization framework.  
Unlike traditional virtualization Docker is fast, lightweight and easy to use.  
Docker allows you to create containers holding all the dependencies for an application.  
Each container is kept isolated from any other, and nothing gets shared.

## Docker のハイライト
>Docker highlights

* サンドボックスのコンテナを提供  
外部からアクセスされず安全にアプリケーションが実行されます。
>Containers provide sand-boxing:  
Applications run securely without outside access.

* 全て高速に動作:  
コンテナはとても高速なシングルプロセスで起動する。
>It all works fast:  
Starting a container is a very fast single process.

* Docker はシステムリソースにやさしい (従来の仮想マシンシステムとは異なる):  
それぞれのアプリケーションが必要とするものに過ぎない。
>Docker is easy on the system resources (unlike VMs):  
No more than what each application needs.

* その*本質*に依存しない:  
フレームワーク、言語、プラットフォーム依存が自由。
>Agnostic in its *essence*:  
Free of framework, language or platform dependencies.

そして最も重要なこと
>And most importantly:

* Docker は複雑さを軽減:  
Docker はわかりやすい英語のコマンドを受け付けます。例えば **docker run [..]**
>Docker reduces complexity:  
Docker accepts commands in plain English, e.g. **docker run [..].**
