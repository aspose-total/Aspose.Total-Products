---
title: C# API aracılığıyla PDF'yi XLTM'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan PDF Dosyasını XLTM'ye Dönüştürmek için C# API'si
url_ignore: /tr/net/conversion/pdf-to-xltm/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XLTM
otherformats: XLAM MD XLTM XLSM FODS ODS SXC TSV XLSB XLT DIF EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PDF'yi XLTM'ye Dönüştürmek için C# API'si" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan PDF Dosyasını C# aracılığıyla XLTM'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak PDF dosyasını herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında kolayca XLTM'ye dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak PDF'yi XLSX'e aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak XLSX'i XLTM'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF'yi XLTM'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak PDF dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak PDF'yi XLSX'e dönüştürün
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi XLTM formatına kaydedin ve 'Xltm'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı PDF'yi C# ile XLTM'ye Dönüştür" %}}
PDF belgeniz parola korumalıysa, parola olmadan XLTM'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfının yeni bir örneğini başlatabilir ve dosya adını ve parolayı argüman olarak iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PDF Dosyasını C# ile Filigran ile XLTM'ye Dönüştürün" %}}
PDF dosyasını XLTM'ye dönüştürürken, çıktı XLTM dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için yeni bir Çalışma Kitabı nesnesi oluşturabilir ve dönüştürülmüş XLSX belgesini açabilir, dizini aracılığıyla Çalışma Sayfası'nı seçebilir, bir Şekil oluşturabilir ve AddTextEffect işlevini kullanabilirsiniz. Bundan sonra XLSX belgenizi Filigranlı XLTM olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-sxc/" name="PDF İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xltx/" name="PDF İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-md/" name="PDF İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-tsv/" name="PDF İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-txt/" name="PDF İle TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-ods/" name="PDF İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xlt/" name="PDF İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xlsm/" name="PDF İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xlam/" name="PDF İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xltm/" name="PDF İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-dif/" name="PDF İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xlsb/" name="PDF İle XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}