---
title: .NET を使用して Excel ファイルを更新する 

description: C# .NET ベースのアプリケーションで Microsoft Office をインストールせずに、Microsoft Excel XLSX、XLS、CSV ドキュメントを編集します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1=".NET 経由で Excel ドキュメントを更新する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、.NET ベースのアプリケーション内で Microsoft Excel XLSX、XLS ファイルを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
学生データ、患者記録、倉庫品目リストなどの Excel ファイルに保存されているデータを、会社のソフトウェアを介して更新することは組織にとって一般的です。 [Aspose.Total for .NET](https://products.aspose.com/total/net/) API は、ソフトウェアを使用してスプレッドシートを変更する機能を提供します。 プログラマーは、数行の API コードを記述するだけで、変更機能を使用してソフトウェアを強化できます。 [Aspose.Total for .NET](https://products.aspose.com/total/net/) パッケージの一部である [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API により、この変更プロセスが容易になります。 以下は、Excel ドキュメントを更新するプロセスです。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2=".NET を使用して Excel ドキュメントを更新する" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API は、Excel スプレッドシートの読み込みを処理する Workbook クラスを提供します。 プロセスは簡単です。 ソース ファイルをパラメーターとして指定して、[Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) オブジェクトを作成します。 [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) メソッドを使用してインデックスを提供することにより、関連するワークシートにアクセスします。 [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) メソッドを使用して、アクセスしたセルのコンテンツを変更し、最後に save() メソッドを呼び出してドキュメントを保存します。

{{% blocks/products/pf/feature-page-code h3=".NET コード - Excel ドキュメントの更新" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="アップデート">}}