---
title: Μετατροπή DOCM σε DIF σε C++
description: C++ API για μετατροπή DOCM σε DIF χωρίς χρήση του Microsoft Word ή του Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: DIF
otherformats: XLAM XLT XLSX XLSM TSV XLTX EXCEL CSV ODS SXC XLS XLTM FODS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για μετατροπή DOCM σε DIF" h2="Εξαγωγή DOCM σε DIF μέσω C++ χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής DOCM σε DIF στις εφαρμογές σας C++ εύκολα. Χρησιμοποιώντας πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API χειρισμού εγγράφων και μετατροπής [Aspose.Words for C++](https://products.aspose.com/words/cpp/), μπορείτε να εξάγετε DOCM σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), μπορείτε να μετατρέψετε HTML σε DIF. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για μετατροπή DOCM σε DIF" %}}
1. Ανοίξτε το αρχείο DOCM χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
2. Μετατρέψτε το DOCM σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string_saveformat)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή DIF χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Πρόσβαση στις ιδιότητες εγγράφου DOCM μέσω C++" %}}
Το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) σάς επιτρέπει επίσης να έχετε πρόσβαση στις ιδιότητες εγγράφου του αρχείου DOCM και σας επιτρέπει να λάβετε μια τεκμηριωμένη απόφαση πριν από τη διαδικασία μετατροπής. Για να αποκτήσετε πρόσβαση στις ιδιότητες εγγράφου, μπορείτε να χρησιμοποιήσετε το [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_docmument_properties) για να αποκτήσετε ενσωματωμένες ιδιότητες και [CustomDocumentProperties](https://https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_docmument_properties) για να αποκτήσετε προσαρμοσμένες ιδιότητες. Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να απαριθμήσετε όλες τις ενσωματωμένες και προσαρμοσμένες ιδιότητες σε ένα έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-docmument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε το αρχείο DIF στη ροή μέσω C++" %}}
Μετά τη μετατροπή του DOCM σε DIF, το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) σάς δίνει τη δυνατότητα να αποθηκεύσετε το έγγραφό σας σε ροή. Για να αποθηκεύσετε αρχεία σε μια ροή, δημιουργήστε ένα αντικείμενο MemoryStream ή FileStream και αποθηκεύστε το αρχείο σε αυτό το αντικείμενο ροής καλώντας το [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) η μέθοδος [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) του αντικειμένου. Καθορίστε την επιθυμητή μορφή αρχείου χρησιμοποιώντας την απαρίθμηση [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) όταν καλείτε το [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xlam/" name="DOCM Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xlt/" name="DOCM Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xlsx/" name="DOCM Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xlsm/" name="DOCM Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-tsv/" name="DOCM Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xltx/" name="DOCM Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-excel/" name="DOCM Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-dif/" name="DOCM Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-ods/" name="DOCM Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-sxc/" name="DOCM Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xls/" name="DOCM Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xltm/" name="DOCM Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-fods/" name="DOCM Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docm-to-xlsb/" name="DOCM Προς την XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}