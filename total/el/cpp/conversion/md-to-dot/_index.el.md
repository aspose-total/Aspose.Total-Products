---
title: C++ API για εξαγωγή MD σε DOT
description: Μετατροπή MD σε DOT εντός εφαρμογών C++.

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DOT
otherformats: PCL MARKDOWN XAMLFLOW MHTML OTT ODT WORDML PS DOTX DOTM DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή MD σε DOT" h2="Αποδώστε το MD σε DOT εντός εφαρμογών C++ χωρίς να απαιτείται εφαρμογή τρίτων" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) Οι βιβλιοθήκες αυτοματοποίησης μορφών αρχείου επιτρέπουν στον προγραμματιστή της C++ να μετατρέψει το MD σε DOT με δύο απλά βήματα. Πρώτον, μπορείτε να χρησιμοποιήσετε το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API για να μετατρέψετε τη μορφή αρχείου MD σε DOC. Δεύτερον, χρησιμοποιώντας προηγμένο API επεξεργασίας εγγράφων Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), μπορείτε να εξαγάγετε το DOC στο DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για απόδοση MD σε DOT" %}}
1. Ανοίξτε το αρχείο MD χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Μετατρέψτε το MD σε DOC χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) του Aspose.Words API
4. Αποθηκεύστε το έγγραφο σε μορφή DOT χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MD file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.md");
// save MD as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dot
wordDoc->Save(u"output.Dot");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Αλλάξτε τον κωδικό πρόσβασης του εγγράφου MD μέσω C++" %}}
Κατά τη διαδικασία απόδοσης του MD σε DOT, μπορείτε να ανοίξετε ένα MD που προστατεύεται με κωδικό πρόσβασης και επίσης να αλλάξετε τον κωδικό πρόσβασής του. Για να αλλάξετε τον κωδικό πρόσβασης ενός αρχείου MD, πρέπει να γνωρίζετε τον κωδικό πρόσβασης κατόχου αυτού του εγγράφου. Μπορείτε να φορτώσετε ένα έγγραφο PDF που προστατεύεται με κωδικό πρόσβασης με το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) καθορίζοντας τον κωδικό πρόσβασης κατόχου του και να χρησιμοποιήσετε τη μέθοδο ChangePasswords για να αλλάξετε τον κωδικό πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία αρχείων DOT μέσω C++" %}}
Μπορείτε επίσης να περιορίσετε την επεξεργασία αρχείων DOT χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Το API σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας την παράμετρο απαρίθμησης [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να περιορίσετε την επεξεργασία σε ένα έγγραφο, ώστε να είναι δυνατή μόνο η επεξεργασία σε πεδία φόρμας.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dot");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-pcl/" name="MD Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-markdown/" name="MD Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-xamlflow/" name="MD Προς την XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-mhtml/" name="MD Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-ott/" name="MD Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-odt/" name="MD Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-wordml/" name="MD Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-ps/" name="MD Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-dotx/" name="MD Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-dotm/" name="MD Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-dot/" name="MD Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/md-to-flatopc/" name="MD Προς την FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}