---
title: XSLFO'yi XLTX'ye Dönüştürmek için Java API
description: Microsoft Excel veya Adobe Reader kullanmadan XSLFO'yi Java API aracılığıyla XLTX'ye aktarın
url: /tr/java/conversion/xslfo-to-xltx/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: XLTX
otherformats: TSV MD XLTX SXC ODS XLSM XLT XLTM XLSB DIF FODS EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XSLFO'yi Java aracılığıyla XLTX'ye aktarın" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API'sini kullanarak XSLFO dosyasını XLTX'ye dönüştürün" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak XSLFO'den XLTX'ye dönüştürme özelliğini Java uygulamalarınıza iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak XSLFO'yi XLSX'e dönüştürebilirsiniz. İkinci adımda, Elektronik Tablo Programlama API'sini [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak XLSX'i XLTX'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFO Dosyasını Java ile XLTX'ye Dönüştür" %}}
1. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak XSLFO dosyasını açın
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- kullanarak XSLFO'yi XLSX'e dönüştürün) ) yöntem
3. [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) kullanarak XLTX formatına kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Cells for Java](https://docs.aspose.com/cells/java/) içerir kurulum/) pom.xml dosyanızda.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
XSLFO belgeniz parola korumalıysa, parola olmadan XLTX'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Belgenin](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-) yeni bir örneğini başlatabilirsiniz. Java.lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Korumalı XSLFO'yi Java ile XLTX'ye Dönüştür" %}}
XSLFO dosyasını XLTX'ye dönüştürürken, çıktı XLTX dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için dönüştürülmüş XLSX dosyasını açmak için yeni bir Çalışma Kitabı oluşturun. Dizini aracılığıyla Çalışma Sayfası'nı seçin, bir Şekil oluşturun ve addTextEffect işlevini kullanın, renkleri, şeffaflığı ve daha fazlasını ayarlayın. Bundan sonra XLSX belgenizi Filigranlı XLTX olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-dif/" name="XSLFO İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-xltx/" name="XSLFO İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-md/" name="XSLFO İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-fods/" name="XSLFO İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-xltm/" name="XSLFO İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-excel/" name="XSLFO İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-xlsm/" name="XSLFO İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-xlam/" name="XSLFO İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-xlt/" name="XSLFO İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-xlsb/" name="XSLFO İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-ods/" name="XSLFO İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xslfo-to-sxc/" name="XSLFO İle SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}