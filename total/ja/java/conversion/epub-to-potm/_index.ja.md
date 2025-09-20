---
title: JavaAPIを介してEPUBをPOTMに変換する
description: MicrosoftWordを使用せずにEPUBをPOTMに変換するJavaAPI
url_ignore: /ja/java/conversion/epub-to-potm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POTM
otherformats: PPTM OTP PPT PPSM SWF XAML POTM POWERPOINT POT POTX PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EPUBをPOTMにエクスポートするJavaAPI" h2="Microsoft<sup>＆reg;</sup>PowerPointまたはAdobe<sup>＆reg;</sup>AcrobatReaderを使用せずにオンプレミスのJavaAPIを介してEPUBをPOTMにエクスポートする" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、Java J2SE、J2EE、J2MEアプリケーション内でEPUBをPOTMに簡単に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、EPUBをPPTXにエクスポートできます。その後、[Aspose.Slides for Java](https://products.aspose.com/slides/java/)PowerPoint Processing APIを使用して、PPTXをPOTMに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをPOTMに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してEPUBファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)メソッドを使用してEPUBをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをPOTM形式で保存し、`を設定します。 SaveFormatとしてのPotm`
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
EPUBファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java経由で暗号化されたEPUBファイルを開く" %}}
EPUBをPOTMに変換した後、プレゼンテーションに事前定義されたビュータイプを追加することもできます。 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)は、[ViewProperties](https：/)を介してPowerPointで開いたときに、生成されたプレゼンテーションのビュータイプを設定する機能を提供します。 /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties)クラス。 [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-)プロパティは、[ViewType](https：/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType)列挙子。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**EPUB**を**POTM（マクロ有効なPowerPointテンプレート）**に変換することは、電子書籍から**自動化されたインタラクティブテンプレート**を生成するために不可欠です。POTMファイルには埋め込まれたマクロを持つ再利用可能なスライドが含まれており、自動化されたワークフロー、動的コンテンツの更新、インタラクティブな機能が可能です。EPUBをPOTMに変換することで、教育関係者、出版社、企業は生産性を向上させ、スライドデザインを標準化し、トレーニングやレポート作成プロセスを効率化する知的なプレゼンテーションを作成できます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用事例" %}}
- **自動化された学術プレゼンテーション** – 事前に構成されたインタラクティブ要素を備えた講義スライドを生成します。
- **企業向けスライド自動化** – 社内プレゼンテーションワークフローを標準化および自動化します。
- **マクロを使用した出版ワークフロー** – マクロを埋め込んでプレゼンテーションテンプレートのコンテンツ更新を効率化します。
- **研究フレームワーク** – 学術的コンテンツをインタラクティブでマクロ有効なスライドに変換します。
- **企業向けトレーニングテンプレート** – チーム全体に再利用可能で自動化されたトレーニングプレゼンテーションを提供します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}
- **EPUBからPOTMへのパイプライン** – 電子書籍をマクロ有効なプレゼンテーションテンプレートに自動変換します。
- **マクロ有効なプレゼンテーションの自動化** – スライドに動的コンテンツとインタラクティブ性を統合します。
- **メタデータ駆動型スライドテンプレート** – 構造化された電子書籍データを使用してプレゼンテーションコンテンツを自動的に埋めます。
- **大量出版テンプレートの作成** – 企業や教育機関向けの大規模なインタラクティブスライドテンプレートを生成します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}