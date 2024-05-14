---
title: Ta bort ODP-anteckningar online eller hantera anteckningar med Android-mobilappar
description: ta bort kommentarer från ODP-filen via onlineappen gratis.Android API-kod för att hantera kommentarer för ODP-filer.

family: total
platformtag: Android
feature: Annotate
informat: ODP
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Rensa kommentarer från ODP-presentation online eller hantera via Android-appar" h2="Utveckla kraftfull Android-baserad ODP-presentationsanteckningsapplikation.Kod listad för att hantera kommentarer för ODP-fil." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ta bort ODP-anteckningar online" %}}

1. Importera ODP-fil för att ta bort kommentarer genom att ladda upp den
1. Gör det genom att klicka inuti släppområdet genom att dra och släppa anteckningsappen
1. Beroende på storleken på ODP-filen och internethastigheten vänta i några sekunder
1. Klicka på knappen "Ta bort" för att rensa kommentarer
1. Ladda ner filen direkt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Ta bort ODP-presentationskommentarer via Android-appen" %}}

1. Lägg till biblioteksreferens till Android-projektet
1. Ladda ODP via Presentationsklassobjekt
1. Iterera genom varje författare via Presentation.getCommentAuthors()-samling
1. Åberopa clear()-metoden för att ta bort kommentaren
1. Ring slutligen getCommentAuthors().clear() för att ta bort alla författare
1. Anropa sparmetoden för att spara filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : Ta bort kommentarer och författare från ODP-presentation" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Lägg till ODP-presentationskommentarer via Android-appen" %}}

1. Lägg till biblioteksreferens till Android-projektet
1. Ladda ODP via Presentationsklassobjekt
1. Anropa Presentation.getCommentAuthors().addAuthor(String, String) för att lägga till författarna
1. Använd ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) för att lägga till kommentarer
1. Anropa sparmetoden för att spara filen with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod: Lägger till kommentarer" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Utveckla ODP Document Annotation Android App</h2>

Behöver du utveckla en ODP-anteckningsmobilapp eller ett verktyg för att ge feedback, ge förslag eller samarbeta med andra om dokumentet?Med [Aspose.Slides for Android via Java](https://products.aspose.com/slides/sv/android-java/) ett underordnat API av [Aspose.Total for Android via Java](https://products.aspose.com/total/sv/android-java/), kan vilken Android-utvecklare som helst integrera ovanstående API-kod i sin dokumentanteckningsapplikation.Kraftfullt Android-bibliotek tillåter programmering av alla dokumentkommentarer.Dessutom kan den stödja många populära format inklusive ODP-format.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-bibliotek för att kommentera ODP-filer" %}}

- Vi är värd för våra Java-paket i [Maven-förråd](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/). 
- Aspose.Slides for Java är en vanlig JAR-fil som innehåller byte-kod.
- Följ [steg för steg instruktioner](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) om hur du installerar Aspose.Slides for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

- J2SE 6.0 (Java 1.6) och högre
- Java-paketet är plattformsoberoende och körs på alla operativsystem med JVM-implementering.

<br />
För mer information, se [Produktdokumentation](https://docs.aspose.com/slides/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}