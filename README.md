# Android Studio Shortcut Key

| 概要            | キー           | 備考           |
| ------------- |-------------|-------------|
| 大、小文字変換 | Cmd + Shift + u |-| 
| 自動フォーマット | Cmd + Opt + l |-| 
| 自動インポート | Ctr + Opt + o |-| 
| 単語選択 | Opt + 上矢印 |-| 
| 行削除 | Cmd + Del |-| 
| 呼び出し元 | Cmd + Alt + h |-| 
| エラーの場所に移動 | 上矢印 + F2 |-| 
| 階層 | Ctr + h |-| 
| 参照先 | Alt + F7 |-| 
| メンバ変数とメンバメソッドの一覧 | Cmd + F12 |-| 
| メソッド、フィールドに移動 | Opt + Cmd + o |-| 
| メソッドが期待している引数を表示 | Ctr + p |-| 
| ファイルで使用している変数のハイライト | Ctr + Shift + F7 |-| 
| クイック定義確認 | Opt + Space |-| 
| オートジェネレーター | Cmd + Opt + t |-| 

# Android adb

| 内容            | コマンド           | 備考           |
| ------------- |-------------|-------------|
| ログ出力 | adb logcat |-| 
| ログをファイルに出力 | adb logcat > file.log |-|
| 時間を含めたログをファイルに出力 | adb logcat -v time > file.log |-|
| adbの停止 | adb kill-server |-|
| adbの起動 | adb start-server |-|
| デバイスのファイルを取得 | adb pull /sdcard/Download/ |-| 
| デバイスにファイルを配置 | adb push 配置するファイル /sdcard/Download/ |-| 


