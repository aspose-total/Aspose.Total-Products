---
title: Μετατροπή CGM σε XLSB μέσω C# API
description: C# API για μετατροπή αρχείου CGM σε XLSB χωρίς χρήση του Microsoft Excel ή του Adobe Reader
url_ignore: /el/net/conversion/cgm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSB
otherformats: XLSB TSV XLTX ODS XLSM XLT XLTM EXCEL SXC TXT FODS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API για απόδοση CGM σε XLSB" h2="Εξαγωγή αρχείου CGM σε XLSB μέσω C# χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να μετατρέψετε το αρχείο CGM σε XLSB σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το CGM στο XLSX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, μπορείτε να μετατρέψετε το XLSX σε XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή CGM σε XLSB" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το CGM σε XLSX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το έγγραφο XLSX χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLSB χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) και ορίστε το "Xlsb" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή προστατευμένου CGM σε XLSB μέσω C#" %}}
Εάν το έγγραφό σας CGM προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLSB χωρίς τον κωδικό πρόσβασης. Χρησιμοποιώντας το API, μπορείτε πρώτα να ανοίξετε το προστατευμένο έγγραφο χρησιμοποιώντας έναν έγκυρο κωδικό πρόσβασης και να το μετατρέψετε μετά από αυτόν. Για να ανοίξετε το κρυπτογραφημένο αρχείο, μπορείτε να αρχικοποιήσετε μια νέα παρουσία της κλάσης [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να μεταβιβάσετε το όνομα αρχείου και τον κωδικό πρόσβασης ως ορίσματα.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε XLSB με υδατογράφημα μέσω C#" %}}
Κατά τη μετατροπή του αρχείου CGM σε XLSB, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLSB. Για να προσθέσετε ένα υδατογράφημα, μπορείτε να δημιουργήσετε ένα νέο αντικείμενο βιβλίου εργασίας και να ανοίξετε το έγγραφο XLSX που μετατράπηκε, να επιλέξετε φύλλο εργασίας μέσω του ευρετηρίου του, να δημιουργήσετε ένα σχήμα και να χρησιμοποιήσετε τη συνάρτηση AddTextEffect. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας XLSX ως XLSB με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε XLSB μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Αξιοποιούμενα προς την πλήρη εκμελώς του δυναμικού σας πεδίο viz και analysis, τα αρχεία CGM (Computer Graphics Metafile) χρησιμοποιούνται για το αποθήκες πληροφορούμενα σχετικά με vector graphics, γεγονότα ιδανικά για τη δημιουργία στατικού γραφικού και εικονογραφίας. Ωστόσο, όταν εργάζονται με δεδομένα που αλλάζουν, πράγματι, τα εγγυπεύματα όπως το Excel γίνονται απαραίτητα για την εικονιζήση και analysis δεδομένων.

Η μετατροπή των αρχείων CGM σε μορφές Excel είναι απαραίτητη για να ενεργοποιήσετε πλήρως τις δυναμικές σας abilities για viz και analysis. Η αυτή μετατροπή επιτρέπει:

**Πωλές χρήσης:**

*   **Ανανέωση γραφικού στατικού**: Μετατρέψτε τα αρχεία CGM για να δημιουργήσετε εποπτόστατη γραφική, λογότυπα και ikons με πιθανότητα ελέγχου ακριβούς για χρώματα, σχήματα και μέγεθες.
*   **Επεξεργασία εικονογραφίας**: Χρησιμοποιήστε το Excel για επεξεργασία vector graphics, συνένωση εικόνων και προσθήκη κειμένου ή εφέλων για ενισχυσμό εικονογραφίας και περιεχομένου viz.
*   **Σχεδίαση εντυπωτικών δελτίων και layout**: Μετατρέψτε τα αρχεία CGM για να δημιουργήσετε διαδραστικά σχέδια δελτίου, συντονίζοντας το περιεχόμενο και προσαρτώντας εύκολα το layout.
*   **Δημιουργία infografik**: Χρησιμοποιήστε το Excel για τη δημιουργία ενδιαφέροντος infografik, οργάνωση δεδομένων και viz ελικότητων σύνθετης πληροφορίας σε μια εφικλή και συντομεμένη μορφή.
*   **Γενέρωση στατικού απολογισμού**: Μετατρέψτε τα αρχεία CGM για να δημιουργήσετε διαδραστικούς απολογισμούς, παρακολουθήστε κρίσιμες επιδόσεις (KPIs) και δημιουργήσετε υψηλής ποιότητας viz για εμβλημάκια επιχειρήσεων.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}