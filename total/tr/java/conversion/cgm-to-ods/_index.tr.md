---
title: CGM'yi ODS'ye Dönüştürmek için Java API
description: Microsoft Excel veya Adobe Reader kullanmadan CGM'yi Java API aracılığıyla ODS'ye aktarın
url_ignore: /tr/java/conversion/cgm-to-ods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODS
otherformats: XLTM XLSB XLSM XLT SXC MD DIF EXCEL ODS XLAM TXT FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM'yi Java aracılığıyla ODS'ye aktarın" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API'sini kullanarak CGM dosyasını ODS'ye dönüştürün" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak CGM'den ODS'ye dönüştürme özelliğini Java uygulamalarınıza iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak CGM'yi XLSX'e dönüştürebilirsiniz. İkinci adımda, Elektronik Tablo Programlama API'sini [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak XLSX'i ODS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM Dosyasını Java ile ODS'ye Dönüştür" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak CGM dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- kullanarak CGM'yi XLSX'e dönüştürün) ) yöntem
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) kullanarak ODS formatına kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) pom.xml dosyanızda.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
CGM belgeniz parola korumalıysa, parola olmadan ODS'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Belgenin](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-) yeni bir örneğini başlatabilirsiniz. Java.lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Korumalı CGM'yi Java ile ODS'ye Dönüştür" %}}
CGM dosyasını ODS'ye dönüştürürken, çıktı ODS dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için dönüştürülmüş XLSX dosyasını açmak için yeni bir Çalışma Kitabı oluşturun. Dizini aracılığıyla Çalışma Sayfası'nı seçin, bir Şekil oluşturun ve addTextEffect işlevini kullanın, renkleri, şeffaflığı ve daha fazlasını ayarlayın. Bundan sonra XLSX belgenizi Filigranlı ODS olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM (Bilgisayar Grafik Meta Dosyası) dosyalarını ODS (OpenDocument Elektronik Tablo) formatına dönüştürmek, vektör tabanlı diyagramları yapılandırılmış verilerle açık kaynak elektronik tablo formatlarında birleştirmeyi sağlar. Bu dönüşüm, hem tablo verilerini hem de yüksek kaliteli görselleri gerektiren teknik raporlama, mühendislik belgeleri ve analitik görevler için önemlidir.

## ✅ Temel Kullanım Durumları
- Gömülü diyagramlarla tablo mühendislik raporları oluşturma.
- Görsel referanslarla açık kaynak proje belgeleri.
- Vektör tabanlı grafiklerle bilimsel veri analitiği.
- Entegre şematiklerle üretim süreci takibi.
- Diyagramlı veriler içeren çevresel ve araştırma raporları.

## ⚙️ Otomasyon Senaryoları
- Birleşik veri ve diyagramları dışa aktaran Java tabanlı ETL sistemleri.
- Yapılandırılmış ve görsel içerik için bilimsel veri dışa aktarma araçları.
- Çoklu formatlı teknik belgeler için Ofis uyumluluk API'leri.
- Otomatik veri görselleştirme boru hatları.
- Çapraz platform erişimi için LibreOffice Calc ile entegrasyon.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}