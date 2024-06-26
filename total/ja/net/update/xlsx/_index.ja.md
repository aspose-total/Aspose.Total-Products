---
title: .NET を使用して XLSX ファイルを更新する
description: Microsoft Excel を使用せずに、C# VB.NET アプリケーションで XLSX ドキュメントを変更します。 

family: total
platformtag: .NET
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1=".NET経由でXLSXファイルを更新" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、.NET ベースのアプリケーションを介して XLSX スプレッドシートを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

開発者の場合、.NET アプリケーションを介して XLSX ファイルを更新しようとしているのは誰ですか? [Aspose.Total for .NET](https://products.aspose.com/total/net/) API は、更新プロセスの自動化に役立ちます。 これは、Microsoft Excel ファイルを含むさまざまな形式を扱うさまざまな .NET API の完全なパッケージです。 [Aspose.Total for .NET](https://products.aspose.com/total/net/) パッケージの一部である ASPOSE.CELL API は、この変更プロセスを容易にします。 以下は、XLSX ドキュメントを更新するプロセスです。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET で XLSX ファイルを更新する方法" %}}

- ソース XLSX ファイルをパラメーターとして持つ新しい [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) クラス オブジェクトを作成します。
- [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) メソッドを使用した関連ワークシートおよび関連セルへのアクセス
- [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) メソッドを使用して、アクセスしたセルに新しいデータを挿入します
- パスをパラメーターとしてファイルを渡すことにより、save() メソッドを使用してファイルを .xlsx ファイルとして保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変更要件" %}}

- XLSX の変更には、Microsoft Windows または .NET、.NET Core、Mono、または Xamarin プラットフォームと互換性のある OS
- Microsoft Visual Studio のような開発環境 
- コマンド ラインから ```nuget install Aspose.Cells``` としてインストールするか、Visual Studio のパッケージ マネージャー コンソール経由で ```Install-Package Aspose.Cells``` を使用してインストールします。
- または、[ダウンロード](https://releases.aspose.com/cells/net) からオフライン MSI インストーラーまたはすべての DLL を ZIP ファイルで取得します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="コード - .NET で XLSX ファイルを更新する" offSpacer="" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}