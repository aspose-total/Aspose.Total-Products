---
title: Python を使用して XLT を DOTX に変換する
description: Microsoft Office を使用しない Python アプリケーションでの XLT から DOTX への変換 

family: total
platformtag: Python
feature: conversion
informat: XLT
outformat: DOTX
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でXLTをDOTXに変換" h2="Microsoft Excel<sup>&reg;</sup> または Word をインストールせずに、Python アプリケーションで XLT から DOTX への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に XLT から DOTX への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 XLT や DOTX ファイルなど、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。 まず [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API を使用して XLT ファイルを HTML に変換します。 その後、Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用して、作成した HTML を任意の Microsoft Word 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XLT を DOTX に変換する方法" %}}
- **ステップ1** Workbook クラスを使用してソース XLT ファイルを開く
- ファイル名と目的のディレクトリ パスを指定して、save(file, SaveFormat.HTML) メソッドを使用して XLT ファイルを HTML に保存します。
-  **ステップ2** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスのインスタンスを含む HTML ファイルをロードする
-  出力 DOTX ファイルのパスを指定して、`save` メソッドを呼び出します。 したがって、XLT ファイルは指定されたパスで DOTX に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XLT から DOTX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) および [Aspose.Words](https://pypi.org/project/aspose-words/))
-  または、次の pip コマンド ```pip install aspose-cells-python``` および ```pip install aspose.words``` を使用します。
-  さらに、Microsoft Windows または Linux ベースの OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) および [Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合、gcc および libpython の追加要件を確認し、[ステップバイステップの説明](https://docs.aspose.com/words/python-net/installation/) に従います。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で XLT を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を DOTX に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-word/" name="XLT に WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-doc/" name="XLT に DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-docx/" name="XLT に DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-docm/" name="XLT に DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-dot/" name="XLT に DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-dotm/" name="XLT に DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-dotx/" name="XLT に DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-mobi/" name="XLT に MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-odt/" name="XLT に ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-ott/" name="XLT に OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-rtf/" name="XLT に RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/xlt-to-wordml/" name="XLT に WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}