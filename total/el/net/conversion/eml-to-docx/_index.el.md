---
title: C# API για εξαγωγή EML σε DOCX
description: Μετατροπή EML σε DOCX χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/eml-to-docx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: PCL PDF TEXT RTF DOTM DOCM DOT MD DOTX TIFF DOCX FLATOPC WORDML EMF XPS PS EPUB OTT GIF ODT PNG JPEG DOC SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EML σε DOCX μέσω .NET" h2=".NET API για απόδοση EML σε DOCX σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EML σε δυνατότητες μετατροπής DOCX μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε DOCX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EML σε DOCX" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOCX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Docx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EML μέσω .NET" %}}
Πριν μετατρέψετε το EML σε DOCX, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό eml, μπορείτε να φορτώσετε το έγγραφο EML, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων DOCX μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EML στο DOCX, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EML σε DOCX μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Τα αρχεία EML (Electronic Mail) χρησιμοποιούνται για το αποθήκισμα κειμένων, τα οποία είναι ιδανικά για τη μετάδοση και την接收ση ελектρονημάτων. Ωστόσο, όταν απαιτούνται διαμόρφωση και παρουσίαση, το Microsoft Word (.docx) γίνεται η επιλογή που προτιμάται.

Η μετατροπή αρχείων EML σε μορφή .docx είναι αναγκαία για να ενεργοποιήσετε πλήρως τις δυνατότητες σας στη διαμόρφωση εγγράφων. Αυτή η μετατροπή σας επιτρέπει:

**Πωσές χρήσης:**

*   **Επικοινωνία Επιχειρήσεων**: Μετατροπή αρχείων EML για τη δημιουργία εγγράφων με εμφάνιση επαγγελματική, όπως σημειώσεις συνεδριάσεων, ενημερώσεις έργου και πρόταση business.
*   **Ατομική Επικοινωνία**: Χρήση του Word για τη διαμόρφωση και επεξεργασία προσωπικών ελ.δ., επιστολών και μηνυμάτων, εξασφαλίζοντας έναν τόνο γυμνασμένος και αναγλύψιμος.
*   **Σημειώσεις Συνεδριάσεων και Δελτίρια**: Μετατροπή αρχείων EML για τη δημιουργία λεπτομερών και οργανωμένων σημειώσεων συνεδριάσεων και δελτίριων, ενισχύοντας την ακρίβεια της καταγραφής και τη δυνατότητα ακολούθου.
*   **Γραπτή και Ακαδημαϊκή Γραφή**: Μετατροπή αρχείων EML για τη δημιουργία εγγράφων με μορφή, όπως άρθρα, πेपερς ερεασών και διατριβές, ενισχύοντας την ευκολία επεξεργασίας και συνεργασίας.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}