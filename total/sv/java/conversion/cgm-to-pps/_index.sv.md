---
title: Konvertera CGM till PPS via Java API
description: Java API för att konvertera CGM till PPS utan att använda Microsoft Word
url_ignore: /sv/java/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPTM POTM SWF POTX POT POWERPOINT PPSM PPS PPT OTP XAML PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att exportera CGM till PPS" h2="Exportera CGM till PPS via lokalt Java API utan att använda Microsoft<sup>&reg;</sup> PowerPoint eller Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du enkelt konvertera CGM till PPS i valfri Java J2SE, J2EE, J2ME-applikation. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/), kan du exportera CGM till PPTX. Efter det, genom att använda [Aspose.Slides för Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, kan du konvertera PPTX till PPS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API för att konvertera CGM till PPS" %}}
1. Öppna CGM-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera CGM till PPTX genom att använda metoden [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Ladda PPTX-dokument genom att använda klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Spara dokumentet i PPS-format med metoden [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) och ställ in ` Pps` som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Slides för Java](https://docs.aspose.com/slides/java/installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
När du laddar CGM-filformatet kan ditt dokument vara lösenordsskyddat. [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) låter dig också öppna krypterade dokument. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Öppna krypterad CGM-fil via Java" %}}
Efter att ha konverterat CGM till PPS kan du också lägga till fördefinierad vytyp för din presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ger en möjlighet att ställa in vytypen för den genererade presentationen när den öppnas i PowerPoint via [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Egenskapen [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) används för att ställa in vytypen genom att använda [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Att konvertera CGM-filer till PPS (PowerPoint Show) möjliggör färdiga presentationer som öppnas i bildspelsläge, perfekt för oövervakade eller kioskliknande visningar. Ingenjörsteam och företag kan använda detta för visuella genomgångar och statiska diagrampresentationer.

## ✅ Viktiga användningsfall
- **Kiosk-baserade presentationer** – Automatiska visningsloopar på utställningar och konferenser.
- **Ingenjörsdesigngenomgångar** – Visuella förklaringar för designgenomgångssessioner.
- **Skrivskyddade affärspresentationer** – Förhindra oavsiktliga redigeringar vid delning.

## ⚙️ Automatiseringsscenario
- **Java-baserade kioskappar** – Generera PPS-filer från CGM-diagram för offentliga visningar.
- **Dynamiska bildspelsskapare** – Auto-generera loopande shower från ingenjörsdata.
- **Oövervakade rapportpresentationer** – Schemalägg automatisk uppspelning för rapporteringscykler.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}