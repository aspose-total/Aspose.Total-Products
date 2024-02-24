---
title: JSON Formatını .NET aracılığıyla PPS'ye dönüştürün
description: Microsoft PowerPoint kullanmadan JSON'u C# ile PPS'ye ayrıştırın
url_ignore: /tr/net/conversion/json-to-pps/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPS PPSX POWERPOINT POTM OTP PPTM PPSM PPT POT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="JSON Formatını C# ile PPS'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan JSON'u PPS'ye ayrıştırmak için C# API'si" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON'u herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında iki basit adımda PPS'ye dönüştürebilirsiniz. İlk olarak, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) kullanarak JSON'u PPTX'e ayrıştırabilirsiniz. Bundan sonra, [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i PPS'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON Formatını C# ile PPS'ye Dönüştür" %}}
1. Yeni bir [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) nesnesi oluşturun ve dosyadan geçerli JSON verilerini okuyun
2. [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) sınıfını ve [Save](https://reference.aspose.com/) kullanarak JSON dosyasını çalışma sayfasına aktarın cell/net/aspose.cells.workbook/save/methods/4) PPTX olarak
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi PPS biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarla ve JSON Formatını C# ile PPS'ye Dönüştür" %}}
JSON'u PPS'ye ayrıştırırken, [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) kullanarak JSON biçiminiz için düzen seçeneklerini de ayarlayabilirsiniz. Diziyi tablo olarak işlemenize, boş değerleri yoksaymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Tüm bu seçenekler, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Filigran ile JSON Formatını PPS'ye Dönüştür" %}}
API'yi kullanarak JSON'u filigranlı PPS'ye de dönüştürebilirsiniz. PPS belgenize filigran eklemek için önce JSON'u PPTX'e ayrıştırıp ona bir filigran ekleyebilirsiniz. Filigran eklemek için yeni oluşturulan PPTX dosyasını [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak yükleyin, ana sunumu seçin, kullanarak şekil tipi ekleyin AddAutoShape ve AddTextFrame kullanarak filigran metni ekleyin. Filigranı ekledikten sonra belgeyi PPS'ye kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}