---
title: Καταργήστε το DOCM Annotation Online ή διαχειριστείτε τους σχολιασμούς μέσω Java
description: διαγράψτε σχόλια από το αρχείο DOCM μέσω της διαδικτυακής εφαρμογής δωρεάν. Java API κώδικα για τη διαχείριση σχολίων αρχείων DOCM.

family: total
platformtag: Java
feature: Annotate
informat: DOCM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Διαγράψτε τα σχόλια από το DOCM Document Online ή Διαχείριση μέσω Java" h2="Αναπτύξτε μια ισχυρή εφαρμογή βοηθητικού προγράμματος σχολιασμού εγγράφων DOCM που βασίζεται σε Java.Παρατίθεται κώδικας για τη διαχείριση σχολίων του αρχείου DOCM μέσω Java." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Κατάργηση DOCM Annotations Online" %}}

1. Εισαγάγετε το αρχείο DOCM για να διαγράψετε σχόλια ανεβάζοντάς το
1. Κάντε το κάνοντας κλικ μέσα στην περιοχή απόθεσης μέσω μεταφοράς και απόθεσης της εφαρμογής σχολιασμού
1. Ανάλογα με το μέγεθος του αρχείου DOCM και την ταχύτητα του Διαδικτύου, περιμένετε μερικά δευτερόλεπτα
1. Κάντε κλικ στο κουμπί "Κατάργηση" για να διαγράψετε τα σχόλια
1. Κατεβάστε το αρχείο άμεσα

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Καταργήστε τα σχόλια του εγγράφου DOCM μέσω Java" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Java
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Λάβετε όλα τα σχόλια από όλους τους κόμβους χρησιμοποιώντας το [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) και το NodeType.COMMENT
1. Επικαλέστε τη μέθοδο [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) για να διαγράψετε όλα τα σχόλια
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Παράδειγμα κώδικα σε Java για τη διαγραφή σχολίων από το αρχείο DOCM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Αφαιρέστε και προσθέστε την απάντηση σχολίου DOCM" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Java
1. Φόρτωση εγγράφου μέσω αντικειμένου κλάσης εγγράφου
1. Λάβετε σχόλια χρησιμοποιώντας το getChild
1. Χρησιμοποιήστε το [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) για την κατάργηση της καθορισμένης απάντησης σε αυτό το σχόλιο
1. Χρησιμοποιήστε το [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) για να προσθέσετε οποιαδήποτε απάντηση σε αυτό το σχόλιο
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Προσθήκη σχολίων μέσω Java" %}}

1. Προσθήκη αναφοράς βιβλιοθήκης στο έργο Java
1. Δημιουργία αντικειμένου κλάσης εγγράφου
1. Χρησιμοποιήστε το [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) για να δημιουργήσετε το σχόλιο
1. Χρησιμοποιήστε getParagraphs().add και getFirstParagraph().getRuns().add
1. Καλέστε τη μέθοδο αποθήκευσης για να αποθηκεύσετε το αρχείο with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Κώδικας Java για να αφαιρέσετε και να προσθέσετε απάντηση σχολίου από το αρχείο DOCM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java Code: Προσθήκη σχολίων" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Αναπτύξτε DOCM Document Annotation Application μέσω Java</h2>

Χρειάζεστε να αναπτύξετε μια εφαρμογή ή βοηθητικό πρόγραμμα σχολιασμού DOCM για να παρέχετε σχόλια, να κάνετε προτάσεις ή να συνεργαστείτε με άλλους στο έγγραφο;Με το [Aspose.Words for Java](https://products.aspose.com/words/java/) ένα θυγατρικό API του [Aspose.Total for Java](https://products.aspose.com/total/java/), οποιοσδήποτε προγραμματιστής Java μπορεί να ενσωματώσει τον παραπάνω κώδικα API στην εφαρμογή σχολιασμού εγγράφων του.Η ισχυρή βιβλιοθήκη Java επιτρέπει τον προγραμματισμό οποιασδήποτε λύσης σχολιασμού εγγράφων. Επιπλέον, μπορεί να υποστηρίξει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής DOCM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Βιβλιοθήκη Java για σχολιασμό αρχείων DOCM" %}}
Υπάρχουν εναλλακτικές επιλογές για να εγκαταστήσετε το "[Aspose.Words for Java](https://products.aspose.com/words/java/)" ή το "[Aspose.Total for Java](https://products.aspose.com/total/java/)" στο σύστημά σας.Το πακέτο Java μας έχει σχεδιαστεί για να είναι cross-platform, συμβατό με υλοποιήσεις JVM σε διάφορα λειτουργικά συστήματα όπως Microsoft Windows, Linux, macOS, Android και iOS. Επιλέξτε αυτό που μοιάζει με τις ανάγκες σας και ακολουθήστε τις οδηγίες βήμα προς βήμα:<br />

- Εγκαταστήστε το [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)
- Ή από το [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)
- Βήμα προς βήμα [Οδηγίες](https://docs.aspose.com/words/java/installation/#install-aspose-words-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

- Java SE 7 ή πρόσφατες εκδόσεις Java
- Ξεχωριστό πακέτο για Java SE 6 σε περίπτωση που έχετε αυτό το ξεπερασμένο JRE.

<br />
Για λεπτομέρειες JogAmp JOGL, Harfbuzz γραμματοσειράς και Java Advanced Imaging JAI, ανατρέξτε στο [Τεκμηρίωση προϊόντος](https://docs.aspose.com/words/java/system-requirements/#optional-dependencies).

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
                          <span itemprop="name"><b>Μπορώ να χρησιμοποιήσω τον παραπάνω κώδικα Java στην εφαρμογή μου;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ναι, μπορείτε να κάνετε λήψη αυτού του κώδικα και να τον χρησιμοποιήσετε για την ανάπτυξη εφαρμογής σχολιασμού εγγράφων που βασίζεται σε Java.Αυτός ο κώδικας μπορεί να χρησιμεύσει ως πολύτιμος πόρος για τη βελτίωση της λειτουργικότητας και των δυνατοτήτων των έργων σας στον τομέα της επεξεργασίας και χειρισμού εγγράφων υποστήριξης.</span>
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
                          <span itemprop="name"><b>Είναι ασφαλές να χρησιμοποιήσετε την ηλεκτρονική εφαρμογή για να σχολιάσετε το έγγραφο DOCM;</b></span>
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
                          <span itemprop="text">Μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού, όπως το Google Chrome, το Firefox, το Opera ή το Safari για online σχολιασμό εγγράφων DOCM.Ωστόσο, εάν αναπτύσσετε μια εφαρμογή επιτραπέζιου υπολογιστή, συνιστούμε να χρησιμοποιήσετε το API επεξεργασίας εγγράφων Aspose.Total για αποτελεσματική διαχείριση.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}