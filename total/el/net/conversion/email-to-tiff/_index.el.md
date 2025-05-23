---
title: C# API για εξαγωγή EMAIL σε TIFF
description: Μετατροπή EMAIL σε TIFF χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-tiff/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TIFF
otherformats: XPS JPEG PNG PS SVG DOCX FLATOPC DOT OTT EPUB MD GIF TEXT DOC PDF ODT WORDML RTF PCL DOTM DOTX DOCM TIFF EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε TIFF μέσω .NET" h2=".NET API για απόδοση EMAIL σε TIFF σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής TIFF μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε TIFF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε TIFF" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή TIFF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Tiff ως SaveFormat
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
Πριν μετατρέψετε το EMAIL σε TIFF, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων TIFF μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο TIFF, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε TIFF μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η μετάδοση των ηλεκτρονικών αρχιβών προς το μορφή TIFF είναι απαραίτηλη για να αποκλειστεί η πλήρης δυναμικότητα των δυνατοτήτων διατήρευσης και αρχιβίσματος εγγράφων. Αυτή η μεταφορά επιτρέπει:

**Υποχρεώσεις χρήσης:**

*   **Αρχιβιστικές Υποστάσεις**: Μεταφέρετε τα ηλεκτρονικά αρχιβών για να διατηρίσετε ιστορικές αποφάσεις, να είστε σε συμμόδεση με νομοθετικά πρότυπα και να διατήξετε την κληρονομιά της εταιρείας σας.
*   **Αναζήτηση Αρχιβίων**: Χρησιμοποιήστε το TIFF για να αναζηξτείτε συγκεκριμένα έγγραφα, να εντοπίσετε χαμένες πληροφορίες και να επιβραδύνετε τα διαδικτυωτικά过程ά του εدارة αρχιβίων.
*   **Απαιτήσεις Ασφάλειας**: Μεταφέρετε τα ηλεκτρονικά αρχιβών για να προστατεύσετε ευαίσθηη δεδομένα, να είστε σε συμμόδεση με κυβερνητικές διατάξεις, και να αποτρέσουμε την άφιξη μη εξουσιοδοτημένων προσώπων ή τη δημοσίευση πληροφοριών εμπιστευτικών.
*   **Συμμόδεση με Δίκες**: Χρησιμοποιήστε το TIFF για να δημιουργήσετε εγγράφους που μπορούν να αποδειχθούν τροποποιημένοι, να δείξτε συμμόδεση με νόμους και να υπερασπίστηκите έναντι κατηγορίας ότι έχουν καταστραφεθεί ή τροποποιηθεί έγγραφα.
*   **Μακρές Περίοδους Αποθήκευσης Αρχιβίων**: Μεταφέρετε τα ηλεκτρονικά αρχιβών για να αποθηκεύσετε εγγράφους για μεγαλύτερες περιόδους, να διατήξετε μακράς διάρκειας διατήρηση δεδομένων και να διατηρίσετε σημαντική επιχειρησιακή πληροφορία.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}