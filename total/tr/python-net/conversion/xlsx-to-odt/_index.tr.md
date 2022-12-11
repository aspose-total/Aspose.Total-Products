---
title: Python kullanarak XLSX'yi ODT'e dönüştürün
description: Microsoft Office kullanmadan Python uygulamalarınızda XLSX'den ODT'e dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XLSX'yi Python aracılığıyla ODT'e dönüştürün" h2="Python uygulamalarınızda Microsoft Excel<sup>&reg;</sup> veya Word yüklemeden XLSX'den ODT'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde XLSX'den ODT'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. XLSX ve ODT dosyaları da dahil olmak üzere farklı biçimlerle uğraşan çeşitli API'lerden oluşan eksiksiz bir pakettir.

Esas olarak iki adımdadır. XLSX dosyasını HTML'ye dönüştürmek için öncelikle [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API'sini kullanın. Daha sonra Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) kullanarak oluşturulan HTML'yi istediğiniz Microsoft Word formatında kaydedin. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da XLSX'yi ODT'e Dönüştürme" %}}
- **Aşama 1** Workbook sınıfını kullanarak kaynak XLSX dosyasını açın
- Dosya adını ve istenen dizin yolunu sağlayarak save(file, SaveFormat.HTML) yöntemini kullanarak XLSX dosyasını HTML'ye kaydedin
-  **Adım 2** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) sınıfının bir örneğini içeren HTML dosyasını yükleyin
-  Çıktı ODT dosyası yolunu belirtirken "kaydet" yöntemini çağırın. Böylece XLSX dosyanız belirtilen yolda ODT'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- XLSX'den ODT'e dönüştürme için Python 3.5 veya üstü gereklidir
- Doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) ve [Aspose.Words](https://pypi.org/project/aspose-words/)) proje içindeki referans API'leri
-  Veya şu pip komutlarını kullanın: ``pip install aspose-cells-python`` ve ```pip install aspose.words```
-  Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) ve [Words](https://docs.aspose.com/words/python-net/system-requirements/) için daha fazlasına bakın) ve Linux için gcc ve libpython için ek gereksinimleri kontrol edin ve [adım adım talimatlar](https://docs.aspose.com/words/python-net/installation/)'ı izleyin.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX'yi Python'da HTML'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da HTML'yi ODT'e Kaydet - Adım 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}