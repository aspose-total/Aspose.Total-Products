---
title: C# API aracılığıyla PCL'yi TGA'ye dönüştürün
description: Herhangi bir üçüncü taraf uygulaması kullanmadan PCL'yi .NET uygulamalarınızda TGA'ye aktarın
url_ignore: /tr/net/conversion/pcl-to-tga/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: TGA
otherformats: TGA IMAGE PSD SVGZ EMZ WMZ WMF  JPEG2000 DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PCL dosyasını C# ile TGA'ye dönüştürün" h2="Adobe<sup>&reg;</sup> Acrobat Reader veya diğer üçüncü taraf uygulamaları kullanmadan PCL'yi .NET uygulamaları içinde TGA'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak, iki basit adımda herhangi bir .NET uygulamasında PCL'yi TGA görüntüsüne kolayca aktarabilirsiniz. Her şeyden önce, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak PCL'yi JPEG'e aktarabilirsiniz. Bundan sonra, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Görüntü İşleme API'sini kullanarak JPEG'i TGA'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PCL dosyasını .NET aracılığıyla TGA'ye dönüştürün" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak PCL dosyasını açın
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) sınıf nesnesini başlatın ve [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) yöntemi
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak JPEG dosyasını yükleyin
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak belgeyi TGA formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C# ile PCL Dosyasını Tek Bir Dosyada TGA'ye Dönüştürün" %}}
API'yi kullanarak, PCL dosyasını TGA'ye tek bir görüntü dosyasına da dönüştürebilirsiniz. Tüm sayfaları dönüştürmek için önce PCL belgenizi bir TIFF dosyasına dönüştürebilir ve ardından TIFF dosyasını TGA'ye aktarabilirsiniz. Giriş dosyasını [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak açabilir ve Resolution, TiffSettings ve TIFF aygıt nesneleri oluşturabilirsiniz. [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) TiffDevice yöntemini kullanarak tek bir TIFF görüntüsü alabilirsiniz. apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) sınıfı. Son olarak, [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfını kullanarak TIFF dosyasını yükleyebilirsiniz.
ve [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) yöntemini kullanarak TGA formatına kaydedin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PCL Dosyasını C# ile TGA'ye Dönüştür ve Döndür" %}}
API'yi kullanarak, çıktı TGA görüntüsünü ihtiyaçlarınıza göre de döndürebilirsiniz. Image.RotateFlip yöntemi, görüntüyü 90/180/270 derece döndürmek ve görüntüyü yatay veya dikey olarak çevirmek için kullanılabilir. Görüntüye uygulamak için döndürme ve çevirme türünü belirtebilirsiniz. Görüntüyü döndürmek ve çevirmek için [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) sınıfı tarafından sunulan fabrika yöntemini kullanarak dönüştürülmüş JPEG görüntüsünü yükleyebilir ve Görüntüyü çağırabilirsiniz. .RotateFlip yöntemi, uygun [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) belirtilirken. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-emz/" name="PCL İle EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-tga/" name="PCL İle TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-jpeg2000/" name="PCL İle JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-image/" name="PCL İle IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-psd/" name="PCL İle PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-wmz/" name="PCL İle WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-svgz/" name="PCL İle SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to/" name="PCL İle" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-wmf/" name="PCL İle WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-dxf/" name="PCL İle DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pcl-to-dicom/" name="PCL İle DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}