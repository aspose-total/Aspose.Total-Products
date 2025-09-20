---
title: Μετατροπή μορφής JSON σε CHM μέσω Java
description: Ανάλυση JSON σε CHM σε Java χωρίς χρήση του Microsoft Word
url_ignore: /el/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή μορφής JSON σε CHM μέσω Java" h2="On premise Java API για ανάλυση JSON σε CHM χωρίς χρήση Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να μετατρέψετε το JSON σε CHM στις εφαρμογές σας Java σε διαδικασία δύο βημάτων. Πρώτον, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/) μπορείτε να αναλύσετε το JSON σε PDF. Στο δεύτερο βήμα, μπορείτε να μετατρέψετε το PDF σε CHM χρησιμοποιώντας το API επεξεργασίας κειμένου [Aspose.Words για Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή μορφής JSON σε CHM μέσω Java" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Εισαγάγετε αρχείο JSON στο φύλλο εργασίας χρησιμοποιώντας την κλάση [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) και το [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) είναι PDF
3. Φορτώστε το έγγραφο PDF χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή CHM χρησιμοποιώντας [Αποθήκευση](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Επιπλέον, το API σάς επιτρέπει να ορίσετε επιλογές διάταξης για το JSON σας ενώ αναλύετε το JSON σε CHM χρησιμοποιώντας το [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Σας επιτρέπει να επεξεργαστείτε τον πίνακα ως πίνακα, να αγνοήσετε τα μηδενικά, να αγνοήσετε τον τίτλο του πίνακα, να αγνοήσετε τον τίτλο του αντικειμένου, να μετατρέψετε τη συμβολοσειρά σε αριθμό ή ημερομηνία, να ορίσετε την ημερομηνία και τη μορφή αριθμού και να ορίσετε στυλ τίτλου. Όλες αυτές οι επιλογές σάς επιτρέπουν να παρουσιάζετε τα δεδομένα σας σύμφωνα με τις ανάγκες σας. Το παρακάτω απόσπασμα κώδικα σάς δείχνει πώς να ορίσετε τις επιλογές διάταξης.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ρυθμίστε τη διάταξη και μετατρέψτε τη μορφή JSON σε CHM μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να αναλύσετε το JSON σε CHM με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας CHM, μπορείτε πρώτα να μετατρέψετε το αρχείο JSON σε PDF και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το αρχείο PDF που δημιουργήθηκε πρόσφατα χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), δημιουργήστε μια παρουσία του TextWatermarkOptions και ορίστε Οι ιδιότητές του, Καλέστε τη μέθοδο Watermark.setText και περάστε κείμενο υδατογραφήματος & αντικείμενο του TextWatermarkOptions. Αφού προσθέσετε το υδατογράφημα, μπορείτε να αποθηκεύσετε το έγγραφο στο CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Η μετατροπή **JSON σε CHM (Συγκεντρωμένη Βοήθεια HTML)** είναι ουσιώδης για τη δημιουργία **συγκεντρωμένων εγχειριδίων βοήθειας** απευθείας από δομημένη τεκμηρίωση. Τα αρχεία CHM συνδυάζουν πολλά θέματα βοήθειας σε ένα μόνο, αναζητήσιμο και προσβάσιμο εκτός σύνδεσης πόρο, κάνοντάς τα ιδανικά για την υποστήριξη λογισμικού και τη διαχείριση της επιχειρησιακής γνώσης. Μετατρέποντας το JSON σε CHM, οι οργανισμοί μπορούν να βελτιώσουν την παράδοση της τεκμηρίωσης, να βελτιώσουν τη χρησιμότητα και να εξασφαλίσουν την προσβασιμότητα ακόμα και χωρίς σύνδεση στο internet.

{{% blocks/products/pf/agp/feature-section-col title="Κύριες Χρήσεις" %}}

- **Τεκμηρίωση λογισμικού** – Συσκευάστε τεχνικούς οδηγούς σε συγκεντρωμένη, χρήστη-φιλική μορφή.
- **Συστήματα βοήθειας εκτός σύνδεσης** – Παράδοση τεκμηρίωσης χωρίς ανάγκη πρόσβασης στο internet.
- **Βάσεις γνώσης επιχείρησης** – Κεντρική διαρθρωμένη τεκμηρίωση της οργανωσιακής γνώσης.
- **Εγχειρίδια εκπαίδευσης** – Διανείμετε συγκεντρωμένους πόρους μάθησης για το προσωπικό ή τους μαθητές.
- **Αναφορές API προγραμματιστών** – Μετατροπή δομημένων ορισμών JSON σε αναζητήσιμες εκτός σύνδεσης αναφορές.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Σενάρια Αυτοματισμού" %}}

- **Σωληνώσεις JSON-προς-CHM** – Αυτοματοποιήστε τη μετατροπή δομημένων δεδομένων σε συγκεντρωμένα εγχειρίδια βοήθειας.
- **Αυτόματη δημιουργία αρχείων βοήθειας** – Δημιουργήστε αρχεία CHM απευθείας από εξελισσόμενο περιεχόμενο βασισμένο σε JSON.
- **Συλλογή δεδομένων-προς-τεκμηρίωση** – Μετατρέψτε δομημένη τεκμηρίωση JSON σε προσβάσιμα συστήματα βοήθειας.
- **Διανομή εκτός σύνδεσης γνώσης** – Κανονικοποιήστε τα εγχειρίδια CHM για εκπαίδευση και υποστήριξη σε όλη την επιχείρηση.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}