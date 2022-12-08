---
title: Μετατροπή DOTX σε μορφή JSON στο Android μέσω Java
description: Αναλύστε τη μορφή DOTX σε JSON σε Android μέσω Java χωρίς χρήση Microsoft Word ή Excel

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή DOTX σε μορφή JSON στο Android μέσω Java" h2="Σχεδιάστε εφαρμογές Android για εξαγωγή DOTX σε JSON χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το DOTX σε μορφή JSON στις Εφαρμογές σας Android μέσω του [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Χρησιμοποιώντας το API χειρισμού εγγράφων και μετατροπής [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), μπορείτε να εξαγάγετε το DOTX σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), μπορείτε να μετατρέψετε HTML σε JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή DOTX σε μορφή JSON στο Android" %}}
1. Ανοίξτε το αρχείο DOTX χρησιμοποιώντας την κλάση [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
2. Μετατρέψτε το DOTX σε HTML χρησιμοποιώντας το [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) ) μέθοδος
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή JSON χρησιμοποιώντας το [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε βιβλιοθήκες στην εφαρμογή σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου DOTX σε μορφή JSON στο Android μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο DOTX εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή JSON χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions. Το ακόλουθο παράδειγμα κώδικα δείχνει πώς ανοίγει ένα κρυπτογραφημένο έγγραφο με κωδικό πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή DOTX σε JSON στο Range στο Android μέσω Java" %}}
Ενώ μετατρέπετε το DOTX σε JSON, μπορείτε επίσης να ορίσετε το εύρος στη μορφή εξόδου JSON. Για να ορίσετε το εύρος, μπορείτε να ανοίξετε το μετατρεπόμενο HTML χρησιμοποιώντας την κλάση Βιβλίο εργασίας, να δημιουργήσετε ένα εύρος δεδομένων προς εξαγωγή χρησιμοποιώντας τη μέθοδο Cells.createRange, να καλέσετε τη μέθοδο JsonUtility.exportRangeToJson με αναφορές Range & ExportRangeToJsonOptions και να γράψετε δεδομένα JSON συμβολοσειράς στο αρχείο μέσω Μέθοδος BufferedWriter.write.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-sxc/" name="DOTX Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xlsm/" name="DOTX Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xlsb/" name="DOTX Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-tsv/" name="DOTX Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xlam/" name="DOTX Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xlt/" name="DOTX Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-dif/" name="DOTX Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-excel/" name="DOTX Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xltx/" name="DOTX Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-csv/" name="DOTX Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xltm/" name="DOTX Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-fods/" name="DOTX Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-ods/" name="DOTX Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/dotx-to-xlsx/" name="DOTX Προς την XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}