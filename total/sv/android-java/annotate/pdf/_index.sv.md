---
title: Ta bort PDF-anteckningar online eller hantera anteckningar med Android-mobilappar
description: ta bort kommentarer från PDF-filen via onlineappen gratis.Android API-kod för att hantera kommentarer för PDF-filer.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Rensa kommentarer från PDF-dokument online eller hantera via Android-appar" h2="Utveckla kraftfulla Android-baserade PDF-dokumentanteckningsverktyg.Kod listad för att hantera kommentarer för PDF-fil." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ta bort PDF-anteckningar online" %}}

1. Importera PDF-fil för att ta bort kommentarer genom att ladda upp den
1. Gör det genom att klicka inuti släppområdet genom att dra och släppa anteckningsappen
1. Beroende på storleken på PDF-filen och internethastigheten vänta i några sekunder
1. Klicka på knappen "Ta bort" för att rensa kommentarer
1. Ladda ner filen direkt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Ta bort PDF Document Comments via Android App API" %}}

1. Lägg till biblioteksreferens till Android-projektet
1. Ladda dokument via dokumentklassobjekt
1. Välj den specifika sidan via getPages().get_Item(Index)
1. Använd AnnotationSelector och få alla textkommentarer via annotationSelector.getSelected()
1. Iterera genom varje anteckning och anrop raderingsmetoden för att ta bort den.
1. Anropa sparmetoden för att spara filen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : Ta bort kommentarer från PDF-fil" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Lägg till anteckning via Android App API" %}}

1. Lägg till biblioteksreferens till Android-projektet
1. Skapa dokumentklassobjekt
1. Lägg till den nya sidan och innehållet med getPages().add()
1. Använd getPages().get_Item(Index) av klassen TextAnnotation
1. Ställ in relevanta kommentarer som titel, ämne, innehåll etc
1. Använd getAnnotations().add för att lägga till kommentarerna
1. Anropa sparmetoden för att spara filen med tillagda kommentarer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : Lägg till PDF-anteckning" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Utveckla PDF Document Annotation Android App</h2>

Behöver du utveckla en PDF-anteckningsmobilapp eller ett verktyg för att ge feedback, ge förslag eller samarbeta med andra om dokumentet?Med [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/sv/android-java/) ett underordnat API av [Aspose.Total for Android via Java](https://products.aspose.com/total/sv/android-java/), kan vilken Android-utvecklare som helst integrera ovanstående API-kod i sin dokumentanteckningsapplikation.Kraftfullt Android-bibliotek tillåter programmering av alla dokumentkommentarer.Dessutom kan den stödja många populära format inklusive PDF-format.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-bibliotek för att kommentera PDF-filer" %}}

- Vi är värd för våra Java-paket i [Maven-förråd](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java är en vanlig JAR-fil som innehåller byte-kod.
- Följ [steg för steg instruktioner](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) om hur du installerar Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

- Android API 31 och 32
- Android 4.0 och senare
- Android Studio och SDK-verktyg

<br />
För mer information om valfria paketberoenden, såsom JogAmp JOGL, Harfbuzz font-motor, Java Advanced Imaging JAI, se [Produktdokumentation](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}