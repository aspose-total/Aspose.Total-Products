---
title: Python を使用して PPSX を XLSX に変換する
description: Microsoft Office を使用しない Python アプリケーションでの PPSX から XLSX への変換 

family: total
platformtag: Python
feature: conversion
informat: PPSX
outformat: XLSX
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でPPSXをXLSXに変換" h2="Microsoft PowerPoint<sup>&reg;</sup> または Excel をインストールせずに、Python アプリケーションで PPSX から XLSX への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に PPSX から XLSX への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 PPSX や XLSX ファイルなど、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。 まず [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API を使用して PPSX ファイルを HTML に変換します。 その後、Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) を使用して、作成した HTML を目的の Microsoft Excel 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で PPSX を XLSX に変換する方法" %}}
- **ステップ1** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) クラス インスタンスを使用してソース PPSX ファイルを開く 
- ファイル名と目的のディレクトリ パスを指定して、[save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) メソッドを使用して PPSX ファイルを HTML に保存します。
-  **ステップ2** Workbook クラスのインスタンスを含む HTML ファイルをロードする
-  出力 XLSX ファイルのパスを指定して、`save` メソッドを呼び出します。したがって、PPSX ファイルは指定されたパスで XLSX に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- PPSX から XLSX への変換には、Python 3.5 以降が必要です。
- PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) および [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) から直接プロジェクト内の API を参照します。
-  または、次の pip コマンド ```pip install aspose.slides``` および ```pip install aspose-cells-python``` を使用します。
-  さらに、Microsoft Windows または Linux ベースの OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) および [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) の詳細を参照)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で PPSX を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を XLSX に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-excel/" name="PPSX に Excel" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-xls/" name="PPSX に XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-xlsx/" name="PPSX に XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-xlsb/" name="PPSX に XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-xltx/" name="PPSX に XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-xltm/" name="PPSX に XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-xlsm/" name="PPSX に XLSM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-csv/" name="PPSX に CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/ppsx-to-tsv/" name="PPSX に TSV" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}


      
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}