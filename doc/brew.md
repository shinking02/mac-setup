# Homebrewによるパッケージのインストール
この章ではHomebrewを用いたパッケージのインストールについて記述しています。

## Homebrewのインストール
https://brew.sh/ja/ を参考にHomebrewをインストール。<br />
インストール後にPATHを通すように指示が出るのでそれに従ってを設定（echoコマンドを実行するだけ）

## パッケージのインストール
[.Brewfile](https://github.com/shinking02/mac-setup/blob/main/config/.Brewfile)をダウンロードし、ホームディレクトリに配置。
その後、下記のコマンドを実行。
```
brew bundle --global
```
