---
title: C# を使用して Web ページの HTML を画像に変換する
description: Web サイトの Web ページをスクレイピングし、HTML を画像にエクスポートします。 Web サイトのデータを JPEG、PNG、GIF、BMP などにスクレイピングする .NET アプリケーションを開発します。 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# 経由で Web ページを画像に変換する" h2="HTML Web ページから Web サイト データを抽出します。 .NET アプリケーション内で HTML を JPG、GIF、PNG、BMP 画像に変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Web ページを画像に変換する理由</h2>
<p>Web ページを画像に変換すると、さまざまな状況で役立ちます。これは多くのアプリケーションに共通の要件です。 シナリオによっては、画面に表示されていない部分も含めて、Web ページ全体を画像としてキャプチャする必要があります。 これは、Web サイトのプレビューを生成したり、領収書や請求書を取得したり、法的目的で Web ページをアーカイブしたりする場合に役立ちます。ドキュメントやテストの目的で Web ページのスクリーンショットを作成するために使用できます。 また、検索結果や画像ギャラリーで使用する Web ページのサムネイルやプレビューを作成するために使用することもできます。 デスクトップ アプリケーションを構築しているか Web アプリケーションを構築しているかに関係なく、C# を使用して Web ページを画像に変換するために利用できるオプションが多数あります。</p><br />

<p>C# を使用して Web ページを画像に変換すると、次のようないくつかの利点が得られます。</p><br />
<ul>
<li>アクセシビリティの向上: 視覚障害やその他の障害のある人にとって、画像は読みやすく、理解しやすくなります。</li>
<li>携帯性の向上: 画像は簡単に共有したり、他のドキュメントやアプリケーションに埋め込んだりできます。</li>
</ul>
<p>C# を使用して Web ページを画像に変換すると、次のようないくつかの課題が生じる可能性があります。</p><br />
<ul>
<li>限られた形式のサポート: 一部の API またはツールは、すべての画像形式をサポートしていない場合や、出力画像のサイズや解像度に制限がある場合があります。</li>
<li>互換性の問題: 一部の Web ページは、すべてのブラウザで正しく表示されない場合や、正しく表示するには特定の設定やプラグインが必要な場合があります。</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# を使用して Web ページを画像に変換するには?" %}}
C# を使用して Web ページを画像に変換するには、HTML ページを JPEG、PNG、TIFF などの画像形式に変換するこの機能を提供する Aspose.HTML for .NET API を使用できます。</p>

1. で使用可能なコンストラクターの 1 つを使用して HTML ドキュメントをロードします。 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). HTML は、ファイル、HTML コード、ストリーム、または URL からロードできます。
2. の新しいインスタンスを作成します [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) ImageFormat プロパティを JPEG に設定します。デフォルトでは、Format プロパティは PNG に設定されています。
3. を活用してください。 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) Converter クラスのメソッドを使用して、HTML ドキュメントを JPEG ファイルとして保存します。 HTMLDocument、ImageSaveOptions、および出力ファイルのパスをパラメータとして ConvertHTML() メソッドに指定する必要があります。
4. 作成された JPEG ファイルは、指定したファイル パスに保存されます。
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Web スクレイピングと画像変換の要件" %}}
``nuget install Aspose.Total`` としてコマンド ラインからインストールするか、Visual Studio のパッケージ マネージャー コンソールから直接インストールします。

二 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 子API、 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) 統合されることになります。

または、オフライン MSI インストーラーまたは ZIP ファイル内の DLL を次のサイトから入手します。 [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}