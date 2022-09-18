---
title: Python'da ODT'yi PPSX'e Dönüştür
description: Python uygulamalarınızda Microsoft Word veya PowerPoint kullanmadan ODT'den PPSX'e dönüştürme 
url: /tr/python-net/conversion/odt-to-ppsx/
family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: PPSX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python kullanarak ODT'yi PPSX'e dönüştürün" h2="Microsoft Word<sup>&reg;</sup> veya PowerPoint yüklemeden Python Uygulamalarınızda ODT'den PPSX'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde bir ODT'den PPSX'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. Farklı biçimlerle ilgilenen çeşitli API'lerden oluşan eksiksiz bir pakettir. Yani **Python'da ODT'yi PPSX'e Nasıl Dönüştürür?**

Esas olarak iki adımdadır. ODT dosyasını PDF'ye dönüştürmek için öncelikle [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API'sini kullanın. Daha sonra PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) kullanarak oluşturulan PDF'yi PPSX formatında Presentation'a kaydedin. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da ODT'yi PPSX'e Dönüştür" %}}
- **Aşama 1** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) sınıfını kullanarak kaynak ODT dosyasını açın
- [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) yöntemini kullanarak dosya adını ve istenen dizin yolunu sağlayarak ODT dosyasını PDF'ye kaydedin.
-  **Adım 2** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) sınıfının bir örneğiyle PDF dosyasını yükleyin
-  Çıktı dosyası yolunu & SaveFormat.PPSX'i parametre olarak belirtirken 'save' yöntemini çağırın. Böylece ODT dosyanız belirtilen yolda PPSX'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- ODT'den PPSX'e dönüştürme için Python 3.5 veya üstü gereklidir
- Proje içindeki referans API'leri doğrudan PyPI'den ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) ve [Aspose.Words](https://pypi.org/project/aspose-words/)) veya
- ``pip install aspose.slides``` ve ```pip install aspose.words``` şu pip komutlarını kullanın. Dahası,
- Microsoft Windows veya Linux tabanlı işletim sistemi ([Slides](https://docs.aspose.com/slides/python-net/system-requirements/) ve [Words](https://docs.aspose.com/words/python-net/system-requirements/) için daha fazlasına bakın) ve Linux için gcc ve libpython için ek gereksinimleri kontrol edin ve [INSTALL](https://docs.aspose.com/words/python-net/installation/) adım adım talimatları izleyin.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python'da ODT'yi PDF'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da PDF'yi PPSX'e Kaydet - 2. Adım" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}