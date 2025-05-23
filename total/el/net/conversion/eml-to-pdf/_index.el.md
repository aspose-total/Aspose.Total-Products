---
title: C# API για εξαγωγή EML σε PDF
description: Μετατροπή EML σε PDF χωρίς χρήση του Microsoft Word ή του Outlook στο .NET
url_ignore: /el/net/conversion/eml-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PDF
otherformats: DOCX DOC SVG FLATOPC WORDML MD PNG TIFF DOTM DOT XPS TEXT EPUB DOCM JPEG GIF PS DOTX RTF PDF OTT EMF ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Εξαγωγή EML σε PDF μέσω .NET" h2=".NET API για απόδοση EML σε PDF σε Windows, macOS και Linux χωρίς χρήση Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Εάν είστε προγραμματιστής .NET που θέλει να προσθέσει EML σε δυνατότητες μετατροπής PDF μέσα στις εφαρμογές σας, τα API χειρισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ο τρόπος προς τα εμπρός. Χρησιμοποιώντας το [Aspose.Email for .NET](https://products.aspose.com/email/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε την HTML σε PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για Μετατροπή EML σε PDF" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την τάξη [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EML μέσω .NET" %}}
Πριν μετατρέψετε το EML σε PDF, εάν θέλετε να βεβαιωθείτε ότι μετατρέπετε το σωστό eml, μπορείτε να φορτώσετε το έγγραφο EML, να το αναλύσετε και να ρίξετε μια ματιά στην επιθυμητή ιδιότητα. Χρησιμοποιώντας την κλάση [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) του [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, μπορείτε να λάβετε πληροφορίες αποστολέα και παραληπτών. Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο μήνυμα ηλεκτρονικού ταχυδρομείου αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία εγγράφων PDF μέσω .NET" %}}
Κατά την αποθήκευση του εγγράφου από το EML στο PDF, ίσως χρειαστεί να προστατεύσετε το έγγραφο εξόδου σας. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να είναι χρήσιμο για να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας. Το API [Aspose.Words for .NET](https://products.aspose.com/words/net/), σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας το [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) παράμετρος απαρίθμησης. Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου EML σε PDF μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Αρχείο ηλεκτρονικού μηνύματος (EML) χρησιμοποιείται για το αποθήκισμα κειμένων που βασίζονται σε μήνυμα, καθ'όσο αυτό είναι ιδανικό για τη μετάδοση και την接收ση ειλικριών. Ωστόσο, όταν πρόκειται για την παρουσίαση έγγραφων με επαγγελματικό χαρακτήρα, τα PDFs γίνονται απαραίτητα για τη δημιουργία εντυπωσιακά εγγράφων, τη υπογραφή ηλεκτρονικών υπογραφτών και την αρχιβόκτηση ψηλών.

Η μετατροπή αρχείων EML σε μορφή PDF είναι απαραίτηλη για να ενεργοποιήσετε τις δυνατότητες σας:

**Πωλούνται χρήσεις:**

*   **Επαγγελματικά έγγραφα**: Μετατρέψτε αρχεία EML σε PDF για τη δημιουργία επαγγελματικών εγγράφων, όπως προτάσεις, σύμβασια και παρουσιάσιά.
*   **Ηλεκτρονικές υπογραφές και ψηλές αποθήκισεις**: Χρησιμοποιήστε το PDF για να ενεργοποιήσετε ασφαλείς ηλεκτρονικές υπογραφές και ψηλές αποθήκισεις ευαίστηρων εγγράφων, σύμφωνα με τα κανονικά περί του θέματος.
*   **Τυπωτική επί πριμ**: Μετατρέψτε αρχεία EML σε PDF για να δημιουργήσετε υψηλής ποιότητας τυπωμένα υλικό, όπως φυλλάκια, δελτίδια και κάρτες επαγγελματίκων, για καμπάνες μάρκετινγκ και εκδηλώσεις.
*   **Διαισθησιμότητα και包容ικότητα**: Χρησιμοποιήστε το PDF για να κάνει τα έγγραφα περισσότερο διαίτηλα προς τους άτομα με αναπηδούς, μετατρέψτα τα αρχεία σε ψηλές ή κατεξοχένες μορφές κειμένου.
*   **Δινομηρηκή διανομή και συνεργασία**: Μετατρέψτε αρχεία EML σε PDF για να μοιδήσετε έγγραφα ασφαλώς μέσω email ή μέσω πλατφορμών συνεργασίας online, ενισχύοντας τα ρυθμά σας και τη παραγωγικότητά σας.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}