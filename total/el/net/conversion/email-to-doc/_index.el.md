---
title: C# API για εξαγωγή EMAIL σε DOC
description: Μετατροπή EMAIL σε DOC χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-doc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOC
otherformats: TEXT RTF DOC JPEG EMF EPUB DOT GIF PCL WORDML ODT TIFF SVG DOCM MD DOTX PS DOTM DOCX OTT PDF XPS FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε DOC μέσω .NET" h2=".NET API για απόδοση EMAIL σε DOC σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής DOC μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε DOC" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Doc ως SaveFormat
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
Πριν μετατρέψετε το EMAIL σε DOC, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων DOC μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο DOC, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε DOC μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Τα αρχεία email είναι ευρύτερα χρησιμοποιούμενα για την επικοινωνία, αλλά όταν έρχεται η ώρα να共χύσιζουμε και να αναλύουμε δεδομένα, τα Microsoft Office αρχεία (DOC) γίνονται απαραίτητα. Η μετάθεση των αρχών email σε μορφή DOC ενεργοποιεί πλήρως τις δυνατότητες σας για δημιουργία και ανάλυση εγγράφων.

Η μετάθεση των αρχών email σε μορφές DOC είναι απαραίτηλη για να ενεργοποιήσετε πλήρως τις δυνατότητες σας για δημιουργία και ανάλυση εγγράφων. Η αυτή μεταβολή σας επιτρέπει να:

**Περιπτώσεις χρήσης:**

*   **Υποβολή Πρότασης Έργου**: Μεταθέστε αρχεία email σε μορφή DOC για να δημιουργήσετε συνοπτικές και επαγγελματικές προτάσεις έργου, που θα περιέχουν βασικές λεπτομέρειες και ημερομηνίες υποβολής.
*   **Δокументοποίηση ΜεETINGs**: Χρησιμοποιήστε τα DOC αρχεία για να οργανώσετε λεπτομερές πρακτικά συνεδριάσεων, άγορες εγράφων και αποφάσεις που λήφθηκαν κατά τη συνεδρίαση.
*   **Ανάλυση Συμβολαίων**: Μεταθέστε αρχεία email σε μορφή DOC για να αναλύσετε συμβόλαια, διασφαλίζοντας ότι όλες οι όροι και προϋποθήκες είναι σαφές μεταξύ των δύο сторін.
*   **Υποβολή Αφίξεων και Επιστολαίων**: Δημιουργήστε επαγγελματικές αφίσες και επιστολές χρησιμοποιώντας模板 DOC, προσαρμοζόμενοι τα εγγράφά σας σε συγκεκριμένες αιτήσεις εργασίας.
*   **Γέννηση Αναφορών Συνεδριάσεων**: Χρησιμοποιήστε τα DOC αρχεία για να δημιουργήσετε αναφορές συνεδριάσεων, που θα περιέχουν βασικές παρουσλέσεις, συζητήσεις και αποτελέσματα.

Ματαξείνοντας τα αρχεία email σε μορφή DOC, είστε σε θέση να διαχειριζείτε και να αναλύσετε μερικώς τις ανάγκες σας για δημιουργία εγγράφων.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}