---
title: C# API για εξαγωγή EMAIL σε IMAGE
description: Μετατροπή EMAIL σε IMAGE χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε IMAGE μέσω .NET" h2=".NET API για απόδοση EMAIL σε IMAGE σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής IMAGE μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε IMAGE" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή IMAGE χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Image ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMAIL μέσω .NET" %}}
Πριν μετατρέψετε το EMAIL σε IMAGE, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων IMAGE μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο IMAGE, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε IMAGE μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
**Επείσωση Email σε Εικόνα: Απενεργοποίηση της Ραφήσης**

Οι ε-mails είναι αποτελεσματικό μέσο για τη μετάδοση πληροφοριών, αλλά τους λείπει η όραμη που χαρακτηρίζει άλλα μορφά, όπως οι εικόνες. Η μετατροπή αρχιφάιλ email σε μορφή εικόνων είναι απαραίτηλη για να ενεργοποιήσει την πλήρη δυναμική της ραφήσης και να διατήξουμε το περιεχόμενο για μελλοντική αναφορά.

Η μετατροπή αρχιφάιλ email σε μορφή εικόνων είναι κρίσιμη για:

**Πωtier Uses:**

*   **Αποθήκευση Περιεχομένου**: Μετατρέψτε ε-mails σε εικόνες για να 捕ήσετε το περιεχόμενο, όπως σημειώσεις συνεδριάσεων, συμφώνους πωλήσεων ή σχεδίαγματα έργου, και να το κάνετε διαθέσιμο για μελλοντική αναφορά.
*   **Προστασία Μαρκών και Λogowmen**: Χρησιμοποιήστε τη μετατροπή σε εικόνες για να διατήξουν την εταιρική ταυτότηα, τα λογότυπα και άλλα vizуαλτικά στοιχεία από ε-mails, υπολογίζοντας την συνεχή συνέχεια μεταξύ όλων των καναλών επικοινωνίας.
*   **Ψηφιακή Αρχιβόληση**: Μετατρέψτε ε-mails σε εικόνες για να δημιουργήσετε ένα ψηφιακό αρχείο ιστορίας της εταιρείας, συμπεριλαμβανομένων κρίσιμων γεγονότων, σταθμών μέλλοντος και διαδικτυακών αποφάσεων.
*   **Διαоступικότητα και Συνολική Συμμετέχηση**: Μετατρέψτε ε-mails σε εικόνες για να είναι το περιεχόμενο περισσότερο προσβάσιμο σε χρήστες με στρεβλωτικές διασπούνσεις ή αναπηδούς, χρησιμοποιώντας περιγραφές κειμένου替代ικού.
*   **Ασφάλεια και Πετρογραφική Συμμόδεση**: Χρησιμοποιήστε τη μετατροπή για να προστατεύσετε ευαίσθηη πληροφορία από άκραντηλη διακλοπή, συμφωνώντας με τα κανονικά περί πρωτοκόλων δεδομένων και εμπισύωση.

Μετά την μετατροπή αρχιφάιλ email σε μορφή εικόνων, οι οργανώσεις μπορούν να ενεργοποιήσουν τη πλήρη δυναμική της ραφήσης, να διατήξουν το περιεχόμενο και να συμμορφωθούν με τα κανονικά περί πρωτοκόλων δεδομένων.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}