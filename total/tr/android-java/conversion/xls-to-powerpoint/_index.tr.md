---
title: Android'de XLS'yi POWERPOINT'a aktarın
description: Microsoft Word kullanmadan XLS'yi POWERPOINT'ye dönüştürmek için Android API
url: /tr/android-java/conversion/xls-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: PPTX DOC DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de XLS'yi POWERPOINT'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Excel kullanmadan Android Uygulamalarınızda XLS'yi POWERPOINT'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java aracılığıyla Android için Aspose.Total](https://products.aspose.com/total/android-java/) güçlü bir Dosya Otomasyonu API'leri paketidir. API'lerinden ikisini kullanarak, Android uygulamalarınıza XLS'den POWERPOINT'a dönüştürme özelliğini entegre edebilirsiniz. İlk adımda, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) kullanarak XLS'yi PDF'ye aktarabilirsiniz. Bundan sonra, [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) kullanarak PDF'yi POWERPOINT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLS'yi POWERPOINT'a Dışa Aktarmak için Android API" %}}
1. [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLS dosyasını açın
2. XLS'yi PDF'ye dönüştürün ve SaveFormat'ı AUTO olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions) kullanarak POWERPOINT biçiminde kaydedin -) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.PDF for Android](https://powerpoints.aspose.com/pdf/androidjava/installation/) ve [Java aracılığıyla Aspose.Cells for Android](https://powerpoints.aspose.com/cells) yükleyin /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de XLS Dosyasından Özel Özellikleri Kaldır" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) belge dönüştürmenin yanı sıra tonlarca başka özellik de sağlar. Dönüştürme işleminden önce, XLS belgesinin özel özelliklerini kaldırabilirsiniz. Özel özellikleri kaldırmak için [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) yöntemini çağırın ve adını iletin. kaldırılacak belge özelliği.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xls-to-pptx/" name="XLS İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xls-to-powerpoint/" name="XLS İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xls-to-powerpointx/" name="XLS İle POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xls-to-word/" name="XLS İle WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}