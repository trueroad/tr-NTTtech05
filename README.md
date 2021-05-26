<!-- -*- coding: utf-8 -*- -->
# 「PDFのコピペが文字化けするのはなぜか？～CID/GIDと原ノ味フォント～」関連資料

[NTT Tech Conference #5
](https://ntt-developers.github.io/ntt-tech-conference/05/)
Presentation
「PDFのコピペが文字化けするのはなぜか？～CID/GIDと原ノ味フォント～」
関連資料です。

なお、2021 年 2 月 26 日当時の最新版だった Chrome 88 や、
その後の Chrome 90 までは文字化けしましたが、
2021 年 5 月 26 日リリースの Chrome 91 では文字化けしなくなりました。

## 発表資料

* [slideshare](https://www.slideshare.net/trueroad_jp/pdfcidgid)
* [PDF](./slide/why-pdf-copy-paste-garbled-release.pdf)
* [ソースファイルなど](./slide/)

## アーカイブ動画

* [アーカイブ動画](https://www.youtube.com/watch?v=y5AQbo8tMlE&t=2222s)

## 書き起こし記事

* [
「PDFをコピペするとなぜ“文字化け”が起きてしまうのか
変換テーブル“ToUnicode CMap”が原因だった」
](https://logmi.jp/tech/articles/324366), [
ログミー Tech
](https://logmi.jp/tech)

## テストファイル

発表資料中で使ったファイルです。

* [適当な HTML （文字化けしていない）](./testfile/foobar.html)
* [Chrome 88 で「PDF に保存」したファイル](./testfile/foobar.html.pdf)
* [QDF 形式に変換したファイル](./testfile/foobar.html.qdf)

## License

Copyright (C) 2021 Masamichi Hosoda.

License: CC BY-SA 4.0

[LICENSE](./LICENSE) をご覧ください。
