---
title: Καταργήστε το DOCX Annotation Online ή διαχειριστείτε τους σχολιασμούς μέσω .NET
description: διαγράψτε σχόλια από το αρχείο DOCX μέσω της διαδικτυακής εφαρμογής δωρεάν.Κώδικας API .NET για διαχείριση σχολίων αρχείων DOCX.

family: total
platformtag: net
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Διαγραφή σχολίων από το DOCX Document Online ή Διαχείριση μέσω .NET" h2="Αναπτύξτε ισχυρή εφαρμογή βοηθητικού προγράμματος σχολιασμού εγγράφων DOCX που βασίζεται σε .NET.Παρατίθεται κώδικας για τη διαχείριση σχολίων του αρχείου DOCX μέσω .NET." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Κατάργηση DOCX Annotations Online" %}}

1. Εισαγάγετε το αρχείο DOCX για να διαγράψετε σχόλια ανεβάζοντάς το
1. Κάντε το κάνοντας κλικ μέσα στην περιοχή απόθεσης μέσω μεταφοράς και απόθεσης της εφαρμογής σχολιασμού
1. Ανάλογα με το μέγεθος του αρχείου DOCX και την ταχύτητα του Διαδικτύου, περιμένετε μερικά δευτερόλεπτα
1. Κάντε κλικ στο κουμπί "Κατάργηση" για να διαγράψετε τα σχόλια
1. Κατεβάστε το αρχείο άμεσα

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Διαγραφή Συγκεκριμένων Σχόλια Εγγράφου DOCX Συγγραφέων μέσω .NET" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο .NET
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Λάβετε σχόλια όλων των κόμβων χρησιμοποιώντας τα GetChildNodes που έχουν NodeType.Comment
1. Επαναλάβετε όλα τα σχόλια και αντιστοιχίστε το όνομα του συγγραφέα
1. Καλέστε τη μέθοδο Κατάργηση για να διαγράψετε το συγκεκριμένο σχόλιο συντάκτη

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός C#: Διαγραφή συγκεκριμένων σχολίων συντάκτη από το αρχείο DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Προσθήκη σχολίων μέσω .NET" %}}

1. Δημιουργία αντικειμένου κλάσης εγγράφου
1. Χρησιμοποιήστε την τάξη σχολίων
1. Προσθέστε τη νέα παράγραφο χρησιμοποιώντας Paragraphs.Add
1. Χρησιμοποιήστε το FirstParagraph.Runs. Προσθέστε την προσθήκη του σχολίου
1. Ή ο άλλος τρόπος είναι να χρησιμοποιήσετε τις κλάσεις CommentRangeStart και CommentRangeEnd
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο με πρόσθετα σχόλια

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή όλων των σχολίων" %}}

1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Δημιουργήστε ένα αντικείμενο ArrayList
1. Αποκτήστε όλα τα GetChildNodes στο NodeCollection
1. Επαναλάβετε σε κάθε συλλογή και προσθέστε σχόλια στο ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κωδικός .NET: Προσθήκη σχολίου από το αρχείο DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Εξαγωγή όλων των σχολίων" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Αναπτύξτε DOCX Document Annotation Application μέσω .NET</h2>

Χρειάζεστε να αναπτύξετε μια εφαρμογή ή βοηθητικό πρόγραμμα σχολιασμού DOCX για να παρέχετε σχόλια, να κάνετε προτάσεις ή να συνεργαστείτε με άλλους στο έγγραφο;Με το [Aspose.Words for .NET](https://products.aspose.com/words/net/) ένα θυγατρικό API του [Aspose.Total for .NET](https://products.aspose.com/total/net/), οποιοσδήποτε προγραμματιστής .NET μπορεί να ενσωματώσει τον παραπάνω κώδικα API στην εφαρμογή σχολιασμού εγγράφων του.Η ισχυρή βιβλιοθήκη .NET επιτρέπει τον προγραμματισμό οποιασδήποτε λύσης σχολιασμού εγγράφων.Επιπλέον, μπορεί να υποστηρίξει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET Library για σχολιασμό αρχείων DOCX" %}}

Υπάρχουν τρεις εναλλακτικές επιλογές για να εγκαταστήσετε το "Aspose.Words for .NET" ή το "Aspose.Total for .NET" στο σύστημά σας.Επιλέξτε αυτό που μοιάζει με τις ανάγκες σας και ακολουθήστε τις οδηγίες βήμα προς βήμα:<br /><br />

- Εγκαταστήστε ένα [Πακέτο NuGet](https://www.nuget.org/packages/Aspose.Words/). Δείτε το [Τεκμηρίωση](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- Εγκαταστήστε τη βιβλιοθήκη χρησιμοποιώντας [Κονσόλα Package Manager](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) στο Visual Studio IDE
- Εγκαταστήστε τη βιβλιοθήκη με το χέρι χρησιμοποιώντας [Windows Installer](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

Το προϊόν μας είναι πλήρως cross-platform και υποστηρίζει όλες τις σημαντικές υλοποιήσεις .NET σύμφωνα με την προδιαγραφή «.NET Standard 2.0»:<br /><br />

- Microsoft .NET Framework, ξεκινώντας από την παλαιότερη έκδοση 2.0 και τελειώνοντας με το πιο πρόσφατο ".NET Framework 4.8"
- .NET Core, ξεκινώντας από το παλαιότερο 2.0 και τελειώνοντας με το πιο πρόσφατο '.NET 6'
- Mono >= 2.6.7
<br /><br />
Καθώς ο κώδικας .NET δεν βασίζεται στο υποκείμενο υλικό ή το λειτουργικό σύστημα, αλλά μόνο σε μια Εικονική Μηχανή, έτσι είστε ελεύθεροι να αναπτύξετε οποιοδήποτε είδος λογισμικού για Windows, macOS, Android, iOS και Linux.Απλώς βεβαιωθείτε ότι έχετε εγκαταστήσει την αντίστοιχη έκδοση των .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.<br /><br />
Συνιστούμε να χρησιμοποιήσετε το Microsoft Visual Studio, το Xamarin και το MonoDevelop IDE για τη δημιουργία εφαρμογών C#, F#, VB.NET.
<br /><br />
Για περισσότερες λεπτομέρειες, ανατρέξτε στο [Τεκμηρίωση προϊόντος](https://docs.aspose.com/words/net/system-requirements/).

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
                          <span itemprop="name"><b>Μπορώ να χρησιμοποιήσω τον παραπάνω κώδικα .NET στην εφαρμογή μου;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ναι, μπορείτε να κάνετε λήψη αυτού του κώδικα και να τον χρησιμοποιήσετε για την ανάπτυξη εφαρμογής σχολιασμού εγγράφων που βασίζεται σε .NET.Αυτός ο κώδικας μπορεί να χρησιμεύσει ως πολύτιμος πόρος για τη βελτίωση της λειτουργικότητας και των δυνατοτήτων των έργων σας στον τομέα της επεξεργασίας και χειρισμού εγγράφων υποστήριξης.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Αυτή η διαδικτυακή εφαρμογή σχολιασμού εγγράφων λειτουργεί μόνο σε Windows;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Έχετε την ευελιξία να ξεκινήσετε τον σχολιασμό εγγράφων για την αφαίρεση σχολίων σε οποιαδήποτε συσκευή, ανεξάρτητα από το λειτουργικό σύστημα στο οποίο εκτελείται, είτε είναι Windows, Linux, Mac OS ή Android.Το μόνο που απαιτείται είναι ένα σύγχρονο πρόγραμμα περιήγησης και μια ενεργή σύνδεση στο Διαδίκτυο.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Είναι ασφαλές να χρησιμοποιήσετε την ηλεκτρονική εφαρμογή για να σχολιάσετε το έγγραφο DOCX;</b></span>
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
                          <span itemprop="text">Μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού, όπως το Google Chrome, το Firefox, το Opera ή το Safari για online σχολιασμό εγγράφων DOCX.Ωστόσο, εάν αναπτύσσετε μια εφαρμογή επιτραπέζιου υπολογιστή, συνιστούμε να χρησιμοποιήσετε το API επεξεργασίας εγγράφων Aspose.Total για αποτελεσματική διαχείριση.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}