---
title: Python'da XLTX oluşturun
description: Microsoft Office kullanmadan Python uygulamalarını kullanarak XLTX dosyası oluşturun. 

family: total
platformtag: Python
feature: create
informat: XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python kullanarak XLTX oluşturun" h2="Microsoft Office<sup>&reg;</sup> yüklemeden Python Uygulamalarınız aracılığıyla XLTX oluşturun." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python uygulaması aracılığıyla XLTX dosyaları oluşturmaya çalışan bir geliştirici için? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API, oluşturma sürecini otomatikleştirmeye yardımcı olabilir. Microsoft Office dosyaları ve Görüntüler dahil olmak üzere farklı biçimlerle ilgilenen çeşitli API'lerden oluşan eksiksiz bir pakettir. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) paketinin bir parçası olan [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API, bu üretim sürecini kolaylaştırır. Aşağıda oluşturma süreci yer almaktadır. Ayrıca, geliştiriciler, XLTX dosyasının değiştirilmesi için uygulamayı kolayca geliştirebilir. XLTX dosyasını Python kullanarak güncellemek, Workbook nesnesini oluştururken parametre olarak var olan dosyayı gerektirmesi dışında aynıdır.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python'da XLTX Dosyası Nasıl Oluşturulur" %}}

- Parametre olarak DosyaFormatType olan yeni [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) sınıfı nesnesi oluşturun
- [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) yöntemini kullanarak gerekli [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet)'ye erişim sağlayın
- [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) yöntemini kullanarak erişilen hücreye veri ekleyin
- Dosyayı parametre olarak yol ile geçirerek [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String) kullanarak belgeyi .xltx dosyası olarak kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Oluşturma Gereksinimleri" %}}

- XLTX üretimi için, proje içindeki API'lere doğrudan PyPI'den ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) başvurun
- Veya aşağıdaki pip komutunu kullanın ```pip install aspose.cells``` 
- Ayrıca [downloads](https://releases.aspose.com/cells/python-java) bölümünden API paketini indirin 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python'da XLTX oluşturun" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xls/" name="üret XLS Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xlsx/" name="Oluşturmak XLSX Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/csv/" name="Oluşturmak CSV Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xlsb/" name="Oluşturmak XLSB Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xlsm/" name="Oluşturmak XLSM Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xlt/" name="Oluşturmak XLT Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xltx/" name="Oluşturmak XLTX Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/xltm/" name="Oluşturmak XLTM Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/ods/" name="Oluşturmak ODS Dosya" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/python-java/create/tsv/" name="Oluşturmak TSV Dosya" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}