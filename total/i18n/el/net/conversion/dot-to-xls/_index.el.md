---
title: .NET API για μετατροπή DOT σε XLS
description: C# API για μετατροπή DOT σε XLS χωρίς χρήση Microsoft Excel ή Adobe Reader
url: /el/net/conversion/dot-to-xls/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: XLS
otherformats: DIF XLS XLT XLSM FODS XLAM XLTM ODS XLS EXCEL XLSX SXC TSV XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για μετατροπή DOT σε XLS" h2="Εξαγωγή DOT σε XLS μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής DOT σε XLS σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να εξαγάγετε το DOT σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε XLS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για μετατροπή DOT σε XLS" %}}
1. Ανοίξτε το αρχείο DOT χρησιμοποιώντας την τάξη [Dotument](https://apireference.aspose.com/words/net/aspose.words/dotument)
2. Μετατρέψτε το DOT σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/words/net/aspose.words.dotument/save/methods/4)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLS χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "XLS" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου DOT από τη ροή μέσω C#" %}}
Το [Aspose.Words for .NET](https://products.aspose.com/words/net/) σάς επιτρέπει επίσης να φορτώνετε έγγραφο DOT μέσω ροής. Για να ανοίξετε ένα έγγραφο από μια ροή, απλώς περάστε ένα αντικείμενο ροής που περιέχει το έγγραφο στον κατασκευαστή [Dotument](https://apireference.aspose.com/words/net/aspose.words/dotument). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να ανοίξετε ένα έγγραφο από μια ροή:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη προσαρμοσμένων ιδιοτήτων σε αρχείο XLS μέσω C#" %}}
Κατά τη μετατροπή του DOT σε XLS, το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) σάς δίνει τη δυνατότητα να προσθέσετε προσαρμοσμένες ιδιότητες στα έγγραφά σας XLS. Για να προσθέσετε μια προσαρμοσμένη ιδιότητα, μπορείτε να χρησιμοποιήσετε τη μέθοδο [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotumentpropertycollection/methods/add/index) για το [CustomDotumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotumentpropertycollection) τάξη. Η μέθοδος Προσθήκη προσθέτει την ιδιότητα στο αρχείο Excel και επιστρέφει μια αναφορά για την ιδιότητα του νέου εγγράφου ως [Aspose.Cells.Properties.DotumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /dotumentproperty) αντικείμενο. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-dif/" name="DOT Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlsb/" name="DOT Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-tsv/" name="DOT Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-fods/" name="DOT Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlt/" name="DOT Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-excel/" name="DOT Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlsx/" name="DOT Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-ods/" name="DOT Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-sxc/" name="DOT Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlam/" name="DOT Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xltm/" name="DOT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlsm/" name="DOT Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xls/" name="DOT Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xltx/" name="DOT Προς την XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}