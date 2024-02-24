---
title: JSON Formatını .NET aracılığıyla DOT'ye dönüştürün
description: Microsoft Word kullanmadan JSON'u C# ile DOT'ye ayrıştırın
url_ignore: /tr/net/conversion/json-to-dot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOT
otherformats: DOT PCL MOBI WORD DOC DOTX FLATOPC PS RTF DOCM OTT ODT WORDML EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="JSON Formatını C# ile DOT'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> Word kullanmadan JSON'u DOT'ye ayrıştırmak için C# API'si" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında JSON'u DOT'ye iki basit şekilde ayrıştırabilirsiniz. adımlar. İlk olarak, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) kullanarak JSON'u PDF'ye aktarabilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak PDF'yi DOT'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON Formatını C# ile DOT'ye Dönüştür" %}}
1. Yeni bir [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) nesnesi oluşturun ve dosyadan geçerli JSON verilerini okuyun
2. [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) sınıfını ve [Save](https://reference.aspose.com/) kullanarak JSON dosyasını çalışma sayfasına aktarın cell/net/aspose.cells.workbook/save/methods/4) PDF olarak
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak PDF belgesi yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) yöntemini kullanarak dokümanı DOT formatında kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarla ve JSON Formatını C# ile DOT'ye Dönüştür" %}}
JSON'u DOT'ye ayrıştırırken, [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) kullanarak JSON'unuz için düzen seçeneklerini de ayarlayabilirsiniz. Diziyi bir tablo olarak işlemenize, boş değerleri yoksaymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Tüm bu seçenekler, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Filigran ile JSON Formatını DOT'ye Ayrıştırma" %}}
API'yi kullanarak JSON'u filigranla DOT'ye de dönüştürebilirsiniz. DOT belgenize filigran eklemek için önce JSON dosyasını PDF'ye ayrıştırıp ona bir filigran ekleyebilirsiniz. Filigran eklemek için yeni oluşturulan PDF dosyasını [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve özelliklerini ayarlayın, Watermark.SetText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin. Filigranı ekledikten sonra belgeyi DOT'ye kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}