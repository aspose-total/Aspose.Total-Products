---
title: C# API για εξαγωγή PS σε MHTML
description: Μετατροπή PS σε MHTML χωρίς χρήση του Microsoft Word
url_ignore: /el/net/conversion/ps-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MHTML
otherformats: DOTM OTT RTF DOTX FLATOPC DOT WORDML ODT MARKDOWN PCL MHTML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Απόδοση PS σε MHTML μέσω .NET" h2=".NET API για εξαγωγή PS σε MHTML σε Windows, macOS και Linux χωρίς χρήση του Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ένα ισχυρό API για την προσθήκη λειτουργιών χειρισμού εγγράφων και μετατροπής στην εφαρμογή σας .NET. Χρησιμοποιώντας προηγμένο API επεξεργασίας PDF [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου PS σε DOC. Μετά από αυτό, χρησιμοποιώντας το ισχυρό API Επεξεργασίας Εγγράφων [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε το DOC σε MHTML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για μετατροπή PS σε MHTML" %}}
1. Ανοίξτε το αρχείο PS χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το PS σε Έγγραφο χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το αρχείο Doc χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή MHTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Mhtml ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Αποκρυπτογραφήστε το αρχείο PS χρησιμοποιώντας τον κωδικό πρόσβασης κατόχου μέσω .NET" %}}
Πριν μετατρέψετε το PS σε MHTML, εάν θέλετε να αποκρυπτογραφήσετε το έγγραφό σας, μπορείτε να το κάνετε χρησιμοποιώντας το API. Για να αποκρυπτογραφήσετε το αρχείο PDF, πρέπει πρώτα να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να ανοίξετε το PS χρησιμοποιώντας τον κωδικό πρόσβασης του κατόχου. Μετά από αυτό, πρέπει να καλέσετε τη μέθοδο [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) του αντικειμένου Document. Τέλος, αποθηκεύστε το ενημερωμένο αρχείο χρησιμοποιώντας τη μέθοδο Save του αντικειμένου Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργία αρχείου MHTML μόνο για ανάγνωση μέσω .NET" %}}
Για να προστατεύσετε το MHTML σας από την επεξεργασία και να αποτρέψετε άλλα άτομα από την επεξεργασία ευαίσθητων και εμπιστευτικών πληροφοριών στο έγγραφό σας, μπορείτε επίσης να ορίσετε την προστασία του εγγράφου χρησιμοποιώντας το API. Μπορείτε να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Αυτό μπορεί να γίνει χρησιμοποιώντας το [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Σας δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας την παράμετρο απαρίθμησης [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Μπορείτε να ρυθμίσετε το έγγραφό σας σε μόνο για ανάγνωση χρησιμοποιώντας τις ακόλουθες γραμμές κώδικα. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου PS σε MHTML μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Πρόσωπο-Δωρομάνη Φόρματ (PDF) χρησιμοποιείται για το αποθήκισμα στατικά γραφικά πληροφορίες, καθ' όπω είναι ιδανικό για τη δημιουργία εφημερίδων και τεξτών. Ωστόσο, όταν εργάζονται με δυναμική δεδομένη πληροφορία, εφαρμογές ιστού like Internet Explorer γίνονται απαραίτητες για την βιζουαλιζατσιον και ανάλυση δεδομένων.

Η μετατροπή αρχιφάιλ PDF σε μορφή MHTML είναι απαραίτητη για να ενεργοποιήσετε τη πλήρη δυναμική σας στην βιζουαλιζατσιον και ανάλυση δεδομένων. Η αυτή μετατροπή σας επιτρέπει να:

**Πωλούνται Απlicaciones:**

*   **Ανάλυση ιστοσελίδων εμπορίου**: Μετατρέψτε αρχιφάιλ PDF για να αναλύσετε δεδομένα ιστοσελίδων εμπορίου, να παρακολουθήσετε πωλήσεις και να εντοπίσετε μοτίβους συμπεριφέρεσης πελατών.
*   **Διερεύνηση και σύγκριση εγγράφων**: Χρησιμοποιήστε MHTML για να αναλύσετε και συγκρινείτε εγγράφους, να παρακολουθήσετε αλλαγές και να μετρήσετε ακύβητα του εγγράφου.
*   **Βάση Γνώσεων Τεχνικής Υποστήριξης**: Μετατρέψτε αρχιφάιλ PDF για να δημιουργήσετε διαδραματικές βάσεις γνώσεων τεχνικής υποστήριξης, να προσομοιοποιήσετε εμπειρική εμπειρία χρηστών και να εγκυρότηνται ιδρύματα.
*   **Εκδόση Επιστημονικών Γραττών**: Χρησιμοποιήστε MHTML για να βιζουαλούντε σύνθετες επιστημονικές δεδομένα, όπως 3D μοντέλα, αποτελέσματα simulatio και πειραματικά δεδομένα, σε μορφή που可以 δημοσιευτεί.
*   **Δημοσίευση Υπολογιστών Συγκρούσεων και Dashboarding**: Μετατρέψτε αρχιφάιλ PDF για να δημιουργήσετε διαδραματικούς δελτίδες και βιζουαλιζατσιονα, τα οποία θα σας βοηθήσουν να συνετόνιζετε κανονισμούς, επιτρέχοντας καλύτερη λύση αποφασών.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}