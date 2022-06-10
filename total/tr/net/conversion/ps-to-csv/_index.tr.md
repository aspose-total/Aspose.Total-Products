---
title: C# API aracılığıyla PS'yi CSV'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan PS Dosyasını CSV'ye Dönüştürmek için C# API'si
url_ignore: /tr/net/conversion/ps-to-csv/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: CSV
otherformats: SXC XLTM TXT XLSB XLAM TSV XLT FODS XLSM DIF EXCEL MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PS'yi CSV'ye Dönüştürmek için C# API'si" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan PS Dosyasını C# aracılığıyla CSV'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak PS dosyasını herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında kolayca CSV'ye dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak PS'yi XLSX'e aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak XLSX'i CSV'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS'yi CSV'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak PS dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak PS'yi XLSX'e dönüştürün
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi CSV formatına kaydedin ve 'Csv'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı PS'yi C# ile CSV'ye Dönüştür" %}}
PS belgeniz parola korumalıysa, parola olmadan CSV'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfının yeni bir örneğini başlatabilir ve dosya adını ve parolayı argüman olarak iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PS Dosyasını C# ile Filigran ile CSV'ye Dönüştürün" %}}
PS dosyasını CSV'ye dönüştürürken, çıktı CSV dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için yeni bir Çalışma Kitabı nesnesi oluşturabilir ve dönüştürülmüş XLSX belgesini açabilir, dizini aracılığıyla Çalışma Sayfası'nı seçebilir, bir Şekil oluşturabilir ve AddTextEffect işlevini kullanabilirsiniz. Bundan sonra XLSX belgenizi Filigranlı CSV olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-sxc/" name="PS İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-xltx/" name="PS İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-md/" name="PS İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-tsv/" name="PS İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-txt/" name="PS İle TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-ods/" name="PS İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-xlt/" name="PS İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-xlsm/" name="PS İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-xlam/" name="PS İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-xltm/" name="PS İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-dif/" name="PS İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ps-to-xlsb/" name="PS İle XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}