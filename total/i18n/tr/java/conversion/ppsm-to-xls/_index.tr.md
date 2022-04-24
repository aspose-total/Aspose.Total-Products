---
title: PPSM'u Java ile XLS Formatına Dönüştür
description: Microsoft Excel veya PowerPoint kullanmadan PPSM'u Java aracılığıyla XLS formatına dönüştürün
url: /tr/java/conversion/ppsm-to-xls/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: XLS
otherformats: FODS SXC EXCEL ODS DIF TSV MHTML XLSM XLTM XLT XLSX XLAM XLSB XLS XLTX MARKDOWN DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile PPSM'u XLS'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Excel veya PowerPoint kullanmadan PPSM'u XLS'ye aktarmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
PPSM dosyasını iki adımda [Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla XLS'ye dönüştürebilirsiniz. İlk adımda, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak PPSM'u HTML'ye aktarabilirsiniz. İkinci olarak, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak HTML'yi XLS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile PPSM'u XLS'ye Dönüştürme" %}}
1. [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPSM dosyasını açın
2. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPSM'u HTML'ye dönüştürün. ISaveOptions-) yöntemi
3. [Çalışma Kitabı](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. Belgeyi [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) kullanarak XLS formatına kaydedin. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
PPSM'u XLS'ye dönüştürmek için Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/) üzerinden kolayca kullanabilirsiniz. aspose/aspose-total) tabanlı proje ve kitaplıkları pom.xml'inize dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Giriş PPSM belgeniz parola korumalıysa, parolayı kullanmadan XLS'ye dönüştüremezsiniz. API, bir LoadOptions nesnesinde doğru parolayı ileterek şifrelenmiş belgeyi açmanıza olanak tanır.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Korumalı PPSM'u Java ile XLS'ye Dönüştür" %}}
PPSM dosyasını XLS'ye dönüştürürken, çıktı XLS dosya biçiminize de filigran ekleyebilirsiniz. Filigran eklemek için dönüştürülmüş HTML dosyasını açmak için yeni bir Çalışma Kitabı oluşturun. Dizini aracılığıyla Çalışma Sayfası'nı seçin, bir Şekil oluşturun ve addTextEffect işlevini kullanın, renkleri, şeffaflığı ve daha fazlasını ayarlayın. Bundan sonra HTML belgenizi Filigranlı XLS olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-fods/" name="PPSM İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xltm/" name="PPSM İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xlt/" name="PPSM İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xlam/" name="PPSM İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-markdown/" name="PPSM İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-excel/" name="PPSM İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-mhtml/" name="PPSM İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xlsb/" name="PPSM İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-ods/" name="PPSM İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-sxc/" name="PPSM İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xls/" name="PPSM İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xltx/" name="PPSM İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xlsx/" name="PPSM İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-tsv/" name="PPSM İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dif/" name="PPSM İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-xlsm/" name="PPSM İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-doc/" name="PPSM İle DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-docx/" name="PPSM İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-docm/" name="PPSM İle DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dot/" name="PPSM İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dotm/" name="PPSM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dotx/" name="PPSM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-odt/" name="PPSM İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-ott/" name="PPSM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-rtf/" name="PPSM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-word/" name="PPSM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-wordml/" name="PPSM İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-text/" name="PPSM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-flatopx/" name="PPSM İle FLAİlePX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}