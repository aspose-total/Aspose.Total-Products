---
title: C＃.NETを介してPOTをDOCに変換する 
url: /ja/net/conversion/pot-to-doc/ 
description: PowerPointのpotドキュメントをC＃を使用してWordのドキュメントファイルに変換します。 ASP.NETまたは他の.NETアプリケーション内で複数のファイルを変換します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C＃を使用してPOTをDOCに変換する" h2=".NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームでMicrosoftPowerPointPOTプレゼンテーションからWordDOCドキュメントへの変換アプリを構築します。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docsLink="https://docs.aspose.com/total/net" installationsDocsLink="https://docs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C＃を使用してPOTをDOCに変換する方法" %}}

PowerPointpotプレゼンテーションからWorddocファイルへのバッチ変換のプロセスを自動化するために、[Aspose.Slides for .NET](https://products.aspose.com/slides/net)と[Aspose.Words for .NET](https://products.aspose.com/words/net)API。前者は、MicrosoftPowerPointスライドを作成または変更できるPowerPointプレゼンテーション操作APIです。一方、後者はMicrosoftWord文書を処理または操作するためのワードプロセッシングAPIです。両方のAPIは、[Aspose.Total for .NET](https://products.aspose.com/total/net)パッケージの一部です。 Nugetから直接[ダウンロード](https://downloads.aspose.com/)するか、パッケージマネージャーコンソールから次のコマンドを使用できます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C＃を介してPOTをDOCに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Slidesfor.NETおよびAspose.Wordsfor.NETの参照を追加します
1. [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPowerPointPOTプレゼンテーションをロードします
1. ドキュメントを[MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0)オブジェクトに保存します
1. [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)を作成し、MemoryStreamオブジェクトで初期化します。
1. [Aspose.Words.Document.Save（ "output.doc"、SaveFormat.Doc)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods)を使用してドキュメントを保存します/ 3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

-Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS。
-MicrosoftVisualStudioのような開発環境。
-プロジェクトで参照されているAspose.Slidesfor.NETおよびAspose.Wordsfor.NETDLL。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このコードサンプルは、C＃を使用してPOTをDOCに変換する方法を示しています" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POT file
Aspose.Slides.Presentation pot = new Aspose.Slides.Presentation("source.pot");

var stream = new MemoryStream();

pot.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var doc = new Aspose.Words.Document(stream);
      
// Save the Word DOC document
doc.Save("output.doc", Aspose.Words.SaveFormat.Doc);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="POTをDOCに変換する無料アプリ" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-doc" name="POT に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-docx" name="POT に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-rtf" name="POT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-dot" name="POT に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-dotx" name="POT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-dotm" name="POT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-docm" name="POT に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-flatopc" name="POT に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-odt" name="POT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-ott" name="POT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-wordml" name="POT に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pot-to-txt" name="POT に TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}