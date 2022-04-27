---
title: Java経由でDOCMをPOTMに変換する
description: MicrosoftWordやPowerPointを使用せずにDOCMをPOTMにエクスポートするJavaAPI
url: /ja/java/conversion/docm-to-potm/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: POTM
otherformats: POWERPOINT PPTM POT PPTX POTX PPS PPSM PPSX POTM PPT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でDOCMをPOTMに変換する" h2="Microsoft<sup>＆reg;</sup> PowerPointまたはWordを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内でオンプレミスのJavaAPIを使用することによるDOCMからPOTMへの変換" >}}
{{% blocks/products/pf/feature-page-summary %}}
多くの場合、開発者はプログラムでDOCMファイルをPOTMに変換する必要があります。 FileAutomationJavaライブラリ[Aspose.TotalforJava]（https://products.aspose.com/total/java/）を使用すると、いくつかの簡単な手順でレンダリングプロセスを自動化できます。 [Aspose.Words for Java]（https://products.aspose.com/words/java/）を使用してDOCMファイルをロードし、HTMLに変換できます。その後、強力なPowerPoint操作Java API [Aspose.Slides for Java]（https://products.aspose.com/slides/java/）を使用して、新しいプレゼンテーションを作成し、その中にHTMLコンテンツを書き込んで、POTMとして保存できます。 。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してDOCMをPOTMに変換する方法" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Docmument）クラスを使用してDOCMファイルを開きます
2. [save]（https://apireference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してDOCMファイルをHTMLに変換します）） 方法
3.新しい[プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）オブジェクトを初期化します
5. BufferedReaderを使用してHTMLファイルからコンテンツを抽出し、プレゼンテーションファイルにコンテンツを書き込みます
6. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-）メソッドを使用してドキュメントをPOTMに保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
DOCMからPOTMファイルへの変換では、[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose）から直接Aspose.TotalforJavaを簡単に使用できます。 / aspose-total）ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用すると、パスワードで保護されたDOCMドキュメントをPOTMに変換することもできます。入力DOCMドキュメントがパスワードで保護されている場合、パスワードを使用せずにPOTM形式に変換することはできません。暗号化されたドキュメントを開くには、LoadOptionsオブジェクトに正しいパスワードを設定し、それをDocmumentコンストラクターに渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-ppsm/" name="DOCM に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-pot/" name="DOCM に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-powerpoint/" name="DOCM に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-pptx/" name="DOCM に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-potx/" name="DOCM に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-pptm/" name="DOCM に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-potm/" name="DOCM に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-pps/" name="DOCM に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-ppsx/" name="DOCM に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-ppt/" name="DOCM に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-csv/" name="DOCM に CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-dif/" name="DOCM に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-fods/" name="DOCM に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-ods/" name="DOCM に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-sxc/" name="DOCM に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-tsv/" name="DOCM に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlam/" name="DOCM に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xltm/" name="DOCM に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-excel/" name="DOCM に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xls/" name="DOCM に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlsb/" name="DOCM に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlsm/" name="DOCM に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlsx/" name="DOCM に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlt/" name="DOCM に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xltm/" name="DOCM に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xltx/" name="DOCM に XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}