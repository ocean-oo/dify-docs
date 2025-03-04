# よくある質問

## プラグインのインストール時にアップロードが失敗する場合の対処方法は？

**エラー詳細**：`PluginDaemonBadRequestError: plugin_unique_identifier is not valid` というエラーメッセージが表示されます。

**解決方法**：プラグインプロジェクトの `manifest.yaml` ファイルと `/provider` パス配下の `.yaml` ファイルの `author` フィールドを GitHub ID に変更してください。

プラグインのパッケージングコマンドを再実行し、新しいプラグインパッケージをインストールしてください。
