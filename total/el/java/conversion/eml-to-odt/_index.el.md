---
title: Εξαγωγή EML σε ODT μέσω Java
description: Java API για μετατροπή EML σε ODT χωρίς χρήση του Microsoft Word ή του Outlook
url_ignore: /el/java/conversion/eml-to-odt/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: ODT
otherformats: DOT PS FLATOPC DOC DOTX DOCX PCL DOTM GIF PNG WORDML ODT RTF TEXT MD EMF PDF SVG XPS JPEG DOCM EPUB TIFF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για απόδοση EML σε ODT" h2="Εξαγωγή EML σε ODT χρησιμοποιώντας το API Java χωρίς χρήση εξαρτήσεων τρίτων" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή eml είναι μια ισχυρή δυνατότητα που οι προγραμματιστές Java μπορούν να ενσωματώσουν σε οποιεσδήποτε εφαρμογές Java J2SE, J2EE, J2ME μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/). Χρησιμοποιώντας δύο API μέσα στο πακέτο, μπορείτε να μετατρέψετε EML Eml σε ODT χωρίς εξαρτήσεις τρίτων. Πρώτον, μπορείτε να χρησιμοποιήσετε το Eml Manipulation API [Aspose.Email για Java](https://products.aspose.com/email/java/) για να μετατρέψετε τη μορφή αρχείου EML σε HTML. Δεύτερον, μπορείτε να αποδώσετε την HTML σε ODT χρησιμοποιώντας το API Επεξεργασίας Εγγράφων [Aspose.Words για Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το EML σε ODT" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) μέθοδος
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή ODT χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το ODT ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Πρέπει να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}