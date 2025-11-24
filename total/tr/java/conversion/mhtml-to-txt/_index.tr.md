---
title: MHTML'yi TXT'ye Dönüştürmek için Java API
description: Microsoft Excel veya Adobe Reader kullanmadan MHTML'yi Java API aracılığıyla TXT'ye aktarın
url_ignore: /tr/java/conversion/mhtml-to-txt/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: TXT
otherformats: XLTM TSV ODS SXC TXT DIF XLAM MD XLT EXCEL XLSB XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MHTML'yi Java aracılığıyla TXT'ye aktarın" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API'sini kullanarak MHTML dosyasını TXT'ye dönüştürün" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak MHTML'den TXT'ye dönüştürme özelliğini Java uygulamalarınıza iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak MHTML'yi XLSX'e dönüştürebilirsiniz. İkinci adımda, Elektronik Tablo Programlama API'sini [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak XLSX'i TXT'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Dosyasını Java ile TXT'ye Dönüştür" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak MHTML dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- kullanarak MHTML'yi XLSX'e dönüştürün) ) yöntem
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) kullanarak TXT formatına kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) pom.xml dosyanızda.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
MHTML belgeniz parola korumalıysa, parola olmadan TXT'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Belgenin](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-) yeni bir örneğini başlatabilirsiniz. Java.lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Korumalı MHTML'yi Java ile TXT'ye Dönüştür" %}}
MHTML dosyasını TXT'ye dönüştürürken, çıktı TXT dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için dönüştürülmüş XLSX dosyasını açmak için yeni bir Çalışma Kitabı oluşturun. Dizini aracılığıyla Çalışma Sayfası'nı seçin, bir Şekil oluşturun ve addTextEffect işlevini kullanın, renkleri, şeffaflığı ve daha fazlasını ayarlayın. Bundan sonra XLSX belgenizi Filigranlı TXT olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



MHTML'yi TXT (düz metin) formatına dönüştürmek, web arşivlerinden tüm metinsel içeriği çıkarırken biçimlendirmeyi kaldırır. TXT dosyaları hafiftir, geniş destek alır ve arama dizinlemesi, metin analizi veya arşivleme amaçları için idealdir.



{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Alanları" %}}



* Çevrimdışı okuma için web içeriğini düz metin olarak arşivleme.

* MHTML sayfalarından metinsel raporları çıkarma ve analiz için.

* Çevrimiçi makaleleri veya öğreticileri hızlı referans için TXT'ye dönüştürme.

* Metin tabanlı işleme, NLP veya yapay zeka araçları için içerik hazırlama.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}



* Büyük ölçekli web arşivleme için toplu MHTML'den TXT'ye dönüştürme.

* Analiz için web sayfalarından metinsel verilerin zamanlanmış çıkarılması.

* Otomatik metin işleme için AI/ML boru hatlarıyla entegrasyon.

* Gerçek zamanlı web içeriği izleme ve raporlama için tetiklenen dönüştürme.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}