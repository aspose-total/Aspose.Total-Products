---
title: Μετατροπή EPUB σε ODP μέσω Java API
description: Java API για μετατροπή EPUB σε ODP χωρίς χρήση του Microsoft Word
url_ignore: /el/java/conversion/epub-to-odp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODP
otherformats: POTM PPTM PPSM PPT SWF POT POWERPOINT PPSX XAML OTP PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή EPUB σε ODP" h2="Εξαγωγή EPUB σε ODP μέσω API Java χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε εύκολα να μετατρέψετε το EPUB σε ODP σε οποιαδήποτε εφαρμογή Java J2SE, J2EE, J2ME. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το EPUB σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, μπορείτε να μετατρέψετε το PPTX σε ODP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή EPUB σε ODP" %}}
1. Ανοίξτε το αρχείο EPUB χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το EPUB σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή ODP χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Odp` ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και περιλαμβάνουν τα [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/) και [Aspose.Slides για Java](https://docs.aspose.com/slides/java/installation/) στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Κατά τη φόρτωση της μορφής αρχείου EPUB, το έγγραφό σας ενδέχεται να προστατεύεται με κωδικό πρόσβασης. Το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/) σάς επιτρέπει επίσης να ανοίγετε κρυπτογραφημένα έγγραφα. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε νέα παρουσία του [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) κλάση και περάστε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το κρυπτογραφημένο αρχείο EPUB μέσω Java" %}}
Μετά τη μετατροπή του EPUB σε ODP, μπορείτε επίσης να προσθέσετε προκαθορισμένο τύπο προβολής για την παρουσίασή σας. Το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) παρέχει τη δυνατότητα να ορίσετε τον τύπο προβολής για την παρουσίαση που δημιουργείται όταν ανοίγει στο PowerPoint μέσω των [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Η ιδιότητα [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) χρησιμοποιείται για τον ορισμό του τύπου προβολής χρησιμοποιώντας το [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) απαριθμητής. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Η μετατροπή **EPUB σε ODP (Παρουσίαση Έγγραφου Άνοιγμα)** είναι ουσιώδης για τη δημιουργία **διαφανειών παρουσίασης** από ψηφιακές δημοσιεύσεις. Τα αρχεία ODP παρέχουν ένα ευέλικτο, ανοιχτό πρότυπο μορφής για τη δημιουργία ενδιαφέροντων συλλογών διαφανειών από περιεχόμενο eBook. Με τη μετατροπή του EPUB σε ODP, οι εκπαιδευτικοί, οι επιχειρήσεις και οι εκδότες μπορούν να επαναχρησιμοποιήσουν το ψηφιακό περιεχόμενο για διαλέξεις, συναντήσεις, εκπαιδευτικά σεμινάρια και παρουσιάσεις μάρκετινγκ αποτελεσματικά.

{{% blocks/products/pf/agp/feature-section-col title="Βασικές Χρήσεις" %}}
- **Διαφάνειες εκπαιδευτικών διαλέξεων** – Μετατροπή κεφαλαίων eBook σε δομημένες παρουσιάσεις αίθουσας διδασκαλίας.
- **Δέσμες επαγγελματικών παρουσιάσεων επιχειρήσεων** – Δημιουργία επαγγελματικών διαφανειών από εταιρικές ή βιομηχανικές δημοσιεύσεις.
- **Περιλήψεις ερευνητικών εργασιών** – Περίληψη ακαδημαϊκού περιεχομένου σε οπτικά ελκυστικές διαφάνειες.
- **Διαφάνειες μάρκετινγκ εκδοτικού οίκου** – Δημιουργία προωθητικών παρουσιάσεων από περιεχόμενο βιβλίου.
- **Διανομή υλικού εκπαίδευσης** – Συσκευασία περιεχομένου μάθησης σε έτοιμες προς χρήση διαφάνειες για εργαστήρια.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Σενάρια Αυτοματοποίησης" %}}
- **Σωλήνες μετατροπής EPUB σε ODP** – Αυτοματοποίηση μετατροπής ψηφιακών δημοσιεύσεων σε συλλογές διαφανειών.
- **Αυτόματη δημιουργία παρουσιάσεων** – Γρήγορη παραγωγή αρχείων ODP από περιεχόμενο eBook.
- **Μαζικές μετατροπές eBook σε διαφάνειες** – Επεξεργασία πολλαπλών δημοσιεύσεων σε παρουσιάσεις μεγάλης κλίμακας.
- **Ροές εργασίας κοινοποίησης γνώσης επιχείρησης** – Βελτιστοποίηση διανομής εκπαιδευτικού και εκπαιδευτικού υλικού.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}