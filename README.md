# fumendai

電子ピアノの押鍵を五線譜に表示し、PDF楽譜と並べて練習するWebアプリ

## check.html

Roland FP-30X などのBluetooth MIDI対応電子ピアノと、タブレットのChromeが正しく通信できるかを確認するための接続チェックツールです。Web MIDIとWeb Bluetoothの2つの経路で接続状況を確認し、鍵盤の入力をリアルタイムに表示します。

### 使い方

1. `check.html` をHTTPS環境（またはlocalhost）でホストし、Android版Chromeで開きます。
2. 画面の案内に従って、経路A（Web MIDI）または経路B（Web Bluetooth直接）でピアノに接続します。
3. 鍵盤を押して、音名や強さが表示されることを確認します。
