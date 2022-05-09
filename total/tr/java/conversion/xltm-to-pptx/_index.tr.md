---
title: Java kullanarak XLTM'yi PPTX'ye dönüştürün
description: Excel veya Word kullanarak XLTM'yi PPTX'a Dışa Aktarmak için Java API
url_ignore: /tr/java/conversion/xltm-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: WORD POWERPOINT PPTXX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XLTM'yi PPTX'a Dışa Aktarmak için Java API" h2="Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
XLTM'yi PPTX'ye işlemek iki adımlı bir işlemdir. Verilen XLTM belgesini PDF'ye dönüştürmek için önce [Aspose.Cells for Java](https://products.aspose.com/cells/java) API'sini ve ardından [Aspose.Pdf for Java](https) kullanacaksınız. ://products.aspose.com/pdf/java) API ile PDF belgenizi kolayca PPTX'a dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) dosya formatı otomasyon kitaplıklarının koleksiyonuna dahildir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API ile XLTM'yi PPTX'ye Dönüştürme" %}}
1. [Çalışma Kitabı](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLTM dosyasını açın
2. XLTM'yi PDF'ye dönüştürün ve SaveFormat'ı AUTO olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) kullanarak PPTX biçiminde kaydedin-) yöntemi ve Pptx'u SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xltm-to-pptxx/" name="XLTM İle PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xltm-to-pptx/" name="XLTM İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xltm-to-powerpoint/" name="XLTM İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xltm-to-word/" name="XLTM İle WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}