---
title: Python を使用して WORD を CSV に変換する
description: Microsoft Word や Excel を使用せずに、Python アプリケーションで WORD から CSV への変換 

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: CSV
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でWORDをCSVに変換" h2="Microsoft Word<sup>&reg;</sup> または Excel をインストールせずに、Python アプリケーションで WORD から CSV への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORD から CSV への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。まず [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を使用して WORD ファイルを HTML に変換します。 その後、Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) を使用して、作成した HTML を目的の Microsoft Excel 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORD を CSV に変換する方法" %}}
- **ステップ 1** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORD ファイルを開く
- ファイル名と目的のディレクトリ パスを指定して、[Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) メソッドを使用して WORD ファイルを HTML に保存します。
-  **ステップ 2** ファイルと LoadOptions をパラメーターとして持つ Workbook クラスのインスタンスを含む HTML ファイルをロードする
-  出力 CSV ファイルのパスを指定して、`save` メソッドを呼び出します。 したがって、WORD ファイルは指定されたパスで CSV に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORD から CSV への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  または、次の pip コマンド ```pip install aspose.words``` および ```pip install aspose-cells-python``` を使用します。 
-  さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[ステップバイステップの説明](https://docs.aspose.com/words/python-net/installation/) に従います。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で WORD を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を CSV に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-excel/" name="WORD に EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xls/" name="WORD に XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xlsx/" name="WORD に XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-csv/" name="WORD に CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-dif/" name="WORD に DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-fods/" name="WORD に FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-ods/" name="WORD に ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-sxc/" name="WORD に SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-tsv/" name="WORD に TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xlam/" name="WORD に XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xlsb/" name="WORD に XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xlt/" name="WORD に XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xltm/" name="WORD に XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xltx/" name="WORD に XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/word-to-xlsm/" name="WORD に XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}