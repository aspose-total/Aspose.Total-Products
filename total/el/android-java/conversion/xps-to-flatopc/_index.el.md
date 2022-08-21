---
title: Android API για απόδοση XPS σε FLATOPC
description: Μετατρέψτε το XPS σε FLATOPC μέσω Android μέσω Java API
url: /el/android-java/conversion/xps-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: FLAT_OPC
otherformats: PS DOTM DOT WORDML DOTX RTF MARKDOWN OTT ODT PCL XAMLFLOW DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το XPS σε FLATOPC στο Android μέσω Java" h2="Μετατρέψτε το XPS σε FLATOPC σε εφαρμογές για κινητά χωρίς εγκατάσταση λογισμικού" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής XPS σε FLATOPC στις εφαρμογές σας για κινητά χρησιμοποιώντας δύο API του πακέτου [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Πρώτα πρέπει να μετατρέψετε το αρχείο XPS σε DOC χρησιμοποιώντας το [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Δεύτερον, χρησιμοποιώντας το API επεξεργασίας κειμένου [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), μπορείτε να αποδώσετε το DOC σε FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή XPS σε FLATOPC στο Android μέσω Java" %}}
1. Ανοίξτε το αρχείο XPS χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το XPS σε DOC χρησιμοποιώντας [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) μέθοδος
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή FLATOPC χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) και ορίστε το FLATOPC ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) και [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λάβετε πληροφορίες για το αρχείο XPS στο Android μέσω Java" %}}
Προτού μετατρέψετε το XPS σε FLATOPC, μπορεί να χρειαστείτε πληροφορίες σχετικά με το έγγραφο, όπως ο συγγραφέας, η ημερομηνία δημιουργίας, οι λέξεις-κλειδιά, η ημερομηνία τροποποίησης, το θέμα και ο τίτλος. Αυτές οι πληροφορίες είναι χρήσιμες για τη λήψη αποφάσεων για τη διαδικασία μετατροπής. Χρησιμοποιώντας το ισχυρό [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, μπορείτε να τα αποκτήσετε όλα. Για να λάβετε πληροφορίες για συγκεκριμένο αρχείο σχετικά με ένα αρχείο XPS, λάβετε πρώτα το αντικείμενο [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) χρησιμοποιώντας το [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Μόλις ανακτηθεί το αντικείμενο DocumentInfo, μπορείτε να λάβετε τις τιμές των μεμονωμένων ιδιοτήτων.
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Εισαγάγετε σημειώσεις τέλους στο έγγραφο FLATOPC στο Android μέσω Java" %}}
Εκτός από τη μετατροπή εγγράφων, μπορείτε επίσης να προσθέσετε μια δέσμη άλλων λειτουργιών στις Εφαρμογές σας Android χρησιμοποιώντας το [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Ένα από αυτά τα χαρακτηριστικά είναι η εισαγωγή σημειώσεων τέλους και η αρίθμηση στο έγγραφο FLATOPC. Εάν θέλετε να εισαγάγετε μια υποσημείωση ή μια σημείωση τέλους σε ένα έγγραφο FLATOPC, χρησιμοποιήστε τη μέθοδο DocumentBuilder.InsertFootnote. Αυτή η μέθοδος εισάγει μια υποσημείωση ή μια σημείωση τέλους στο έγγραφο. Οι κλάσεις EndnoteOptions και FootnoteOptions αντιπροσωπεύουν επιλογές αρίθμησης για υποσημείωση και σημείωση τέλους.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.flat_opc", SaveFormat.FLAT_OPC);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-ps/" name="XPS Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-dotm/" name="XPS Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-dot/" name="XPS Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-wordml/" name="XPS Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-dotx/" name="XPS Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-rtf/" name="XPS Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-markdown/" name="XPS Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-ott/" name="XPS Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-odt/" name="XPS Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-pcl/" name="XPS Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-xamlflow/" name="XPS Προς την XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-flatopc/" name="XPS Προς την FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}