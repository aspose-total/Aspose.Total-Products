---
title: CGM'yi C# API aracılığıyla PPS'ye aktarın
description: Microsoft Word kullanmadan CGM'yi PPS'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPS PPTM POWERPOINT PPT PPSX XAML POTM POTX SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM'yi .NET üzerinden PPS'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta CGM'yi PPS'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak CGM'yi iki basit adımda PPS'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak CGM dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i PPS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi PPS'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak CGM dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak CGM'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi PPS formatına kaydedin ve 'Pps'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla CGM Dosyasından XMP Meta Verilerini Alın" %}}[Document]
CGM'yi PPS'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir CGM dosyasının XMP meta verilerine erişmenizi sağlar. Bir CGM dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi CGM dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur PPS Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, PPS dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını Programatik Olarak PPS'e Dönüştürme: Kullanım Örnekleri" %}}
CGM (Bilgisayar Grafik Meta Dosyaları) dosyası, vektör grafik bilgisi kaydı olarak kullanılarak oluşturulan statik grafikler ve illüstrasyonlar için ideal bir formattır. Ancak, dinamik veri işleme başladığımızda tablolar gibi Excel programlarını kullanarak veri vizualizasyonu ve analiz işlemleri yapılması daha uygun olur.

CGM dosyalarını PPS (Portable Presentation) formatına çevirmek, sunumların ve vizualizasyonların tam potansiyelini açığa çıkarmak için zorunlu bir adımdır. Bu çevirme, aşağıdaki işlevleri sağlamaktadır:

**Kullanım Durumları:**

*   **Sunum Tasarımı**: CGM dosyalarını PPS formatına çevirmekle profesyonel görünüşlü slaytlar, animasyonlar ve geçişler oluşturabilirsiniz.
*   **Eğitim ve Öğretim Materyali**: PPS formatını kullanarak etkileşimli eğitim malzemeleri, simülasyonlar ve rehber kitapçıkları oluşturarak öğrenme sonuçlarını artırabilirsiniz.
*   **Pazarlama ve Satış Malzemeri**: CGM dosyalarını pazarlama kollektifleri, ürün demo'ları ve pazarlama materyalleri olarak çevirmekle ikna edici satış malzemesi oluşturabilirsiniz.
*   **Şirket İnlü Materyali**: PPS formatını kullanarak iç iletişim, raporlar ve grafipler oluşturarak bilgi paylaşımını daha iyi yapabilirsiniz.
*   **Organizasyon ve Sergi Gösterimleri**: CGM dosyalarını etkileyici organizasyon grafikleri, stand tasarımı ve fuar göstergileri olarak çevirmekle göz alırmazsınız.

CGM dosyalarını PPS formatına çevirmek,最新 sunum yazılımının özelliklerini kullanmanıza izin verir. Bu çevirme, profesyonel derecede sunumlar oluşturmak için zorunlu bir adımdır. Her projenizde profesyonel derecedeki sunumlar gerektiğinde bu adımın önemli olduğunu unutmamalıyız.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}