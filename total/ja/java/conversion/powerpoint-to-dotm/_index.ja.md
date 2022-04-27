---
title: Java経由でPOWERPOINTをDOTMに変換する
description: MicrosoftWordやPowerPointを使用せずにPOWERPOINTをDOTMにエクスポートするJavaAPI
url: /ja/java/conversion/powerpoint-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: DOTM
otherformats: RTF OTT DOTMX WORDML DOTMM DOTM DOT ODT WORD DOTX FLATOPC TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でPOWERPOINTをDOTMに変換する" h2="任意のJavaJ2SE、J2EE、J2MEアプリケーション内でのPowerPointPOWERPOINTからDOTMへの変換のためのオンプレミスJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）ファイル形式自動化ライブラリにより、Java開発者はPowerPointPOWERPOINTからWordDOTMへのバッチ変換プロセスを自動化できます。ドキュメントの変換は2段階のプロセスであり、2つのAPIを使用する必要があります。 POWERPOINTをHTMLに変換するためのプレゼンテーションの操作と管理のためのPowerPointAPIである[Aspose.SlidesforJava]（https://products.aspose.com/slides/java/）を使用します。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for Java]（https://products.aspose.com/words/java/）を使用して、HTMLをDOTMに変換します。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してPOWERPOINTをDOTMに変換する方法" %}}
1. [プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用してPOWERPOINTファイルを開きます
2. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesを使用してPOWERPOINTをHTMLに変換します。 ISaveOptions-）メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Dotmument]（https://apireference.aspose.com/words/java/com.aspose.words/Dotmument）クラスを使用して変換されたHTMLファイルをロードします
4. [save]（https://apireference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,int））メソッドを使用してドキュメントをDOTM形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
POWERPOINTからDOTMファイルへの変換では、[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose）から直接Aspose.TotalforJavaを簡単に使用できます。 / aspose-total）ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用して、透かしを使用してPOWERPOINTファイルからDOTMへの変換を実行することもできます。 DOTMドキュメントに透かしを追加するには、最初にPOWERPOINTファイルをHTMLに変換し、それに透かしを追加します。透かしを追加するには、[Dotmument]（https://apireference.aspose.com/words/java/com.aspose.words/Dotmument）クラスを使用して新しく作成したHTMLファイルをロードし、TextWatermarkOptionsのインスタンスを作成して設定します。そのプロパティ、Watermark.setTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-protected-powerpoint-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-word/" name="POWERPOINT に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dotx/" name="POWERPOINT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-odt/" name="POWERPOINT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-ott/" name="POWERPOINT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-rtf/" name="POWERPOINT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-flatopc/" name="POWERPOINT に FLAにPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-wordml/" name="POWERPOINT に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dotmm/" name="POWERPOINT に DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-text/" name="POWERPOINT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dotmx/" name="POWERPOINT に DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dotm/" name="POWERPOINT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dot/" name="POWERPOINT に DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}