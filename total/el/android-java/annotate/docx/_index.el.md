---
title: Καταργήστε το DOCX Annotation Online ή διαχειριστείτε τους σχολιασμούς χρησιμοποιώντας τις εφαρμογές Android για κινητά
description: διαγράψτε σχόλια από το αρχείο DOCX μέσω της διαδικτυακής εφαρμογής δωρεάν.Κώδικας API Android για διαχείριση σχολίων αρχείων DOCX.

family: total
platformtag: Android
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Εκκαθάριση σχολίων από το DOCX Document Online ή Διαχείριση μέσω εφαρμογών Android" h2="Αναπτύξτε μια ισχυρή εφαρμογή βοηθητικού προγράμματος σχολιασμού εγγράφων DOCX που βασίζεται σε Android.Ο κωδικός παρατίθεται για τη διαχείριση σχολίων του αρχείου DOCX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Κατάργηση DOCX Annotations Online" %}}

1. Εισαγάγετε το αρχείο DOCX για να διαγράψετε σχόλια ανεβάζοντάς το
1. Κάντε το κάνοντας κλικ μέσα στην περιοχή απόθεσης μέσω μεταφοράς και απόθεσης της εφαρμογής σχολιασμού
1. Ανάλογα με το μέγεθος του αρχείου DOCX και την ταχύτητα του Διαδικτύου, περιμένετε μερικά δευτερόλεπτα
1. Κάντε κλικ στο κουμπί "Κατάργηση" για να διαγράψετε τα σχόλια
1. Κατεβάστε το αρχείο άμεσα

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Καταργήστε τα σχόλια του εγγράφου DOCX μέσω της εφαρμογής Android" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Android
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Λάβετε όλα τα σχόλια από όλους τους κόμβους χρησιμοποιώντας [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) και NodeType.COMMENT
1. Επικαλέστε τη μέθοδο [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) για να διαγράψετε όλα τα σχόλια
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Διαγραφή σχολίων από το αρχείο DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Αφαιρέστε και προσθέστε την απάντηση σχολίου DOCX" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Android
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Λάβετε σχόλια χρησιμοποιώντας το getChild
1. Χρησιμοποιήστε το [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) για την κατάργηση της καθορισμένης απάντησης σε αυτό το σχόλιο
1. Χρησιμοποιήστε το [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) για να προσθέσετε οποιαδήποτε απάντηση σε αυτό το σχόλιο
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Προσθήκη σχολίων μέσω της εφαρμογής Android" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Android
1. Δημιουργία αντικειμένου κλάσης εγγράφου
1. Χρησιμοποιήστε το [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) για να δημιουργήσετε το σχόλιο
1. Χρησιμοποιήστε getParagraphs().add και getFirstParagraph().getRuns().add
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Αφαίρεση και προσθήκη σχολίου απάντησης από το αρχείο DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Κωδικός: Προσθήκη σχολίων" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Αναπτύξτε την εφαρμογή Android Annotation DOCX Document</h2>

Χρειάζεστε να αναπτύξετε μια εφαρμογή ή βοηθητικό πρόγραμμα σχολιασμού DOCX για κινητά για να παρέχετε σχόλια, να κάνετε προτάσεις ή να συνεργαστείτε με άλλους στο έγγραφο;Με το [Aspose.Words for Android via Java](https://products.aspose.com/words/el/android-java/) ένα θυγατρικό API του [Aspose.Total for Android via Java](https://products.aspose.com/total/el/android-java/), οποιοσδήποτε προγραμματιστής Android μπορεί να ενσωματώσει τον παραπάνω κώδικα API στην εφαρμογή σχολιασμού εγγράφων του.Η ισχυρή βιβλιοθήκη Android επιτρέπει τον προγραμματισμό οποιασδήποτε λύσης σχολιασμού εγγράφων.Επιπλέον, μπορεί να υποστηρίξει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Βιβλιοθήκη Android για σχολιασμό αρχείων DOCX" %}}

- Φιλοξενούμε τα πακέτα Java μας σε [Αποθετήρια Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Το Aspose.Words for Java είναι ένα κοινό αρχείο JAR που περιέχει κώδικα byte.
- Ακολουθήστε το [οδηγίες βήμα προς βήμα](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) για τον τρόπο εγκατάστασης του Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

- Υποστηρίζονται Java SE 7 και πιο πρόσφατες εκδόσεις Java.
- Ξεχωριστό πακέτο για Java SE 6 σε περίπτωση που κάποιος υποχρεούται να χρησιμοποιήσει ξεπερασμένο JRE.
- Το πακέτο Java είναι cross-platform και τρέχει σε όλα τα λειτουργικά συστήματα με υλοποίηση JVM.
- Τα λειτουργικά συστήματα περιλαμβάνουν τα Microsoft Windows, Linux, macOS, Android και iOS.

<br />
Για περισσότερες λεπτομέρειες σχετικά με τις προαιρετικές εξαρτήσεις πακέτων, όπως JogAmp JOGL, μηχανή γραμματοσειρών Harfbuzz, Java Advanced Imaging JAI, ανατρέξτε στο [Τεκμηρίωση προϊόντος](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}