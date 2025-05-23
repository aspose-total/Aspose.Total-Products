---
title: C# API για εξαγωγή EMLX σε PNG
description: Μετατροπή EMLX σε PNG χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/emlx-to-png/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: PNG JPEG DOCX FLATOPC TEXT OTT XPS WORDML ODT DOTX EPUB DOC PS TIFF RTF GIF MD DOCM SVG EMF DOTM DOT PDF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMLX σε PNG μέσω .NET" h2=".NET API για απόδοση EMLX σε PNG σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMLX σε δυνατότητες μετατροπής PNG μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMLX σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMLX σε PNG" %}}
1. Ανοίξτε το αρχείο EMLX χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMLX σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή PNG χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Png ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMLX μέσω .NET" %}}
Πριν μετατρέψετε το EMLX σε PNG, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό emlx, μπορείτε να φορτώσετε το έγγραφο EMLX, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων PNG μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMLX στο PNG, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMLX σε PNG μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Το αρχιτύπογραφη Μεσσηγένηδοτη (EMF) αρχεία χρησιμοποιούνται για το αποθήκις πληροφορομένων ράστερ εικόνων, καθ'όπω είναι ιδανικά για τη δημιουργία στατικών εικόνων και εικονογραφήσεων. Ωστόσο, όταν εργαζόμαστε με δεδομένα που απαιτούν δυναμική επεξεργασία, άλλα αρχιτύπογραφη μορφές γίνονται απαραίτητες για τη λειτουργία επεξεργασίας και τροποποίησης εικόνων.

Η μετατροπή αρχιτύπογραφη αρχείων σε μορφή PNG είναι απαραίτητη για να ενεργοποιήσετε πλήρως τις δυνατότητες σας στην επεξέργωση και τροποποίηση εικόνων. Η αυτή μετατροπή επιτρέπει:

**Πωtiered Use Cases:**

* **Επεξεργασία εικόνων και τροποποίηση**: Μετατροπή αρχιτύπογραφη αρχείων για επεξέργωση και τροποποίηση εικόνων, προσθήκη κειμένου, σχήμάτων και εφέκτων.
* **Σχεδιασμός ikonόσ και ανάπτυξη**: Χρήση PNG για τη δημιουργία可缩放ικονών, λογότυπων και γραφικών για πολλά προγράμματα.
* **Γραφικά και εικονογραφίες**: Μετατροπή αρχιτύπογραφη αρχείων για την δημιουργία σύνθετων εικονογραφιών, γραφικών και animáσεων που μπορούν να χρησιμοποιηθούν σε δημοσίευσεις.
* **Optimization for Web and Mobile Devices**: Χρήση PNG για την optimίωση εικόνων για ιστοσελίδες και κινητικά συστήματα, διασφαλίζοντας γρήγορη φόρμαση και υψηλή ποιότητα εικόνων.
* **Δεδομένα vizualισα και αναφορές**: Μετατροπή αρχιτύπογραφη αρχείων για τη δημιουργία interaktιβών vizουαλισάτων και αναφορών, χρησιμοποιώντας PNG για την εμφάνιση δεδομένων που βασίζονται σε πληροφορίες.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}