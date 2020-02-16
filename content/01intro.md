---
title: FlutterとFirebaseを知ろう
author:
  - wami
---

# FlutterとFirebaseを知ろう

<div class="lead">

FlutterとFirebaseについてそれぞれ学んでいきましょう。テスト

</div>

<div class="draft-author">

</div>

## Flutter

オープンソースのモバイルアプリケーションフレームワークです。

特徴は次のとおりです。

 - 対応言語はDart
 - Hot Reload対応
 - AndroidやiOSが開発可能なマルチプラットフォーム対応
 - 開発元はGoogle

![Flutterロゴ](assets/flutter.png)

<div class="page-break"></div>

<div class="column">

### Dart

Googleによって開発されたWebプログラミング言語です。

JavaScriptの代替となる言語として作られました。
JavaScriptやJavaに記法が似ており、どちらかの言語を使ったことがある方には始めやすい言語だと思います。

</div>

### ReactNativeやXamarinとの比較

デスクトップアプリが作れるXamarinに比べると対応プラットフォーム数は劣りますが、
ReactNativeと対応プラットフォーム数は同じです。

| 対応プラットフォーム | Flutter/Dart | ReactNative/JavaScript | Xamarin/.NET|
|---|---|---|---|
|Android|○|○|○|
|iOS|○|○|○|
|デスクトップ（Win）|-|-|○|
|デスクトップ（Mac）|-|-|○|
|Web（フロントエンド）|-|-|○|
|Web（バックエンド）|-|-|-|



## Firebase

FirebaseはGoogleが運営するBaaSです。

BaaS（backend as a service）とは、サーバーサイドのプログラミングが不要でデータベースや認証機能、プッシュ通知などを行ってくれるサービスです。

今回は、「Cloud Firestore」（※2018年9月現在、β版のみ提供）というクエリと自動スケーリング機能を兼ね備えたリアルタイムデータベースを使用します。
