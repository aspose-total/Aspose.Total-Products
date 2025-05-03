---
title: PS'yi C# API aracılığıyla XAML'ye aktarın
description: Microsoft Word kullanmadan PS'yi XAML'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PS'yi .NET üzerinden XAML'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta PS'yi XAML'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak PS'yi iki basit adımda XAML'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak PS dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i XAML'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS'yi XAML'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak PS dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak PS'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi XAML formatına kaydedin ve 'Xaml'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla PS Dosyasından XMP Meta Verilerini Alın" %}}[Document]
PS'yi XAML'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir PS dosyasının XMP meta verilerine erişmenizi sağlar. Bir PS dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi PS dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur XAML Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, XAML dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PS Dosyasını Programatik Olarak XAML'e Dönüştürme: Kullanım Örnekleri" %}}
PS (Portable Document Format) dosyaları, vektör grafik bilgilerini kaydedip oluşturmak için ideal hale gelen bir formattır. Bu nedenle statik grafikler, logolar ve illüstrasyonlar oluşturmak için kullanılmaktadır. Ancak dinamik veri ile çalışan uygulamalarda XAML (Extensible Application Markup Language), kullanıcı arayüzü ve uygulamalar oluşturmak için zorunlu hale gelir.

PS dosyaları XAML formatına çevirmek, uygulama geliştirme yeteneklerinizi açmağa yardımcı olur. Bu çevrim, aşağıdaki işlevleri gerçekleştirmenize izin verir:

**Kullanım Durumları:**

* **Mobil Uygulama Geliştirme**: Intüitif kullanıcı arayüzü oluşturmak için nativ mobil uygulamalar oluşturabilir ve XAML'in gücünü kullanarak kullanıcının keyfi bir deneyim yaşamasına yardımcı olabilir.
* **Desktop Uygulama Geliştirme**: XAML'in veri bağlantısı, animasyon ve şablonlaşma yeteneklerini kullanarak güçlü ve ölçeklenebilir desktop uygulamaları oluşturabilir.
* **UI Komponent Library'leri**: PS dosyalarını XAML formatına çevirmek suretiyle reusable UI komponentleri, such as buttons, text fields ve menüler oluşturabilir.
* **3D Grafik ve Animasyon**: XAML ile 3D grafikler ve animasyonlar uygulamalarınızda hayata geçirebilirsiniz.
* **Erişilebilirlik ve özelleştirme**: PS dosyalarını XAML formatına çevirmek suretiyle erişilebilir ve özelleştirilebilir UI elemanları oluşturabilir, böylece uygulamalarınız farklı kullanıcı gereksinimleri ve tercihlerine uygun hale gelir.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}