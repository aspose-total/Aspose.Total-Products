---
title: Μετατροπή PPTM σε RTF μέσω Java
description: Java API για εξαγωγή PPTM σε RTF χωρίς χρήση Microsoft Word ή PowerPoint
url: /el/java/conversion/pptm-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: RTF
otherformats: DOTM RTFX TEXT WORD OTT DOTX WORDML DOT RTF RTFM ODT FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PPTM σε RTF μέσω Java" h2="On Premise Java API για μετατροπή PowerPoint PPTM σε RTF σε οποιαδήποτε εφαρμογή Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Οι βιβλιοθήκες αυτοματισμού μορφής αρχείου εξουσιοδοτούν τους προγραμματιστές Java να αυτοματοποιούν τη διαδικασία μετατροπής ομαδικής μετατροπής του PowerPoint PPTM σε Word RTF. Η μετατροπή του εγγράφου είναι μια διαδικασία δύο βημάτων και περιλαμβάνει τη χρήση δύο API. Θα χρησιμοποιήσουμε το [Aspose.Slides for Java](https://products.aspose.com/slides/java/) που είναι ένα PowerPoint API για χειρισμό και διαχείριση παρουσιάσεων για τη μετατροπή PPTM σε HTML. Στη συνέχεια, χρησιμοποιώντας το πλούσιο σε δυνατότητες API επεξεργασίας κειμένου [Aspose.Words για Java](https://products.aspose.com/words/java/) θα μετατρέψουμε το HTML σε RTF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το PPTM σε RTF μέσω Java" %}}
1. Ανοίξτε το αρχείο PPTM χρησιμοποιώντας την τάξη [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPTM σε HTML χρησιμοποιώντας το [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. μέθοδο ISaveOptions-) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την κλάση [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument)
4. Αποθηκεύστε το έγγραφο σε μορφή RTF χρησιμοποιώντας τη μέθοδο [save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για μετατροπή αρχείου PPTM σε RTF, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose έργο που βασίζεται στο /aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να πραγματοποιήσετε μετατροπή αρχείου PPTM σε RTF με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας RTF, μπορείτε πρώτα να μετατρέψετε το αρχείο PPTM σε HTML και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το νέο αρχείο HTML χρησιμοποιώντας την κλάση [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument), δημιουργήστε μια παρουσία του TextWatermarkOptions και ορίστε Οι ιδιότητές του, Καλέστε τη μέθοδο Watermark.setText και περάστε κείμενο υδατογραφήματος & αντικείμενο του TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-word/" name="PPTM Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dotx/" name="PPTM Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-odt/" name="PPTM Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-ott/" name="PPTM Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-rtf/" name="PPTM Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-flatopc/" name="PPTM Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-wordml/" name="PPTM Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-rtfm/" name="PPTM Προς την RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-text/" name="PPTM Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-rtfx/" name="PPTM Προς την RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dotm/" name="PPTM Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dot/" name="PPTM Προς την DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}