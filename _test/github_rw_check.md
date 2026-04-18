# GitHub ストレージ読み書き動作確認

作成時刻: 2026-04-18 (JST)
検証対象: storage_type=github での aipatto_commit → aipatto_read_file サイクル
ルートリポ: tatugmad/aipatto
期待: このファイルが GitHub リポにコミットされ、同じパスで読み出すと同じ内容が返る
