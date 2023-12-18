# 職務経歴書
### プロフィール
 - 氏名：梁晉榮 Liang Jin Rong
 - 国籍：台湾 Taiwan
 - 言語：中国語、英語、日本語
 - Github：[@JinRong1125](https://github.com/JinRong1125)
# 職務経歴
## 株式会社Gunosy　2019年9月 - 現在
### ニュースアプリ Gunosy, LUCRA の Android 開発・運用
 - Gunosy https://play.google.com/store/apps/details?id=com.gunosy.android
#### プロジェクト概要
 - チーム規模：10人
 - 役割: Android エンジニア
#### 主な業務と成果
 - 動画広告の実装

   - Android UI Layout を Component 化にして、SDK として他アプリの実装に使えるように、全 Product の実装工数を削減
   - 再生 SDK の ExoPlayer に Kotlin Coroutines の Multithreading 運用を加えて、Performance Tuning による動画再生のユーザー体験を向上
   - Server-Side, Marketing Team を含めて、アプリの仕様設計を担当、iOS の開発にも共有し、両 OS の実装工数を削減
   - 詳細：https://gunosy.co.jp/ad
 - ラジオ機能の実装
   - Kotlin Coroutines Flow の導入をリードし、Code MVI Architecture を新しく設計・運用、今後開発の見通しと効率を向上
   - Server-Side, Design Team と連携しながら、Animation を含めた複雑な UI 実装を行う
   - 詳細：https://gunosy.co.jp/news/255
 - 通知の Push 実装
   - Android における Notification の仕様を調査し、Marketing Team に通知の施策運用に対して、参考出来る情報を提供
   - Android 13 通知権限の規制に伴い、許諾フローの要件定義から実装まで担当し、Push における許諾率と開封率を向上
 - 開発環境・継続的改善
   - RxJava の Kotlin Coroutines 移行に伴い、RxJava の不具合を大幅に削減
   - 広告 SDK の 大規模な Refactoring に当たって、Facade Pattern の概念を導入することにより、複数アプリでの開発効率を向上
   - CI/CD に Lint Check, Automatic Release, Unit Test を導入、既存機能の Code 品質を維持しながら、Deploy 効率の強化
   - MagicPod 自動化テストの運用に当たって、QA Team と連携しながら、CI/CD の Shell Scripts を完備
   - App Start の起動速度を改善し、Firebase Performance Monitoring を通じて起動時間を５０%短縮し、ユーザー体験を向上
 - 知見共有
   - Android 技術勉強会の社内発表
   - 新規施策の技術選定・実装設計
   - Android 技術ブログの執筆
     - CircleCI + Android UI Test スクリーンショットの確認仕組み https://tech.gunosy.io/draft/entry/9HzgjQG21FB_Js3xtGBmL1R8Tks

     - Android + Kotlin Coroutines の実用的な開発Tips https://tech.gunosy.io/entry/android_coroutine_tips
     - Gradle + Kotlin + CircleCI による Android Google Play デプロイの自動化 https://tech.gunosy.io/entry/android_google_play_deploy
     - Android MVI with Coroutines Flow https://tech.gunosy.io/entry/2022/10/17/140000
## INNORZ CO., Ltd. (Taiwan)　2018年9月 - 2019年7月
### Online Casino アプリの React Native 開発
#### プロジェクト概要
 - チーム規模：10人
 - 役割: React + Android エンジニア
#### 主な業務と成果
 - React Native 開発

   - Redex Flow による Components の実装
   - Animation Components の実装
 - Android Native 側の開発
   - Web Socket + Kotlin Coroutines の統合運用による Architecture の設計
   - Canvas を用いた SVG Format の画像を迅速に描画出来る Tool の実装
 - 開発環境・継続的改善
   - Agile 開発手法の運用
   - Appium を用いた自動化テストを、QA Team と連携しながら運用を行う
## Tatung Technology Inc. (Taiwan)　2016年10月 - 2018年5月
### Multimedia アプリ の Android TV, Tablet, Phone 開発
#### プロジェクト概要
 - チーム規模：8人
 - 役割: Android エンジニア
#### 主な業務と成果
 - VOD Service: TV, Tablet, Phone アプリ開発

   - Linux Base, Android AOSP 版での開発を行う
   - Android TV Leanback を用いた UI/UX の実装
   - SQLite を用いた番組表 Data の取り扱い
   - Android JNI を用いた Microsoft PlayReady DRM の仕組み対応
   - User Account における複数 Device の認証仕組みを、開発 Team 全体で取り組む
 - Media Player: TV アプリ開発
   - DLNA Guide Line に沿った Media Contents 共有仕組み UPnP の実装
   - Android Storage Access Framework を用いた Linux Base FAT32/NTFS での Contents File 取り扱いによる対応
   - https://github.com/JinRong1125/MediaStore
 - Live Streaming: TV, Phone アプリ開発
   - RTMP 経由の HLS Stream による、リアルタイム配信の仕組み実装
   - Socket I.O を用いたチャット機能の実装
   - Android Material Design を用いて、アプリの Prototype を Design Team と連携しながら、UI/UX の設計を行う
   - https://github.com/JinRong1125/LiveMobile
 - Screen Mirroring: Phone アプリ開発
   - UPnP 規格に基づいた、H.264 Stream のスマホ画面を、リアルタイムで共有する機能の実装
   - Android Screen Capture + Media Codec による Tuning で、配信の遅延を削減
   - Youtube Data API の利用による動画の共有
   - https://github.com/JinRong1125/DLNACaster
## Skills
### Programming
#### Android
 - 実務経験6年
 - Android Framework, NDK に携わった経験は１年
#### Kotlin
 - 実務経験5年
 - 主に Android 開発
#### Java
 - 実務経験3年
 - 主に Android 開発
#### React Native
 - 実務経験1年
 - 主に Smart Phone 開発
#### JavaScript, TypeScript
 - 実務経験1年
 - React Native による開発
#### MySQL
 - 実務経験1年
 - 主に自社製品の VOD Service 開発に関わる運用
#### Flutter
 - 実務経験なし
 - ゲームアプリ開発の勉強
#### Python
 - 実務経験なし
 - TensorFlow 利用の勉強
 - 音楽アプリ RESTful API 開発の勉強
### Services
#### AWS
 - 実務経験2年
 - 主に RESTful API のアプリ開発に関わる運用
#### Firebase
 - 実務経験4年
 - 主に Crashlytics, Analytics による Monitor の運用
#### GCP
 - 実務経験なし
 - 音楽アプリ開発の勉強
## Side Projects
### Dougaku 音楽配信 Android アプリ
 - Android 開発
 - https://github.com/JinRong1125/Dougaku
### Rhytube 音楽ゲーム Android アプリ
 - Flutter 開発
 - https://github.com/JinRong1125/Rhytube
### Android Architecture Showcase
 - Kotlin Coroutines + Jetpack Compose による、MVI Architecture の設計紹介
 - https://github.com/JinRong1125/MVI-Coroutines-Compose
### Receipt レシピ探し Android アプリ
 - Google GMS Vision を利用した、食材名の画像認識による、レシピ探しのアプリ
 - https://github.com/JinRong1125/Receipt
## 人物像
### 強み
 - 課題の原因特定・解決
 - 技術選定・方針決め
 - 資料から情報にするドキュメント化
### 弱み
 - 人のマネジメント
 - プロジェクトのリーダシップ
 - 施策の計画・提案
### 改善したいこと
 - 
