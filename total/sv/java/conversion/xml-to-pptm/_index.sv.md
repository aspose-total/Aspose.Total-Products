---
title: Konvertera XML till PPTM via Java API
description: Java API för att konvertera XML till PPTM utan att använda Microsoft Word
url: /sv/java/conversion/xml-to-pptm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: PPTM
otherformats: POWERPOINT OTP PPTM PPS XAML POTM PPSX PPT POTX SWF PPSM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att exportera XML till PPTM" h2="Exportera XML till PPTM via lokalt Java API utan att använda Microsoft<sup>&reg;</sup> PowerPoint eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du enkelt konvertera XML till PPTM i valfri Java J2SE, J2EE, J2ME-applikation. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/), kan du exportera XML till PPTX. Efter det, genom att använda [Aspose.Slides för Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, kan du konvertera PPTX till PPTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera XML till PPTM" %}}
1. Öppna XML-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XML till PPTX genom att använda metoden [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Spara dokumentet i PPTM-format med metoden [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) och ställ in ` Pptm` som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Slides för Java](https://docs.aspose.com/slides/java/ installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
När du laddar XML-filformatet kan ditt dokument vara lösenordsskyddat. [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) låter dig också öppna krypterade dokument. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öppna krypterad XML-fil via Java" %}}
Efter att ha konverterat XML till PPTM kan du också lägga till fördefinierad vytyp för din presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ger en möjlighet att ställa in vytypen för den genererade presentationen när den öppnas i PowerPoint via [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Egenskapen [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) används för att ställa in vytypen genom att använda [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-pps/" name="XML Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-swf/" name="XML Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-potx/" name="XML Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ppsx/" name="XML Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-potm/" name="XML Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ppt/" name="XML Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ppsm/" name="XML Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xaml/" name="XML Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-otp/" name="XML Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-pptm/" name="XML Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-pot/" name="XML Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-powerpoint/" name="XML Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}