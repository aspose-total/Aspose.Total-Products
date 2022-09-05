---
title: Python によるドキュメント変換 
url: /ja/python-net/conversion/
description: Microsoft Word 形式の DOC、DOCX を PDF、画像などに変換したり、プレゼンテーション スライド、電子メール メッセージ、3D 画像を数行の Python コードで変換したりできます。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python API を使用したドキュメント変換" h2=".NET 経由で Aspose.Words for Python を使用して、Microsoft<sup>&reg;</sup> Office Word、PDF、画像、およびその他のさまざまな形式を変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python APIs](https://products.aspose.com/total/python-net/) は、ドキュメント自動化ソリューションをゼロから開発するか、既存のアプリケーションを強化して、ドキュメント、プレゼンテーション、電子メール、および 3D ファイルを作成、編集、または変換する速度を上げます。 Python API は、Microsoft Office Word とプレゼンテーション スライドを処理するだけでなく、PDF、HTML、画像、電子メール ファイルなども処理します。 API はソフトウェアに依存せず、ドキュメント管理および操作ソリューションの完全なセットです。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word を PDF に変換する" %}}
Total Python API は、Microsoft Word から PDF、画像、Markdown、HTML への複数の変換をサポートしています。 API により、Word ドキュメントを PDF に変換するプロセスが簡単になり、DOC、DOCX ファイルのドキュメントに近い品質の出力が得られます。 プロセスは、DOC または DOCX ファイルを [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) オブジェクトにロードし、[save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) メソッドとそのディレクトリ パスを対象の PDF 形式で指定します。 とても簡単です。 PDF 1.7 や 1.5 などの PDF 規格を指定する必要がある場合、API は設定用に [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.Saving/pdfcompliance/) 列挙を提供します。 [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.Saving/pdfsaveoptions/)。 

{{% blocks/products/pf/feature-page-code h3="Python - Word から PDF への変換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word から画像への変換" %}}
単語から画像への変換は、Python API の antho 機能です。 変換だけでなく、明るさ、コントラスト、水平および垂直解像度などのさまざまな保存オプションを簡単に設定できます。プロセスは、 Document オブジェクトを介してドキュメントを読み込み、指定されたパスを持つ目的の画像ファイルの拡張子で保存メソッドを呼び出します。 さまざまな保存オプションを指定するために、API には [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.Saving/imagesaveoptions/)、[FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.Saving/fixedpagesaveoptions/) または [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.Saving/saveoptions/) クラスを必要なシナリオで使用されます。 以下のコード サンプルは、いくつかの追加設定を適用して最初のドキュメント ページのプレビューを作成する方法を示しています。

{{% blocks/products/pf/feature-page-code h3="Python - 単語から画像への変換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint を Word に変換する" %}}
Python API は、Microsoft PowerPoint PPT / PPTX から Word DOC / DOCX ファイルへの変換をサポートしています。 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) と [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用してこの変換を実行しました。 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) を使用して PPT/PPTX ファイルを読み込みます。 Words ドキュメント クラス オブジェクトを取得します。各スライドを反復処理し、スライド イメージを生成して挿入し、スライドの図形を反復処理してスライド テキストを挿入します。

{{% blocks/products/pf/feature-page-code h3="Python - PowerPoint スライドから Word への変換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}