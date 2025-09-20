---
title: Μετατροπή EPUB σε PPT μέσω Java API
description: Java API για μετατροπή EPUB σε PPT χωρίς χρήση του Microsoft Word
url_ignore: /el/java/conversion/epub-to-ppt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPT
otherformats: POWERPOINT PPT PPS PPTM XAML SWF POT OTP POTX PPSX POTM PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή EPUB σε PPT" h2="Εξαγωγή EPUB σε PPT μέσω API Java χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε εύκολα να μετατρέψετε το EPUB σε PPT σε οποιαδήποτε εφαρμογή Java J2SE, J2EE, J2ME. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το EPUB σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, μπορείτε να μετατρέψετε το PPTX σε PPT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή EPUB σε PPT" %}}
1. Ανοίξτε το αρχείο EPUB χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το EPUB σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Ppt` ως SaveFormat
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
Μετά τη μετατροπή του EPUB σε PPT, μπορείτε επίσης να προσθέσετε προκαθορισμένο τύπο προβολής για την παρουσίασή σας. Το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) παρέχει τη δυνατότητα να ορίσετε τον τύπο προβολής για την παρουσίαση που δημιουργείται όταν ανοίγει στο PowerPoint μέσω των [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Η ιδιότητα [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) χρησιμοποιείται για τον ορισμό του τύπου προβολής χρησιμοποιώντας το [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) απαριθμητής. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Η μετατροπή **EPUB σε PPT (Παρουσίαση PowerPoint)** είναι ουσιώδης για τη δημιουργία **επεξεργάσιμων αρχείων παρουσίασης** από ψηφιακές δημοσιεύσεις. Τα αρχεία PPT επιτρέπουν στο περιεχόμενο του eBook να μετατραπεί σε πλήρως προσαρμόσιμες διαφάνειες, επιτρέποντας σε εκπαιδευτικούς, ερευνητές και επιχειρήσεις να δημιουργήσουν επαγγελματικές παρουσιάσεις αποτελεσματικά. Με τη μετατροπή του EPUB σε PPT, οι οργανισμοί μπορούν να βελτιστοποιήσουν τη δημιουργία διαφανειών, να διατηρήσουν τη συνοχή του περιεχομένου και να βελτιώσουν τις ροές κοινοποίησης γνώσεων.

{{% blocks/products/pf/agp/feature-section-col title="Βασικές Περιπτώσεις Χρήσης" %}}
- **Ακαδημαϊκές διαφάνειες** – Μετατρέψτε κεφάλαια εγχειριδίων σε δομημένες, επεξεργάσιμες διαλέξεις.
- **Εταιρικές παρουσιάσεις** – Δημιουργήστε επιχειρηματικές παρουσιάσεις από εκδόσεις και αναφορές του κλάδου.
- **Παρουσιάσεις έρευνας** – Δημιουργήστε επαγγελματικές διαφάνειες για συνέδρια και σεμινάρια.
- **Υλικό εκδοτικού οίκου** – Αναδιαμορφώστε το περιεχόμενο eBook για μάρκετινγκ και προωθητικές παρουσιάσεις.
- **Εκπαιδευτικές συνεδρίες εκπαίδευσης** – Αναπτύξτε εκπαιδευτικές διαφάνειες για εργαστήρια και προγράμματα ηλεκτρονικής μάθησης.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Σενάρια Αυτοματισμού" %}}
- **Αγωγοί EPUB προς PPT** – Αυτοματοποιήστε τη μετατροπή των eBook σε διαφάνειες PowerPoint.
- **Αυτόματη δημιουργία συλλογής διαφανειών** – Δημιουργήστε γρήγορα παρουσιάσεις έτοιμες για επεξεργασία από πολλαπλές εκδόσεις.
- **Μαζική μετατροπή εκδόσεων σε PPT** – Μετατρέψτε αποτελεσματικά μεγάλες συλλογές eBook σε σύνολα διαφανειών.
- **Αυτοματισμός παρουσιάσεων επιχείρησης** – Ενσωματώστε τη δημιουργία PPT στις ροές κοινοποίησης γνώσεων και εκπαίδευσης του οργανισμού.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}