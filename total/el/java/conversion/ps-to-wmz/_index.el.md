---
title: Μετατροπή PS σε WMZ μέσω Java
description: Εξαγωγή αρχείου PS σε WMZ στις εφαρμογές σας Java χωρίς να χρησιμοποιήσετε καμία εφαρμογή τρίτου μέρους
url_ignore: /el/java/conversion/ps-to-wmz/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: WMZ
otherformats: TGA  DXF EMZ WMF PSD WMZ JPEG2000 IMAGE SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PS σε WMZ μέσω Java" h2="Εξαγωγή αρχείου PS σε WMZ εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς τη χρήση του Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το αρχείο ps σε εικόνα WMZ σε Java με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το PS σε JPEG. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, μπορείτε να αποδώσετε το JPEG σε WMZ. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή PS σε WMZ μέσω Java" %}}
1. Ανοίξτε το αρχείο PS χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Αρχικοποιήστε το αντικείμενο κλάσης και αποδώστε το PS σε JPEG χρησιμοποιώντας το [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. μέθοδος aspose.pdf.Page-java.io.OutputStream-).
3. Φορτώστε το αρχείο JPEG χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Αποθηκεύστε το έγγραφο σε μορφή WMZ χρησιμοποιώντας [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PS σε WMZ σε ένα μόνο αρχείο μέσω Java" %}}
Το API σάς επιτρέπει επίσης να εξάγετε αρχείο PS σε WMZ σε ένα μόνο αρχείο. Για να μετατρέψετε όλες τις σελίδες, μπορείτε πρώτα να αποδώσετε το έγγραφο PS σε ένα αρχείο TIFF και μετά να εξαγάγετε το αρχείο TIFF σε WMZ. Μπορείτε να ανοίξετε το αρχείο εισόδου χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) και να δημιουργήσετε αντικείμενα συσκευής Resolution, TiffSettings και TIFF. Μπορείτε να λάβετε μία εικόνα TIFF χρησιμοποιώντας το [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) μέθοδος της κλάσης [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Τέλος, μπορείτε να φορτώσετε το αρχείο TIFF χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) και να το αποθηκεύσετε σε μορφή WMZ χρησιμοποιώντας [save](https:// μέθοδο apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PS σε WMZ με υδατογράφημα μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να εξάγετε το αρχείο PS σε WMZ με υδατογράφημα στο έγγραφό σας WMZ. Για να προσθέσετε ένα υδατογράφημα, μπορείτε πρώτα να μετατρέψετε το PS σε JPEG και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε υδατογράφημα, φορτώστε ένα αρχείο εικόνας χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), δημιουργήστε ένα αντικείμενο του [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) κλάση και αρχικοποιήστε την με αντικείμενο Image, δημιουργήστε ένα νέο [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) αντικειμένου και ορίστε τη μετάφραση και τον μετασχηματισμό στην επιθυμητή γωνία και προσθέστε υδατογράφημα χρησιμοποιώντας το [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Μέθοδος drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Αφού προσθέσετε το υδατογράφημα στην εικόνα σας, μπορείτε να αποθηκεύσετε το JPEG σε μορφή WMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή & περιστροφή αρχείου PS σε WMZ μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να περιστρέψετε την εικόνα εξόδου WMZ σύμφωνα με τις ανάγκες σας. Η μέθοδος Image.rotateFlip μπορεί να χρησιμοποιηθεί για την περιστροφή της εικόνας κατά 90/180/270 μοίρες και την αναστροφή της εικόνας οριζόντια ή κάθετα. Η βιβλιοθήκη παρέχει απλές μεθόδους για την εκτέλεση σύνθετων λειτουργιών, ενώ συγκεντρώνει όλες τις άσχημες λεπτομέρειες. Μπορείτε να καθορίσετε τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. Για να περιστρέψετε και να αναστρέψετε την εικόνα, μπορείτε να φορτώσετε την εικόνα JPEG που έχει μετατραπεί χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) και να καλέσετε την εικόνα. μέθοδο rotateFlip ενώ καθορίζετε το κατάλληλο [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}