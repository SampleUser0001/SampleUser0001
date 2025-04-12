
# Home

- [Home](#home)
  - [TipsList](#tipslist)
  - [Tools](#tools)
    - [形態素解析](#形態素解析)
    - [Google API](#google-api)
      - [Youtube](#youtube)
    - [AWS](#aws)
      - [AWS Lambda](#aws-lambda)
  - [Template](#template)
  - [Java](#java)
    - [MultiThread](#multithread)
    - [JUnit](#junit)
    - [SpringBoot](#springboot)
    - [SpringBatch](#springbatch)
  - [JavaScript](#javascript)
    - [Node.js](#nodejs)
    - [TypeScript](#typescript)
    - [Vue.js](#vuejs)
    - [jQuery](#jquery)
    - [React.js](#reactjs)
  - [HTML/CSS/JavaScript](#htmlcssjavascript)
    - [Jekyll](#jekyll)
  - [PHP](#php)
    - [Laravel](#laravel)
      - [参考](#参考)
    - [Slim](#slim)
  - [Python](#python)
    - [Django](#django)
  - [Golang](#golang)
    - [リポジトリ](#リポジトリ)
  - [Ruby](#ruby)
  - [C#](#c)
  - [AR](#ar)
  - [GoogleAnalytics](#googleanalytics)
    - [その他](#その他)
  - [DB](#db)
    - [MySQL](#mysql)
  - [Others](#others)
    - [Selenium](#selenium)
  - [Transfer](#transfer)
  - [S3](#s3)
  - [Repositories](#repositories)
  - [非公開一覧へのリンク](#非公開一覧へのリンク)

## TipsList

- [TipsList](https://sampleuser0001.github.io/cloud9_note/)

## Tools

| ツール名/リンク | 概要 | 使用言語 |
| :---- | :--- | :-- |
| [Replace](https://github.com/SampleUser0001/ReplaceByJava) | 一括置換 | Java |
| [SrcToMarkdown](https://github.com/SampleUser0001/SrcToMarkdown) | ソースディレクトリ配下のファイルをMarkdown形式に変換する | Node.js |
| [DiffProperties_forMaven](https://github.com/SampleUser0001/DiffProperties_forMaven) | Javaのpropertiesの差分取得 | Java |
| [Sorter_forMaven](https://github.com/SampleUser0001/Sorter_forMaven) | tsvファイルのソートを行う。 | Java |
| [ConvertSpaceIndexToComma](https://github.com/SampleUser0001/ConvertSpaceIndexToComma) | (Linuxでよく見かける)半角スペースインデントをカンマ区切りに変換する | Python |
| [Diff_TSV](https://github.com/SampleUser0001/Diff_TSV) | tsvファイルのdiffを取得する。 | Java |
| [composer.lock to TSV](https://github.com/SampleUser0001/composer_lock_toTSV) | composer.lockをtsvに変換する。 | Python |
| [Use_md-to-pdf](https://github.com/SampleUser0001/Use_md-to-pdf) | md-to-pdfを使用して Markdown -> PDF変換する。 | Node.js |
| [Database_Table_info_to_Json_Common](https://github.com/SampleUser0001/Database_Table_info_to_Json_Common) | DB情報をjson出力するライブラリ。 | Java | 
| [Windows_copies_bat](https://github.com/SampleUser0001/Windows_copies_bat) | 一覧ファイルを引数にファイルコピーを行うバッチ。 | bat |
| [SQL_Executor_Java](https://github.com/SampleUser0001/SQL_Executor_Java) | SQLを実行して結果をファイル出力する。 | Java |
| [GetExtension](https://github.com/SampleUser0001/GetExtension) | 拡張子一覧を取得する。 | Java |
| [Merge_and_Diff](https://github.com/SampleUser0001/Merge_and_Diff) | ファイルをマージする。マージしたときに項目の有無を確認する。(Diff_TSVでできたような気がするが・・・) | Java |
| [Export_Excel_Width_Poi](https://github.com/SampleUser0001/Export_Excel_Width_Poi) | Apache POIで列幅を取得する。 | Java |
| [Create_Daily_Task_OpenProject](https://github.com/SampleUser0001/Create_Daily_Task_OpenProject) | OpenProjectに日次タスクを作成する | Python |
| [diff_select](https://github.com/SampleUser0001/diff_select) | Selectの実行結果の差分を出力する(Oracle) | bash |
| [Generate_combination_tsv](https://github.com/SampleUser0001/Generate_combination_tsv) | 組み合わせ表を生成する | Python |
| [markdown-it_like_jekyll](https://github.com/SampleUser0001/markdown-it_like_jekyll) | markdown-itを使ってJekyllっぽいことをする | Node.js |

### 形態素解析

| ツール名 | 概要 | 使用言語 |
| :------ | :-- | :--- |
| [Get_NG_Pattern](https://github.com/SampleUser0001/Get_NG_Pattern) | [GetYoutubeArchiveComment](https://github.com/SampleUser0001/GetYoutubeArchiveComment)で取得したコメントを形態素解析し、NG対象とするコメントを出力する。 | Python |
| [Research_Mplg_similarity](https://github.com/SampleUser0001/Research_Mplg_similarity) | 形態素解析した場合としなかった場合の、文章の類似度の比較を行う。 | Python |

### Google API

#### Youtube

Botで自動生成されるメッセージを自動でBANするためのツール案。  
NGにしたユーザやコメントをDBに登録して共有化したら、複数ユーザに対応することも考えられる。

1. [GetYoutubeLiveComment](https://github.com/SampleUser0001/GetYoutubeLiveComment)でコメント取得
2. [Use_MeCab_for_LiveComment](https://github.com/SampleUser0001/Use_MeCab_for_LiveComment)でコメント解析＋NGパターンのコメントを生成
3. [GetYoutubeLiveComment](https://github.com/SampleUser0001/GetYoutubeLiveComment)でコメントを取得しながら、2で取得したNGコメントと類似度を見ながらNG判定
4. [YoutubeAPI_liveChatBans](https://github.com/SampleUser0001/YoutubeAPI_liveChatBans)でBAN

等。

| ツール名/リンク | 概要 | 使用言語 |
| :---- | :--- | :-- |
| [GetYoutubeLiveComment](https://github.com/SampleUser0001/GetYoutubeLiveComment)  | YoutubeのLiveのコメントを取得する。 | Python |
| [GetYoutubeArchiveComment](https://github.com/SampleUser0001/GetYoutubeArchiveComment) | YoutubeのArchiveのコメントを取得する。(Youtubeの規約に抵触するため非公開。アーカイブのコメントを取得するAPIの実装を希望。 -> Youtube) | Python |
| [Use_MeCab_for_LiveComment](https://github.com/SampleUser0001/Use_MeCab_for_LiveComment) | [Get_NG_Pattern](https://github.com/SampleUser0001/Get_NG_Pattern)で生成した形態素解析結果から[GetYoutubeLiveComment](https://github.com/SampleUser0001/GetYoutubeLiveComment)の出力結果コメントにNG判定を付与する。 | Python |
| [Use_MeCab_for_ArchiveComment](https://github.com/SampleUser0001/Use_MeCab_for_ArchiveComment) | [Get_NG_Pattern](https://github.com/SampleUser0001/Get_NG_Pattern)で生成した形態素解析結果から[GetYoutubeArchiveComment](https://github.com/SampleUser0001/GetYoutubeArchiveComment)の出力結果コメントにNG判定を付与する。 | Python |
| [GoogleAPI_OAuth_init_setting](https://github.com/SampleUser0001/GoogleAPI_OAuth_init_setting) | GoogleAPIのOAuth2.0ファイルを有効化する。 | Python | 
| [YoutubeAPI_OAuth](https://github.com/SampleUser0001/YoutubeAPI_OAuth) | 実行サンプル。指定した動画にlikeする。 | Python |
| [YoutubeAPI_liveChatBans](https://github.com/SampleUser0001/YoutubeAPI_liveChatBans) | liveChatBansを実行してみる。 | Python |
| [Get_Youtube_channel_subscriber_count](https://github.com/SampleUser0001/Get_Youtube_channel_subscriber_count) | チャンネル登録者数を取得する。（概数しか出ない） | Python |

### AWS

| ツール名/リンク | 概要 | 使用言語 |
| :---- | :--- | :-- |
| [AWS_Pipeline_CodeBuild](https://github.com/SampleUser0001/AWS_Pipeline_CodeBuild) | AWS PipelineとAWS CodeBuildを紐付ける。適当に修正して使う。 | Python |

#### AWS Lambda

| ツール名/リンク | 概要 | 使用言語 |
| :---- | :--- | :-- |
| [Get_Mergeable_Lambda](https://github.com/SampleUser0001/Get_Mergeable_Lambda) | 起動引数のリポジトリのブランチがマージ可能かを取得する。 | Python |
| [MergeEventDetection](https://github.com/SampleUser0001/MergeEventDetection) | [Get_Mergeable_Lambda](https://github.com/SampleUser0001/Get_Mergeable_Lambda)を呼ぶ。起動引数の制御をする。 | Python |
| [Use_serverless_Python](https://github.com/SampleUser0001/Use_serverless_Python) | serverlessを使ってみる | Python |
| [AWS_EventBridge_Lambda_Tutorial](https://github.com/SampleUser0001/AWS_EventBridge_Lambda_Tutorial) | EventBridgeからLambdaを呼び出す。[eventに任意の値を設定できるようにする。](https://sampleuser0001.github.io/cloud9_note/AWS/AWS_Lambda.html#%E4%BB%BB%E6%84%8F%E3%81%AE%E5%80%A4%E3%82%92%E8%A8%AD%E5%AE%9A%E3%81%99%E3%82%8B)

## Template

- [TemplateMaven](https://github.com/SampleUser0001/TemplateMaven)
- [TemplateNode](https://github.com/SampleUser0001/TemplateNode)
- [Template Python on Docker](https://github.com/SampleUser0001/Template_Python_on_Docker)
- [Template_Selenium_Python_on_Docker](https://github.com/SampleUser0001/Template_Selenium_Python_on_Docker)
- [Template_PHP_MySQL_Nginx](https://github.com/SampleUser0001/Template_PHP_MySQL_Nginx)
- [Minecraft Server on Docker](https://github.com/SampleUser0001/MinecraftServer_onDocker)
- [NginxContainerTemplate](https://github.com/SampleUser0001/NginxContainerTemplate)
- [Template_MeCab](https://github.com/SampleUser0001/Template_MeCab)
- [TypeScript_MySQL_onDocker](https://github.com/SampleUser0001/TypeScript_MySQL_onDocker)
- [Node_Script_Template](https://github.com/SampleUser0001/Node_Script_Template)
- [Template_React.js](https://github.com/SampleUser0001/Template_React)

## Java

| リポジトリ | 概要 |
| :-- | :-- |
| [JavaSamples](https://github.com/SampleUser0001/JavaSamples) | Javaのサンプル集 |
| [Sample_ReadXML_byJava](https://github.com/SampleUser0001/Sample_ReadXML_byJava) | JavaでXMLを読み込む |
| [Use_zipcloud_json](https://github.com/SampleUser0001/Use_zipcloud_json) | APIを叩いてJSONを読み込む。 |
| [GetPowerMock](https://github.com/SampleUser0001/GetPowerMock) | PowerMockの使用方法のサンプル |
| [GetSimilarity_Java](https://github.com/SampleUser0001/GetSimilarity_Java) | 文字列の類似度を取得する。 |
| [Research_garbled_text_Java](https://github.com/SampleUser0001/Research_garbled_text_Java) | 文字化け調査用。文字コードを指定して、16進 <-> 文字列変換を行う。 |
| [Filepath_Java](https://github.com/SampleUser0001/Filepath_Java) | JavaのPathインスタンスの扱いについて調査 |
| [Binary_or_Text_Java](https://github.com/SampleUser0001/Binary_or_Text_Java) | バイナリかテキストかの判定を行う |
| [Regular_Expression_Java](https://github.com/SampleUser0001/Regular_Expression_Java) | 正規表現を扱う |
| [Database_Table_info_to_Json_Common](https://github.com/SampleUser0001/Database_Table_info_to_Json_Common) | DB情報をjson出力するライブラリ。 |
| [Poi_Sample_Java](https://github.com/SampleUser0001/Poi_Sample_Java) | Poiで遊ぶ | 
| [PoiStyleSample](https://github.com/SampleUser0001/PoiStyleSample) | PoiでExcel書式を扱う。 |
| [Poi_WriteReadAppend](https://github.com/SampleUser0001/Poi_WriteReadAppend) | Poiでファイルの書き込み/読み込みを行う。 |
| [To_Webhook_message_Java](https://github.com/SampleUser0001/To_Webhook_message_Java) | WebhookにPOSTする |
| [Generics_Enum_Java](https://github.com/SampleUser0001/Generics_Enum_Java) | Enumで型を振り分ける。（ジェネリクスは使わなかった。） | 
| [Amazon_SQS_API_Reference_Sample](https://github.com/SampleUser0001/Amazon_SQS_API_Reference_Sample) | Amazon SQSのQueue作成、メッセージ送信、メッセージ受信、メッセージ削除を実装する。（[Amazon SQS メッセージキューの使用](https://docs.aws.amazon.com/ja_jp/sdk-for-java/v1/developer-guide/examples-sqs-message-queues.html)） |
| [Tree_Java](https://github.com/SampleUser0001/Tree_Java) | 木構造を実装する。 |
| [Convert_by_enum_Java](https://github.com/SampleUser0001/Convert_by_enum_Java) | 型変換をenmu経由で行う実装のサンプル（当初ジェネリクスを使おうとして頓挫した実装パターン。） |
| [Use_Optional_Java:SampleUser0001:Github](https://github.com/SampleUser0001/Use_Optional_Java) | Optionalクラスを使ってnullチェックを行う。 |
| [Practice_JGit_AzureDevOps](https://github.com/SampleUser0001/Practice_JGit_AzureDevOps) | JGitを使ってみる。 |
| [Get_Azure_DevOps_PullRequest_Java](https://github.com/SampleUser0001/Get_Azure_DevOps_PullRequest_Java) | Azure DevOps APIを実行して、プルリクエストタイトルを取得する。 |
| [Sqlite_Java](https://github.com/SampleUser0001/Sqlite_Java) | Javaでsqliteに接続する。 |

### MultiThread

| リポジトリ | 概要 |
| :-- | :-- |
| [MultiThreadSample](https://github.com/SampleUser0001/MultiThreadSample.git) | ExecutorServiceを使用したマルチスレッドの実装のサンプル集 |
| [UseConcurrentHashMap_byJava](https://github.com/SampleUser0001/UseConcurrentHashMap_byJava) | マルチスレッドでMap.put, ConcurrentHashMap.put, ConcurrentHashMap.putIfAbsentでmapに登録した場合の動作確認プロジェクト。 |
| [UseConcurrentHashMap_byJava_02](https://github.com/SampleUser0001/UseConcurrentHashMap_byJava_02) | Mapに対してputしながらgetした場合の挙動。HashMapとConcurrentHashMapの違い |

### JUnit

JUnit自体ではなく、サンプルで使えそうなプロジェクトたち。

| リポジトリ | 概要 |
| :-- | :-- |
| [Practice_Quick_Sort](https://github.com/SampleUser0001/Practice_Quick_Sort) | クイックソートのサンプル。マルチスレッドで実装して高速化しようとしたが、インスタンス生成コストのほうが高かった。|
| [GetPowerMock](https://github.com/SampleUser0001/GetPowerMock) | PowerMockの使用方法のサンプル |
| [Database_Table_info_to_Json_Common](https://github.com/SampleUser0001/Database_Table_info_to_Json_Common) | DB情報をjson出力するライブラリ。 |

### SpringBoot

[https://spring.pleiades.io/spring-boot/docs/current/reference/html/](https://spring.pleiades.io/spring-boot/docs/current/reference/html/)

| リポジトリ | 概要 | ドキュメントURL | 
| :-- | :-- | :-- |
| [SpringBoot_FirstApplication](https://github.com/SampleUser0001/SpringBoot_FirstApplication) | 初めての Spring Boot アプリケーションの開発:SpringBoot入門 | [https://spring.pleiades.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.first-application](https://spring.pleiades.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.first-application) |
| [SpringBoot_FileDownload](https://github.com/SampleUser0001/SpringBoot_FileDownload) | ファイルダウンロードの実装 | - |
| [SpringBoot_FileUpload](https://github.com/SampleUser0001/SpringBoot_FileUpload) | ファイルアップロードの実装 | [ファイルのアップロード:SpringBoot](https://spring.pleiades.io/guides/gs/uploading-files/) |
| [SpringBoot_OAuth2](https://github.com/SampleUser0001/SpringBoot_OAuth2) | OAuth2実装 | [チュートリアル  Spring Boot と OAuth2 - 公式サンプルコード](https://spring.pleiades.io/guides/tutorials/spring-boot-oauth2/) |
| [SpringBoot_REST_API](https://github.com/SampleUser0001/SpringBoot_REST_API) | REST API実装 | [REST API の作成](https://spring.pleiades.io/guides/gs/rest-service/) |
| [SpringBoot_JPA_sqlite](https://github.com/SampleUser0001/SpringBoot_JPA_sqlite) | SpringBootのJPAでsqliteに接続する。 | [JPA でインメモリ H2 データアクセス](https://spring.pleiades.io/guides/gs/accessing-data-jpa/) |
| [SpringBoot_sqlite](https://github.com/SampleUser0001/SpringBoot_sqlite) | SpringBootでsqliteに接続する。JPAは使用しない。（SpringBoot 3系にVerUpを試みたら、hibernateのバージョン整合性が解消できなかった。） | - |
| [SpringBoot_WebApp_Post](https://github.com/SampleUser0001/SpringBoot_WebApp_Post) | ブラウザからPOSTする。 | [Web 画面フォーム送信処理](https://spring.pleiades.io/guides/gs/handling-form-submission/) |
| [SpringBoot_Thymeleaf](https://github.com/SampleUser0001/SpringBoot_Thymeleaf) | SpringBoot + ThymeleafでWebページを生成する。 | [Thymeleaf Web 画面の作成](https://spring.pleiades.io/guides/gs/serving-web-content/) |
| [SpringBoot_RestTemplate](https://github.com/SampleUser0001/SpringBoot_RestTemplate) | RestTemplateでAPIを呼び出す。 | [RestTemplate で REST API の利用](https://spring.pleiades.io/guides/gs/consuming-rest/) |
| [Web_Application_SpringBoot_sqlite](https://github.com/SampleUser0001/Web_Application_SpringBoot_sqlite) | SpringBoot + Thymeleaf + sqlite + Bootstrap | - |
| [SpringBoot_WebSocket](https://github.com/SampleUser0001/SpringBoot_WebSocket) | リアルタイムWebアプリ(WebSockert) | [WebSocket でインタラクティブ Web アプリケーション作成](https://spring.pleiades.io/guides/gs/messaging-stomp-websocket/) |
| [SpringBoot_Properties](https://github.com/SampleUser0001/SpringBoot_Properties) | propertiesファイルを読み込む | [【Spring Boot】プロパティファイル:b1san's Blog](https://b1san-blog.com/post/spring/spring-properties/) |
| [SpringBoot_CustomSchedule](https://github.com/SampleUser0001/SpringBoot_CustomSchedule) | Scheduleを制御する | - |
| [SpringBoot_and_React.js](https://github.com/SampleUser0001/SpringBoot_and_React) | SpringBoot + React.js | [React.js と Spring Data REST](https://spring.pleiades.io/guides/tutorials/react-and-spring-data-rest/) |
| [SpringBoot_and_React_2](https://github.com/SampleUser0001/SpringBoot_and_React_2) | SpringBoot + React.jsののBackend側。[SpringBoot_and_React_2_Front](https://github.com/SampleUser0001/SpringBoot_and_React_2_Front)がFrontend。 | [【React.js】SpringBootで作成したAPIを呼び出す方法](https://qiita.com/curry__30/items/c91d489551de68adb759) |

### SpringBatch

| リポジトリ | 概要 | ドキュメントURL |
| :-- | :-- | :-- |
| [SpringBoot_Batch](https://github.com/SampleUser0001/SpringBoot_Batch) | SpringBatchのサンプル | [まずは実践、Spring Boot Batchの動かし方:Qiita](https://qiita.com/kawakawaryuryu/items/4b3f5cc7574b7bd6b625) |
| [SpringBatch_2](https://github.com/SampleUser0001/SpringBatch_2) | SpringBatchのお勉強 | [Spring解体新書(バッチ編):Amazon](https://www.amazon.co.jp/dp/B09D3ZTJTB/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1) |

## JavaScript

### Node.js

| リポジトリ | 概要 |
| :-- | :-- |
| [Practice_Hands_on_Node.js](https://github.com/SampleUser0001/Practice_Hands_on_Node.js) | ハンズオンNode.jsの勉強 |
| [NodeBeginnerBook](https://github.com/SampleUser0001/NodeBeginnerBook) | Nodeビギナーズガイド |
| [Practice_Nodejs](https://github.com/SampleUser0001/Practice_Nodejs) | Node.jsの勉強用 |
| [NodeEJSSample](https://github.com/SampleUser0001/NodeEJSSample) | EJS |
| [NodeFileDownloadSample](https://github.com/SampleUser0001/NodeFileDownloadSample) | ファイルダウンロード |
| [SelfMadeHttpHeader](https://github.com/SampleUser0001/SelfMadeHttpHeader) | 手動でHTTPヘッダを設定する。(HTTPインジェクションの調査) |
| [ReadJson_Node](https://github.com/SampleUser0001/ReadJson_Node) | jsonファイルを読み込む。|
| [import_static_express_Node](https://github.com/SampleUser0001/import_static_express_Node) | expressでstaticファイルを読み込む |
| [ReadFile_JavaScript](https://github.com/SampleUser0001/ReadFile_JavaScript) | ファイルを読み込む。(txt, csv, json) |
| [Practice_Express_Nodejs](https://github.com/SampleUser0001/Practice_Express_Nodejs) | ExpressのGetting startedを試す |

### TypeScript

| リポジトリ | 概要 |
| :-- | :-- |
| [Practice_Programing_TypeScript](https://github.com/SampleUser0001/Practice_Programing_TypeScript) | オライリー プログラミングTypeScriptの勉強用 |
| [Study_TypeScript](https://github.com/SampleUser0001/Study_TypeScript) | TypeScriptの勉強用 |
| [TypeScript_express_decorator](https://github.com/SampleUser0001/TypeScript_express_decorator) | TypeScript + expressでデコレータ(Javaで言うアノテーション)を使う。 |
| [TypeScript_MySQL_onDocker](https://github.com/SampleUser0001/TypeScript_MySQL_onDocker) | TypeScript + MySQL環境をDockerで構築する。 |
| [Use_import_TypeScript](https://github.com/SampleUser0001/Use_import_TypeScript) | export/import文の使い方 |
| [Use_Sequelize_TypeScript](https://github.com/SampleUser0001/Use_Sequelize_TypeScript) | Sequelize(DB関連のライブラリ) |
| [TypeScriptDoc_Sample](https://github.com/SampleUser0001/TypeScriptDoc_Sample) | TypeScriptDocを使ってみる |

### Vue.js

| リポジトリ | 概要 |
| :-- | :-- |
| [Vue_Practice](https://github.com/SampleUser0001/Vue_Practice) | Vue.jsの勉強をする。 |
| [vue_cli_test](https://github.com/SampleUser0001/vue_cli_test) | Vue CLIでVue.jsを動かす |

### jQuery

| リポジトリ | 概要 |
| :--------- | :--- |
| [Practice_jQuery_Desktop_Reference](https://github.com/SampleUser0001/Practice_jQuery_Desktop_Reference) | [jQueryデスクトップリファレンス:O'Reilly Japan](https://www.oreilly.co.jp/books/9784873115245/) の勉強用|
| [Oreilly_jQuery_Cookbook](https://github.com/SampleUser0001/Oreilly_jQuery_Cookbook) | [jQueryクックブック:O'Reilly Japan](https://www.oreilly.co.jp/books/9784873114682/)の勉強用 |

### React.js

| リポジトリ | 概要 | 参考 |
| :--------- | :--- | :-- |
| [React_Hands_on_Learning_Practice](https://github.com/SampleUser0001/React_Hands_on_Learning_Practice) | [Reactハンズオンラーニング 第2版:O'Reilly Japan](https://www.oreilly.co.jp/books/9784873119380/)の勉強用 | - |
| [List_React](https://github.com/SampleUser0001/List_React) | Checkbox + Listを作成する。 | - |
| [SpringBoot_and_React_2_Front](https://github.com/SampleUser0001/SpringBoot_and_React_2_Front) | SpringBoot + React.jsののFrontend側。[SpringBoot_and_React_2](https://github.com/SampleUser0001/SpringBoot_and_React_2)がBackend。| [【React.js】SpringBootで作成したAPIを呼び出す方法](https://qiita.com/curry__30/items/c91d489551de68adb759) |

## HTML/CSS/JavaScript

| リポジトリ | 概要 |
| :-- | :-- |
| [HTML5_CSS_JavaScript_Programing](https://github.com/SampleUser0001/HTML5_CSS_JavaScript_Programing) | ゲームを作りながら楽しく学べるHTML5+CSS+JavaScriptプログラミング［改訂版］の練習用 |
| [OnloadJavaScript](https://github.com/SampleUser0001/OnloadJavaScript) | 画面遷移時にJavaScriptを実行する。 |
| [Practice_Hands_on_JavaScript](https://github.com/SampleUser0001/Practice_Hands_on_JavaScript) | ハンズオンJavaScriptの勉強 |
| [CircleGraph_CSS](https://github.com/SampleUser0001/CircleGraph_CSS) | 円グラフを書く | 
| [Call_SpringBoot_REST_API](https://github.com/SampleUser0001/Call_SpringBoot_REST_API) | [SpringBoot_REST_API](https://github.com/SampleUser0001/SpringBoot_REST_API)を呼ぶ。 |
| [Bootstrap_practices](https://github.com/SampleUser0001/Bootstrap_practices) | Bootstrapの練習用。 |
| [Bootstrap_practices(Github Pages)](https://sampleuser0001.github.io/Bootstrap_practices/index.html) | Bootstrapの練習用。(Github Pages) |

### Jekyll

- [Jekyll_Tutorial](https://github.com/SampleUser0001/Jekyll_Tutorial)

## PHP

| リポジトリ | 概要 |
| :-- | :-- |
| [PHP_Tutorial](https://github.com/SampleUser0001/PHP_Tutorial) | [これ](https://www.php.net/manual/ja/tutorial.php)をやってみる |
| [Practice_Learning_PHP](https://github.com/SampleUser0001/Practice_Learning_PHP) | オライリー 初めてのPHP勉強 |
| [CreateCookie_byPHP](https://github.com/SampleUser0001/CreateCookie_byPHP) | PHPでのCookieの扱い（setcookie） |
| [SelfMadeHttpHeader_PHP](https://github.com/SampleUser0001/SelfMadeHttpHeader_PHP.git) | GetパラメータにJavaScriptを埋め込む |
| [XSS_Nginx](https://github.com/SampleUser0001/XSS_Nginx) | クロスサイトスクリプティング対応の調査 |

### Laravel

| リポジトリ | 概要 |
| :-- | :-- |
| [CreateCookie_byLaravel](https://github.com/SampleUser0001/CreateCookie_byLaravel) | Laravel（PHPフレームワーク）でCookieを生成する。 |
| [Practice_Laravel](https://github.com/SampleUser0001/Practice_Laravel.git) | Laravelの勉強用 |

``` sh
PROJECT_NAME=example-app
curl -s https://laravel.build/${PROJECT_NAME} | bash
cd ${PROJECT_NAME} && ./vendor/bin/sail up
```

#### 参考

- [公式:Laravelとの出会い](https://readouble.com/laravel/8.x/ja/installation.html?header=Windows%25E3%2581%25A7%25E5%25A7%258B%25E3%2582%2581%25E3%2582%258B)
- [RitoLabo:Laravel Sail なら Docker 開発環境がコマンド 2 撃で構築できる。PHP/MySQLからキューやメール環境までオールインワン](https://www.ritolab.com/entry/217)
  - こっちのほうが詳しい。

### Slim

| リポジトリ | 概要 |
| :--------- | :--- |
| [Practice_Slim_PHP](https://github.com/SampleUser0001/Practice_Slim_PHP) | [Installation - SlimFramework](https://www.slimframework.com/docs/v4/start/installation.html)を試した。 |

## Python

| リポジトリ | 概要 |
| :-- | :-- |
| [PythonSamples](https://github.com/SampleUser0001/PythonSamples) | Pythonの基本的な文法のサンプル。 |
| [Directory_monitaring_Python](https://github.com/SampleUser0001/Directory_monitaring_Python) | ディレクトリの監視を行う。 |
| [AES_Cipher_byPython](https://github.com/SampleUser0001/AES_Cipher_byPython) | PythonでAES暗号化を行う。（ツール自体の暗号化はあきらめた。） |
| [CreateGraphByPython](https://github.com/SampleUser0001/CreateGraphByPython) | グラフを描く。 |
| [Use_PySimpleGui](https://github.com/SampleUser0001/Use_PySimpleGui) | PySampleGuiを使ってみる。 |
| [CallWebAPI_inPython](https://github.com/SampleUser0001/CallWebAPI_inPython) | PythonでWebAPIを叩く。 |
| [LoadEnv_inPython](https://github.com/SampleUser0001/LoadEnv_inPython.git) | Pythonで.envファイルを読み込む。（python-dotenv） |
| [FileReadWrite_inPython](https://github.com/SampleUser0001/FileReadWrite_inPython) | ファイル読み書き、日付取得のサンプル |
| [UseJson_inPython](https://github.com/SampleUser0001/UseJson_inPython) | jsonを扱う。 |
| [Use_BeautifulSoup_Python](https://github.com/SampleUser0001/Use_BeautifulSoup_Python) | bs4(HTMLスクレイピングライブラリ)を使用する。 |
| [DiffExecuteSpeed_ByPython](https://github.com/SampleUser0001/DiffExecuteSpeed_ByPython) | diffの実行時間の環境ごとの比較 |
| [Enum_inPython](https://github.com/SampleUser0001/Enum_inPython) | Enumの扱いを調査 |
| [Import_inPython](https://github.com/SampleUser0001/Import_inPython) | import文の使い方を調査 |
| [OutputLog_inPython](https://github.com/SampleUser0001/OutputLog_inPython) | ログの出力 |
| [Use_Polymorphism_Python](https://github.com/SampleUser0001/Use_Polymorphism_Python) | ポリモーフィズム |
| [dict_list_inPython](https://github.com/SampleUser0001/dict_list_inPython) | dictとlistを同じループで回したい（無理だった） |
| [Use_pycld2_Python](https://github.com/SampleUser0001/Use_pycld2_Python) | 言語判定ライブラリのpycld2を使用してみる |
| [Use_obs-websocket-py](https://github.com/SampleUser0001/Use_obs-websocket-py) | obs-websocket-pyを使用してみる |
| [Use_Dataclasses_Python](https://github.com/SampleUser0001/Use_Dataclasses_Python) | Data Classを使ってみる | 
| [call_type_Python](https://github.com/SampleUser0001/call_type_Python) | ひたすらtype関数を呼ぶ |
| [Use_Type_Hint_Python](https://github.com/SampleUser0001/Use_Type_Hint_Python) | Type Hintを使う |
| [ReadJson_Python](https://github.com/SampleUser0001/ReadJson_Python) | jsonを読み込んでいい感じに扱う方法を調べる |
| [MergeAndConvertJsonKeys_Python](https://github.com/SampleUser0001/MergeAndConvertJsonKeys_Python) | 複数ファイルのjsonを読み込んでキーだけをマージして出力する。（まだうまく行っていない） |
| [MultiThread_Python](https://github.com/SampleUser0001/MultiThread_Python) | Pythonでマルチスレッドを使う | 
| [MultiProcessing_Python](https://github.com/SampleUser0001/MultiProcessing_Python) | Pythonでマルチプロセスを使う |
| [Use_GitPython_Lambda](https://github.com/SampleUser0001/Use_GitPython_Lambda) | AWS LambdaでGitPythonを使う |
| [Exec_Unix_Command_Python](https://github.com/SampleUser0001/Exec_Unix_Command_Python) | Pythonでunixコマンドを叩く |
| [Exec_aws_cli_Python](https://github.com/SampleUser0001/Exec_aws_cli_Python) | Pythonでaws-cliコマンドを叩く |
| [Use_Boto3](https://github.com/SampleUser0001/Use_Boto3) | Boto3でaws-cliと同じことをする。（aws-cliが不要なので、AWS Lambdaからでも実行できる。） |
| [Use_XML_parser_Python](https://github.com/SampleUser0001/Use_XML_parser_Python) | XMLのパースを行う。 |
| [Use_Streamlit_Python](https://github.com/SampleUser0001/Use_Streamlit_Python) | Streamlitを使ってみた。 |
| [AWS_SQS_Sample_Python_Put](https://github.com/SampleUser0001/AWS_SQS_Sample_Python_Put) | AWS SQSにputする。 |
| [Use_graphviz](https://github.com/SampleUser0001/Use_graphviz) | グラフを作成する |
| [OpenPyXL_Sample](https://github.com/SampleUser0001/OpenPyXL_Sample) | OpenPyXLでExcelファイルを作成する |

### Django

| リポジトリ | 概要 |
| :------- | :-- |
| [Tutorial_Django](https://github.com/SampleUser0001/Tutorial_Django) | Djangoチュートリアル | 
| [Tutorial_Django_2](https://github.com/SampleUser0001/Tutorial_Django_2) | チュートリアル再勉強。いずれマージする。 |
| [Practice_React_Django](https://github.com/SampleUser0001/Practice_React_Django) | React.js + Django | 
| [django_project](https://github.com/SampleUser0001/django_project) | 試す用の環境 |

## Golang

### リポジトリ

| リポジトリ | 概要 |
| :----------- | :--- |
| [logrus_conf](https://github.com/SampleUser0001/logrus_conf) | logrusの設定を読み込む |

## Ruby 

| リポジトリ | 概要 |
| :-------- | :-- |
| [Tutorial_Ruby](https://github.com/SampleUser0001/Tutorial_Ruby) | Rubyのチュートリアル |
| [Professional_Ruby](https://github.com/SampleUser0001/Professional_Ruby) | 「プロを目指す人のためのRuby入門」の勉強用 |

## C#

| リポジトリ | 概要 |
| :-- | :-- |
| [First_CSharp_Project](https://github.com/SampleUser0001/First_CSharp_Project) | Head First C#のお勉強用。 | 

## AR

[AR.md](./AR.md)

## GoogleAnalytics

- [Use_GoogleAnalytics](https://sampleuser0001.github.io/Use_GoogleAnalytics/)
  - [リポジトリ](https://github.com/SampleUser0001/Use_GoogleAnalytics)
- [Test_GoogleAnalytics](https://sampleuser0001.github.io/Test_GoogleAnalytics/)

### その他

- [Use_ModalWindow](https://sampleuser0001.github.io/Use_ModalWindow)
- [GoToTop_Sample](https://sampleuser0001.github.io/GoToTop_Sample/)
- [HLS-sample-with-AWS-S3](https://sampleuser0001.github.io/HLS-sample-with-AWS-S3/)
  - Amazon Elastic TranscoderとAWS S3を使用してmp4→m3u8ファイルの変換
- [Cryptographic_tool_byVBA](https://sampleuser0001.github.io/Cryptographic_tool_byVBA/)
  - 暗号化ツール（VBA版）

## DB

### MySQL

| リポジトリ | 概要 |
| :--------- | :--- |
| [Practice_MySQL_Tutorial](https://github.com/SampleUser0001/Practice_MySQL_Tutorial) | shで実行する |

## Others

| リポジトリ | 概要 |
| :--------- | :--- |
| [FTP_Server_on_Docker](https://github.com/SampleUser0001/FTP_Server_on_Docker) | FTPサーバを作成する。 |
| [Subversion_server_on_Docker](https://github.com/SampleUser0001/Subversion_server_on_Docker) | Subversionサーバを作成する。 |
| [basic_auth_by_nginx](https://github.com/SampleUser0001/basic_auth_by_nginx) | nginxでBasic認証を設定する。 |

### Selenium

| リポジトリ | 概要 |
| :--------- | :--- |
| [Use_Selenium_Python](https://github.com/SampleUser0001/Use_Selenium_Python) | Seleniumを試す |
| [Use_Selenium_Browser_Automate](https://github.com/SampleUser0001/Use_Selenium_Browser_Automate) | Seleniumのクイックツアーを試してみる（まだやってない） |
| [First_Selenium_Script](https://github.com/SampleUser0001/First_Selenium_Script) | [最初のSeleniumスクリプトを書く:Selenium](https://www.selenium.dev/ja/documentation/webdriver/getting_started/first_script/)を試してみる |

## Transfer

- [Transfer_service_memlog](https://github.com/SampleUser0001/Transfer_service_memlog)
- [FilePublicRepository](https://github.com/SampleUser0001/FilePublicRepository)
  - [GithubPages](https://sampleuser0001.github.io/FilePublicRepository/)

## S3

- [https://ittimfn-public.s3-ap-northeast-1.amazonaws.com/index.html](https://ittimfn-public.s3-ap-northeast-1.amazonaws.com/index.html)
- [http://ittimfn-public-lambda.s3-website-ap-northeast-1.amazonaws.com/](http://ittimfn-public-lambda.s3-website-ap-northeast-1.amazonaws.com/)

## Repositories

[https://github.com/SampleUser0001](https://github.com/SampleUser0001)

## 非公開一覧へのリンク

- [PrivateNotes : Github](https://github.com/SampleUser0001/PrivateNotes)
- [Privateへのリンク : AWS Amplify](https://main.d1er9p57pxkuki.amplifyapp.com/)

<!--
**SampleUser0001/SampleUser0001** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
