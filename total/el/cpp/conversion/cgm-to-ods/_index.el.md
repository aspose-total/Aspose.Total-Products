---
title: C++ API για μετατροπή CGM σε ODS
description: Μετατροπή CGM σε ODS μέσω C++ API χωρίς χρήση Microsoft Excel ή Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: ODS
otherformats: XLTM XLTX XLT CSV TXT XLSM FODS XLAM XLSB TSV MD EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το CGM σε ODS σε εφαρμογές C++" h2="Μετατροπή CGM σε ODS σε εγγενείς εφαρμογές C++ χωρίς να απαιτείται Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή CGM σε ODS σε C++ μέσω των βιβλιοθηκών αυτοματοποίησης μορφών αρχείου [Aspose.Total for C++](https://products.aspose.com/total/cpp/) είναι μια απλή διαδικασία δύο βημάτων. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το CGM σε XLSX χρησιμοποιώντας το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), στη συνέχεια χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API προγραμματισμού υπολογιστικών φύλλων, μπορείτε να μετατρέψετε το XLSX σε ODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για μετατροπή CGM σε ODS" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Μετατρέψτε το CGM σε XLSX χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή ODS χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λήψη ή ρύθμιση πληροφοριών αρχείου CGM μέσω C++" %}}
Το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) σάς επιτρέπει επίσης να λαμβάνετε πληροφορίες σχετικά με το έγγραφό σας CGM και σας επιτρέπει να λαμβάνετε τεκμηριωμένες αποφάσεις πριν από τη διαδικασία μετατροπής. Για να λάβετε συγκεκριμένες πληροφορίες αρχείου ενός αρχείου CGM, πρέπει πρώτα να καλέσετε τη μέθοδο [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) τάξη. Μόλις ανακτηθεί το αντικείμενο DocumentInfo, μπορείτε να λάβετε τις τιμές των μεμονωμένων ιδιοτήτων. Επιπλέον, μπορείτε επίσης να ορίσετε τις ιδιότητες χρησιμοποιώντας αντίστοιχες μεθόδους της κλάσης DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε τη μορφή αρχείου ODS στη ροή μέσω C++" %}}
Το [Aspose.Cells for C++](https://products.aspose.com/cells/net/) επιτρέπει την αποθήκευση της μορφής αρχείου ODS για ροή. Για να αποθηκεύσετε αρχεία σε μια ροή, δημιουργήστε ένα αντικείμενο MemoryStream ή FileStream και αποθηκεύστε το αρχείο σε αυτό το αντικείμενο ροής καλώντας το [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) η μέθοδος [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) του αντικειμένου. Καθορίστε την επιθυμητή μορφή αρχείου χρησιμοποιώντας την απαρίθμηση [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) κατά την κλήση της μεθόδου Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-ods-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-xltm/" name="CGM Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-xltx/" name="CGM Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-xlt/" name="CGM Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-ods/" name="CGM Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-txt/" name="CGM Προς την TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-xlsm/" name="CGM Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-fods/" name="CGM Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-xlam/" name="CGM Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-xlsb/" name="CGM Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-tsv/" name="CGM Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-md/" name="CGM Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/cgm-to-excel/" name="CGM Προς την EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}