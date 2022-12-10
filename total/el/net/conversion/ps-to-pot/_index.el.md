---
title: Εξαγωγή PS σε POT μέσω C# API
description: .NET API για μετατροπή PS σε POT χωρίς χρήση του Microsoft Word
url_ignore: /el/net/conversion/ps-to-pot/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POT
otherformats: POT PPSM PPS SWF XAML POWERPOINT POTX POTM PPSX PPTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Απόδοση PS σε POT μέσω .NET" h2=".NET API για εξαγωγή PS σε POT σε Windows, macOS και Linux χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας ένα πακέτο ισχυρών API αυτοματισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να αποδώσετε το PS σε POT με δύο απλά βήματα. Χρησιμοποιώντας το API επεξεργασίας PDF [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου PS σε PPTX. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας παρουσίασης [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), μπορείτε να μετατρέψετε το PPTX σε POT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή PS σε POT" %}}
1. Ανοίξτε το αρχείο PS χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το PS σε PPTX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το αρχείο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή POT χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) και ορίστε το "Pot" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.ps");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λάβετε μεταδεδομένα XMP από το αρχείο PS μέσω .NET" %}}
Κατά τη μετατροπή του PS σε POT, ενδέχεται να χρειαστείτε επιπλέον πληροφορίες μεταδεδομένων XMP για να δώσετε προτεραιότητα στη διαδικασία ομαδικής μετατροπής. Για παράδειγμα, μπορείτε να λάβετε και να ταξινομήσετε τα έγγραφα μετατροπής με βάση την ημερομηνία δημιουργίας και να επεξεργαστείτε τα έγγραφα ανάλογα. Το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/) σάς επιτρέπει να έχετε πρόσβαση στα μεταδεδομένα XMP ενός αρχείου PS. Για να λάβετε τα μεταδεδομένα ενός αρχείου PS, μπορείτε να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να ανοίξετε το αρχείο εισόδου PS. Μετά από αυτό, μπορείτε να λάβετε τα μεταδεδομένα του αρχείου χρησιμοποιώντας την ιδιότητα [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.ps");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργία αρχείου POT μόνο για ανάγνωση μέσω .NET" %}}
Χρησιμοποιώντας το [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, μπορείτε να βελτιώσετε περαιτέρω τις δυνατότητες της εφαρμογής μετατροπής σας. Ένα από τα χαρακτηριστικά μπορεί να είναι να δημιουργήσετε το αρχείο εξόδου σας μόνο για ανάγνωση για να αυξήσετε την ασφάλεια. Το API σάς επιτρέπει να ορίσετε το αρχείο POT σε Μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι χρήστες (αφού ανοίξουν την παρουσίαση) βλέπουν την πρόταση μόνο για ανάγνωση. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-pot/" name="PS Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-ppsx/" name="PS Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-swf/" name="PS Προς την SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-powerpoint/" name="PS Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-otp/" name="PS Προς την OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-potm/" name="PS Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-ppt/" name="PS Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-pps/" name="PS Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-potx/" name="PS Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-xaml/" name="PS Προς την XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-ppsm/" name="PS Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/ps-to-pptm/" name="PS Προς την PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}