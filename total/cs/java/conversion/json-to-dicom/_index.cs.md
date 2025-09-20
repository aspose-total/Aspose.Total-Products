---
title: Převeďte formát JSON na DICOM přes Java
description: Analyzujte JSON na DICOM v Javě bez použití Microsoft PowerPoint
url_ignore: /cs/java/conversion/json-to-dicom/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DICOM
otherformats: DICOM DXF WMF TGA SVGZ EMZ IMAGE JPEG2000 PSD WMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převeďte formát JSON na DICOM přes Java" h2="Java API pro analýzu formátu JSON na DICOM v jakékoli aplikaci Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete převést formát JSON na DICOM v jakékoli aplikaci Java ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) můžete analyzovat JSON na JPEG. Poté můžete pomocí [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) převést JPEG na DICOM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na DICOM přes Java" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a otevřete soubor JSON
2. Uložte JSON jako JPEG pomocí [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
3. Načtěte dokument JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Uložte dokument do formátu DICOM pomocí [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
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
Kromě toho vám API umožňuje analyzovat JSON na DICOM se zadanými možnostmi rozvržení. Chcete-li určit možnosti rozložení, můžete použít třídu [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit datum a formát čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nastavte rozložení a převeďte formát JSON na DICOM přes Java" %}}
Pomocí API můžete také převést JSON na DICOM s vodoznakem v dokumentu DICOM. Chcete-li přidat vodoznak, můžete nejprve převést JSON na JPEG a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte soubor obrázku pomocí třídy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), vytvořte objekt [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) a inicializujte ji pomocí objektu Image, vytvořte novou [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objekt a nastavte překlad a transformaci na požadovaný úhel a přidejte vodoznak pomocí [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po přidání vodoznaku do obrázku můžete uložit JPEG jako formát DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Převod **JSON na DICOM (Digital Imaging and Communications in Medicine)** je klíčový pro transformaci **strukturovaných zdravotních dat** do standardizovaných lékařských obrazových formátů. DICOM je globálním standardem pro ukládání, přenášení a vizualizaci lékařských obrázků, umožňuje poskytovatelům zdravotní péče, výzkumníkům a systémům umělé inteligence pracovat s konzistentními, interoperabilními daty. Převodem JSON na DICOM lze strukturované záznamy pacientů a klinická data bezproblémově integrovat do obrazových pracovních postupů, podporujících přesné diagnostiky a lepší výsledky zdravotní péče.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}

- **Vizualizace záznamů pacientů** – Převeďte strukturovaná zdravotní data do vizuálních obrazových formátů.
- **AI založené na lékařských obrazech** – Umožněte systémům strojového učení zpracovávat datasety řízené JSONem.
- **Interoperabilita ve zdravotnictví** – Standardizujte strukturovaná data do globálně akceptovaných formátů DICOM.
- **Radiologické pracovní postupy** – Integrujte zprávy založené na JSONu do obrazových a diagnostických systémů.
- **Integrace klinických výzkumných dat** – Převeďte strukturované datasety do obrazově kompatibilních formátů pro studie.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}

- **Potrubí JSON-to-DICOM** – Automatizujte transformaci zdravotních dat do obrazově připravených formátů.
- **Automatická konverze lékařských zpráv** – Generujte soubory DICOM přímo z klinických zpráv založených na JSONu.
- **Zdravotnické obrazové úložiště v cloudu** – Umožněte škálovatelnou, interoperabilní výměnu obrazových dat v cloudu.
- **AI řízené diagnostické systémy** – Napájejte pokročilé diagnostické nástroje konverzí ze strukturovaného na obrazový formát.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}