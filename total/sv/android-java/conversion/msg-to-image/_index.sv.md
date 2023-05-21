---
title: Skicka MSG till IMAGE i Andorid-appen
description: Exportera MSG till IMAGE utan att använda Microsoft Word eller Outlook i dina Andorid-program

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: IMAGE
otherformats: PDF EPUB OTT RTF DOC EMF SVG DOCM TIFF DOCX DOTM ODT MD GIF PNG DOT XPS DOTX FLATOPC JPEG BMP WORDML PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Förvandla MSG till IMAGE i Andorid Apps" h2="Utformar Andorid-applikationer för att exportera MSG till IMAGE genom att använda Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps är enkla att använda för slutanvändare dagligen. Dag för dag ökar antalet användare av Andorid-telefoner. Genom att använda de kraftfulla [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) filformatsautomatiseringsbibliotek kan du utveckla applikationer för e-postmanipulation och -konvertering. Du kan konvertera MSG till IMAGE genom att kombinera [Aspose.Msg for Android Java](https://products.aspose.com/msg/android-java/) och [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Med det första API:et kan du konvertera MSG-filformatet till HTML och genom att använda det andra API:et kan du rendera HTML som IMAGE. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera MSG till IMAGE i Andorid" %}}
1. Öppna MSG-filen med klassen [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. Konvertera MSG till HTML genom att använda [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) metod
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i IMAGE-format med [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) och ställ in IMAGE som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://releases.aspose.com/total/java/) och installera [Aspose.Msg för Android via Java](https://docs.aspose.com/msg/androidjava/installation/) och [Aspose.Words för Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}