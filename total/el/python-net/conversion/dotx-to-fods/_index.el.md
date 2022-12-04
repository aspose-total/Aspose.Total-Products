---
title: Μετατροπή DOTX σε FODS χρησιμοποιώντας Python
description: Μετατροπή DOTX σε FODS στις εφαρμογές Python σας χωρίς τη χρήση Microsoft Word ή Excel 

family: total
platformtag: Python
feature: conversion
informat: DOTX
outformat: FODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή DOTX σε FODS μέσω Python" h2="Μετατροπή DOTX σε FODS στις εφαρμογές σας Python χωρίς εγκατάσταση του Microsoft Word<sup>&reg;</sup> ή του Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή Python, ο οποίος προσπαθεί να προσθέσει μια δυνατότητα μετατροπής DOTX σε FODS εντός της εφαρμογής. Το [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας μετατροπής. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές.

Είναι κυρίως σε δύο βήματα. Αρχικά χρησιμοποιήστε το [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API για να μετατρέψετε το αρχείο DOTX σε HTML. Στη συνέχεια, χρησιμοποιώντας το Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), αποθηκεύστε το HTML που δημιουργήθηκε στην επιθυμητή μορφή Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το DOTX σε FODS στην Python" %}}
- **Βήμα 1** Ανοίξτε το αρχείο προέλευσης DOTX χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Αποθηκεύστε το αρχείο DOTX σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) παρέχοντας το όνομα του αρχείου και την επιθυμητή διαδρομή καταλόγου
-  **Βήμα 2** Φόρτωση αρχείου HTML με μια παρουσία κλάσης Βιβλίου εργασίας με αρχείο και LoadOptions ως παραμέτρους
-  Καλέστε τη μέθοδο «αποθήκευση» ενώ καθορίζετε τη διαδρομή του αρχείου FODS εξόδου. Έτσι, το αρχείο DOTX μετατρέπεται σε FODS στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

- Για τη μετατροπή DOTX σε FODS, απαιτείται Python 3.5 ή νεότερη έκδοση
- Αναφορά API εντός του έργου απευθείας από το PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) και [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Ή χρησιμοποιήστε τις ακόλουθες εντολές pip ```pip install aspose.words``` και ```pip install aspose-cells-python``` 
-  Επιπλέον, το λειτουργικό σύστημα Microsoft Windows ή Linux (δείτε περισσότερα για [Words](https://docs.aspose.com/words/python-net/system-requirements/) και [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) και για Linux ελέγξτε τις πρόσθετες απαιτήσεις για gcc και libpython και ακολουθήστε το [οδηγίες βήμα προς βήμα](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση DOTX σε HTML στην Python - Βήμα 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση HTML σε FODS στην Python - Βήμα 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}