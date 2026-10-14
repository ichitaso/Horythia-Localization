# Horythia
### Horythiaは、アプリとシステム間の境界を制御します。

**アプリごとに端末の設定を自動で切り替え。Wi-Fi、モバイル通信、明るさ、音量、おやすみモード、位置情報の偽装など。Respring不要。**

## Horythiaとは
指定したアプリを開いた瞬間に端末の設定を自動で変更し、アプリを離れると元に戻します。アプリごとに一度設定すれば、あとは任せられます。

ベースとなったTweakはNetworkDisablerというものです。redditのユーザーからのリクエストで作り直しました。

名前はギリシャ神話に出てくるカリスのようなラテン語っぽい造語です。呼び方はホォリシアという感じ

<p middle="center">
  <img width="30%" alt="Settings View" src="https://github.com/user-attachments/assets/ce0d72a2-4fed-49ed-9ca1-1534a8a8bb77" />
  <img width="30%" alt="Location Spoofing" src="https://github.com/user-attachments/assets/65f2da33-59a9-4c2d-8b57-fe8cf6f525e0" />
  <img width="30%" alt="Home Screen Settings View" src="https://github.com/user-attachments/assets/31b3c9cc-9584-4a97-85c1-2f084e077dd7" />
  <img  width="30%" alt="3D Touch Menu" src="https://github.com/user-attachments/assets/92735e1d-7249-432d-9295-431b82d93f12" />
</p>

## 主な機能
次の項目を、アプリごとに自由に組み合わせて設定できます。

- Wi-Fi: オン / オフ
- モバイルデータ通信: オン / オフ
- 位置情報サービス: オン / オフ
- **位置情報を偽装**: そのアプリだけで任意の位置を使用。地図から選択（検索・タップ）お気に入り機能もあり、または緯度・経度を入力
- 機内モード: オン
- おやすみモード: オン
- 低電力モード: オン
- Bluetooth: オン / オフ
- VPN: オン
- 自動ロック: オフ
- 明るさの自動調節: オフ
- 明るさ: レベルを指定
- 音量: レベルを指定
- 画面の向きのロック: オフ

その他の機能:
- ホーム画面のアイコンを長押し（フォースタッチ）して、すぐに設定できるメニュー
- 検索付きのアプリ一覧。設定済みのアプリは一番上に表示
- 設定の書き出し / 読み込み、アプリ単位または全体のリセット
- 反対の項目（Wi-Fiのオン / オフなど）は同時に選べないよう自動でロック
- 変更は即時に反映。Respringは不要

## 動作環境
- iOS 15.0 以降
- rootless / rootful / roothide 脱獄環境（roothideパッケージはHavocで対応していないため個別対応） 
- Depends（mobilesubstrate / ElleKit), PreferenceLoader
- 動作確認デバイス: iOS 15.1 (Dopamine roothide) / iOS 15.4.1 (Dopamine) / iOS 16.5 (Dopamine) / iPadOS 17.5.1 (Dopamine) / iPadOS 18.6 (palera1n) / iOS 26.0.1 (Dopamine)

## メリット
- **設定したら任せきり**: アプリを開くと最適な設定が適用され、離れると元に戻ります
- **全体ではなくアプリ単位**: アプリごとに必要な状態を用意できます
- **すぐ使える**: アイコンを長押しして、そのアプリの設定を変更できます
- **安心して試せる**: 設定をまとめてバックアップ・復元できます
- **17言語に対応**

## 対応言語
English、日本語、简体中文、繁體中文、한국어、Español、Français、Deutsch、Italiano、Português (Brasil)、Русский、العربية、Türkçe、Bahasa Indonesia、ไทย、Tiếng Việt、Nederlands

## 返金ポリシー
お使いの端末やiOSバージョンでHorythiaが動作せず、解決できない場合は購入から3日以内にご連絡ください。
サポートを行っても動作しない場合、Havoc経由で返金の手続きをします。購入前に上記の動作環境をご確認ください。


## 重要な注意事項
- Horythiaは、アプリが前面にある間、Wi-Fiやモバイル通信などの実際のシステム設定を変更し、離れたあとに元へ戻します。設定済みのアプリを開いている間にSpringBoardが再起動すると、一部の設定が変更されたままになることがあります。
- **位置情報の偽装**は、そのアプリが受け取る位置だけを置き換えます。端末全体の位置は変わりません。独自の位置チェックやサーバー側の検証があるアプリでは、本物の位置を検知される場合があります
- 対象のアプリがTweakを読み込める必要があります。Choicyなどでアプリごとに注入を制限している場合は、そのアプリでHorythiaを許可してください
- **位置情報の偽装を規約で禁止しているアプリやゲームがあります。自己責任でご使用ください**
- 機内モードは、Wi-Fiをオンのままにするオプションがあります
- 位置情報を偽装するTweakやアプリがある場合、それが原因でTweakが正しく機能しないため注意して下さい。
- 位置情報の偽装のためUIKitフィルターを使用していますが、基本の機能はSpringBoard上で動作します。

## プライバシー
Horythiaはデータを収集・送信しません。次の2点にご注意ください。
- 「地図から選択」は、地図の表示と検索にAppleの地図サービスを使います
- 「メールでサポート」は、機種名、iOSバージョン、端末ID（UDID）、インストール済みパッケージ一覧を含むメールを自動で作成します。送信前に内容を確認・編集できます

## 連携アドオン
CCSupport用のアドオン（コントロールセンターからHorythiaのオン / オフを切り替え）は、別途CCSupportをインストールする必要があります。

## 動画
実際の動作はこちら: <a href="https://www.youtube.com/watch?v=NMXWyFqaAgQ" target="_blank">iOS Tweaks Horythia demonstration - YouTube</a>

## サポート
メール: 設定内のリンクもしくはHavocのページ経由でお問い合わせ可能です / Bluesky: [@ichitaso.com](https://bsky.app/profile/ichitaso.com) / Discord: https://discord.gg/FuDBaWryge
