---
title: Μετατροπή CGM σε XLSM μέσω C# API
description: C# API για μετατροπή αρχείου CGM σε XLSM χωρίς χρήση του Microsoft Excel ή του Adobe Reader
url_ignore: /el/net/conversion/cgm-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSM
otherformats: XLSB XLT XLTX XLSM XLAM XLTM MD TSV EXCEL TXT ODS FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για απόδοση CGM σε XLSM" h2="Εξαγωγή αρχείου CGM σε XLSM μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να μετατρέψετε το αρχείο CGM σε XLSM σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το CGM στο XLSX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε το XLSX σε XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή CGM σε XLSM" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το CGM σε XLSX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLSM χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "Xlsm" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου CGM σε XLSM μέσω C#" %}}
Εάν το έγγραφό σας CGM προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLSM χωρίς τον κωδικό πρόσβασης. Χρησιμοποιώντας το API, μπορείτε πρώτα να ανοίξετε το προστατευμένο έγγραφο χρησιμοποιώντας έναν έγκυρο κωδικό πρόσβασης και να το μετατρέψετε μετά από αυτόν. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε μια νέα παρουσία της κλάσης [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να μεταβιβάσετε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε XLSM με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου CGM σε XLSM, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLSM. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο XLSX που μετατράπηκε, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη συνάρτηση AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας XLSX ως XLSM με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε XLSM μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Ενεργοποιώντας τη μετάδοση αρχιτεκτονικής CGM (Computer Graphics Metafile) σε μορφή XLSM (Excel Smart Document), απελευθερώνουμε την πλήρη δυναμική των δυνατοτήτων vizualizzation και analysis δεδομένων σας. Η αυτή μεταφορά επιτρέπει:

**Περιπτώσεις χρήσης:**

* **Σχεδίαση προϊόντων και Προσχεδισμό**: Μετατροπή αρχιτεκτονικών CGM σε διαδραματικούς 3D μονόλους προϊόντων, υπολογισμό εμπειρικής εμπειρίας χρηστών και εγκυρότητα σχεδίων σας στην Excel.

* **Επιστημονική έρευνα και analysis**: Χρήση XLSM για vizualizzation σύνθετης επιστημονικής δεδομένων, όπως αποτελέσματα πειραμάτων, outputs συμυλογιστών και 3D μονόλους, ενισχύοντας την κατανόηση και τη λήψη αποφάσεων.

* **Βιζουαλιστική επιχειρησιακή και Αναφορά**: Μετατροπή αρχιτεκτονικών CGM σε διαδραματικούς πίνακες εικονωνεύσεων, αναφορές και vizualizzation για τους συνεργάτες σας στην Excel Smart Document.

* **Μαρκετίνγκ και ανάλυση πωλήσεων**: Χρήση XLSM για vizualizzation δεδομένων συμπεριλαμβανομένου του πωητικού προφίλ, παρακολούθησης τάσεων πωλήσεων και αναγνώρισης μοτίβων επιτυχίας καμπάνιας μάρκετινγκ.

* **Αρχιτεκτονική και Μηχανική Σχεδίαση**: Μετατροπή αρχιτεκτονικών CGM σε διαδραματικούς μονόλους κατασκευών, υπολογισμό δοσιοτικής σταθερότητας και analysis επιφάνειας και επιδόσεων σε Excel.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}