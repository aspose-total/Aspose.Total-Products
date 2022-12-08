---
title: Μετατροπή DOCX σε PPSM μέσω Java
description: Java API για εξαγωγή DOCX σε PPSM χωρίς χρήση Microsoft Word ή PowerPoint
url_ignore: /el/java/conversion/docx-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: PPSM
otherformats: PPTX POT POTM PPS PPTM PPT POTX POWERPOINT PPSX PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή DOCX σε PPSM μέσω Java" h2="Μετατροπή DOCX σε PPSM με χρήση του API Java εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Συχνά οι προγραμματιστές πρέπει να μετατρέψουν το αρχείο DOCX σε PPSM μέσω προγραμματισμού. Χρησιμοποιώντας τις βιβλιοθήκες Java Automation αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να αυτοματοποιήσετε τη διαδικασία απόδοσης με μερικά απλά βήματα. Μπορείτε να φορτώσετε το αρχείο DOCX χρησιμοποιώντας το [Aspose.Words για Java](https://products.aspose.com/words/java/) και να το μετατρέψετε σε HTML. Στη συνέχεια, χρησιμοποιώντας ισχυρό χειρισμό PowerPoint Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) μπορείτε να δημιουργήσετε μια νέα Παρουσίαση, να γράψετε περιεχόμενο HTML σε αυτήν και να το αποθηκεύσετε ως PPSM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το DOCX σε PPSM μέσω Java" %}}
1. Ανοίξτε το αρχείο DOCX χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Μετατρέψτε το αρχείο DOCX σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Εξάγετε περιεχόμενο από αρχείο HTML χρησιμοποιώντας το BufferedReader και γράψτε το περιεχόμενο στο αρχείο παρουσίασής σας
6. Αποθηκεύστε το έγγραφο στο PPSM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για μετατροπή αρχείου DOCX σε PPSM, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose έργο που βασίζεται στο /aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docx-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Το API σάς επιτρέπει επίσης να μετατρέπετε έγγραφα DOCX που προστατεύονται με κωδικό πρόσβασης σε PPSM. Εάν το έγγραφο DOCX εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή PPSM χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Για να ανοίξετε ένα κρυπτογραφημένο έγγραφο, μπορείτε να ορίσετε τον σωστό κωδικό πρόσβασης στο αντικείμενο LoadOptions και να τον μεταβιβάσετε στον κατασκευαστή του εγγράφου.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-docx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-ppsm/" name="DOCX Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-pot/" name="DOCX Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-powerpoint/" name="DOCX Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-pptx/" name="DOCX Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-potx/" name="DOCX Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-pptm/" name="DOCX Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-potm/" name="DOCX Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-pps/" name="DOCX Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-ppsx/" name="DOCX Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-ppt/" name="DOCX Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-csv/" name="DOCX Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-dif/" name="DOCX Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-fods/" name="DOCX Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-ods/" name="DOCX Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-sxc/" name="DOCX Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-tsv/" name="DOCX Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xlam/" name="DOCX Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xltm/" name="DOCX Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-excel/" name="DOCX Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xls/" name="DOCX Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xlsb/" name="DOCX Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xlsm/" name="DOCX Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xlsx/" name="DOCX Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xlt/" name="DOCX Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xltm/" name="DOCX Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/docx-to-xltx/" name="DOCX Προς την XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}