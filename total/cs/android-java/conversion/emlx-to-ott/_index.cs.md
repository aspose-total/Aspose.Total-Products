---
title: Vykreslete EMLX do OTT v aplikaci Andorid
description: Exportujte EMLX do OTT bez použití Microsoft Word nebo Outlook ve vašich aplikacích Andorid

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: OTT
otherformats: GIF MD EPUB BMP FLATOPC DOC EMF PNG SVG TEXT DOTX DOCX TIFF ODT WORDML JPEG PCL XPS PS DOCM PDF DOT RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformujte EMLX na OTT v Andorid Apps" h2="Návrh aplikací Andorid pro export EMLX do OTT pomocí Andorid přes Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikace Andorid jsou snadno použitelné pro koncové uživatele na každodenní bázi. Počet uživatelů telefonů Andorid se každým dnem zvyšuje. Pomocí výkonných knihoven [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation můžete vyvíjet aplikace pro manipulaci a konverzi e-mailů. E-mailovou adresu EMLX můžete převést na OTT kombinací [Aspose.Emlx pro Android Java](https://products.aspose.com/emlx/android-java/) a [Aspose.Words pro Andorid Java](https://products.aspose.com/words/android-java/). Pomocí prvního API můžete převést formát souboru EMLX do HTML a pomocí druhého API můžete vykreslit HTML jako OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést EMLX na OTT v Andoridu" %}}
1. Otevřete soubor EMLX pomocí třídy [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Převeďte EMLX na HTML pomocí [uložit](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu OTT pomocí [uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte OTT jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Emlx pro Android přes Javu](https://docs.aspose.com/emlx/androidjava/installation/) a [Aspose.Words pro Andorid přes Javu](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.OTT
document.save("output.ott", SaveFormat.OTT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-gif/" name="EMLX Na GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-md/" name="EMLX Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-epub/" name="EMLX Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-ott/" name="EMLX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-flatopc/" name="EMLX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-doc/" name="EMLX Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-emf/" name="EMLX Na EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-png/" name="EMLX Na PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-svg/" name="EMLX Na SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-text/" name="EMLX Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-dotx/" name="EMLX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-docx/" name="EMLX Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-tiff/" name="EMLX Na TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-odt/" name="EMLX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-wordml/" name="EMLX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-jpeg/" name="EMLX Na JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-pcl/" name="EMLX Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-xps/" name="EMLX Na XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-ps/" name="EMLX Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-docm/" name="EMLX Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-pdf/" name="EMLX Na PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-dot/" name="EMLX Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-rtf/" name="EMLX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/emlx-to-dotm/" name="EMLX Na DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}