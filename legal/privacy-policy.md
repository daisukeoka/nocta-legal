---
layout: default
title: Privacy Policy / プライバシーポリシー
---

# プライバシーポリシー

最終更新日: 2026年3月29日

Nocta - AI Diary（以下「本アプリ」）をご利用いただきありがとうございます。本プライバシーポリシーは、本アプリにおける情報の取り扱いについて説明するものです。

## 1. 収集する情報

### 1.1 ユーザーが提供する情報
- 写真（カメラ撮影またはフォトライブラリから選択）
- 感情の選択
- ひとことメモ（任意）

これらの情報は**端末内（ローカルストレージ）にのみ保存**されます。当社のサーバーにユーザーデータを保存することはありません。

### 1.2 AI応答の生成に使用する情報
日記生成機能を利用する際、写真（リサイズ済み）、選択された感情、メモは、AI応答を生成するために外部AIサービスに送信されます。この通信は当社の Supabase Edge Function を経由して行われます。

- 送信される情報: リサイズされた写真（base64形式）、感情、メモ、写真の撮影日時、言語設定
- 送信先: Google Gemini API または Anthropic Claude API（Supabase Edge Function 経由）
- 写真は日記生成のためにのみ使用され、外部サーバーに保存されることはありません
- Anthropic 社のプライバシーポリシー: https://www.anthropic.com/privacy
- Google のプライバシーポリシー: https://policies.google.com/privacy

### 1.3 生体認証情報
本アプリは Face ID / Touch ID によるロック機能を提供しています。生体認証データは端末のセキュアな領域で処理され、本アプリがアクセスすることはありません。

## 2. 情報の保存場所

| 情報 | 保存場所 |
|------|----------|
| 日記データ（テキスト・タイトル） | 端末内のみ（AsyncStorage） |
| 写真 | 端末内のみ（ファイルシステム） |
| アプリ設定 | 端末内のみ（AsyncStorage） |
| 生成回数 | 端末内のみ（AsyncStorage） |

当社は独自のサーバーにユーザーの個人データを保存しません。

## 3. 第三者サービス

本アプリは以下の第三者サービスを利用しています。各サービスの利用規約・プライバシーポリシーもあわせてご確認ください。

| サービス | 用途 | プライバシーポリシー |
|----------|------|----------------------|
| Google Gemini API | AI日記生成（無料プラン） | https://policies.google.com/privacy |
| Anthropic Claude API | AI日記生成（Proプラン） | https://www.anthropic.com/privacy |
| Supabase | API通信の中継 | https://supabase.com/privacy |

## 4. 子どものプライバシー

本アプリは13歳未満のお子様を対象としておらず、13歳未満のお子様から意図的に個人情報を収集することはありません。

## 5. データの削除

アプリ内のデータはすべて端末内に保存されています。アプリをアンインストールすることで、すべてのデータが削除されます。

## 6. 地域別の権利

### 6.1 欧州経済領域（EEA）のユーザー — GDPR
EU一般データ保護規則（GDPR）に基づき、EEA にお住まいのユーザーには以下の権利があります。

- **アクセス権**: ご自身のデータへのアクセスを求める権利
- **訂正権**: 不正確なデータの訂正を求める権利
- **削除権**: データの削除を求める権利
- **処理の制限権**: データ処理の制限を求める権利
- **データポータビリティ権**: データを移転可能な形式で受け取る権利
- **異議申立権**: データ処理に異議を申し立てる権利

本アプリのデータは端末内にのみ保存されるため、上記の権利はアプリのアンインストールにより行使できます。

処理の法的根拠: 本アプリのデータ処理は、サービス提供に必要な処理（GDPR第6条1項(b)）および正当な利益（GDPR第6条1項(f)）に基づきます。

### 6.2 カリフォルニア州のユーザー — CCPA
カリフォルニア州消費者プライバシー法（CCPA）に基づき、カリフォルニア州にお住まいのユーザーには以下の権利があります。

- 収集される個人情報のカテゴリを知る権利
- 個人情報の削除を求める権利
- 個人情報の販売をオプトアウトする権利

当社はユーザーの個人情報を第三者に販売しません。

## 7. プライバシーポリシーの変更

本プライバシーポリシーは、必要に応じて更新されることがあります。変更があった場合は、本ページの最終更新日を更新します。

## 8. お問い合わせ

プライバシーに関するご質問やご要望がございましたら、以下までご連絡ください。

メール: nocta.diary@gmail.com

---

# Privacy Policy

Last Updated: March 29, 2026

Thank you for using Nocta - AI Diary (the "App"). This Privacy Policy explains how information is handled in the App.

## 1. Information We Collect

### 1.1 Information You Provide
- Photos (taken with the camera or selected from the photo library)
- Emotion selections
- Quick notes (optional)

This information is stored **only on your device (local storage)**. We do not store user data on our servers.

### 1.2 Information Used for AI Generation
When using the diary generation feature, photos (resized), selected emotions, and notes are sent to external AI services to generate diary entries. This communication is routed through our Supabase Edge Function.

- Information sent: Resized photos (base64), emotions, notes, photo timestamps, language setting
- Destination: Google Gemini API or Anthropic Claude API (via Supabase Edge Function)
- Photos are used only for diary generation and are not stored on external servers
- Anthropic's Privacy Policy: https://www.anthropic.com/privacy
- Google's Privacy Policy: https://policies.google.com/privacy

### 1.3 Biometric Information
The App offers a lock feature using Face ID / Touch ID. Biometric data is processed in the device's secure enclave and is never accessed by the App.

## 2. Where Information Is Stored

| Information | Storage Location |
|-------------|-----------------|
| Diary data (text, titles) | Device only (AsyncStorage) |
| Photos | Device only (file system) |
| App settings | Device only (AsyncStorage) |
| Generation counts | Device only (AsyncStorage) |

We do not store personal user data on our own servers.

## 3. Third-Party Services

The App uses the following third-party services. Please review their respective privacy policies.

| Service | Purpose | Privacy Policy |
|---------|---------|---------------|
| Google Gemini API | AI diary generation (Free plan) | https://policies.google.com/privacy |
| Anthropic Claude API | AI diary generation (Pro plan) | https://www.anthropic.com/privacy |
| Supabase | API communication relay | https://supabase.com/privacy |

## 4. Children's Privacy

The App is not intended for children under 13 years of age, and we do not knowingly collect personal information from children under 13.

## 5. Data Deletion

All app data is stored on your device. Uninstalling the App will delete all data.

## 6. Regional Rights

### 6.1 Users in the European Economic Area (EEA) — GDPR
Under the General Data Protection Regulation (GDPR), users residing in the EEA have the following rights:

- **Right of access**: Request access to your data
- **Right to rectification**: Request correction of inaccurate data
- **Right to erasure**: Request deletion of your data
- **Right to restriction**: Request restriction of data processing
- **Right to data portability**: Receive your data in a transferable format
- **Right to object**: Object to data processing

Since the App stores data only on your device, these rights can be exercised by uninstalling the App.

Legal basis for processing: Data processing in the App is based on the necessity for service provision (GDPR Article 6(1)(b)) and legitimate interests (GDPR Article 6(1)(f)).

### 6.2 California Users — CCPA
Under the California Consumer Privacy Act (CCPA), California residents have the following rights:

- The right to know what categories of personal information are collected
- The right to request deletion of personal information
- The right to opt out of the sale of personal information

We do not sell users' personal information to third parties.

## 7. Changes to This Policy

This Privacy Policy may be updated as needed. Any changes will be reflected by updating the "Last Updated" date on this page.

## 8. Contact Us

If you have any questions or concerns about privacy, please contact us at:

Email: nocta.diary@gmail.com
