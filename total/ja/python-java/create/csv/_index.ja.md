---
title: Python で CSV を作成する
description: Microsoft Office を使用せずに、Python アプリケーションを使用して CSV ファイルを生成します。 

family: total
platformtag: Python
feature: create
informat: CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して CSV を作成する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Python アプリケーションを介して CSV を生成します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Python アプリケーションを介して CSV ファイルを作成しようとしている開発者は誰ですか? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API は、作成プロセスの自動化に役立ちます。 これは、Microsoft Office ファイルや画像など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) パッケージの一部である [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API により、この生成プロセスが容易になります。 以下、作成過程です。 さらに、開発者は、CSV ファイルを変更するためにアプリケーションを簡単に拡張できます。 Python プロセスを使用して CSV ファイルを更新する方法は、Workbook オブジェクトの作成時にパラメータとして既存のファイルが必要であることを除いて同じです。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で CSV ファイルを作成する方法" %}}

- ファイルFormatType をパラメーターとして持つ新しい [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) クラス オブジェクトを作成します。
- [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) メソッドを使用して、必要な [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) へのアクセスを取得します
- [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)メソッドを使用してアクセスしたセルにデータを挿入します
- パラメータとしてパスを指定してファイルを渡すことにより、[save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) を使用してドキュメントを .csv ファイルとして保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="作成要件" %}}

- CSV 生成の場合、プロジェクト内の API を PyPI から直接参照 ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- または、次の pip コマンド ```pip install aspose.cells``` を使用します。` 
- さらに、[downloads](https://releases.aspose.com/cells/python-java) セクションから API パッケージをダウンロードします。 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で CSV を作成する" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}