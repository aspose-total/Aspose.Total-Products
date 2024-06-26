---
title: Rendelje meg az OFT-t DOC-nek az Andorid alkalmazásban
description: Exportálja az OFT-t DOC-be Microsoft Word vagy Outlook használata nélkül az Andorid-alkalmazásokban

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOC
otherformats: MD GIF DOTM WORDML SVG DOCX DOT ODT PNG TIFF EPUB XPS OTT TEXT PS EMF DOTX FLATOPC DOCM PCL RTF JPEG PDF BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Alakítsa át az OFT-t DOC-vé az Andorid Apps-ben" h2="Andorid alkalmazások tervezése OFT DOC-be exportálásához Andorid használatával Java API-n keresztül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az Andorid Apps a végfelhasználók számára napi szinten könnyen használható. Napról napra nő az Andorid telefonokat használók száma. A hatékony [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) fájlformátum-automatizálási könyvtárak segítségével e-mail-kezelési és -konvertáló alkalmazásokat fejleszthet. Az OFT-t DOC-vé konvertálhatja az [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) és az [Aspose.Words for Andorid Java](https://) kombinációjával products.aspose.com/words/android-java/). Az első API-val konvertálhatja az OFT fájlformátumot HTML-re, a második API-val pedig a HTML-t DOC-ként jelenítheti meg. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Az OFT konvertálása DOC-re az Andoridban" %}}
1. Nyissa meg az OFT fájlt a [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage) osztály használatával
2. Alakítsa át az OFT-címet HTML-vé a [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) segítségével )) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot DOC formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) segítségével metódust, és állítsa be a DOC-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és telepítse az [Aspose.Oft for Android via Java](https://docs.aspose.com/oft/androidjava/installation/) és az [Aspose.Words for Andorid via Java](https://docs.aspose.com/words) /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOC
document.save("output.doc", SaveFormat.DOC); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}