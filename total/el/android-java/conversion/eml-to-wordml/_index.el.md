---
title: Απόδοση EML σε WORDML στην εφαρμογή Andorid
description: Εξαγωγή EML σε WORDML χωρίς χρήση του Microsoft Word ή του Outlook σε εφαρμογές Andorid

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: WORD_ML
otherformats: DOC EPUB PS PDF DOT DOTM GIF DOTX PCL EMF FLATOPC RTF ODT OTT TEXT DOCM JPEG PNG XPS DOCX BMP TIFF MD SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε το EML σε WORDML στις εφαρμογές Andorid" h2="Σχεδιασμός εφαρμογών Andorid για εξαγωγή EML σε WORDML χρησιμοποιώντας το Andorid μέσω Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Οι εφαρμογές Andorid είναι εύκολες στη χρήση για τους τελικούς χρήστες σε καθημερινή βάση. Μέρα με τη μέρα ο αριθμός των χρηστών τηλεφώνων Andorid αυξάνεται. Χρησιμοποιώντας τις πανίσχυρες βιβλιοθήκες [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Αυτοματισμού μορφοποίησης αρχείων, μπορείτε να αναπτύξετε εφαρμογές χειρισμού eml και μετατροπής. Μπορείτε να μετατρέψετε EML σε WORDML με το συνδυασμό των [Aspose.Eml για Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words για Andorid Java](https://products.aspose.com/words/android-java/). Χρησιμοποιώντας το πρώτο API μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML και χρησιμοποιώντας το δεύτερο API, μπορείτε να αποδώσετε το HTML ως WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή EML σε WORDML στο Andorid" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) μέθοδος
3. Φορτώστε HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή WORDML χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το WORDML ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.Eml για Android μέσω Java](https://docs.aspose.com/eml/androidjava/installation/) και το [Aspose.Words for Andorid μέσω Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.WORD_ML
document.save("output.word_ml", SaveFormat.WORD_ML); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-doc/" name="EML Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-epub/" name="EML Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-ps/" name="EML Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-pdf/" name="EML Προς την PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-dot/" name="EML Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-dotm/" name="EML Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-gif/" name="EML Προς την GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-dotx/" name="EML Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-pcl/" name="EML Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-emf/" name="EML Προς την EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-flatopc/" name="EML Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-rtf/" name="EML Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-odt/" name="EML Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-ott/" name="EML Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-text/" name="EML Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-docm/" name="EML Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-jpeg/" name="EML Προς την JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-png/" name="EML Προς την PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-xps/" name="EML Προς την XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-docx/" name="EML Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-wordml/" name="EML Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-tiff/" name="EML Προς την TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-md/" name="EML Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/eml-to-svg/" name="EML Προς την SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}