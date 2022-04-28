---
title: Převeďte TEX na IMAGE přes C# API
description: Exportujte TEX do IMAGE ve svých aplikacích .NET bez použití jakékoli aplikace třetí strany
url: /cs/net/conversion/tex-to-image/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: JPEG2000
otherformats: DXF WMZ WMF TGA EMZ JPEG2000 SVGZ PSD  IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést soubor TEX na IMAGE přes C#" h2="Export TEX do IMAGE v rámci aplikací .NET bez použití Adobe<sup>&reg;</sup> Acrobat Reader nebo jiných aplikací třetích stran" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno exportovat TEX do obrazu IMAGE v jakékoli aplikaci .NET ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete exportovat TEX do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) můžete převést JPEG na IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor TEX na IMAGE přes .NET" %}}
1. Otevřete soubor TEX pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicializujte objekt třídy [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) a vykreslete TEX do JPEG pomocí [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Načtěte soubor JPEG pomocí třídy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Uložte dokument do formátu IMAGE pomocí metody [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor TEX na IMAGE v jediném souboru přes C#" %}}
Pomocí rozhraní API můžete také převést soubor TEX na IMAGE na jeden soubor obrázku. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument TEX do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do IMAGE. Vstupní soubor můžete otevřít pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a vytvořit objekty Resolution, TiffSettings a TIFF. Jeden obrázek TIFF můžete získat pomocí metody [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) metody [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) třídy. Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
a uložte jej do formátu IMAGE pomocí metody [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést a otočit soubor TEX na IMAGE přes C#" %}}
Pomocí API můžete také otočit výstupní obrázek IMAGE podle svých potřeb. Metodu Image.RotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí tovární metody vystavené třídou [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) a zavolat obrázek .Metoda RotateFlip při specifikaci příslušného [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-emz/" name="TEX Na EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-tga/" name="TEX Na TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-jpeg2000/" name="TEX Na JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-image/" name="TEX Na IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-psd/" name="TEX Na PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-wmz/" name="TEX Na WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-svgz/" name="TEX Na SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to/" name="TEX Na" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-wmf/" name="TEX Na WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-dxf/" name="TEX Na DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tex-to-dicom/" name="TEX Na DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}