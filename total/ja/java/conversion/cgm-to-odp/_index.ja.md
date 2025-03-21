---
title: JavaAPIを介してCGMをODPに変換する
description: MicrosoftWordを使用せずにCGMをODPに変換するJavaAPI
url_ignore: /ja/java/conversion/cgm-to-odp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODP
otherformats: PPS SWF POTX PPSX POTM PPT PPSM XAML OTP PPTM POT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGMをODPにエクスポートするJavaAPI" h2="Microsoft<sup>＆reg;</sup>PowerPointまたはAdobe<sup>＆reg;</sup>AcrobatReaderを使用せずにオンプレミスのJavaAPIを介してCGMをODPにエクスポートする" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、Java J2SE、J2EE、J2MEアプリケーション内でCGMをODPに簡単に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、CGMをPPTXにエクスポートできます。その後、[Aspose.Slides for Java](https://products.aspose.com/slides/java/)PowerPoint Processing APIを使用して、PPTXをODPに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをODPに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してCGMファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)メソッドを使用してCGMをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをODP形式で保存し、`を設定します。 SaveFormatとしてのOdp`
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-odp.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
CGMファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java経由で暗号化されたCGMファイルを開く" %}}
CGMをODPに変換した後、プレゼンテーションに事前定義されたビュータイプを追加することもできます。 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)は、[ViewProperties](https：/)を介してPowerPointで開いたときに、生成されたプレゼンテーションのビュータイプを設定する機能を提供します。 /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties)クラス。 [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-)プロパティは、[ViewType](https：/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType)列挙子。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}