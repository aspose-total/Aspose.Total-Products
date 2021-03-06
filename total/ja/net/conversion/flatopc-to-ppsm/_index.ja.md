---
title: C＃.NETを介してFLATOPCをPPSMに変換する 
url: /ja/net/conversion/flatopc-to-ppsm/ 
description: C＃を使用してWordドキュメントドキュメントをPowerPointppsmファイルに変換します。 ASP.NETまたは他の.NETアプリケーション内で複数のファイルを変換します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C＃を使用してFLATOPCをPPSMに変換する" h2=".NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームでMicrosoftWordFLATOPCからPowerPointPPSMへの変換アプリを構築します。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" flatopcsLink="https://flatopcs.aspose.com/total/net" installationsFlatopcsLink="https://flatopcs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://flatopcs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C＃を使用してFLATOPCをPPSMに変換する方法" %}}

WordドキュメントファイルからPowerPointppsmプレゼンテーションへのバッチ変換のプロセスを自動化するために、[Aspose.Words for .NET](https://products.aspose.com/words/net)と[Aspose.Slides for .NET](https://products.aspose.com/slides/net)API。前者は、MicrosoftWord文書を処理または操作するためのワードプロセッシングAPIです。一方、後者は、MicrosoftPowerPointスライドを作成または変更できるプレゼンテーション操作APIです。両方のAPIは、[Aspose.Total for .NET](https://products.aspose.com/total/net)パッケージの一部です。 Nugetから直接[ダウンロード](https://downloads.aspose.com/)するか、パッケージマネージャーコンソールから次のコマンドを使用できます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C＃を介してFLATOPCをPPSMに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Totalfor.NETの参照を追加します
1. [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)クラスを使用してFLATOPCファイルをロードします
1. FLATOPCドキュメントをHTMLに保存します
1. [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)オブジェクトを作成します
1. プレゼンテーション内の任意のスライド形状のテキストフレームにHTMLコンテンツをインポートします
1. [Aspose.Slides.Presentation.Save（ "output.ppsm"、SaveFormat.Ppsm)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods)を使用してドキュメントを保存します/ 5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

-Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS。
-MicrosoftVisualStudioのような開発環境。
--Aspose.Words for .NET＆amp;プロジェクトで参照されている.NETDLLの場合はAspose.Slides、.NETDLLの場合はAspose.Total。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このコードサンプルは、C＃を使用してFLATOPCをPPSMに変換する方法を示しています" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word FLATOPC file
Aspose.Words.Document flatopc = new Aspose.Words.Document("sourceWordFile.flatopc");

// Save FLATOPC file to HTML 
flatopc.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages FLATOPC documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPSM.

using (Presentation ppsm = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPSM Presentation
	ppsm.Save("filepath\\pres.ppsm", Aspose.Slides.Export.SaveFormat.Ppsm);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="FLATOPCをPPSMに変換する無料アプリ" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-ppt/" name="FLATOPC に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-pptx/" name="FLATOPC に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-pps/" name="FLATOPC に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-pot/" name="FLATOPC に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-ppsx/" name="FLATOPC に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-pptm/" name="FLATOPC に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-ppsm/" name="FLATOPC に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-potx/" name="FLATOPC に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-potm/" name="FLATOPC に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/flatopc-to-ppsm/" name="FLATOPC に PPSM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}