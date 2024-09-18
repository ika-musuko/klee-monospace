Japanese programming font<br>
日本語のプログラミングフォント<br>
Download from [Releases](https://github.com/ika-musuko/klee-monospace/releases)
<br>
![screenshot of the font](screenshot.png)

## How to patch
1. Prerequisite: [`fonttools`](https://github.com/fonttools/fonttools)
2. Download [Klee One](https://fonts.google.com/specimen/Klee+One)
3. Download [LXGWWenKai](https://github.com/lxgw/LxgwWenKai)
4. Copy the following files in this directory:
    - KleeOne-Regular.ttf
    - KleeOne-SemiBold.ttf
    - LXGWWenKaiMono-Regular.ttf
    - LXGWWenKaiMono-Bold.ttf
5. `python klee-monospace.py KleeOne-Regular.ttf LXGWWenKaiMono-Regular.ttf; python klee-monospace.py KleeOne-SemiBold.ttf LXGWWenKaiMono-Bold.ttf`
6. Open `demo.html` for a demo

## Recommended [kitty](https://github.com/kovidgoyal/kitty) settings
```
font_family KleeOneMonospace
font_size 16

modify_font cell_width 100%
modify_font cell_height 80%
modify_font baseline 5
text_composition_strategy 3.0 10 # Adjust this based on your display
```

## パッチする方法
1. 前提として[`fonttools`](https://github.com/fonttools/fonttools)をインストールする
2. [Klee One](https://fonts.google.com/specimen/Klee+One)をダウンロードする
3. [LXGWWenKai](https://github.com/lxgw/LxgwWenKai)をダウンロードする
4. 以下のファイルをこのディレクトリにコピーする
    - KleeOne-Regular.ttf
    - KleeOne-SemiBold.ttf
    - LXGWWenKaiMono-Regular.ttf
    - LXGWWenKaiMono-Bold.ttf
5. `python klee-monospace.py KleeOne-Regular.ttf LXGWWenKaiMono-Regular.ttf; python klee-monospace.py KleeOne-SemiBold.ttf LXGWWenKaiMono-Bold.ttf`
6. `demo.html`を開いて確認する

## [kitty](https://github.com/kovidgoyal/kitty)のおすすめの設定
```
font_family KleeOneMonospace
font_size 16

modify_font cell_width 100%
modify_font cell_height 80%
modify_font baseline 5
text_composition_strategy 3.0 10 # こちらがディスプレイによって要調整
```
