---
title: Απόδοση OFT σε GIF στην εφαρμογή Andorid
description: Εξαγωγή OFT σε GIF χωρίς χρήση του Microsoft Word ή του Outlook σε εφαρμογές Andorid

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: GIF
otherformats: EPUB RTF DOTX DOTM TEXT XPS EMF TIFF OTT FLATOPC DOCM PS DOT DOCX DOC WORDML PCL SVG ODT PNG PDF BMP MD JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε το OFT σε GIF στις εφαρμογές Andorid" h2="Σχεδιασμός εφαρμογών Andorid για εξαγωγή OFT σε GIF χρησιμοποιώντας το Andorid μέσω Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Οι εφαρμογές Andorid είναι εύκολες στη χρήση για τους τελικούς χρήστες σε καθημερινή βάση. Μέρα με τη μέρα ο αριθμός των χρηστών τηλεφώνων Andorid αυξάνεται. Χρησιμοποιώντας τις πανίσχυρες βιβλιοθήκες [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Αυτοματισμού μορφοποίησης αρχείων, μπορείτε να αναπτύξετε εφαρμογές χειρισμού oft και μετατροπής. Μπορείτε να μετατρέψετε OFT σε GIF με το συνδυασμό των [Aspose.Oft για Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words για Andorid Java](https://products.aspose.com/words/android-java/). Χρησιμοποιώντας το πρώτο API μπορείτε να μετατρέψετε τη μορφή αρχείου OFT σε HTML και χρησιμοποιώντας το δεύτερο API, μπορείτε να αποδώσετε το HTML ως GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή OFT σε GIF στο Andorid" %}}
1. Ανοίξτε το αρχείο OFT χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Μετατρέψτε το OFT σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) μέθοδος
3. Φορτώστε HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή GIF χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το GIF ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.Oft για Android μέσω Java](https://docs.aspose.com/oft/androidjava/installation/) και το [Aspose.Words for Andorid μέσω Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.GIF
document.save("output.gif", SaveFormat.GIF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-epub/" name="OFT Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-rtf/" name="OFT Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-dotx/" name="OFT Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-dotm/" name="OFT Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-text/" name="OFT Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-xps/" name="OFT Προς την XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-emf/" name="OFT Προς την EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-tiff/" name="OFT Προς την TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-ott/" name="OFT Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-flatopc/" name="OFT Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-docm/" name="OFT Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-ps/" name="OFT Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-dot/" name="OFT Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-docx/" name="OFT Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-doc/" name="OFT Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-wordml/" name="OFT Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-pcl/" name="OFT Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-svg/" name="OFT Προς την SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-odt/" name="OFT Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-png/" name="OFT Προς την PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-pdf/" name="OFT Προς την PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-gif/" name="OFT Προς την GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-md/" name="OFT Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/oft-to-jpeg/" name="OFT Προς την JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}