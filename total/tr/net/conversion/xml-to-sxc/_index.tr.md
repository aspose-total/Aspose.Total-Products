---
title: C# API aracılığıyla XML'yi SXC'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan XML Dosyasını SXC'ye Dönüştürmek için C# API'si
url_ignore: /tr/net/conversion/xml-to-sxc/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: SXC
otherformats: EXCEL FODS MD ODS XLT TXT SXC XLTM XLAM XLSM XLTX XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XML'yi SXC'ye Dönüştürmek için C# API'si" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan XML Dosyasını C# aracılığıyla SXC'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak XML dosyasını herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında kolayca SXC'ye dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak XML'yi XLSX'e aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak XLSX'i SXC'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XML'yi SXC'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak XML dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak XML'yi XLSX'e dönüştürün
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi SXC formatına kaydedin ve 'Sxc'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı XML'yi C# ile SXC'ye Dönüştür" %}}
XML belgeniz parola korumalıysa, parola olmadan SXC'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfının yeni bir örneğini başlatabilir ve dosya adını ve parolayı argüman olarak iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XML Dosyasını C# ile Filigran ile SXC'ye Dönüştürün" %}}
XML dosyasını SXC'ye dönüştürürken, çıktı SXC dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için yeni bir Çalışma Kitabı nesnesi oluşturabilir ve dönüştürülmüş XLSX belgesini açabilir, dizini aracılığıyla Çalışma Sayfası'nı seçebilir, bir Şekil oluşturabilir ve AddTextEffect işlevini kullanabilirsiniz. Bundan sonra XLSX belgenizi Filigranlı SXC olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}