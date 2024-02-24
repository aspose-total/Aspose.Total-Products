---
title: C# を使用した Web スクレイピング - HTML を Word ファイルに変換する 
description: Aspose API を統合することで、Web サイトの Web ページをスクレイピングし、.NET アプリケーション経由で HTML を Microsoft Word ドキュメントにエクスポートします。 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: WORD
otherformats: EXCEL POWERPOINT PDF IMAGES
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# による Web スクレイピング" h2=".NET アプリケーション内の Web ページからデータを抽出し、HTML を Microsoft Word ファイルに変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Webスクラッチとは何ですか?</h2>

<p>Web スクレイピングは、Web ハーベスティング、データ スクレイピング、Web データ抽出、または Web クローリングとも呼ばれ、Web サイトからデータを抽出するために使用される技術です。 これには、専用のソフトウェアまたはツールを利用して、Web ページから特定の情報を取得する自動プロセスが含まれます。</p><br />
<p>Web スクレイピング ソフトウェアまたはスクリプトは、人間の閲覧動作をシミュレートし、Web サイトと対話してデータを収集するように設計されています。 これらのツールは、HTTP リクエストを Web サーバーに送信し、HTML または XML レスポンスを取得し、取得したコンテンツから必要なデータ要素を抽出します。</p><br />

<p>抽出されたデータには、特定の要件に応じて、テキスト、画像、表、リンク、価格、製品の詳細、レビューなど、さまざまな種類の情報を含めることができます。 抽出されたデータは通常、さらなる分析、保存、または他のシステムとの統合のために、DOC、DOCX、CSV、JSON、データベースなどの構造化形式で保存されます。</p><br />

<p>Web スクレイピングには多数の用途があり、さまざまな業界で使用されています。 市場調査、競合分析、センチメント分析、価格監視、データ集約、コンテンツスクレイピング、見込み客発掘などに使用できます。</p><br />

<p>ただし、Web スクレイピングは責任を持って倫理的に実行する必要があることに注意することが重要です。 Web サイトの利用規約を尊重し、法的規制を遵守し、プライバシーや知的財産権を侵害する可能性のある活動に従事しないことが重要です。</p>

<h2 class="heading-border">Aspose.HTML を Web スクレイピング API として使用する</h2>

<p>Aspose.Total for .NET の子 API である Aspose.HTML for .NET API を利用すると、HTML ドキュメントからの情報の分析と抽出を伴う独自のアプリケーションを簡単に開発できます。 API は、このプロセスを容易にする堅牢なツールセットを提供します。</p><br />

<p>スクレイパーを構築する場合、データ セレクターは、HTML ファイルから必要な情報を識別して抽出する上で重要な役割を果たします。 通常、これらのセレクターは XPath、CSS セレクター、またはその両方の組み合わせを利用して、HTML 構造内の特定のデータ要素を見つけます。 これらのセレクターは、ドキュメント内を移動し、抽出するデータを正確に指定する手段として機能します。</p>

<h2 class="heading-border">Webスクレイピングのために実行できるタスク</h2>

<p>Aspose.HTML for .NET を利用すると、Web ページからのデータ抽出が簡単に自動化され、開発者は次の Web スクレイピング タスクを効果的に実行できます。</p><br />

1. [HTMLナビゲーション](https://docs.aspose.com/html/net/html-navigation/) - HTML ドキュメントとその要素を徹底的に検査します。 詳細な分析、要素反復のカスタム フィルタリング、CSS セレクターまたは XPath を使用したシームレスなナビゲーションのための機能を提供します。
2. [ダウンロードウェブサイト](https://docs.aspose.com/html/net/download-website/) - URL から Web サイトをダウンロードし、ダウンロード プロセスをカスタマイズします。 これにより、Web サイト全体をダウンロードするか、特定の Web ページをダウンロードするかを選択し、要件に合わせてプロセスを適応させることができます。
3. [URLからファイルをダウンロード](https://docs.aspose.com/html/net/download-file-from-url/) 
4. [ウェブサイトから画像をダウンロード](https://docs.aspose.com/html/net/download-images-from-website/) - Web サイトからさまざまな種類の画像をダウンロードします。
5. [ウェブサイトから SVG をダウンロード](https://docs.aspose.com/html/net/download-svg-from-website/) - C# を使用して Web サイトからスケーラブル ベクター グラフィックス SVG ファイルをダウンロードする

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# を使用して Web データを抽出するにはどうすればよいですか?" %}}

1. を活用してください。 [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/htmldocument/) URL から HTML ドキュメントを初期化するコンストラクター
2. 使用 [QuerySelectorAll(selector)](https://reference.aspose.com/html/net/aspose.html.dom/document/queryselectorall/) メソッドを使用してセレクターを指定し、セレクターに一致するすべての要素を取得します。
3. 要素のリストをループし、結果を必要な形式で出力します。
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Web スクラッチと変換の要件" %}}
``nuget install Aspose.Total`` としてコマンド ラインからインストールするか、Visual Studio のパッケージ マネージャー コンソールから直接インストールします。

二 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 子API、 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) と [Aspose.Words for .NET](https://products.aspose.com/words/net/) 統合されることになります。

または、オフライン MSI インストーラーまたは ZIP ファイル内の DLL を次のサイトから入手します。 [ダウンロード](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "extract-data-using-csharp.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Aspose.Words を使用した HTML から Word への変換" %}}
<p>HTML ファイルをプログラムで Word 形式に変換する必要がある場合は、Aspose.Total の別の子 API である Aspose.Words for .NET がシンプルで効率的なソリューションを提供します。 開発者は、この最新の文書処理 API を使用して、わずか数行の C# コードで HTML を Word に簡単に変換できます。</p><br />

<p>Aspose.Words for .NET は、HTML から Word への高速変換を提供し、優れた品質の結果を保証します。ブラウザで直接 HTML から Word への変換をテストすることもできます。 この強力な C# ライブラリは、HTML ファイルのさまざまな一般的な形式への変換をサポートします。</p><br />

<p>Aspose.Words が提供する機能を使用すると、開発者は HTML ファイルを Word 形式にシームレスに変換でき、アプリケーション内の変換プロセスを簡素化できます。</p><br />

<p>C# で HTML を Word に変換するには、次の簡単な手順に従います。:</p><br />

1. スクラップされた HTML ファイルをローカル ドライブから読み取ります。
1. Word 拡張子を使用して目的のファイル形式を指定し、ファイルを Word として保存します。
1. HTML の読み取りと Word ドキュメントの書き込みの両方で、完全修飾ファイル名を使用できます。
1. 作成された Word 文書には、元の HTML ファイルの内容と書式設定が保持されます。

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-html-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}