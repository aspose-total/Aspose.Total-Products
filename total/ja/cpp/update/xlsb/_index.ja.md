---
title: C++ を使用して XLSB ファイルを更新する
description: Microsoft Excel を使用せずに C++ アプリケーションで XLSB ドキュメントを変更する.
family: total
platformtag: C++
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ 経由で XLSB ファイルを更新する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、C++ ベースのアプリケーションを介して XLSB スプレッドシートを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

C++ アプリケーション内で XLSB ファイルを更新しようとしているプログラマー向け, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API は、更新プロセスの自動化に役立ちます。 これは、Microsoft Excel ドキュメントを含む複数の形式を扱うさまざまな C++ ライブラリの完全なパッケージです。 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) パッケージの一部である [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API は、この変更プロセスを容易にします。 XLSB ドキュメントを更新するプロセスは、最初にシートにアクセスし、次に C++ を使用して Excel でセル値を更新するだけで簡単です。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ で XLSB ファイルを更新する方法" %}}

- [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) を使用して XLSB ファイルをロードする
- GetIWorksheets()->GetObjectByIndex(0) を使用した関連 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) および GetICells()->GetObjectByIndex を使用した関連セルへのアクセス
- PutValue メソッドを使用して、アクセスしたセルに新しいデータを挿入します
- パラメータとしてパスを指定してファイルを渡し、Save メソッドを使用してファイルを .xlsb ファイルとして保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変更要件" %}}

- XLSB の変更については、Windows および Linux システムの [システム要求](https://docs.aspose.com/cells/cpp/system-requirements/) に従ってください。 
- コマンド ラインから ```nuget install Aspose.Total.Cpp``` としてインストールします。
- または、```Install-Package Aspose.Total.Cpp``` を使用して Visual Studio のパッケージ マネージャー コンソール経由で
- または、[ダウンロード](https://releases.aspose.com/cells/cpp) からオフライン MSI インストーラーまたは DLL を ZIP ファイルで取得します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="コード - C++ での XLSB ファイルの更新" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}