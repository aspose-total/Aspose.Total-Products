---
title: Konvertálja a EPUB-et PPTM-vé Java API-n keresztül
description: Java API a EPUB konvertálásához PPTM-vé Microsoft Word használata nélkül
url_ignore: /hu/java/conversion/epub-to-pptm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPTM
otherformats: PPSX OTP POTM SWF POT PPT XAML POTX PPTM PPS PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a EPUB exportálásához PPTM-be" h2="EPUB exportálása PPTM-be helyszíni Java API-n keresztül Microsoft<sup>&reg;</sup> PowerPoint vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával könnyedén konvertálhatja a EPUB-et PPTM-vé bármely Java J2SE, J2EE, J2ME alkalmazáson belül. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával exportálhatja a EPUB-et PPTX-be. Ezt követően az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API használatával konvertálhatja a PPTX-t PPTM-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a EPUB PPTM-vé konvertálásához" %}}
1. Nyissa meg a EPUB-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a EPUB-et PPTX-re a [mentés](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
4. Mentse a dokumentumot PPTM formátumba a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) metódussal, és állítsa be a ` Pptm` SaveFormat néven
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
A EPUB fájlformátum betöltése közben előfordulhat, hogy a dokumentum jelszóval védett. Az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) lehetővé teszi titkosított dokumentumok megnyitását is. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a titkosított EPUB fájlt Java-n keresztül" %}}
A EPUB PPTM-re konvertálása után előre meghatározott nézettípust is hozzáadhat a bemutatóhoz. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) lehetőséget biztosít a generált prezentáció nézettípusának beállítására, amikor a PowerPointban a [ViewProperties](https:/) segítségével megnyitják. /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) osztály. A [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) tulajdonság a nézet típusának beállítására szolgál a [ViewType](https:/) használatával. /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Az **EPUB to PPTM (Makróval engedélyezett PowerPoint bemutató)** konvertálása elengedhetetlen az **interaktív bemutatók automatizálásához** az e-könyvekből. A PPTM fájlok támogatják a beágyazott makrókat, lehetővé téve a dinamikus tartalmat, az automatizált munkafolyamatokat és az interaktív funkciókat. Az EPUB átalakításával PPTM-mé a vállalkozások, oktatók és kiadók intelligens bemutatókat hozhatnak létre, amelyek fokozzák az elkötelezettséget, szabványosítják a tartalmat, és egyszerűsítik a nagy léptékű bemutatók előállítását.

{{% blocks/products/pf/agp/feature-section-col title="Kulcsfontosságú felhasználási esetek" %}}
- **Vállalati üzleti intelligencia bemutatók** – Dinamikus diák létrehozása automatizált adatfrissítésekkel és elemzésekkel.
- **Automatizált oktatási anyagok** – Interaktív és makróvezérelt tartalmú oktatói bemutatók készítése.
- **Akadémiai kutatási bemutatók** – Tudományos tartalom átalakítása strukturált, interaktív diákokká.
- **Kiadási munkafolyamatok** – Az e-könyv tartalmának makróval engedélyezett bemutatókká történő átalakításának egyszerűsítése.
- **Vállalati diavetítés automatizálás** – Nagy léptékű bemutatók létrehozásának szabványosítása és automatizálása csapatokon belül.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}
- **EPUB-to-PPTM csatornák** – Az e-könyvek automatizált átalakítása makróval engedélyezett diákokká.
- **Automatizált makróval engedélyezett bemutatók generálása** – Interaktivitás és dinamikus funkciók beágyazása a diákokba.
- **Metaadatvezérelt diaváltás** – Prezentációk kitöltése strukturált e-könyvadatok felhasználásával.
- **Vállalati kiadási munkafolyamatok** – Az automatizált PPTM előállítás skálázása szervezeteken belül.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}