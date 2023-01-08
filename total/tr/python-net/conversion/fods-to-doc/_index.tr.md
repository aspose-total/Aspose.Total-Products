---
title: Python kullanarak FODS'yi DOC'e dönüştürün
description: Microsoft Office kullanmadan Python uygulamalarınızda FODS'den DOC'e dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: FODS
outformat: DOC
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="FODS'yi Python aracılığıyla DOC'e dönüştürün" h2="Python uygulamalarınızda Microsoft Excel<sup>&reg;</sup> veya Word yüklemeden FODS'den DOC'e dönüştürme" >}}

{{% blocks/products/pf/feature-page-summary %}}

Uygulama içinde FODS'den DOC'e dönüştürme özelliği eklemeye çalışan bir Python geliştiricisi için. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. FODS ve DOC dosyaları da dahil olmak üzere farklı biçimlerle uğraşan çeşitli API'lerden oluşan eksiksiz bir pakettir.

Esas olarak iki adımdadır. FODS dosyasını HTML'ye dönüştürmek için öncelikle [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API'sini kullanın. Daha sonra Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) kullanarak oluşturulan HTML'yi istediğiniz Microsoft Word formatında kaydedin. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da FODS'yi DOC'e Dönüştürme" %}}
- **Aşama 1** Workbook sınıfını kullanarak kaynak FODS dosyasını açın
- Dosya adını ve istenen dizin yolunu sağlayarak save(file, SaveFormat.HTML) yöntemini kullanarak FODS dosyasını HTML'ye kaydedin
-  **Adım 2** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) sınıfının bir örneğini içeren HTML dosyasını yükleyin
-  Çıktı DOC dosyası yolunu belirtirken "kaydet" yöntemini çağırın. Böylece FODS dosyanız belirtilen yolda DOC'e dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- FODS'den DOC'e dönüştürme için Python 3.5 veya üstü gereklidir
- Doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) ve [Aspose.Words](https://pypi.org/project/aspose-words/)) proje içindeki referans API'leri
-  Veya şu pip komutlarını kullanın: ``pip install aspose-cells-python`` ve ```pip install aspose.words```
-  Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) ve [Words](https://docs.aspose.com/words/python-net/system-requirements/) için daha fazlasına bakın) ve Linux için gcc ve libpython için ek gereksinimleri kontrol edin ve [adım adım talimatlar](https://docs.aspose.com/words/python-net/installation/)'ı izleyin.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FODS'yi Python'da HTML'ye Kaydet - Adım 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da HTML'yi DOC'e Kaydet - Adım 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-word/" name="FODS İle WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-doc/" name="FODS İle DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-docx/" name="FODS İle DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-docm/" name="FODS İle DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-dot/" name="FODS İle DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-dotm/" name="FODS İle DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-dotx/" name="FODS İle DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-mobi/" name="FODS İle MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-odt/" name="FODS İle ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-ott/" name="FODS İle OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-rtf/" name="FODS İle RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-net/conversion/fods-to-wordml/" name="FODS İle WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}