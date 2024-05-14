---
title: Καταργήστε το XLTM Annotation Online ή διαχειριστείτε τους σχολιασμούς χρησιμοποιώντας τις εφαρμογές Android για κινητά
description: διαγράψτε σχόλια από το αρχείο XLTM μέσω της διαδικτυακής εφαρμογής δωρεάν.Κώδικας API Android για διαχείριση σχολίων αρχείων XLTM.

family: total
platformtag: Android
feature: Annotate
informat: XLTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Εκκαθάριση σχολίων από το XLTM Document Online ή Διαχείριση μέσω εφαρμογών Android" h2="Αναπτύξτε μια ισχυρή εφαρμογή βοηθητικού προγράμματος σχολιασμού εγγράφων XLTM που βασίζεται σε Android.Κωδικός που παρατίθεται για τη διαχείριση σχολίων του αρχείου XLTM." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Κατάργηση XLTM Annotations Online" %}}

1. Εισαγάγετε το αρχείο XLTM για να διαγράψετε σχόλια ανεβάζοντάς το
1. Κάντε το κάνοντας κλικ μέσα στην περιοχή απόθεσης μέσω μεταφοράς και απόθεσης της εφαρμογής σχολιασμού
1. Ανάλογα με το μέγεθος του αρχείου XLTM και την ταχύτητα του Διαδικτύου, περιμένετε μερικά δευτερόλεπτα
1. Κάντε κλικ στο κουμπί "Κατάργηση" για να διαγράψετε τα σχόλια
1. Κατεβάστε το αρχείο άμεσα

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Καταργήστε τα σχόλια του εγγράφου XLTM μέσω του API της εφαρμογής Android" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Android
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης βιβλίου εργασίας
1. Επιλέξτε το συγκεκριμένο φύλλο εργασίας
1. Λάβετε όλα τα σχόλια από τη χρήση του [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Λάβετε όλα τα σχόλια με νήματα μέσω getThreadedComments
1. Χρησιμοποιήστε removeAt για να αφαιρέσετε σχόλια και συγγραφείς αντίστοιχα
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Κατάργηση σχολίων από το έγγραφο XLTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ενημέρωση σχολίων XLTM με νήματα" %}}

1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης βιβλίου εργασίας
1. Λάβετε το συγκεκριμένο φύλλο εργασίας
1. Λάβετε το σχολιασμό με νήματα χρησιμοποιώντας το getComments().getThreadedComments(Index).get(Index)
1. Χρησιμοποιήστε τη μέθοδο setNotes για να ενημερώσετε το σχόλιο
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Προσθήκη σχολίων μέσω του API της εφαρμογής Android" %}}

1. Δημιουργία εγγράφου μέσω αντικειμένου κλάσης βιβλίου εργασίας
1. Λάβετε το συγκεκριμένο φύλλο εργασίας
1. Προσθήκη ευρετηρίου σχολίων μέσω getComments().add
1. Χρησιμοποιήστε τη μέθοδο setNotes για να προσθέσετε σχόλιο
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Ενημέρωση σχολίου με νήματα του αρχείου XLTM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Προσθήκη σχολίων" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Αναπτύξτε την εφαρμογή Android Annotation XLTM Document</h2>

Χρειάζεστε να αναπτύξετε μια εφαρμογή ή βοηθητικό πρόγραμμα σχολιασμού XLTM που βασίζεται στο Android για να παρέχετε σχόλια, να κάνετε προτάσεις ή να συνεργαστείτε με άλλους στο έγγραφο;Με το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/el/android-java/) ένα θυγατρικό API του [Aspose.Total for Android via Java](https://products.aspose.com/total/el/android-java/), οποιοσδήποτε προγραμματιστής Android μπορεί να ενσωματώσει τον παραπάνω κώδικα API στην εφαρμογή σχολιασμού εγγράφων του.Η ισχυρή βιβλιοθήκη Android επιτρέπει τον προγραμματισμό οποιασδήποτε λύσης σχολιασμού εγγράφων.Επιπλέον, μπορεί να υποστηρίξει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής XLTM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για σχολιασμό αρχείων XLTM" %}}

- Φιλοξενούμε τα πακέτα Java μας σε [Αποθετήρια Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Το Aspose.Cells for Java είναι ένα κοινό αρχείο JAR που περιέχει byte-code.
- Ακολουθήστε το [οδηγίες βήμα προς βήμα](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) σχετικά με τον τρόπο εγκατάστασης του Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

- Android OS 2.0 ή νεότερη έκδοση.
- Το πακέτο Java είναι cross-platform και τρέχει σε όλα τα λειτουργικά συστήματα με υλοποίηση JVM.

<br />
Για περισσότερες λεπτομέρειες, ανατρέξτε στο [Τεκμηρίωση προϊόντος](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}