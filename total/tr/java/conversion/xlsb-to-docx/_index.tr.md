---
title: Java kullanarak XLSB'yi DOCX'ye dönüştürün
description: Excel veya Word kullanarak XLSB'yi DOCX'a Dışa Aktarmak için Java API
url_ignore: /tr/java/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCXX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XLSB'yi DOCX'a Dışa Aktarmak için Java API" h2="Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
XLSB'yi DOCX'ye işlemek iki adımlı bir işlemdir. Verilen XLSB belgesini PDF'ye dönüştürmek için önce [Aspose.Cells for Java](https://products.aspose.com/cells/java) API'sini ve ardından [Aspose.Pdf for Java](https) kullanacaksınız. ://products.aspose.com/pdf/java) API ile PDF belgenizi kolayca DOCX'a dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) dosya formatı otomasyon kitaplıklarının koleksiyonuna dahildir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API ile XLSB'yi DOCX'ye Dönüştürme" %}}
1. [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSB dosyasını açın
2. XLSB'yi PDF'ye dönüştürün ve SaveFormat'ı AUTO olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) kullanarak DOCX biçiminde kaydedin-) yöntemi ve Docx'u SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xlsb-to-docxx/" name="XLSB İle DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xlsb-to-pptx/" name="XLSB İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xlsb-to-powerpoint/" name="XLSB İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xlsb-to-word/" name="XLSB İle WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}