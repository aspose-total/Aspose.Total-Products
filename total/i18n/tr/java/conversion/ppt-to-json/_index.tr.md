---
title: PPT'yi Java ile JSON Formatına Dönüştür
description: Microsoft Excel veya PowerPoint kullanmadan Java aracılığıyla PPT'yi JSON formatına dönüştürün
url: /tr/java/conversion/ppt-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PPT'yi Java ile JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Excel veya PowerPoint kullanmadan PPT'yi JSON'a aktarmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla PPT'yi JSON formatına dönüştürmek, iki adımlı basit bir işlemdir. İlk adımda, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak PPT'yi HTML'ye aktarabilirsiniz. İkinci olarak, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak HTML'yi JSON'a dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT'yi Java ile JSON Formatına Dönüştür" %}}
1. [Sunum](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPT dosyasını açın
2. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPT'yi HTML'ye dönüştürün. ISaveOptions-) yöntemi
3. [Çalışma Kitabı](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. Belgeyi [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) kullanarak JSON biçiminde kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz PPT belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. API, bir LoadOptions nesnesinde doğru parolayı ileterek şifrelenmiş belgeyi açmanıza olanak tanır.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Korumalı PPT'yi JSON Formatına Dönüştür" %}}
PPT'yi JSON'a dönüştürürken, aralığı JSON çıktı biçiminize de ayarlayabilirsiniz. Aralığı ayarlamak için dönüştürülen HTML'yi Workbook sınıfını kullanarak açabilir, Cells.createRange yöntemini kullanarak dışa aktarılacak bir veri aralığı oluşturabilir, Range & ExportRangeToJsonOptions referanslarıyla JsonUtility.exportRangeToJson yöntemini çağırabilir ve dosyaya dize JSON verilerini yazabilirsiniz. BufferedWriter.write yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-doc/" name="PPT İle DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-docm/" name="PPT İle DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-docx/" name="PPT İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-dot/" name="PPT İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-dotm/" name="PPT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-dotx/" name="PPT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-odt/" name="PPT İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-ott/" name="PPT İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-rtf/" name="PPT İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-text/" name="PPT İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-word/" name="PPT İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppt-to-wordml/" name="PPT İle WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}