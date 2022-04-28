---
title: Μετατροπή DOT σε PPSX μέσω Java
description: Java API για εξαγωγή DOT σε PPSX χωρίς χρήση Microsoft Word ή PowerPoint
url: /el/java/conversion/dot-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: PPSX
otherformats: POTX PPSM PPT POTM PPS PPSX POT POWERPOINT PPTX PPTM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή DOT σε PPSX μέσω Java" h2="Μετατροπή DOT σε PPSX με χρήση του API Java εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Συχνά οι προγραμματιστές πρέπει να μετατρέψουν το αρχείο DOT σε PPSX μέσω προγραμματισμού. Χρησιμοποιώντας τις βιβλιοθήκες Java Automation αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να αυτοματοποιήσετε τη διαδικασία απόδοσης με μερικά απλά βήματα. Μπορείτε να φορτώσετε το αρχείο DOT χρησιμοποιώντας το [Aspose.Words για Java](https://products.aspose.com/words/java/) και να το μετατρέψετε σε HTML. Στη συνέχεια, χρησιμοποιώντας ισχυρό χειρισμό PowerPoint Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) μπορείτε να δημιουργήσετε μια νέα Παρουσίαση, να γράψετε περιεχόμενο HTML σε αυτήν και να το αποθηκεύσετε ως PPSX .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το DOT σε PPSX μέσω Java" %}}
1. Ανοίξτε το αρχείο DOT χρησιμοποιώντας την κλάση [Dotument](https://apireference.aspose.com/words/java/com.aspose.words/Dotument)
2. Μετατρέψτε το αρχείο DOT σε HTML χρησιμοποιώντας [save](https://apireference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Εξάγετε περιεχόμενο από αρχείο HTML χρησιμοποιώντας το BufferedReader και γράψτε το περιεχόμενο στο αρχείο παρουσίασής σας
6. Αποθηκεύστε το έγγραφο στο PPSX χρησιμοποιώντας τη μέθοδο [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για μετατροπή αρχείου DOT σε PPSX, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose έργο που βασίζεται στο /aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dot-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Το API σάς επιτρέπει επίσης να μετατρέπετε έγγραφα DOT που προστατεύονται με κωδικό πρόσβασης σε PPSX. Εάν το έγγραφο DOT εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή PPSX χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Για να ανοίξετε ένα κρυπτογραφημένο έγγραφο, μπορείτε να ορίσετε τον σωστό κωδικό πρόσβασης στο αντικείμενο LoadOptions και να τον μεταβιβάσετε στον κατασκευαστή του εγγράφου.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dot-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-ppsm/" name="DOT Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-pot/" name="DOT Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-powerpoint/" name="DOT Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-pptx/" name="DOT Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-potx/" name="DOT Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-pptm/" name="DOT Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-potm/" name="DOT Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-pps/" name="DOT Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-ppsx/" name="DOT Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-ppt/" name="DOT Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-csv/" name="DOT Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-dif/" name="DOT Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-fods/" name="DOT Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-ods/" name="DOT Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-sxc/" name="DOT Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-tsv/" name="DOT Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlam/" name="DOT Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xltm/" name="DOT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-excel/" name="DOT Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xls/" name="DOT Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlsb/" name="DOT Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlsm/" name="DOT Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlsx/" name="DOT Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xlt/" name="DOT Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xltm/" name="DOT Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/dot-to-xltx/" name="DOT Προς την XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}