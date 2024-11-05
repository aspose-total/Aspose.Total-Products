---
title: Exportálja az EMAIL-t PDF-be Java-n keresztül
description: Java API az EMAIL PDF-vé konvertálásához Microsoft Word vagy Outlook használata nélkül
url_ignore: /hu/java/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: XPS DOC TEXT PDF GIF PCL DOTX DOCM MD EMF OTT RTF DOT ODT TIFF EPUB FLATOPC SVG WORDML PS JPEG DOTM DOCX PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API az EMAIL rendereléséhez PDF-be" h2="Exportálja az EMAIL e-mail-címet PDF-be a helyszíni Java API használatával, harmadik féltől származó függőségek használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az e-mail konvertálás egy hatékony funkció, amelyet a Java fejlesztők integrálhatnak bármely Java J2SE, J2EE, J2ME alkalmazásba az [Aspose.Total for Java](https://products.aspose.com/total/java/). A csomagon belüli két API használatával az EMAIL e-mail címet PDF-vé alakíthatja harmadik féltől való függőség nélkül. Először is használhatja az Email Manipulation API-t [Aspose.Email for Java](https://products.aspose.com/email/java/) az EMAIL fájlformátum HTML-lé alakításához. Másodszor, a HTML-t PDF-be renderelheti a Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet az EMAIL-t PDF-vé konvertálni" %}}
1. Nyissa meg az EMAIL fájlt a [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) osztály használatával
2. Alakítsa át az EMAIL e-mail-címet HTML-vé a [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) segítségével)) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot PDF formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) metódust, és állítsa be a PDF-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://releases.aspose.com/total/java/) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-pdf.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}