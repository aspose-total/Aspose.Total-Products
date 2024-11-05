---
title: Exportera MSG till DOTM via Java
description: Java API för att konvertera MSG till DOTM utan att använda Microsoft Word eller Outlook
url_ignore: /sv/java/conversion/msg-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOTM
otherformats: EPUB DOCM MD XPS JPEG EMF OTT DOTM PNG FLATOPC GIF DOTX SVG TIFF DOT PS WORDML PCL PDF DOCX ODT DOC TEXT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att rendera MSG till DOTM" h2="Exportera MSG till DOTM genom att använda det lokala Java API utan att använda några tredje parts beroenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-postkonvertering är en kraftfull funktion som Java-utvecklare kan integrera i alla Java J2SE, J2EE, J2ME-applikationer via [Aspose.Total for Java](https://products.aspose.com/total/java/). Genom att använda två API:er i paketet kan du konvertera e-post MSG till DOTM utan några tredje parts beroenden. För det första kan du använda Msg Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) för att konvertera MSG-filformat till HTML. För det andra kan du rendera HTML till DOTM genom att använda Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar MSG till DOTM" %}}
1. Öppna MSG-filen med klassen [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Konvertera MSG till HTML genom att använda [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) metod
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i DOTM-format med [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) och ställ in DOTM som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du måste använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}