---
title: C# API για εξαγωγή EMAIL σε TEXT
description: Μετατροπή EMAIL σε TEXT χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: EPUB GIF MD RTF DOCM PCL FLATOPC JPEG PDF EMF WORDML DOTX ODT DOTM DOC DOT XPS SVG PNG DOCX OTT TIFF TEXT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε TEXT μέσω .NET" h2=".NET API για απόδοση EMAIL σε TEXT σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής TEXT μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε TEXT" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή TEXT χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Text ως SaveFormat
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
Πριν μετατρέψετε το EMAIL σε TEXT, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων TEXT μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο TEXT, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε TEXT μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η μετάφραση του κειμένου στον ελληνικό γλώσσα:

Η ανάμεση από ηλεκτρονικά μηνύματα (Email to Text Conversion) είναι μια μέθοδος για να εξτράχουμε πληροφορίες, την οποία μπορούμε να χρησιμοποιήσουμε για να δημιουργήσουμε γραπτά αρχεία και συνοπτικά σημειώματα. Όμως, όταν εργαζόμαστε με μακρές αλυσίδες μηνυμάτων, εργαλεία όπως τα παλάτια ηλεκτρονικών μηνυμάτων είναι απαραίτητα για να οργανωθούν και να跟踪θούν οι συνομιλίες.

Η μετάθεση των ηλεκτρονικών μηνυμάτων σε αρχεία κειμένου είναι απαραίτηση για να ενεργοποιήσουμε πλήρως τις δυνατότητες μας για τη διατήρηση αρχείου και την σύνθεση συνοπτικών σημειωμάτων. Η αυτή μεταφορά επιτρέπει:

**Περιγραφόμενες χρήσεις:**

*   **Αρχιβування ηλεκτρονικών μηνυμάτων**: Μεταφέρω τα ηλεκτρονικά μηνύματα για να δημιουργήσω γραπτά αρχεία, αρχίβα και συνοπτικά σημειώματα προς ιστορική αναφορά.

*   **Ανάλυση επικοινωνίας πελατών**: Χρησιμοποιώ αρχεία κειμένου για να αναλύω τις συνομιλίες πελατών, να跟踪ω τα ζητήματα και να εντοπίσω τάσεις στην επικοινωνία.

*   **Συνοπτικά σημειώματα και πράξεις συνεδριών**: Μεταφέρω τα ηλεκτρονικά μηνύματα για να δημιουργήσω συνοπτικά σημειώματα, σημειώματα συνεδριών και πρακτικές βραχυπρόσθεγες προς ομάδα και στόλους.

*   **Μonitoring καμπανιών μάρκετινγκ**: Χρησιμοποιώ αρχεία κειμένου για να παρακολυφώ τις συνομιλίες σχετικά με καμπάνιες μάρκετινγκ, να跟踪ω τις απαντήσεις και να μέτρω την εμπλοκή.

*   **Διατήρηση νόμου**: Μεταφέρω τα ηλεκτρονικά μηνύματα για να δημιουργήσω επίσημα γραπτά αρχεία, αποδεικτικά και πρακτικά προς σκοπό του δικαίου.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}