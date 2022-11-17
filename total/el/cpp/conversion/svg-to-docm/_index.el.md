---
title: C++ API για εξαγωγή SVG σε DOCM
description: Μετατροπή SVG σε DOCM εντός εφαρμογών C++.

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOCM
otherformats: DOTX MARKDOWN FLATOPC WORDML OTT DOTM XAMLFLOW MHTML PS DOT PCL ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή SVG σε DOCM" h2="Αποδώστε το SVG σε DOCM εντός εφαρμογών C++ χωρίς να απαιτείται εφαρμογή τρίτων" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) Οι βιβλιοθήκες αυτοματοποίησης μορφών αρχείου επιτρέπουν στον προγραμματιστή της C++ να μετατρέψει το SVG σε DOCM με δύο απλά βήματα. Πρώτον, μπορείτε να χρησιμοποιήσετε το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API για να μετατρέψετε τη μορφή αρχείου SVG σε DOC. Δεύτερον, χρησιμοποιώντας προηγμένο API επεξεργασίας εγγράφων Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), μπορείτε να εξαγάγετε το DOC στο DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για απόδοση SVG σε DOCM" %}}
1. Ανοίξτε το αρχείο SVG χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Μετατρέψτε το SVG σε DOC χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) του Aspose.Words API
4. Αποθηκεύστε το έγγραφο σε μορφή DOCM χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.svg");
// save SVG as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Docm
wordDoc->Save(u"output.Docm");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Αλλάξτε τον κωδικό πρόσβασης του εγγράφου SVG μέσω C++" %}}
Κατά τη διαδικασία απόδοσης του SVG σε DOCM, μπορείτε να ανοίξετε ένα SVG που προστατεύεται με κωδικό πρόσβασης και επίσης να αλλάξετε τον κωδικό πρόσβασής του. Για να αλλάξετε τον κωδικό πρόσβασης ενός αρχείου SVG, πρέπει να γνωρίζετε τον κωδικό πρόσβασης κατόχου αυτού του εγγράφου. Μπορείτε να φορτώσετε ένα έγγραφο PDF που προστατεύεται με κωδικό πρόσβασης με το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) καθορίζοντας τον κωδικό πρόσβασης κατόχου του και να χρησιμοποιήσετε τη μέθοδο ChangePasswords για να αλλάξετε τον κωδικό πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Περιορίστε την επεξεργασία αρχείων DOCM μέσω C++" %}}
Μπορείτε επίσης να περιορίσετε την επεξεργασία αρχείων DOCM χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Μερικές φορές μπορεί να χρειαστεί να περιορίσετε τη δυνατότητα επεξεργασίας ενός εγγράφου και να επιτρέψετε μόνο ορισμένες ενέργειες με αυτό. Το API σάς δίνει τη δυνατότητα να ελέγχετε τον τρόπο με τον οποίο περιορίζετε το περιεχόμενο χρησιμοποιώντας την παράμετρο απαρίθμησης [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να περιορίσετε την επεξεργασία σε ένα έγγραφο, ώστε να είναι δυνατή μόνο η επεξεργασία σε πεδία φόρμας.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Docm");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-dotx/" name="SVG Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-markdown/" name="SVG Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-flatopc/" name="SVG Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-wordml/" name="SVG Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-ott/" name="SVG Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-dotm/" name="SVG Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-xamlflow/" name="SVG Προς την XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-mhtml/" name="SVG Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-ps/" name="SVG Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-dot/" name="SVG Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-pcl/" name="SVG Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/svg-to-odt/" name="SVG Προς την ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}