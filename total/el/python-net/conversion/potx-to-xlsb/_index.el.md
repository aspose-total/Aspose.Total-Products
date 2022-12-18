---
title: Μετατροπή POTX σε XLSB χρησιμοποιώντας Python
description: Μετατροπή POTX σε XLSB στις εφαρμογές Python σας χωρίς τη χρήση του Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: POTX
outformat: XLSB
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή POTX σε XLSB μέσω Python" h2="Μετατροπή POTX σε XLSB στις εφαρμογές Python χωρίς εγκατάσταση του Microsoft PowerPoint<sup>&reg;</sup> ή του Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή Python, ο οποίος προσπαθεί να προσθέσει μια δυνατότητα μετατροπής POTX σε XLSB εντός της εφαρμογής. Το [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας μετατροπής. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές, συμπεριλαμβανομένων αρχείων POTX και XLSB.

Είναι κυρίως σε δύο βήματα. Αρχικά χρησιμοποιήστε το [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API για να μετατρέψετε το αρχείο POTX σε HTML. Στη συνέχεια, χρησιμοποιώντας το Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), αποθηκεύστε το HTML που δημιουργήθηκε στην επιθυμητή μορφή Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το POTX σε XLSB στην Python" %}}
- **Βήμα 1** Χρησιμοποιήστε την παρουσία κλάσης [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) για να ανοίξετε το αρχείο προέλευσης POTX 
- Αποθηκεύστε το αρχείο POTX σε HTML χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) παρέχοντας το όνομα του αρχείου και την επιθυμητή διαδρομή καταλόγου
-  **Βήμα 2** Φόρτωση αρχείου HTML με μια παρουσία της κλάσης Workbook
-  Καλέστε τη μέθοδο «αποθήκευση» ενώ καθορίζετε τη διαδρομή του αρχείου XLSB εξόδου. Έτσι, το αρχείο POTX μετατρέπεται σε XLSB στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

- Για τη μετατροπή POTX σε XLSB, απαιτείται Python 3.5 ή νεότερη έκδοση
- Αναφορά API εντός του έργου απευθείας από το PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) και [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Ή χρησιμοποιήστε τις ακόλουθες εντολές pip ```pip install aspose.slides``` και ```pip install aspose-cells-python```
-  Επιπλέον, λειτουργικό σύστημα που βασίζεται σε Microsoft Windows ή Linux (δείτε περισσότερα για [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) και [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση POTX σε HTML στην Python - Βήμα 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση HTML σε XLSB στην Python - Βήμα 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}