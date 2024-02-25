---
title: Εξαγωγή MSG σε WORD μέσω Java
description: Java API για μετατροπή MSG σε WORD χωρίς χρήση του Microsoft Word ή του Outlook
url_ignore: /el/java/conversion/msg-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD
otherformats: WORD XPS TIFF DOTX MD PNG DOCX DOC PDF EPUB GIF TEXT PS RTF DOTM JPEG DOCM PCL EMF OTT WORDML DOT ODT SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για απόδοση MSG σε WORD" h2="Εξαγωγή MSG σε WORD χρησιμοποιώντας το API Java χωρίς χρήση εξαρτήσεων τρίτων" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή msg είναι μια ισχυρή δυνατότητα που οι προγραμματιστές Java μπορούν να ενσωματώσουν σε οποιεσδήποτε εφαρμογές Java J2SE, J2EE, J2ME μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/). Χρησιμοποιώντας δύο API μέσα στο πακέτο, μπορείτε να μετατρέψετε MSG Msg σε WORD χωρίς εξαρτήσεις τρίτων. Πρώτον, μπορείτε να χρησιμοποιήσετε το Msg Manipulation API [Aspose.Email για Java](https://products.aspose.com/email/java/) για να μετατρέψετε τη μορφή αρχείου MSG σε HTML. Δεύτερον, μπορείτε να αποδώσετε την HTML σε WORD χρησιμοποιώντας το API Επεξεργασίας Εγγράφων [Aspose.Words για Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το MSG σε WORD" %}}
1. Ανοίξτε το αρχείο MSG χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Μετατρέψτε το MSG σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) μέθοδος
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή WORD χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το WORD ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Πρέπει να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCX
document.save("output.docx", SaveFormat.DOCX);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}