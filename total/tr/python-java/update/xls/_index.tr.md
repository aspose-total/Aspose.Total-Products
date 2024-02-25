---
title: Python Kullanarak XLS Dosyasını Güncelleyin
description: Microsoft Excel kullanmadan Python uygulamalarında XLS belgesini değiştirin. 

family: total
platformtag: Python
feature: update
informat: XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python Üzerinden XLS Dosyasını Güncelleyin" h2="Microsoft Office<sup>&reg;</sup> yüklemeden Python Uygulamalarınız aracılığıyla XLS elektronik tablolarını değiştirin." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python uygulaması aracılığıyla XLS dosyalarını güncellemeye çalışan bir geliştirici için mi? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API, güncelleme sürecini otomatikleştirmeye yardımcı olabilir. Microsoft Excel dosyaları da dahil olmak üzere farklı biçimlerle ilgilenen çeşitli API'lerden oluşan eksiksiz bir pakettir. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) paketinin bir parçası olan ASPOSE.CELL API, bu değiştirme işlemini kolaylaştırır. Aşağıda XLS belgesinin güncellenmesi süreci yer almaktadır.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da XLS Dosyası Nasıl Güncellenir" %}}

- Parametre olarak kaynak XLS dosyasına sahip yeni [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) sınıfı nesnesi oluşturun
- [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) yöntemi kullanılarak ilgili Çalışma Sayfasına erişim
- [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) yöntemini kullanarak erişilen hücreye yeni veri ekleyin
- Dosyayı parametre olarak yol ile ileterek save() yöntemini kullanarak dosyayı .xls dosyası olarak kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Değişiklik Gereksinimleri" %}}

- XLS değişikliği için, proje içindeki API'lere doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) başvurun
- Veya aşağıdaki pip komutunu kullanın ```pip install aspose.cells``` 
- Ayrıca [İndirilenler](https://releases.aspose.com/cells/python-java) bölümünden API paketini indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod - Python'da XLS Dosyasını Güncelle" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}