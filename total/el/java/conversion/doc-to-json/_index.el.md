---
title: Μετατροπή DOC σε μορφή JSON μέσω Java
description: Μετατροπή DOC σε μορφή JSON μέσω Java χωρίς χρήση του Microsoft Word ή του Microsoft Excel
url_ignore: /el/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή DOC σε μορφή JSON μέσω Java" h2="Στο Premise Java API για μετατροπή DOC σε JSON χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή DOC σε μορφή JSON μέσω [Aspose.Total for Java](https://products.aspose.com/total/java/) είναι μια απλή διαδικασία δύο βημάτων. Χρησιμοποιώντας το πλούσιο σε χαρακτηριστικά, το API χειρισμού εγγράφων και μετατροπής [Aspose.Words για Java](https://products.aspose.com/words/java/), μπορείτε να εξάγετε το DOC σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/), μπορείτε να μετατρέψετε HTML σε JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή DOC σε μορφή JSON μέσω Java" %}}
1. Ανοίξτε το αρχείο DOC χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Μετατρέψτε το DOC σε HTML χρησιμοποιώντας το [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) μέθοδος
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή JSON χρησιμοποιώντας το [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο DOC εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή JSON χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions. Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να προσπαθήσετε να ανοίξετε ένα κρυπτογραφημένο έγγραφο με κωδικό πρόσβασης:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου DOC σε μορφή JSON μέσω Java" %}}
Ενώ μετατρέπετε το DOC σε JSON, μπορείτε επίσης να ορίσετε το εύρος στη μορφή εξόδου JSON. Για να ορίσετε το εύρος, μπορείτε να ανοίξετε το μετατρεπόμενο HTML χρησιμοποιώντας την κλάση Βιβλίο εργασίας, να δημιουργήσετε ένα εύρος δεδομένων προς εξαγωγή χρησιμοποιώντας τη μέθοδο Cells.createRange, να καλέσετε τη μέθοδο JsonUtility.exportRangeToJson με αναφορές Range & ExportRangeToJsonOptions και να γράψετε δεδομένα JSON συμβολοσειράς στο αρχείο μέσω Μέθοδος BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlam/" name="DOC Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlt/" name="DOC Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-csv/" name="DOC Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlsx/" name="DOC Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-fods/" name="DOC Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xltm/" name="DOC Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlsm/" name="DOC Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xltx/" name="DOC Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-ods/" name="DOC Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlsb/" name="DOC Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-excel/" name="DOC Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-sxc/" name="DOC Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-tsv/" name="DOC Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-dif/" name="DOC Προς την DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}