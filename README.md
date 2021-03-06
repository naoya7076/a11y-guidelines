# freee Accessibility Guidelines

freee株式会社が作成しているアクセシビリティー・ガイドラインの一般公開版のリポジトリーです。現在作成中で、随時更新する予定です。

このガイドラインの作成の経緯などについて詳しくは、[ガイドラインのイントロダクション](https://a11y-guidelines.freee.co.jp/intro/index.html)と、[freee Developers Blogの記事](https://developers.freee.co.jp/entry/a11y-guidelines-202004.0)をご覧ください。

## 最新ファイルの入手

以下のURLで最新のファイルを入手していただけます:

* HTML版: <https://a11y-guidelines.freee.co.jp/>
* HTMLファイルをまとめたzipファイルおよびソースファイル: <https://github.com/freee/a11y-guidelines/releases/latest>

## この文書に関するお問い合わせなど

この文書に関するお問い合わせ、ご意見などは、このリポジトリーでissueを作成してお知らせください。

誤字脱字の修正など、エディトリアルな修正の提案については、issueまたはpull requestを作成してください。

## ソースについて

この文書はreStructuredTextで記述し、Sphinxで処理しています。
HTMLファイルの生成には、Python 3.x (開発環境では3.7.xを使っています)、[Sphinx](https://www.sphinx-doc.org/en/master/)と[Read the Docs Sphinx Theme (sphinx_rtd_theme)](https://github.com/readthedocs/sphinx_rtd_theme)が必要です。

このリポジトリーをcloneしたうえで、Pythonが利用できる環境で、以下のように実行するとHTMLを生成することができます:

`````
% pip install --upgrade pip
% pip install -r requirements.txt
% make html
`````

## ライセンス

![クリエイティブ・コモンズ・ライセンス](https://i.creativecommons.org/l/by/4.0/88x31.png)
「freeeアクセシビリティー・ガイドライン」は、freee株式会社が作成したもので、[クリエイティブ・コモンズ 表示 4.0 国際 ライセンス](http://creativecommons.org/licenses/by/4.0/)で提供されています。

Copyright © 2020, freee株式会社

## 更新履歴

### [Ver. 202005.0](https://github.com/freee/a11y-guidelines/releases/202005.0/) (2020年5月21日、Global Accessibility Awareness Day)

* 一部文言を修正
* 色に関するガイドラインについて、色弱者に加えて視覚障害者のアクセスに影響することを「意図」に明記
* 参考情報の追加:
    - [自動的に変化するコンテンツの問題点](https://a11y-guidelines.freee.co.jp/explanations/dynamic_content-auto-updated.html)
    - [フォーム・コントロールのラベル付けの必要性](https://a11y-guidelines.freee.co.jp/explanations/form-labeling.html)
    - [色を用いた表現に関する注意点](https://a11y-guidelines.freee.co.jp/explanations/color-only.html)
    - [フォーム操作で発生する動的な変化が及ぼす影響](https://a11y-guidelines.freee.co.jp/explanations/form-dynamic-content.html)
    - [入力エラーの扱い](https://a11y-guidelines.freee.co.jp/explanations/form-errors.html)
    - [小さすぎるクリックやタッチのターゲット・サイズの問題点](https://a11y-guidelines.freee.co.jp/explanations/target-size.html#exp-target-size)
    - [画像化されたテキストの問題点](https://a11y-guidelines.freee.co.jp/explanations/images_of_text-usage.html)
    - [画像化されたテキストを使用する場合の代替情報の提供](https://a11y-guidelines.freee.co.jp/explanations/images_of_text-text-alternative.html)
    - [コントラスト比確保の重要性](https://a11y-guidelines.freee.co.jp/explanations/contrast.html)
    - [ユーザーCSSを適用したチェックの実施方法](https://a11y-guidelines.freee.co.jp/explanations/text-custom-css.html)
    - [キーボード・トラップが引き起こす問題](https://a11y-guidelines.freee.co.jp/explanations/keyboard-notrap.html)
    - [様々なユーザーの入力手段の特徴とそのサポート](https://a11y-guidelines.freee.co.jp/explanations/input_device-various.html)
    - [音声・映像コンテンツの存在を認知可能にする](https://a11y-guidelines.freee.co.jp/explanations/multimedia-perceivable.html)
    - [音声の自動再生とアクセシビリティー](https://a11y-guidelines.freee.co.jp/explanations/multimedia-autoplay.html)
    - [音声・映像コンテンツのアクセシビリティーを確保する](https://a11y-guidelines.freee.co.jp/explanations/multimedia-content-access.html)
    - [Tab/Shift+Tabキーを用いたチェック](https://a11y-guidelines.freee.co.jp/explanations/tab-order-check.html)
* 参考情報の更新:
    - [Reactコンポーネントなどのアクセシビリティー](https://a11y-guidelines.freee.co.jp/explanations/markup-component.html): AccessibleNameとroleについて加筆
* 誤字修正 ([#3](https://github.com/freee/a11y-guidelines/pull/3), [#5](https://github.com/freee/a11y-guidelines/pull/5), [#6](https://github.com/freee/a11y-guidelines/pull/6), 他)
* CSSなど修正

### [Ver. 202004.0](https://github.com/freee/a11y-guidelines/releases/202004.0/) (2020年4月30日)

* 初版公開
