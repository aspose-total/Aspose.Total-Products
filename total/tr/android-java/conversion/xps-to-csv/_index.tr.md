---
title: Java aracılığıyla Android'de XPS'yi CSV'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan Java API aracılığıyla Android'de XPS'yi CSV'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: CSV
otherformats: XLSM FODS MD XLTX TSV XLAM TXT DIF SXC XLSB XLT XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de XPS'yi CSV'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader gerektirmeden Android uygulamalarında XPS'yi CSV'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
Android uygulamalarınızda XPS'den CSV'ye dönüştürme özelliğini iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) kullanarak XPS'yi XLSX'e çevirebilirsiniz. İkinci olarak, Güçlü Elektronik Tablo İşleme API'sini [Java üzerinden Android için Aspose.Cells](https://products.aspose.com/cells/android-java/) kullanarak XLSX'i CSV'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) ürün ailesi kapsamındadır. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS'yi CSV'ye Dönüştürmek için Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak XPS dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak XPS'yi XLSX'e dönüştürün ) yöntem
3. [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) ve [Java aracılığıyla Aspose.Cells for Android](https://docs.aspose.com/cells) yükleyin /java/aspose-cells-for-android-via-java-installation/) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de XPS Dosyasının XMP Meta Verilerini Alın" %}}
[Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) bir XPS dosyasının XMP meta verilerine erişmenizi sağlar. Meta verileri almak için bir [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturun ve giriş XPS dosyasını açın ve [getMetadata()] öğesini kullanın. meta verileri almak için (https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) özelliği.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de CSV Belgesini koruyun" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), ihtiyaçlarınıza bağlı olarak CSV dosyanızın korunmasını destekler. Belgenizi korumak için [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) yöntemini kullanabilirsiniz [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfı.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-csv.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xlsm/" name="XPS İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-fods/" name="XPS İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-md/" name="XPS İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xltx/" name="XPS İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-tsv/" name="XPS İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xlam/" name="XPS İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-txt/" name="XPS İle TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-dif/" name="XPS İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-sxc/" name="XPS İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xlsb/" name="XPS İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xlt/" name="XPS İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/xps-to-xltm/" name="XPS İle XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}