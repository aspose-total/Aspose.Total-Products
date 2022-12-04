---
title: Python を使用して DOTX を FODS に変換する
description: Microsoft Word や Excel を使用せずに、Python アプリケーションで DOTX から FODS への変換 

family: total
platformtag: Python
feature: conversion
informat: DOTX
outformat: FODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でDOTXをFODSに変換" h2="Microsoft Word<sup>&reg;</sup> または Excel をインストールせずに、Python アプリケーションで DOTX から FODS への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に DOTX から FODS への変換機能を追加しようとしている Python 開発者向け。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。

主に2段階です。まず [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を使用して DOTX ファイルを HTML に変換します。 その後、Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) を使用して、作成した HTML を目的の Microsoft Excel 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で DOTX を FODS に変換する方法" %}}
- **ステップ 1** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース DOTX ファイルを開く
- ファイル名と目的のディレクトリ パスを指定して、[Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) メソッドを使用して DOTX ファイルを HTML に保存します。
-  **ステップ 2** ファイルと LoadOptions をパラメーターとして持つ Workbook クラスのインスタンスを含む HTML ファイルをロードする
-  出力 FODS ファイルのパスを指定して、`save` メソッドを呼び出します。 したがって、DOTX ファイルは指定されたパスで FODS に変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- DOTX から FODS への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  または、次の pip コマンド ```pip install aspose.words``` および ```pip install aspose-cells-python``` を使用します。 
-  さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[ステップバイステップの説明](https://docs.aspose.com/words/python-net/installation/) に従います。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で DOTX を HTML に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で HTML を FODS に保存する - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}