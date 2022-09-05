---
title: C++ によるドキュメント変換 
url: /ja/cpp/conversion/
description: C++ API を使用して、Word、Excel、PowerPoint、PDF、JSON、画像などのさまざまなドキュメント形式を変換します。 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ を使用したドキュメント変換" h2="C++ ライブラリを使用して、Microsoft<sup>&reg;</sup> Office Word、Excel、PowerPoint、PDF、画像、およびその他のさまざまな形式を変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ ライブラリ](https://products.aspose.com/total/cpp/) は、ドキュメント変換の問題を解決し、開発者は、新しく開発されたアプリケーションまたは既存のアプリケーションに API を統合することで、ドキュメント管理および操作ソリューションを簡単に自動化できます。 C++ プログラマーは、ソフトウェアに依存することなく、ソリューション内でさまざまな形式のドキュメントの作成、編集、変換などの機能を追加できます。 txt から PDF、SVG から PNG、XLSX から CSV、JSON から CSV、Word から PDF、HTML から PDF などの一般的なケースはほとんどありませんが、簡単に変換できます。 さらに、以下にリストされている API 取引のいくつかのケースと、関連する変換ケースのいくつかのリンクが示されています。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word を Excel に変換する" %}}
Total C++ API は、Microsoft Word DOC/DOCX から Excel への変換をサポートしています。  処理は、[ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document) クラス参照を使用して Word DOC/DOCX ファイルを読み込み、[保存](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) メンバー関数を使用して、最初に HTML に変換します。 次に、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) クラス リファレンスを使用して HTML ドキュメントを読み込み、[Save](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) メンバー関数を使用して、ドキュメントを Excel 形式で保存します。 

{{% blocks/products/pf/feature-page-code h3="C++ - Word から Excel への変換" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDFからWordへの変換" %}}
C++ 変換ライブラリは、PDF から word DOC、DOCX およびその他の形式への変換もサポートしています。 PDF を RTF にレンダリングする場合を考えると、これは 2 段階のプロセスです。まず PDF を Word DOC/DOCX 形式に変換し、次にそれを RTF にレンダリングします。 これには、[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) クラス リファレンスを使用して PDF ファイルをロードし、[Save](https://reference.aspose) を呼び出す手順が含まれます。 .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) PDF を Word に変換するメンバー関数。 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Aspose.Words API のクラス リファレンスを使用して Word DOC / DOCX ファイルを再度読み込み、次を使用して RTF 形式で保存します。 [保存](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) メンバー関数。

{{% blocks/products/pf/feature-page-code h3="C++ - PDFからWordへの変換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="JSON を Word に変換する" %}}
JSON 変換の場合、C++ API は、JSON から Word、Json から PowerPoint、Word から JSON など、さまざまな組み合わせをサポートしています。 Word 変換の場合を考えると、プロセスは、新しい [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) オブジェクトを使用してファイルから有効な JSON データを読み取り、呼び出します。 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) メソッドで JSON を PDF ファイルとして保存します。 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) クラスを使用して保存したファイルを読み込み、[Save](https://reference) を使用して Word ドキュメント形式で保存します。 .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) メソッド。
{{% blocks/products/pf/feature-page-code h3="C++ - JSON から Word への変換" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}