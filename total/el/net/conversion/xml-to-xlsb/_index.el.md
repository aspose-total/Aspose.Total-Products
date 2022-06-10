---
title: Μετατροπή XML σε XLSB μέσω C# API
description: C# API για μετατροπή αρχείου XML σε XLSB χωρίς χρήση του Microsoft Excel ή του Adobe Reader
url_ignore: /el/net/conversion/xml-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: XLSB
otherformats: XLTX XLT SXC XLSB MD XLTM XLSM FODS XLAM TSV TXT ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για απόδοση XML σε XLSB" h2="Εξαγωγή αρχείου XML σε XLSB μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να μετατρέψετε το αρχείο XML σε XLSB σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το XML στο XLSX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε το XLSX σε XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή XML σε XLSB" %}}
1. Ανοίξτε το αρχείο XML χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το XML σε XLSX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLSB χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "Xlsb" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου XML σε XLSB μέσω C#" %}}
Εάν το έγγραφό σας XML προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLSB χωρίς τον κωδικό πρόσβασης. Χρησιμοποιώντας το API, μπορείτε πρώτα να ανοίξετε το προστατευμένο έγγραφο χρησιμοποιώντας έναν έγκυρο κωδικό πρόσβασης και να το μετατρέψετε μετά από αυτόν. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε μια νέα παρουσία της κλάσης [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να μεταβιβάσετε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου XML σε XLSB με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου XML σε XLSB, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLSB. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο XLSX που μετατράπηκε, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη συνάρτηση AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας XLSX ως XLSB με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-sxc/" name="XML Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-xltx/" name="XML Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-md/" name="XML Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-tsv/" name="XML Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-txt/" name="XML Προς την TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-ods/" name="XML Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-xlt/" name="XML Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-xlsm/" name="XML Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-xlam/" name="XML Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-xltm/" name="XML Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-dif/" name="XML Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xml-to-xlsb/" name="XML Προς την XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}