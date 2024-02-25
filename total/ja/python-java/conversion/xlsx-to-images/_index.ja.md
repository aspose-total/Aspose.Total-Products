---
title: Python を使用して XLSX を画像に変換する
description: XLSX からイメージ TIFF BMP PNG JPEG GIF EMF SVG への Python アプリケーションでの変換 (Microsoft Excel を使用しない) 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python経由でXLSXを画像に変換" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Python アプリケーションで XLSX を JPG、TIFF、BMP、PNG、GIF 画像に変換します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内で XLSX を PNG、BMP、TIFF、JPEG、および GIF 画像変換機能に追加しようとしている Python 開発者向け。 場合によっては、Web またはデスクトップ アプリケーションに Excel スプレッドシートを埋め込む必要があります。 そのような場合、スプレッドシートを画像にエクスポートすることが 1 つの解決策です。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API は、Excel ファイルを画像にエクスポートしたり、変換プロセスを自動化するのに役立ちます。 これは、子 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API を介して Microsoft Excel 形式を含むさまざまな形式を処理するさまざまな API の完全なパッケージです。 現在、Python Excel to Image Converter API は、Excel ファイルの EMF、WMF、JPEG、PNG、BMP、GIF、TIFF、SVG、GLTF、PICT、SVM、および Office 互換 EMF への変換をサポートしているか、サポートされている [フォーマット](https://docs.aspose.com/cells/python-java/supported-file-formats/) を確認してください。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XLSX を画像に変換する方法" %}}

- XLSX ファイルをロードするための [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) クラス オブジェクトの作成
- [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) クラスを使用し、出力画像関連のオプションを指定します
- [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) メソッドを使用して変換用ワークシートにアクセスする
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) メソッドを使用して、ワークシートのすべてのページを画像として保存します。 XLSX ファイルは、指定されたパスでイメージに変換されるようになりました

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XLSX から画像 (JPG、PNG、GIF、BMP、TIFF) への変換では、プロジェクト内の API を PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) から直接参照します。
- または、次の pip コマンド ```pip install aspose.cells``` を使用します。 
- さらに、[ダウンロード](https://releases.aspose.com/cells/python-java) セクションから API パッケージをダウンロードします。 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonによるXLSXから画像への変換" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}