---
title: Μετατροπή CGM σε WMF μέσω C# API
description: Εξάγετε το CGM σε WMF στις εφαρμογές σας .NET χωρίς να χρησιμοποιήσετε καμία εφαρμογή τρίτου μέρους
url_ignore: /el/net/conversion/cgm-to-wmf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: WMF
otherformats: EMZ SVGZ WMF TGA JPEG2000 DXF  PSD WMZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή αρχείου CGM σε WMF μέσω C#" h2="Εξαγωγή CGM σε WMF εντός εφαρμογών .NET χωρίς τη χρήση του Adobe<sup>&reg;</sup> Acrobat Reader ή άλλων εφαρμογών τρίτων" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να εξαγάγετε εικόνα CGM σε WMF σε οποιαδήποτε εφαρμογή .NET με δύο απλά βήματα. Πρώτα απ 'όλα, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το CGM σε JPEG. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, μπορείτε να μετατρέψετε το JPEG σε WMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή αρχείου CGM σε WMF μέσω .NET" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την τάξη [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Αρχικοποιήστε το αντικείμενο κλάσης [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) και αποδώστε το CGM σε JPEG χρησιμοποιώντας το [Process](https://apireference.aspose. μέθοδος com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1)
3. Φορτώστε το αρχείο JPEG χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Αποθηκεύστε το έγγραφο σε μορφή WMF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε WMF σε ένα μόνο αρχείο μέσω C#" %}}https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε το αρχείο CGM σε WMF σε ένα μόνο αρχείο εικόνας. Για να μετατρέψετε όλες τις σελίδες, μπορείτε πρώτα να αποδώσετε το έγγραφο CGM σε ένα αρχείο TIFF και μετά να εξάγετε το αρχείο TIFF σε WMF. Μπορείτε να ανοίξετε το αρχείο εισόδου χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) και να δημιουργήσετε αντικείμενα συσκευής Resolution, TiffSettings και TIFF. Μπορείτε να λάβετε μια μεμονωμένη εικόνα TIFF χρησιμοποιώντας τη μέθοδο [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) του [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) κλάση. Τέλος, μπορείτε να φορτώσετε το αρχείο TIFF χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
και αποθηκεύστε το σε μορφή WMF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή και περιστροφή αρχείου CGM σε WMF μέσω C#" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να περιστρέψετε την εικόνα εξόδου WMF σύμφωνα με τις ανάγκες σας. Η μέθοδος Image.RotateFlip μπορεί να χρησιμοποιηθεί για την περιστροφή της εικόνας κατά 90/180/270 μοίρες και την αναστροφή της εικόνας οριζόντια ή κάθετα. Μπορείτε να καθορίσετε τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. Για να περιστρέψετε και να αναστρέψετε την εικόνα, μπορείτε να φορτώσετε την εικόνα JPEG που έχει μετατραπεί χρησιμοποιώντας την εργοστασιακή μέθοδο που εκτίθεται από την κλάση [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) και να καλέσετε την εικόνα .RotateFlip μέθοδος καθορίζοντας το κατάλληλο [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου CGM σε WMF μέσω προγραμματισμού: Περιπτώσεις χρήσης" %}}
Η μετάφραση του κειμένου:

Η μετατροπή αρχιτεκτονικών γραφικών μηνυμάτων (CGM) σε μορφή Windows Metafile (WMF) είναι απαραίτηλη για να αποκαλυφθούν οι πλήρεις δυνατότητες των γράφων σας και των διαγραμμάτων σας.

Η μετατροπή αυτών των αρχιτεκτονικών γραφικών μηνυμάτων σε μορφή WMF επιτρέπει:

**Πωtiered Uses:**

* **Γραφική Σχεδίαση και Ιλισσασμά:** Μετατροπή CGM σε λεπτομερή γράφικά, εικόνες και λογότυπα, τα οποία είναι ιδανικά για χρήση σε πολλά μέσα.
* **Αρχιτεκτονική Βιζουαλizaton:** Χρήση της μορφής WMF για να vizualizeσετε 3D μοντέλα, σχεδιαγράμματα κτίσιν και αρχιτεκτονικές σχέσεις, επιτρέποντας καλύτερη συνεργασία και επικοινωνία με πελάτες και στόχους σας.
* **Τεχνική Σχέση και CAD:** Μετατροπή CGM σε τεχνικά γράφια, blueprints και σχεδιαγράμματα CAD, τα οποία είναι απαραίτητα για το ανάπτυξη προϊώντος, κατασκευές και μηχανικές εφαρμογές.
* **Σχεσιακές Εκδήλωση:** Χρήση της μορφής WMF για να δημιουργήσετε λεπτομερή και εικονιχέντα σχέδια, όπως γραφικά, ikons και λογότυπα, υπογραμμίζοντας τη δημιουργικότητά σας και τα χάρτια σας.
* **Δημοσίευση και Εκδηλώσεις:** Μετατροπή CGM σε δυναμικές και εικονιμένες εκδηλώσεις, παρουσίαγμένες σε οθόλοι ή ψηφιακή πλατφόρμα, με στόχο να συγκινήσουν το κοινό σας και να μεταδώσουν μηνύματα αποτεξικά.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}