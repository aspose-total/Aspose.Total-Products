---
title: C# API για εξαγωγή EMAIL σε PDF
description: Μετατροπή EMAIL σε PDF χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: OTT DOT MD ODT TEXT PCL PS SVG DOCX DOTM DOCM JPEG RTF FLATOPC PNG XPS WORDML PDF EPUB DOC EMF DOTX TIFF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε PDF μέσω .NET" h2=".NET API για απόδοση EMAIL σε PDF σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής PDF μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε PDF" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή PDF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Pdf ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMAIL μέσω .NET" %}}
Πριν μετατρέψετε το EMAIL σε PDF, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων PDF μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο PDF, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε PDF μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η ανάπαλη των αρχείου email σε μορφή PDF είναι απαραίτητη για να ενεργοποιήσετε πλήρως τις δυνατότητες σας σε όιανδήποτε διαχείριση εγγράφων. Η αυτή ανάπαλη επιτρέπει:

**Υποχρεώσεις (Use Cases):**

*   **Διεθνείς Υπογραφές και Συμμόσχεση**: Μετατρέψτε τα αρχεία email σε μορφή PDF για να διατηρίσετε επίσημα έγγραφα, να εγγυώσετε τη συμμόσχεση προς τους κανονισμούς και να υποστήξετε τις εξετάσεις.
*   **Μάρκετινγκ Υλικό και Εκστρατεύσεις**: Χρησιμοποιήστε την ανάπαλη σε PDF για να δημιουργήσετε έγγραφα μάρκετινγκ που είναι έτοιμα προς εκτύπωση, φυλλάδες, και εκστρατείες promotion που θα υπογραμμίζουν τη φυσιογνωμία της εταιρείας σας.
*   **Περιβαλλοντικά Μαθήματα και Εκπαίδευση**: Μετατρέψτε τα αρχεία email σε μορφή PDF για να δημιουργήσετε ενεργή εγχειρίδια εκπαίδευσης, υλικό μάθησης και βιβλία σπουδών για φοιτητές ή εργαζόμενοι.
*   **Υποψήφια Επιχειρήσεων και Συμβόλαι**: Χρησιμοποιήστε την ανάπαλη σε PDF για να δημιουργήσετε επαγγελματικά έγγραφα υποψήφιων επιχειρήσεων, συμβόλαι και συμφώνους που θα κοιίσουν καθαρά τη στάση σας.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}