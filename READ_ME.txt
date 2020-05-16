
*********************************************************************
AI kaga v1.4   by HiTouch
************************************************************************
①AI艦船DDH-184ヘリコプター搭載護衛艦『かが』にて発着シナリオを実行することができます。
※Carrier Controlにてエレベータを上下することが出来ます。

②MPCarrierへ『kaga』を追加し、マルチプレイ上での操舵が可能になります。
※事前にFlightGearの機体データ『MP Carrier』をインストールが必要です。

***********************************************************************

（インストールについて）

解凍したフォルダ内のファイルを下記指示に従い展開してください。

【手順１】
AI-kaga/AIフォルダ内の
　kaga_demo.xml

⇒　FlightGear *.*.*/data/AIの直下へ移動

【手順２】
AI-kaga/Aircraft/MPCarrierフォルダ内の
   kaga-set.xml

⇒　FlightGear *.*.*/data/Aircraft/MPCarrierの直下へ移動

【手順３】
AI-kaga/Aircraft/MPCarrier/Modelsフォルダ内の
   Splashフォルダ及び mp-kaga.xml

⇒　FlightGear *.*.*/data/Aircraft/MPCarrier/Modelsの直下へ移動

【手順４】
AI-kaga/Aircraft/MPCarrier/Systemsフォルダ内の
   kaga-views.xml
   kaga-walk-views.nas
   MPCarriers.nas
⇒　FlightGear *.*.*/data/Aircraft/MPCarrier/Systemsの直下へ移動
   ※MPCarriers.nasは上書きになります。別名で元ファイルを保管しておくことを薦めます。

【手順５】
AI-kaga/gui/dialogsフォルダ内の"kaga.xml"を

⇒　FlightGear *.*.*/data/gui/dialogsの直下へ移動

【手順６】
AI-kaga/Models/Geometryフォルダ内の"kaga"フォルダを

⇒　FlightGear *.*.*/data/Models/Geometryの直下へ移動

【手順７】
AI-kaga/Navaildsフォルダ内の
carrier_nav.dat.gz
⇒　FlightGear *.*.*/data/Navaildsの直下へ移動
   ※carrier_nav.dat.gzは上書きになります。別名で元ファイルを保管しておくことを薦めます。

********************************************************************

【AIシナリオ"kaga_demo"について】
このシナリオは関西空港から南下するルートで航行する『かが』に発着するシナリオです。
メニューのAI/AI Objectsからkagaを選択すれば航行ルートの変更やエレベータを上下できます。
艦内は格納庫になっています。デッキライトも点灯できます。

速度10ktで航行。TACANチャンネルは"032Y"です。

艦上からのスタート方法はJPサイト等を参照ください。

Additional optionsの入力
--ai-scenario=kaga_demo
--carrier=kaga
--parkpos=P1 (or P2 or P3 or P4 or P5 or ELV1 or ELV2)

【マルチプレイによる運用】
ランチャーの機体選択でMPCarrierよりkagaを選択し、シナリオ『kaga-demo』を選択し実行してください。
[CTRL+a]でマニュアル操作が可能になります。

【マルチプレイでkagaに着艦】
メニュー/Multiplayer/MPCarrier Selectionでkagaを選択してください。








