---
title: Μετατροπή CGM σε TXT μέσω C# API
description: C# API για μετατροπή αρχείου CGM σε TXT χωρίς χρήση του Microsoft Excel ή του Adobe Reader
url_ignore: /el/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για απόδοση CGM σε TXT" h2="Εξαγωγή αρχείου CGM σε TXT μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να μετατρέψετε το αρχείο CGM σε TXT σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το CGM στο XLSX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε το XLSX σε TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή CGM σε TXT" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το CGM σε XLSX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή TXT χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "Txt" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου CGM σε TXT μέσω C#" %}}
Εάν το έγγραφό σας CGM προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε TXT χωρίς τον κωδικό πρόσβασης. Χρησιμοποιώντας το API, μπορείτε πρώτα να ανοίξετε το προστατευμένο έγγραφο χρησιμοποιώντας έναν έγκυρο κωδικό πρόσβασης και να το μετατρέψετε μετά από αυτόν. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε μια νέα παρουσία της κλάσης [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να μεταβιβάσετε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε TXT με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου CGM σε TXT, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου TXT. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο XLSX που μετατράπηκε, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη συνάρτηση AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας XLSX ως TXT με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε TXT μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Τα αρχεία CGM (Computer Graphics Metafile) χρησιμοποιούνται για το αποθήκισμα πληροφοριών εικονογραφίας βίκτορας, γεγονός που τα καθιστά ιδανικά για τη δημιουργία στατικών εικόνων και εμβαδών. Ωστόσο, όταν εργάζονται με δεδομένα που είναι δυναμικά, εγγυόνονται χρήσεις όπως η εφαρμογή του προγράμματος Notepad για βασικές πράξεις επεξεργασίας κειμένου και για την δημιουργία εγγυαμάτων.

Η μετατροπή των αρχείων CGM σε μορφές κειμένου απλό είναι αναγκαία, για να ενεργοποιήσετε πλήρως τις δυνατότητες σας για επεξεργασία κειμένου. Η μετάβαση αυτή σας επιτρέπει:

**Πωλές χρήσης:**

*   **Δокументαταция δεδομένων**: Μετατροπή των αρχείων CGM σε ανθρώπινες διαβάσιμες μορφές, που ευκολύνουν τη συνεχή κατανόηση και τη μετάδοση της πληροφορίας για τα γραφικά.
*   **Επεξεργασία κειμένου**: Χρήση του προγράμματος Notepad για επεξεργασία και τροποποίηση κειμένου που έχει ανακτηθεί από αρχεία CGM, το οποίο είναι κατάλληλο για βασικές εργασίες επεξεργασίας κειμένου.
*   **Δημιουργία ASCII Art**: Μετατροπή των αρχείων CGM σε μορφή ASCII art, δημιουργώντας απλά, κείμενα-εικόνα που βασίζονται σε χαρακτήρες ASCII, τα οποία μπορούν να χρησιμοποιηθούν για καλλιτεχνικούς ή διακοσμητικούς σκοπούς.
*   **Ενγαγές δεδομένων σε άλλα εργαλεία**: Μετατροπή των αρχείων CGM σε μορφή κειμένου απλό, για να εισάγονται τα δεδομένα γραφικών σε άλλα προγράμματα επεξεργασίας κειμένου ή λογιστικά προγράμματα, ενισχύοντας τις δυνατότητες σας για επεξεργασία κειμένου.
*   **Γενικά εγγυαμάτα και debugging**: Μετατροπή των αρχείων CGM σε μορφή κειμένου απλό, για να δημιουργηθούν βασικές ανακοινώσεις και λоги debug, που βοηθούν στον εντοπισμό τροφών και προβλημάτων κατά τη διαδικασία ανάπτυξης.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}