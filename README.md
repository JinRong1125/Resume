## 職務経歴書
### プロフィール
 - 氏名：梁晉榮 Liang Jin Rong
 - 国籍：台湾 Taiwan
 - 言語：中国語、英語、日本語
 - Github：[@JinRong1125](https://github.com/JinRong1125)
 - 本文リンク：https://github.com/JinRong1125/Resume

### 概要
Android エンジニアとして約 9 年のモバイルアプリ開発経験を持ち、主にマルチメディア系アプリの開発に携わってきました。今後も Android 技術を軸に技術スタックを積み上げ、幅広いサービスの開発に挑み続けたいと考えています。

# 職務経歴

## KINTOテクノロジーズ株式会社　2024年7月 - 現在

### AIプレゼン動画生成 POC Web アプリの開発
#### プロジェクト概要
 - チーム規模：10 人
 - 役割：R&D エンジニア
 - 目的：対話型 LLM を起点に、ユーザーが自然言語からプレゼン動画を自動生成できる仕組みの実証

#### 主な業務と成果
##### AIサービスの技術検証と価値提供の評価
 - ボイスクローン・アバター動画・動画生成の各 AI サービスについて、出力品質と安定性を比較検証
 - 各サービスの API 仕様を分析し、動画生成パイプラインへの統合方式を設計
 - 検証結果をもとに、プロダクトとして提供可能な価値と技術的制約を整理

##### AI動画生成アプリの構築
 - HyperFrames を基盤に、LangGraph によるオーケストレーションでユーザー向け動画生成アプリを構築
 - 対話型 LLM を用いて、ユーザー入力から動画構成を生成する一連のパイプラインを設計
 - 非同期レンダリングや状態管理を含む、一般ユーザー向けに安定動作する処理フローを実装
 - Server・Client App 開発チームと連携しながら、生成パイプラインをバックエンドとフロントエンドへ統合するアーキテクチャを議論・設計
 - HyperFrames: https://github.com/heygen-com/hyperframes

### AI音楽生成 POC Flutter アプリの開発
#### プロジェクト概要
 - チーム規模：5 人
 - 役割：R&D エンジニア
 - 目的：納車時にオリジナル楽曲をプレゼントすることで、お客様の感動と思い出に残る体験を創出する

#### 主な業務と成果
##### 音楽生成AIの技術検証と価値検討
 - 各種音楽生成AI サービスについて、曲調の再現性と出力の安定性を比較検証
 - 「感動と思い出」のコンセプトに基づき、AIで提供できる体験価値を検討・提案
 - 検証結果をもとに、サービス化に向けた技術的な実現性と制約を整理

##### Flutterアプリの機能検証
 - 音楽生成AI の API を組み込み、ユーザー入力から楽曲を生成する処理フローを実装
 - 楽曲再生などの基本機能を備えた検証用アプリを Flutter で構築

### KINTO Unlimited の Android 開発・運用
 - https://play.google.com/store/apps/details?id=com.kinto.unlimited
 - 車のサブスクリプションサービスアプリ

#### プロジェクト概要
 - チーム規模：15 人
 - 役割：Android エンジニア

#### 主な業務と成果
##### AIチャット機能の実装検証
   - 目的：サービスに特化したAIとの対話を通じて、ユーザーがサービス関連の質問への回答を得られるAIチャット機能の実証
   - Vertex AI・Azure AI の API を用いたチャット機能を Android アプリに構築・検証し、Server Side チームと連携して API を設計
   - ChatGPT・Gemini のモバイルアプリをベンチマークに、Marketing・Design・開発チームと UI/UX を設計・議論し、要件をすり合わせ
   - LLaMA Factory・MLC LLM を用いたオンデバイス AI を構築し、Android アプリ上で動作と実用性を検証
   - LLaMA Factory: https://github.com/hiyouga/LlamaFactory
   - MLC LLM: https://github.com/mlc-ai/mlc-llm

##### これなにガイドの実装
   - 機能：スマホのカメラを車内の各種スイッチにかざすと、当該機能の使い方をテキストと動画で案内する機能
   - TensorFlow の機械学習を用いて、スイッチの画像認識モデルを構築・運用
   - MediaPipe フレームワークと OpenCV による画像処理を活用し、ユーザーに AR 体験を提供
   - Marketing・Security・開発の各チームと要件・制約を調整しながら実装計画を策定し、機能の設計から導入までを一貫して推進
   - 詳細：https://corp.kinto-jp.com/news/detail/?id=press_20240626
   - 技術ブログ：https://blog.kinto-technologies.com/posts/2026-03-27-korenani-guide-mediapipe-ar/

##### 新規・既存機能の改善
   - 既存コードベースの設計・コーディング規約を考慮し、保守性を損なわない形で新規機能の追加とリファクタリングを実施
   - Material 3 を導入し、開発チームと議論しながら、Android アプリの実装デザインを定義する Design System を再設計
   - 既存機能における XML を使った複雑な UI/UX 実装（スクロールなど）を Jetpack Compose へ移行

## 株式会社Gunosy　2019年9月 - 2024年6月

### 「グノシー」「LUCRA」の Android 開発・運用
 - ニュースアプリ　グノシー：https://play.google.com/store/apps/details?id=com.gunosy.android
 - 女性向け情報アプリ　LUCRA

#### プロジェクト概要
 - チーム規模：10 人
 - 役割：Android エンジニア

#### 主な業務と成果
##### 雨雲レーダーの実装
   - Google Map を用いて、現在地域の雨雲の予想情報を提示する機能
   - Design・Analytics チームと連携し、UI/UX と要件定義の設計からリリースまで、開発の実装をリード

##### 動画広告の実装
   - Android UI Layout をコンポーネント化し、SDK として他アプリでも利用できるようにすることで、全プロダクトの実装工数を削減
   - 再生 SDK の ExoPlayer に Kotlin Coroutines のマルチスレッド運用を加え、パフォーマンスチューニングによって動画再生のユーザー体験を向上
   - Server-Side・Marketing チームを含めてアプリの仕様設計を担当し、iOS を含めた実装の工数を削減
   - 詳細：https://gunosy.co.jp/ad

##### ラジオ機能の実装
   - Kotlin Coroutines Flow の初導入をリードし、コードアーキテクチャ MVI を新たに設計・運用、今後の開発の見通しと効率を向上
   - Server-Side・Design チームと連携しながら、アニメーションを含めた複雑な UI 実装を担当
   - 詳細：https://gunosy.co.jp/news/255

##### Push 通知の改善
   - Android における Notification の仕様を調査し、Marketing チームへ通知施策の運用に参考となる情報を提供
   - Android 13 の通知権限への対応に伴い、他チームを巻き込み、許諾フローの要件定義から実装まで自ら担当し、Push の許諾率と開封率を向上

##### チュートリアルの実装
   - Android ユーザーの習性を調査し、Marketing・Analytics チームと議論しながら仕様の要件定義を実施
   - 初回起動ユーザー向け施策の結果として、新規ユーザーの獲得数を向上

##### 開発環境の改善
   - CI/CD に Lint Check・Automatic Release・E2E Unit Test を導入し、新規・既存機能の安定性を維持しながらアプリのデプロイ品質を強化
   - MagicPod による自動化テストの運用にあたり、QA チームと連携して CI/CD の実行パイプラインとスクリプトを整備
   - CircleCI から GitHub Actions への移行に際し、Git Flow の概念を用いてパイプラインを再設計し、デプロイ効率を向上

##### 継続的改善
   - RxJava から Kotlin Coroutines への移行に伴い、RxJava の不具合解消とクラッシュの解決により、アプリのクラッシュフリー率 99.9% を達成
   - 広告 SDK 全体のリファクタリングにおいて Facade パターンを導入し、複数アプリでの開発効率を向上
   - App 起動速度を改善し、Firebase Performance Monitoring を通じて起動時間を 50% 短縮、ユーザー体験を向上

##### 知見共有
   - 技術勉強会での社内発表
   - 新規施策の技術選定・実装設計
   - 技術ブログの執筆
     - CircleCI + Android UI Test スクリーンショットの確認の仕組み：https://tech.gunosy.io/entry/android_test_screenshot
     - Android + Kotlin Coroutines の実用的な開発 Tips：https://tech.gunosy.io/entry/android_coroutine_tips
     - Gradle + Kotlin + CircleCI による Android Google Play デプロイの自動化：https://tech.gunosy.io/entry/android_google_play_deploy
     - Android MVI with Coroutines Flow：https://tech.gunosy.io/entry/2022/10/17/140000

## INNORZ CO., Ltd. (Taiwan)　2018年9月 - 2019年7月

### オンラインカジノアプリの React Native 開発
#### プロジェクト概要
 - チーム規模：10 人
 - 役割：React + Android エンジニア

#### 主な業務と成果
##### React Native 開発
   - Redux Flow に適用するコンポーネントの実装
   - アニメーションコンポーネントの実装

##### Android Native 側の開発
   - WebSocket + Kotlin Coroutines の統合運用によるアーキテクチャの設計
   - Canvas を用いて SVG 形式の画像を高速に描画するツールの実装

##### 開発環境・継続的改善
   - アジャイル開発手法の運用
   - Appium を用いた自動化テストを QA チームと連携しながら運用

## Tatung Technology Inc. (Taiwan)　2016年10月 - 2018年5月

### Android TV 搭載のセットトップボックスおよび Android スマホ向けマルチメディアアプリの開発・運用
#### プロジェクト概要
 - チーム規模：8 人
 - 役割：Android エンジニア

#### 主な業務と成果
##### VOD 動画配信サービス（TV・タブレット・スマホアプリ開発）
   - Linux ベース、Android AOSP 版での開発を担当
   - Android TV Leanback を用いた UI/UX の実装
   - SQLite を用いた番組表データの取り扱い
   - Android JNI を用いた Microsoft PlayReady DRM の仕組みへの対応
   - ユーザーアカウントにおける複数デバイスの認証の仕組みを、開発チーム全体で構築

##### メディアプレイヤー（TV アプリ開発）
   - MediaBrowserService を用いてプレイヤー機能を実装
   - DLNA ガイドラインに沿ったメディアコンテンツ共有の仕組み（UPnP）を実装
   - Android Storage Access Framework を用い、Linux ベースの FAT32／NTFS でのコンテンツファイル取り扱いに対応
   - https://github.com/JinRong1125/MediaStore

##### ライブ配信サービス（TV・スマホアプリ開発）
   - RTMP 経由の HLS ストリームによるリアルタイム配信の仕組みを実装
   - Socket.IO を用いたチャット機能の実装
   - Android Material Design を用い、Design チームと連携しながらアプリのプロトタイプの UI/UX を設計
   - https://github.com/JinRong1125/LiveMobile

##### スクリーンミラーリング（スマホアプリ開発）
   - UPnP 規格に基づき、H.264 ストリームでスマホ画面をリアルタイム共有する機能を実装
   - Android Screen Capture + Media Codec のチューニングにより、配信の遅延を削減
   - YouTube Data API を利用した動画の共有
   - https://github.com/JinRong1125/DLNACaster

## スキル
### フレームワーク
#### Android
 - 実務経験 9 年
 - AOSP・NDK の経験は 1 年

#### React Native
 - 実務経験 1 年
 - 主にスマホアプリの開発

#### Flutter
 - 実務経験 1 年
 - 主にスマホアプリの開発

#### TensorFlow
 - 実務経験 1 年
 - 主に物体認識への応用

#### MediaPipe
 - 実務経験 1 年
 - 拡張現実への応用

#### OpenCV
 - 実務経験 1 年
 - 拡張現実における画像処理への応用

### プログラミング言語
#### Kotlin
 - 実務経験 7 年
 - 主に Android 開発

#### Java
 - 実務経験 5 年
 - 主に Android 開発

#### JavaScript・TypeScript
 - 実務経験 1 年
 - 主に React Native 開発
 - LangGraph の開発

#### Python
 - 実務経験 1 年
 - TensorFlow・LLM への応用

#### C++
 - 実務経験 1 年
 - MediaPipe・OpenCV の構築・導入

#### MySQL
 - 実務経験 1 年
 - 主に VOD サービス開発に関わる運用

### サービス
#### AWS
 - 実務経験 3 年
 - 主にフロントエンド開発に関わる機能の運用

#### Firebase
 - 実務経験 5 年
 - 主に Crashlytics・Analytics によるモニタリングの運用

#### GCP
 - 実務経験なし
 - 音楽アプリ開発に向けた学習

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
   - まず技術の専門分野で信頼されるようになり、常にメンバーを後押しできるリードエンジニアを目指したい
 - プロジェクトのリーダーシップ
   - 技術スタックを広げるとともに、小さな施策から大きなスケールのプロジェクトへ携わっていきたい
 - 施策の計画・提案
   - 技術を活かしたうえで、プロダクト開発における新たな課題解決や成長につながる提案に挑戦したい

### 将来像
 - Android 技術に精通し、どんなジャンルのアプリでも迅速かつ高品質に開発できるようになる
 - Android 技術を通じて技術スタックを増やし、開発能力をアプリからサービスへと広げる

## サイドプロジェクト
### Dougaku 音楽配信 Android アプリ
 - Android 開発
 - https://github.com/JinRong1125/Dougaku

### Rhytube 音楽ゲーム Android アプリ
 - Flutter 開発
 - https://github.com/JinRong1125/Rhytube

### Android Architecture Showcase
 - Kotlin Coroutines + Jetpack Compose による MVI アーキテクチャの設計紹介
 - https://github.com/JinRong1125/MVI-Coroutines-Compose

### Receipt レシピ探し Android アプリ
 - Google GMS Vision を利用し、食材名の画像認識でレシピを探すアプリ
 - https://github.com/JinRong1125/Receipt
