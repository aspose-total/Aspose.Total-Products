---
title: C# API aracılığıyla CGM'yi SVGZ'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan CGM'yi .NET uygulamalarınızda SVGZ'ye aktarın
url_ignore: /tr/net/conversion/cgm-to-svgz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SVGZ
otherformats: TGA JPEG2000 IMAGE SVGZ WMF  WMZ PSD EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM dosyasını C# ile SVGZ'ye dönüştürün" h2="Adobe<sup>&reg;</sup> Acrobat Reader veya diğer üçüncü taraf uygulamaları kullanmadan CGM'yi .NET uygulamaları içinde SVGZ'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak, iki basit adımda herhangi bir .NET uygulamasında CGM'yi SVGZ görüntüsüne kolayca aktarabilirsiniz. Her şeyden önce, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak CGM'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Görüntü İşleme API'sini kullanarak JPEG'i SVGZ'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM dosyasını .NET aracılığıyla SVGZ'ye dönüştürün" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak CGM dosyasını açın
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) yöntemi
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak JPEG dosyasını yükleyin
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak belgeyi SVGZ formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C# ile CGM Dosyasını Tek Bir Dosyada SVGZ'ye Dönüştürün" %}}
API'yi kullanarak, CGM dosyasını SVGZ'ye tek bir görüntü dosyasına da dönüştürebilirsiniz. Tüm sayfaları dönüştürmek için önce CGM belgenizi bir TIFF dosyasına dönüştürebilir ve ardından TIFF dosyasını SVGZ'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) TiffDevice yöntemini kullanarak tek bir TIFF görüntüsü alabilirsiniz. apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) sınıfı. Son olarak, [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak TIFF dosyasını yükleyebilirsiniz.
ve [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak SVGZ formatına kaydedin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını C# ile SVGZ'ye Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı SVGZ görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.RotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfı tarafından sunulan fabrika yöntemini kullanarak dönüştürülmüş JPEG görüntüsünü yükleyebilir ve Görüntüyü çağırabilirsiniz. .RotateFlip yöntemi, uygun [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) belirtilirken. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını Programatik Olarak SVGZ'e Dönüştürme: Kullanım Örnekleri" %}}
CGM (Computer Graphics Metafile) dosya formatları, vektör grafik bilgisi kaydı oluşturmak için kullanılır. Bu formatlar, statik grafikler ve illüstrasyonların oluşturulmasında idealdir. Ancak, dinamik veri işlemleri sırasında tablolar gibi spreadsheet programları gibi araçlar zorunlu hale gelirken, bu verilerin vizualizasyonu ve analizi için büyük bir ihtiyaç haline gelir.

CGM dosya formatlarını SVGZ formatına çevirmek, vektör grafiklerinizi daha fazla potansiyel kullanmanıza yardımcı olur. Bu çevrim, size以下用途ları gerçekleştirmeniz sağlar:

**Kullanım Durumları:**

- **Statik Grafik Oluşturma**: CGM dosyalarını yüksek kalitede statik grafikler, illüstrasyonlar ve logolar oluşturmak için çeviriniz.
- **Marka ve Kimlik Tasarımı**: SVGZ formatını kullanarak marka kimlikleri, ikonlar ve görsellerinizi tasarlamağa izin verir. Bu grafikler boyut değişikliğine uğradığında da niteliğinde bozulmama sahiptir.
- **Ambalaj ve Etiket Tasarımı**: CGM dosyalarını ambalaj ve etiket tasarımı için çeviriniz, mağazada dikkat çekici ve görsel bir izlenim oluşturabilir.
- **Dijital Varlıklar Yönetimi**: CGM dosyalarını SVGZ formatında depolarak, dijital varlıkların yönetimini daha etkili hale getirirsiniz. Bu format, ekipmanlar arasında kolayca paylaşılabilir ve erişilebilir.
- **Web ve Mobil Cihazlarda Optimize Edilmiş Grafikler**: SVGZ formatını kullanarak CGM dosyalarını web ve mobil cihazlarda hızlı yüklenme ve yüksek kalitede görüntüler elde edebilirsiniz.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}