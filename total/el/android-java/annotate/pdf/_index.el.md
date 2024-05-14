---
title: Καταργήστε το PDF Annotation Online ή διαχειριστείτε τους σχολιασμούς χρησιμοποιώντας τις εφαρμογές Android για κινητά
description: διαγράψτε σχόλια από το αρχείο PDF μέσω της διαδικτυακής εφαρμογής δωρεάν.Κώδικας API Android για διαχείριση σχολίων αρχείων PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Εκκαθάριση σχολίων από το PDF Document Online ή Διαχείριση μέσω εφαρμογών Android" h2="Αναπτύξτε μια ισχυρή εφαρμογή βοηθητικού προγράμματος σχολιασμού εγγράφων PDF που βασίζεται σε Android.Κωδικός που παρατίθεται για τη διαχείριση σχολίων του αρχείου PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Κατάργηση PDF Annotations Online" %}}

1. Εισαγάγετε το αρχείο PDF για να διαγράψετε σχόλια ανεβάζοντάς το
1. Κάντε το κάνοντας κλικ μέσα στην περιοχή απόθεσης μέσω μεταφοράς και απόθεσης της εφαρμογής σχολιασμού
1. Ανάλογα με το μέγεθος του αρχείου PDF και την ταχύτητα του Διαδικτύου, περιμένετε μερικά δευτερόλεπτα
1. Κάντε κλικ στο κουμπί "Κατάργηση" για να διαγράψετε τα σχόλια
1. Κατεβάστε το αρχείο άμεσα

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Καταργήστε τα σχόλια του εγγράφου PDF μέσω του API της εφαρμογής Android" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Android
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Επιλέξτε τη συγκεκριμένη σελίδα μέσω getPages().get_Item(Index)
1. Χρησιμοποιήστε το AnnotationSelector και λάβετε όλους τους σχολιασμούς κειμένου μέσω annotationSelector.getSelected()
1. Επαναλάβετε σε κάθε σχολιασμό και καλέστε τη μέθοδο διαγραφής για να την αφαιρέσετε.
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Διαγραφή σχολίων από το αρχείο PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Προσθήκη σχολιασμού μέσω του API εφαρμογής Android" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Android
1. Δημιουργία αντικειμένου κλάσης εγγράφου
1. Προσθέστε τη νέα σελίδα και το περιεχόμενο χρησιμοποιώντας το getPages().add()
1. Χρησιμοποιήστε getPages().get_Item(Index) της κλάσης TextAnnotation
1. Ορίστε τους σχετικούς σχολιασμούς όπως τίτλος, θέμα, περιεχόμενο κ.λπ
1. Χρησιμοποιήστε το getAnnotations().add για να προσθέσετε τους σχολιασμούς
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο με πρόσθετα σχόλια
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Προσθήκη σχολιασμού PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Αναπτύξτε την εφαρμογή Android Annotation PDF Document</h2>

Χρειάζεστε να αναπτύξετε μια εφαρμογή ή βοηθητικό πρόγραμμα σχολιασμού PDF για κινητά για να παρέχετε σχόλια, να κάνετε προτάσεις ή να συνεργαστείτε με άλλους στο έγγραφο;Με το [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/el/android-java/) ένα θυγατρικό API του [Aspose.Total for Android via Java](https://products.aspose.com/total/el/android-java/), οποιοσδήποτε προγραμματιστής Android μπορεί να ενσωματώσει τον παραπάνω κώδικα API στην εφαρμογή σχολιασμού εγγράφων του.Η ισχυρή βιβλιοθήκη Android επιτρέπει τον προγραμματισμό οποιασδήποτε λύσης σχολιασμού εγγράφων.Επιπλέον, μπορεί να υποστηρίξει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Βιβλιοθήκη Android για σχολιασμό αρχείων PDF" %}}

- Φιλοξενούμε τα πακέτα Java μας σε [Αποθετήρια Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Το Aspose.PDF for Java είναι ένα κοινό αρχείο JAR που περιέχει κώδικα byte.
- Ακολουθήστε το [οδηγίες βήμα προς βήμα](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) σχετικά με τον τρόπο εγκατάστασης του Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

- Android API 31 και 32
- Android 4.0 και νεότερη έκδοση
- Εργαλεία Android Studio και SDK

<br />
Για περισσότερες λεπτομέρειες σχετικά με τις προαιρετικές εξαρτήσεις πακέτων, όπως JogAmp JOGL, μηχανή γραμματοσειρών Harfbuzz, Java Advanced Imaging JAI, ανατρέξτε στο [Τεκμηρίωση προϊόντος](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}