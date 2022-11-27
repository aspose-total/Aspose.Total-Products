---
title: Python を使用して Excel ファイルを更新する 

description: Python アプリケーション内に Microsoft Office をインストールせずに Microsoft Excel XLSX、XLS、CSV ドキュメントを編集
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python 経由で Excel ドキュメントを更新する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Python アプリケーション内の Microsoft Excel XLSX、XLS ファイルを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
学生データ、患者記録、倉庫品目リストなどの Excel ファイルに保存されているデータを、会社のソフトウェアを介して更新することは組織にとって一般的です。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API は、ソフトウェアを介してスプレッドシートを変更する機能を提供します。 プログラマーは、API を統合し、数行のコードを記述することで、変更機能を使用してソフトウェアを強化できます。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) パッケージの一部である [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API は、この変更プロセスを容易にします。以下は、Excel ドキュメントを更新するプロセスです。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して Excel ドキュメントを更新する" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API は、Excel スプレッドシートの読み込みを処理する Workbook クラスを提供します。 プロセスは簡単です。 ソース ファイルをパラメーターとして指定して、[Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) クラス オブジェクトを作成します。 [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) メソッドを使用して、インデックスを提供することにより、関連するワークシートにアクセスします。 [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) メソッドを呼び出してアクセスしたセルのコンテンツを変更し、最後に save() メソッドを呼び出してドキュメントを保存します。

{{% blocks/products/pf/feature-page-code h3="Python - Excel ドキュメントの更新" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="アップデート">}}