---
title: C# API για εξαγωγή EML σε TEXT
description: Μετατροπή EML σε TEXT χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/eml-to-text/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TEXT
otherformats: PNG DOT DOTM JPEG ODT MD XPS PS WORDML DOCX FLATOPC EPUB SVG TIFF DOTX RTF OTT DOCM DOC PDF PCL GIF TEXT EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EML σε TEXT μέσω .NET" h2=".NET API για απόδοση EML σε TEXT σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EML σε δυνατότητες μετατροπής TEXT μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EML σε TEXT" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EML μέσω .NET" %}}
Πριν μετατρέψετε το EML σε TEXT, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό eml, μπορείτε να φορτώσετε το έγγραφο EML, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων TEXT μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EML στο TEXT, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EML σε TEXT μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Αρχείο Μηνύματος Ηλεκτρονικού (EML) χρησιμοποιείται για το αποθήκισμα πληροφοριών κειμένου, καθ'όσο αυτό είναι ιδανικό για τη δημιουργία可读έων μηνυμάτων και εμαιλών. Ωστόσο, όταν εργάζονται με περιεχόμενο πολυμέσως, έγγραφα όπως PDFs γίνονται απαραίτητα για τη διαμοιξή και την άποψη.

Η μετατροπή αρχείων EML σε Στοιχεία Κειμένου είναι αναγκαία για να ενεργοποιήσετε πλήρως τα δυναμικά σας περιεχόμενο και τις δυνατότητες ανάλυσης. Η μετάδοση αυτή επιτρέπει:

**Πωtiered Uses:**

*   **Ανάλυση μηνυμάτων**: Μετατροπή αρχείων EML για να αναλύσετε εμαιλς μηνύματα, να跟踪ήσετε το συμπεριφορά του αποστολέα και να εντοπίσετε μοτίβους επικοινωνίας.
*   **Αυτόματη Εκμεταλλευση Email Marketing**: Χρήση Στοιχείων Κειμένου για να βιζιτενίσσετε δεδομένα email marketing, να αυτοματοποιήσετε καμπάνες και να μετράξουμε τα ανοικτικά率.
*   **Δокументация Υποστήριξης Πελάτη**: Μετατροπή αρχείων EML για να δημιουργήσετε可读έα documentation, FAQs και βάσεις γνώσεων πελατών, ενισχύοντας καλύτερα υπηρεσίες υποστήριξης.
*   **Αποθήκισμα Ιστορικού**: Χρήση Στοιχείων Κειμένου για να αποθηκεύσετε και να ανακτήσετε ιστορικά αρχεία εμαιλών, συνετό προς όφελους κανονισμούς και απαιτήσεις αποθήκευσης.
*   **Επανεπίμεξαμενη Περιεχόμενης**: Μετατροπή αρχείων EML για να δημιουργήσετε περιεχόμενο που μπορεί να μοιδίνει, όπως άρθρα μπλогου, ενημερώσεις social media και ανακοινώσεις τύπου, ενισχύοντας καλύτερη συμμετοχή και εμβαδό.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}