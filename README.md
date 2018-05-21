# optimize-pdf
Command-line script to re-render, optimize and fix PDF document using ghostscript

## 機能
* PDF をリニアライズ (最適化)
* 非埋込フォントを埋め込み
* 画像の JPEG 圧縮の有効・無効化
* 画像のリサンプル処理の有効・無効化
* フォントのアウトライン化

## コマンドライン

    optimize-pdf input_file [options] [input_files ...]
        -h, --help            show this help message and exit
        --gs-prog GS_PROG     ghostscriptのパスを指定する
        --enable-jpeg         画像のJPEG圧縮を行う
        --preserve-bookmark   PDF文書のブックマークを保持する
        --no-downsample       画像のリサンプル処理を無効にする
        --pdfx3               PDFx3形式に保存する
        --outline-fonts       フォントのアウトライン化を行う
        -o OUTPUT, --output OUTPUT 出力PDFファイル名を指定する
        --gs-option GS_OPTION   ghostscript に追加のオプションを追加する


