# How to load items / アイテムのロード方法
## Select laungage / 言語選択
- [#English](#English) (work in progress)
- [#日本語](#日本語)

## English
## How to load items
1. Upload the corresponding 3D model in GLB format to the web.
    - The app must be available to download and use from the website.
    - Example:Upload to Google Drive to get a shared link
    - If you want to try it out, please use this QR code image.  
    ![QR code image](pict/capybara.png)    
    - (Thanks to  Momoma's [low-poly capybara](https://booth.pm/ja/items/1145634).)
1. Start the V date application and call up the character.
1. View the prepared QR code on the camera. Be aware of the following:
    - Hold the QR code until the model is displayed.
    - It is recommended to put it on a desk. I don't recommend having one.
    - Reflect the QR code from various angles, not just one direction.
    - (The reason for these is to measure the physical size of the QR code during import.)
1. When the model is displayed, you can move the QR code to any position.
    - You can use it to guide your eyes, so please try it.

## 日本語
## アイテムのロード方法
- 動画での説明はこちらです。（手順1,2後の説明） [https://youtu.be/Fpb5nilpZlE](https://youtu.be/Fpb5nilpZlE)
1. 対応するGLB形式の3Dモデル（作り方は後述）をWebにアップロードします。
    - アプリがそのWebサイトからダウンロードして利用するため、アプリからアクセスが可能になっている必要があります。
    - 例：Google Drive にアップロードして共有リンクを取得する  
    （注：Google Driveサイトで取得できるリンクはビュアーページのURLなので、ファイル直接のリンクに修正する必要があります。[参考サイト](https://qiita.com/rot-z/items/299ac40361690c51ce1d)）
1. 1でアップロードしたファイルのURLをQRコードにします。
    - QRコードを作成する場合は装飾等を行わないようにしてください。
    - 推奨のQRコード作成サイト: [https://qr.quel.jp](https://qr.quel.jp)
    - とりあえず試したい方はこちらのQRコード画像を利用してください。   
    ![QRコード画像](pict/capybara.png)  
    （momoma氏作の[ローポリカピバラ](https://booth.pm/ja/items/1145634)を改変して使わせていただきました）
1. Vデートなうアプリを起動し、キャラクターを呼び出します。
1. 準備したQRコードをカメラに映します。この際以下の点の注意してください。
    - モデルが表示されるまでQRコードを静止させてください。
      - 机の上に置くなどを推奨します。手持ちは非推奨です。
    - １方向だけでなく色々な角度からQRコードを映してください。
    - （これらの理由は、読み込み時にQRコードの物理的な大きさを測定するためです）
1. モデルが表示されたらQRコードを好きな位置に移動させることでアイテムの場所を移動させることができます。  
視線の誘導にも使えるので試してみてください。

## アイテムの消去方法
- 出現させたアイテムを消す機能は現在未実装です。  
申し訳ないですが、アプリの再起動をお願いいたします。

## 読み込み対応3Dモデルの作成方法
- マテリアルとしてMTOONを使い、UniVRMのExportGLB機能を使ってエクスポートします。（詳細は後日追記します）
