# Rowing Live Layout

Rowing Live Layout はローイングのレース配信上でレーンなどの情報を表示するツールです。OBS のブラウザ機能でhtml ファイルを画面上に表示します。json ファイルを編集することで表示内容を書き換えることができます。

## 使い方

### OBSへの配置

ソースからブラウザ（Webページ）を追加し、ローカルファイルにチェックを入れます。フォルダ内の`index.html`もしくは`draw.html`、を選択し、幅を1920px、高さを1080pxにして配置します。

<!-- <img src="https://wolphtype.com/img/materials/obs.png" style="width:800px;height:auto;"> -->

### データを編集する方法

フォルダ内にある`info.json`を編集することでデータの更新ができます。`""`は削除せず記入・保存してください。テキストエディタを持っていない場合は <a href="https://azure.microsoft.com/ja-jp/products/visual-studio-code/">VSCode</a>などをインストールすると良いでしょう。
