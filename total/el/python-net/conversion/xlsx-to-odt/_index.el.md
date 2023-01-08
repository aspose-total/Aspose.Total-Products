---
title: Μετατροπή XLSX σε ODT χρησιμοποιώντας Python
description: Μετατροπή XLSX σε ODT στις εφαρμογές Python σας χωρίς τη χρήση του Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή XLSX σε ODT μέσω Python" h2="Μετατροπή XLSX σε ODT στις εφαρμογές σας Python χωρίς εγκατάσταση του Microsoft Excel<sup>&reg;</sup> ή του Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή Python, ο οποίος προσπαθεί να προσθέσει μια δυνατότητα μετατροπής XLSX σε ODT εντός της εφαρμογής. Το [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας μετατροπής. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές, συμπεριλαμβανομένων αρχείων XLSX και ODT.

Είναι κυρίως σε δύο βήματα. Αρχικά χρησιμοποιήστε το [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API για να μετατρέψετε το αρχείο XLSX σε HTML. Στη συνέχεια, χρησιμοποιώντας το Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), αποθηκεύστε το HTML που δημιουργήθηκε στην επιθυμητή μορφή Microsoft Word. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το XLSX σε ODT στην Python" %}}
- **Βήμα 1** Ανοίξτε το αρχείο προέλευσης XLSX χρησιμοποιώντας την κλάση Workbook
- Αποθηκεύστε το αρχείο XLSX σε HTML χρησιμοποιώντας τη μέθοδο save(file, SaveFormat.HTML) παρέχοντας το όνομα του αρχείου και την επιθυμητή διαδρομή καταλόγου
-  **Βήμα 2** Φόρτωση αρχείου HTML με μια παρουσία της κλάσης [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Καλέστε τη μέθοδο «αποθήκευση» ενώ καθορίζετε τη διαδρομή του αρχείου ODT εξόδου. Έτσι, το αρχείο XLSX μετατρέπεται σε ODT στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

- Για τη μετατροπή XLSX σε ODT, απαιτείται Python 3.5 ή νεότερη έκδοση
- Αναφορά API εντός του έργου απευθείας από το PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) και [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Ή χρησιμοποιήστε τις ακόλουθες εντολές pip ```pip install aspose-cells-python``` και ```pip install aspose.words```
-  Επιπλέον, το λειτουργικό σύστημα Microsoft Windows ή Linux (δείτε περισσότερα για [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) και [Words](https://docs.aspose.com/words/python-net/system-requirements/)) και για Linux ελέγξτε τις πρόσθετες απαιτήσεις για gcc και libpython και ακολουθήστε το [οδηγίες βήμα προς βήμα](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση XLSX σε HTML στην Python - Βήμα 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση HTML σε ODT στην Python - Βήμα 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-word/" name="XLSX Προς την WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-doc/" name="XLSX Προς την DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-docx/" name="XLSX Προς την DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-docm/" name="XLSX Προς την DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-dot/" name="XLSX Προς την DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-dotm/" name="XLSX Προς την DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-dotx/" name="XLSX Προς την DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-mobi/" name="XLSX Προς την MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-odt/" name="XLSX Προς την ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-ott/" name="XLSX Προς την OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-rtf/" name="XLSX Προς την RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/xlsx-to-wordml/" name="XLSX Προς την WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}