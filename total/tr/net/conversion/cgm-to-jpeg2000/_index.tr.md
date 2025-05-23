---
title: C# API aracılığıyla CGM'yi JPEG2000'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan CGM'yi .NET uygulamalarınızda JPEG2000'ye aktarın
url_ignore: /tr/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM dosyasını C# ile JPEG2000'ye dönüştürün" h2="Adobe<sup>&reg;</sup> Acrobat Reader veya diğer üçüncü taraf uygulamaları kullanmadan CGM'yi .NET uygulamaları içinde JPEG2000'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak, iki basit adımda herhangi bir .NET uygulamasında CGM'yi JPEG2000 görüntüsüne kolayca aktarabilirsiniz. Her şeyden önce, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak CGM'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Görüntü İşleme API'sini kullanarak JPEG'i JPEG2000'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM dosyasını .NET aracılığıyla JPEG2000'ye dönüştürün" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak CGM dosyasını açın
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) yöntemi
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak JPEG dosyasını yükleyin
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak belgeyi JPEG2000 formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C# ile CGM Dosyasını Tek Bir Dosyada JPEG2000'ye Dönüştürün" %}}
API'yi kullanarak, CGM dosyasını JPEG2000'ye tek bir görüntü dosyasına da dönüştürebilirsiniz. Tüm sayfaları dönüştürmek için önce CGM belgenizi bir TIFF dosyasına dönüştürebilir ve ardından TIFF dosyasını JPEG2000'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) TiffDevice yöntemini kullanarak tek bir TIFF görüntüsü alabilirsiniz. apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) sınıfı. Son olarak, [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak TIFF dosyasını yükleyebilirsiniz.
ve [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak JPEG2000 formatına kaydedin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını C# ile JPEG2000'ye Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı JPEG2000 görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.RotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfı tarafından sunulan fabrika yöntemini kullanarak dönüştürülmüş JPEG görüntüsünü yükleyebilir ve Görüntüyü çağırabilirsiniz. .RotateFlip yöntemi, uygun [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) belirtilirken. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını Programatik Olarak JPEG2000'e Dönüştürme: Kullanım Örnekleri" %}}
CGM (Computer Graphics Metafile) dosyası, vektör grafik bilgilerini kaydetmek için kullanılır. Bu, statik görsel ve illüstrasyon oluşturmak için ideal bir çözüm sağlar. Ancak dinamik verilerle çalışan durumlarda ise JPEG 2000 formatları gibi daha üstün sıkıştırma ve kalite özellikleri ile avantajlıdır.

CGM dosyalarını JPEG 2000 formatına çevirmek, resim sıkıştırma ve kalite yeteneklerinizi maksimuma çıkarmak için zorunlu bir adımdır. Bu çevrim, aşağıdaki işlevleri gerçekleştirmenize yardımcı olur:

**Kullanım Durumları:**

*   **Yüksek Kalitede Resim Düzenleme**: CGM dosyalarını yüksek kaliteli resimler oluşturmak, web için optimize etmek ve tüm pazarlama malzemelerinde tutarlı bir marka görüntüğü sağlamak için kullanabilirsiniz.
*   **Arşivleme ve Koruma Uygulamaları**: JPEG 2000 formatını kullanarak büyük bir resim verisetini sıkıştırmak ve kaydetmek, değerli görsel içerikleri uzun süreli olarak korumak ve erişilebilirlir hale getirmek için ideal bir yoludur.
*   **Tibbi Görünteleme ve Diagnostik**: CGM dosyalarını tibbi görüntüler oluşturmak için kullanabilirsiniz. Bu, detaylı ve yüksek kaliteli tibbi görüntüler oluşturarak hataları azaltır ve hastalara daha iyi sonuçlar sağlar.
*   **El Sanatları ve Yayın Uygulamaları**: JPEG 2000 formatını kullanarak büyük bir bilim resim verisetini sıkıştırmak ve yayınlamak,全球 iş birliklerini destekleyerek bilgi paylaşımını kolaylaştırır.
*   **Dijital Kütüphaneler ve Arşivler**: CGM dosyalarını dijital kütüphanelerde ve arşivlerde kullanmak, kültürel mirasları ve tarihsel objeyi gelecek kuşaklara aktarabilme yeteneklerini sağlar.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}