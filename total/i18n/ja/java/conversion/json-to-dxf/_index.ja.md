---
title: Java経由でJSON形式をDXFに変換する
description: Microsoft PowerPointを使用せずに、JavaでJSONをDXFに解析します
url: /ja/java/conversion/json-to-dxf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DXF
otherformats: DXF WMF WMZ SVGZ TGA JPEG2000 PSD EMZ DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でJSON形式をDXFに変換する" h2="Java J2SE、J2EE、J2MEアプリケーション内でJSON形式をDXFに解析するJava API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を使用すると、2つの簡単な手順で任意のJavaアプリケーション内でJSON形式をDXFに変換できます。まず、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、JSONをJPEGに解析できます。その後、[Aspose.Imaging for Java]（https://products.aspose.com/imaging/java/）を使用して、JPEGをDXFに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でJSON形式をDXFに変換する" %}}
1.新しい[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）オブジェクトを作成し、JSONファイルを開きます
2. [save]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions）を使用してJSONをJPEGとして保存します） 方法
3. [Image]（https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image）クラスを使用してJPEGドキュメントをロードします
4. [save]（https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBaseを使用してドキュメントをDXF形式で保存します-） 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
さらに、APIを使用すると、指定されたレイアウトオプションを使用してJSONをDXFに解析できます。レイアウトオプションを指定するには、[JsonLayoutOptions]（https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions）クラスを使用できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、Javaを介してJSON形式をDXFに変換する" %}}
APIを使用して、DXFドキュメントに透かしを入れたJSONをDXFに変換することもできます。透かしを追加するには、最初にJSONをJPEGに変換し、透かしを追加します。透かしを追加するには、[Image]（https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image）クラスを使用して画像ファイルを読み込み、[Graphics]（https ：//apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics）クラスをImageオブジェクトで初期化し、新しい[Matrix]（https://apireference.aspose.com/imaging/java/ com.aspose.imaging / Matrix）オブジェクトを作成し、変換と変換を目的の角度に設定し、[Graphics.drawString]（https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-）メソッド。画像に透かしを追加した後、JPEGをDXF形式で保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-jpeg2000/" name="JSON に JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-emz/" name="JSON に EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-psd/" name="JSON に PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-wmf/" name="JSON に WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-wmz/" name="JSON に WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-dxf/" name="JSON に DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-image/" name="JSON に IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-svgz/" name="JSON に SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-dicom/" name="JSON に DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-tga/" name="JSON に TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}