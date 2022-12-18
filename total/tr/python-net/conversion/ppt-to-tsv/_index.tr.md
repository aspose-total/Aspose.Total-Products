---
title: Python kullanarak PPT'yi TSV'e dönüştürün
description: Microsoft Office kullanmadan Python uygulamalarınızda PPT'den TSV'e dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: PPT
outformat: TSV
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPT'yi Python aracılığıyla TSV'e dönüştürün" h2="Microsoft PowerPoint<sup>&reg;</sup> veya Excel yüklemeden Python uygulamalarınızda PPT'den TSV'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde PPT'den TSV'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. PPT ve TSV dosyaları dahil olmak üzere farklı biçimlerle ilgilenen çeşitli API'lerin eksiksiz bir paketidir.

Esas olarak iki adımdadır. PPT dosyasını HTML'ye dönüştürmek için öncelikle [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API'yi kullanın. Daha sonra Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) kullanarak oluşturulan HTML'yi istenilen Microsoft Excel formatında kaydediniz. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da PPT'yi TSV'e Dönüştürme" %}}
- **Aşama 1** Kaynak PPT dosyasını açmak için [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) sınıfı örneğini kullanın 
- Dosya adını ve istenen dizin yolunu sağlayarak [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) yöntemini kullanarak PPT dosyasını HTML'ye kaydedin
-  **Adım 2** Workbook sınıfının bir örneğini içeren HTML dosyasını yükleyin
-  Çıktı TSV dosyası yolunu belirtirken "kaydet" yöntemini çağırın. Böylece PPT dosyanız belirtilen yolda TSV'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- PPT'den TSV'e dönüştürme için Python 3.5 veya üstü gereklidir
- Doğrudan PyPI'den ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) ve [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) proje içindeki referans API'leri
-  Veya şu pip komutlarını kullanın: ``pip install aspose.slides``` ve ```pip install aspose-cells-python```
-  Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) ve [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) için daha fazlasına bakın)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPT'yi Python'da HTML'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da HTML'yi TSV'e Kaydet - Adım 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}