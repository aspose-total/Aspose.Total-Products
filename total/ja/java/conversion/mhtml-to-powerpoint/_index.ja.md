---
title: JavaAPIを介してMHTMLをPOWERPOINTに変換する
description: MicrosoftWordを使用せずにMHTMLをPOWERPOINTに変換するJavaAPI
url: /ja/java/conversion/mhtml-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: PPT
otherformats: PPTM OTP POTM XAML POTX PPT PPSX POWERPOINT POT PPSM PPS SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MHTMLをPOWERPOINTにエクスポートするJavaAPI" h2="Microsoft<sup>＆reg;</sup>PowerPointまたはAdobe<sup>＆reg;</sup>AcrobatReaderを使用せずにオンプレミスのJavaAPIを介してMHTMLをPOWERPOINTにエクスポートする" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を使用すると、Java J2SE、J2EE、J2MEアプリケーション内でMHTMLをPOWERPOINTに簡単に変換できます。まず、[Aspose.PDF for Java]（https://products.aspose.com/pdf/java/）を使用すると、MHTMLをPPTXにエクスポートできます。その後、[Aspose.Slides for Java]（https://products.aspose.com/slides/java/）PowerPoint Processing APIを使用して、PPTXをPOWERPOINTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTMLをPOWERPOINTに変換するJavaAPI" %}}
1. [ドキュメント]（https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document）クラスを使用してMHTMLファイルを開きます
2. [save]（https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-）メソッドを使用してMHTMLをPPTXに変換します
3. [プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用してPPTXドキュメントをロードします
4. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-）メソッドを使用してドキュメントをPOWERPOINT形式で保存し、`を設定します。 SaveFormatとしてのPowerpoint`
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できます[Aspose.PDF for Java]（https://docs.aspose.com/pdf/java/installation/）と[Aspose.Slides for Java]（https://docs.aspose.com/slides/java/あなたのpom.xmlのinstallation/）。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
MHTMLファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Java]（https://products.aspose.com/pdf/java/）を使用すると、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、[ドキュメント]の新しいインスタンスを初期化できます（https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-）クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java経由で暗号化されたMHTMLファイルを開く" %}}
MHTMLをPOWERPOINTに変換した後、プレゼンテーションに事前定義されたビュータイプを追加することもできます。 [Aspose.Slides for Java]（https://products.aspose.com/slides/java/）は、[ViewProperties]（https：/）を介してPowerPointで開いたときに、生成されたプレゼンテーションのビュータイプを設定する機能を提供します。 /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties）クラス。 [setLastView]（https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-）プロパティは、[ViewType]（https：/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType）列挙子。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-pps/" name="MHTML に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-swf/" name="MHTML に SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-potx/" name="MHTML に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-ppsx/" name="MHTML に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-potm/" name="MHTML に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-ppt/" name="MHTML に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-ppsm/" name="MHTML に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-xaml/" name="MHTML に XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-otp/" name="MHTML に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-pptm/" name="MHTML に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-pot/" name="MHTML に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mhtml-to-powerpoint/" name="MHTML に POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}