---
title: C# API για εξαγωγή EMAIL σε XPS
description: Μετατροπή EMAIL σε XPS χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/email-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: ODT DOTM DOCX PDF JPEG TEXT DOCM WORDML RTF PS PNG TIFF DOTX EMF XPS GIF MD DOC OTT DOT SVG PCL EPUB FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EMAIL σε XPS μέσω .NET" h2=".NET API για απόδοση EMAIL σε XPS σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EMAIL σε δυνατότητες μετατροπής XPS μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EMAIL σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EMAIL σε XPS" %}}
1. Ανοίξτε το αρχείο EMAIL χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Μετατρέψτε το EMAIL σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMAIL μέσω .NET" %}}
Πριν μετατρέψετε το EMAIL σε XPS, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό email, μπορείτε να φορτώσετε το έγγραφο EMAIL, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων XPS μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EMAIL στο XPS, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EMAIL σε XPS μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Μετατροχούμε Email σε Αρχιπέγγραμματα XPS: Απεντοίπωση της Δύναμης του Βιζουαλ Κοντέντα.

Emails είναι ένα βασικό εργαλείο επικοινωνίας, αλλά όταν γίνεται λόγος για περιεχόμενο βιζουαλ, συχνά δεν είναι αρκετό. Από άποψη άλλων μορφών, όπως PDF ή XPS, τα οποία διατηρούν το αρχικό γραφικό και το σχήμα, οι email μπορούν να χαθούν σε ποιότητα εικόνων και στοιχεία καττακύψας κατά την μετάδοση.

Εδώ έρχεται η μετατροπή. Η μετατροπή email σε αρχιπέγγραμματα XPS είναι ένα απλό过程 που σας επιτρέπεται:

**Πωtiered Benefits:**

*   **Απώλεια Μηδέν Βιζουαλ Περιεχόμενου**: Μετατροπή email σε αρχιπέγγραμματα XPS για να διατηρίσετε το βιζουαλ περιεχόμενο σας, ακόμα και όταν το κοιτάτε ή το αποθηκεύετε.
*   **Εντυπωσιακά Επικοινωνία**: Χρησιμοποιήστε αρχιπέγγραμματα XPS για να δημιουργήσετε εντυπωσιακές εκδόσεις email, ιδανικές για παρουσίαση, αναφορά ή άλλη επίσημη επικοινωνία.
*   **Ασφάλεια και Συμμόδεια**: Μετατροπή email σε αρχιπέγγραμματα XPS για να συμμορφώσετε με νομολογικούς απαιτήσεις και να διατηρίσετε τη βεδαριά του ευαίσθηου περιεχόμενου σας.
*   **Αρχιβόζηση και Διατήρηση**: Αποθηκεύετε αρχιπέγγραμματα XPS για να διατηρίσετε τα αρχεία email και τις εικόνες σας για μελλοντική αναφορά ή συμμόδεια.
*   **Διαоступιμότητα και Συνοδηγία**: Μετατροπή email σε αρχιπέγγραμματα XPS για να βελτιώσετε την διαθεσιά σας προς όσους έχουν περιορισμένες δυναμικότητες όρασης.

Μετατροχούμε τις email σας σε αρχιπέγγραμματα XPS και ανοίγουμε τη πύλη προς την πλήρη δυναμική του βιζουαλ περιεχόμενου σας.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}