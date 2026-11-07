# AevBenchmark Pro

日本語 / English対応のゲーミングデザイン静的ブラウザベンチマークサイトです。

## 機能
- CPU / JavaScript演算テスト（時間調整）
- Canvas描画FPS測定とリアルタイム描画デモ
- TypedArrayメモリ読み書き測定
- DOM生成負荷テスト
- localStorage I/O測定
- 任意URLへのネットワーク応答時間測定（CORS・ネットワーク条件に依存）
- Web API対応状況チェック（WebGL、WebGPU、Workerなど）
- CPU測定の安定性・変動率テスト
- デバイス・ブラウザ情報表示
- 総合スコアと項目別内訳
- ブラウザ内測定履歴、JSON / CSVエクスポート、レポートコピー
- PC・タブレット・スマートフォン対応
- GitHub ActionsによるGitHub Pagesデプロイ

## 公開方法
1. **Settings → Pages** を開く
2. Sourceを **GitHub Actions** に設定
3. **Actions** タブでデプロイ完了を確認
4. 公開URL: https://mylifereading6666-oss.github.io/AevBenchmark/

## プライバシーと注意
- サーバー、アカウント、分析トラッキングは使用しません。
- 測定履歴はブラウザの localStorage に保存されます。
- ネットワークテストは入力されたURLへのリクエストを行います。
- 本サイトはブラウザ上の参考測定です。物理GPU全性能、実RAM帯域、CPU型番、温度を直接測定するものではありません。
- スコアはブラウザ、端末、電源モード、温度、バックグラウンド処理などで変動し、異なる機種間の厳密比較には適しません。
- 高負荷テストは発熱・電池消費を増やす可能性があります。端末が熱くなったり動作が重くなった場合は停止してください.
