---
title: C# API για εξαγωγή CGM σε MHTML
description: Μετατροπή CGM σε MHTML χωρίς χρήση του Microsoft Word
url_ignore: /el/net/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: WORDML MHTML DOTX MARKDOWN DOT FLATOPC XAMLFLOW RTF PCL ODT PS DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Απόδοση CGM σε MHTML μέσω .NET" h2=".NET API για εξαγωγή CGM σε MHTML σε Windows, macOS και Linux χωρίς χρήση του Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for .NET](https://products.aspose.com/total/net/) είναι ένα ισχυρό API για την προσθήκη λειτουργιών χειρισμού εγγράφων και μετατροπής στην εφαρμογή σας .NET. Χρησιμοποιώντας προηγμένο API επεξεργασίας PDF [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου CGM σε DOC. Μετά από αυτό, χρησιμοποιώντας το ισχυρό API Επεξεργασίας Εγγράφων [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να αποδώσετε το DOC σε MHTML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API για μετατροπή CGM σε MHTML" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το CGM σε Έγγραφο χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το αρχείο Doc χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή MHTML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) και ορίστε το Mhtml ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.mhtml", SaveFormat.Mhtml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Αποκρυπτογραφήστε το αρχείο CGM χρησιμοποιώντας τον κωδικό πρόσβασης κατόχου μέσω .NET" %}}
Πριν μετατρέψετε το CGM σε MHTML, εάν θέλετε να αποκρυπτογραφήσετε το έγγραφό σας, μπορείτε να το κάνετε χρησιμοποιώντας το API. Για να αποκρυπτογραφήσετε το αρχείο PDF, πρέπει πρώτα να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να ανοίξετε το CGM χρησιμοποιώντας τον κωδικό πρόσβασης του κατόχου. Μετά από αυτό, πρέπει να καλέσετε τη μέθοδο [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) του αντικειμένου Document. Τέλος, αποθηκεύστε το ενημερωμένο αρχείο χρησιμοποιώντας τη μέθοδο Save του αντικειμένου Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

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

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-ott/" name="CGM Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-mhtml/" name="CGM Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-wordml/" name="CGM Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-dot/" name="CGM Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-odt/" name="CGM Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-rtf/" name="CGM Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-ps/" name="CGM Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-flatopc/" name="CGM Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-pcl/" name="CGM Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-markdown/" name="CGM Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-xamlflow/" name="CGM Προς την XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/cgm-to-dotx/" name="CGM Προς την DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}