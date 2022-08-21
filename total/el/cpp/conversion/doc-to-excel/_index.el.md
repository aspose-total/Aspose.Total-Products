---
title: Μετατροπή DOC σε EXCEL σε C++
description: C++ API για μετατροπή DOC σε EXCEL χωρίς χρήση του Microsoft Word ή του Microsoft Excel
url: /el/cpp/conversion/doc-to-excel/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLSX
otherformats: XLAM XLSX XLT FODS SXC XLS CSV XLSM XLTX TSV XLTM DIF XLSB ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για μετατροπή DOC σε EXCEL" h2="Εξαγωγή DOC σε EXCEL μέσω C++ χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής DOC σε EXCEL στις εφαρμογές σας C++ εύκολα. Χρησιμοποιώντας πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API χειρισμού εγγράφων και μετατροπής [Aspose.Words for C++](https://products.aspose.com/words/cpp/), μπορείτε να εξάγετε DOC σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), μπορείτε να μετατρέψετε HTML σε EXCEL. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για μετατροπή DOC σε EXCEL" %}}
1. Ανοίξτε το αρχείο DOC χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Μετατρέψτε το DOC σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή EXCEL χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Πρόσβαση στις ιδιότητες εγγράφου DOC μέσω C++" %}}
Το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) σάς επιτρέπει επίσης να έχετε πρόσβαση στις ιδιότητες εγγράφου του αρχείου DOC και σας επιτρέπει να λάβετε μια τεκμηριωμένη απόφαση πριν από τη διαδικασία μετατροπής. Για να αποκτήσετε πρόσβαση στις ιδιότητες εγγράφου, μπορείτε να χρησιμοποιήσετε το [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) για να αποκτήσετε ενσωματωμένες ιδιότητες και [CustomDocumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) για να αποκτήσετε προσαρμοσμένες ιδιότητες. Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να απαριθμήσετε όλες τις ενσωματωμένες και προσαρμοσμένες ιδιότητες σε ένα έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε το αρχείο EXCEL στη ροή μέσω C++" %}}
Μετά τη μετατροπή του DOC σε EXCEL, το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) σάς δίνει τη δυνατότητα να αποθηκεύσετε το έγγραφό σας σε ροή. Για να αποθηκεύσετε αρχεία σε μια ροή, δημιουργήστε ένα αντικείμενο MemoryStream ή FileStream και αποθηκεύστε το αρχείο σε αυτό το αντικείμενο ροής καλώντας το [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) η μέθοδος [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) του αντικειμένου. Καθορίστε την επιθυμητή μορφή αρχείου χρησιμοποιώντας την απαρίθμηση [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) όταν καλείτε το [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xlam/" name="DOC Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xlsx/" name="DOC Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xlt/" name="DOC Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-fods/" name="DOC Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-sxc/" name="DOC Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xls/" name="DOC Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-excel/" name="DOC Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xlsm/" name="DOC Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xltx/" name="DOC Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-tsv/" name="DOC Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xltm/" name="DOC Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-dif/" name="DOC Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-xlsb/" name="DOC Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/doc-to-ods/" name="DOC Προς την ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}