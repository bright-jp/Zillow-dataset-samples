# Zillow-dataset-samples

<h2>Zillowの物件リスティング1001件のサンプルデータセット</h2>

![Zillow dataset header](https://github.com/luminati-io/Zillow-dataset-samples/blob/main/zillow-datasets.PNG)

1000件を超える物件リスティングのZillowデータセットサンプルです。データセットは <b>Bright Data API</b> を使用して抽出されました。

<h2>この無料データセットに含まれるデータポイント:</h2>

* ```zpid```: Zillow上の物件リスティングの一意の識別子
* ```url```: 物件リスティングのURLまたはリンク
* ```city```: 物件が所在する市区町村
* ```state```: 物件が所在する州
* ```streetAddress```: 物件の住所（番地）
* ```zipcode```: 物件のZIPコード
* ```price```: 物件価格
* ```homeStatus```: 住宅のステータス（例: 販売中、成約済み）
* ```homeType```: 住宅タイプ
* ```longitude```: 物件の経度座標
* ```latitude```: 物件の緯度座標
* ```photoCount```: 物件リスティングに紐づく写真数
* ```currency```: 価格および見積もりが表示される通貨
* ```livingArea```: 物件の延床面積（居住面積）の合計
* ```lotSize```: 敷地面積
* ```propertyTaxRate```: 物件の固定資産税率
* ```rentZestimate```: Zillowによる当該物件の賃料推定値
* ```description```: 物件に関するテキスト説明または詳細
* ```tourViewCount```: 物件ツアーの閲覧数
* ```streetViewMetadataUrlMediaWallLatLong```: 緯度・経度を使用したストリートビューのメタデータURL
* ```isVerifiedClaimedByCurrentSignedInUser```: 現在サインインしているユーザーにより、クレームされたリスティングが検証済みかどうかを示します（True/False）
* ```isZillowOwned```: Zillowが当該物件を所有しているかどうかを示します（True/False）

ほかにも多数あります。

これは「Zillow Property Listings (public data)」データセットから派生したサンプルサブセットです。  
このデータセットには <b>134,060,000 companies</b> を超えるデータが含まれます。

利用可能なデータセットのファイル形式: <b>JSON, NDJSON, JSON Lines, CSV, or Parquet. Optionally, files can be compressed to .gz</b>.

データセットの配信タイプの選択肢: <b>Email, API download, Webhook, Amazon S3, Google Cloud storage, Google Cloud PubSub, Microsoft Azure, Snowflake, SFTP</b>.

更新頻度: <b>Once, Daily, Weekly, Monthly, Quarterly, or Custom basis</b>.

抽出したデータポイントに追加できるデータエンリッチメント: <b>Based on request.</b>

<b>[Zillowの完全なデータセットを入手する](https://brightdata.jp/products/datasets/zillow)</b>。


![Zillow dataset visual](https://github.com/luminati-io/Zillow-dataset-samples/blob/main/zillow-datasets-image.PNG)

<h2>Zillowデータセットのユースケースは何ですか？</h2>

<h3>1. 住宅需要分析</h3>

Zillowデータセットを活用して、住宅需要および販売トレンドを予測します。市場サイクルを特定し、最安値および高値の期間を分析することで、最適な機会を見極めます。

<h3>2. 不動産価格のトレンドと成長</h3>

Zillow上の物件価格を、ローカルな不動産データと比較・モニタリングします。所在地別の設備・特徴を分析し、住宅購入者の期待や市場環境に関するインサイトを得ます。

<h3>3. 投資インサイト</h3>

Zillowデータセットを使用して、最も賃貸利回りの高い物件を特定し、市場ダイナミクスを分析します。賃貸サイクル、空室率、その他の主要指標を明らかにし、情報に基づいた投資判断を行います。

<h2>学術研究者およびNGO向けのWebスクレイピングツールとデータセットへの無料アクセス</h2>

Bright Initiativeは、環境および社会的なさまざまな課題の推進に取り組む主要な大学学部・研究者、NGOおよびNPOに対して、Bright Dataの <b>[Web Scraper APIs](https://brightdata.jp/products/web-scraper)</b> と <b>[すぐに使えるデータセット](https://brightdata.jp/products/datasets)</b> へのアクセスを提供します。申請は <b>[こちら](https://brightinitiative.com)</b> から送信できます。