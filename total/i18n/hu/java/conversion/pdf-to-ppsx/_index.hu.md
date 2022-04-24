---
title: Konvertálja a PDF-et PPSX-vé Java API-n keresztül
description: Java API a PDF konvertálásához PPSX-vé Microsoft Word használata nélkül
url: /hu/java/conversion/pdf-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PPSX
otherformats: POWERPOINT POTX PPSX PPS SWF POT PPSM PPT OTP POTM PPTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a PDF exportálásához PPSX-be" h2="PDF exportálása PPSX-be helyszíni Java API-n keresztül Microsoft<sup>&reg;</sup> PowerPoint vagy Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával könnyedén konvertálhatja a PDF-et PPSX-vé bármely Java J2SE, J2EE, J2ME alkalmazáson belül. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával exportálhatja a PDF-et PPTX-be. Ezt követően az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API használatával konvertálhatja a PPTX-t PPSX-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a PDF PPSX-vé konvertálásához" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a PDF-et PPTX-re a [mentés](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
4. Mentse a dokumentumot PPSX formátumba a [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) metódussal, és állítsa be a ` Ppsx` SaveFormat néven
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Slides for Java](https://docs.aspose.com/slides/java/) install/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
A PDF fájlformátum betöltése közben előfordulhat, hogy a dokumentum jelszóval védett. Az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) lehetővé teszi titkosított dokumentumok megnyitását is. A titkosított fájl megnyitásához inicializálhatja a [Dokumentum] új példányát (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a titkosított PDF fájlt Java-n keresztül" %}}
A PDF PPSX-re konvertálása után előre meghatározott nézettípust is hozzáadhat a bemutatóhoz. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) lehetőséget biztosít a generált prezentáció nézettípusának beállítására, amikor a PowerPointban a [ViewProperties](https:/) segítségével megnyitják. /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) osztály. A [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) tulajdonság a nézet típusának beállítására szolgál a [ViewType](https:/) használatával. /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-pps/" name="PDF Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-swf/" name="PDF Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-potx/" name="PDF Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ppsx/" name="PDF Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-potm/" name="PDF Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ppt/" name="PDF Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ppsm/" name="PDF Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-xaml/" name="PDF Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-otp/" name="PDF Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-pptm/" name="PDF Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-pot/" name="PDF Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-powerpoint/" name="PDF Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}