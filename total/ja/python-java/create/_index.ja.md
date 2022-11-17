---
title: Python を使用して Microsoft Excel ファイルを作成および更新する 

description: Microsoft Office をインストールせずに Microsoft Excel ワークシート レポートを作成する 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して Excel レポートを作成する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Python アプリケーション内で Microsoft Excel SpreadSheets XLS、XLSX ドキュメントを作成および更新します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) は、XLS および XLSX を含む Microsoft Excel 形式でドキュメントを作成、読み取り、および書き込むための Python API です。 この API は [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) パッケージの一部です。 さらに、開発者は、データ、画像、グラフ、ワークシート内のピボット テーブル、およびその他の多くの機能を挿入するためのコードを簡単に作成できます。 Python API は、さまざまな [数式](https://docs.aspose.com/cells/python-java/supported-formula-functions/) の設定、テキストを列に変換、スマート マーカー、動的数式オプションなどの機能もサポートしています。 以下は、スプレッドシートを作成および変更するためのいくつかのサンプル コードです。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して Excel ファイルを作成する方法" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API は、ファイルの作成を処理する Workbook クラスを提供します。 プロセスは簡単です。 Workbook クラス オブジェクトを作成し、インデックスを指定して関連する Worksheet にアクセスします。 putValue メソッドを使用してアクセスしたセルにコンテンツを追加し、最後に save() メソッドを呼び出してドキュメントを特定の名前で保存します。

{{% blocks/products/pf/feature-page-code h3="コード 1 - シンプルな Excel ファイルの作成" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="コード 2 - Microsoft Excel ドキュメント内に画像を挿入する" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して Microsoft Excel ファイルを更新する方法" %}}

Excel ファイルの作成と更新のプロセスは、唯一の違いを除いてほぼ同じです。 違いは、作成プロセス中に空の Workbook オブジェクトが作成され、更新プロセス中に既存の Excel ファイルが必要になることです。 したがって、既存のファイルをパラメーターとして Workbook クラスに渡します。 残りの手順は同じです

{{% blocks/products/pf/feature-page-code h3="コード 3 - Microsoft Excel ドキュメントの更新" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}