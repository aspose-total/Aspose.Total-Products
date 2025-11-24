---
title: Převést MHTML na DICOM přes Java
description: Exportujte soubor MHTML do DICOM ve svých aplikacích Java bez použití jakékoli aplikace třetí strany
url_ignore: /cs/java/conversion/mhtml-to-dicom/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DICOM
otherformats: EMZ TGA WMF IMAGE WMZ DICOM JPEG2000 DXF SVGZ PSD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést MHTML na DICOM přes Java" h2="Exportujte soubor MHTML do DICOM v rámci jakékoli aplikace Java J2SE, J2EE, J2ME bez použití Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Soubor mhtml můžete převést na obrázek DICOM v Javě ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete exportovat MHTML do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) můžete vykreslit JPEG do DICOM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export MHTML do DICOM přes Java" %}}
1. Otevřete soubor MHTML pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicializujte objekt třídy a vykreslete MHTML do JPEG pomocí [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice).
3. Načtěte soubor JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Uložte dokument do formátu DICOM pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte MHTML na DICOM v jediném souboru přes Java" %}}
API také umožňuje exportovat soubor MHTML do DICOM do jednoho souboru. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument MHTML do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do DICOM. Vstupní soubor můžete otevřít pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a vytvořit objekty Resolution, TiffSettings a TIFF. Pomocí [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)  můžete získat jeden obrázek TIFF metoda třídy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a uložit jej do formátu DICOM pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte MHTML na DICOM s vodoznakem přes Java" %}}
Pomocí API můžete také exportovat soubor MHTML do DICOM s vodoznakem v dokumentu DICOM. Chcete-li přidat vodoznak, můžete nejprve převést MHTML na JPEG a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte soubor obrázku pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), vytvořte objekt [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) a inicializujte ji pomocí objektu Image, vytvořte novou [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objekt a nastavte překlad a transformaci na požadovaný úhel a přidejte vodoznak pomocí [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po přidání vodoznaku do obrázku můžete uložit JPEG jako formát DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převést a otočit MHTML na soubor DICOM přes Java" %}}
Pomocí API můžete také otočit výstupní obrázek DICOM podle svých potřeb. Metodu Image.rotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Knihovna poskytuje jednoduché metody pro provádění složitých operací a zároveň zapouzdřuje všechny ošklivé detaily. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a zavolat obrázek. metodu rotationFlip při specifikaci příslušného [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Převod souborů MHTML (webový archiv) do formátu DICOM (Digital Imaging and Communications in Medicine) umožňuje integrovat webové lékařské obrázky, zprávy nebo grafy do klinických obrázkových pracovních postupů. DICOM zajišťuje kompatibilitu s PACS a softwary pro lékařské zobrazování.



{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}



* Archivace diagnostických obrázků z webových stránek do formátu DICOM.

* Převod online lékařských zpráv pro systémy nemocničních EMR.

* Sdílení radiologických nebo ultrazvukových obrázků extrahovaných z webových portálů.

* Integrování klinických webových nástěnek do obrázkových pracovních postupů.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}



* Plánovaná hromadná konverze webového lékařského obsahu do formátu DICOM.

* Spuštěné generování pro integraci s PACS a aktualizace EMR.

* Automatická archivace pro telemedicínské platformy.

* Integrace do diagnostických potrubí asistovaných umělou inteligencí.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}