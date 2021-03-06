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

## この手引きについて
>About this guide

この手引ではツアーに連れて行き、Docker が動かしているものを見せます。
>In this introduction we will take you on a tour and show you what makes Docker tick.

[最初のページ](http://docs.docker.io/introduction/understanding-docker/)で有益である。
>On the first page, which is *informative*:

* あなたは Docker の情報を見つけるでしょう。  
>You will find information on Docker;

* そして Docker の特徴を発見してください。
>And discover Docker's features.

* また、仮想マシンと Docker を比較します。
>We will also compare Docker to virtual machines;

* そしていくつかの使用事例を参照してください。
>And see some common use cases.

### [Docker を理解するには、ここをクリックしてください。](http://docs.docker.io/introduction/understanding-docker/)
>Click here to go to Understanding Docker.

[2ページ目](http://docs.docker.io/introduction/technology/)には上述の技術的な情報があります。
>The second page has technical information on:

* Dokcer のアーキテクチャ、
>The architecture of Docker;

* 根本的なテクノロジーと、 
>The underlying techology, and;

* Docker がどのように機能するか。
>How Docker works.

### [テクノロジーを理解するには、ここをクリックしてください。](http://docs.docker.io/introduction/technology/)
>Click here to go to Understanding the Technology.

3ページ目で実用的な使い方を得られます。そこで次のことが出来ます。
>On the [third page](http://docs.docker.io/introduction/working-with-docker/) we get practical. There you can:

* Docker のコンポーネントを学ぶ。(即ちコンテナ、イメージ、Dockerfile)
>Learn about Docker's components (i.e. Containers, Images and the Dockerfile);

* そして、すぐに一緒に作業を開始しましょう。
>And get started working with them straight away.

### Docker で作業するにはここをクリックしてください。
>Click here to go to Working with Docker.

* 最後に、4ページ目で、実際に見てください。 
>Finally, on the fourth page, we go hands on and see:

* インストール手順そして、
>The installation instructions, and:

* Docker がどのように難しい問題を容易にするかを。
>How Docker makes some hard problems much, much easier.

### Docker を取得するにはここをクリックしてください。
>Click here to go to Get Docker.

備考: 私達はあなたの時間がどれほど貴重かを知っています。
従って、このドキュメントは誰でも任意の部分から始める時に必要とされるように用意した。
Docker を理解するページを見て Docker がいかに変わっているかを確認することを推奨するが、
既に知識を持っていて早く始めたいなら、ためらうことなく Docker で作業するページを訪れてください。
>Node: We know how valuable your time is.
Therefore, the documentation is prepared in away to allow anyone to start from any section need.
Although we strongly recommend that you visit Understanding Docker to see how Docker is different, if you already have some knowledge and want to quickly get started with Docker, don't hesitate to jump to Working with Docker.
