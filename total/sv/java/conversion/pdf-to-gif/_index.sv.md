---
title: Konvertering online från PDF till GIF eller utveckla Java-baserad applikation för att konvertera PDF-filer
description: Gratis onlineapp för att konvertera PDF till GIF-filer. Java-konverteringsbibliotekskod för PDF-dokument.  

family: total
platformtag: Java
feature: conversion
informat: PDF
outformat: GIF
otherformats: DOTM PS MHTML PCL WORDML FLATOPC MARKDOWN DOT GIF RTF XAMLFLOW ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Online PDF till GIF-konverteringsapp och Java-kod för att konvertera PDF-filer" h2="Utveckla kraftfull Java-baserad PDF konvertering och export applikation.  Konvertera enstaka eller flera PDF-filer till GIF och andra format via Java Automation API.  Konvertera fritt PDF-filer online via app med omedelbar nedladdning." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Gratis onlinekonverteringsapp från PDF till GIF" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=gif&from=pdf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera filer från PDF till GIF online med appen" %}}

1. Ladda upp PDF-filer för att konvertera
1. Vänta i några sekunder eller mer beroende på storleken på PDF
1. Håll ett öga på uppladdningsstatusfältet
1. Klicka på knappen "Konvertera".
1. PDF kommer att konverteras till GIF-dokument
1. Ladda ner den konverterade GIF-filen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertera PDF till GIF via Java Automation API" %}}


1. Öppna PDF-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera PDF till DOC genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda DOC-fil genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) av Aspose.Words
4. Spara dokumentet i GIF-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) och ställ in GIF som SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}


```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```



{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Få fler fall för att spara PDF till GIF med andra funktioner som Konverteringskrav, Öppna lösenordsskyddat PDF-dokument via Java.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Utveckla PDF filkonverteringsapplikation med Java</h2>

Behöver du utveckla Java-baserad programvara för att enkelt spara och exportera PDF-filer till GIF-dokument?  Med [Aspose.Total for Java](https://products.aspose.com/total/sv/java/) kan alla Java-utvecklare integrera ovanstående API-kod för att programmera konverteringsapplikationen i olika format inklusive Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, e-postfiler, bilder (JPG, PNG, BMP, GIF) och andra format.  Kraftfullt Java-bibliotek för dokumentkonvertering, stöder många populära format inklusive PDF-format.  Genom att exportera och rendera dokument till andra format kan programmerare använda Aspose.Total for Java underordnade API:er inklusive [Aspose.Words for Java](https://products.aspose.com/words/sv/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/sv/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/sv/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/sv/java/) och mer.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF Konverteringsbibliotek för Java" %}}

Det finns alternativa alternativ för att integrera Aspose.Total for Java på ditt system.  Välj en som liknar dina behov och följ steg-för-steg-instruktionerna:<br /><br />

- Använd Aspose.Total for Java direkt från ett Maven-baserat projekt och inkludera relevant underordnad API i pom.xml.
- Alternativt kan man få en ZIP-fil från [nedladdningar](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sparar PDF till GIF appkrav" %}}

Alla operativsystem som kan köra Java Runtime Environment (JRE) kan köra Aspose.Total for Java.  Följande listar de flesta, men inte alla, operativsystem som stöds.  <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS och andra
- macOS: 10.9 (Mavericks) och senare
- Mobil: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}
**PDF till GIF**-konverteringsprocessen används i stor utsträckning för att skapa **animerade eller statiska GIF:ar** från PDF-dokument. Det möjliggör snabb delning av PDF-sidor som lätta GIF:ar, perfekta för **sociala medier, e-lärande och digitala marknadsföringsflöden**.
{{% blocks/products/pf/agp/feature-section-col title="Huvudsakliga användningsområden" %}}
- Konvertera PDF-presentationer till animerade GIF:ar
- Dela PDF-innehåll på **sociala medieplattformar**
- Skapa utbildnings-GIF:ar från PDF-diagram
- Marknadsföringskampanjer med **lätta GIF-innehåll**
- Snabb förhandsgranskning av PDF-sidor
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenarier" %}}
- Automatiserad **PDF till GIF batchkonvertering**
- PDF-till-GIF-pipelines för schemaläggning i sociala medier
- Utbildningsflöden som genererar GIF:ar från läroböcker
- Integration med marknadsföringsplattformar för GIF-kampanjer
- Företagsautomatisering för förhandsgranskning av PDF som GIF
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}