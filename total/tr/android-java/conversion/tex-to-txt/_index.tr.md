---
title: Java aracılığıyla Android'de TEX'yi TXT'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan Java API aracılığıyla Android'de TEX'yi TXT'ye dönüştürün
url: /tr/android-java/conversion/tex-to-txt/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: TXT
otherformats: SXC MD XLTM TSV XLSB XLT ODS FODS DIF XLAM XLTX XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de TEX'yi TXT'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader gerektirmeden Android uygulamalarında TEX'yi TXT'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
Android uygulamalarınızda TEX'den TXT'ye dönüştürme özelliğini iki aşamalı bir süreçte entegre edebilirsiniz. İlk olarak, [Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) kullanarak TEX'yi XLSX'e çevirebilirsiniz. İkinci olarak, Güçlü Elektronik Tablo İşleme API'sini [Java üzerinden Android için Aspose.Cells](https://products.aspose.com/cells/android-java/) kullanarak XLSX'i TXT'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) ürün ailesi kapsamındadır. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX'yi TXT'ye Dönüştürmek için Android API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak TEX dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak TEX'yi XLSX'e dönüştürün ) yöntem
3. [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. Belgeyi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) ve [Java aracılığıyla Aspose.Cells for Android](https://docs.aspose.com/cells) yükleyin /java/aspose-cells-for-android-via-java-installation/) uygulamalarınızda.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de TEX Dosyasının XMP Meta Verilerini Alın" %}}
[Java üzerinden Android için Aspose.PDF](https://products.aspose.com/pdf/android-java/) bir TEX dosyasının XMP meta verilerine erişmenizi sağlar. Meta verileri almak için bir [Belge](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturun ve giriş TEX dosyasını açın ve [getMetadata()] öğesini kullanın. meta verileri almak için (https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) özelliği.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de TXT Belgesini koruyun" %}}
[Java aracılığıyla Android için Aspose.Cells](https://products.aspose.com/cells/android-java/), ihtiyaçlarınıza bağlı olarak TXT dosyanızın korunmasını destekler. Belgenizi korumak için [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) yöntemini kullanabilirsiniz [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfı.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-txt.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-sxc/" name="TEX İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-md/" name="TEX İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xltm/" name="TEX İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-tsv/" name="TEX İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xlsb/" name="TEX İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xlt/" name="TEX İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-ods/" name="TEX İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-fods/" name="TEX İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-dif/" name="TEX İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xlam/" name="TEX İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xltx/" name="TEX İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xlsm/" name="TEX İle XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}