# WorldModeler / ワールドモデラー

Roblox のマップを、地面をぬって 部品（ブロックでできた小さなモデル）を置いて作る無料のツールです。できたマップは 1つの .rbxmx にして Roblox Studio に入れられます。
A free tool for building Roblox maps: paint the ground, place parts (small block models), and export the whole map to Roblox Studio as one .rbxmx.

> **いまはベータ版です。** うまく動かない所があれば、紹介ページのお問い合わせから教えてください：https://hajimete.myvoxels.com/creators/worldmodeler/#contact
>
> **This is a beta.** If something does not work, please tell me through the contact form: https://hajimete.myvoxels.com/creators/worldmodeler/#contact

## 開き方 / Open it

- zip を右クリックして「すべて展開」を選びます。できたフォルダの中の `WorldModeler` フォルダを開き、種類が「アプリケーション」の `WorldModeler` をダブルクリックします。インストールは要りません。ネットなしで動きます。
- 動作を確かめたのは Windows だけです。アプリには電子署名がないため、はじめて開く時に Windows の警告が出ることがあります。その時は「詳細情報」から「実行」を選んでください。

- Right-click the zip and choose "Extract All". Open the `WorldModeler` folder inside and double-click `WorldModeler`, the file whose type is "Application". No install, and it works offline.
- It has only been tested on Windows. The app is not code-signed, so Windows may show a warning the first time. Choose "More info", then "Run anyway".

## 作り方 / Make a map

1. はじめの窓で「まっさら」か 見本の「夜の縁日の神社」を選びます。
2. 地面をぬり、下の列から部品を選んで置きます。ブロックモデラーで作った `.blockmodel` も「＋」で部品にできます。
3. 「保存」で `.blockmap`（あとで続きを作れる形）に、「Roblox へ書き出す」で `.rbxmx` にします。
4. Roblox Studio で エクスプローラーの Workspace を右クリック →「挿入」→「Robloxモデルをインポート」で `.rbxmx` を選ぶと、マップが入ります（窓に ドラッグしても入ります）。

1. In the first window, choose "Blank" or the sample "Shrine festival at night".
2. Paint the ground, pick parts from the bar at the bottom and place them. A `.blockmodel` made with BlockModeler becomes a part with "＋".
3. "Save" writes a `.blockmap` (to keep working on it later). "Export to Roblox" writes a `.rbxmx`.
4. In Roblox Studio, right-click Workspace in the Explorer, choose "Insert" → "Import Roblox Model" and pick the `.rbxmx` (or drag it into the window).

## AI とつなぐ（MCP） / Connect AI (MCP)

画面の「AI とつなぐ（MCP）」を押すと、Claude Code に貼る 1行が出ます。貼って Enter のあと、新しいチャットに 画面の「AI に たのむ文を コピー」で コピーした 文を 貼ると、AI がアプリの画面の上でマップを組みます。スイッチは はじめオフです。オンの間だけ、この PC の中から AI がマップにさわれます。くわしくは `kit/CLAUDE.md` にあります。

Press "Connect AI (MCP)" on the screen to get one line to paste into Claude Code. After that, paste the text from "Copy the request for your AI" into a new chat, and the AI builds the map in the app's window. The switch starts off; only while it is on can an AI on this PC touch the map. The details are in `kit/CLAUDE.md`.

## ライセンス / License

`LICENSE-WorldModeler.txt` を見てください。無料で使えます。作ったマップは あなたの物です。
See `LICENSE-WorldModeler.txt`. Free to use; the maps you make are yours.

Roblox is a trademark of Roblox Corporation. This software is not affiliated with or endorsed by Roblox Corporation.
