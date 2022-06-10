---
title: Převést XPS na TGA přes Java
description: Exportujte soubor XPS do TGA ve svých aplikacích Java bez použití jakékoli aplikace třetí strany
url_ignore: /cs/java/conversion/xps-to-tga/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: TGA
otherformats: EMZ SVGZ PSD TGA DXF WMF JPEG2000 IMAGE WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést XPS na TGA přes Java" h2="Exportujte soubor XPS do TGA v rámci jakékoli aplikace Java J2SE, J2EE, J2ME bez použití Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Soubor xps můžete převést na obrázek TGA v Javě ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete exportovat XPS do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) můžete vykreslit JPEG do TGA. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export XPS do TGA přes Java" %}}
1. Otevřete soubor XPS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicializujte objekt třídy a vykreslete XPS do JPEG pomocí [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice).
3. Načtěte soubor JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Uložte dokument do formátu TGA pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte XPS na TGA v jediném souboru přes Java" %}}
API také umožňuje exportovat soubor XPS do TGA do jednoho souboru. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument XPS do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do TGA. Vstupní soubor můžete otevřít pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a vytvořit objekty Resolution, TiffSettings a TIFF. Pomocí [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)  můžete získat jeden obrázek TIFF metoda třídy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a uložit jej do formátu TGA pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte XPS na TGA s vodoznakem přes Java" %}}
Pomocí API můžete také exportovat soubor XPS do TGA s vodoznakem v dokumentu TGA. Chcete-li přidat vodoznak, můžete nejprve převést XPS na JPEG a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte soubor obrázku pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), vytvořte objekt [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) a inicializujte ji pomocí objektu Image, vytvořte novou [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objekt a nastavte překlad a transformaci na požadovaný úhel a přidejte vodoznak pomocí [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po přidání vodoznaku do obrázku můžete uložit JPEG jako formát TGA. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převést a otočit XPS na soubor TGA přes Java" %}}
Pomocí API můžete také otočit výstupní obrázek TGA podle svých potřeb. Metodu Image.rotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Knihovna poskytuje jednoduché metody pro provádění složitých operací a zároveň zapouzdřuje všechny ošklivé detaily. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a zavolat obrázek. metodu rotationFlip při specifikaci příslušného [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

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