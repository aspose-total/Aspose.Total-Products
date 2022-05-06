---
title: Μετατροπή POWERPOINT σε MARKDOWN μέσω C#
description: Μετατροπή POWERPOINT σε MARKDOWN σε C# χωρίς χρήση Microsoft Excel ή Powerpoint
url_ignore: /el/net/conversion/powerpoint-to-markdown/
family: total
platformtag: net
feature: conversion
informat: POWERPOINT
outformat: MARKDOWN
otherformats: EXCEL MARKDOWN XLSX ODS XLS DIF XLT FODS MHTML XLTM TSV XLAM XLSM SXC XLTX XLSB DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή POWERPOINT σε MARKDOWN μέσω C#" h2=".NET API για μετατροπή POWERPOINT σε MARKDOWN χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να μετατρέψετε το αρχείο POWERPOINT σε MARKDOWN σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), μπορείτε να εξαγάγετε το POWERPOINT σε HTML. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε HTML σε MARKDOWN.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το POWERPOINT σε MARKDOWN μέσω C#" %}}
1. Ανοίξτε το αρχείο POWERPOINT χρησιμοποιώντας την τάξη [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
2. Εξαγωγή POWERPOINT ως HTML χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε MARKDOWN χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου POWERPOINT σε MARKDOWN μέσω C#" %}}
Κατά τη μετατροπή του αρχείου POWERPOINT σε MARKDOWN, εάν το έγγραφο POWERPOINT εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε MARKDOWN χωρίς να αποκρυπτογραφήσετε το έγγραφο. Όταν το έγγραφό σας προστατεύεται με κωδικό πρόσβασης, σημαίνει ότι επιβάλλει ορισμένους περιορισμούς στην παρουσίαση. Για να καταργήσετε τους περιορισμούς, πρέπει να εισαγάγετε τον κωδικό πρόσβασης. Μια παρουσίαση που προστατεύεται με κωδικό πρόσβασης θεωρείται κλειδωμένη παρουσίαση. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή POWERPOINT σε MARKDOWN με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου POWERPOINT σε MARKDOWN, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου MARKDOWN. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο HTML που έχει μετατραπεί, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη λειτουργία AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας HTML ως MARKDOWN με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-fods/" name="POWERPOINT Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xltm/" name="POWERPOINT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xlt/" name="POWERPOINT Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xlam/" name="POWERPOINT Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-markdown/" name="POWERPOINT Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-excel/" name="POWERPOINT Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-mhtml/" name="POWERPOINT Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xlsb/" name="POWERPOINT Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-ods/" name="POWERPOINT Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-sxc/" name="POWERPOINT Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xls/" name="POWERPOINT Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xltx/" name="POWERPOINT Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xlsx/" name="POWERPOINT Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-tsv/" name="POWERPOINT Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-dif/" name="POWERPOINT Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-xlsm/" name="POWERPOINT Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-doc/" name="POWERPOINT Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-docx/" name="POWERPOINT Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-docm/" name="POWERPOINT Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-dot/" name="POWERPOINT Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-dotm/" name="POWERPOINT Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-dotx/" name="POWERPOINT Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-odt/" name="POWERPOINT Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-ott/" name="POWERPOINT Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-rtf/" name="POWERPOINT Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-word/" name="POWERPOINT Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-wordml/" name="POWERPOINT Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-text/" name="POWERPOINT Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/powerpoint-to-flatopx/" name="POWERPOINT Προς την FLAΠρος τηνPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}