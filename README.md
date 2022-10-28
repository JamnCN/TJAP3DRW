# Taiko-Re-Strap
 
# 使用上の注意
このプログラムを使用した不具合・問題については責任を負いかねます。

## How 2 Build
- VisualStudio 2017 & C# 7.3
- VC++ toolset
- SlimDX用の署名

## ライセンス関係
Fork元より引用。

> 以下のライブラリを使用しています。
> * bass
> * Bass.Net
> * DirectShowLib
> * FDK21
> * SlimDX
> * SharpDX
> * ReadJEnc
> * xadec
> * IPAフォント
> * libogg
> * libvorbis
> 「実行時フォルダ/Licenses」に収録しています。
> 
> また、このプログラムはFROM氏の「DTXMania」を元に製作しています。

# Changelog
```
v0.0　TJAPlayer3-Develop-ReWrite(touhou_renren氏開発)
v0.1(2022_03/2)　難易度選択画面のタイトル、サブタイトルの文字縮小の追加
v0.2(2022_03/19)　東方背景の追加(現在アーカイブ化)
v0.2.1(2022_03/20)　演奏右上のタイトル名が縮小倍率時の座標ずれを修正(タイトル名が短い時のセンターラインのずれは直せてない)
v0.3(2022_04/03)　通常背景の上背景と下背景それに伴ったクリア背景の追加、2P用のプチキャラを選択できるように
v0.3.1(2022_04/06)　changelogの追加、ASIO4ALL、DirectX、SlimDXのインストーラーを同梱(\インストールが必要)
v0.3.2(2022_04/08)　使われていないコード、Usingの削除
v0.4(2022_04/13)　.Net Framwork 4.8 Runtimeの同梱、2P Rollエフェクトの修正、演奏中の2Pスコアランクの追加、AssemblyInfoの更新
v0.4.5(2022_04/17)　2Pスコアランクのコードを一旦削除、リザルトの演出スキップを追加
v0.5(2022_04/20)　リザルト画面にスコアランク、王冠を表示するように(2P不可)
v0.5.1(2022_04/25)　エンディングアニメの追加、入魂時のキャラクターエフェクトの追加(仮テクスチャ)
v0.5.2(2022_04/27)　選曲のジャンルバックのスクロール速度を調整
v0.5.3(2022_04/29)　(CYakigasi氏)のネームプレート調整機能の移植、演奏終了演出(クリア成功)を従来のものに変更
v0.5.4(2022_04/30)　風船のフレーム座標の修正
v0.5.5(2022_05/01)　演奏オプションをmtaikoに表示、難易度選択画面にいくつか効果音を追加
v0.5.6(2022_05/04)　演奏オプションアイコンを選曲画面、リザルト画面に表示
v0.5.6.1(2022_05/05)　不要なテクスチャの読み込みを削除、ドンダフルコンボのループを追加
v0.5.6.2(2022_05/06)　キャラクターエフェクトのフェード追加
v0.5.7(2022_05/07)　下背景変更、下背景のフェード追加
v0.5.7.1(2022_07/11)　魂の点滅実装、その他調整
v0.5.7.2(2022_08/10)　MTaiko,Level-up&downを画像一枚化、リザルトの演出の一部を追加、ソフト名「Taiko-Re-Strap」に決定！
v0.5.7.3(2022_08/11)　ボカロのフォントカラー修正、ネームプレートの段位表示を削除
v0.5.7.4(2022_08/14)　下クリア背景に船を追加
v0.5.8(2022_08/15)　リザルトにキャラクターを表示
v0.5.9(2022_08/16)　選曲画面の描画順を修正、タイトルと選曲画面のキャラクタの再生速度,座標を修正、難易度選択画面に操作ガイド追加
v0.5.9.1(2022_08/19)　オプション設定の文字ずれ修正
v0.5.9.2(2022_08/30)　Box_Charaの描画順修正
v0.5.9.3(2022_09/12)　.NETFramework4.8.1(仮)
v0.5.9.4(2022_09/16)　2PMTaikoの描画ミスを修正
v0.6.0(2022_10/27)　一部の使っていないクラスをコメントアウト、特定のテクスチャの品質向上、
v0.6.1(2022_10/28)　使っていないコードを削除

# Thanks
以下の開発者様のコードを参考に開発させていただいております。

>DTXMania(FROM様)
>TJAP2fPC(Kairera0467様)
>TJAPlayer3(Aioilight様)
>TJAPlayer3(TwoPointZero様)
>TJAPlayer3-Develop-ReWrite(touhou_renren様)
>DonSpire(CYakigasi様)
>TJAPlayer3-f(Mr.Ojii様)
>OpenTaiko(0auBSQ様)
