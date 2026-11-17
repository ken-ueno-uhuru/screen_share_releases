# ScreenShareSwitcher 配布用

Google Meet などの画面共有で、共有する画面をワンクリックで切り替えるアプリの配布用リポジトリ。
ここにはビルド済みのアプリだけを置いている。

## Mac 版

最新版: <!-- mac-latest -->[ScreenShareSwitcher-0.3.0.zip](https://github.com/ken-ueno-uhuru/screen_share_releases/releases/download/mac-v0.3.0/ScreenShareSwitcher-0.3.0.zip)<!-- /mac-latest -->

- Apple シリコン（M1 以降）、macOS 14 以降
- 一度インストールすれば、以降は新しい版が出るとアプリが通知して自動で更新できる（メニューバーのアイコンを右クリック →「アップデートを確認…」でも確認できる）

### インストール

1. 上の zip をダウンロードして解凍し、`ScreenShareSwitcher.app` を「アプリケーション」フォルダに移す
2. ダブルクリックすると「開けません」と出るので「完了」で閉じる
3. 「システム設定」→「プライバシーとセキュリティ」の下の方にある「このまま開く」を押し、もう一度起動して「開く」を押す
4. 画面収録の許可を求められるので、「システム設定」→「プライバシーとセキュリティ」→「画面収録とシステムオーディオ録音」で ScreenShareSwitcher をオンにして、アプリを起動し直す
5. バーでアプリを選んだときに「アクセシビリティ」、Chrome のタブ一覧を初めて開いたときに「オートメーション」の許可を求められるので、オンにする

### 使い方

- メニューバーのアイコンをクリック（または `⌃⌥S`）で共有モードを開始
- Meet の「画面を共有」→「ウィンドウ」で「Screen Share Mirror」を選ぶ
- バーのアイコンをクリックすると、共有する画面が切り替わる

## Windows 版

最新版: <!-- win-latest -->[ScreenShareSwitcher.exe（0.3.0）](https://github.com/ken-ueno-uhuru/screen_share_releases/releases/download/win-v0.3.0/ScreenShareSwitcher.exe)<!-- /win-latest -->

- Windows 11
- 一度入れれば、以降は新しい版が出ると裏でダウンロードされ、タスクトレイに通知が出る。トレイのアイコンを右クリック →「再起動してアップデート」か、次にアプリを起動し直したときに更新される（「アップデートを確認…」でも確認できる）

### インストール

1. 上の `ScreenShareSwitcher.exe` をダウンロードし、ドキュメントなど自分のフォルダに置く（自動アップデートで exe を書き換えるため、「Program Files」などには置かない）
2. ダブルクリックで起動する。「Windows によって PC が保護されました」と出たら「詳細情報」→「実行」を押す（署名していないため。最初の 1 回だけ）
3. タスクトレイにアイコンが出る
4. ログイン時に自動で起動したい場合は、exe を右クリック →「ショートカットの作成」で作ったショートカットを、`Win+R` →「`shell:startup`」で開いたフォルダに移す

やめるときは、トレイのアイコンを右クリック →「ScreenShareSwitcher を終了」してから exe を削除する。

### 使い方

- タスクトレイのアイコンをクリック（または `Ctrl+Alt+S`）で共有モードを開始
- Meet の「画面を共有」→「ウィンドウ」で「Screen Share Mirror」を選ぶ
- バーのアイコンをクリックすると、共有する画面が切り替わる
