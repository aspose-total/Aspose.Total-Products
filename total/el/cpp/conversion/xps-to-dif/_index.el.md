---
title: C++ API για μετατροπή XPS σε DIF
description: Μετατροπή XPS σε DIF μέσω C++ API χωρίς χρήση Microsoft Excel ή Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: DIF
otherformats: XLSM MD ODS TSV SXC XLT TXT XLAM XLTM XLTX XLSB EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το XPS σε DIF σε εφαρμογές C++" h2="Μετατροπή XPS σε DIF σε εγγενείς εφαρμογές C++ χωρίς να απαιτείται Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή XPS σε DIF σε C++ μέσω των βιβλιοθηκών αυτοματοποίησης μορφών αρχείου [Aspose.Total for C++](https://products.aspose.com/total/cpp/) είναι μια απλή διαδικασία δύο βημάτων. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το XPS σε XLSX χρησιμοποιώντας το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), στη συνέχεια χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API προγραμματισμού υπολογιστικών φύλλων, μπορείτε να μετατρέψετε το XLSX σε DIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για μετατροπή XPS σε DIF" %}}
1. Ανοίξτε το αρχείο XPS χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Μετατρέψτε το XPS σε XLSX χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή DIF χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λήψη ή ρύθμιση πληροφοριών αρχείου XPS μέσω C++" %}}
Το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) σάς επιτρέπει επίσης να λαμβάνετε πληροφορίες σχετικά με το έγγραφό σας XPS και σας επιτρέπει να λαμβάνετε τεκμηριωμένες αποφάσεις πριν από τη διαδικασία μετατροπής. Για να λάβετε συγκεκριμένες πληροφορίες αρχείου ενός αρχείου XPS, πρέπει πρώτα να καλέσετε τη μέθοδο [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) τάξη. Μόλις ανακτηθεί το αντικείμενο DocumentInfo, μπορείτε να λάβετε τις τιμές των μεμονωμένων ιδιοτήτων. Επιπλέον, μπορείτε επίσης να ορίσετε τις ιδιότητες χρησιμοποιώντας αντίστοιχες μεθόδους της κλάσης DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε τη μορφή αρχείου DIF στη ροή μέσω C++" %}}
Το [Aspose.Cells for C++](https://products.aspose.com/cells/net/) επιτρέπει την αποθήκευση της μορφής αρχείου DIF για ροή. Για να αποθηκεύσετε αρχεία σε μια ροή, δημιουργήστε ένα αντικείμενο MemoryStream ή FileStream και αποθηκεύστε το αρχείο σε αυτό το αντικείμενο ροής καλώντας το [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) η μέθοδος [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) του αντικειμένου. Καθορίστε την επιθυμητή μορφή αρχείου χρησιμοποιώντας την απαρίθμηση [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) κατά την κλήση της μεθόδου Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-dif-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-xlsm/" name="XPS Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-md/" name="XPS Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-ods/" name="XPS Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-tsv/" name="XPS Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-sxc/" name="XPS Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-xlt/" name="XPS Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-txt/" name="XPS Προς την TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-xlam/" name="XPS Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-xltm/" name="XPS Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-xltx/" name="XPS Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-xlsb/" name="XPS Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xps-to-excel/" name="XPS Προς την EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}