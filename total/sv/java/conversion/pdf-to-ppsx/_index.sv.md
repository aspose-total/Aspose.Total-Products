---
title: Konvertera PDF till PPSX via Java API
description: Java API för att konvertera PDF till PPSX utan att använda Microsoft Word
url: /sv/java/conversion/pdf-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PPSX
otherformats: POWERPOINT POTX PPSX PPS SWF POT PPSM PPT OTP POTM PPTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att exportera PDF till PPSX" h2="Exportera PDF till PPSX via lokalt Java API utan att använda Microsoft<sup>&reg;</sup> PowerPoint eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du enkelt konvertera PDF till PPSX i valfri Java J2SE, J2EE, J2ME-applikation. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/), kan du exportera PDF till PPTX. Efter det, genom att använda [Aspose.Slides för Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, kan du konvertera PPTX till PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera PDF till PPSX" %}}
1. Öppna PDF-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera PDF till PPTX genom att använda metoden [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Spara dokumentet i PPSX-format med metoden [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) och ställ in ` Ppsx` som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Slides för Java](https://docs.aspose.com/slides/java/ installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
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
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
När du laddar PDF-filformatet kan ditt dokument vara lösenordsskyddat. [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) låter dig också öppna krypterade dokument. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öppna krypterad PDF-fil via Java" %}}
Efter att ha konverterat PDF till PPSX kan du också lägga till fördefinierad vytyp för din presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ger en möjlighet att ställa in vytypen för den genererade presentationen när den öppnas i PowerPoint via [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Egenskapen [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) används för att ställa in vytypen genom att använda [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
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
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-pps/" name="PDF Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-swf/" name="PDF Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-potx/" name="PDF Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-ppsx/" name="PDF Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-potm/" name="PDF Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-ppt/" name="PDF Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-ppsm/" name="PDF Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-xaml/" name="PDF Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-otp/" name="PDF Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-pptm/" name="PDF Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-pot/" name="PDF Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-powerpoint/" name="PDF Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}