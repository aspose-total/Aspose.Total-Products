---
title: Konvertálja a EPUB-et ODP-vé Java API-n keresztül
description: Java API a EPUB konvertálásához ODP-vé Microsoft Word használata nélkül
url_ignore: /hu/java/conversion/epub-to-odp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODP
otherformats: POTM PPTM PPSM PPT SWF POT POWERPOINT PPSX XAML OTP PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a EPUB exportálásához ODP-be" h2="EPUB exportálása ODP-be helyszíni Java API-n keresztül Microsoft<sup>&reg;</sup> PowerPoint vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával könnyedén konvertálhatja a EPUB-et ODP-vé bármely Java J2SE, J2EE, J2ME alkalmazáson belül. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával exportálhatja a EPUB-et PPTX-be. Ezt követően az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API használatával konvertálhatja a PPTX-t ODP-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a EPUB ODP-vé konvertálásához" %}}
1. Nyissa meg a EPUB-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a EPUB-et PPTX-re a [mentés](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
4. Mentse a dokumentumot ODP formátumba a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) metódussal, és állítsa be a ` Odp` SaveFormat néven
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```

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
A EPUB ODP-re konvertálása után előre meghatározott nézettípust is hozzáadhat a bemutatóhoz. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) lehetőséget biztosít a generált prezentáció nézettípusának beállítására, amikor a PowerPointban a [ViewProperties](https:/) segítségével megnyitják. /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) osztály. A [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) tulajdonság a nézet típusának beállítására szolgál a [ViewType](https:/) használatával. /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-pps/" name="EPUB Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-swf/" name="EPUB Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-potx/" name="EPUB Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-ppsx/" name="EPUB Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-potm/" name="EPUB Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-ppt/" name="EPUB Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-ppsm/" name="EPUB Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-xaml/" name="EPUB Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-otp/" name="EPUB Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-pptm/" name="EPUB Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-pot/" name="EPUB Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/epub-to-powerpoint/" name="EPUB Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}