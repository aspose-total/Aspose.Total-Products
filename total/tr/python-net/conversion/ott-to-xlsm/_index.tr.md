---
title: Python kullanarak OTT'yi XLSM'e dönüştürün
description: Python uygulamalarınızda Microsoft Word veya Excel kullanmadan OTT'den XLSM'e dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: OTT
outformat: XLSM
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="OTT'yi Python aracılığıyla XLSM'e dönüştürün" h2="Microsoft Word<sup>&reg;</sup> veya Excel yüklemeden Python uygulamalarınızda OTT'den XLSM'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde OTT'den XLSM'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. Farklı biçimlerle uğraşan çeşitli API'lerin eksiksiz bir paketidir.

Esas olarak iki adımdadır. OTT dosyasını HTML'ye dönüştürmek için öncelikle [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API'sini kullanın. Daha sonra Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) kullanarak oluşturulan HTML'yi istenilen Microsoft Excel formatında kaydediniz. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da OTT'yi XLSM'e Dönüştürme" %}}
- **1. Adım** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) sınıfını kullanarak kaynak OTT dosyasını açın
- Dosya adını ve istenen dizin yolunu sağlayarak [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) yöntemini kullanarak OTT dosyasını HTML'ye kaydedin
-  **2. Adım** Parametre olarak file ve LoadOptions ile Workbook sınıfının bir örneğini içeren HTML dosyasını yükleyin
-  Çıktı XLSM dosyası yolunu belirtirken "kaydet" yöntemini çağırın. Böylece OTT dosyanız belirtilen yolda XLSM'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- OTT'den XLSM'e dönüştürme için Python 3.5 veya üstü gereklidir
- Doğrudan PyPI'den ([Aspose.Words](https://pypi.org/project/aspose-words/) ve [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) proje içindeki referans API'leri
-  Veya şu pip komutlarını kullanın: ``pip install aspose.words`` ve ```pip install aspose-cells-python``` 
-  Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Words](https://docs.aspose.com/words/python-net/system-requirements/) ve [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) için daha fazlasına bakın) ve Linux için gcc ve libpython için ek gereksinimleri kontrol edin ve [adım adım talimatlar](https://docs.aspose.com/words/python-net/installation/)'ı izleyin.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OTT'yi Python'da HTML'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da HTML'yi XLSM'e Kaydet - Adım 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}