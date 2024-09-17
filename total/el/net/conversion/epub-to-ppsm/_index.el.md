---
title: Εξαγωγή EPUB σε PPSM μέσω C# API
description: .NET API για μετατροπή EPUB σε PPSM χωρίς χρήση του Microsoft Word
url_ignore: /el/net/conversion/epub-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSM
otherformats: PPSM POTX OTP PPTM SWF POWERPOINT XAML PPT POTM PPS PPSX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Απόδοση EPUB σε PPSM μέσω .NET" h2=".NET API για εξαγωγή EPUB σε PPSM σε Windows, macOS και Linux χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας ένα πακέτο ισχυρών API αυτοματισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να αποδώσετε το EPUB σε PPSM με δύο απλά βήματα. Χρησιμοποιώντας το API επεξεργασίας PDF [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου EPUB σε PPTX. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας παρουσίασης [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), μπορείτε να μετατρέψετε το PPTX σε PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή EPUB σε PPSM" %}}
1. Ανοίξτε το αρχείο EPUB χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το EPUB σε PPTX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το αρχείο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPSM χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) και ορίστε το "Ppsm" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λάβετε μεταδεδομένα XMP από το αρχείο EPUB μέσω .NET" %}}
Κατά τη μετατροπή του EPUB σε PPSM, ενδέχεται να χρειαστείτε επιπλέον πληροφορίες μεταδεδομένων XMP για να δώσετε προτεραιότητα στη διαδικασία ομαδικής μετατροπής. Για παράδειγμα, μπορείτε να λάβετε και να ταξινομήσετε τα έγγραφα μετατροπής με βάση την ημερομηνία δημιουργίας και να επεξεργαστείτε τα έγγραφα ανάλογα. Το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/) σάς επιτρέπει να έχετε πρόσβαση στα μεταδεδομένα XMP ενός αρχείου EPUB. Για να λάβετε τα μεταδεδομένα ενός αρχείου EPUB, μπορείτε να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να ανοίξετε το αρχείο εισόδου EPUB. Μετά από αυτό, μπορείτε να λάβετε τα μεταδεδομένα του αρχείου χρησιμοποιώντας την ιδιότητα [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργία αρχείου PPSM μόνο για ανάγνωση μέσω .NET" %}}
Χρησιμοποιώντας το [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, μπορείτε να βελτιώσετε περαιτέρω τις δυνατότητες της εφαρμογής μετατροπής σας. Ένα από τα χαρακτηριστικά μπορεί να είναι να δημιουργήσετε το αρχείο εξόδου σας μόνο για ανάγνωση για να αυξήσετε την ασφάλεια. Το API σάς επιτρέπει να ορίσετε το αρχείο PPSM σε Μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι χρήστες (αφού ανοίξουν την παρουσίαση) βλέπουν την πρόταση μόνο για ανάγνωση. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}