---
title: C# API aracılığıyla XPS'yi XLTX'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan XPS Dosyasını XLTX'ye Dönüştürmek için C# API'si
url: /tr/net/conversion/xps-to-xltx/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: XLTX
otherformats: TSV DIF XLSB ODS MD XLTM TXT XLT XLAM XLTX SXC EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XPS'yi XLTX'ye Dönüştürmek için C# API'si" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan XPS Dosyasını C# aracılığıyla XLTX'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak XPS dosyasını herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında kolayca XLTX'ye dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak XPS'yi XLSX'e aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak XLSX'i XLTX'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS'yi XLTX'ye Dönüştürmek için .NET API" %}}
1. [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak XPS dosyasını açın
2. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak XPS'yi XLSX'e dönüştürün
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi XLTX formatına kaydedin ve 'Xltx'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı XPS'yi C# ile XLTX'ye Dönüştür" %}}
XPS belgeniz parola korumalıysa, parola olmadan XLTX'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfının yeni bir örneğini başlatabilir ve dosya adını ve parolayı argüman olarak iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XPS Dosyasını C# ile Filigran ile XLTX'ye Dönüştürün" %}}
XPS dosyasını XLTX'ye dönüştürürken, çıktı XLTX dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için yeni bir Çalışma Kitabı nesnesi oluşturabilir ve dönüştürülmüş XLSX belgesini açabilir, dizini aracılığıyla Çalışma Sayfası'nı seçebilir, bir Şekil oluşturabilir ve AddTextEffect işlevini kullanabilirsiniz. Bundan sonra XLSX belgenizi Filigranlı XLTX olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-sxc/" name="XPS İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-xltx/" name="XPS İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-md/" name="XPS İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-tsv/" name="XPS İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-txt/" name="XPS İle TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-ods/" name="XPS İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-xlt/" name="XPS İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-xlsm/" name="XPS İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-xlam/" name="XPS İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-xltm/" name="XPS İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-dif/" name="XPS İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-xlsb/" name="XPS İle XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}