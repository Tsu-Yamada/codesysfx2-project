# Node.js 環境をセットアップ

creation date：July 21th in 2024
update

## Node.jsをインストールする

Install Version：20.15.1・LTS
![alt text](image.png)

ここでは、ビルド済みインストーラーをダウンロードします。
`☁ Download Node.js v**.**.*` アイコンをクリック。（`v**.**.*` はNode.Jsのバージョン）

![alt text](image-1.png)

ダウンロードしたインストーラー(msiファイル)`node-v**.**.*-x64.msi` を起動します。

![alt text](image-2.png)

インストーラーが起動したら、`Next`をクリックします。

![alt text](image-3.png)

"Node.js is licensed for use as follows:"の内容を確認し、"I accept the terms in License Agreement"をチェック、`Next`をクリックします。

![alt text](image-4.png)

インストール先のディレクトリーを設定します。変更する必要がなければそのまま`Next`をクリックします。
（変更する場合は、ディレクトリーを直接記入するか、`Change...`をクリックしディレクトリーを指定します。）

![alt text](image-5.png)

インストール内容をカスタムします。
デフォルト設定の場合は、そのまま`Next`をクリックします。

![alt text](image-6.png)

チェックボックスにチェックを入れます。
※チェックを入れることで、Node.jsを利用するときに別途必要な様々なツールが、Node.jsインストール完了後に自動インストールされます。

![alt text](image-7.png)

`🛡Install` をクリックします。

![alt text](image-8.png)

ユーザーアカウント制御が表示されたら`はい`をクリックします。
インストールがはじまります。
![alt text](image-9.png)

インストールが完了すると以下の画面が表示されます。
`Finish`をクリックすると、コマンドプロンプトが表示されます。

![alt text](image-11.png)

適当にキーを押します。

![alt text](image-10.png)

キーを押します。

![alt text](image-12.png)

PowerShellを起動するユーザーアカウント制御が表示をされたら`はい`をクリックします。

![alt text](image-13.png)

## Node.jsのバージョン確認

コマンドプロンプトを起動します。  
`Node -v`を入力し、`⏎ Enter`を押します。

![alt text](image-14.png)

ヴァージョンが表示されます（画面の例では、v20.15.1）

