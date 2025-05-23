---
title: C# API για εξαγωγή EMAIL σε WORD
description: Μετατροπή EMAIL σε WORD χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: DOCM ODT TEXT PCL OTT DOCX PS FLATOPC EPUB XPS GIF WORD DOTX DOC DOTM MD WORDML PDF DOT JPEG PNG RTF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε WORD μέσω .NET" h2=".NET API για απόδοση EMAIL σε WORD σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής WORD μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε WORD" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή WORD χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Word ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMAIL μέσω .NET" %}}
Πριν μετατρέψετε το EMAIL σε WORD, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων WORD μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο WORD, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε WORD μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Ενσωδεύζοντας>Emails到Word文档: Απλήωση της Πotential Communication Capabilities

Τα εμαιλς είναι ιδανικά για αποθήκευση σύντομων μηνύων, άρα είναι κατάλληλα για εποχικές επικοινωνίες και μη επίσημες διακωσίες. Ωστόσο, όταν ακούειται γιά δημιουργία επίσημων εγγράφων και παρουσίασης σκοπός, τα Word文档 γίνονται απαραίτητα για τη μετάδοση σύνθετης πληροφορίας και ιδέών.

Η μετατροπή του περιεχομένου των εμαιλς σε μορφή Word είναι απαραίτηλη για να αποκαλυφθεί η πλήρη δυναμικότητα των δυνάμεων σας στην επικοινωνία. Η αυτή μετατροπή επιτρέπει:

**Πωσές χρήσεις:**

*   **Διεθνείς Αναφορές**: Μετατρέψτε εμαιλς για να δημιουργήσετε επαγγελματικούς εγγράφους δελτίων, που παρέχουν πληροφορίες σχετικά με εταιρικές ανακοινώσεις, οικονομικά δεδομένα και αγοράσεις.

*   **Πολιτικές Αναφορές και Υποψήφια**: Χρησιμοποιήστε Word για να δημιουργήσετε επίσημες πολιτικές αναφορές, υποψήφια και παρουσίαση προς τους αποφασιστές, τους συνεργάτες και τους πελάτες.

*   **Ακαδημαϊκές Συγγραφές και Ερευνές**: Μετατρέψτε εμαιλς για να δημιουργήσετε υψηλής ποιότητας ακαδηματικές εργασίας, ερευνητικά δελτία και αναφορές βιβλιογραφίας, διασφαλίζοντας ακριβείς αναφορές και αναφορές.

*   **Διακοσμητικές Μίνιες και Πρόγραμμα Γελοίου**: Χρησιμοποιήστε Word για να δημιουργήσετε επίσημες μίνιες και πρόγραμματα γέλοιο, ενισχύοντας την αποτελεσματική επικοινωνία και τη διατήρηση εγγράφων.

*   **Ατοπικές Συγγραφές και Blog Posts**: Μετατρέψτε εμαιλς για να δημιουργήσετε ενδιαφέροντες ατοπικούς εγγράφους, blog posts και άρθρα, που υπογραμμίζουν τα γούρτα σας σε γραμματική και δημιουργικότητα.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}