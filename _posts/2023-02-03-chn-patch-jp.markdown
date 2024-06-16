---
title: "CHAOS;HEAD NOAH Overhaul Patch (日本語)"
layout: post
permalink: "/projects/chn-patch-jp.html"
active_tab: projects
date: 2023-02-03 00:00:00 +0100
excerpt: <p>カオスの世界へようこそ。</p>
hidden: true
---

# [**English**]({{ "/projects/chn-patch.html" | relative_url }})

### 規制コンテンツの修正

CHAOS;HEAD NOAH の Switch・PC 版は移植の際に PSP・PS3 版をベースにしたため一部のテキストがオミットされてしまった。ゲーム内の規制箇所は計 11 シーンに及び、特にあるルートではテキストにして５００行を超える重要な場面が簡略化されている。

当パッチではそれぞれの規制箇所を Xbox 360・Vita 版に基づいて修正した。

下着 DLC の規制も同様に撤廃。本移植でカットされた星来の別衣装を実装した。

### バグ修正

再生されない動画、映らない立ち絵、画像の表示ミスといった重大なバグを修正。

見落としたバグがあれば、ぜひ Discord サーバーに参加してお知らせください！

### QoL の改良

少し読み進む度に文字送りを止めていたスキップ機能を改善。ちゃんとテキストを飛ばせるようになった。

共通ルートクリア後に予め決められた章まで飛ばせるショートカットメニューは元々誤った開放条件が付けられたまま発売されていた。もちろんこれも修正済。

そして最後に Xbox 360・Vita 版をより忠実に再現するため、一部 Tips の解除条件を変更した。お楽しみに！

### セーブデータの互換性

パッチ適用前のセーブデータをそのまま持ち越して読み込むことができる

# インストール方法

### Steam

1. **[↓ インストーラーをダウンロードしてください。](https://github.com/CommitteeOfZero/chn-patch/releases).** ソースコードではなく、`CHNSteamPatch-v<version>-Setup.zip`をダウロードしてください。
2. ゲームフォルダー以外のハードドライブのどこかでアーカイブを解凍してください。
3. [下着 DLC](https://store.steampowered.com/app/2103330/CHAOSHEAD_NOAH__COSTUME_DLC/)がインストールされていて**Steam は実行中であることを確認してください。**
4. 新しく作られた`CHNSteamPatch-v<version>-Setup`フォルダーに移動してから`CHNSteamPatch-Installer.exe`を実行してください。**※音量注意**

- インストーラーが`MSVCP140_1.dll`についてのエラーで停止したら[Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe)（32 ビットバージョンの vc_redist.x86.exe）をインストールして再試行してください。

5. Finish をクリックしてインストーラーが閉じたら、ご自由に`CHNSteamPatch-v<version>-Setup`フォルダーを削除できます。

### GOG

1. **[↓ インストーラーをダウンロードしてください。](https://github.com/CommitteeOfZero/chn-patch/releases).** ソースコードではなく、`CHNGOGPatch-v<version>-Setup.zip`をダウロードしてください。
2. ゲームフォルダー以外のハードドライブのどこかでアーカイブを解凍してください。
3. [下着 DLC](https://www.gog.com/en/game/chaos_head_noah_costume_dlc)がインストールされていることを確認してください。
4. 新しく作られた`CHNGOGPatch-v<version>-Setup`フォルダーに移動してから`CHNGOGPatch-Installer.exe`を実行してください。**※音量注意**

- インストーラーが`MSVCP140_1.dll`についてのエラーで停止したら[Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe)（32 ビットバージョンの vc_redist.x86.exe）をインストールして再試行してください。

4. Finish をクリックしてインストーラーが閉じたら、ご自由に`CHNGOGPatch-v<version>-Setup`フォルダーを削除できます。

### CFW Switch

1. **[↓ パッチアーカイブをダウンロード](https://github.com/CommitteeOfZero/chn-patch/releases)**
   ソースコードではなく、`CHNSwitchJPPatch-v<version>-Setup.zip`をダウンロードしてください。
2. アーカイブ内容を Switch 用の SD カードのルートフォルダーに展開してください。
