---
title: Μετατροπή ODT σε FODS σε C++
description: C++ API για μετατροπή ODT σε FODS χωρίς χρήση του Microsoft Word ή του Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: FODS
otherformats: XLSB ODS TSV XLSM XLAM XLTX XLS XLTM XLSX SXC XLT EXCEL CSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για μετατροπή ODT σε FODS" h2="Εξαγωγή ODT σε FODS μέσω C++ χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής ODT σε FODS στις εφαρμογές σας C++ εύκολα. Χρησιμοποιώντας πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API χειρισμού εγγράφων και μετατροπής [Aspose.Words for C++](https://products.aspose.com/words/cpp/), μπορείτε να εξάγετε ODT σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), μπορείτε να μετατρέψετε HTML σε FODS. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για μετατροπή ODT σε FODS" %}}
1. Ανοίξτε το αρχείο ODT χρησιμοποιώντας την αναφορά κλάσης [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
2. Μετατρέψτε το ODT σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string_saveformat)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή FODS χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Πρόσβαση στις ιδιότητες εγγράφου ODT μέσω C++" %}}
Το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) σάς επιτρέπει επίσης να έχετε πρόσβαση στις ιδιότητες εγγράφου του αρχείου ODT και σας επιτρέπει να λάβετε μια τεκμηριωμένη απόφαση πριν από τη διαδικασία μετατροπής. Για να αποκτήσετε πρόσβαση στις ιδιότητες εγγράφου, μπορείτε να χρησιμοποιήσετε το [BuiltInOdtumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_odtument_properties) για να αποκτήσετε ενσωματωμένες ιδιότητες και [CustomOdtumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_odtument_properties) για να αποκτήσετε προσαρμοσμένες ιδιότητες. Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να απαριθμήσετε όλες τις ενσωματωμένες και προσαρμοσμένες ιδιότητες σε ένα έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-odtument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε το αρχείο FODS στη ροή μέσω C++" %}}
Μετά τη μετατροπή του ODT σε FODS, το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) σάς δίνει τη δυνατότητα να αποθηκεύσετε το έγγραφό σας σε ροή. Για να αποθηκεύσετε αρχεία σε μια ροή, δημιουργήστε ένα αντικείμενο MemoryStream ή FileStream και αποθηκεύστε το αρχείο σε αυτό το αντικείμενο ροής καλώντας το [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) η μέθοδος [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) του αντικειμένου. Καθορίστε την επιθυμητή μορφή αρχείου χρησιμοποιώντας την απαρίθμηση [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) όταν καλείτε το [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xlsb/" name="ODT Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-ods/" name="ODT Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-tsv/" name="ODT Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xlsm/" name="ODT Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xlam/" name="ODT Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xltx/" name="ODT Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xls/" name="ODT Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xltm/" name="ODT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xlsx/" name="ODT Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-sxc/" name="ODT Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-xlt/" name="ODT Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-excel/" name="ODT Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-fods/" name="ODT Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/odt-to-dif/" name="ODT Προς την DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}