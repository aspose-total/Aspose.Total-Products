---
title: Vykreslete MSG do TEXT v aplikaci Andorid
description: Exportujte MSG do TEXT bez použití Microsoft Word nebo Outlook ve vašich aplikacích Andorid

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: TEXT
otherformats: RTF DOC DOT BMP FLATOPC ODT DOCX GIF PCL EMF XPS DOTX JPEG DOTM OTT WORDML DOCM SVG PS TIFF MD PNG PDF EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformujte MSG na TEXT v Andorid Apps" h2="Návrh aplikací Andorid pro export MSG do TEXT pomocí Andorid přes Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikace Andorid jsou snadno použitelné pro koncové uživatele na každodenní bázi. Počet uživatelů telefonů Andorid se každým dnem zvyšuje. Pomocí výkonných knihoven [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation můžete vyvíjet aplikace pro manipulaci a konverzi e-mailů. E-mailovou adresu MSG můžete převést na TEXT kombinací [Aspose.Msg pro Android Java](https://products.aspose.com/msg/android-java/) a [Aspose.Words pro Andorid Java](https://products.aspose.com/words/android-java/). Pomocí prvního API můžete převést formát souboru MSG do HTML a pomocí druhého API můžete vykreslit HTML jako TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést MSG na TEXT v Andoridu" %}}
1. Otevřete soubor MSG pomocí třídy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Převeďte MSG na HTML pomocí [uložit](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu TEXT pomocí [uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte TEXT jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://releases.aspose.com/total/java/) a nainstalovat [Aspose.Msg pro Android přes Javu](https://docs.aspose.com/msg/androidjava/installation/) a [Aspose.Words pro Andorid přes Javu](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}