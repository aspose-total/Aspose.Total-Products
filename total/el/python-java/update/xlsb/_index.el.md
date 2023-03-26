---
title: Ενημερώστε το αρχείο XLSB χρησιμοποιώντας Python
description: Τροποποιήστε το έγγραφο XLSB σε εφαρμογές Python χωρίς τη χρήση του Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ενημερώστε το αρχείο XLSB μέσω Python" h2="Τροποποιήστε τα υπολογιστικά φύλλα XLSB μέσω των εφαρμογών Python χωρίς να εγκαταστήσετε το Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή, που προσπαθεί να ενημερώσει αρχεία XLSB μέσω της εφαρμογής Python; Το [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας ενημέρωσης. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές, συμπεριλαμβανομένων αρχείων Microsoft Excel. Το ASPOSE.CELL API που αποτελεί μέρος του πακέτου [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) καθιστά εύκολη αυτή τη διαδικασία τροποποίησης. Ακολουθεί η διαδικασία ενημέρωσης του εγγράφου XLSB.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να ενημερώσετε το αρχείο XLSB στην Python" %}}

- Δημιουργήστε νέο αντικείμενο κλάσης [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) με παράμετρο το αρχείο προέλευσης XLSB
- Πρόσβαση στο σχετικό φύλλο εργασίας με τη μέθοδο [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Εισαγάγετε νέα δεδομένα στο κελί στο οποίο έχετε πρόσβαση χρησιμοποιώντας τη μέθοδο [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Αποθηκεύστε το αρχείο ως αρχείο .xlsb χρησιμοποιώντας τη μέθοδο save() περνώντας το αρχείο με τη διαδρομή ως παράμετρο

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις Τροποποίησης" %}}

- Για τροποποίηση XLSB, αναφέρετε τα API εντός του έργου απευθείας από το PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ή χρησιμοποιήστε την ακόλουθη εντολή pip ```pip install aspose.cells``` 
- Επιπλέον, κατεβάστε το πακέτο API από την ενότητα [Λήψεις](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κώδικας - Ενημέρωση αρχείου XLSB στην Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}