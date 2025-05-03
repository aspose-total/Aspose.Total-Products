---
title: EPUB'yi C# API aracılığıyla PPTM'ye aktarın
description: Microsoft Word kullanmadan EPUB'yi PPTM'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/epub-to-pptm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPTM
otherformats: PPS SWF POT OTP PPSM POTX PPSX PPT POTM PPTM POWERPOINT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EPUB'yi .NET üzerinden PPTM'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta EPUB'yi PPTM'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak EPUB'yi iki basit adımda PPTM'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak EPUB dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i PPTM'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB'yi PPTM'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak EPUB dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak EPUB'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi PPTM formatına kaydedin ve 'Pptm'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla EPUB Dosyasından XMP Meta Verilerini Alın" %}}[Document]
EPUB'yi PPTM'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir EPUB dosyasının XMP meta verilerine erişmenizi sağlar. Bir EPUB dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi EPUB dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur PPTM Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, PPTM dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pptm", SaveFormat.Pptm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EPUB Dosyasını Programatik Olarak PPTM'e Dönüştürme: Kullanım Örnekleri" %}}
EPUB dosyası, dijital içerikleri depolamak için kullanılır. Bu formatlar, yayın ve yazılmış materyallerin dağıtılmasında ideal bir şekilde kullanılır. Ancak, etkileşimli sunumlar sırasında .pptm formatları, dinleyicileri etkileyen ve karmaşık bilgileri iletmek için zorunlu hale gelir. Bu reason of why EPUB dosyalarının .PPTM formatına çevirmesi gerekiyor.

Bu çevrim, size şunları yapmamızı sağlar:

- **Eğitim sunumları oluşturmak için EPUB dosyalarını etkileşimli eğitim içeriği olarak kullanın, dersler, rehberler ve çalışma malzemeleriyle birlikte.**
- **İşverici eğitim oturumları, seminerler ve çalışanlar için sunular oluşturarak etkileyici bir şekilde işverici eğitim geliştirin.**
- **Konferans materyallerini EPUB dosyalarını kullanarak tamamlı konferans malzemeleri oluşturun, sunular, takdimler ve katkı notları ile birlikte.**
- **Önline kurs içeriğini .PPTM formatında kullanarak ders slaytları, görevler ve etkileşimli testler ile online eğitim verin.**
- **Çarpanlık sunumları oluşturmak için EPUB dosyalarını kullanarak ürün demo'ları, satış malzemeleri ve etkileyici bir şekilde pazarlama sunumları oluşturun.**
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}