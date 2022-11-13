---
title: Python Kullanarak TSV Dosyasını Güncelleyin
description: Microsoft Excel kullanmadan Python uygulamalarında TSV belgesini değiştirin. 
url: /tr/python-java/update/tsv/
family: total
platformtag: Python
feature: update
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python Üzerinden TSV Dosyasını Güncelleyin" h2="Microsoft Office<sup>&reg;</sup> yüklemeden Python Uygulamalarınız aracılığıyla TSV elektronik tablolarını değiştirin." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python uygulaması aracılığıyla TSV dosyalarını güncellemeye çalışan bir geliştirici için mi? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API, güncelleme sürecini otomatikleştirmeye yardımcı olabilir. Microsoft Excel dosyaları da dahil olmak üzere farklı biçimlerle ilgilenen çeşitli API'lerden oluşan eksiksiz bir pakettir. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) paketinin bir parçası olan ASPOSE.CELL API, bu değiştirme işlemini kolaylaştırır. Aşağıda TSV belgesinin güncellenmesi süreci yer almaktadır.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da TSV Dosyası Nasıl Güncellenir" %}}

- Parametre olarak kaynak TSV dosyasına sahip yeni [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) sınıfı nesnesi oluşturun
- [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) yöntemi kullanılarak ilgili Çalışma Sayfasına erişim
- [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) yöntemini kullanarak erişilen hücreye yeni veri ekleyin
- Dosyayı parametre olarak yol ile ileterek save() yöntemini kullanarak dosyayı .tsv dosyası olarak kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Değişiklik Gereksinimleri" %}}

- TSV değişikliği için, proje içindeki API'lere doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) başvurun
- Veya aşağıdaki pip komutunu kullanın ```pip install aspose.cells``` 
- Ayrıca [İndirilenler](https://downloads.aspose.com/cells/python-java) bölümünden API paketini indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod - Python'da TSV Dosyasını Güncelle" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Değişiklik Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xls/" name="Güncelleme XLS Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xlsx/" name="Güncelleme XLSX Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/csv/" name="Güncelleme CSV Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xlsb/" name="Güncelleme XLSB Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xlsm/" name="değiştir XLSM Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xlt/" name="Güncelleme XLT Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xltx/" name="Güncelleme XLTX Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/xltm/" name="Güncelleme XLTM Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/update/tsv/" name="Güncelleme TSV Dosya" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}