---
title: API de Android para renderizar SVG a DOTX
description: Transforme SVG a DOTX a través de Android a través de la API de Java
url: /es/android-java/conversion/svg-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOTX
otherformats: PCL FLATOPC ODT MARKDOWN DOTM DOT WORDML PS RTF DOCM XAMLFLOW OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar SVG a DOTX en Android a través de Java" h2="Convierta SVG a DOTX en aplicaciones móviles sin instalar ningún software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de SVG a DOTX en sus aplicaciones móviles mediante el uso de dos API del paquete [Aspose.Total para Android Java](https://products.aspose.com/total/android-java/). Primero debe convertir el archivo SVG a DOC usando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/). En segundo lugar, mediante el uso de la API de procesamiento de textos [Aspose.Words para Android Java](https://products.aspose.com/words/android-java/), puede convertir DOC en DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta SVG a DOTX en Android a través de Java" %}}
1. Abra el archivo SVG usando la clase [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta SVG a DOC usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el archivo DOC usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato DOTX usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure DOTX como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Words para Android a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTX
outputDocument.save("output.dotx", SaveFormat.DOTX);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga información del archivo SVG en Android a través de Java" %}}
Antes de convertir SVG a DOTX, es posible que necesite información sobre el documento, incluido el autor, la fecha de creación, las palabras clave, la fecha de modificación, el asunto y el título. Esta información es útil para la toma de decisiones para el proceso de conversión. Con la potente API [Aspose.PDF para Android a través de Java](https://docs.aspose.com/pdf/androidjava/), puede obtenerlo todo. Para obtener información específica de un archivo SVG, primero obtenga el objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Una vez que se recupera el objeto DocumentInfo, puede obtener los valores de las propiedades individuales.
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG document
Document doc = new Document("template.svg");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Insertar notas finales en el documento DOTX en Android a través de Java" %}}
Además de la conversión de documentos, también puede agregar un montón de otras funciones dentro de sus aplicaciones de Android utilizando la API [Aspose.Words para Android a través de Java](https://products.aspose.com/words/androidjava/). Una de esas características es la inserción de notas al final y la numeración en el documento DOTX. Si desea insertar una nota al pie o una nota al final en un documento DOTX, utilice el método DocumentBuilder.InsertFootnote. Este método inserta una nota al pie o una nota al final en el documento. Las clases EndnoteOptions y FootnoteOptions representan opciones de numeración para notas al pie y notas al final.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.dotx", SaveFormat.DOTX);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-pcl/" name="SVG A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-flatopc/" name="SVG A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-odt/" name="SVG A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-markdown/" name="SVG A MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-dotm/" name="SVG A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-dot/" name="SVG A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-wordml/" name="SVG A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-ps/" name="SVG A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-rtf/" name="SVG A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-dotx/" name="SVG A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-xamlflow/" name="SVG A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/svg-to-ott/" name="SVG A OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}