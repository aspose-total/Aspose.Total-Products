---
title: Απόδοση MSG σε MD στην εφαρμογή Andorid
description: Εξαγωγή MSG σε MD χωρίς χρήση του Microsoft Word ή του Outlook σε εφαρμογές Andorid

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: MD
otherformats: DOTM TIFF WORDML EMF FLATOPC OTT PNG PS DOCX XPS DOC PCL DOCM RTF ODT EPUB TEXT BMP PDF GIF SVG DOTX JPEG DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε το MSG σε MD στις εφαρμογές Andorid" h2="Σχεδιασμός εφαρμογών Andorid για εξαγωγή MSG σε MD χρησιμοποιώντας το Andorid μέσω Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Οι εφαρμογές Andorid είναι εύκολες στη χρήση για τους τελικούς χρήστες σε καθημερινή βάση. Μέρα με τη μέρα ο αριθμός των χρηστών τηλεφώνων Andorid αυξάνεται. Χρησιμοποιώντας τις πανίσχυρες βιβλιοθήκες [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Αυτοματισμού μορφοποίησης αρχείων, μπορείτε να αναπτύξετε εφαρμογές χειρισμού msg και μετατροπής. Μπορείτε να μετατρέψετε MSG σε MD με το συνδυασμό των [Aspose.Msg για Android Java](https://products.aspose.com/msg/android-java/) & [Aspose.Words για Andorid Java](https://products.aspose.com/words/android-java/). Χρησιμοποιώντας το πρώτο API μπορείτε να μετατρέψετε τη μορφή αρχείου MSG σε HTML και χρησιμοποιώντας το δεύτερο API, μπορείτε να αποδώσετε το HTML ως MD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή MSG σε MD στο Andorid" %}}
1. Ανοίξτε το αρχείο MSG χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Μετατρέψτε το MSG σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) μέθοδος
3. Φορτώστε HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή MD χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το MD ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://releases.aspose.com/total/java/) και εγκαταστήστε το [Aspose.Msg για Android μέσω Java](https://docs.aspose.com/msg/androidjava/installation/) και το [Aspose.Words for Andorid μέσω Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.MD
document.save("output.md", SaveFormat.MD); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}