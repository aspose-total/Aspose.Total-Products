---
title: CGMをPCLにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してCGMをPCLに変換する
url_ignore: /ja/java/conversion/cgm-to-pcl/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PCL
otherformats: DOTX RTF WORDML OTT MARKDOWN MHTML PS DOTM ODT XAMLFLOW PCL FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してCGMをPCLに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにCGMをPCLにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、CGMをPCLに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してCGMファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをPCLに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをPCLに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してCGMファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してCGMをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをPCL形式で保存し、PCLを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-pcl.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
CGMをPCLに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してパスワードで保護されたCGMドキュメントを開く" %}}
入力ドキュメントをPCLファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 PCLをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}