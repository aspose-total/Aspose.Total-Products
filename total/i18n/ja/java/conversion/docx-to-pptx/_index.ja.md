---
title: Java経由でDOCXをPPTXに変換する
description: MicrosoftWordやPowerPointを使用せずにDOCXをPPTXにエクスポートするJavaAPI
url: /ja/java/conversion/docx-to-pptx/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: PPTX
otherformats: POTX PPTM POT POTM PPSM POWERPOINT PPSX PPT PPS PPTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でDOCXをPPTXに変換する" h2="Microsoft <sup>＆reg; </ sup> PowerPointまたはWordを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内でオンプレミスのJavaAPIを使用することによるDOCXからPPTXへの変換" >}}
{{% blocks/products/pf/feature-page-summary %}}
多くの場合、開発者はプログラムでDOCXファイルをPPTXに変換する必要があります。 FileAutomationJavaライブラリ[Aspose.TotalforJava]（https://products.aspose.com/total/java/）を使用すると、いくつかの簡単な手順でレンダリングプロセスを自動化できます。 [Aspose.Words for Java]（https://products.aspose.com/words/java/）を使用してDOCXファイルをロードし、HTMLに変換できます。その後、強力なPowerPoint操作Java API [Aspose.Slides for Java]（https://products.aspose.com/slides/java/）を使用して、新しいプレゼンテーションを作成し、その中にHTMLコンテンツを書き込んで、PPTXとして保存できます。 。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してDOCXをPPTXに変換する方法" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Docxument）クラスを使用してDOCXファイルを開きます
2. [save]（https://apireference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してDOCXファイルをHTMLに変換します）） 方法
3.新しい[プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）オブジェクトを初期化します
5. BufferedReaderを使用してHTMLファイルからコンテンツを抽出し、プレゼンテーションファイルにコンテンツを書き込みます
6. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-）メソッドを使用してドキュメントをPPTXに保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
DOCXからPPTXファイルへの変換では、[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose）から直接Aspose.TotalforJavaを簡単に使用できます。 / aspose-total）ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用すると、パスワードで保護されたDOCXドキュメントをPPTXに変換することもできます。入力DOCXドキュメントがパスワードで保護されている場合、パスワードを使用せずにPPTX形式に変換することはできません。暗号化されたドキュメントを開くには、LoadOptionsオブジェクトに正しいパスワードを設定し、それをDocxumentコンストラクターに渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-docx-to-pptx.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-ppsm/" name="DOCX に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-pot/" name="DOCX に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-powerpoint/" name="DOCX に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-pptx/" name="DOCX に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-potx/" name="DOCX に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-pptm/" name="DOCX に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-potm/" name="DOCX に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-pps/" name="DOCX に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-ppsx/" name="DOCX に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-ppt/" name="DOCX に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-csv/" name="DOCX に CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-dif/" name="DOCX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-fods/" name="DOCX に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-ods/" name="DOCX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-sxc/" name="DOCX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-tsv/" name="DOCX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlam/" name="DOCX に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xltm/" name="DOCX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-excel/" name="DOCX に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xls/" name="DOCX に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlsb/" name="DOCX に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlsm/" name="DOCX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlsx/" name="DOCX に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlt/" name="DOCX に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xltm/" name="DOCX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xltx/" name="DOCX に XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}