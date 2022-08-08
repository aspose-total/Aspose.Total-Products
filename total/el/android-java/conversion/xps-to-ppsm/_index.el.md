---
title: Εξαγωγή XPS σε PPSM στο Android
description: Android API για μετατροπή XPS σε PPSM χωρίς χρήση του Microsoft Word
url: /el/android-java/conversion/xps-to-ppsm/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPSM
otherformats: POT SWF POTX OTP POTM PPTM POWERPOINT PPS ODP XAML PPT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή XPS σε PPSM στο Android μέσω Java" h2="Μετατρέψτε το XPS σε PPSM στις Εφαρμογές σας Android χωρίς τη χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής XPS σε PPSM στις εφαρμογές σας Android, χρησιμοποιώντας δύο απλά βήματα. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το XPS σε PPTX χρησιμοποιώντας το [Aspose.PDF για Android μέσω Java](https://products.aspose.com/pdf/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides για Android μέσω Java](https://products.aspose.com/slides/android-java/), μπορείτε να μετατρέψετε το PPTX σε PPSM. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για εξαγωγή XPS σε PPSM" %}}
1. Ανοίξτε το αρχείο XPS χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το XPS σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κατηγορία [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPSM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Ppsm` ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.PDF για Android μέσω Java](https://docs.aspose.com/pdf/androidjava/installation/) και [Aspose.Slides για Android μέσω Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το αρχείο XPS που προστατεύεται με κωδικό πρόσβασης στο Android μέσω Java" %}}
Κατά τη φόρτωση της μορφής αρχείου XPS, το έγγραφό σας ενδέχεται να προστατεύεται με κωδικό πρόσβασης. Το [Aspose.PDF για Android μέσω Java](https://products.aspose.com/pdf/android-java/) σάς επιτρέπει επίσης να ανοίγετε κρυπτογραφημένα έγγραφα. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε νέα παρουσία του [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) κλάση και περάστε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργήστε μικρογραφία του αρχείου PPSM σε εφαρμογές Android" %}}
Μετά τη μετατροπή του XPS σε PPSM, μπορείτε επίσης να δημιουργήσετε μικρογραφίες του εγγράφου εξόδου σας. Χρησιμοποιώντας το πλούσιο σε χαρακτηριστικό [Aspose.Slides για Android μέσω Java](https://products.aspose.com/slides/android-java/) μπορείτε να δημιουργήσετε μικρογραφίες των διαφανειών δημιουργώντας και παρουσίαση του [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) τάξη. Μετά από αυτό, μπορείτε να λάβετε την αναφορά οποιασδήποτε επιθυμητής διαφάνειας χρησιμοποιώντας το αναγνωριστικό ή το ευρετήριό της και να λάβετε τη μικρογραφία της αναφερόμενης διαφάνειας σε μια καθορισμένη κλίμακα.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("output.ppsm");
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
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-pot/" name="XPS Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-swf/" name="XPS Προς την SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-potx/" name="XPS Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-otp/" name="XPS Προς την OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-potm/" name="XPS Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-pptm/" name="XPS Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-powerpoint/" name="XPS Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-pps/" name="XPS Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-ppsm/" name="XPS Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-xaml/" name="XPS Προς την XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-ppt/" name="XPS Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xps-to-ppsx/" name="XPS Προς την PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}