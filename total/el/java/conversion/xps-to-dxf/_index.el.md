---
title: Μετατροπή XPS σε DXF μέσω Java
description: Εξαγωγή αρχείου XPS σε DXF στις εφαρμογές σας Java χωρίς να χρησιμοποιήσετε καμία εφαρμογή τρίτου μέρους
url_ignore: /el/java/conversion/xps-to-dxf/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: DXF
otherformats: WMZ IMAGE DXF EMZ WMF SVGZ TGA JPEG2000  PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή XPS σε DXF μέσω Java" h2="Εξαγωγή αρχείου XPS σε DXF εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς τη χρήση του Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το αρχείο xps σε εικόνα DXF σε Java με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το XPS σε JPEG. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, μπορείτε να αποδώσετε το JPEG σε DXF. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή XPS σε DXF μέσω Java" %}}
1. Ανοίξτε το αρχείο XPS χρησιμοποιώντας την κλάση [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Αρχικοποιήστε το αντικείμενο κλάσης και αποδώστε το XPS σε JPEG χρησιμοποιώντας το [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. μέθοδος aspose.pdf.Page-java.io.OutputStream-).
3. Φορτώστε το αρχείο JPEG χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Αποθηκεύστε το έγγραφο σε μορφή DXF χρησιμοποιώντας [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή XPS σε DXF σε ένα μόνο αρχείο μέσω Java" %}}
Το API σάς επιτρέπει επίσης να εξάγετε αρχείο XPS σε DXF σε ένα μόνο αρχείο. Για να μετατρέψετε όλες τις σελίδες, μπορείτε πρώτα να αποδώσετε το έγγραφο XPS σε ένα αρχείο TIFF και μετά να εξαγάγετε το αρχείο TIFF σε DXF. Μπορείτε να ανοίξετε το αρχείο εισόδου χρησιμοποιώντας την κλάση [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) και να δημιουργήσετε αντικείμενα συσκευής Resolution, TiffSettings και TIFF. Μπορείτε να λάβετε μία εικόνα TIFF χρησιμοποιώντας το [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- java.io.OutputStream-) μέθοδος της κλάσης [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Τέλος, μπορείτε να φορτώσετε το αρχείο TIFF χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) και να το αποθηκεύσετε σε μορφή DXF χρησιμοποιώντας [save](https:// μέθοδο apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή XPS σε DXF με υδατογράφημα μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να εξάγετε το αρχείο XPS σε DXF με υδατογράφημα στο έγγραφό σας DXF. Για να προσθέσετε ένα υδατογράφημα, μπορείτε πρώτα να μετατρέψετε το XPS σε JPEG και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε υδατογράφημα, φορτώστε ένα αρχείο εικόνας χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), δημιουργήστε ένα αντικείμενο του [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) κλάση και αρχικοποιήστε την με αντικείμενο Image, δημιουργήστε ένα νέο [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) αντικειμένου και ορίστε τη μετάφραση και τον μετασχηματισμό στην επιθυμητή γωνία και προσθέστε υδατογράφημα χρησιμοποιώντας το [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Μέθοδος drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Αφού προσθέσετε το υδατογράφημα στην εικόνα σας, μπορείτε να αποθηκεύσετε το JPEG σε μορφή DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή & περιστροφή αρχείου XPS σε DXF μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να περιστρέψετε την εικόνα εξόδου DXF σύμφωνα με τις ανάγκες σας. Η μέθοδος Image.rotateFlip μπορεί να χρησιμοποιηθεί για την περιστροφή της εικόνας κατά 90/180/270 μοίρες και την αναστροφή της εικόνας οριζόντια ή κάθετα. Η βιβλιοθήκη παρέχει απλές μεθόδους για την εκτέλεση σύνθετων λειτουργιών, ενώ συγκεντρώνει όλες τις άσχημες λεπτομέρειες. Μπορείτε να καθορίσετε τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. Για να περιστρέψετε και να αναστρέψετε την εικόνα, μπορείτε να φορτώσετε την εικόνα JPEG που έχει μετατραπεί χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) και να καλέσετε την εικόνα. μέθοδο rotateFlip ενώ καθορίζετε το κατάλληλο [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-emz/" name="XPS Προς την EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-tga/" name="XPS Προς την TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-jpeg2000/" name="XPS Προς την JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-image/" name="XPS Προς την IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-psd/" name="XPS Προς την PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-wmz/" name="XPS Προς την WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-svgz/" name="XPS Προς την SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to/" name="XPS Προς την" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-wmf/" name="XPS Προς την WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-dxf/" name="XPS Προς την DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xps-to-dicom/" name="XPS Προς την DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}