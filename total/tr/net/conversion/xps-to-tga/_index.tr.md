---
title: C# API aracılığıyla XPS'yi TGA'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan XPS'yi .NET uygulamalarınızda TGA'ye aktarın
url: /tr/net/conversion/xps-to-tga/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: TGA
otherformats: EMZ SVGZ PSD TGA DXF WMF JPEG2000 IMAGE WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XPS dosyasını C# ile TGA'ye dönüştürün" h2="Adobe<sup>&reg;</sup> Acrobat Reader veya diğer üçüncü taraf uygulamaları kullanmadan XPS'yi .NET uygulamaları içinde TGA'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak, iki basit adımda herhangi bir .NET uygulamasında XPS'yi TGA görüntüsüne kolayca aktarabilirsiniz. Her şeyden önce, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak XPS'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Görüntü İşleme API'sini kullanarak JPEG'i TGA'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS dosyasını .NET aracılığıyla TGA'ye dönüştürün" %}}
1. [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak XPS dosyasını açın
2. [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) sınıf nesnesini başlatın ve [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) yöntemi
3. [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak JPEG dosyasını yükleyin
4. [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak belgeyi TGA formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C# ile XPS Dosyasını Tek Bir Dosyada TGA'ye Dönüştürün" %}}
API'yi kullanarak, XPS dosyasını TGA'ye tek bir görüntü dosyasına da dönüştürebilirsiniz. Tüm sayfaları dönüştürmek için önce XPS belgenizi bir TIFF dosyasına dönüştürebilir ve ardından TIFF dosyasını TGA'ye aktarabilirsiniz. Giriş dosyasını [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) TiffDevice yöntemini kullanarak tek bir TIFF görüntüsü alabilirsiniz. apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) sınıfı. Son olarak, [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak TIFF dosyasını yükleyebilirsiniz.
ve [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak TGA formatına kaydedin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XPS Dosyasını C# ile TGA'ye Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı TGA görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.RotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) sınıfı tarafından sunulan fabrika yöntemini kullanarak dönüştürülmüş JPEG görüntüsünü yükleyebilir ve Görüntüyü çağırabilirsiniz. .RotateFlip yöntemi, uygun [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) belirtilirken. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-emz/" name="XPS İle EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-tga/" name="XPS İle TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-jpeg2000/" name="XPS İle JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-image/" name="XPS İle IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-psd/" name="XPS İle PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-wmz/" name="XPS İle WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-svgz/" name="XPS İle SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to/" name="XPS İle" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-wmf/" name="XPS İle WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-dxf/" name="XPS İle DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/xps-to-dicom/" name="XPS İle DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}