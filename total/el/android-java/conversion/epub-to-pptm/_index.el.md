---
title: Εξαγωγή EPUB σε PPTM στο Android
description: Android API για μετατροπή EPUB σε PPTM χωρίς χρήση του Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPTM
otherformats: PPT OTP PPS POTX POTM PPSX PPSM POWERPOINT SWF POT XAML ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή EPUB σε PPTM στο Android μέσω Java" h2="Μετατρέψτε το EPUB σε PPTM στις Εφαρμογές σας Android χωρίς τη χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής EPUB σε PPTM στις εφαρμογές σας Android, χρησιμοποιώντας δύο απλά βήματα. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το EPUB σε PPTX χρησιμοποιώντας το [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), μπορείτε να μετατρέψετε το PPTX σε PPTM. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για εξαγωγή EPUB σε PPTM" %}}
1. Ανοίξτε το αρχείο EPUB χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το EPUB σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κατηγορία [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPTM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Pptm` ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://releases.aspose.com/total/java/) και εγκαταστήστε το [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) και [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το αρχείο EPUB που προστατεύεται με κωδικό πρόσβασης στο Android μέσω Java" %}}
Κατά τη φόρτωση της μορφής αρχείου EPUB, το έγγραφό σας ενδέχεται να προστατεύεται με κωδικό πρόσβασης. Το [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) σάς επιτρέπει επίσης να ανοίγετε κρυπτογραφημένα έγγραφα. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε νέα παρουσία του [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) κλάση και περάστε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργήστε μικρογραφία του αρχείου PPTM σε εφαρμογές Android" %}}
Μετά τη μετατροπή του EPUB σε PPTM, μπορείτε επίσης να δημιουργήσετε μικρογραφίες του εγγράφου εξόδου σας. Χρησιμοποιώντας το πλούσιο σε χαρακτηριστικό [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) μπορείτε να δημιουργήσετε μικρογραφίες των διαφανειών δημιουργώντας και παρουσίαση του [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) τάξη. Μετά από αυτό, μπορείτε να λάβετε την αναφορά οποιασδήποτε επιθυμητής διαφάνειας χρησιμοποιώντας το αναγνωριστικό ή το ευρετήριό της και να λάβετε τη μικρογραφία της αναφερόμενης διαφάνειας σε μια καθορισμένη κλίμακα.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("output.pptm");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}