---
title: Εξαγωγή CGM σε XAML μέσω C# API
description: .NET API για μετατροπή CGM σε XAML χωρίς χρήση του Microsoft Word
url_ignore: /el/net/conversion/cgm-to-xaml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XAML
otherformats: SWF POT PPTM OTP PPT XAML PPSX PPSM POTX POTM POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Απόδοση CGM σε XAML μέσω .NET" h2=".NET API για εξαγωγή CGM σε XAML σε Windows, macOS και Linux χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας ένα πακέτο ισχυρών API αυτοματισμού μορφής αρχείου [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να αποδώσετε το CGM σε XAML με δύο απλά βήματα. Χρησιμοποιώντας το API επεξεργασίας PDF [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να μετατρέψετε τη μορφή αρχείου CGM σε PPTX. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας παρουσίασης [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), μπορείτε να μετατρέψετε το PPTX σε XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API για Μετατροπή CGM σε XAML" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Μετατρέψτε το CGM σε PPTX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Φορτώστε το αρχείο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή XAML χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) και ορίστε το "Xaml" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Λάβετε μεταδεδομένα XMP από το αρχείο CGM μέσω .NET" %}}
Κατά τη μετατροπή του CGM σε XAML, ενδέχεται να χρειαστείτε επιπλέον πληροφορίες μεταδεδομένων XMP για να δώσετε προτεραιότητα στη διαδικασία ομαδικής μετατροπής. Για παράδειγμα, μπορείτε να λάβετε και να ταξινομήσετε τα έγγραφα μετατροπής με βάση την ημερομηνία δημιουργίας και να επεξεργαστείτε τα έγγραφα ανάλογα. Το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/) σάς επιτρέπει να έχετε πρόσβαση στα μεταδεδομένα XMP ενός αρχείου CGM. Για να λάβετε τα μεταδεδομένα ενός αρχείου CGM, μπορείτε να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να ανοίξετε το αρχείο εισόδου CGM. Μετά από αυτό, μπορείτε να λάβετε τα μεταδεδομένα του αρχείου χρησιμοποιώντας την ιδιότητα [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Δημιουργία αρχείου XAML μόνο για ανάγνωση μέσω .NET" %}}
Χρησιμοποιώντας το [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, μπορείτε να βελτιώσετε περαιτέρω τις δυνατότητες της εφαρμογής μετατροπής σας. Ένα από τα χαρακτηριστικά μπορεί να είναι να δημιουργήσετε το αρχείο εξόδου σας μόνο για ανάγνωση για να αυξήσετε την ασφάλεια. Το API σάς επιτρέπει να ορίσετε το αρχείο XAML σε Μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι χρήστες (αφού ανοίξουν την παρουσίαση) βλέπουν την πρόταση μόνο για ανάγνωση. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε XAML μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η μετάφραση του κειμένου:

Η μετατροπή αρχιτεκτονικών CGM σε μορφές XAML είναι απαραίτηλη για να αποκαλυφθεί η πλήρη δυναμική των δυνατостей σας στην σχεδίαση UI.

Η μετατροπή αυτών των αρχιτεκτονικών σε μορφές XAML σας επιτρέχει να:

**Πωtier Use Cases:**

*   **Δεvelopment της βιβλιοθήκης UI Component**: Μετατροπή αρχιτεκτονικών CGM για τη δημιουργία μιας βιβλιοθήκης UI components που μπορούν να χρησιμοποιηθούν εκπληξαμενώς, μειώνοντας το χρόνο ανάπτυξης και βελτιώνοντας την εσωτερική συνοχή των εφαρμοστικών προγραμμάτων.
*   **Εφαρμογή Συστήματος Design**: Χρήση του XAML για τη.visualizaton και την υλοποίηση συστημάτων design, διασφαλίζοντας μια συνοχή χρήσης用户 σε πολλά πλατφόρμες.
*   **Προσχεδίαση και Testing Usability**: Μετατροπή αρχιτεκτονικών CGM για τη δημιουργία αδραματικών πρωτυπών και testing usability, που βοηθούν στις αποφάσεις σχεδίας και στην βελτιωση της συνοχής χρήσης.
*   **Optimization of Accessibility**: Χρήση του XAML για την ανάλυση και την βελτιωση της προσβασιμότητας, διασφαλίζοντας ότι τα προγράμματα είναι可用的 από όποιοςδήποτε.

*   **Data-Driven Design**: Μετατροπή αρχιτεκτονικών CGM για τη δημιουργία σχεδίων που βασίζονται σε δεδομένα, χρησιμοποιώντας αναλυτικά και反馈用户 για να ενημερώσουν τις αποφάσεις σχεδίας και να βελτιώσουν τα αποτελέσματα επιχειρήσεων.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}