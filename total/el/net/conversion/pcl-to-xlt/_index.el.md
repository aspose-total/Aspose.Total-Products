---
title: Μετατροπή PCL σε XLT μέσω C# API
description: C# API για μετατροπή αρχείου PCL σε XLT χωρίς χρήση του Microsoft Excel ή του Adobe Reader
url_ignore: /el/net/conversion/pcl-to-xlt/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: XLT
otherformats: XLSM ODS XLSB TXT MD DIF XLT XLTX FODS XLTM EXCEL XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για απόδοση PCL σε XLT" h2="Εξαγωγή αρχείου PCL σε XLT μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να μετατρέψετε το αρχείο PCL σε XLT σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το PCL στο XLSX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε το XLSX σε XLT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή PCL σε XLT" %}}
1. Ανοίξτε το αρχείο PCL χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το PCL σε XLSX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLT χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "Xlt" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου PCL σε XLT μέσω C#" %}}
Εάν το έγγραφό σας PCL προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLT χωρίς τον κωδικό πρόσβασης. Χρησιμοποιώντας το API, μπορείτε πρώτα να ανοίξετε το προστατευμένο έγγραφο χρησιμοποιώντας έναν έγκυρο κωδικό πρόσβασης και να το μετατρέψετε μετά από αυτόν. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε μια νέα παρουσία της κλάσης [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να μεταβιβάσετε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου PCL σε XLT με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου PCL σε XLT, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLT. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο XLSX που μετατράπηκε, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη συνάρτηση AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας XLSX ως XLT με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-sxc/" name="PCL Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-xltx/" name="PCL Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-md/" name="PCL Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-tsv/" name="PCL Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-txt/" name="PCL Προς την TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-ods/" name="PCL Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-xlt/" name="PCL Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-xlsm/" name="PCL Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-xlam/" name="PCL Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-xltm/" name="PCL Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-dif/" name="PCL Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pcl-to-xlsb/" name="PCL Προς την XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}