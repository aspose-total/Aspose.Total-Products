---
title: Μετατροπή μορφής JSON σε PPT μέσω Java
description: Ανάλυση JSON σε PPT σε Java χωρίς χρήση του Microsoft PowerPoint
url_ignore: /el/java/conversion/json-to-ppt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: POTX PPS POWERPOINT PPTM PPT PPSM POT PPSX POTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή μορφής JSON σε PPT μέσω Java" h2="Java API για ανάλυση της μορφής JSON σε PPT χωρίς τη χρήση Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for Java](https://products.aspose.com/total/java/), μπορείτε να μετατρέψετε τη μορφή JSON σε PPT σε οποιαδήποτε εφαρμογή Java με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/), μπορείτε να αναλύσετε το JSON σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/), μπορείτε να μετατρέψετε το PPTX σε PPT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή μορφής JSON σε PPT μέσω Java" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) και ανοίξτε το αρχείο JSON
2. Αποθηκεύστε το JSON ως PPTX χρησιμοποιώντας το [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) μέθοδος
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Επιπλέον, το API σάς επιτρέπει να αναλύετε το JSON σε PPT με καθορισμένες επιλογές διάταξης. Για να καθορίσετε τις επιλογές διάταξης, μπορείτε να χρησιμοποιήσετε την κλάση [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Σας επιτρέπει να επεξεργαστείτε έναν πίνακα ως πίνακα, να αγνοήσετε μηδενικά, να αγνοήσετε τον τίτλο του πίνακα, να αγνοήσετε τον τίτλο του αντικειμένου, να μετατρέψετε τη συμβολοσειρά σε αριθμό ή ημερομηνία, να ορίσετε ημερομηνία και μορφή αριθμού και να ορίσετε στυλ τίτλου. Όλες αυτές οι επιλογές σάς επιτρέπουν να παρουσιάζετε τα δεδομένα σας σύμφωνα με τις ανάγκες σας. Το παρακάτω απόσπασμα κώδικα σάς δείχνει πώς να ορίσετε τις επιλογές διάταξης.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ορίστε τη διάταξη και μετατρέψτε τη μορφή JSON σε PPT μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε JSON σε PPT με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας PPT, μπορείτε πρώτα να αναλύσετε το JSON σε PPTX και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το αρχείο PPTX που δημιουργήθηκε πρόσφατα χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), κάντε βρόχο σε όλες τις διαφάνειες, προσθέστε κείμενο χρησιμοποιώντας το addTextFrame, ορίστε όλες τις σχετικές επιλογές όπως το χρώμα, το fillType και άλλα και μπορείτε να αποθηκεύσετε το έγγραφο σε PPT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pps/" name="JSON Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ppt/" name="JSON Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pptm/" name="JSON Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ppsm/" name="JSON Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-powerpoint/" name="JSON Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pot/" name="JSON Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-potm/" name="JSON Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-otp/" name="JSON Προς την OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ppsx/" name="JSON Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-potx/" name="JSON Προς την POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}