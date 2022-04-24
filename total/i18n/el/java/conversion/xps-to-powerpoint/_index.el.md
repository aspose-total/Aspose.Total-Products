---
title: Μετατροπή XPS σε POWERPOINT μέσω Java API
description: Java API για μετατροπή XPS σε POWERPOINT χωρίς χρήση του Microsoft Word
url: /el/java/conversion/xps-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: PPT
otherformats: PPSX POTM POT OTP SWF XAML PPT POTX PPSM PPTM PPS POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή XPS σε POWERPOINT" h2="Εξαγωγή XPS σε POWERPOINT μέσω API Java χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε εύκολα να μετατρέψετε το XPS σε POWERPOINT σε οποιαδήποτε εφαρμογή Java J2SE, J2EE, J2ME. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το XPS σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, μπορείτε να μετατρέψετε το PPTX σε POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή XPS σε POWERPOINT" %}}
1. Ανοίξτε το αρχείο XPS χρησιμοποιώντας την κλάση [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το XPS σε PPTX χρησιμοποιώντας τη μέθοδο [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή POWERPOINT χρησιμοποιώντας τη μέθοδο [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) και ορίστε « Powerpoint` ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και περιλαμβάνουν τα [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/) και [Aspose.Slides για Java](https://docs.aspose.com/slides/java/ install/) στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Κατά τη φόρτωση της μορφής αρχείου XPS, το έγγραφό σας ενδέχεται να προστατεύεται με κωδικό πρόσβασης. Το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/) σάς επιτρέπει επίσης να ανοίγετε κρυπτογραφημένα έγγραφα. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε νέα παρουσία του [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) κλάση και περάστε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το κρυπτογραφημένο αρχείο XPS μέσω Java" %}}
Μετά τη μετατροπή του XPS σε POWERPOINT, μπορείτε επίσης να προσθέσετε προκαθορισμένο τύπο προβολής για την παρουσίασή σας. Το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) παρέχει τη δυνατότητα να ορίσετε τον τύπο προβολής για την παρουσίαση που δημιουργείται όταν ανοίγει στο PowerPoint μέσω των [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Η ιδιότητα [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) χρησιμοποιείται για τον ορισμό του τύπου προβολής χρησιμοποιώντας το [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) απαριθμητής. 
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-pps/" name="XPS Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-swf/" name="XPS Προς την SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-potx/" name="XPS Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-ppsx/" name="XPS Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-potm/" name="XPS Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-ppt/" name="XPS Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-ppsm/" name="XPS Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-xaml/" name="XPS Προς την XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-otp/" name="XPS Προς την OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-pptm/" name="XPS Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-pot/" name="XPS Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-powerpoint/" name="XPS Προς την POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}