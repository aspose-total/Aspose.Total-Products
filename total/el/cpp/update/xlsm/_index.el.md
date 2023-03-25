---
title: Ενημερώστε το αρχείο XLSM χρησιμοποιώντας C++
description: Τροποποιήστε το έγγραφο XLSM σε εφαρμογές C++ χωρίς τη χρήση του Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ενημερώστε το αρχείο XLSM μέσω C++" h2="Τροποποιήστε τα υπολογιστικά φύλλα XLSM μέσω των εφαρμογών σας που βασίζονται στη C++ χωρίς να εγκαταστήσετε το Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή, ο οποίος προσπαθεί να ενημερώσει αρχεία XLSM εντός της εφαρμογής C++, Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας ενημέρωσης. Είναι ένα πλήρες πακέτο διαφορετικών βιβλιοθηκών C++ που ασχολούνται με πολλαπλές μορφές, συμπεριλαμβανομένων των εγγράφων του Microsoft Excel. Το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API που αποτελεί μέρος του πακέτου [Aspose.Total for C++](https://products.aspose.com/total/cpp/) κάνει αυτή τη διαδικασία τροποποίησης εύκολη. Η διαδικασία ενημέρωσης του εγγράφου XLSM είναι απλή αφού πρώτα αποκτήσετε πρόσβαση στο φύλλο και στη συνέχεια ενημερώστε την τιμή του κελιού στο excel χρησιμοποιώντας C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να ενημερώσετε το αρχείο XLSM σε C++" %}}

- Φορτώστε το αρχείο XLSM χρησιμοποιώντας το [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Πρόσβαση σε σχετικό [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) χρησιμοποιώντας GetIWorksheets()->GetObjectByIndex(0) και σχετικό κελί χρησιμοποιώντας GetICells()->GetObjectByIndex
- Εισαγάγετε νέα δεδομένα στο κελί στο οποίο έχετε πρόσβαση χρησιμοποιώντας τη μέθοδο PutValue
- Αποθηκεύστε το αρχείο ως αρχείο .xlsm χρησιμοποιώντας τη μέθοδο Save περνώντας το αρχείο με τη διαδρομή ως παράμετρο

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις Τροποποίησης" %}}

- Για τροποποίηση XLSM, ακολουθώντας το [Απαιτήσεις συστήματος](https://docs.aspose.com/cells/cpp/system-requirements/) για συστήματα Windows και Linux 
- Εγκατάσταση από τη γραμμή εντολών ως ``` nuget install Aspose.Total.Cpp```
- Ή μέσω της κονσόλας Package Manager του Visual Studio με ```Install-Package Aspose.Total.Cpp```
- Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [Λήψεις](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κώδικας - Ενημερώστε το αρχείο XLSM σε C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}