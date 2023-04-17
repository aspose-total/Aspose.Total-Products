---
title: Μετατροπή XLS σε DOC χρησιμοποιώντας Java ή με δωρεάν Online Converter
description: Java API για εξαγωγή XLS σε DOC ή διαδικτυακά με χρήση Excel ή Word ή διαδικτυακά. Δοκιμάστε γρήγορα τον δωρεάν διαδικτυακό μετατροπέα CSV σε DOC πριν ενσωματώσετε τον κώδικα.
url_ignore: /el/java/conversion/xls-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOC
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή XLS σε DOC ή διαδικτυακά" h2="On Premise Java API για εξαγωγή XLS σε DOC ή διαδικτυακά χωρίς να βασίζεστε στο Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η απόδοση του XLS σε DOC είναι μια διαδικασία δύο βημάτων. Θα χρησιμοποιήσετε πρώτα το [Aspose.Cells for Java](https://products.aspose.com/cells/java) API για να μετατρέψετε το δεδομένο έγγραφο XLS σε PDF και, στη συνέχεια, χρησιμοποιώντας το [Aspose.Pdf για Java](https://products.aspose.com/pdf/java) API, μπορείτε εύκολα να μετατρέψετε το έγγραφο PDF σας σε DOC. Και τα δύο API ανήκουν στη συλλογή των βιβλιοθηκών αυτοματισμού μορφών αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε XLS σε DOC μέσω Java API" %}}
1. Ανοίξτε το αρχείο XLS χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Μετατρέψτε το XLS σε PDF και ορίστε το SaveFormat σε AUTO
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) και ορίστε το Doc ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Πρέπει να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Διαδικτυακός μετατροπέας για XLS σε DOC</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xls" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xls-to-doc/">Δοκιμάστε τη δωρεάν εφαρμογή μας για μετατροπή XLS σε DOC</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Συχνές Ερωτήσεις</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Πώς μπορώ να μετατρέψω XLS σε DOC Online;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Η διαδικτυακή εφαρμογή για μετατροπή XLS είναι ενσωματωμένη παραπάνω. Η διαδικασία μετατροπής περιλαμβάνει την προσθήκη του αρχείου XLS είτε με μεταφορά και απόθεση στη λευκή περιοχή είτε κάνοντας κλικ μέσα στην περιοχή για εισαγωγή του αρχείου. Μόλις προστεθεί το αρχείο, απλώς κάντε κλικ στο κουμπί Μετατροπή για να ξεκινήσει η διαδικασία μετατροπής. Μόλις ολοκληρωθεί, μπορείτε να κάνετε λήψη του αρχείου DOC που μετατράπηκε πρόσφατα με ένα μόνο κλικ.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Πόσος χρόνος χρειάζεται για τη μετατροπή XLS;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Η ταχύτητα αυτού του διαδικτυακού μετατροπέα καθορίζεται σε μεγάλο βαθμό από το μέγεθος του αρχείου XLS που μετατρέπεται. Τα μικρότερα αρχεία XLS μπορούν να μετατραπούν σε DOC μέσα σε λίγα δευτερόλεπτα. Επιπλέον, εάν έχετε ενσωματώσει τον κώδικα μετατροπής σε μια εφαρμογή Java, η αποτελεσματικότητα της εφαρμογής θα επηρεάσει επίσης τη διαδικασία μετατροπής.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Είναι ασφαλής η μετατροπή XLS σε DOC χρησιμοποιώντας τον δωρεάν μετατροπέα Aspose.Total;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Φυσικά! Αφού ολοκληρωθεί η διαδικασία μετατροπής, ένας σύνδεσμος λήψης για το αρχείο DOC θα είναι άμεσα διαθέσιμος. Τα μεταφορτωμένα αρχεία διαγράφονται αυτόματα μετά από 24 ώρες και οι σύνδεσμοι λήψης δεν θα είναι πλέον ενεργοί πέρα από αυτό το χρονικό πλαίσιο. Μπορείτε να είστε βέβαιοι ότι τα αρχεία σας είναι ασφαλή και ότι η μετατροπή αρχείων, συμπεριλαμβανομένου του XLS, είναι απολύτως ασφαλής. Η δωρεάν εφαρμογή έχει ενσωματωθεί κυρίως για δοκιμαστικούς σκοπούς, επιτρέποντάς σας να επαληθεύσετε τα αποτελέσματα πριν ενσωματώσετε τον κώδικα στο έργο σας.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Τι πρόγραμμα περιήγησης πρέπει να χρησιμοποιήσω για τη μετατροπή XLS;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Για διαδικτυακή μετατροπή, μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού, όπως Google Chrome, Firefox, Opera ή Safari. Ωστόσο, εάν αναπτύσσετε μια εφαρμογή για υπολογιστές, το Aspose.Total XLS Conversion API είναι μια εξαιρετική επιλογή, καθώς έχει σχεδιαστεί για να λειτουργεί απρόσκοπτα σε τέτοια περιβάλλοντα.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}