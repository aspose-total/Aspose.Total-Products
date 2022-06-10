---
title: Μετατροπή PPSX σε μορφή JSON μέσω Java
description: Μετατροπή PPSX σε μορφή JSON μέσω Java χωρίς χρήση Microsoft Excel ή PowerPoint
url_ignore: /el/java/conversion/ppsx-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PPSX σε μορφή JSON μέσω Java" h2="Σε Premise Java API για εξαγωγή PPSX σε JSON χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή του PPSX σε μορφή JSON μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/) είναι μια απλή διαδικασία δύο βημάτων. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το PPSX σε HTML χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Δεύτερον, χρησιμοποιώντας το [Aspose.Cells for Java](https://products.aspose.com/cells/java/), μπορείτε να μετατρέψετε HTML σε JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή PPSX σε μορφή JSON μέσω Java" %}}
1. Ανοίξτε το αρχείο PPSX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPSX σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. μέθοδος ISaveOptions-).
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή JSON χρησιμοποιώντας [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο PPSX εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή JSON χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου PPSX σε μορφή JSON μέσω Java" %}}
Ενώ μετατρέπετε το PPSX σε JSON, μπορείτε επίσης να ορίσετε το εύρος στη μορφή εξόδου JSON. Για να ορίσετε το εύρος, μπορείτε να ανοίξετε το μετατρεπόμενο HTML χρησιμοποιώντας την κλάση Βιβλίο εργασίας, να δημιουργήσετε ένα εύρος δεδομένων προς εξαγωγή χρησιμοποιώντας τη μέθοδο Cells.createRange, να καλέσετε τη μέθοδο JsonUtility.exportRangeToJson με αναφορές Range & ExportRangeToJsonOptions και να γράψετε δεδομένα JSON συμβολοσειράς στο αρχείο μέσω Μέθοδος BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-doc/" name="PPSX Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-docm/" name="PPSX Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-docx/" name="PPSX Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-dot/" name="PPSX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-dotm/" name="PPSX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-dotx/" name="PPSX Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-odt/" name="PPSX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-ott/" name="PPSX Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-rtf/" name="PPSX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-text/" name="PPSX Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-word/" name="PPSX Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ppsx-to-wordml/" name="PPSX Προς την WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}