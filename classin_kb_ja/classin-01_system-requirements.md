---
kb_name: ClassIn ヘルプセンター ナレッジベース
language: ja-JP
category: ClassIn（クライアント）
subcategory: "1. 動作要件とデバイス情報確認"
batch: 10 of N
translated_from: zh-CN (source: ClassIn/1._配置要求与查询)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 1. 動作要件とデバイス情報確認

<!-- DOC_BOUNDARY -->
```yaml
title: "デバイス情報の確認：スペック、ベンチマークスコア、通信速度、チップモデル"
source_title_zh: "设备信息查询：配置，跑分，网速，芯片型号"
```

## デバイス情報の確認：スペック、ベンチマークスコア、通信速度、チップモデル

## 一、パソコンのスペックを確認する

### こんな時に使う
パソコンのスペック確認とは、特定のソフトウェアの動作要件を満たしているかどうかを確認するために、パソコンのハードウェアとシステムの仕様を調べることです。パソコンを利用するユーザーは、「パソコンの動作要件」に記載されているハードウェアパラメーターを参照し、ご自身のパソコンのハードウェア構成と照らし合わせて、ClassInを実行できるかどうかを確認できます。

### 操作手順

**（1）Windowsパソコンの場合**
1. デスクトップの「PC」を右クリックします。
2. 「プロパティ」を選択します。
3. 「デバイスの仕様」でメモリ容量とCPUモデルを確認します。

![](https://cofile.eeo.cn/res-store%2F207d74d5f0e039ef1498ace4e289f42cb4e480653d840eb3c47df6733319d61b_254401?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=82c2969925bd7134ba35e3fb67c100d9ed687e63)

**（2）Macパソコンの場合**
1. 「Launchpad」を開きます。
2. 検索欄に「ターミナル」と入力し、「ターミナル」アプリを開きます。
3. ターミナルウィンドウのプロンプト（例：`LeondeMacbook-Air:~ shouhouzhichi$`）の右側に `sysctl machdep.cpu.brand_string` と入力します。
4. 入力後、Enterキーを押します。
5. コマンド実行後の出力結果で、パソコンのCPUモデル情報を確認します。

![](https://cofile.eeo.cn/res-store%2Fd8e2f7bd40c5df5a8612c7bb3e852b5d2fe0243d74dcf5560cb1859dd34fcea5_361026?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=24d5c2fa2a2f9e340e6f51170e22071a2f610772)

## 二、通信速度を確認する

ClassInを使ってオンライン授業・学習を行う際に安定したネットワーク接続を確保するため、開始前にご自身のネットワーク状況を確認してください。事前にネットワークを検査し設定を最適化しておくことで、ClassInをスムーズに動作させ、オンライン授業を安定してサポートできます。

### 使用方法
検査結果で注目すべき主な指標は、ネットワークの上り速度、下り速度、遅延、ジッター、パケットロス率です。ネットワークが以下の要件をすべて同時に満たしていない場合、ClassIn利用時に接続の不安定さや頻繁な切断などの問題が発生し、授業に支障をきたす可能性があります。

| 最低限必要なネットワーク要件 |
| --- |
| 上り速度：2Mbps以上 |
| 下り速度：2Mbps以上 |
| 遅延：中国国内：50ms以内、海外地域：300ms以内 |
| パケットロス率：0%であること |

1. 「ブラウザ」を開きます。
2. ブラウザのアドレスバーに以下を入力します：https://www.speedtest.cn
3. 「測定」をクリックします。

![](https://cofile.eeo.cn/res-store%2F46e397fb953659ed33b6119718556f27b879769eae8acb042399cad96d359215_366221?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=1c368b8a4de4a408039fe6447a6a79dccd3d22eb)

## 三、デバイスのベンチマークスコアを確認する

### こんな時に使う
ユーザーは、パソコンのCPUモデルに基づいて、指定のCPUベンチマークスコア確認サイトでCPUの性能スコアを調べることで、ClassInが正常に動作するかどうかを確認できます。

### 使用方法
教師用パソコンのCPU性能スコアは6000点以上が必要です。

生徒用パソコンのCPU性能スコアは4000点以上が必要です。

### 操作手順
1. ブラウザのアドレスバーに次のURLを入力します：https://www.cpubenchmark.net/cpu_list.php
2. 検索欄にお使いのパソコンのCPUモデルを入力します。
3. 「Find CPU」をクリックして検索します。
4. 左側の黄色いエリアで、ご自身のパソコンのCPUモデルと完全に一致するものを探します。
5. 右側の「CPU Mark」欄の数値を確認します。この数値がお使いのパソコンのCPU性能スコアです。

![](https://cofile.eeo.cn/res-store%2F57ebd37b9391dcc022dca39ec54aa02be8efe5a589e51f54dec7efb985ed1179_379263?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a6179c425172f8f5c7289fccf95558b10e6f3f36)

## 四、Macのチップモデルを確認する

ClassInはMac向けに2種類のインストーラーを用意しています：Intelチップ搭載Mac用と、Appleシリコン（M1、M2など）搭載Mac用です。そのため、インストーラーをダウンロードする前に、まずご自身のパソコンのプロセッサの種類を確認し、対応するインストーラーを選んでダウンロードする必要があります。

1. 画面左上の「Appleメニュー」アイコンにマウスを合わせます。
2. メニューの「このMacについて」をクリックします。
3. 「このMacについて」画面の「プロセッサ」欄でCPUチップモデルを確認します。

![](https://cofile.eeo.cn/res-store%2Fa123ab72dc9c959fe87db4f2f7e97e2c25cae4e4e015a92b5a98d9815a6cfc25_461854?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=9a884733f148e07102c7b71df32b6837e017f04e)

<!-- DOC_BOUNDARY -->
```yaml
title: "動作要件"
source_title_zh: "配置要求"
```

## 動作要件

## 一、動作要件とは？

動作要件とは、ClassInソフトウェアを実行する際にデバイスに求められるハードウェア・ソフトウェア面での具体的な要件を指します。これらの要件には通常、プロセッサ、メモリ、オペレーティングシステムなどの主要な要素が含まれます。プロセッサ、メモリ、OSは、ソフトウェアが正常に動作するための基本条件です。授業の規模によってもハードウェアへの要求は異なり、ClassInでは登壇人数が増えるほど、ソフトウェアを安定して快適に動作させるためにデバイスへのハードウェア要件も高くなります。

## 二、パソコンの動作要件

| | 最低動作要件（生徒／録画しない教師） | 最低動作要件（録画教師） | 推奨動作要件（教師／生徒） |
| --- | --- | --- | --- |
| プロセッサ | Intel Core i3 第8世代以上、AMD Ryzen 3 第2世代以上 | Intel Core i5 第8世代以上、AMD Ryzen 5 第1世代以上 | Intel Core i7 第9世代以上、AMD Ryzen 7 第2世代以上 |
| メモリ | Windows：8GB RAM以上、Mac：4GB RAM以上 | Windows：16GB RAM以上、Mac：4GB RAM以上 | Windows：16GB RAM以上、Mac：8GB RAM以上 |
| OS | Windows 7以上、macOS 10.13以上 | Windows 7以上、macOS 10.13以上 | Windows 10以上、macOS 12以上 |
| 画面解像度 | 1280×720以上 | 1280×720以上 | 1920×1080以上 |
| ネットワーク帯域幅 | 2Mbps以上 | 4Mbps以上 | 6Mbps以上 |

## 三、スマートフォン・タブレットの動作要件

| | 最低動作要件（生徒／録画しない教師） | 最低動作要件（録画教師） | 推奨動作要件（教師／生徒） |
| --- | --- | --- | --- |
| OS | iOS：11以上、Android：7.0以上、HarmonyOS：1.0以上 | iOS：11以上、Android：10.0以上、HarmonyOS：2.0以上 | iOS：14以上、Android：10.0以上、HarmonyOS：2.0以上 |
| メモリ | Android：4GB以上、iPad/iPhone：2GB以上 | Android：8GB以上、iPad/iPhone：2GB以上 | Android：8GB以上、iPad/iPhone：3GB以上 |
| プロセッサ型番 | iPad/iPhone：A9以上。Android：Snapdragon 7シリーズ 730G以上／Snapdragon 8シリーズ 835以上／Kirin 8シリーズ 810以上／Kirin 9シリーズ 970以上／Dimensity 720以上／Helio G90T以上。 | iPad/iPhone：A11以上。Android：Snapdragon 8シリーズ 855以上／Kirin 9シリーズ 980以上／Dimensity 1000以上。 | iPad/iPhone：A12以上。Android：Snapdragon 8シリーズ 865以上／Kirin 9シリーズ 9000以上／Dimensity 1100以上。 |
| iPad/iPhone機種 | iPhone 6以降、iPad 5以降、iPad mini 4以降、iPad Air 3以降、iPad Pro以降。 | iPhone 8以降、iPad 6以降、iPad Pro以降。 | iPhone XS以降、iPad 8以降、iPad Pro 2以降、iPad mini 5以降、iPad Air 3以降。 |
| ネットワーク帯域幅 | 2Mbps以上 | 4Mbps以上 | 6Mbps以上 |

## 四、ClassIn X 推奨デバイス

教育シーンによって推奨されるデバイス性能は異なります：

**ダブルティーチャー教室**

![](https://cofile.eeo.cn/res-store%2F17766803a0c8c5cd1f6c361665599b60b57c960ecb9b915fcbb19071f3a640fd_100043?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=329f9adba452c88a144b07c0f7ec43fd3ac41910)

**通常の対面授業**

![](https://cofile.eeo.cn/res-store%2Fb8f0fd78dc217d592076750452affe93afff5f6def42a2f944e1047a904446df_119426?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=8c223e25fd4fb3ac83c68d1295ae42eee76c9cb6)

最低動作要件で推奨される機能：ペン、教材（PPT／PDF／音声動画など）、コードスキャンでの画像共有、補助カメラなどの基本的な授業ツール。

最低動作要件では非推奨の機能：Nobookおよびビデオウォール。

推奨動作要件を満たしていれば、すべての機能を利用できます。

## 五、ダブルティーチャー教育の推奨デバイス

ダブルティーチャー教室は、オンラインと対面授業を組み合わせた新しい試みとして、2015年に普及しました。オンラインの主講師と、教室での指導・進行を担う担任教師の役割分担により、優れた教師が地域を越えて授業を行うことを実現しています。

![](https://cofile.eeo.cn/res-store%2F7cd38a3d4277c24347b109ecad3e542b9e0224e85e797599f5d990e83e919dd0_885358?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a1c3b82b8bbb05039045350426d371e43dfc79a4)

ますます多くのパートナーが、ダブルティーチャー教室のインタラクションツールとしてClassInを選んでいます。ユーザーがより良い授業体験を得られるよう、以下のハードウェア調達プランを推奨しています：

![](https://cofile.eeo.cn/res-store%2F6ef3fbf38d682224d94a4f0f45a0fec73d64e410cda3072a5a13883bf3ebeba4_138418?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ee9c1339eb20a8b7f5866e5e316484816f6d3223)

## 六、リモート会議の推奨デバイス

EEOは、最もプロフェッショナルなオンライン教室製品の開発に取り組んでいます。実際の運用において、ClassInは非常に安定して使いやすいリモート会議システムでもあります。

ClassInユーザーがより良いリモート会議体験を得られるよう、私たち自身の使用経験に基づいて以下のハードウェアデバイスを推奨します。

![](https://cofile.eeo.cn/res-store%2Fdbd247b10b9b7e07ce4cf454f8b05bbcb1171ec9932abbf8821dc1f6cda00f58_279364?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ea97775d29e905af9a38f5fbd29b6bdcc69745c3)

![](https://cofile.eeo.cn/res-store%2F786974847dfd91a935b2103049e4c3db4af2bffee859539e13be64d9c1e84aa9_265608?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=41dda5ec9a238fdc43a21bdc9cd0f65f04c659aa)

*免責事項：本ページの情報は、EEOの実験校（一丟丟実験校）における実際の使用経験をまとめたものであり、市場にあるすべての製品を網羅するものではなく、厳密な製品評価でもありません。あくまで参考としてご利用ください。*
