---
title: Εξαγωγή EML σε DOC μέσω Java
description: Java API για μετατροπή EML σε DOC χωρίς χρήση του Microsoft Word ή του Outlook
url_ignore: /el/java/conversion/eml-to-doc/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOC
otherformats: MD PCL PS JPEG TIFF RTF DOTX PNG DOC DOCM DOCX EPUB DOT WORDML EMF DOTM TEXT FLATOPC OTT SVG XPS GIF ODT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για απόδοση EML σε DOC" h2="Εξαγωγή EML σε DOC χρησιμοποιώντας το API Java χωρίς χρήση εξαρτήσεων τρίτων" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή eml είναι μια ισχυρή δυνατότητα που οι προγραμματιστές Java μπορούν να ενσωματώσουν σε οποιεσδήποτε εφαρμογές Java J2SE, J2EE, J2ME μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/). Χρησιμοποιώντας δύο API μέσα στο πακέτο, μπορείτε να μετατρέψετε EML Eml σε DOC χωρίς εξαρτήσεις τρίτων. Πρώτον, μπορείτε να χρησιμοποιήσετε το Eml Manipulation API [Aspose.Email για Java](https://products.aspose.com/email/java/) για να μετατρέψετε τη μορφή αρχείου EML σε HTML. Δεύτερον, μπορείτε να αποδώσετε την HTML σε DOC χρησιμοποιώντας το API Επεξεργασίας Εγγράφων [Aspose.Words για Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το EML σε DOC" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) μέθοδος
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) και ορίστε το DOC ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Πρέπει να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOC
document.save("output.doc", SaveFormat.DOC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-png/" name="MSG Προς την PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-doc/" name="MSG Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-ott/" name="MSG Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-odt/" name="MSG Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-wordml/" name="MSG Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-dotx/" name="MSG Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-svg/" name="MSG Προς την SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-docx/" name="MSG Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-epub/" name="MSG Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-text/" name="MSG Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-xps/" name="MSG Προς την XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-ps/" name="MSG Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-flatopc/" name="MSG Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-docm/" name="MSG Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-jpeg/" name="MSG Προς την JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-tiff/" name="MSG Προς την TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-dot/" name="MSG Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-emf/" name="MSG Προς την EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-rtf/" name="MSG Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-gif/" name="MSG Προς την GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-pcl/" name="MSG Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-dotm/" name="MSG Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-md/" name="MSG Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/msg-to-pdf/" name="MSG Προς την PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}