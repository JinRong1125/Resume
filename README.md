## 職務経歴書
### プロフィール
 - 氏名：梁晉榮 Liang Jin Rong
 - 国籍：台湾 Taiwan
 - 言語：中国語、英語、日本語
 - Github：[@JinRong1125](https://github.com/JinRong1125)
 - 本文リンク： https://github.com/JinRong1125/Resume
 - 画像付きの作品履歴書：
https://www.cakeresume.com/jinrong
### 概要
Android エンジニアとして約 7 年の開発経験を持ち、主にマルチメディア系のアプリ開発に携わってきました。現職ではユーザー数百万人の Gunosy Android アプリ開発を担当しています。今後も Android 技術を通じて技術スタックを積み上げ、幅広いサービスの開発に挑み続けたいと思っています。
# 職務経歴
## 株式会社Gunosy　2019年9月 - 現在
### ニュースアプリ Gunosy, LUCRA の Android 開発・運用
 - Gunosy https://play.google.com/store/apps/details?id=com.gunosy.android
### プロジェクト概要
 - チーム規模：10 人
 - 役割：Android エンジニア
### 主な業務と成果
#### 雨雲レーダーの実装
   - Google Map を用いた現在地域にある雨雲の予想情報を提示する機能
   - Design, Analytics Team と連携して、UI/UX と要件定義の設計からリリースまで、開発の実装をリードする
#### 動画広告の実装
   - Android UI Layout を Component 化にして、SDK として他アプリの実装に使えるように、全 Product 実装の工数を削減
   - 再生 SDK の ExoPlayer に Kotlin Coroutines の Multithreading 運用を加えて、Performance Tuning による動画再生のユーザー体験を向上
   - Server-Side, Marketing Team を含めて、アプリの仕様設計を担当し、iOSを含めた実装の工数を削減
   - 詳細：https://gunosy.co.jp/ad
#### ラジオ機能の実装
   - Kotlin Coroutines Flow の初導入をリードし、Code Architecture: MVI を新しく設計・運用、今後開発の見通しと効率を向上
   - Server-Side, Design Team と連携しながら、Animation を含めた複雑な UI 実装を行う
   - 詳細：https://gunosy.co.jp/news/255
#### 通知の Push 改善
   - Android における Notification の仕様を調査し、Marketing Team に通知の施策運用に対して、参考出来る情報を提供
   - Android 13 通知権限の対応に伴い、他チームを巻き込んで、許諾フローの要件定義から実装まで自ら担当し、Push における許諾率と開封率を向上
#### チュートリアルの実装
   - Android ユーザーの習性を調査し、Marketing, Analytics Team と議論しながら、仕様の要件定義を行う
   - 初回起動のユーザーに対する施策の結果として、新規ユーザーの獲得数を向上
#### 開発環境の改善
   - CI/CD に Lint Check, Automatic Release, E2E Unit Test を導入、新規・既存機能の安定性を維持しながら、アプリの Deploy 品質を強化
   - MagicPod 自動化テストの運用にて、QA Team と連携しながら、CI/CD の実行 Pipeline, Scripts を完備
   - CircleCI を Gihub Actions に移行することに当たり、Git Flow の概念を用いて Pipeline を再設計、Deploy 効率を向上
#### 継続的改善
   - RxJava の Kotlin Coroutines 移行に伴い、RxJava の不具合解消と Crash の解決で、アプリのクラッシュフリー率を99.9%達成
   - 広告 SDK の 全体 Refactoring にて、Facade Pattern の概念を導入することにより、複数アプリでの開発効率を向上
   - App Start の起動速度を改善し、Firebase Performance Monitoring を通じて起動時間を５０%短縮し、ユーザー体験を向上
#### 知見共有
   - 技術勉強会の社内発表
   - 新規施策の技術選定・実装設計
   - 技術ブログの執筆
     - CircleCI + Android UI Test スクリーンショットの確認仕組み https://tech.gunosy.io/entry/android_test_screenshot

     - Android + Kotlin Coroutines の実用的な開発Tips https://tech.gunosy.io/entry/android_coroutine_tips
     - Gradle + Kotlin + CircleCI による Android Google Play デプロイの自動化 https://tech.gunosy.io/entry/android_google_play_deploy
     - Android MVI with Coroutines Flow https://tech.gunosy.io/entry/2022/10/17/140000
## INNORZ CO., Ltd. (Taiwan)　2018年9月 - 2019年7月
### Online Casino アプリの React Native 開発
### プロジェクト概要
 - チーム規模：10 人
 - 役割：React + Android エンジニア
### 主な業務と成果
#### React Native 開発

   - Redux Flow に適用する Components の実装
   - Animation Components の実装
#### Android Native 側の開発
   - Web Socket + Kotlin Coroutines の統合運用による Architecture の設計
   - Canvas を用いた SVG Format の画像を迅速に描画出来る Tool の実装
#### 開発環境・継続的改善
   - Agile 開発手法の運用
   - Appium を用いた自動化テストを、QA Team と連携しながら運用を行う
## Tatung Technology Inc. (Taiwan)　2016年10月 - 2018年5月
### Android TV 搭載のセットトップボックス及び Android スマホで、Multimedia アプリの開発・運用
### プロジェクト概要
 - チーム規模：8 人
 - 役割：Android エンジニア
### 主な業務と成果
#### VOD Service 動画配信サービス: TV, Tablet, Phone アプリ開発

   - Linux Base, Android AOSP 版での開発を行う
   - Android TV Leanback を用いた UI/UX の実装
   - SQLite を用いた番組表 Data の取り扱い
   - Android JNI を用いた Microsoft PlayReady DRM の仕組み対応
   - User Account における複数 Device の認証仕組みを、開発 Team 全体で取り組む
#### Media Player メディアプレイヤー: TV アプリ開発
   - MediaBrowserService を用いて、プレイヤーの機能を実装
   - DLNA Guide Line に沿った Media Contents の共有仕組み UPnP の実装
   - Android Storage Access Framework を用いた Linux Base FAT32/NTFS での Contents File 取り扱いによる対応
   - https://github.com/JinRong1125/MediaStore
#### Live Streaming ライブ配信サービス: TV, Phone アプリ開発
   - RTMP 経由の HLS Stream による、リアルタイム配信の仕組み実装
   - Socket I.O を用いたチャット機能の実装
   - Android Material Design を用いて、アプリの Prototype を Design Team と連携しながら、UI/UX の設計を行う
   - https://github.com/JinRong1125/LiveMobile
#### Screen Mirroring スクリーンキャスト: Phone アプリ開発
   - UPnP 規格に基づいた、H.264 Stream のスマホ画面を、リアルタイムで共有する機能の実装
   - Android Screen Capture + Media Codec による Tuning で、配信の遅延を削減
   - Youtube Data API の利用による動画の共有
   - https://github.com/JinRong1125/DLNACaster
## Skills
### Programming
#### Android
 - 実務経験 7 年
 - Android Framework, NDK に携わった経験は 1 年
#### Kotlin
 - 実務経験 5 年
 - 主に Android 開発
#### Java
 - 実務経験 3 年
 - 主に Android 開発
#### React Native
 - 実務経験 1 年
 - 主に Smart Phone 開発
#### JavaScript, TypeScript
 - 実務経験 1 年
 - React Native による開発
#### MySQL
 - 実務経験 1 年
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
 - 実務経験 2 年
 - 主に RESTful API にて、Android アプリ開発に関わる運用
#### Firebase
 - 実務経験 4 年
 - 主に Crashlytics, Analytics による Monitor の運用
#### GCP
 - 実務経験なし
 - 音楽アプリ開発の勉強
## 人物像
### 強み
 - 課題の原因特定・解決
 - 技術選定・方針決め
 - 情報の収集・活用
### 普通
 - コミュニケーション能力
 - 進捗の管理能力
 - 協調性・柔軟性
### 弱み
 - 人のマネジメント
   - まず技術に関する相談に乗れるようになり、常にメンバーを後押しするリードエンジニアを目指す
 - プロジェクトのリーダシップ
   - 技術スタックを広げることに連れて、小さい施策から、大きいスケールのプロジェクトに携わって行きたい
 - 施策の計画・提案
   - 技術を活かした上で、プロダクトの開発に対する新たな課題解決や成長させる提案に挑戦したい
### 将来像
 - Android 技術を精通し、どんなジャンルのアプリでも迅速に、かつ高品質で開発出来る
 - Android 技術を通じで、技術スタックを増やし、開発能力をアプリからサービスに広げる
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
