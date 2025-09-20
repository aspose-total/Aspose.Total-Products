---
title: Převeďte formát JSON na DXF přes Java
description: Analyzujte JSON na DXF v Javě bez použití Microsoft PowerPoint
url_ignore: /cs/java/conversion/json-to-dxf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DXF
otherformats: DXF WMF WMZ SVGZ TGA JPEG2000 PSD EMZ DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převeďte formát JSON na DXF přes Java" h2="Java API pro analýzu formátu JSON na DXF v jakékoli aplikaci Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete převést formát JSON na DXF v jakékoli aplikaci Java ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) můžete analyzovat JSON na JPEG. Poté můžete pomocí [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) převést JPEG na DXF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na DXF přes Java" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a otevřete soubor JSON
2. Uložte JSON jako JPEG pomocí [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
3. Načtěte dokument JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Uložte dokument do formátu DXF pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Kromě toho vám API umožňuje analyzovat JSON na DXF se zadanými možnostmi rozvržení. Chcete-li určit možnosti rozložení, můžete použít třídu [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit datum a formát čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nastavte rozložení a převeďte formát JSON na DXF přes Java" %}}
Pomocí API můžete také převést JSON na DXF s vodoznakem v dokumentu DXF. Chcete-li přidat vodoznak, můžete nejprve převést JSON na JPEG a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte soubor obrázku pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), vytvořte objekt [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) a inicializujte ji pomocí objektu Image, vytvořte novou [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objekt a nastavte překlad a transformaci na požadovaný úhel a přidejte vodoznak pomocí [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po přidání vodoznaku do obrázku můžete uložit JPEG jako formát DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Převod **JSON na DXF (Drawing Exchange Format)** je zásadní pro generování **CAD výkresů** ze strukturovaných datových sad. DXF je široce přijímaný formát v architektuře, inženýrství, průmyslovém designu a GIS aplikacích, což ho činí ideálním pro transformaci dat založených na JSON do přesných, editovatelných technických výkresů. Tento převod umožňuje bezproblémové pracovní postupy od dat k designu, zlepšuje interoperabilitu mezi CAD systémy a podporuje automatizaci v moderních návrhových procesech.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}

- **Architektonické rozvrhy** – Převeďte stavební data do editovatelných CAD podlažních plánů.
- **Inženýrské modely** – Generujte konstrukční a mechanické návrhy z JSON vstupů.
- **Automatizace CAD řízená JSON** – Zjednodušte pracovní postupy CAD transformací strukturovaných dat.
- **Pracovní postupy průmyslového designu** – Vytvářejte přesné výkresy produktů a komponentů z dat JSON.
- **GIS mapování** – Převeďte geoprostorová data do DXF pro městské plánování a infrastrukturní projekty.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}

- **JSON na DXF potrubí** – Automatizujte transformaci strukturovaných dat do kresby připravené pro CAD.
- **Automatizované generování CAD výkresů** – Vytvářejte technické diagramy přímo z datových sad JSON.
- **Pracovní postupy od dat k designu** – Umocněte bezproblémovou integraci strukturovaných dat do aplikací CAD.
- **Chytré modelování infrastruktury** – Posilněte moderní infrastrukturní a mapovací systémy výstupy DXF řízenými JSON.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}