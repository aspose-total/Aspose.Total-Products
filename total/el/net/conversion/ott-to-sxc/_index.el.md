---
title: .NET API για μετατροπή OTT σε SXC
description: C# API για μετατροπή OTT σε SXC χωρίς χρήση Microsoft Excel ή Adobe Reader
url_ignore: /el/net/conversion/ott-to-sxc/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: SXC
otherformats: EXCEL DIF SXC XLSM XLTM ODS XLT FODS XLS XLSB XLSX XLTX TSV XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για μετατροπή OTT σε SXC" h2="Εξαγωγή OTT σε SXC μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Word ή Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να συμπεριλάβετε τη δυνατότητα μετατροπής OTT σε SXC σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να εξαγάγετε το OTT σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε SXC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για μετατροπή OTT σε SXC" %}}
1. Ανοίξτε το αρχείο OTT χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Μετατρέψτε το OTT σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή SXC χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "SXC" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου OTT από τη ροή μέσω C#" %}}
Το [Aspose.Words for .NET](https://products.aspose.com/words/net/) σάς επιτρέπει επίσης να φορτώνετε έγγραφο OTT μέσω ροής. Για να ανοίξετε ένα έγγραφο από μια ροή, απλώς περάστε ένα αντικείμενο ροής που περιέχει το έγγραφο στον κατασκευαστή [Document](https://reference.aspose.com/words/net/aspose.words/document). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να ανοίξετε ένα έγγραφο από μια ροή:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Προσθήκη προσαρμοσμένων ιδιοτήτων σε αρχείο SXC μέσω C#" %}}
Κατά τη μετατροπή του OTT σε SXC, το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) σάς δίνει τη δυνατότητα να προσθέσετε προσαρμοσμένες ιδιότητες στα έγγραφά σας SXC. Για να προσθέσετε μια προσαρμοσμένη ιδιότητα, μπορείτε να χρησιμοποιήσετε τη μέθοδο [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) για το [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) τάξη. Η μέθοδος Προσθήκη προσθέτει την ιδιότητα στο αρχείο Excel και επιστρέφει μια αναφορά για την ιδιότητα του νέου εγγράφου ως [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties /documentproperty) αντικείμενο. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-dif/" name="OTT Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xlsb/" name="OTT Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-tsv/" name="OTT Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-fods/" name="OTT Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xlt/" name="OTT Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-excel/" name="OTT Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xlsx/" name="OTT Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-ods/" name="OTT Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-sxc/" name="OTT Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xlam/" name="OTT Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xltm/" name="OTT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xlsm/" name="OTT Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xls/" name="OTT Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ott-to-xltx/" name="OTT Προς την XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}