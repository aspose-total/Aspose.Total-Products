---
title: C++ API για μετατροπή MHTML σε XLSM
description: Μετατροπή MHTML σε XLSM μέσω C++ API χωρίς χρήση Microsoft Excel ή Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: XLSM
otherformats: SXC ODS DIF EXCEL XLTX XLT CSV FODS XLSB MD TXT XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το MHTML σε XLSM σε εφαρμογές C++" h2="Μετατροπή MHTML σε XLSM σε εγγενείς εφαρμογές C++ χωρίς να απαιτείται Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Η μετατροπή MHTML σε XLSM σε C++ μέσω των βιβλιοθηκών αυτοματοποίησης μορφών αρχείου [Aspose.Total for C++](https://products.aspose.com/total/cpp/) είναι μια απλή διαδικασία δύο βημάτων. Στο πρώτο βήμα, μπορείτε να εξαγάγετε το MHTML σε XLSX χρησιμοποιώντας το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), στη συνέχεια χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API προγραμματισμού υπολογιστικών φύλλων, μπορείτε να μετατρέψετε το XLSX σε XLSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για μετατροπή MHTML σε XLSM" %}}
1. Ανοίξτε το αρχείο MHTML χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Μετατρέψτε το MHTML σε XLSX χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLSM χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λήψη ή ρύθμιση πληροφοριών αρχείου MHTML μέσω C++" %}}
Το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) σάς επιτρέπει επίσης να λαμβάνετε πληροφορίες σχετικά με το έγγραφό σας MHTML και σας επιτρέπει να λαμβάνετε τεκμηριωμένες αποφάσεις πριν από τη διαδικασία μετατροπής. Για να λάβετε συγκεκριμένες πληροφορίες αρχείου ενός αρχείου MHTML, πρέπει πρώτα να καλέσετε τη μέθοδο [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) τάξη. Μόλις ανακτηθεί το αντικείμενο DocumentInfo, μπορείτε να λάβετε τις τιμές των μεμονωμένων ιδιοτήτων. Επιπλέον, μπορείτε επίσης να ορίσετε τις ιδιότητες χρησιμοποιώντας αντίστοιχες μεθόδους της κλάσης DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αποθηκεύστε τη μορφή αρχείου XLSM στη ροή μέσω C++" %}}
Το [Aspose.Cells for C++](https://products.aspose.com/cells/net/) επιτρέπει την αποθήκευση της μορφής αρχείου XLSM για ροή. Για να αποθηκεύσετε αρχεία σε μια ροή, δημιουργήστε ένα αντικείμενο MemoryStream ή FileStream και αποθηκεύστε το αρχείο σε αυτό το αντικείμενο ροής καλώντας το [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) η μέθοδος [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) του αντικειμένου. Καθορίστε την επιθυμητή μορφή αρχείου χρησιμοποιώντας την απαρίθμηση [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) κατά την κλήση της μεθόδου Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsm-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}