---
title: AndroidのDOCにXLSをエクスポートする または無料のオンライン コンバーターを使用
description: MicrosoftWordを使用せずにXLSをDOCに変換するAndroidAPI またはオンライン。コードを統合する前に、無料の XLS から DOC へのオンライン コンバーターをすばやくテストします。

family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: DOC
otherformats: DOCX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndroid上のDOCにXLSをレンダリングする またはオンラインアプリ" h2="Microsoft <sup>&reg;</sup> Excelを使用せずに、Androidアプリケーション内でXLSをDOCに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)は、強力なファイル自動化APIのパッケージです。 2つのAPIを使用することで、Androidアプリケーション内でXLSからDOCへの変換機能を統合できます。最初のステップでは、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用してXLSをPDFにエクスポートできます。その後、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用して、PDFをDOCに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSをDOCにエクスポートするAndroidAPI" %}}
1. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSファイルを開きます
2. XLSをPDFに変換し、SaveFormatをAUTOに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをDOC形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/)と[Aspose.Cells for Android via Java](https://docs.aspose.com/cells)をインストールしますアプリケーションの/java/ aspose-cells-for-android-via-java-installation /＃install-asposecells-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLSからDOCへの無料オンラインコンバーター</h3>

<iframe title="xlsからdocへの変換オンラインツール" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=doc&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのXLSファイルからカスタムプロパティを削除する" %}}
ドキュメントの変換とは別に、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)には、他にもたくさんの機能があります。変換プロセスの前に、XLSドキュメントのカスタムプロパティを削除できます。カスタムプロパティを削除するには、[DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String))メソッドを呼び出して、の名前を渡します。削除するドキュメントプロパティ。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>よくある質問</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>オンラインで XLS を DOC に変換するにはどうすればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">XLS変換用のオンラインアプリは上記に統合されています。 XLS から DOC への変換プロセスを開始するには、まず XLS ファイルをインポートします。これには 2 つの方法があります。XLS ファイルを変換ツールにドラッグ アンド ドロップするか、ツールの白い領域内をクリックしてコンピュータを参照し、変換する XLS ファイルを選択します。 XLS ファイルを正常にインポートしたら、[変換] ボタンをクリックして変換プロセスを開始する必要があります。 <br />
変換プロセス中に、XLS ファイルは DOC ファイルに変換されます。変換ツールは魔法のように機能し、プロセスが完了すると、新しく変換された DOC ファイルをダウンロードできるようになります。これは、複雑なソフトウェアや技術的な知識がなくても、ワンクリックで出力 DOC ファイルを簡単に取得できることを意味します。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLS の変換にはどのくらいの時間がかかりますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">このオンライン XLS から DOC へのコンバーターの重要な機能の 1 つは、変換速度が速いことです。ただし、変換プロセスの速度は、主に変換する XLS ファイルのサイズに依存します。小さなサイズの XLS ファイルで作業している場合、変換プロセスはわずか数秒で完了することが期待できます。<br />

さらに、Android App アプリケーション内に変換コードを統合した場合、変換プロセスの速度は、アプリケーションをどのように最適化したかによって異なります。アプリケーションが適切に最適化され、変換プロセスを効率的に処理するように設計されている場合、変換速度は速くなります。一方、アプリケーションがこの目的に最適化されていない場合は、変換プロセスが完了するまでに時間がかかる場合があります。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>無料の Aspose.Total コンバーターを使用して XLS を DOC に変換しても安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろん！ DOC ファイルのダウンロード リンクは、変換後すぐに利用できるようになります。 XLS から DOC へのコンバーターでは、プライバシーとセキュリティを真剣に考えています。お客様のファイルには機密情報や個人情報が含まれていることを理解しているため、ファイルの安全性を確保するためにいくつかの対策を講じています。<br />

まず、アップロードされたすべてのファイルは 24 時間後に自動的に削除されます。つまり、変換プロセスが完了し、変換されたファイルをダウンロードすると、元の XLS ファイルと結果の DOC ファイルがサーバーから削除されます。さらに、ファイルのダウンロード リンクは 24 時間後に機能を停止し、この期間が過ぎると誰もファイルにアクセスできなくなります。<br />

また、ファイルが不正アクセスから確実に保護されるように対策を講じています。変換プロセス中または変換後に誰もあなたのファイルにアクセスすることはできません。また、コンピューターとサーバー間のすべてのデータ転送は暗号化され、安全です。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLS を変換するには、どのブラウザを使用すればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">このオンラインの XLS から DOC へのコンバーターは、Google Chrome、Firefox、Opera、Safari などの最新のブラウザーからアクセスできます。つまり、このツールは、インターネットに接続されている任意のデバイスで簡単に使用でき、特別なソフトウェアや技術的な知識は必要ありません。<br />

ただし、デスクトップ アプリケーションを開発していて、XLS ファイルを DOC ファイルに変換する必要がある場合は、Aspose.Total XLS Conversion API を使用することをお勧めします。この API は、デスクトップ アプリケーション内で XLS ファイルを DOC ファイルにスムーズかつ効率的に変換する方法を提供します。 Aspose.Total XLS Conversion API は、使いやすく、アプリケーションに統合できるように設計されており、高速で信頼性の高い変換プロセスを提供します。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}