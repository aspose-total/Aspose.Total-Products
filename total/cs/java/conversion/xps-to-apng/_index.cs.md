---
title: Převést XPS na APNG přes Java
description: Exportujte soubor XPS do APNG ve svých aplikacích Java bez použití jakékoli aplikace třetí strany
url_ignore: /cs/java/conversion/xps-to-apng/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: APNG
otherformats: DXF  PSD TGA IMAGE SVGZ JPEG2000 WMZ EMZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést XPS na APNG přes Java" h2="Exportujte soubor XPS do APNG v rámci jakékoli aplikace Java J2SE, J2EE, J2ME bez použití Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Soubor xps můžete převést na obrázek APNG v Javě ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete exportovat XPS do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) můžete vykreslit JPEG do APNG. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export XPS do APNG přes Java" %}}
1. Otevřete soubor XPS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicializujte objekt třídy a vykreslete XPS do JPEG pomocí [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice).
3. Načtěte soubor JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Uložte dokument do formátu APNG pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte XPS na APNG v jediném souboru přes Java" %}}
API také umožňuje exportovat soubor XPS do APNG do jednoho souboru. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument XPS do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do APNG. Vstupní soubor můžete otevřít pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a vytvořit objekty Resolution, TiffSettings a TIFF. Pomocí [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)  můžete získat jeden obrázek TIFF metoda třídy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a uložit jej do formátu APNG pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte XPS na APNG s vodoznakem přes Java" %}}
Pomocí API můžete také exportovat soubor XPS do APNG s vodoznakem v dokumentu APNG. Chcete-li přidat vodoznak, můžete nejprve převést XPS na JPEG a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte soubor obrázku pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), vytvořte objekt [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) a inicializujte ji pomocí objektu Image, vytvořte novou [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objekt a nastavte překlad a transformaci na požadovaný úhel a přidejte vodoznak pomocí [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po přidání vodoznaku do obrázku můžete uložit JPEG jako formát APNG. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převést a otočit XPS na soubor APNG přes Java" %}}
Pomocí API můžete také otočit výstupní obrázek APNG podle svých potřeb. Metodu Image.rotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Knihovna poskytuje jednoduché metody pro provádění složitých operací a zároveň zapouzdřuje všechny ošklivé detaily. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a zavolat obrázek. metodu rotationFlip při specifikaci příslušného [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Převádění souborů XPS (XML Paper Specification) na **APNG (Animované přenosné síťové grafiky)** umožňuje statickým dokumentům XPS transformovat se na animované vizuály, ideální pro dynamické prezentace a webové interaktivní grafiky.



{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}



* Vytváření animovaných přehledů z reportů založených na XPS.

* Vizuální zobrazení pro vzdělávací vizualizace s pohybovými prvky pro online kurzy.

* Interaktivní marketingová grafika pro webové stránky nebo sociální média.

* Vizualizace pracovních postupů nebo trendů dat v čase.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}



* Hromadná konverze archivů XPS do APNG pro e-learningové platformy.

* Integrace s webovými publikovanými potrubími pro animovaný obsah.

* Spouštěná generace interaktivních vizuálů pro přehledy.

* Automatizovaná konverze pro marketingové a školicí kampaně.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}