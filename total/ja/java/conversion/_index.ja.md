---
title: Javaによるファイル形式の変換 
url: /ja/java/conversion/
description: Microsoft Office Word、Excel、PowerPoint、Outlook、PDF、HTML、3D画像、図、ビデオ形式、およびその他のさまざまな形式を、わずか数行のJavaコードで変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaによるファイル形式の変換" h2="他のソフトウェアを使用せずに、Microsoft <sup>＆reg; </ sup> Officeドキュメント、PDF、画像、HTML、およびその他の複数のファイルを変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library]（https://products.aspose.com/total/java/）は、ドキュメント操作ソリューションをゼロから開発したり、既存のアプリケーションを拡張してドキュメント管理を簡単に処理したりすることを高速化します。 APIは、Microsoft Officeドキュメントを作成、編集、変換するだけでなく、PDF、HTML、画像TIFF、JPG、PNG、BMP、SVG、電子メールファイル、ビデオ形式、3D、CADなどを処理します。これは、Java J2SE、J2EE、J2MEアプリケーション内にソフトウェアの依存関係がないドキュメント管理および操作ソリューションAPIのコレクションです。プログラマーは、Javaベースのアプリケーション内で最も一般的な形式を簡単に作成、更新、レンダリング、印刷、および変換できます。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="WordからExcelへの変換" %}}
Total APIは、Microsoft Word形式の相互変換だけでなく、WordからExcel、PDF、HTML、画像、EPUB、Markdown、XPSへの変換もサポートしています。変換のプロセスは簡単です。 **WordからExcel**への変換の場合を考えてみましょう。 [Document]（https://apireference.aspose.com/words/java/com.aspose.words/Document）クラスを使用してMicrosoft Wordファイルをロードし、[Save method]（https： //apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions））。次に、[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用して変換されたHTMLドキュメントを開き、[Save]（https：/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions））メソッド。
 開発者は[WordをPDFに変換]（https://products.aspose.com/words/java/conversion/word-to-pdf/）することもできます。


{{% blocks/products/pf/feature-page-code h3="Java WordからExcelへの変換" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="PDFを画像に変換する" %}}
APIは、PDFをJPEG2000、EMZ、WMZ、TGA、PSD、DXF、WMF、SVGZ、APNG、DICOM、Powerpoint、Excelなどの形式の画像に変換することをサポートしています。 PDFから画像への変換では、JPG画像をターゲットファイルと考えてみましょう。プロセスは、Documentクラスを使用してPDFファイルをロードし、[JpegDeviceクラス]（https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice）オブジェクトを初期化し、[プロセス]（https ：//apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1）メソッド
[Image]（https://apireference.aspose.com/imaging/java/aspose.imaging/image）クラスを使用してJPEGファイルをロードし、最後にSaveメソッドを呼び出します。

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="PowerPointをExcelファイルに変換する" %}}

Microsoft PowerPointファイルを、Excel Word、MHTML、メインのAspose.Total forJavaAPIに含まれる関連するサブAPIなどのさまざまなファイルに変換します。 PowerPointファイルをExcelドキュメントに変換するプロセス、[プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用してPowerPointファイルをロードし、**PowerPointをHTML**に変換する[保存]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-）メソッドを使用します。次に、[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用して変換されたHTMLドキュメントをロードし、[save]（https：/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions））メソッド。 **PowerPointからWord**への変換のコードもリストされています。

{{% blocks/products/pf/feature-page-code h3="JavaPowerPointからExcelへの変換" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="JavaPowerPointからWordへの変換" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}