---
title: PCL'yi FODS'ye Dönüştürmek için Java API
description: Microsoft Excel veya Adobe Reader kullanmadan PCL'yi Java API aracılığıyla FODS'ye aktarın
url: /tr/java/conversion/pcl-to-fods/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: FODS
otherformats: TSV XLSM XLSB FODS TXT ODS XLTX XLT DIF XLAM SXC EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PCL'yi Java aracılığıyla FODS'ye aktarın" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API'sini kullanarak PCL dosyasını FODS'ye dönüştürün" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak PCL'den FODS'ye dönüştürme özelliğini Java uygulamalarınıza iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak PCL'yi XLSX'e dönüştürebilirsiniz. İkinci adımda, Elektronik Tablo Programlama API'sini [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak XLSX'i FODS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PCL Dosyasını Java ile FODS'ye Dönüştür" %}}
1. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak PCL dosyasını açın
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- kullanarak PCL'yi XLSX'e dönüştürün) ) yöntem
3. [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) kullanarak FODS formatına kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Cells for Java](https://docs.aspose.com/cells/java/) içerir kurulum/) pom.xml dosyanızda.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
PCL belgeniz parola korumalıysa, parola olmadan FODS'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Belgenin](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-) yeni bir örneğini başlatabilirsiniz. Java.lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Korumalı PCL'yi Java ile FODS'ye Dönüştür" %}}
PCL dosyasını FODS'ye dönüştürürken, çıktı FODS dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için dönüştürülmüş XLSX dosyasını açmak için yeni bir Çalışma Kitabı oluşturun. Dizini aracılığıyla Çalışma Sayfası'nı seçin, bir Şekil oluşturun ve addTextEffect işlevini kullanın, renkleri, şeffaflığı ve daha fazlasını ayarlayın. Bundan sonra XLSX belgenizi Filigranlı FODS olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-dif/" name="PCL İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-xltx/" name="PCL İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-md/" name="PCL İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-fods/" name="PCL İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-xltm/" name="PCL İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-excel/" name="PCL İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-xlsm/" name="PCL İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-xlam/" name="PCL İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-xlt/" name="PCL İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-xlsb/" name="PCL İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-ods/" name="PCL İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-sxc/" name="PCL İle SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}