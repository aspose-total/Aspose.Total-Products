---
title: C# API aracılığıyla CGM'yi TXT'ye dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan CGM Dosyasını TXT'ye Dönüştürmek için C# API'si
url_ignore: /tr/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM'yi TXT'ye Dönüştürmek için C# API'si" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan CGM Dosyasını C# aracılığıyla TXT'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak CGM dosyasını herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında kolayca TXT'ye dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak CGM'yi XLSX'e aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak XLSX'i TXT'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi TXT'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak CGM dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak CGM'yi XLSX'e dönüştürün
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak XLSX belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi TXT formatına kaydedin ve 'Txt'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı CGM'yi C# ile TXT'ye Dönüştür" %}}
CGM belgeniz parola korumalıysa, parola olmadan TXT'ye dönüştüremezsiniz. API'yi kullanarak, korumalı belgeyi önce geçerli bir şifre kullanarak açabilir ve ardından dönüştürebilirsiniz. Şifrelenmiş dosyayı açmak için [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfının yeni bir örneğini başlatabilir ve dosya adını ve parolayı argüman olarak iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını C# ile Filigran ile TXT'ye Dönüştürün" %}}
CGM dosyasını TXT'ye dönüştürürken, çıktı TXT dosya biçiminize filigran da ekleyebilirsiniz. Filigran eklemek için yeni bir Çalışma Kitabı nesnesi oluşturabilir ve dönüştürülmüş XLSX belgesini açabilir, dizini aracılığıyla Çalışma Sayfası'nı seçebilir, bir Şekil oluşturabilir ve AddTextEffect işlevini kullanabilirsiniz. Bundan sonra XLSX belgenizi Filigranlı TXT olarak kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını Programatik Olarak TXT'e Dönüştürme: Kullanım Örnekleri" %}}
CGM (Computer Graphics Metafile) dosya formatı, vektör grafik bilgilerini kaydetmek için kullanılır ve statik görseller ve illüstrasyonların oluşturulmasında idealdir. Ancak dinamik veri işleme sırasında metin editörleri gibi araçlar, temel metin işleme ve belgeleme süreçlerinde kullanılmaya başlar.

CGM dosyalarının ham metin formatlarına çevrilmesi, metin düzenleme yeteneklerini açmak için zorunludur. Bu çevrim, aşağıdaki işlevleri sağlar:

**Kullanım Durumları:**

*   **Veri Dökümantasyonu**: CGM dosyalarını ham metin olarak çevirmekle insan okunabilir belge oluşturulur, bu da grafik bilgilerinin daha kolay anlaşılmasını ve paylaşılmasını sağlar.
*   **Metin İşleme**: Notepad gibi editörlerle ham metin verileri düzenlenebilir hale gelir, temel metin işleme süreçlerinde kullanılabilir.
*   **ASCII Sanatı Oluşturma**: CGM dosyaları ASCII sanatı olarak çevrilerek basitleştirilmiş görsel ifadeler oluşturulur, bu da sanatsal veya dekoratif amaçlarla kullanılır.
*   **Diğer Araçlarda Veri Girişi**: Ham metin formatına çevrilmiş grafik bilgilerini diğer metin editörlerine veya yazım araçlarına aktararak genişletilmiş metin işleme yetenekleri sağlar.
*   **Temel Rapor ve Hataba**: CGM dosyaları ham metin olarak çevrilmekle temel raporlar ve hataba kaydı oluşturulur, bu da geliştirme sürecinde hataları belirlemek için yardımcı olur.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}