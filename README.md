# リモートワーク ハンドブック

## これは何

NTT コミュニケーションズ株式会社の有志で整備した、リモートワークを効率的に行うための手引きです。


## 閲覧方法

TBD ですが、現状 GitHub Pages で公開することを計画しています。

## ビルド方法（暫定）
1. Hugo Extended をインストールする（参考： https://gohugo.io/getting-started/installing/ ）
2. `git clone --recursive https://github.com/ppyv/remote-work-handbook.git`
   （外部テーマを submodule として呼んでいるので、 `--recursive` が必須）
3. `cd remote-work-handbook`
4. `hugo server`
5. ブラウザで http://localhost:1313 へアクセスする

現状 config.toml の `baseURL` がめちゃくちゃなので、単に `hugo` を実行することで得られる静的ファイルはもれなく破損した状態になります。

## ライセンス (LICENSE)
この作品はクリエイティブ・コモンズ・表示 - 非営利 - 継承 4.0 国際・ライセンスで提供されています。このライセンスのコピーを閲覧するには、http://creativecommons.org/licenses/by-nc-sa/4.0/ を訪問して下さい。

## To Do
- [X] ライセンスの整備
- [X] 公開先の整理
  - GitHub Pages
- [ ] How to contribute の整備
- [ ] Editorconfig の準備

## Author
© NTT Communications Corporation 2020
