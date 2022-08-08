---
title: Εξαγωγή PCL σε POT στο Android
description: Android API για μετατροπή PCL σε POT χωρίς χρήση του Microsoft Word
url: /el/android-java/conversion/pcl-to-pot/
family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: POT
otherformats: PPT XAML PPTM PPSX SWF POTM PPSM POWERPOINT PPS ODP POTX OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή PCL σε POT στο Android μέσω Java" h2="Μετατρέψτε το PCL σε POT στις Εφαρμογές σας Android χωρίς τη χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής PCL σε POT στις εφαρμογές σας Android, χρησιμοποιώντας δύο απλά βήματα. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το PCL σε PPTX χρησιμοποιώντας το [Aspose.PDF για Android μέσω Java](https://products.aspose.com/pdf/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides για Android μέσω Java](https://products.aspose.com/slides/android-java/), μπορείτε να μετατρέψετε το PPTX σε POT. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για εξαγωγή PCL σε POT" %}}
1. Ανοίξτε το αρχείο PCL χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το PCL σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κατηγορία [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή POT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Pot` ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.PDF για Android μέσω Java](https://docs.aspose.com/pdf/androidjava/installation/) και [Aspose.Slides για Android μέσω Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το αρχείο PCL που προστατεύεται με κωδικό πρόσβασης στο Android μέσω Java" %}}
Κατά τη φόρτωση της μορφής αρχείου PCL, το έγγραφό σας ενδέχεται να προστατεύεται με κωδικό πρόσβασης. Το [Aspose.PDF για Android μέσω Java](https://products.aspose.com/pdf/android-java/) σάς επιτρέπει επίσης να ανοίγετε κρυπτογραφημένα έγγραφα. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε νέα παρουσία του [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) κλάση και περάστε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργήστε μικρογραφία του αρχείου POT σε εφαρμογές Android" %}}
Μετά τη μετατροπή του PCL σε POT, μπορείτε επίσης να δημιουργήσετε μικρογραφίες του εγγράφου εξόδου σας. Χρησιμοποιώντας το πλούσιο σε χαρακτηριστικό [Aspose.Slides για Android μέσω Java](https://products.aspose.com/slides/android-java/) μπορείτε να δημιουργήσετε μικρογραφίες των διαφανειών δημιουργώντας και παρουσίαση του [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) τάξη. Μετά από αυτό, μπορείτε να λάβετε την αναφορά οποιασδήποτε επιθυμητής διαφάνειας χρησιμοποιώντας το αναγνωριστικό ή το ευρετήριό της και να λάβετε τη μικρογραφία της αναφερόμενης διαφάνειας σε μια καθορισμένη κλίμακα.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-ppt/" name="PCL Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-xaml/" name="PCL Προς την XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-pptm/" name="PCL Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-ppsx/" name="PCL Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-swf/" name="PCL Προς την SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-potm/" name="PCL Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-ppsm/" name="PCL Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-powerpoint/" name="PCL Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-pps/" name="PCL Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-pot/" name="PCL Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-potx/" name="PCL Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pcl-to-otp/" name="PCL Προς την OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}