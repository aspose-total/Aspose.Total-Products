---
title: Exportálja az EML-t DOCM-be Java-n keresztül
description: Java API az EML DOCM-vé konvertálásához Microsoft Word vagy Outlook használata nélkül
url_ignore: /hu/java/conversion/eml-to-docm/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCM
otherformats: ODT TEXT RTF DOTX PNG GIF SVG EMF EPUB DOCX DOC PS PCL WORDML MD TIFF DOTM XPS JPEG PDF FLATOPC OTT DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API az EML rendereléséhez DOCM-be" h2="Exportálja az EML e-mail-címet DOCM-be a helyszíni Java API használatával, harmadik féltől származó függőségek használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az e-mail konvertálás egy hatékony funkció, amelyet a Java fejlesztők integrálhatnak bármely Java J2SE, J2EE, J2ME alkalmazásba az [Aspose.Total for Java](https://products.aspose.com/total/java/). A csomagon belüli két API használatával az EML e-mail címet DOCM-vé alakíthatja harmadik féltől való függőség nélkül. Először is használhatja az Eml Manipulation API-t [Aspose.Email for Java](https://products.aspose.com/email/java/) az EML fájlformátum HTML-lé alakításához. Másodszor, a HTML-t DOCM-be renderelheti a Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet az EML-t DOCM-vé konvertálni" %}}
1. Nyissa meg az EML fájlt a [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) osztály használatával
2. Alakítsa át az EML e-mail-címet HTML-vé a [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) segítségével)) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot DOCM formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) metódust, és állítsa be a DOCM-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://releases.aspose.com/total/java/) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCM
document.save("output.docm", SaveFormat.DOCM);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}