---
title: Μετατροπή PPTM σε XLTM μέσω C#
description: Μετατροπή PPTM σε XLTM σε C# χωρίς χρήση Microsoft Excel ή Powerpoint
url: /el/net/conversion/pptm-to-xltm/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: XLTM
otherformats: XLSX XLSM ODS XLSB XLTX FODS XLT XLS TSV XLTM MARKDOWN MHTML EXCEL XLAM DIF SXC DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PPTM σε XLTM μέσω C#" h2=".NET API για μετατροπή PPTM σε XLTM χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να μετατρέψετε το αρχείο PPTM σε XLTM σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), μπορείτε να εξαγάγετε το PPTM σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το PPTM σε XLTM μέσω C#" %}}
1. Ανοίξτε το αρχείο PPTM χρησιμοποιώντας την τάξη [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
2. Εξαγωγή PPTM ως HTML χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε XLTM χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου PPTM σε XLTM μέσω C#" %}}
Κατά τη μετατροπή του αρχείου PPTM σε XLTM, εάν το έγγραφο PPTM εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLTM χωρίς να αποκρυπτογραφήσετε το έγγραφο. Όταν το έγγραφό σας προστατεύεται με κωδικό πρόσβασης, σημαίνει ότι επιβάλλει ορισμένους περιορισμούς στην παρουσίαση. Για να καταργήσετε τους περιορισμούς, πρέπει να εισαγάγετε τον κωδικό πρόσβασης. Μια παρουσίαση που προστατεύεται με κωδικό πρόσβασης θεωρείται κλειδωμένη παρουσίαση. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PPTM σε XLTM με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου PPTM σε XLTM, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLTM. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο HTML που έχει μετατραπεί, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη λειτουργία AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας HTML ως XLTM με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-fods/" name="PPTM Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xltm/" name="PPTM Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlt/" name="PPTM Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlam/" name="PPTM Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-markdown/" name="PPTM Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-excel/" name="PPTM Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-mhtml/" name="PPTM Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlsb/" name="PPTM Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-ods/" name="PPTM Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-sxc/" name="PPTM Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xls/" name="PPTM Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xltx/" name="PPTM Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlsx/" name="PPTM Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-tsv/" name="PPTM Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dif/" name="PPTM Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlsm/" name="PPTM Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-doc/" name="PPTM Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-docx/" name="PPTM Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-docm/" name="PPTM Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dot/" name="PPTM Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dotm/" name="PPTM Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dotx/" name="PPTM Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-odt/" name="PPTM Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-ott/" name="PPTM Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-rtf/" name="PPTM Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-word/" name="PPTM Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-wordml/" name="PPTM Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-text/" name="PPTM Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-flatopx/" name="PPTM Προς την FLAΠρος τηνPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}