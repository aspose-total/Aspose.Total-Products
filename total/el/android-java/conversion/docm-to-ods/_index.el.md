---
title: Android API για μετατροπή DOCM σε ODS
description: Μετατροπή DOCM σε ODS στο Android μέσω Java χωρίς χρήση του Microsoft Word ή του Microsoft Excel
url: /el/android-java/conversion/docm-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: ODS
otherformats: SXC CSV XLTX XLAM XLS FODS DIF XLT XLSM TSV EXCEL XLSB XLTM XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή DOCM σε ODS στις Εφαρμογές Android" h2="Εξαγωγή DOCM σε ODS στο Android μέσω Java χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/) μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής DOCM σε ODS στις εφαρμογές σας Android. Πρώτον, μπορείτε να μετατρέψετε το DOCM σε HTML χρησιμοποιώντας πλούσιο σε χαρακτηριστικά, API χειρισμού εγγράφων και μετατροπής [Aspose.Words για Android μέσω Java](https://products.aspose.com/words/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/android-java/), μπορείτε να μετατρέψετε HTML σε ODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για μετατροπή DOCM σε ODS" %}}
1. Ανοίξτε το αρχείο DOCM χρησιμοποιώντας την κλάση [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument)
2. Μετατρέψτε το DOCM σε HTML χρησιμοποιώντας το [Save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions) ) μέθοδος
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή ODS χρησιμοποιώντας το [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.Cells για Android μέσω Java](https://docms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) και [Aspose.Words για Android μέσω Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Καταργήστε τις αχρησιμοποίητες πληροφορίες από ένα έγγραφο DOCM στο Android μέσω Java" %}}
Πριν μετατρέψετε το DOCM σε ODS, μπορείτε να αφαιρέσετε αχρησιμοποίητες πληροφορίες από το έγγραφο DOCM μέσω του [Aspose.Words για Android μέσω Java](https://products.aspose.com/words/android-java/). Μερικές φορές μπορεί να χρειαστεί να αφαιρέσετε αχρησιμοποίητες ή διπλότυπες πληροφορίες για να μειώσετε το μέγεθος του εγγράφου εξόδου και τον χρόνο επεξεργασίας. Η κλάση [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) σάς επιτρέπει να καθορίσετε επιλογές για τον καθαρισμό εγγράφων. Για να αφαιρέσετε διπλότυπα στυλ ή απλώς αχρησιμοποίητα στυλ ή λίστες από το έγγραφο, μπορείτε να χρησιμοποιήσετε τη μέθοδο [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Docmument#cleanup()). Μπορείτε να χρησιμοποιήσετε τα [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) και [UnusedBuiltinStyles](https://reference.aspose.com/words/java) για τον εντοπισμό και την αφαίρεση στυλ που επισημαίνονται ως "αχρησιμοποίητα".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε το αρχείο ODS στη ροή στο Android μέσω Java" %}}
Μετά τη μετατροπή του DOCM σε ODS, το [Aspose.Cells για Android μέσω Java](https://products.aspose.com/cells/android-java/) σάς δίνει τη δυνατότητα να αποθηκεύσετε το έγγραφό σας σε ροή. Εάν χρειάζεται να αποθηκεύσετε αρχεία σε μια ροή, τότε θα πρέπει να δημιουργήσετε ένα αντικείμενο FileOutputStream και, στη συνέχεια, [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) το αρχείο σε αυτό το αντικείμενο Stream καλώντας τη μέθοδο αποθήκευσης του [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) αντικείμενο.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-sxc/" name="DOCM Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-ods/" name="DOCM Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xltx/" name="DOCM Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xlam/" name="DOCM Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xls/" name="DOCM Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-fods/" name="DOCM Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-dif/" name="DOCM Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xlt/" name="DOCM Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xlsm/" name="DOCM Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-tsv/" name="DOCM Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-excel/" name="DOCM Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xlsb/" name="DOCM Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xltm/" name="DOCM Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/docm-to-xlsx/" name="DOCM Προς την XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}