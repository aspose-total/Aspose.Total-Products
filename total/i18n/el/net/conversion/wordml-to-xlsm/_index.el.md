---
title: .NET API για μετατροπή WORDML σε XLSM
description: C# API για μετατροπή WORDML σε XLSM χωρίς χρήση Microsoft Excel ή Adobe Reader
url: /el/net/conversion/wordml-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: WORDML
outformat: XLSM
otherformats: XLSX XLAM XLSB SXC FODS ODS DIF EXCEL XLT XLTM XLSM XLTX XLS TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για μετατροπή WORDML σε XLSM" h2="Εξαγωγή WORDML σε XLSM μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής WORDML σε XLSM σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να εξαγάγετε το WORDML σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για μετατροπή WORDML σε XLSM" %}}
1. Ανοίξτε το αρχείο WORDML χρησιμοποιώντας την τάξη [Wordmlument](https://apireference.aspose.com/words/net/aspose.words/wordmlument)
2. Μετατρέψτε το WORDML σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/words/net/aspose.words.wordmlument/save/methods/4)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLSM χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "XLSM" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου WORDML από τη ροή μέσω C#" %}}
Το [Aspose.Words for .NET](https://products.aspose.com/words/net/) σάς επιτρέπει επίσης να φορτώνετε έγγραφο WORDML μέσω ροής. Για να ανοίξετε ένα έγγραφο από μια ροή, απλώς περάστε ένα αντικείμενο ροής που περιέχει το έγγραφο στον κατασκευαστή [Wordmlument](https://apireference.aspose.com/words/net/aspose.words/wordmlument). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να ανοίξετε ένα έγγραφο από μια ροή:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη προσαρμοσμένων ιδιοτήτων σε αρχείο XLSM μέσω C#" %}}
Κατά τη μετατροπή του WORDML σε XLSM, το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) σάς δίνει τη δυνατότητα να προσθέσετε προσαρμοσμένες ιδιότητες στα έγγραφά σας XLSM. Για να προσθέσετε μια προσαρμοσμένη ιδιότητα, μπορείτε να χρησιμοποιήσετε τη μέθοδο [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordmlumentpropertycollection/methods/add/index) για το [CustomWordmlumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordmlumentpropertycollection) τάξη. Η μέθοδος Προσθήκη προσθέτει την ιδιότητα στο αρχείο Excel και επιστρέφει μια αναφορά για την ιδιότητα του νέου εγγράφου ως [Aspose.Cells.Properties.WordmlumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /wordmlumentproperty) αντικείμενο. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-dif/" name="WORDML Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xlsb/" name="WORDML Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-tsv/" name="WORDML Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-fods/" name="WORDML Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xlt/" name="WORDML Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-excel/" name="WORDML Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xlsx/" name="WORDML Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-ods/" name="WORDML Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-sxc/" name="WORDML Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xlam/" name="WORDML Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xltm/" name="WORDML Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xlsm/" name="WORDML Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xls/" name="WORDML Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/wordml-to-xltx/" name="WORDML Προς την XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}