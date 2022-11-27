---
title: C++ を使用して Excel ファイルを更新する 

description: C++ ベースのアプリケーションで Microsoft Office をインストールせずに、Microsoft Excel XLSX、XLS、CSV ドキュメントを編集します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ 経由で Excel ドキュメントを更新する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、C++ ベースのアプリケーション内で Microsoft Excel XLSX、XLS ファイルを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
学生データ、患者記録、倉庫品目リストなどの Excel ファイルに保存されているデータを、会社のソフトウェアを介して更新することは組織にとって一般的です。 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API は、ソフトウェアを使用してスプレッドシートを変更する機能を提供します。 プログラマーは、数行の API コードを記述するだけで、変更機能を使用してソフトウェアを強化できます。 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) パッケージの一部である [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API により、この変更プロセスが容易になります。 以下は、Excel ドキュメントを更新するプロセスです。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="C++ を使用して Excel ドキュメントを更新する" %}}

[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API を使用して、[CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) を使用してソース ドキュメントを読み込みます。 GetIWorksheets()->GetObjectByIndex(0) を使用して [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) にアクセスし、GetICells()->GetObjectByIndex を使用して必要なセルにアクセスします。 PutValue メソッドを使用して、アクセスしたセルの内容を変更します。 最後に、save() メソッドを呼び出してドキュメントを保存します。

{{% blocks/products/pf/feature-page-code h3="C++ コード - Excel ドキュメントの更新" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="アップデート">}}