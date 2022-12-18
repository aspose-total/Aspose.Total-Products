---
title: Python を使用して PPTM を EXCEL に変換する
description: Microsoft Office を使用しない Python アプリケーションでの PPTM から EXCEL への変換 

family: total
platformtag: Python
feature: conversion
informat: PPTM
outformat: EXCEL
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でPPTMをEXCELに変換" h2="Microsoft PowerPoint<sup>&reg;</sup> または Excel をインストールせずに、Python アプリケーションで PPTM から EXCEL への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に PPTM から EXCEL への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 PPTM や EXCEL ファイルなど、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。 まず [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API を使用して PPTM ファイルを HTML に変換します。 その後、Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) を使用して、作成した HTML を目的の Microsoft Excel 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で PPTM を EXCEL に変換する方法" %}}
- **ステップ1** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) クラス インスタンスを使用してソース PPTM ファイルを開く 
- ファイル名と目的のディレクトリ パスを指定して、[save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) メソッドを使用して PPTM ファイルを HTML に保存します。
-  **ステップ2** Workbook クラスのインスタンスを含む HTML ファイルをロードする
-  出力 EXCEL ファイルのパスを指定して、`save` メソッドを呼び出します。したがって、PPTM ファイルは指定されたパスで EXCEL に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- PPTM から EXCEL への変換には、Python 3.5 以降が必要です。
- PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) および [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) から直接プロジェクト内の API を参照します。
-  または、次の pip コマンド ```pip install aspose.slides``` および ```pip install aspose-cells-python``` を使用します。
-  さらに、Microsoft Windows または Linux ベースの OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) および [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) の詳細を参照)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で PPTM を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を EXCEL に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}