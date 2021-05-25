# Home

[cloud9_note](https://sampleuser0001.github.io/cloud9_note/)

- [Home](#home)
  - [Tools](#tools)
    - [形態素解析](#形態素解析)
  - [Template](#template)
  - [Java](#java)
    - [MultiThread](#multithread)
  - [JavaScript](#javascript)
    - [Node.js](#nodejs)
    - [TypeScript](#typescript)
    - [Vue.js](#vuejs)
  - [PHP](#php)
    - [Laravel](#laravel)
      - [参考](#参考)
  - [Python](#python)
  - [AR](#ar)
  - [GoogleAnalytics](#googleanalytics)
  - [HTML/CSS/JavaScript](#htmlcssjavascript)
    - [その他](#その他)
  - [Transfer](#transfer)
  - [S3](#s3)
  - [Repositories](#repositories)
  - [非公開一覧へのリンク](#非公開一覧へのリンク)

## Tools

| ツール名 | 概要 | リンク | 使用言語 |
| :---- | :--- | :--- | :-- |
| Replace | 一括置換 | [Replace](https://github.com/SampleUser0001/ReplaceByJava) | Java |
| DiffProperties | Javaのpropertiesの差分を取得する | [DiffProperties](https://github.com/SampleUser0001/DiffProperties) | Java |
| ConvertSpaceIndexToComma | (Linuxでよく見かける)半角スペースインデントをカンマ区切りに変換する | [ConvertSpaceIndexToComma](https://github.com/SampleUser0001/ConvertSpaceIndexToComma) | Python |
| GetYoutubeLiveComment | YoutubeのLiveのコメントを取得する。 | [GetYoutubeLiveComment](https://github.com/SampleUser0001/GetYoutubeLiveComment) | Python |
| GetYoutubeArchiveComment | YoutubeのArchiveのコメントを取得する。(Youtubeの規約に抵触するため非公開。アーカイブのコメントを取得するAPIの実装を希望。 -> Youtube) | [GetYoutubeArchiveComment](https://github.com/SampleUser0001/GetYoutubeArchiveComment) | Python |
| OWASPZAP_ResultJson_toTSV | OWASP ZAPの実行結果をTSVに変換する。 | [OWASPZAP_ResultJson_toTSV](https://github.com/SampleUser0001/OWASPZAP_ResultJson_toTSV) | Java |

### 形態素解析

| ツール名 | 概要 | 使用言語 |
| :------ | :-- | :--- |
| [Get_NG_Pattern](https://github.com/SampleUser0001/Get_NG_Pattern) | [GetYoutubeArchiveComment](https://github.com/SampleUser0001/GetYoutubeArchiveComment)で取得したコメントを形態素解析し、NG対象とするコメントを出力する。 | Python |
| [Use_MeCab_for_LiveComment](https://github.com/SampleUser0001/Use_MeCab_for_LiveComment) | [Get_NG_Pattern](https://github.com/SampleUser0001/Get_NG_Pattern)で生成した形態素解析結果から[GetYoutubeLiveComment](https://github.com/SampleUser0001/GetYoutubeLiveComment)の出力結果コメントにNG判定を付与する。 | Python |
| [Use_MeCab_for_ArchiveComment](https://github.com/SampleUser0001/Use_MeCab_for_ArchiveComment) | [Get_NG_Pattern](https://github.com/SampleUser0001/Get_NG_Pattern)で生成した形態素解析結果から[GetYoutubeArchiveComment](https://github.com/SampleUser0001/GetYoutubeArchiveComment)の出力結果コメントにNG判定を付与する。 | Python |

## Template

- [TemplateMaven](https://github.com/SampleUser0001/TemplateMaven)
- [TemplateNode](https://github.com/SampleUser0001/TemplateNode)
- [Template Python on Docker](https://github.com/SampleUser0001/Template_Python_on_Docker)
- [Template_PHP_MySQL_Nginx](https://github.com/SampleUser0001/Template_PHP_MySQL_Nginx)
- [Minecraft Server on Docker](https://github.com/SampleUser0001/MinecraftServer_onDocker)
- [NginxContainerTemplate](https://github.com/SampleUser0001/NginxContainerTemplate)
- [Template_MeCab](https://github.com/SampleUser0001/Template_MeCab)
- [TypeScript_MySQL_onDocker](https://github.com/SampleUser0001/TypeScript_MySQL_onDocker)

## Java

| リポジトリ | 概要 |
| :-- | :-- |
| [JavaSamples](https://github.com/SampleUser0001/JavaSamples) | Javaのサンプル集 |
| [Sample_ReadXML_byJava](https://github.com/SampleUser0001/Sample_ReadXML_byJava) | JavaでXMLを読み込む |
| [Use_zipcloud_json](https://github.com/SampleUser0001/Use_zipcloud_json) | APIを叩いてJSONを読み込む。 |

### MultiThread

| リポジトリ | 概要 |
| :-- | :-- |
| [MultiThreadSample](https://github.com/SampleUser0001/MultiThreadSample.git) | ExecutorServiceを使用したマルチスレッドの実装のサンプル集 |
| [UseConcurrentHashMap_byJava](https://github.com/SampleUser0001/UseConcurrentHashMap_byJava) | マルチスレッドでMap.put, ConcurrentHashMap.put, ConcurrentHashMap.putIfAbsentでmapに登録した場合の動作確認プロジェクト。 |
| [UseConcurrentHashMap_byJava_02](https://github.com/SampleUser0001/UseConcurrentHashMap_byJava_02) | Mapに対してputしながらgetした場合の挙動。HashMapとConcurrentHashMapの違い |

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

### TypeScript

| リポジトリ | 概要 |
| :-- | :-- |
| [Practice_Programing_TypeScript](https://github.com/SampleUser0001/Practice_Programing_TypeScript) | オライリー プログラミングTypeScriptの勉強用 |
| [Study_TypeScript](https://github.com/SampleUser0001/Study_TypeScript) | TypeScriptの勉強用 |
| [TypeScript_express_decorator](https://github.com/SampleUser0001/TypeScript_express_decorator) | TypeScript + expressでデコレータ(Javaで言うアノテーション)を使う。 |
| [TypeScript_MySQL_onDocker](https://github.com/SampleUser0001/TypeScript_MySQL_onDocker) | TypeScript + MySQL環境をDockerで構築する。 |
| [Use_import_TypeScript](https://github.com/SampleUser0001/Use_import_TypeScript) | export/import文の使い方 |

### Vue.js

| リポジトリ | 概要 |
| :-- | :-- |
| [Vue_Practice](https://github.com/SampleUser0001/Vue_Practice) | Vue.jsの勉強をする。 |
| [vue_cli_test](https://github.com/SampleUser0001/vue_cli_test) | Vue CLIでVue.jsを動かす |

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

## AR

[AR.md](./AR.md)

## GoogleAnalytics

- [Use_GoogleAnalytics](https://sampleuser0001.github.io/Use_GoogleAnalytics/)
  - [リポジトリ](https://github.com/SampleUser0001/Use_GoogleAnalytics)
- [Test_GoogleAnalytics](https://sampleuser0001.github.io/Test_GoogleAnalytics/)

## HTML/CSS/JavaScript

| リポジトリ | 概要 |
| :-- | :-- |
| [HTML5_CSS_JavaScript_Programing](https://github.com/SampleUser0001/HTML5_CSS_JavaScript_Programing) | ゲームを作りながら楽しく学べるHTML5+CSS+JavaScriptプログラミング［改訂版］の練習用 |
| [OnloadJavaScript](https://github.com/SampleUser0001/OnloadJavaScript) | 画面遷移時にJavaScriptを実行する。 |

### その他

- [Use_ModalWindow](https://sampleuser0001.github.io/Use_ModalWindow)
- [GoToTop_Sample](https://sampleuser0001.github.io/GoToTop_Sample/)
- [HLS-sample-with-AWS-S3](https://sampleuser0001.github.io/HLS-sample-with-AWS-S3/)
  - Amazon Elastic TranscoderとAWS S3を使用してmp4→m3u8ファイルの変換
- [Cryptographic_tool_byVBA](https://sampleuser0001.github.io/Cryptographic_tool_byVBA/)
  - 暗号化ツール（VBA版）

## Transfer

- [Transfer_service_memlog](https://github.com/SampleUser0001/Transfer_service_memlog)

## S3

- [https://ittimfn-public.s3-ap-northeast-1.amazonaws.com/index.html](https://ittimfn-public.s3-ap-northeast-1.amazonaws.com/index.html)

## Repositories

[https://github.com/SampleUser0001](https://github.com/SampleUser0001)

## 非公開一覧へのリンク

[PrivateNotes](https://github.com/SampleUser0001/PrivateNotes)

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
