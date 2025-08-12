---
title: Μετατροπή CGM σε PPSM μέσω Java API
description: Java API για μετατροπή CGM σε PPSM χωρίς χρήση του Microsoft Word
url_ignore: /el/java/conversion/cgm-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPSM
otherformats: OTP PPSM PPS SWF PPSX POTX POT PPT XAML PPTM POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή CGM σε PPSM" h2="Εξαγωγή CGM σε PPSM μέσω API Java χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε εύκολα να μετατρέψετε το CGM σε PPSM σε οποιαδήποτε εφαρμογή Java J2SE, J2EE, J2ME. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το CGM σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, μπορείτε να μετατρέψετε το PPTX σε PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή CGM σε PPSM" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το CGM σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPSM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Ppsm` ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και περιλαμβάνουν τα [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/) και [Aspose.Slides για Java](https://docs.aspose.com/slides/java/installation/) στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Κατά τη φόρτωση της μορφής αρχείου CGM, το έγγραφό σας ενδέχεται να προστατεύεται με κωδικό πρόσβασης. Το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/) σάς επιτρέπει επίσης να ανοίγετε κρυπτογραφημένα έγγραφα. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε νέα παρουσία του [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) κλάση και περάστε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το κρυπτογραφημένο αρχείο CGM μέσω Java" %}}
Μετά τη μετατροπή του CGM σε PPSM, μπορείτε επίσης να προσθέσετε προκαθορισμένο τύπο προβολής για την παρουσίασή σας. Το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) παρέχει τη δυνατότητα να ορίσετε τον τύπο προβολής για την παρουσίαση που δημιουργείται όταν ανοίγει στο PowerPoint μέσω των [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Η ιδιότητα [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) χρησιμοποιείται για τον ορισμό του τύπου προβολής χρησιμοποιώντας το [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) απαριθμητής. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
<h2>✅ Κύριες Χρήσεις</h2>
- **Δυναμικά Οπτικά Πίνακες Ελέγχου** – Ενημέρωση σε πραγματικό χρόνο των διαγραμμάτων κατά τη διάρκεια των παρουσιάσεων.
- **Τεχνικές Παρουσιάσεις με Ενσωματωμένα Macros** – Δυνατότητα διαδραστικής εξερεύνησης δεδομένων.
- **Αυτοματοποιημένες Εμφανίσεις Προσομοιώσεων** – Παρουσίαση ζωντανών εξόδων προσομοίωσης χωρίς χειροκίνητη ρύθμιση.

<h2>⚙️ Σενάρια Αυτοματισμού</h2>
- **Μηχανές Αποτύπωσης Μακροενεργοποιημένων PowerPoint βασισμένες σε Java** – Δημιουργία και παράδοση παρουσιάσεων με Macros.
- **Διαδραστικές Τεχνικές Ενημερώσεις** – Ενσωμάτωση διαγραμμάτων και υπολογισμών που δημιουργήθηκαν με Java.
- **Έξυπνες Ροές Παρουσιάσεων** – Σύνδεση πολλαπλών αρχείων PPSM σε ένα σύστημα καθοδηγούμενης παρουσίασης.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}