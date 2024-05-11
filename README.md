# 『［改訂第9版］LaTeX美文書作成入門』サポートページ

2023年12月9日発売です。

## リンク

* [技術評論社（紙版）](https://gihyo.jp/book/2023/978-4-297-13889-9)
* [アマゾン（紙版）](https://www.amazon.co.jp/dp/4297138891)

## 入力例

第2章の入力例（コピペできます）：

```latex
\documentclass{jlreq}
\begin{document}

アインシュタインは $E=mc^2$ と言った。

\end{document}
```

## 文字コードを判別・変換するツールnkf、Windows版の入手先（p. 347）

文字コードを判別・変換するツールnkfのWindows版は、例えば https://github.com/kkato233/nkf/releases から入手できます。

## 「カバーのそで」コンテンツの公開

紙版の書籍にはフルカラーのカバーが掛かっています。カバーの折り込み部分（「そで」という）が深かったため、本文の2色刷りでは表現しきれなかった、フルカラー印刷できれば載せたかったというコンテンツを刷り込んでみました。電子版では提供が難しかったため、こちらで一般公開することにしました。

* [カバーの表2：xcolorパッケージで提供される色の見本（第7章）](covers/cover-hyo2.pdf)
* [カバーの表3：Beamerによるスライド作成（第18章）](covers/cover-hyo3.pdf)

## 訂正

* p.289 八登崇之さんの `bxghost` → 朝倉卓人さんの `bxghost`（八登さんのは `pxghost` で、これを拡張したものが朝倉さんの `bxghost` です。混乱してしまい、たいへん失礼しました）
* p.383 `\usepackage{mathcomp}` を使えば `\text...` を `tc...` → `\usepackage{mathcomp}` を使えば `\text...` を `\tc...`
