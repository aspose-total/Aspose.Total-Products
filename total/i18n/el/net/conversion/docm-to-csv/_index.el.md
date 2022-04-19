---
title: .NET API για μετατροπή DOCM σε CSV
description: C# API για μετατροπή DOCM σε CSV χωρίς χρήση Microsoft Excel ή Adobe Reader
url: /el/net/conversion/docm-to-csv/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: CSV
otherformats: XLSX XLTM FODS EXCEL XLAM DIF ODS SXC XLSB XLS XLT XLTX XLSM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για μετατροπή DOCM σε CSV" h2="Εξαγωγή DOCM σε CSV μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής DOCM σε CSV σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να εξαγάγετε το DOCM σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε CSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για μετατροπή DOCM σε CSV" %}}
1. Ανοίξτε το αρχείο DOCM χρησιμοποιώντας την τάξη [Docmument](https://apireference.aspose.com/words/net/aspose.words/docmument)
2. Μετατρέψτε το DOCM σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/words/net/aspose.words.docmument/save/methods/4)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή CSV χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "CSV" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου DOCM από τη ροή μέσω C#" %}}
Το [Aspose.Words for .NET](https://products.aspose.com/words/net/) σάς επιτρέπει επίσης να φορτώνετε έγγραφο DOCM μέσω ροής. Για να ανοίξετε ένα έγγραφο από μια ροή, απλώς περάστε ένα αντικείμενο ροής που περιέχει το έγγραφο στον κατασκευαστή [Docmument](https://apireference.aspose.com/words/net/aspose.words/docmument). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να ανοίξετε ένα έγγραφο από μια ροή:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη προσαρμοσμένων ιδιοτήτων σε αρχείο CSV μέσω C#" %}}
Κατά τη μετατροπή του DOCM σε CSV, το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) σάς δίνει τη δυνατότητα να προσθέσετε προσαρμοσμένες ιδιότητες στα έγγραφά σας CSV. Για να προσθέσετε μια προσαρμοσμένη ιδιότητα, μπορείτε να χρησιμοποιήσετε τη μέθοδο [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocmumentpropertycollection/methods/add/index) για το [CustomDocmumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocmumentpropertycollection) τάξη. Η μέθοδος Προσθήκη προσθέτει την ιδιότητα στο αρχείο Excel και επιστρέφει μια αναφορά για την ιδιότητα του νέου εγγράφου ως [Aspose.Cells.Properties.DocmumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /docmumentproperty) αντικείμενο. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-dif/" name="DOCM Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xlsb/" name="DOCM Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-tsv/" name="DOCM Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-fods/" name="DOCM Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xlt/" name="DOCM Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-excel/" name="DOCM Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xlsx/" name="DOCM Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-ods/" name="DOCM Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-sxc/" name="DOCM Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xlam/" name="DOCM Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xltm/" name="DOCM Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xlsm/" name="DOCM Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xls/" name="DOCM Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docm-to-xltx/" name="DOCM Προς την XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}