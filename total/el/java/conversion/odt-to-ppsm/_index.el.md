---
title: Μετατροπή ODT σε PPSM μέσω Java
description: Java API για εξαγωγή ODT σε PPSM χωρίς χρήση Microsoft Word ή PowerPoint
url_ignore: /el/java/conversion/odt-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: PPSM
otherformats: PPSX PPSM PPTX PPS POTM POTX PPT POWERPOINT PPTM POT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή ODT σε PPSM μέσω Java" h2="Μετατροπή ODT σε PPSM με χρήση του API Java εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Συχνά οι προγραμματιστές πρέπει να μετατρέψουν το αρχείο ODT σε PPSM μέσω προγραμματισμού. Χρησιμοποιώντας τις βιβλιοθήκες Java Automation αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να αυτοματοποιήσετε τη διαδικασία απόδοσης με μερικά απλά βήματα. Μπορείτε να φορτώσετε το αρχείο ODT χρησιμοποιώντας το [Aspose.Words για Java](https://products.aspose.com/words/java/) και να το μετατρέψετε σε HTML. Στη συνέχεια, χρησιμοποιώντας ισχυρό χειρισμό PowerPoint Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) μπορείτε να δημιουργήσετε μια νέα Παρουσίαση, να γράψετε περιεχόμενο HTML σε αυτήν και να το αποθηκεύσετε ως PPSM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το ODT σε PPSM μέσω Java" %}}
1. Ανοίξτε το αρχείο ODT χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Μετατρέψτε το αρχείο ODT σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Εξάγετε περιεχόμενο από αρχείο HTML χρησιμοποιώντας το BufferedReader και γράψτε το περιεχόμενο στο αρχείο παρουσίασής σας
6. Αποθηκεύστε το έγγραφο στο PPSM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για μετατροπή αρχείου ODT σε PPSM, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose έργο που βασίζεται στο /aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Το API σάς επιτρέπει επίσης να μετατρέπετε έγγραφα ODT που προστατεύονται με κωδικό πρόσβασης σε PPSM. Εάν το έγγραφο ODT εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή PPSM χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Για να ανοίξετε ένα κρυπτογραφημένο έγγραφο, μπορείτε να ορίσετε τον σωστό κωδικό πρόσβασης στο αντικείμενο LoadOptions και να τον μεταβιβάσετε στον κατασκευαστή του εγγράφου.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-ppsm/" name="ODT Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-pot/" name="ODT Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-powerpoint/" name="ODT Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-pptx/" name="ODT Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-potx/" name="ODT Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-pptm/" name="ODT Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-potm/" name="ODT Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-pps/" name="ODT Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-ppsx/" name="ODT Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-ppt/" name="ODT Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-csv/" name="ODT Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-dif/" name="ODT Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-fods/" name="ODT Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-ods/" name="ODT Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-sxc/" name="ODT Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-tsv/" name="ODT Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xlam/" name="ODT Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xltm/" name="ODT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-excel/" name="ODT Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xls/" name="ODT Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xlsb/" name="ODT Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xlsm/" name="ODT Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xlsx/" name="ODT Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xlt/" name="ODT Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xltm/" name="ODT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/odt-to-xltx/" name="ODT Προς την XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}