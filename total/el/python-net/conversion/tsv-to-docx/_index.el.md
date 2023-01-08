---
title: Μετατροπή TSV σε DOCX χρησιμοποιώντας Python
description: Μετατροπή TSV σε DOCX στις εφαρμογές Python σας χωρίς τη χρήση του Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: DOCX
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή TSV σε DOCX μέσω Python" h2="Μετατροπή TSV σε DOCX στις εφαρμογές σας Python χωρίς εγκατάσταση του Microsoft Excel<sup>&reg;</sup> ή του Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή Python, ο οποίος προσπαθεί να προσθέσει μια δυνατότητα μετατροπής TSV σε DOCX εντός της εφαρμογής. Το [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας μετατροπής. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές, συμπεριλαμβανομένων αρχείων TSV και DOCX.

Είναι κυρίως σε δύο βήματα. Αρχικά χρησιμοποιήστε το [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API για να μετατρέψετε το αρχείο TSV σε HTML. Στη συνέχεια, χρησιμοποιώντας το Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), αποθηκεύστε το HTML που δημιουργήθηκε στην επιθυμητή μορφή Microsoft Word. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το TSV σε DOCX στην Python" %}}
- **Βήμα 1** Ανοίξτε το αρχείο προέλευσης TSV χρησιμοποιώντας την κλάση Workbook
- Αποθηκεύστε το αρχείο TSV σε HTML χρησιμοποιώντας τη μέθοδο save(file, SaveFormat.HTML) παρέχοντας το όνομα του αρχείου και την επιθυμητή διαδρομή καταλόγου
-  **Βήμα 2** Φόρτωση αρχείου HTML με μια παρουσία της κλάσης [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Καλέστε τη μέθοδο «αποθήκευση» ενώ καθορίζετε τη διαδρομή του αρχείου DOCX εξόδου. Έτσι, το αρχείο TSV μετατρέπεται σε DOCX στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

- Για τη μετατροπή TSV σε DOCX, απαιτείται Python 3.5 ή νεότερη έκδοση
- Αναφορά API εντός του έργου απευθείας από το PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) και [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Ή χρησιμοποιήστε τις ακόλουθες εντολές pip ```pip install aspose-cells-python``` και ```pip install aspose.words```
-  Επιπλέον, το λειτουργικό σύστημα Microsoft Windows ή Linux (δείτε περισσότερα για [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) και [Words](https://docs.aspose.com/words/python-net/system-requirements/)) και για Linux ελέγξτε τις πρόσθετες απαιτήσεις για gcc και libpython και ακολουθήστε το [οδηγίες βήμα προς βήμα](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση TSV σε HTML στην Python - Βήμα 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση HTML σε DOCX στην Python - Βήμα 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-word/" name="TSV Προς την WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-doc/" name="TSV Προς την DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-docx/" name="TSV Προς την DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-docm/" name="TSV Προς την DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-dot/" name="TSV Προς την DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-dotm/" name="TSV Προς την DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-dotx/" name="TSV Προς την DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-mobi/" name="TSV Προς την MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-odt/" name="TSV Προς την ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-ott/" name="TSV Προς την OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-rtf/" name="TSV Προς την RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/python-net/conversion/tsv-to-wordml/" name="TSV Προς την WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}