# I/O ベンチマークツール

## 満たす仕様

- [ ] Linux 上で動作する。
- [ ] ファイルシステム上の通常ファイルに対して、シーケンシャルな書き込みを行う。
- [ ] 書き込みを行うファイルを開く際、O_SYNC フラグを指定する。
- [ ] コマンドライン引数で並列度を受け取り、その並列度でベンチマークを行う。各ベンチマーク処理はそれぞれ異なるファイルへ書き込む。
- [ ] コマンドライン引数でブロックサイズを受け取り、書き込みはブロックサイズ単位で行う。
- [ ] コマンドライン引数でファイルサイズを受け取り、各ファイルにこのサイズまで書き込みを行う。
- [ ] 全ベンチマーク処理の完了後、並列で実行したベンチマークごとにスループットとレイテンシの平均値、最良値、最悪値をそれぞれ表示する。
