# 駅すぱあとWebサービス HTML5インターフェースサンプル

## 1.はじめに

 * **概要**

 「駅すぱあとWebサービス」を利用したGUIのサンプルコードです。

 自由に改変してご利用いただけますが、サンプルとしてのご提供のため、お問い合わせ等のサポートは承っておりません。ユーザーズガイドをご用意しておりますので、ご参照ください。

 なお、サンプルコードへのご意見・ご要望につきましては、[GitHubのIssue](https://github.com/EkispertWebService/GUI-LightEdition/issues/new)へ投稿いただけますと幸いです。今後のサンプルご提供にあたり参考とさせていただきます。

 * **お申込み**

 はじめてご利用いただく場合は[駅すぱあとワールド](https://ekiworld.net/)でのお申込み(無償)とキーの発行が必要になります。

 なお、お申し込みは下記のページから行ってください。

 [駅すぱあとWebサービス フリープラン](https://ekiworld.net/service/sier/webservice/free_provision.html)

 また、後日、認証キーをメールにてお送りいたします。

## 2.ご利用方法

 * **ソースコードのインクルード**

 ソースコードをダウンロードした後、任意のディレクトリにファイルを展開します。<br>
 なお、各パーツごとにディレクトリが分かれていますので、jsファイル、expCssディレクトリ、および、expImagesディレクトリをコピーして利用します。<br>

 ※expCss、および、expImagesディレクトリはディレクトリ名を変更せずにそのままコピーしてください。

 なお、表示するページごとにJavaScriptをインクルードする必要があります。<br>
 インクルードは下記使用例を参考に記述してください。<br>

 `<script type="text/javascript" src="コンポーネント名.js?key=keycode" charset="UTF-8"></script>`

 ※ keycode の部分には、弊社発行のキーコードを記述します。<br>
 ※ コンポーネントのご利用には認証キーが必要になります。認証キーはサービス契約時に弊社より送付されます。<br>

 また、下記のパーツをご利用の場合はCSSファイルのインクルードも必要になります。<br>
 ・日付入力パーツ<br>
 ・駅名入力パーツ<br>
 ・探索条件パーツ<br>

 `<link class="css" rel="stylesheet" type="text/css" href="expCss/コンポーネント名.css">`

## 3.IE8/IE9での制限

 * **制限事項**

 IE8/IE9は標準でJSONに対応していないため、そのままでは利用することが出来ません。<br>

 * **回避方法**

 IE8/IE9の場合は"json2.js"等を利用し、JSONへの拡張を行なってください。<br>
 なお、IE10/IE11やFIrefox、Chromeは標準で対応していますので、追加は不要です。<br>
