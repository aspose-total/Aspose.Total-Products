---
title: Python を使用して TSV ファイルを更新する
description: Microsoft Excel を使用せずに、Python アプリケーションで TSV ドキュメントを変更します。 

family: total
platformtag: Python
feature: update
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python 経由で TSV ファイルを更新する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Python アプリケーションを介して TSV スプレッドシートを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Python アプリケーションを介して TSV ファイルを更新しようとしている開発者は誰ですか? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API は、更新プロセスの自動化に役立ちます。 これは、Microsoft Excel ファイルを含むさまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) パッケージの一部である ASPOSE.CELL API は、この変更プロセスを容易にします。 以下は、TSV ドキュメントを更新するプロセスです。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で TSV ファイルを更新する方法" %}}

- ソース TSV ファイルをパラメーターとして持つ新しい [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) クラス オブジェクトを作成します。
- [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) メソッドを使用した関連ワークシートへのアクセス
- [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) メソッドを使用して、アクセスしたセルに新しいデータを挿入します
- パスをパラメーターとしてファイルを渡すことにより、save() メソッドを使用してファイルを .tsv ファイルとして保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変更要件" %}}

- TSV の変更については、プロジェクト内の API を PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) から直接参照します。
- または、次の pip コマンド ```pip install aspose.cells``` を使用します。 
- さらに、[ダウンロード](https://releases.aspose.com/cells/python-java) セクションから API パッケージをダウンロードします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="コード - Python で TSV ファイルを更新する" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}