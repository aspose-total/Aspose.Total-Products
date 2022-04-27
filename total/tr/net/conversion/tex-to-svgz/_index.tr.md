---
title: C# API aracılığıyla TEX'yi SVGZ'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan TEX'yi .NET uygulamalarınızda SVGZ'ye aktarın
url: /tr/net/conversion/tex-to-svgz/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: SVGZ
otherformats: SVGZ JPEG2000 WMZ EMZ TGA IMAGE  WMF PSD DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TEX dosyasını C# ile SVGZ'ye dönüştürün" h2="Adobe<sup>&reg;</sup> Acrobat Reader veya diğer üçüncü taraf uygulamaları kullanmadan TEX'yi .NET uygulamaları içinde SVGZ'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak, iki basit adımda herhangi bir .NET uygulamasında TEX'yi SVGZ görüntüsüne kolayca aktarabilirsiniz. Her şeyden önce, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak TEX'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Görüntü İşleme API'sini kullanarak JPEG'i SVGZ'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX dosyasını .NET aracılığıyla SVGZ'ye dönüştürün" %}}
1. [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak TEX dosyasını açın
2. [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) sınıf nesnesini başlatın ve [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) yöntemi
3. [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak JPEG dosyasını yükleyin
4. [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak belgeyi SVGZ formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C# ile TEX Dosyasını Tek Bir Dosyada SVGZ'ye Dönüştürün" %}}
API'yi kullanarak, TEX dosyasını SVGZ'ye tek bir görüntü dosyasına da dönüştürebilirsiniz. Tüm sayfaları dönüştürmek için önce TEX belgenizi bir TIFF dosyasına dönüştürebilir ve ardından TIFF dosyasını SVGZ'ye aktarabilirsiniz. Giriş dosyasını [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) TiffDevice yöntemini kullanarak tek bir TIFF görüntüsü alabilirsiniz. apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) sınıfı. Son olarak, [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak TIFF dosyasını yükleyebilirsiniz.
ve [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak SVGZ formatına kaydedin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="TEX Dosyasını C# ile SVGZ'ye Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı SVGZ görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.RotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) sınıfı tarafından sunulan fabrika yöntemini kullanarak dönüştürülmüş JPEG görüntüsünü yükleyebilir ve Görüntüyü çağırabilirsiniz. .RotateFlip yöntemi, uygun [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) belirtilirken. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-emz/" name="TEX İle EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-tga/" name="TEX İle TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-jpeg2000/" name="TEX İle JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-image/" name="TEX İle IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-psd/" name="TEX İle PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-wmz/" name="TEX İle WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-svgz/" name="TEX İle SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to/" name="TEX İle" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-wmf/" name="TEX İle WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-dxf/" name="TEX İle DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-dicom/" name="TEX İle DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}