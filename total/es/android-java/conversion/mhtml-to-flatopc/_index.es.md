---
title: API de Android para renderizar MHTML a FLATOPC
description: Transforme MHTML a FLATOPC a través de Android a través de la API de Java
url: /es/android-java/conversion/mhtml-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: FLAT_OPC
otherformats: RTF OTT XAMLFLOW DOTM WORDML MARKDOWN ODT PCL DOTX PS DOCM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar MHTML a FLATOPC en Android a través de Java" h2="Convierta MHTML a FLATOPC en aplicaciones móviles sin instalar ningún software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de MHTML a FLATOPC en sus aplicaciones móviles mediante el uso de dos API del paquete [Aspose.Total para Android Java](https://products.aspose.com/total/android-java/). Primero debe convertir el archivo MHTML a DOC usando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/). En segundo lugar, mediante el uso de la API de procesamiento de textos [Aspose.Words para Android Java](https://products.aspose.com/words/android-java/), puede convertir DOC en FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta MHTML a FLATOPC en Android a través de Java" %}}
1. Abra el archivo MHTML usando la clase [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MHTML a DOC usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el archivo DOC usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato FLATOPC usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure FLATOPC como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Words para Android a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga información del archivo MHTML en Android a través de Java" %}}
Antes de convertir MHTML a FLATOPC, es posible que necesite información sobre el documento, incluido el autor, la fecha de creación, las palabras clave, la fecha de modificación, el asunto y el título. Esta información es útil para la toma de decisiones para el proceso de conversión. Con la potente API [Aspose.PDF para Android a través de Java](https://docs.aspose.com/pdf/androidjava/), puede obtenerlo todo. Para obtener información específica de un archivo MHTML, primero obtenga el objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Una vez que se recupera el objeto DocumentInfo, puede obtener los valores de las propiedades individuales.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML document
Document doc = new Document("template.mhtml");
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

{{% blocks/products/pf/feature-page-section  h2="Insertar notas finales en el documento FLATOPC en Android a través de Java" %}}
Además de la conversión de documentos, también puede agregar un montón de otras funciones dentro de sus aplicaciones de Android utilizando la API [Aspose.Words para Android a través de Java](https://products.aspose.com/words/androidjava/). Una de esas características es la inserción de notas al final y la numeración en el documento FLATOPC. Si desea insertar una nota al pie o una nota al final en un documento FLATOPC, utilice el método DocumentBuilder.InsertFootnote. Este método inserta una nota al pie o una nota al final en el documento. Las clases EndnoteOptions y FootnoteOptions representan opciones de numeración para notas al pie y notas al final.
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
doc.save("output.flat_opc", SaveFormat.FLAT_OPC);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-rtf/" name="MHTML A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-ott/" name="MHTML A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-xamlflow/" name="MHTML A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-dotm/" name="MHTML A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-wordml/" name="MHTML A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-markdown/" name="MHTML A MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-odt/" name="MHTML A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-pcl/" name="MHTML A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-dotx/" name="MHTML A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-ps/" name="MHTML A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-flatopc/" name="MHTML A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/mhtml-to-dot/" name="MHTML A DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}