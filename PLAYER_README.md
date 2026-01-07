# 星影の約束（プレイヤー向け簡易ガイド）

開発版ではなく、配布ビルドで遊ぶ人向けの案内です。Godotのインストールは不要で、同梱の実行ファイルで起動できます。

---

## 動作環境
- Windows 10/11（デスクトップ版ビルドを想定）
- それ以外のOSは今後追加予定（Mac/Linuxなど）

---

## ダウンロード
1. GitHub Releases ページから最新版の zip をダウンロード
2. 好きな場所に展開

---

## 起動方法（Windows）
1. 展開したフォルダ内の `.exe` を実行
2. SmartScreen で警告が出た場合は「詳細情報」→「実行」を選択（署名なしビルドのため）

---

## 基本操作
- 移動: 矢印キー / WASD
- インタラクト: F
- キャンセル / メニュー: Esc
- マップ移動: M

---

## セーブデータ
Godotの `user://` に保存されます。OS別の例:
- Windows: `%AppData%/Godot/app_userdata/星影の約束/`
- macOS: `~/Library/Application Support/Godot/app_userdata/星影の約束/`
- Linux: `~/.local/share/godot/app_userdata/星影の約束/`

---

## 既知の注意点
- 配布ビルドは署名なしです。Windows SmartScreen や macOS Gatekeeper で警告される場合があります。
- 解像度や入力設定は今後のビルドで調整予定です。
- 不具合を見つけた場合は、再現手順とあわせて Issueで知らせてもらえると助かります。

---

## フィードバック
GitHubのIssueで報告・要望を受付中です。プレイ環境（OS/ビルド版）と再現手順を書いてもらえるとスムーズです。
---

## ライセンス
本作はCC BY-NC 4.0（表示-非営利）で公開しています。詳細は LICENSE を参照してください。
