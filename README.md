# qu1n5ify
全て十五の所為です。様の『15』模倣を支援するソフトです
テキストと2進数列(binary.txt)に基づき、文字が点滅する動画を生成します。  
任意でMIDIファイル(input.mid)を読み込めば、タイミングを同期可能です。動画と曲を合わせやすいように、正弦波を鳴らします。
READMEの作り方が少しわかりました。

## 使い方
1. `quinzify.exe`をダウンロードし、`fonts.zip`を解凍し、inputフォルダを隣に作成します。
2. inputフォルダ内で`binary.txt` に二進数列を記述してください。
3. inputフォルダ内に`input.mid` を配置すると、MIDIノートに基づいたタイミングと音が合成されます。
4. アプリを実行し、表示したいテキストを入力してください。
5. `output.mp4`がいい感じ に動画が生成されます。

## 注意事項♡
- `binary.txt` に0と1以外が含まれると、プログラムは中断されます♡
- MIDIファイルが無い場合は0.5秒間隔で処理されます♡

## 使用フォント
このソフトウェアは「源全ゴシック」フォントを使用しています。
- 配布元: [源全ゴシック Google Drive](https://drive.google.com/drive/folders/19WidrJoCmI5qLJV-eR_ydURIwxB2-DSH)
- ライセンス: SIL Open Font License 1.1 ([OFL 公式サイト](https://scripts.sil.org/OFL))
- クレジット: © 2021 全て語り手の所為です。

`fonts/` フォルダ内にライセンス文書（OFL.txt）と補足資料を同梱しています。
