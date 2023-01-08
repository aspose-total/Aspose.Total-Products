---
title: Python を使用して XLSX を RTF に変換する
description: Microsoft Office を使用しない Python アプリケーションでの XLSX から RTF への変換 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: RTF
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でXLSXをRTFに変換" h2="Microsoft Excel<sup>&reg;</sup> または Word をインストールせずに、Python アプリケーションで XLSX から RTF への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に XLSX から RTF への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 XLSX や RTF ファイルなど、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。 まず [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API を使用して XLSX ファイルを HTML に変換します。 その後、Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用して、作成した HTML を任意の Microsoft Word 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XLSX を RTF に変換する方法" %}}
- **ステップ1** Workbook クラスを使用してソース XLSX ファイルを開く
- ファイル名と目的のディレクトリ パスを指定して、save(file, SaveFormat.HTML) メソッドを使用して XLSX ファイルを HTML に保存します。
-  **ステップ2** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスのインスタンスを含む HTML ファイルをロードする
-  出力 RTF ファイルのパスを指定して、`save` メソッドを呼び出します。 したがって、XLSX ファイルは指定されたパスで RTF に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XLSX から RTF への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) および [Aspose.Words](https://pypi.org/project/aspose-words/))
-  または、次の pip コマンド ```pip install aspose-cells-python``` および ```pip install aspose.words``` を使用します。
-  さらに、Microsoft Windows または Linux ベースの OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) および [Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合、gcc および libpython の追加要件を確認し、[ステップバイステップの説明](https://docs.aspose.com/words/python-net/installation/) に従います。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で XLSX を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を RTF に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-word/" name="XLSX に WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-doc/" name="XLSX に DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-docx/" name="XLSX に DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-docm/" name="XLSX に DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-dot/" name="XLSX に DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-dotm/" name="XLSX に DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-dotx/" name="XLSX に DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-mobi/" name="XLSX に MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-odt/" name="XLSX に ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-ott/" name="XLSX に OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-rtf/" name="XLSX に RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlsx-to-wordml/" name="XLSX に WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}