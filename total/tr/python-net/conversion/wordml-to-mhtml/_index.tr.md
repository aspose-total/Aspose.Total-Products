---
title: Python'da WORDML'yi MHTML'ye Dönüştür
description: Python uygulamalarınızda Microsoft Word kullanmadan WORDML'den mhtml Web arşiv formatına ve HtmlFixed dosya dönüştürme 

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python kullanarak WORDML'yi MHTML'ye dönüştürün" h2="Python Uygulamalarınızda Microsoft Word<sup>&reg;</sup> yüklemeden WORDML'den MHTML'ye, HtmlFixed ve HTML dönüştürme." >}}

{{% blocks/products/pf/feature-page-summary %}}

MHTML'ye (Web arşiv formatı) dönüştürme özelliği veya HtmlFixed'e WORDML eklemeye çalışan bir Python geliştiricisi için, uygulama içinde kesinlikle konumlandırılmış öğeleri kullanarak belgeyi HTML biçiminde kaydetmek ister. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API, dönüştürme sürecini otomatikleştirmeye yardımcı olabilir. Farklı biçimlerle uğraşan çeşitli API'lerden oluşan eksiksiz bir pakettir. 

WORDML'yi MHTML'ye dönüştürme özelliğini eklemek için [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) Paketinin bir parçası olan [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API'sini kullanıyoruz. WORDML dosyasının basit olması durumunda, sadece iki satır kod. WORDML dosyasını yükleyin ve MHTML veya HTML_FIXED olarak SaveFormat numaralandırmasıyla birlikte uygun dosya yolu ile kaydetme yöntemini çağırın. Ancak, belge modelini orijinaline yakın bir şekilde restore etmek gerekirse, sonuçta ortaya çıkan belgede gidiş-dönüş bilgisi adı verilen bazı ekstra bilgilerin kaydedilmesi gerekir.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Nasıl Python'da WORDML'yi MHTML'ye Dönüştür" %}}
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) sınıfını kullanarak kaynak WORDML dosyasını yükleyin
- [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) örneğini oluşturun.
- export_roundtrip_information öğesini True olarak ayarlayın
- [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/)'ı MHTML olarak belirtin
- Çıktı dosyası yolunu & SaveFormat'ı parametre olarak belirtirken 'save' yöntemini çağırın. Böylece WORDML dosyanız belirtilen yolda MHTML'ye dönüştürülür.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

- WORDML'den MHTML'ye veya HtmlFixed format dönüştürme için Python 3.5 veya üstü gereklidir
- Proje içindeki referans API'leri doğrudan PyPI'den ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Veya ```pip install aspose.words``` aşağıdaki pip komutlarını kullanın.
- Ayrıca, Microsoft Windows veya Linux tabanlı işletim sistemi ([Words](https://docs.aspose.com/words/python-net/system-requirements/) için daha fazlasına bakın) ve Linux için gcc ve libpython için ek gereksinimleri kontrol edin ve [INSTALL](https://docs.aspose.com/words/python-net/installation/) adım adım talimatları izleyin.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python'da WORDML'yi MHTML'ye Kaydet - Basit" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python'da WORDML'den MHTML'ye Dönüştürme" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}