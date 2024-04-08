---
title: Καταργήστε το DOTX Annotation Online ή διαχειριστείτε τους σχολιασμούς μέσω C++
description: διαγράψτε σχόλια από το αρχείο DOTX μέσω της διαδικτυακής εφαρμογής δωρεάν. Κώδικας API C++ για διαχείριση σχολίων αρχείων DOTX.

family: total
platformtag: cpp
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Διαγραφή σχολίων από το DOTX Document Online ή Διαχείριση μέσω C++" h2="Αναπτύξτε μια ισχυρή εφαρμογή βοηθητικού προγράμματος σχολιασμού εγγράφων DOTX που βασίζεται σε C++. Παρατίθεται κώδικας για τη διαχείριση σχολίων του αρχείου DOTX μέσω C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Κατάργηση DOTX Annotations Online" %}}

1. Εισαγάγετε το αρχείο DOTX για να διαγράψετε σχόλια ανεβάζοντάς το
1. Κάντε το κάνοντας κλικ μέσα στην περιοχή απόθεσης μέσω μεταφοράς και απόθεσης της εφαρμογής σχολιασμού
1. Ανάλογα με το μέγεθος του αρχείου DOTX και την ταχύτητα του Διαδικτύου, περιμένετε μερικά δευτερόλεπτα
1. Κάντε κλικ στο κουμπί "Κατάργηση" για να διαγράψετε τα σχόλια
1. Κατεβάστε το αρχείο άμεσα

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Διαγραφή σχολίων εγγράφου DOTX μέσω C++" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο C++
1. Φόρτωση αρχείου DOTX
1. Λάβετε όλους τους κόμβους χρησιμοποιώντας το GetChildNodes που έχουν ως παράμετρο NodeType::Comment
1. Καλέστε το NodeCollection.Clear στη συλλογή σχολίων

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός C++: Διαγραφή σχολίων από το αρχείο DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Προσθήκη σχολίων μέσω C++" %}}

1. Δημιουργία αντικειμένου κλάσης Document και DocumentBuilder
1. Ή Φορτώστε το έγγραφο
1. Χρησιμοποιήστε την τάξη σχολίων για να προσθέσετε το σχόλιο
1. Χρησιμοποιήστε τη μέθοδο AppendChild με το σχόλιο obj ως παράμετρο
1. Χρησιμοποιήστε σχετική μέθοδο όπως get_Paragraphs()->Add
1. Ή ο άλλος τρόπος είναι να χρησιμοποιήσετε τις κλάσεις CommentRangeStart και CommentRangeEnd
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο με πρόσθετα σχόλια

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή όλων των σχολίων" %}}

1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Αποκτήστε όλα τα GetChildNodes στο NodeCollection
1. Επαναλάβετε κάθε συλλογή και συλλέξτε πληροφορίες για αυτές

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός C++: Προσθήκη σχολίου στο αρχείο DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Εξαγωγή όλων των σχολίων" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Αναπτύξτε DOTX Document Annotation Application μέσω C++</h2>

Χρειάζεστε να αναπτύξετε μια εφαρμογή ή βοηθητικό πρόγραμμα σχολιασμού DOTX για να παρέχετε σχόλια, να κάνετε προτάσεις ή να συνεργαστείτε με άλλους στο έγγραφο;Με το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ένα θυγατρικό API του [Aspose.Total for C++](https://products.aspose.com/total/el/cpp/), οποιοσδήποτε προγραμματιστής C++ μπορεί να ενσωματώσει τον παραπάνω κώδικα API στην εφαρμογή σχολιασμού εγγράφων του.Η ισχυρή βιβλιοθήκη C++ επιτρέπει τον προγραμματισμό οποιασδήποτε λύσης σχολιασμού εγγράφων.Επιπλέον, μπορεί να υποστηρίξει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής DOTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Βιβλιοθήκη C++ για σχολιασμό αρχείων DOTX" %}}

Υπάρχουν τρεις επιλογές για να εγκαταστήσετε το Aspose.Words για C++ στο περιβάλλον προγραμματιστή σας.Επιλέξτε αυτό που μοιάζει με τις ανάγκες σας και ακολουθήστε τις οδηγίες βήμα προς βήμα:<br /><br />

- Install a [Πακέτο NuGet](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Τεκμηρίωση](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Εγκαταστήστε τη βιβλιοθήκη χρησιμοποιώντας [Κονσόλα Package Manager](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) στο Visual Studio IDE
- Εγκαταστήστε τη βιβλιοθήκη με το χέρι χρησιμοποιώντας [Windows Installer](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}
Μπορείτε να χρησιμοποιήσετε αυτήν τη βιβλιοθήκη C++ για να αναπτύξετε λογισμικό σε λειτουργικά συστήματα Microsoft Windows, Linux και macOS:<br /><br />

- GCC >= 6.3.0 και Clang >= 3.9.1 απαιτούνται για Linux
- Xcode >= 12.5.1, Clang και libc++ απαιτούνται για macOS

<br /><br />
Εάν αναπτύσσετε λογισμικό για Linux ή macOS, ελέγξτε πληροφορίες σχετικά με πρόσθετες εξαρτήσεις βιβλιοθήκης (fontconfig και πακέτα ανοιχτού κώδικα mesa-glu) στο [Τεκμηρίωση προϊόντος](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Συχνές ερωτήσεις" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Συχνές ερωτήσεις</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Μπορώ να χρησιμοποιήσω τον παραπάνω κώδικα C++ στην εφαρμογή μου;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ναι, μπορείτε να κάνετε λήψη αυτού του κώδικα και να τον χρησιμοποιήσετε για την ανάπτυξη εφαρμογής σχολιασμού εγγράφων που βασίζεται στη C++.Αυτός ο κώδικας μπορεί να χρησιμεύσει ως πολύτιμος πόρος για τη βελτίωση της λειτουργικότητας και των δυνατοτήτων των έργων σας στον τομέα της επεξεργασίας και χειρισμού εγγράφων υποστήριξης.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Αυτή η διαδικτυακή εφαρμογή σχολιασμού εγγράφων λειτουργεί μόνο σε Windows;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Έχετε την ευελιξία να ξεκινήσετε τον σχολιασμό εγγράφων για την αφαίρεση σχολίων σε οποιαδήποτε συσκευή, ανεξάρτητα από το λειτουργικό σύστημα στο οποίο εκτελείται, είτε είναι Windows, Linux, Mac OS ή Android. Το μόνο που απαιτείται είναι ένα σύγχρονο πρόγραμμα περιήγησης και μια ενεργή σύνδεση στο Διαδίκτυο.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Είναι ασφαλές να χρησιμοποιήσετε την ηλεκτρονική εφαρμογή για να σχολιάσετε το έγγραφο DOTX;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Φυσικά! Τα αρχεία εξόδου που δημιουργούνται μέσω της υπηρεσίας μας θα αφαιρεθούν με ασφάλεια και αυτόματα από τους διακομιστές μας εντός 24 ωρών.Ως αποτέλεσμα, οι σύνδεσμοι εμφάνισης που σχετίζονται με αυτά τα αρχεία θα πάψουν να λειτουργούν μετά από αυτήν την περίοδο.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ποιο πρόγραμμα περιήγησης πρέπει να χρησιμοποιήσει την εφαρμογή;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού, όπως το Google Chrome, το Firefox, το Opera ή το Safari για online σχολιασμό εγγράφων DOTX.Ωστόσο, εάν αναπτύσσετε μια εφαρμογή επιτραπέζιου υπολογιστή, συνιστούμε να χρησιμοποιήσετε το API επεξεργασίας εγγράφων Aspose.Total για αποτελεσματική διαχείριση.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}