---
title: Python を使用して XLS を DOC に変換する
description: Microsoft Office を使用しない Python アプリケーションでの XLS から DOC への変換 

family: total
platformtag: Python
feature: conversion
informat: XLS
outformat: DOC
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でXLSをDOCに変換" h2="Microsoft Excel<sup>&reg;</sup> または Word をインストールせずに、Python アプリケーションで XLS から DOC への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に XLS から DOC への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 XLS や DOC ファイルなど、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。 まず [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API を使用して XLS ファイルを HTML に変換します。 その後、Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用して、作成した HTML を任意の Microsoft Word 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XLS を DOC に変換する方法" %}}
- **ステップ1** Workbook クラスを使用してソース XLS ファイルを開く
- ファイル名と目的のディレクトリ パスを指定して、save(file, SaveFormat.HTML) メソッドを使用して XLS ファイルを HTML に保存します。
-  **ステップ2** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスのインスタンスを含む HTML ファイルをロードする
-  出力 DOC ファイルのパスを指定して、`save` メソッドを呼び出します。 したがって、XLS ファイルは指定されたパスで DOC に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XLS から DOC への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) および [Aspose.Words](https://pypi.org/project/aspose-words/))
-  または、次の pip コマンド ```pip install aspose-cells-python``` および ```pip install aspose.words``` を使用します。
-  さらに、Microsoft Windows または Linux ベースの OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) および [Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合、gcc および libpython の追加要件を確認し、[ステップバイステップの説明](https://docs.aspose.com/words/python-net/installation/) に従います。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で XLS を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を DOC に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-word/" name="XLS に WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-doc/" name="XLS に DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-docx/" name="XLS に DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-docm/" name="XLS に DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-dot/" name="XLS に DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-dotm/" name="XLS に DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-dotx/" name="XLS に DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-mobi/" name="XLS に MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-odt/" name="XLS に ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-ott/" name="XLS に OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-rtf/" name="XLS に RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xls-to-wordml/" name="XLS に WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}