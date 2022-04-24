---
title: Java経由でODTをPPSに変換する
description: MicrosoftWordやPowerPointを使用せずにODTをPPSにエクスポートするJavaAPI
url: /ja/java/conversion/odt-to-pps/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: PPS
otherformats: POTX POTM PPT POT PPTM PPTX PPSX PPS PPSM POWERPOINT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でODTをPPSに変換する" h2="Microsoft <sup>＆reg; </ sup> PowerPointまたはWordを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内でオンプレミスのJavaAPIを使用することによるODTからPPSへの変換" >}}
{{% blocks/products/pf/feature-page-summary %}}
多くの場合、開発者はプログラムでODTファイルをPPSに変換する必要があります。 FileAutomationJavaライブラリ[Aspose.TotalforJava]（https://products.aspose.com/total/java/）を使用すると、いくつかの簡単な手順でレンダリングプロセスを自動化できます。 [Aspose.Words for Java]（https://products.aspose.com/words/java/）を使用してODTファイルをロードし、HTMLに変換できます。その後、強力なPowerPoint操作Java API [Aspose.Slides for Java]（https://products.aspose.com/slides/java/）を使用して、新しいプレゼンテーションを作成し、その中にHTMLコンテンツを書き込んで、PPSとして保存できます。 。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してODTをPPSに変換する方法" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Odtument）クラスを使用してODTファイルを開きます
2. [save]（https://apireference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してODTファイルをHTMLに変換します）） 方法
3.新しい[プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）オブジェクトを初期化します
5. BufferedReaderを使用してHTMLファイルからコンテンツを抽出し、プレゼンテーションファイルにコンテンツを書き込みます
6. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-）メソッドを使用してドキュメントをPPSに保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
ODTからPPSファイルへの変換では、[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose）から直接Aspose.TotalforJavaを簡単に使用できます。 / aspose-total）ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用すると、パスワードで保護されたODTドキュメントをPPSに変換することもできます。入力ODTドキュメントがパスワードで保護されている場合、パスワードを使用せずにPPS形式に変換することはできません。暗号化されたドキュメントを開くには、LoadOptionsオブジェクトに正しいパスワードを設定し、それをOdtumentコンストラクターに渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-ppsm/" name="ODT に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-pot/" name="ODT に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-powerpoint/" name="ODT に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-pptx/" name="ODT に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-potx/" name="ODT に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-pptm/" name="ODT に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-potm/" name="ODT に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-pps/" name="ODT に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-ppsx/" name="ODT に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-ppt/" name="ODT に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-csv/" name="ODT に CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-dif/" name="ODT に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-fods/" name="ODT に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-ods/" name="ODT に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-sxc/" name="ODT に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-tsv/" name="ODT に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xlam/" name="ODT に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xltm/" name="ODT に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-excel/" name="ODT に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xls/" name="ODT に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xlsb/" name="ODT に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xlsm/" name="ODT に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xlsx/" name="ODT に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xlt/" name="ODT に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xltm/" name="ODT に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odt-to-xltx/" name="ODT に XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}