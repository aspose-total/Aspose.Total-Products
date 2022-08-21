---
title: Vykreslete OFT do DOTM v aplikaci Andorid
description: Exportujte OFT do DOTM bez použití Microsoft Word nebo Outlook ve vašich aplikacích Andorid
url: /cs/android-java/conversion/oft-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOTM
otherformats: FLATOPC PDF GIF TEXT DOT XPS RTF PCL MD EPUB OTT EMF DOTX BMP DOCX PS ODT DOCM PNG DOC SVG JPEG TIFF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformujte OFT na DOTM v Andorid Apps" h2="Návrh aplikací Andorid pro export OFT do DOTM pomocí Andorid přes Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikace Andorid jsou snadno použitelné pro koncové uživatele na každodenní bázi. Počet uživatelů telefonů Andorid se každým dnem zvyšuje. Pomocí výkonných knihoven [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation můžete vyvíjet aplikace pro manipulaci a konverzi e-mailů. E-mailovou adresu OFT můžete převést na DOTM kombinací [Aspose.Oft pro Android Java](https://products.aspose.com/oft/android-java/) a [Aspose.Words pro Andorid Java](https://products.aspose.com/words/android-java/). Pomocí prvního API můžete převést formát souboru OFT do HTML a pomocí druhého API můžete vykreslit HTML jako DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést OFT na DOTM v Andoridu" %}}
1. Otevřete soubor OFT pomocí třídy [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Převeďte OFT na HTML pomocí [uložit](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu DOTM pomocí [uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte DOTM jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Oft pro Android přes Javu](https://docs.aspose.com/oft/androidjava/installation/) a [Aspose.Words pro Andorid přes Javu](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOTM
document.save("output.dotm", SaveFormat.DOTM); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-flatopc/" name="OFT Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-pdf/" name="OFT Na PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-gif/" name="OFT Na GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-text/" name="OFT Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-dot/" name="OFT Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-xps/" name="OFT Na XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-rtf/" name="OFT Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-pcl/" name="OFT Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-md/" name="OFT Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-epub/" name="OFT Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-ott/" name="OFT Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-emf/" name="OFT Na EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-dotx/" name="OFT Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-dotm/" name="OFT Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-docx/" name="OFT Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-ps/" name="OFT Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-odt/" name="OFT Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-docm/" name="OFT Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-png/" name="OFT Na PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-doc/" name="OFT Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-svg/" name="OFT Na SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-jpeg/" name="OFT Na JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-tiff/" name="OFT Na TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/oft-to-wordml/" name="OFT Na WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}