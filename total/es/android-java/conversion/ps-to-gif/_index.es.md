---
title: API de Android para renderizar PS a GIF
description: Transforme PS a GIF a través de Android a través de la API de Java
url: /es/android-java/conversion/ps-to-gif/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: GIF
otherformats: PCL FLATOPC DOT WORDML XAMLFLOW OTT MARKDOWN RTF MHTML DOCM ODT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PS a GIF en Android a través de Java" h2="Convierta PS a GIF en aplicaciones móviles sin instalar ningún software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de PS a GIF en sus aplicaciones móviles mediante el uso de dos API del paquete [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Primero debe convertir el archivo PS a DOC usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). En segundo lugar, mediante el uso de la API de procesamiento de textos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puede convertir DOC en GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta PS a GIF en Android a través de Java" %}}
1. Abra el archivo PS usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta PS a DOC usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el archivo DOC usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato GIF usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure GIF como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga información del archivo PS en Android a través de Java" %}}
Antes de convertir PS a GIF, es posible que necesite información sobre el documento, incluido el autor, la fecha de creación, las palabras clave, la fecha de modificación, el asunto y el título. Esta información es útil para la toma de decisiones para el proceso de conversión. Con la potente API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), puede obtenerlo todo. Para obtener información específica de un archivo PS, primero obtenga el objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Una vez que se recupera el objeto DocumentInfo, puede obtener los valores de las propiedades individuales.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS document
Document doc = new Document("template.ps");
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

{{% blocks/products/pf/feature-page-section  h2="Insertar notas finales en el documento GIF en Android a través de Java" %}}
Además de la conversión de documentos, también puede agregar un montón de otras funciones dentro de sus aplicaciones de Android utilizando la API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Una de esas características es la inserción de notas al final y la numeración en el documento GIF. Si desea insertar una nota al pie o una nota al final en un documento GIF, utilice el método DocumentBuilder.InsertFootnote. Este método inserta una nota al pie o una nota al final en el documento. Las clases EndnoteOptions y FootnoteOptions representan opciones de numeración para notas al pie y notas al final.
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
doc.save("output.gif", SaveFormat.GIF);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-pcl/" name="PS A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-flatopc/" name="PS A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-dot/" name="PS A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-wordml/" name="PS A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-xamlflow/" name="PS A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-ott/" name="PS A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-markdown/" name="PS A MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-rtf/" name="PS A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-mhtml/" name="PS A MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-gif/" name="PS A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-odt/" name="PS A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ps-to-dotm/" name="PS A DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}