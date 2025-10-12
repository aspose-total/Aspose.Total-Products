---
title: ODP'yi Java ile JSON Formatına Dönüştür
description: Microsoft Excel veya PowerPoint kullanmadan Java aracılığıyla ODP'yi JSON formatına dönüştürün
url_ignore: /tr/java/conversion/odp-to-json/
family: total
platformtag: net
feature: conversion
informat: ODP
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ODP'yi Java ile JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Excel veya PowerPoint kullanmadan ODP'yi JSON'a aktarmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla ODP'yi JSON formatına dönüştürmek, iki adımlı basit bir işlemdir. İlk adımda, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak ODP'yi HTML'ye aktarabilirsiniz. İkinci olarak, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak HTML'yi JSON'a dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODP'yi Java ile JSON Formatına Dönüştür" %}}
1. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak ODP dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak ODP'yi HTML'ye dönüştürün. ISaveOptions-) yöntemi
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. Belgeyi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) kullanarak JSON biçiminde kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz ODP belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. API, bir LoadOptions nesnesinde doğru parolayı ileterek şifrelenmiş belgeyi açmanıza olanak tanır.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Korumalı ODP'yi JSON Formatına Dönüştür" %}}
ODP'yi JSON'a dönüştürürken, aralığı JSON çıktı biçiminize de ayarlayabilirsiniz. Aralığı ayarlamak için dönüştürülen HTML'yi Workbook sınıfını kullanarak açabilir, Cells.createRange yöntemini kullanarak dışa aktarılacak bir veri aralığı oluşturabilir, Range & ExportRangeToJsonOptions referanslarıyla JsonUtility.exportRangeToJson yöntemini çağırabilir ve dosyaya dize JSON verilerini yazabilirsiniz. BufferedWriter.write yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**ODP'yi JSON'a dönüştürmek**, sunum içeriğinin yapılandırılmış bir şekilde çıkarılmasını sağlar, **makine tarafından okunabilir bir formata** dönüştürerek modern web veya otomasyon sistemleriyle sorunsuz veri alışverişi, analiz ve entegrasyon sağlar.
{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Alanları" %}}

* API'ler için sunum verilerini yapılandırılmış formata dönüştürme
* Analiz veya dizinleme için slaytların, metnin ve metaverilerin çıkarılması
* Sunum içeriğini web tabanlı uygulamalara taşıma
* Arama ve geri alma için sunum verilerini veritabanlarında saklama
* AI destekli içerik anlama ve sınıflandırmayı kolaylaştırma
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}
* İçerik yönetim sistemleri için otomatik ODP'den JSON'a dönüştürme
* ETL (Çıkart, Dönüştür, Yükle) borularına entegrasyon
* Sunum verilerinin web veya mobil uygulamalarda dinamik olarak oluşturulması
* Dijital varlık depoları veya API'ler için toplu dönüştürme
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}