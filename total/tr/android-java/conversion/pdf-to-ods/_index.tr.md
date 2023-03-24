---
title: Java aracılığıyla Android'de PDF'yi ODS'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan Java API aracılığıyla Android'de PDF'yi ODS'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: ODS
otherformats: XLTX CSV DIF TSV TXT XLTM SXC XLSM FODS XLT EXCEL XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de PDF'yi ODS'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader gerektirmeden Android uygulamalarında PDF'yi ODS'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
Android uygulamalarınızda PDF'den ODS'ye dönüştürme özelliğini iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) kullanarak PDF'yi XLSX'e çevirebilirsiniz. İkinci olarak, Güçlü Elektronik Tablo İşleme API'sini [Java üzerinden Android için Aspose.Cells](https://products.aspose.com/cells/android-java/) kullanarak XLSX'i ODS'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) ürün ailesi kapsamındadır. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF'yi ODS'ye Dönüştürmek için Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak PDF dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak PDF'yi XLSX'e dönüştürün yöntem
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) ve [Java aracılığıyla Aspose.Cells for Android](https://docs.aspose.com/cells) yükleyin /java/aspose-cells-for-android-via-java-installation/) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de PDF Dosyasının XMP Meta Verilerini Alın" %}}
[Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) bir PDF dosyasının XMP meta verilerine erişmenizi sağlar. Meta verileri almak için bir [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturun ve giriş PDF dosyasını açın ve [getMetadata()] öğesini kullanın. meta verileri almak için (https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) özelliği.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de ODS Belgesini koruyun" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), ihtiyaçlarınıza bağlı olarak ODS dosyanızın korunmasını destekler. Belgenizi korumak için [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) yöntemini kullanabilirsiniz [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfı.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-ods.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}