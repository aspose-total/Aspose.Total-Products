---
title: Convert XLTM to Image using Python
description: XLTM to image TIFF BMP PNG JPEG GIF EMF SVG conversion in your Python applications without using Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLTM
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XLTM to Image Via Python" h2="XLTM to JPG, TIFF, BMP, PNG, GIF images conversion in your Python Applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

For a Python developer, who is trying to add a XLTM to PNG, BMP, TIFF, JPEG and GIF Image conversion feature within application. As sometimes it's required to embed Excel spreadsheets in the web or desktop applications. In such cases exporting spreadsheets to images is the one soultion. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API can help to export Excel files to images as well as to automate the conversion process. It's a full package of various APIs dealing different formats including Microsoft Excel formats via its child [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API. Currently Python Excel to Image Converter API supports conversion of Excel Files to EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM and Office Compatible EMF or check the supported [formats](https://docs.aspose.com/cells/python-java/supported-file-formats/). 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert XLTM to Images in Python" %}}

- Create [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) class object to load XLTM file
- Use [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) class and specify the output image relevant options
- Get the access the worksheet for conversion using [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) method
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Save all pages of worksheet as an image using [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) method. Now XLTM file is converted to Images at the specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For XLTM to Images (JPG, PNG, GIF, BMP, TIFF) conversion, reference APIs within the project directly from PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Or use the following pip command ```pip install aspose.cells``` 
- Moreover, Download the API package from the [downloads](https://releases.aspose.com/cells/python-java) section 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTM To Images Conversion via Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}