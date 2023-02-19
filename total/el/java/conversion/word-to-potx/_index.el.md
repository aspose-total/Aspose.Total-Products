---
title: Μετατροπή WORD σε POTX μέσω Java
description: Java API για εξαγωγή WORD σε POTX χωρίς χρήση Microsoft Word ή PowerPoint
url_ignore: /el/java/conversion/word-to-potx/
family: total
platformtag: net
feature: conversion
informat: WORDX
outformat: POTX
otherformats: POTX POWERPOINT PPS PPTX PPT PPSM POT PPTM PPSX POTM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή WORD σε POTX μέσω Java" h2="Μετατροπή WORD σε POTX με χρήση του API Java εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Συχνά οι προγραμματιστές πρέπει να μετατρέψουν το αρχείο WORD σε POTX μέσω προγραμματισμού. Χρησιμοποιώντας τις βιβλιοθήκες Java Automation αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να αυτοματοποιήσετε τη διαδικασία απόδοσης με μερικά απλά βήματα. Μπορείτε να φορτώσετε το αρχείο WORD χρησιμοποιώντας το [Aspose.Words για Java](https://products.aspose.com/words/java/) και να το μετατρέψετε σε HTML. Στη συνέχεια, χρησιμοποιώντας ισχυρό χειρισμό PowerPoint Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) μπορείτε να δημιουργήσετε μια νέα Παρουσίαση, να γράψετε περιεχόμενο HTML σε αυτήν και να το αποθηκεύσετε ως POTX .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το WORD σε POTX μέσω Java" %}}
1. Ανοίξτε το αρχείο WORD χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Μετατρέψτε το αρχείο WORD σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Εξάγετε περιεχόμενο από αρχείο HTML χρησιμοποιώντας το BufferedReader και γράψτε το περιεχόμενο στο αρχείο παρουσίασής σας
6. Αποθηκεύστε το έγγραφο στο POTX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για μετατροπή αρχείου WORD σε POTX, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose έργο που βασίζεται στο /aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-word-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Δωρεάν Online Μετατροπέας για WORD σε POTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potx&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Το API σάς επιτρέπει επίσης να μετατρέπετε έγγραφα WORD που προστατεύονται με κωδικό πρόσβασης σε POTX. Εάν το έγγραφο WORD εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή POTX χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Για να ανοίξετε ένα κρυπτογραφημένο έγγραφο, μπορείτε να ορίσετε τον σωστό κωδικό πρόσβασης στο αντικείμενο LoadOptions και να τον μεταβιβάσετε στον κατασκευαστή του εγγράφου.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-word-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-ppsm/" name="WORD Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-pot/" name="WORD Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-powerpoint/" name="WORD Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-pptx/" name="WORD Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-potx/" name="WORD Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-pptm/" name="WORD Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-potm/" name="WORD Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-pps/" name="WORD Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-ppsx/" name="WORD Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-ppt/" name="WORD Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-csv/" name="WORD Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-dif/" name="WORD Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-fods/" name="WORD Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-ods/" name="WORD Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-sxc/" name="WORD Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-tsv/" name="WORD Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xlam/" name="WORD Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xltm/" name="WORD Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-excel/" name="WORD Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xls/" name="WORD Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xlsb/" name="WORD Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xlsm/" name="WORD Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xlsx/" name="WORD Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xlt/" name="WORD Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xltm/" name="WORD Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/word-to-xltx/" name="WORD Προς την XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}