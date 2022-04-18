---
title: Převeďte MHTML na DXF přes C# API
description: Exportujte MHTML do DXF ve svých aplikacích .NET bez použití jakékoli aplikace třetí strany
url: /cs/net/conversion/mhtml-to-dxf/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DXF
otherformats: SVGZ EMZ  DXF WMF WMZ PSD IMAGE TGA JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést soubor MHTML na DXF přes C#" h2="Export MHTML do DXF v rámci aplikací .NET bez použití Adobe<sup>&reg;</sup> Acrobat Reader nebo jiných aplikací třetích stran" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno exportovat MHTML do obrazu DXF v jakékoli aplikaci .NET ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF pro .NET] (https://products.aspose.com/pdf/net/) můžete exportovat MHTML do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) můžete převést JPEG na DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte soubor MHTML na DXF přes .NET" %}}
1. Otevřete soubor MHTML pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicializujte objekt třídy [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) a vykreslete MHTML do JPEG pomocí [Proces](https://apireference.aspose. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Načtěte soubor JPEG pomocí třídy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Uložte dokument do formátu DXF pomocí metody [Uložit](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor MHTML na DXF v jediném souboru přes C#" %}}
Pomocí rozhraní API můžete také převést soubor MHTML na DXF na jeden soubor obrázku. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument MHTML do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do DXF. Vstupní soubor můžete otevřít pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a vytvořit objekty Resolution, TiffSettings a TIFF. Jeden obrázek TIFF můžete získat pomocí metody [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) metody [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) třídy. Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
a uložte jej do formátu DXF pomocí metody [Uložit](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést a otočit soubor MHTML na DXF přes C#" %}}
Pomocí API můžete také otočit výstupní obrázek DXF podle svých potřeb. Metodu Image.RotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí tovární metody vystavené třídou [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) a zavolat obrázek .Metoda RotateFlip při specifikaci příslušného [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-emz/" name="MHTML Na EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-tga/" name="MHTML Na TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-jpeg2000/" name="MHTML Na JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-image/" name="MHTML Na IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-psd/" name="MHTML Na PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-wmz/" name="MHTML Na WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-svgz/" name="MHTML Na SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to/" name="MHTML Na" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-wmf/" name="MHTML Na WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-dxf/" name="MHTML Na DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/mhtml-to-dicom/" name="MHTML Na DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}