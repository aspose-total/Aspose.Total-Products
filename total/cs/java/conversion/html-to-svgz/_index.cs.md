---
title: Převést HTML na SVGZ přes Java
description: Exportujte soubor HTML do SVGZ ve svých aplikacích Java bez použití jakékoli aplikace třetí strany
url_ignore: /cs/java/conversion/html-to-svgz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: SVGZ
otherformats: EMZ JPEG2000 PSD WMF TGA IMAGE WMZ DXF SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést HTML na SVGZ přes Java" h2="Exportujte soubor HTML do SVGZ v rámci jakékoli aplikace Java J2SE, J2EE, J2ME bez použití Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Soubor html můžete převést na obrázek SVGZ v Javě ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) můžete exportovat HTML do JPEG. Poté pomocí rozhraní API pro zpracování obrazu [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) můžete vykreslit JPEG do SVGZ. Obě rozhraní API jsou součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export HTML do SVGZ přes Java" %}}
1. Otevřete soubor HTML pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicializujte objekt třídy a vykreslete HTML do JPEG pomocí [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice).
3. Načtěte soubor JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Uložte dokument do formátu SVGZ pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte HTML na SVGZ v jediném souboru přes Java" %}}
API také umožňuje exportovat soubor HTML do SVGZ do jednoho souboru. Chcete-li převést všechny stránky, můžete nejprve vykreslit svůj dokument HTML do jednoho souboru TIFF a poté můžete soubor TIFF exportovat do SVGZ. Vstupní soubor můžete otevřít pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) a vytvořit objekty Resolution, TiffSettings a TIFF. Pomocí [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)  můžete získat jeden obrázek TIFF metoda třídy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Nakonec můžete načíst soubor TIFF pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a uložit jej do formátu SVGZ pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte HTML na SVGZ s vodoznakem přes Java" %}}
Pomocí API můžete také exportovat soubor HTML do SVGZ s vodoznakem v dokumentu SVGZ. Chcete-li přidat vodoznak, můžete nejprve převést HTML na JPEG a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte soubor obrázku pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), vytvořte objekt [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) a inicializujte ji pomocí objektu Image, vytvořte novou [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objekt a nastavte překlad a transformaci na požadovaný úhel a přidejte vodoznak pomocí [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po přidání vodoznaku do obrázku můžete uložit JPEG jako formát SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převést a otočit HTML na soubor SVGZ přes Java" %}}
Pomocí API můžete také otočit výstupní obrázek SVGZ podle svých potřeb. Metodu Image.rotateFlip lze použít k otočení obrázku o 90/180/270 stupňů a převrácení obrázku vodorovně nebo svisle. Knihovna poskytuje jednoduché metody pro provádění složitých operací a zároveň zapouzdřuje všechny ošklivé detaily. Můžete určit typ otočení a převrácení, které se má použít na obrázek. Chcete-li obrázek otočit a převrátit, můžete načíst převedený obrázek JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) a zavolat obrázek. metodu rotationFlip při specifikaci příslušného [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Převádění **HTML na SVGZ (komprimované SVG)** je zásadní pro generování **škálovatelných, komprimovaných vektorových grafik** z webových stránek. SVGZ zachovává jasnost a škálovatelnost vektorových grafik a zároveň výrazně snižuje velikost souborů, což je ideální pro responzivní design, webové vizuály připravené pro web a interaktivní digitální obsah. Přeměnou obsahu HTML na SVGZ mohou organizace optimalizovat výkon, zlepšit načítací časy a efektivně spravovat vektorová aktiva napříč platformami.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}

* **Infografiky** – Vytvářejte vizuálně ostré, kompaktní vektorové grafiky pro zobrazení dat.
* **Diagramy připravené pro web** – Generujte škálovatelné diagramy, které se bezproblémově integrují do webových stránek.
* **Lehké publikování** – Snížení velikosti souborů pro rychlejší doručení v digitálních publikacích.
* **Vizuální aktiva přátelská k mobilním zařízením** – Zajistěte ostré grafiky na jakékoli obrazovce nebo zařízení.
* **Interaktivní designy** – Podpora animací a interaktivity při zachování malých velikostí souborů.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}

* **Potrubí HTML-to-SVGZ** – Automatizujte převod obsahu webových stránek na komprimované vektorové grafiky.
* **Automatizovaná komprese vektorů** – Vytvářejte konzistentně optimalizované soubory SVGZ pro webové a mobilní použití.
* **Hromadné pracovní postupy s diagramy** – Efektivně zpracovávejte více vektorových aktiv pro velké projekty.
* **Publikování lehkých v podnikovém měřítku** – Integrujte generování SVGZ do škálovatelných pracovních postupů digitálního publikování.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}