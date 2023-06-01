---
title: Μετατροπή DOC σε PPTX μέσω C++ ή με δωρεάν Online Converter
description: Εξαγωγή DOC σε PPTX στις εφαρμογές σας C++ χωρίς χρήση του Microsoft Word του PowerPoint ή διαδικτυακά. Δοκιμάστε γρήγορα τον δωρεάν διαδικτυακό μετατροπέα DOC σε PPTX πριν ενσωματώσετε τον κώδικα.

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: PPTX
otherformats: POWERPOINT ODP POTM POT PPS PPSM PPTM PPT POTX PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για μετατροπή DOC σε PPTX ή Online App" h2="Εξαγωγή DOC σε PPTX εντός των εφαρμογών σας C++ χωρίς χρήση του Microsoft Word&reg; ή PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) αποτελείται από ισχυρά API αυτοματισμού αρχείων που επιτρέπουν την αυτοματοποίηση της μετατροπής DOC σε PPTX ενώ χρησιμοποιούνται δύο από τα API του. Φορτώστε το DOC σας χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) και μετατρέψτε το σε HTML και, στη συνέχεια, φορτώστε το HTML μέσω χειρισμού του PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) για να δημιουργήσετε μια νέα παρουσίαση και να την αποθηκεύσετε ως PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή DOC σε PPTX σε C++" %}}
1. Ανοίξτε το αρχείο DOC χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Μετατρέψτε το DOC σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Προσθέστε ένα AutoShape στη διαφάνειά σας και προσθέστε το AddTextFrame σε αυτό
5. Φορτώστε το περιεχόμενο HTML και γράψτε το στο αρχείο παρουσίασης
6. Αποθηκεύστε το έγγραφο σε μορφή PPTX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το Pptx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOC file with an instance of Document
Document document = new Document("template.doc");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.doc");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Δωρεάν Online Μετατροπέας για DOC σε PPTX</h3>

<iframe title="Εργαλείο μετατροπής pptx σε doc" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου DOC που προστατεύεται με κωδικό πρόσβασης μέσω C++" %}}
Εκτός από τη μετατροπή εγγράφων, το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API επιτρέπει τόνους λειτουργιών χειρισμού εγγράφων για προγραμματιστές C++. Σε περίπτωση που η μορφή αρχείου DOC του Microsoft Word προστατεύεται με κωδικό πρόσβασης, μπορείτε να την ανοίξετε χρησιμοποιώντας το API. Για να φορτώσετε το κρυπτογραφημένο έγγραφο, μπορείτε να χρησιμοποιήσετε μια ειδική υπερφόρτωση κατασκευαστή, η οποία δέχεται ένα αντικείμενο [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Αυτό το αντικείμενο περιέχει την ιδιότητα Κωδικός πρόσβασης, η οποία καθορίζει τη συμβολοσειρά κωδικού πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.doc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη σχολίων στο έγγραφο PPTX μέσω C++" %}}
Κατά την αποθήκευση του DOC ως PPTX, μπορείτε επίσης να χρησιμοποιήσετε το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) για να προσθέσετε επιπλέον δυνατότητες στο έγγραφο PPTX. Για παράδειγμα, μπορείτε να προσθέσετε σχόλια στην παρουσίασή σας. Το σχόλιο της διαφάνειας παρουσίασης σχετίζεται με έναν συγκεκριμένο συγγραφέα. Η κλάση Presentation περιέχει τη συλλογή των συγγραφέων στο ICommentAuthorCollection που είναι υπεύθυνοι για την προσθήκη σχολίων διαφάνειας. Για κάθε συγγραφέα, υπάρχει μια συλλογή σχολίων στο ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
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
                          <span itemprop="name"><b>Πώς μπορώ να μετατρέψω DOC σε PPTX Online;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Μπορείτε να βρείτε την ηλεκτρονική εφαρμογή για μετατροπή DOC παραπάνω. Για να ξεκινήσετε τη διαδικασία μετατροπής, μπορείτε να προσθέσετε το αρχείο DOC είτε με μεταφορά και απόθεση είτε κάνοντας κλικ μέσα στη λευκή περιοχή για εισαγωγή του εγγράφου. Αφού προσθέσετε το αρχείο, μπορείτε απλά να κάνετε κλικ στο κουμπί "Μετατροπή". Αφού ολοκληρωθεί η μετατροπή DOC σε PPTX, μπορείτε να κάνετε λήψη του αρχείου που μετατράπηκε με ένα μόνο κλικ.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Πόσος χρόνος χρειάζεται για τη μετατροπή DOC;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Η ταχύτητα αυτού του διαδικτυακού μετατροπέα εξαρτάται σε μεγάλο βαθμό από το μέγεθος του αρχείου DOC που μετατρέπεται. Τα μικρά αρχεία DOC μπορούν να μετατραπούν σε PPTX μέσα σε λίγα δευτερόλεπτα. Εάν χρησιμοποιείτε τον κώδικα μετατροπής σε μια εφαρμογή C++, η ταχύτητα μετατροπής θα εξαρτηθεί από το πόσο καλά έχετε βελτιστοποιήσει την εφαρμογή σας.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Είναι ασφαλής η μετατροπή DOC σε PPTX χρησιμοποιώντας τον δωρεάν μετατροπέα Aspose.Total;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Φυσικά! Αφού το αρχείο DOC μετατραπεί σε PPTX χρησιμοποιώντας τον διαδικτυακό μας μετατροπέα, ο σύνδεσμος λήψης για το αρχείο PPTX θα είναι άμεσα διαθέσιμος. Λαμβάνουμε σοβαρά υπόψη την ασφάλεια και το απόρρητο των μεταφορτωμένων αρχείων σας και τα διαγράφουμε 24 ώρες μετά την ολοκλήρωση της διαδικασίας μετατροπής. Να είστε βέβαιοι, κανείς δεν θα έχει πρόσβαση στα αρχεία σας. Η διαδικασία μετατροπής μας, συμπεριλαμβανομένης της μετατροπής DOC, είναι απολύτως ασφαλής. Παρέχουμε μια δωρεάν εφαρμογή για δοκιμαστικούς σκοπούς, ώστε να μπορείτε να επαληθεύσετε τα αποτελέσματα πριν ενσωματώσετε τον κώδικα.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Τι πρόγραμμα περιήγησης πρέπει να χρησιμοποιήσω για τη μετατροπή DOC;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Για διαδικτυακή μετατροπή DOC, μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης, όπως Google Chrome, Firefox, Opera ή Safari. Ωστόσο, εάν αναπτύσσετε μια εφαρμογή για υπολογιστές, το Aspose.Total DOC Conversion API συνιστάται για ομαλή απόδοση.</span>
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