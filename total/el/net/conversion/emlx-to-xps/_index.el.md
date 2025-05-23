---
title: C# API για εξαγωγή EMLX σε XPS
description: Μετατροπή EMLX σε XPS χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/emlx-to-xps/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: XPS
otherformats: TEXT OTT EMF WORDML GIF XPS TIFF DOCM DOCX DOT ODT DOTM DOTX PNG RTF FLATOPC EPUB DOC PS PCL PDF JPEG SVG MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMLX σε XPS μέσω .NET" h2=".NET API για απόδοση EMLX σε XPS σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMLX σε δυνατότητες μετατροπής XPS μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMLX σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMLX σε XPS" %}}
1. Ανοίξτε το αρχείο EMLX χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMLX σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMLX μέσω .NET" %}}
Πριν μετατρέψετε το EMLX σε XPS, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό emlx, μπορείτε να φορτώσετε το έγγραφο EMLX, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων XPS μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMLX στο XPS, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMLX σε XPS μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
ΕΜΛΞ (Electronic Messaging Layer with Extensions) αρχεία χρησιμοποιούνται για το αποθήκισμα πληροφοριών πλάνου, κάνοντας τα ιδανικά για τη μετάδοση εμαιλών και την αλλαγή μηνυμάτων επιχειρησιακού τύπου. Ωστόσο, όταν εργάζονται με δεδομένα που βασίζονται σε εικόνες, έγγραφα με ΣΠΣ (XML Paper Specification) γίνονται απαραίτητα για τη ληψη και τη κοινοποίηση βιζουαλικών περιεχομένων.

Η μετατροπή αρχείων ΕΜΛΞ σε μορφές ΣΠΣ επιτρέπει την εκμελώςευση πλήρης δυναμικότητας των δυνατοτήτων σας για τη μετάδοση και τη ληψη εγγράφων, καθώς και για τη δημιουργία εικόνων. Αυτή η μετατροπή επιτρέπει:

**Αποδόσεις Υποθέσεων:**

*   **Μέταδοση Εγγράφων:** Μετατρέψτε αρχεία ΕΜΛΞ για να μοιδήσετε έγγραφα, απολογιστικά και παρουσιάστικα με συνάδεις και πελάτες σας, διασφαλίζοντας την ακύρση και τη βεβαίωση της ανταλλαγής.
*   **Опτιμισμός Εκτύπωσης:** Χρησιμοποιήστε το ΣΠΣ για να επιτιμήσετε τα layouts, τις εικόνες και τα σχεδια για μια καλύτερη ποιότητα εικόνων και μικρότερα αρχεία.
*   **Επεξεργασία Εικόνων και Αξιοποίηση:** Μετατρέψτε αρχεία ΕΜΛΞ για να επεξεργάζεστε και να βελτιώσετε περιεχόμενα εικόνων,包括 γραφικά, φωτογραφίες και εικαστικά.
*   **Ενορμήωση Ηλεκτρονικής Υπογραφής:** Χρησιμοποιήστε το ΣΠΣ για να ενσωμάσετε ηλεκτρονικές υπογραφές, διασφαλίζοντας την ασφάλεια και τη πιστοποίηση των εγγράφων σας.
*   **Διεγνώσιμη και Συνοδεσία:** Μετατρέψτε αρχεία ΕΜΛΞ για να δημιουργήσετε διαγνώσιμα και συνοδευόμενα έγγραφα, σύμφωνα με πρόσθεγκα Ακύρης Βαρύτηδας, ενισχύοντας τη διαβέτις τους.

Η μετάδοση αυτών των πληροφοριών θα σας βοηθήσει να χρησιμοποιήσετε τα πιθανότερα δυνατά σας για τη δημιουργία, το εμείςσιμο και την κατανομή εγγράφων.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}