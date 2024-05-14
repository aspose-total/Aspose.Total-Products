---
title: Verwijder PDF-annotatie online of beheer annotaties met behulp van mobiele Android-apps
description: verwijder opmerkingen uit het PDF-bestand gratis via de online app.Android API-code om opmerkingen over PDF-bestanden te beheren.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Wis opmerkingen uit PDF-documenten online of beheer ze via Android-apps" h2="Ontwikkel een krachtige Android-gebaseerde PDF-hulpprogramma voor documentannotatie.Code vermeld voor het beheren van opmerkingen over het PDF-bestand." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Verwijder PDF-annotaties online" %}}

1. Importeer het PDF-bestand om opmerkingen te verwijderen door deze te uploaden
1. Doe dit door in het neerzetgebied te klikken via slepen en neerzetten van de annotatie-app
1. Wacht enkele seconden, afhankelijk van de grootte van het PDF-bestand en de internetsnelheid
1. Klik op de knop 'Verwijderen' om reacties te verwijderen
1. Download het bestand direct

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Verwijder PDF-documentopmerkingen via de Android App API" %}}

1. Voeg bibliotheekreferentie toe aan het Android-project
1. Document laden via documentklasseobject
1. Selecteer de specifieke pagina via getPages().get_Item(Index)
1. Gebruik de AnnotationSelector en ontvang alle tekstannotaties via annotationSelector.getSelected()
1. Doorloop elke annotatie en roep de verwijdermethode aan om deze te verwijderen.
1. Roep de opslagmethode aan om het bestand op te slaan.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: verwijder opmerkingen uit het PDF-bestand" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Voeg annotatie toe via de Android App API" %}}

1. Voeg bibliotheekreferentie toe aan het Android-project
1. Maak een documentklasseobject
1. Voeg de nieuwe pagina en inhoud toe met getPages().add()
1. Gebruik getPages().get_Item(Index) van de klasse TextAnnotation
1. Stel de relevante annotaties in, zoals titel, onderwerp, inhoud enz
1. Gebruik getAnnotations().add om de annotaties toe te voegen
1. Roep de opslagmethode aan om het bestand met toegevoegde opmerkingen op te slaan
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code: PDF-annotatie toevoegen" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Ontwikkel een Android-app voor PDF-documentannotatie</h2>

Wilt u een mobiele PDF-annotatieapp of -hulpprogramma ontwikkelen om feedback te geven, suggesties te doen of met anderen aan het document samen te werken?Met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/nl/android-java/), een onderliggende API van [Aspose.Total for Android via Java](https://products.aspose.com/total/nl/android-java/), kan elke Android-ontwikkelaar de bovenstaande API-code integreren in zijn documentannotatietoepassing.Krachtige Android-bibliotheek maakt het programmeren van elke documentannotatie-oplossing mogelijk.Bovendien ondersteunt het vele populaire formaten, waaronder het PDF-formaat.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-bibliotheek om PDF-bestanden te annoteren" %}}

- Wij hosten onze Java-pakketten in [Maven-opslagplaatsen](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java is een veelgebruikt JAR-bestand dat bytecode bevat.
- Volg [stap voor stap instructies](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) voor het installeren van Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

- Android-API 31 en 32
- Android 4.0 en hoger
- Android Studio- en SDK-tools

<br />
Voor meer details over optionele pakketafhankelijkheden, zoals JogAmp JOGL, Harfbuzz font engine, Java Advanced Imaging JAI, raadpleeg [Productdocumentatie](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}