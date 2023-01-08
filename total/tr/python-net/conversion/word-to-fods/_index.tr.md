---
title: Python kullanarak WORD'yi FODS'e dönüştürün
description: Python uygulamalarınızda Microsoft Word veya Excel kullanmadan WORD'den FODS'e dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: FODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORD'yi Python aracılığıyla FODS'e dönüştürün" h2="Microsoft Word<sup>&reg;</sup> veya Excel yüklemeden Python uygulamalarınızda WORD'den FODS'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde WORD'den FODS'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. Farklı biçimlerle uğraşan çeşitli API'lerin eksiksiz bir paketidir.

Esas olarak iki adımdadır. WORD dosyasını HTML'ye dönüştürmek için öncelikle [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API'sini kullanın. Daha sonra Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) kullanarak oluşturulan HTML'yi istenilen Microsoft Excel formatında kaydediniz. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da WORD'yi FODS'e Dönüştürme" %}}
- **1. Adım** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) sınıfını kullanarak kaynak WORD dosyasını açın
- Dosya adını ve istenen dizin yolunu sağlayarak [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) yöntemini kullanarak WORD dosyasını HTML'ye kaydedin
-  **2. Adım** Parametre olarak file ve LoadOptions ile Workbook sınıfının bir örneğini içeren HTML dosyasını yükleyin
-  Çıktı FODS dosyası yolunu belirtirken "kaydet" yöntemini çağırın. Böylece WORD dosyanız belirtilen yolda FODS'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- WORD'den FODS'e dönüştürme için Python 3.5 veya üstü gereklidir
- Doğrudan PyPI'den ([Aspose.Words](https://pypi.org/project/aspose-words/) ve [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) proje içindeki referans API'leri
-  Veya şu pip komutlarını kullanın: ``pip install aspose.words`` ve ```pip install aspose-cells-python``` 
-  Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Words](https://docs.aspose.com/words/python-net/system-requirements/) ve [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) için daha fazlasına bakın) ve Linux için gcc ve libpython için ek gereksinimleri kontrol edin ve [adım adım talimatlar](https://docs.aspose.com/words/python-net/installation/)'ı izleyin.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="WORD'yi Python'da HTML'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da HTML'yi FODS'e Kaydet - Adım 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-excel/" name="WORD İle EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xls/" name="WORD İle XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xlsx/" name="WORD İle XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-csv/" name="WORD İle CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-dif/" name="WORD İle DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-fods/" name="WORD İle FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-ods/" name="WORD İle ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-sxc/" name="WORD İle SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-tsv/" name="WORD İle TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xlam/" name="WORD İle XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xlsb/" name="WORD İle XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xlt/" name="WORD İle XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xltm/" name="WORD İle XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xltx/" name="WORD İle XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/word-to-xlsm/" name="WORD İle XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}