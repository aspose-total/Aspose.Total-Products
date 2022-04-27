---
title: Převeďte XPS na JPEG2000 přes C# API
description: Exportujte XPS do JPEG2000 ve svých aplikacích .NET bez použití jakékoli aplikace třetí strany
url: /cs/net/conversion/xps-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: JPEG2000
otherformats: IMAGE  TGA DXF WMF JPEG2000 EMZ WMZ SVGZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést soubor XPS na JPEG2000 přes C#" h2="Export XPS do JPEG2000 v rámci aplikací .NET bez použití Adobe<sup>&reg;</sup> Acrobat Reader nebo jiných aplikací třetích stran" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno exportovat XPS do obrazu JPEG2000 v jakékoli aplikaci .NET ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete exportovat XPS do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) můžete převést JPEG na JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor XPS na JPEG2000 přes .NET" %}}
1. Otevřete soubor XPS pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicializujte objekt třídy [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) a vykreslete XPS do JPEG pomocí [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Načtěte soubor JPEG pomocí třídy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Uložte dokument do formátu JPEG2000 pomocí metody [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor XPS na JPEG2000 v jediném souboru přes C#" %}}
Pomocí rozhraní API můžete také převést soubor XPS na JPEG2000 na jeden soubor obrázku. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument XPS do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do JPEG2000. Vstupní soubor můžete otevřít pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a vytvořit objekty Resolution, TiffSettings a TIFF. Jeden obrázek TIFF můžete získat pomocí metody [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) metody [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) třídy. Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
a uložte jej do formátu JPEG2000 pomocí metody [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést a otočit soubor XPS na JPEG2000 přes C#" %}}
Pomocí API můžete také otočit výstupní obrázek JPEG2000 podle svých potřeb. Metodu Image.RotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí tovární metody vystavené třídou [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) a zavolat obrázek .Metoda RotateFlip při specifikaci příslušného [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-emz/" name="XPS Na EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-tga/" name="XPS Na TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-jpeg2000/" name="XPS Na JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-image/" name="XPS Na IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-psd/" name="XPS Na PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-wmz/" name="XPS Na WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-svgz/" name="XPS Na SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to/" name="XPS Na" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-wmf/" name="XPS Na WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-dxf/" name="XPS Na DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xps-to-dicom/" name="XPS Na DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}