---
title: Android API によるドキュメント変換 
url: /ja/android-java/conversion/
description: Android 変換 API を使用して、Word、Excel、PowerPoint、HTML、PDF、および画像形式を変換します。 Android は Office docx、xlsx、pptx を PDF に変換します。 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android API を使用したドキュメント変換" h2="Aspose.Total for Android を Java 経由で使用して、Microsoft<sup>&reg;</sup> Office Word、Excel、PowerPoint、PDF、画像、およびその他のさまざまな形式を変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) は、他のソフトウェアに依存することなく、Android アプリケーション向けのドキュメント変換および管理ソリューションを提供します。 プログラマーは、新しく開発されたアプリケーションまたは既存のアプリケーションに API を統合することにより、ドキュメント管理および操作ソリューションを簡単に自動化できます。 API を統合することにより、Programmer は、アプリケーション内でさまざまな形式のドキュメントを作成、編集、または変換する機能を簡単に追加できます。 Android の PDF コンバーター API は、Office DOCX、XLSX、PPTX から PDF へ、またはその逆のような変換ケースを処理します。さらに、以下にリストされている API 取引のいくつかのケースと、関連する変換ケースのいくつかのリンクが示されています。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PDFをCSVに変換" %}}
Total Android API は、PDF から Excel XLSX および CSV への変換をサポートします。これは 2 段階のプロセスです。 合計 2 つの API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) および [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) が関与しています。プロセスは、最初に PDF を Excel XLSX 形式に変換し、次に XLSX を CSV に変換できます。 詳しくは、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) クラスで PDF ファイルを読み込み、[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) メソッド。 次に、[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) クラスを使用してレンダリングされた XLSX ドキュメントをロードし、[save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) メソッド。

{{% blocks/products/pf/feature-page-code h3="Android - PDF から Excel への変換" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel から Word への変換" %}}
Android API は、Excel の変換も処理します。 プロセスは、[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) クラスを使用して EXCEL XLSX ファイルを読み込み、最初に SaveFormat を AUTO に設定して EXCEL を PDF に変換します。 次に、保存した PDF ファイルを [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) クラスを使用して読み込み、[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) メソッドを使用して、ドキュメントを Word DOC/DOCX 形式で保存します。

{{% blocks/products/pf/feature-page-code h3="Android - Excel から Word への変換" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="POWERPOINT を HTML および MHTML に変換する" %}}
Android Total API は PowerPoint ファイルを含むさまざまな形式に対応しているため、プレゼンテーションを HTML および MHTML に変換できます。 プロセスは、[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) クラスを使用して POWERPOINT PPT/PPTX ファイルを読み込み、[save](https://reference.aspose) を呼び出します。 .com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) メソッドを使用して POWERPOINT を HTML に変換します。 さらに、[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) クラスを使用して変換された HTML ドキュメントを読み込み、[save](https://reference.aspose) を呼び出します。 .com/cells/java/com.aspose.cells/) MHTML 変換用のメソッド。 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint スライドから HTML および MHTML への変換" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}