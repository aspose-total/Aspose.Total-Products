---
title: JSON Formatını .NET aracılığıyla DICOM'ye dönüştürün
description: Üçüncü taraf bağımlılıklarını kullanmadan JSON'u C#'ta DICOM'ye ayrıştırın
url_ignore: /tr/net/conversion/json-to-dicom/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DICOM
otherformats: DICOM IMAGE SVGZ TGA WMZ WMF PSD EMZ DXF JPEG2000
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="JSON Formatını C# ile DICOM'ye Dönüştür" h2="Üçüncü taraf bağımlılıklarını kullanmadan JSON'u DICOM'ye ayrıştırmak için C# API'si" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında JSON'u DICOM'ye iki basit şekilde ayrıştırabilirsiniz. adımlar. İlk olarak, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) kullanarak JSON'u JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) kullanarak JPEG'i DICOM'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON Formatını C# ile DICOM'ye Dönüştür" %}}
1. Yeni bir [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) nesnesi oluşturun ve dosyadan JSON verilerini okuyun
2. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak JSON'u JPEG'e dönüştürün
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak JPEG belgesi yükleyin
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak belgeyi DICOM formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarla ve JSON Formatını C# ile DICOM'ye Dönüştür" %}}
JSON'u DICOM'ye ayrıştırırken, [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) kullanarak JSON'unuz için düzen seçeneklerini de ayarlayabilirsiniz. Diziyi bir tablo olarak işlemenize, boş değerleri yoksaymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Tüm bu seçenekler, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Filigran ile JSON Formatını DICOM'ye Ayrıştırma" %}}
API'yi kullanarak, DICOM belgenizdeki filigranlı JSON'u DICOM'ye de dönüştürebilirsiniz. Filigran eklemek için önce JSON belgenizi JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. İşlemi göstermek için dönüştürülmüş JPEG görüntünüzü yükleyebilir, Matrix sınıfının bir nesnesini kullanarak dönüşümler ekleyebilir ve [Grafikler](https://reference.aspose.com/imaging/) kullanarak görüntü yüzeyine filigran olarak bir dize çizebilirsiniz. net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) yöntemi. Filigranı ekledikten sonra JPEG'i DICOM formatında kaydedebilirsiniz. Aşağıda, belgenize nasıl çapraz filigran ekleneceğini gösteren bir kod örneği verilmiştir. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}