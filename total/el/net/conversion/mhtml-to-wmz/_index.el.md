---
title: Μετατροπή MHTML σε WMZ μέσω C# API
description: Εξάγετε το MHTML σε WMZ στις εφαρμογές σας .NET χωρίς να χρησιμοποιήσετε καμία εφαρμογή τρίτου μέρους
url: /el/net/conversion/mhtml-to-wmz/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: WMZ
otherformats: JPEG2000 WMZ PSD WMF EMZ TGA DXF  SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή αρχείου MHTML σε WMZ μέσω C#" h2="Εξαγωγή MHTML σε WMZ εντός εφαρμογών .NET χωρίς τη χρήση του Adobe<sup>&reg;</sup> Acrobat Reader ή άλλων εφαρμογών τρίτων" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε εύκολα να εξαγάγετε εικόνα MHTML σε WMZ σε οποιαδήποτε εφαρμογή .NET με δύο απλά βήματα. Πρώτα απ 'όλα, χρησιμοποιώντας το [Aspose.PDF για .NET](https://products.aspose.com/pdf/net/), μπορείτε να εξαγάγετε το MHTML σε JPEG. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, μπορείτε να μετατρέψετε το JPEG σε WMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή αρχείου MHTML σε WMZ μέσω .NET" %}}
1. Ανοίξτε το αρχείο MHTML χρησιμοποιώντας την τάξη [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Αρχικοποιήστε το αντικείμενο κλάσης [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) και αποδώστε το MHTML σε JPEG χρησιμοποιώντας το [Process](https://apireference.aspose. μέθοδος com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1)
3. Φορτώστε το αρχείο JPEG χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Αποθηκεύστε το έγγραφο σε μορφή WMZ χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή αρχείου MHTML σε WMZ σε ένα μόνο αρχείο μέσω C#" %}}https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε το αρχείο MHTML σε WMZ σε ένα μόνο αρχείο εικόνας. Για να μετατρέψετε όλες τις σελίδες, μπορείτε πρώτα να αποδώσετε το έγγραφο MHTML σε ένα αρχείο TIFF και μετά να εξάγετε το αρχείο TIFF σε WMZ. Μπορείτε να ανοίξετε το αρχείο εισόδου χρησιμοποιώντας την κλάση [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) και να δημιουργήσετε αντικείμενα συσκευής Resolution, TiffSettings και TIFF. Μπορείτε να λάβετε μια μεμονωμένη εικόνα TIFF χρησιμοποιώντας τη μέθοδο [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) του [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) κλάση. Τέλος, μπορείτε να φορτώσετε το αρχείο TIFF χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
και αποθηκεύστε το σε μορφή WMZ χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή και περιστροφή αρχείου MHTML σε WMZ μέσω C#" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να περιστρέψετε την εικόνα εξόδου WMZ σύμφωνα με τις ανάγκες σας. Η μέθοδος Image.RotateFlip μπορεί να χρησιμοποιηθεί για την περιστροφή της εικόνας κατά 90/180/270 μοίρες και την αναστροφή της εικόνας οριζόντια ή κάθετα. Μπορείτε να καθορίσετε τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. Για να περιστρέψετε και να αναστρέψετε την εικόνα, μπορείτε να φορτώσετε την εικόνα JPEG που έχει μετατραπεί χρησιμοποιώντας την εργοστασιακή μέθοδο που εκτίθεται από την κλάση [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) και να καλέσετε την εικόνα .RotateFlip μέθοδος καθορίζοντας το κατάλληλο [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-emz/" name="MHTML Προς την EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-tga/" name="MHTML Προς την TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-jpeg2000/" name="MHTML Προς την JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-image/" name="MHTML Προς την IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-psd/" name="MHTML Προς την PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-wmz/" name="MHTML Προς την WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-svgz/" name="MHTML Προς την SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to/" name="MHTML Προς την" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-wmf/" name="MHTML Προς την WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-dxf/" name="MHTML Προς την DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/mhtml-to-dicom/" name="MHTML Προς την DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}