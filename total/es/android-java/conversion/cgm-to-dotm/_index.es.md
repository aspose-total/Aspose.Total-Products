---
title: API de Android para renderizar CGM a DOTM
description: Transforme CGM a DOTM a través de Android a través de la API de Java
url: /es/android-java/conversion/cgm-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: DOTM
otherformats: MARKDOWN FLATOPC DOTX DOT WORDML PS XAMLFLOW ODT MHTML OTT RTF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar CGM a DOTM en Android a través de Java" h2="Convierta CGM a DOTM en aplicaciones móviles sin instalar ningún software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de CGM a DOTM en sus aplicaciones móviles mediante el uso de dos API del paquete [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Primero debe convertir el archivo CGM a DOC usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). En segundo lugar, mediante el uso de la API de procesamiento de textos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puede convertir DOC en DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta CGM a DOTM en Android a través de Java" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta CGM a DOC usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el archivo DOC usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato DOTM usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure DOTM como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga información del archivo CGM en Android a través de Java" %}}
Antes de convertir CGM a DOTM, es posible que necesite información sobre el documento, incluido el autor, la fecha de creación, las palabras clave, la fecha de modificación, el asunto y el título. Esta información es útil para la toma de decisiones para el proceso de conversión. Con la potente API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), puede obtenerlo todo. Para obtener información específica de un archivo CGM, primero obtenga el objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Una vez que se recupera el objeto DocumentInfo, puede obtener los valores de las propiedades individuales.
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM document
Document doc = new Document("template.cgm");
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

{{% blocks/products/pf/feature-page-section  h2="Insertar notas finales en el documento DOTM en Android a través de Java" %}}
Además de la conversión de documentos, también puede agregar un montón de otras funciones dentro de sus aplicaciones de Android utilizando la API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Una de esas características es la inserción de notas al final y la numeración en el documento DOTM. Si desea insertar una nota al pie o una nota al final en un documento DOTM, utilice el método DocumentBuilder.InsertFootnote. Este método inserta una nota al pie o una nota al final en el documento. Las clases EndnoteOptions y FootnoteOptions representan opciones de numeración para notas al pie y notas al final.
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
doc.save("output.dotm", SaveFormat.DOTM);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-markdown/" name="CGM A MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-flatopc/" name="CGM A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-dotx/" name="CGM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-dot/" name="CGM A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-wordml/" name="CGM A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-ps/" name="CGM A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-xamlflow/" name="CGM A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-odt/" name="CGM A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-mhtml/" name="CGM A MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-ott/" name="CGM A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-rtf/" name="CGM A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/cgm-to-pcl/" name="CGM A PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}