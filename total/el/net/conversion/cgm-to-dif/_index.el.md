---
title: Μετατροπή CGM σε DIF μέσω C# API
description: C# API για μετατροπή αρχείου CGM σε DIF χωρίς χρήση του Microsoft Excel ή του Adobe Reader
url_ignore: /el/net/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: FODS EXCEL ODS XLT TSV MD XLTX XLSB TXT DIF XLTM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για απόδοση CGM σε DIF" h2="Εξαγωγή αρχείου CGM σε DIF μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να μετατρέψετε το αρχείο CGM σε DIF σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το CGM στο XLSX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε το XLSX σε DIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή CGM σε DIF" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το CGM σε XLSX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή DIF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "Dif" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου CGM σε DIF μέσω C#" %}}
Εάν το έγγραφό σας CGM προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε DIF χωρίς τον κωδικό πρόσβασης. Χρησιμοποιώντας το API, μπορείτε πρώτα να ανοίξετε το προστατευμένο έγγραφο χρησιμοποιώντας έναν έγκυρο κωδικό πρόσβασης και να το μετατρέψετε μετά από αυτόν. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε μια νέα παρουσία της κλάσης [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να μεταβιβάσετε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε DIF με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου CGM σε DIF, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου DIF. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο XLSX που μετατράπηκε, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη συνάρτηση AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας XLSX ως DIF με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε DIF μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η μετάφραση του κειμένου:

Η μετατροπή των αρχιτεκτονικών γραφικών (CGM) σε μορφή DIF είναι απαραίτηλη για να ενεργοποιήσετε πλήρως τις δυνατότητες σας στα vector γράφη και στις εργασίες εικονιστικής. Η αυτή μετατροπή επιτρέπει:

**Πωtiered Uses:**

*   **Επεξεργασία Vector Graphics**: Μετατροπή αρχιτεκτονικών γραφικών σε μορφή DIF για επεξεργασία και τροποποίηση vector γράφων, δημιουργία ακριβών σχημάτων καιγραμμών.
*   **Σχεδιά εικονιστικής**: Χρήση μορφών DIF για δημιουργία επαγγελματικών εικονιών, με λεπτομερή έλεγχο της πλάκας γραμμών, του στυλ και των χρώσεων.
*   **Αρχιτεκτονική Βιζουαλισα**: Μετατροπή αρχιτεκτονικών γραφικών για vizualισα αρχιτεκτονικών σχεδίων, δημιουργία 2D και 3D μονελών και επικύρωση της προθέσης σχεδίου.
*   **Γραφική Σχεδιά και Εκτύπωση**: Χρήση μορφών DIF για ετοιμάσία vector γράφων προς εκτύπωση, με υψηλότερη ποιότητα输出 και ακριβή γραμμωτή.
*   **Computer-Aided Design (CAD)**: Μετατροπή αρχιτεκτονικών γραφικών για ενίσχυση workflow του CAD, αυτοματοποίηση εργασιών όπως η μετατροπή δεδομένων και η διαχείρηση αρχιτεκτονικών αρχιών.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}