---
title: C# API για εξαγωγή EML σε JPEG
description: Μετατροπή EML σε JPEG χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/eml-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: JPEG
otherformats: FLATOPC DOTX DOC PDF EPUB DOCM DOTM JPEG TEXT PCL PS OTT DOCX GIF MD XPS RTF SVG PNG WORDML DOT EMF TIFF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EML σε JPEG μέσω .NET" h2=".NET API για απόδοση EML σε JPEG σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EML σε δυνατότητες μετατροπής JPEG μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EML σε JPEG" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή JPEG χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Jpeg ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EML μέσω .NET" %}}
Πριν μετατρέψετε το EML σε JPEG, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό eml, μπορείτε να φορτώσετε το έγγραφο EML, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων JPEG μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EML στο JPEG, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EML σε JPEG μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η μετάτροπή αρχείων EML σε μορφή JPEG είναι μια πρακτική μέθοδος για να αξιοποιήσετε τα δεδομένα σας και να δημιουργήσετε εντυπωτικά προεπισήματα ή κομματιαία από τα μηνύματα. Η χρήση αρχών JPEG είναι απαραίτηλη όταν εργάζεστε με εικόνες που έχουν κάνει επειδή αυτά μπορούν να παρουσιάζονται σε μια μορφή που είναι ευχάριστη και εντυπωτική.

Η μετάτροπή αυτών των αρχείων σε μορφή JPEG σας επιτρέπει να:

**Περιφέρετε τα用途:**

* **Δημιουργία καμπάνσεων ηλεκτρονικού ταχυδρομού**: Μετατρέβετε τα αρχεία EML για να δημιουργήσετε εντυπωτικές καμπάνσεις με εικόνες προεπισήματα, δημοσιεύσεις σε κοινωνικά δίκτυα και κομματιαία από τα μηνύματα.
* **Αρχεία νewsletter και μπλог**: Χρησιμοποιείτε τα JPEG για να παρουσιάσετε τα αρχεία σας νewsletter και μπλog με τρόπο που είναι περισσότερο εντυπωτικό για τους αναγνώστες σας.
* **Μοιρασμός σε πλατφόρμες κοινωνικής δικτύωσης**: Μετατρέβετε τα EML αρχεία για να μοιράζετε το περιεχόμενο σας σε πλατφόρμες όπως το Twitter, Facebook ή LinkedIn με εικόνες που είναι ευχάριστες.
* **Δημιουργία προσαρμοσμένων πελατών email**: Μετατρέβετε τα EML αρχεία για να δημιουργήσετε自αδύναμε πελατές email με εντυπωτικές διεπαγγελίες και εμπειρία χρήστη.
* **Παρουσίαση δεδομένων και αναφορά**: Χρησιμοποιείτε τα JPEG για να παρουσιάσετε δεδομένα σε μορφή που είναι περισσότερο εντυπωτική, κάνοντας έτσι ευκολότερη την κατανόηση σύντηλων πληροφοριών από τη μεριά των συνεργατών σας.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}