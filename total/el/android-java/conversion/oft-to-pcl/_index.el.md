---
title: Απόδοση OFT σε PCL στην εφαρμογή Andorid
description: Εξαγωγή OFT σε PCL χωρίς χρήση του Microsoft Word ή του Outlook σε εφαρμογές Andorid

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PCL
otherformats: TIFF ODT TEXT DOCX MD EPUB PNG DOC FLATOPC DOTX OTT DOT SVG RTF WORDML JPEG DOTM PS PDF BMP XPS EMF DOCM GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε το OFT σε PCL στις εφαρμογές Andorid" h2="Σχεδιασμός εφαρμογών Andorid για εξαγωγή OFT σε PCL χρησιμοποιώντας το Andorid μέσω Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Οι εφαρμογές Andorid είναι εύκολες στη χρήση για τους τελικούς χρήστες σε καθημερινή βάση. Μέρα με τη μέρα ο αριθμός των χρηστών τηλεφώνων Andorid αυξάνεται. Χρησιμοποιώντας τις πανίσχυρες βιβλιοθήκες [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Αυτοματισμού μορφοποίησης αρχείων, μπορείτε να αναπτύξετε εφαρμογές χειρισμού oft και μετατροπής. Μπορείτε να μετατρέψετε OFT σε PCL με το συνδυασμό των [Aspose.Oft για Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words για Andorid Java](https://products.aspose.com/words/android-java/). Χρησιμοποιώντας το πρώτο API μπορείτε να μετατρέψετε τη μορφή αρχείου OFT σε HTML και χρησιμοποιώντας το δεύτερο API, μπορείτε να αποδώσετε το HTML ως PCL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή OFT σε PCL στο Andorid" %}}
1. Ανοίξτε το αρχείο OFT χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Μετατρέψτε το OFT σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) μέθοδος
3. Φορτώστε HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή PCL χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το PCL ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://releases.aspose.com/total/java/) και εγκαταστήστε το [Aspose.Oft για Android μέσω Java](https://docs.aspose.com/oft/androidjava/installation/) και το [Aspose.Words for Andorid μέσω Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

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
// call save method while passing SaveFormat.PCL
document.save("output.pcl", SaveFormat.PCL); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}