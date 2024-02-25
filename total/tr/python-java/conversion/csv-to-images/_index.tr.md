---
title: Python kullanarak CSV'i Görüntüye dönüştürün
description: Microsoft Excel kullanmadan Python uygulamalarınızda TIFF BMP PNG JPEG GIF EMF SVG dönüştürme görüntüsüne CSV 

family: total
platformtag: Python
feature: conversion
informat: CSV
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="CSV'i Python Üzerinden Görüntüye Dönüştür" h2="Python Uygulamalarınızda Microsoft Office<sup>&reg;</sup> yüklemeden CSV'den JPG, TIFF, BMP, PNG, GIF görüntülerine dönüştürme." >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde PNG, BMP, TIFF, JPEG ve GIF Görüntü dönüştürme özelliğine CSV eklemeye çalışan bir Python geliştiricisi için. Bazen Excel elektronik tablolarını web veya masaüstü uygulamalarına yerleştirmek gerekir. Bu gibi durumlarda, elektronik tabloları görüntülere dışa aktarmak tek ruhtur. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API, Excel dosyalarını görüntülere aktarmanın yanı sıra dönüştürme işlemini otomatikleştirmeye yardımcı olabilir. Alt [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API'si aracılığıyla Microsoft Excel biçimleri de dahil olmak üzere farklı biçimlerle ilgilenen çeşitli API'lerden oluşan eksiksiz bir pakettir. Şu anda Python Excel to Image Converter API, Excel Dosyalarının EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM ve Office Uyumlu EMF'ye dönüştürülmesini destekler veya desteklenen [Formatlar](https://docs.aspose.com/cells/python-java/supported-file-formats/)'yi kontrol edin. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da CSV Görüntülere Nasıl Dönüştürülür" %}}

- CSV dosyasını yüklemek için [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) sınıfı nesnesi oluşturun
- [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) sınıfını kullanın ve çıktı görüntüsüyle ilgili seçenekleri belirtin
- [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) yöntemini kullanarak dönüşüm için çalışma sayfasına erişin
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) yöntemini kullanarak çalışma sayfasının tüm sayfalarını resim olarak kaydedin. Şimdi CSV dosyası, belirtilen yolda Görüntülere dönüştürülür

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- CSV'den Görüntülere (JPG, PNG, GIF, BMP, TIFF) dönüştürme için, proje içindeki API'lere doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) başvurun
- Veya aşağıdaki pip komutunu kullanın ```pip install aspose.cells``` 
- Ayrıca [İndirilenler](https://releases.aspose.com/cells/python-java) bölümünden API paketini indirin 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV Python ile Görüntülere Dönüştürme" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}