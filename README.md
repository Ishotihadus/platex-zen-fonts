# Zen Fontmaps for pLaTeX / upLaTeX

旧エイワンの Zen フォント（ZEN オールド明朝など）を使えるようにする pLaTeX / upLaTeX のなんやかんやです。

`fonts` の中身を、構造を保ったまま `/usr/local/texlive/texmf-local` にコピーしてください。

```bash
sudo cp -rv fonts /usr/local/texlive/texmf-local
```

`sudo mktexlsr` したのち、`sudo kanji-config-updmap-sys --mode=ja zen` を実行すると、デフォルトのフォントが Zen フォントになります。

## ライセンス

Zen フォントは [SIL Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL) 下で提供されています。
