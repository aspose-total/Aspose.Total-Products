---
title: C＃によるファイル形式の変換 

description: Microsoft Word、Excel、PowerPoint、Outlook、PDF、HTML、3D画像、図、ビデオ形式、およびその他の多くの一般的なファイルを、わずか数行のC＃コードで変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C＃によるファイル形式の変換 .NET" h2="Microsoft <sup>&reg;</sup> Officeファイル、PDF、画像、HTML、およびその他のさまざまな形式を、他のソフトウェアを使用せずに変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NETトータルライブラリ](https://products.aspose.com/total/net/) ドキュメント管理ソリューションをゼロから開発するか、既存のアプリケーションを拡張してドキュメント操作を簡単に処理できるようにします。 APIは、Microsoft Officeドキュメントを管理するだけでなく、PDF、HTML、画像TIFF、JPG、PNG、BMPおよびSVG、電子メールファイル、ビデオ形式、GISデータ形式なども処理します。これは、ソフトウェアに依存することなく、ドキュメント管理および操作ソリューションAPIの完全なセットです。プログラマーは、.NETベースのアプリケーション内で最も一般的な形式を簡単に作成、更新、レンダリング、印刷、および変換できます。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="WordをPDFに変換" %}}
Total APIは、Microsoft Word形式の相互変換だけでなく、WordからPDF、HTML、画像、EPUB、Markdown、XPSへの変換もサポートしています。変換のプロセスは簡単です。 Documentクラスを介してドキュメントをロードし、ターゲット形式でSaveメソッドを呼び出すだけです。とても簡単です。開発者は、**WordからPDF**にコードを統合する前に、[変換結果]（https://products.aspose.com/words/net/conversion/word-to-pdf/）を確認できます。


{{% blocks/products/pf/feature-page-code h3="C＃-WordからPDFへの変換" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="PDFを画像に変換する" %}}
APIは、PDFから画像、Powerpoint、Excel、およびその他の形式への変換をサポートしています。 PDFから画像への変換では、JPG画像をターゲットファイルと考えてみましょう。プロセスは、Documentクラスを使用してPDFファイルをロードし、[JpegDeviceクラス]（https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice）オブジェクトを初期化し、[プロセス]（https ：//apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1）メソッド
[Image]（https://reference.aspose.com/imaging/net/aspose.imaging/image）クラスを使用してJPEGファイルをロードし、最後にSaveメソッドを呼び出します。

{{% blocks/products/pf/feature-page-code h3="C＃-PDFから画像への変換" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="ExcelをWordとPowerPointに変換する" %}}

Microsoft Excel形式をWordやPowerPointなどのさまざまなファイルに変換するために、メインのAspose.Total for.NETAPIに含まれる関連するサブAPI。 ExcelファイルをWord文書に変換するプロセス、[Workbook]（https://reference.aspose.com/cells/net/aspose.cells/workbook）クラスを使用してEXCELファイルをロードし、最初にEXCELをPDFに変換し、SaveFormatをAutoに設定します。次に、Documentクラスを使用して変換されたPDFファイルをロードし、Saveメソッドを呼び出して、Doc、DocxをSaveFormatとして設定します。 Microsoft**ExcelからPowerpoint**への変換用のコードもリストされています。

{{% blocks/products/pf/feature-page-code h3="C＃-JSONからExcelへの変換" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C＃-ExcelからJSONへの変換" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}