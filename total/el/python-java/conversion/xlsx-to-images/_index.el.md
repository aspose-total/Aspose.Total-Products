---
title: Μετατροπή XLSX σε Εικόνα χρησιμοποιώντας Python
description: Μετατροπή XLSX σε εικόνα TIFF BMP PNG JPEG GIF EMF SVG στις εφαρμογές Python σας χωρίς τη χρήση του Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή XLSX σε Εικόνα μέσω Python" h2="Μετατροπή εικόνων XLSX σε JPG, TIFF, BMP, PNG, GIF στις εφαρμογές σας Python χωρίς εγκατάσταση του Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή Python, ο οποίος προσπαθεί να προσθέσει ένα XLSX στη δυνατότητα μετατροπής εικόνας PNG, BMP, TIFF, JPEG και GIF εντός της εφαρμογής. Καθώς μερικές φορές απαιτείται η ενσωμάτωση υπολογιστικών φύλλων του Excel σε εφαρμογές ιστού ή επιτραπέζιου υπολογιστή. Σε τέτοιες περιπτώσεις, η εξαγωγή υπολογιστικών φύλλων σε εικόνες είναι η μοναδική. Το [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API μπορεί να βοηθήσει στην εξαγωγή αρχείων Excel σε εικόνες καθώς και στην αυτοματοποίηση της διαδικασίας μετατροπής. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές, συμπεριλαμβανομένων μορφών Microsoft Excel μέσω του θυγατρικού του [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API. Επί του παρόντος, το Python Excel σε Image Converter API υποστηρίζει τη μετατροπή αρχείων Excel σε EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM και EMF συμβατό με το Office ή ελέγξτε το υποστηριζόμενο [Μορφές](https://docs.aspose.com/cells/python-java/supported-file-formats/). 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το XLSX σε εικόνες στην Python" %}}

- Δημιουργήστε αντικείμενο κλάσης [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) για να φορτώσετε το αρχείο XLSX
- Χρησιμοποιήστε την κλάση [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) και καθορίστε τις σχετικές επιλογές της εικόνας εξόδου
- Αποκτήστε πρόσβαση στο φύλλο εργασίας για μετατροπή χρησιμοποιώντας τη μέθοδο [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Αποθηκεύστε όλες τις σελίδες του φύλλου εργασίας ως εικόνα χρησιμοποιώντας τη μέθοδο [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Τώρα το αρχείο XLSX μετατρέπεται σε Εικόνες στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

- Για μετατροπή XLSX σε Εικόνες (JPG, PNG, GIF, BMP, TIFF), αναφέρετε τα API εντός του έργου απευθείας από το PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ή χρησιμοποιήστε την ακόλουθη εντολή pip ```pip install aspose.cells``` 
- Επιπλέον, κατεβάστε το πακέτο API από την ενότητα [Λήψεις](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Μετατροπή XLSX σε εικόνες μέσω Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}