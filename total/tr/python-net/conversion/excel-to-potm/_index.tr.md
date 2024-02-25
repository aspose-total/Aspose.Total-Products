---
title: Python kullanarak EXCEL'yi POTM'e dönüştürün
description: Microsoft Office kullanmadan Python uygulamalarınızda EXCEL'den POTM'e dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EXCEL'yi Python aracılığıyla POTM'e dönüştürün" h2="Python uygulamalarınızda Microsoft Excel<sup>&reg;</sup> veya PowerPoint yüklemeden EXCEL'den POTM'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde EXCEL'den POTM'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. EXCEL ve POTM dosyaları da dahil olmak üzere farklı biçimlerle uğraşan çeşitli API'lerden oluşan eksiksiz bir pakettir..

Esas olarak iki adımda. EXCEL dosyasını PDF'ye dönüştürmek için öncelikle [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API'sini kullanın. Bundan sonra, PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/)'ı kullanarak, oluşturulan PDF'yi istenen Microsoft PowerPoint formatında kaydedin.. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da EXCEL'yi POTM'e Dönüştürme" %}}
- **Aşama 1** Kaynak EXCEL dosyasını açmak için Workbook sınıfı örneğini kullanın 
- Dosya adını ve istenen dizin yolunu sağlayarak save yöntemini kullanarak EXCEL dosyasını PDF'ye kaydedin
-  **Adım 2** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) sınıfını kullanarak PDF dosyasını yükleyin
-  Çıkış POTM dosyası yolunu belirtirken [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) yöntemini çağırın. Böylece EXCEL dosyanız belirtilen yolda POTM'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- EXCEL'den POTM'e dönüştürme için Python 3.5 veya üstü gereklidir
- Doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) ve [Aspose.Slides](https://pypi.org/project/Aspose.Slides/)) proje içindeki referans API'leri
-  Veya şu pip komutlarını kullanın: ``pip install aspose-cells-python`` ve ``pip install aspose.slides```
-  Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) ve [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) için daha fazlasına bakın)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="EXCEL'yi Python'da PDF'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da PDF'yi POTM'e Kaydet - Adım 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}