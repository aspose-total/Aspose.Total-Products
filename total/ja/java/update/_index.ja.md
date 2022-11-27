---
title: Java を使用して Excel ファイルを更新する 

description: Java ベースのアプリケーション内に Microsoft Office をインストールせずに、Microsoft Excel XLSX、XLS、CSV ドキュメントを編集します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java 経由で Excel ドキュメントを更新する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Java ベースのアプリケーション内で Microsoft Excel XLSX、XLS ファイルを変更します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
学生データ、患者記録、倉庫品目リストなどの Excel ファイルに保存されているデータを、会社のソフトウェアを介して更新することは組織にとって一般的です。 [Aspose.Total for Java](https://products.aspose.com/total/java/) API は、独自のソフトウェアを使用してスプレッドシートを変更する機能を提供します。 プログラマーは、数行の API コードを記述するだけで、変更機能を使用してソフトウェアを強化できます。 [Aspose.Total for Java](https://products.aspose.com/total/java/) パッケージの一部である [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API により、この変更プロセスが容易になります。 以下は、Excel ドキュメントを更新するプロセスです。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Java を使用して Excel ドキュメントを更新する" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API は、Excel スプレッドシートの読み込みを処理する [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) クラスを提供します。 プロセスは簡単です。 ソース ファイルをパラメーターとして指定して、Workbook クラス オブジェクトを作成します。 [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) メソッドを使用して、関連するワークシートと関連するセルにアクセスします。 [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) メソッドを使用して、アクセスしたセルのコンテンツを変更し、最後に save() メソッドを呼び出してドキュメントを保存します。

{{% blocks/products/pf/feature-page-code h3="Java コード - Excel ドキュメントの更新" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="アップデート">}}