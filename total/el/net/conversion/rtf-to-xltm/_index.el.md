---
title: .NET API για μετατροπή RTF σε XLTM
description: C# API για μετατροπή RTF σε XLTM χωρίς χρήση Microsoft Excel ή Adobe Reader
url: /el/net/conversion/rtf-to-xltm/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLTM
otherformats: FODS XLS XLSB XLSX XLTM XLTX XLAM TSV ODS XLT EXCEL SXC DIF XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για μετατροπή RTF σε XLTM" h2="Εξαγωγή RTF σε XLTM μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής RTF σε XLTM σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να εξαγάγετε το RTF σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για μετατροπή RTF σε XLTM" %}}
1. Ανοίξτε το αρχείο RTF χρησιμοποιώντας την τάξη [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument)
2. Μετατρέψτε το RTF σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/words/net/aspose.words.rtfument/save/methods/4)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLTM χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "XLTM" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου RTF από τη ροή μέσω C#" %}}
Το [Aspose.Words for .NET](https://products.aspose.com/words/net/) σάς επιτρέπει επίσης να φορτώνετε έγγραφο RTF μέσω ροής. Για να ανοίξετε ένα έγγραφο από μια ροή, απλώς περάστε ένα αντικείμενο ροής που περιέχει το έγγραφο στον κατασκευαστή [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να ανοίξετε ένα έγγραφο από μια ροή:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(https
{{% blocks/products/pf/feature-page-section  h2="Προσθήκη προσαρμοσμένων ιδιοτήτων σε αρχείο XLTM μέσω C#" %}}
Κατά τη μετατροπή του RTF σε XLTM, το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) σάς δίνει τη δυνατότητα να προσθέσετε προσαρμοσμένες ιδιότητες στα έγγραφά σας XLTM. Για να προσθέσετε μια προσαρμοσμένη ιδιότητα, μπορείτε να χρησιμοποιήσετε τη μέθοδο [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection/methods/add/index) για το [CustomRtfumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection) τάξη. Η μέθοδος Προσθήκη προσθέτει την ιδιότητα στο αρχείο Excel και επιστρέφει μια αναφορά για την ιδιότητα του νέου εγγράφου ως [Aspose.Cells.Properties.RtfumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /rtfumentproperty) αντικείμενο. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-dif/" name="RTF Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xlsb/" name="RTF Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-tsv/" name="RTF Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-fods/" name="RTF Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xlt/" name="RTF Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-excel/" name="RTF Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xlsx/" name="RTF Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-ods/" name="RTF Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-sxc/" name="RTF Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xlam/" name="RTF Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xltm/" name="RTF Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xlsm/" name="RTF Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xls/" name="RTF Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-xltx/" name="RTF Προς την XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}