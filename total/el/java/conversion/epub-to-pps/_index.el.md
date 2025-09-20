---
title: Μετατροπή EPUB σε PPS μέσω Java API
description: Java API για μετατροπή EPUB σε PPS χωρίς χρήση του Microsoft Word
url_ignore: /el/java/conversion/epub-to-pps/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPS POTX POTM POT PPSX XAML PPTM PPSM SWF OTP PPT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή EPUB σε PPS" h2="Εξαγωγή EPUB σε PPS μέσω API Java χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε εύκολα να μετατρέψετε το EPUB σε PPS σε οποιαδήποτε εφαρμογή Java J2SE, J2EE, J2ME. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το EPUB σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, μπορείτε να μετατρέψετε το PPTX σε PPS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή EPUB σε PPS" %}}
1. Ανοίξτε το αρχείο EPUB χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το EPUB σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPS χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Pps` ως SaveFormat
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
Μετά τη μετατροπή του EPUB σε PPS, μπορείτε επίσης να προσθέσετε προκαθορισμένο τύπο προβολής για την παρουσίασή σας. Το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) παρέχει τη δυνατότητα να ορίσετε τον τύπο προβολής για την παρουσίαση που δημιουργείται όταν ανοίγει στο PowerPoint μέσω των [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Η ιδιότητα [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) χρησιμοποιείται για τον ορισμό του τύπου προβολής χρησιμοποιώντας το [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) απαριθμητής. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Η μετατροπή **EPUB σε PPS (PowerPoint Show)** είναι ουσιώδης για τη δημιουργία **έτοιμων παρουσιάσεων** από ψηφιακές δημοσιεύσεις. Τα αρχεία PPS επιτρέπουν στις παρουσιάσεις να ξεκινήσουν αμέσως σε λειτουργία παρουσίασης, κάνοντάς τα ιδανικά για συνέδρια, εκπαίδευση και μάρκετινγκ. Μετατρέποντας το EPUB σε PPS, εκπαιδευτικοί, εκδότες και επιχειρήσεις μπορούν να παρέχουν πολιτισμένες, προσβάσιμες παρουσιάσεις χωρίς χειροκίνητη επεξεργασία, βελτιώντας την επικοινωνία και την κοινοποίηση περιεχομένου.

{{% blocks/products/pf/agp/feature-section-col title="Βασικές Χρήσεις" %}}
- **Διαφάνειες συνεδρίων** – Δημιουργία πολιτισμένων παρουσιάσεων για επαγγελματικά γεγονότα.
- **Συνεδρίες εκπαίδευσης** – Παράδοση εκπαιδευτικών διαφανειών έτοιμων για άμεση αναπαραγωγή.
- **Προεπισκοπήσεις εκδοτικών εταιρειών** – Παρουσίαση περιεχομένου βιβλίου σε διαδραστική μορφή παρουσίασης.
- **Αναπαραγωγή ακαδημαϊκών διαλέξεων** – Παροχή διαφανειών διαλέξεων για ομαλή εμφάνιση στην τάξη.
- **Επιχειρηματικές παρουσιάσεις** – Παρουσίαση πληροφοριών προϊόντων ή υπηρεσιών σε προπαρασκευασμένες παρουσιάσεις διαφανειών.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Σενάρια Αυτοματισμού" %}}
- **Σωλήνες EPUB προς PPS** – Αυτοματοποιήστε τη μετατροπή των ηλεκτρονικών βιβλίων σε έτοιμες παρουσιάσεις.
- **Αυτόματη δημιουργία παρουσιάσεων** – Γρήγορη δημιουργία αρχείων PPS από πολλαπλές ψηφιακές δημοσιεύσεις.
- **Δημιουργία παρουσιάσεων με βάση τα μεταδεδομένα** – Πληρώστε παρουσιάσεις χρησιμοποιώντας δομημένα δεδομένα eBook.
- **Αυτοματισμός δημοσίευσης σε επίπεδο επιχείρησης** – Ενσωματώστε τη δημιουργία PPS στις ροές μεγάλης κλίμακας παρουσιάσεων.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}