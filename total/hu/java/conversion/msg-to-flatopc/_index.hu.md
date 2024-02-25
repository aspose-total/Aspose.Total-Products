---
title: Exportálja az MSG-t FLATOPC-be Java-n keresztül
description: Java API az MSG FLATOPC-vé konvertálásához Microsoft Word vagy Outlook használata nélkül
url_ignore: /hu/java/conversion/msg-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: FLAT_OPC
otherformats: FLATOPC SVG XPS PCL GIF DOTM DOCM PDF DOTX PS EPUB DOT DOC JPEG TIFF WORDML EMF PNG MD ODT TEXT DOCX RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API az MSG rendereléséhez FLATOPC-be" h2="Exportálja az MSG e-mail-címet FLATOPC-be a helyszíni Java API használatával, harmadik féltől származó függőségek használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az e-mail konvertálás egy hatékony funkció, amelyet a Java fejlesztők integrálhatnak bármely Java J2SE, J2EE, J2ME alkalmazásba az [Aspose.Total for Java](https://products.aspose.com/total/java/). A csomagon belüli két API használatával az MSG e-mail címet FLATOPC-vé alakíthatja harmadik féltől való függőség nélkül. Először is használhatja az Msg Manipulation API-t [Aspose.Email for Java](https://products.aspose.com/email/java/) az MSG fájlformátum HTML-lé alakításához. Másodszor, a HTML-t FLATOPC-be renderelheti a Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet az MSG-t FLATOPC-vé konvertálni" %}}
1. Nyissa meg az MSG fájlt a [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) osztály használatával
2. Alakítsa át az MSG e-mail-címet HTML-vé a [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) segítségével)) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot FLATOPC formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) metódust, és állítsa be a FLATOPC-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://releases.aspose.com/total/java/) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.FLAT_OPC
document.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}