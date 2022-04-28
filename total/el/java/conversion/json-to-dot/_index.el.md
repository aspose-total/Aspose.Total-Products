---
title: Μετατροπή μορφής JSON σε DOT μέσω Java
description: Ανάλυση JSON σε DOT σε Java χωρίς χρήση του Microsoft Word
url: /el/java/conversion/json-to-dot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOT
otherformats: RTF FLATOPC ODT DOTX WORDML PCL DOC EPUB OTT WORD PS MOBI DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή μορφής JSON σε DOT μέσω Java" h2="On premise Java API για ανάλυση JSON σε DOT χωρίς χρήση Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να μετατρέψετε το JSON σε DOT στις εφαρμογές σας Java σε διαδικασία δύο βημάτων. Πρώτον, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/) μπορείτε να αναλύσετε το JSON σε PDF. Στο δεύτερο βήμα, μπορείτε να μετατρέψετε το PDF σε DOT χρησιμοποιώντας το API επεξεργασίας κειμένου [Aspose.Words για Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή μορφής JSON σε DOT μέσω Java" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Εισαγάγετε αρχείο JSON στο φύλλο εργασίας χρησιμοποιώντας την κλάση [JsonUtility](https://apireference.aspose.com/cells/java/com.aspose.cells/JsonUtility) και το [Save](https://apireference.aspose.com/ cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) είναι PDF
3. Φορτώστε το έγγραφο PDF χρησιμοποιώντας την τάξη [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOT χρησιμοποιώντας [Αποθήκευση](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Επιπλέον, το API σάς επιτρέπει να ορίσετε επιλογές διάταξης για το JSON σας ενώ αναλύετε το JSON σε DOT χρησιμοποιώντας το [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Σας επιτρέπει να επεξεργαστείτε τον πίνακα ως πίνακα, να αγνοήσετε τα μηδενικά, να αγνοήσετε τον τίτλο του πίνακα, να αγνοήσετε τον τίτλο του αντικειμένου, να μετατρέψετε τη συμβολοσειρά σε αριθμό ή ημερομηνία, να ορίσετε την ημερομηνία και τη μορφή αριθμού και να ορίσετε στυλ τίτλου. Όλες αυτές οι επιλογές σάς επιτρέπουν να παρουσιάζετε τα δεδομένα σας σύμφωνα με τις ανάγκες σας. Το παρακάτω απόσπασμα κώδικα σάς δείχνει πώς να ορίσετε τις επιλογές διάταξης.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ρυθμίστε τη διάταξη και μετατρέψτε τη μορφή JSON σε DOT μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να αναλύσετε το JSON σε DOT με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας DOT, μπορείτε πρώτα να μετατρέψετε το αρχείο JSON σε PDF και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το αρχείο PDF που δημιουργήθηκε πρόσφατα χρησιμοποιώντας την κλάση [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), δημιουργήστε μια παρουσία του TextWatermarkOptions και ορίστε Οι ιδιότητές του, Καλέστε τη μέθοδο Watermark.setText και περάστε κείμενο υδατογραφήματος & αντικείμενο του TextWatermarkOptions. Αφού προσθέσετε το υδατογράφημα, μπορείτε να αποθηκεύσετε το έγγραφο στο DOT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-flatopc/" name="JSON Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-docm/" name="JSON Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-word/" name="JSON Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-wordml/" name="JSON Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-odt/" name="JSON Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-rtf/" name="JSON Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-doc/" name="JSON Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-mobi/" name="JSON Προς την MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ott/" name="JSON Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-dotx/" name="JSON Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pcl/" name="JSON Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-dot/" name="JSON Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-epub/" name="JSON Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ps/" name="JSON Προς την PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}