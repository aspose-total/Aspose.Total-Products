---
title: Μετατροπή DOC σε PPT μέσω Java
description: Java API για εξαγωγή DOC σε PPT χωρίς χρήση Microsoft Word ή PowerPoint
url_ignore: /el/java/conversion/doc-to-ppt/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: PPT
otherformats: POT PPS PPT PPTX PPSX PPTM POWERPOINT POTX PPSM POTM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή DOC σε PPT μέσω Java" h2="Μετατροπή DOC σε PPT με χρήση του API Java εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint ή Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Συχνά οι προγραμματιστές πρέπει να μετατρέψουν το αρχείο DOC σε PPT μέσω προγραμματισμού. Χρησιμοποιώντας τις βιβλιοθήκες Java Automation αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/) μπορείτε να αυτοματοποιήσετε τη διαδικασία απόδοσης με μερικά απλά βήματα. Μπορείτε να φορτώσετε το αρχείο DOC χρησιμοποιώντας το [Aspose.Words για Java](https://products.aspose.com/words/java/) και να το μετατρέψετε σε HTML. Στη συνέχεια, χρησιμοποιώντας ισχυρό χειρισμό PowerPoint Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) μπορείτε να δημιουργήσετε μια νέα Παρουσίαση, να γράψετε περιεχόμενο HTML σε αυτήν και να το αποθηκεύσετε ως PPT .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το DOC σε PPT μέσω Java" %}}
1. Ανοίξτε το αρχείο DOC χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Μετατρέψτε το αρχείο DOC σε HTML χρησιμοποιώντας [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) μέθοδος
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Εξάγετε περιεχόμενο από αρχείο HTML χρησιμοποιώντας το BufferedReader και γράψτε το περιεχόμενο στο αρχείο παρουσίασής σας
6. Αποθηκεύστε το έγγραφο στο PPT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για μετατροπή αρχείου DOC σε PPT, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose έργο που βασίζεται στο /aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Δωρεάν Online Μετατροπέας για DOC σε PPT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppt&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Το API σάς επιτρέπει επίσης να μετατρέπετε έγγραφα DOC που προστατεύονται με κωδικό πρόσβασης σε PPT. Εάν το έγγραφο DOC εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε μορφή PPT χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Για να ανοίξετε ένα κρυπτογραφημένο έγγραφο, μπορείτε να ορίσετε τον σωστό κωδικό πρόσβασης στο αντικείμενο LoadOptions και να τον μεταβιβάσετε στον κατασκευαστή του εγγράφου.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-ppsm/" name="DOC Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-pot/" name="DOC Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-powerpoint/" name="DOC Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-pptx/" name="DOC Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-potx/" name="DOC Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-pptm/" name="DOC Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-potm/" name="DOC Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-pps/" name="DOC Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-ppsx/" name="DOC Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-ppt/" name="DOC Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-csv/" name="DOC Προς την CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-dif/" name="DOC Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-fods/" name="DOC Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-ods/" name="DOC Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-sxc/" name="DOC Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-tsv/" name="DOC Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlam/" name="DOC Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xltm/" name="DOC Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-excel/" name="DOC Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xls/" name="DOC Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlsb/" name="DOC Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlsm/" name="DOC Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlsx/" name="DOC Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xlt/" name="DOC Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xltm/" name="DOC Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/doc-to-xltx/" name="DOC Προς την XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}