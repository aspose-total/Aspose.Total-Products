---
title: C# API για εξαγωγή EML σε XPS
description: Μετατροπή EML σε XPS χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/eml-to-xps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: XPS
otherformats: DOC PS WORDML DOCX PNG DOTM SVG EMF ODT MD DOTX OTT XPS EPUB GIF DOT JPEG DOCM RTF PCL TIFF PDF FLATOPC TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EML σε XPS μέσω .NET" h2=".NET API για απόδοση EML σε XPS σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EML σε δυνατότητες μετατροπής XPS μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EML σε XPS" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή XPS χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Xps ως SaveFormat
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
Πριν μετατρέψετε το EML σε XPS, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό eml, μπορείτε να φορτώσετε το έγγραφο EML, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων XPS μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EML στο XPS, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EML σε XPS μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Αρχείο Μηνύματος Ηλεκτρονικού (EML) χρησιμοποιείται για το αποθήκισμα κειμένων ηλεκτρονικών μηνυμάτων, γεγονός που το καθιστά κατάλληλο για τη δημιουργία στατικών εγγράφων και μηνυμάτων. Ωστόσο, όταν εργαζόμαστε με δυναμικά πολυμέσα δεδομένα, αρχείο XPS (XML Paper Specification) γίνεται απαραίτητο για τη διατήρηση του στυλισμού και του σχεδίου του περιεχομένου.

Η μετάδοση αρχείων EML σε μορφή XPS είναι απαραίτησιμη για να ενεργοποιήσετε πλήρως τις δυνατότητες σας για τη διατήρηση και παρουσίαση των εγγράφων σας. Η μετατροπή αυτή επιτρέπει:

**Πωtieres Use Cases:**

*   **Αρχειοπορεσέρβηση Δокументών**: Μετατροπή αρχείων EML για να διατηρήσετε ιστορικά ηλεκτρονικά μηνύματα, εγγράφους και μηνύματα σε μορφή που διατηρεί το αρχικό τους σχέδιο και στυλισμό.
*   **Εκδοση Ε-书**: Χρήση του XPS για τη δημιουργία διαδραστικών ε-书, ενώ διατηρείται ο στυλισμός και η γραμματολογία του κειμένου για μια άριστη εμπειρία ανάγνωσης.
*   **Διεξεγνώσιμη Ληξυχή**: Μετατροπή αρχείων EML για να επαληθεύσετε ψηφιακά υπογραφάρια και να διασφιστείτε την αυθεντικότητα των ηλεκτρονικών μηνυμάτων και εγγράφων.
*   **Συναφτότητα με Πρότυπα Αccessibility**: Χρήση του XPS για τη δημιουργία εγγράφων που συμφωνούν με τα πρότυπα WCAG, εξασφαλίζοντας την συμβατότητά τους με τεχνολογίες βοηθήσματος.
*   **Αναλυτική Ωρίωση**: Μετατροπή αρχείων EML για να αναλύσετε το περιεχόμενο ηλεκτρονικών μηνυμάτων προς σκοπό ωμολογικής ανάλυσης, όπως η προσδιογή της τοποθεσίας του αποστολέα ή η ταξινόμηση του μαλαιζίου.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}