---
title: Μετατροπή PDF σε IMAGE μέσω Java
description: Εξαγωγή αρχείου PDF σε IMAGE στις εφαρμογές σας Java χωρίς να χρησιμοποιήσετε καμία εφαρμογή τρίτου μέρους
url_ignore: /el/java/conversion/pdf-to-image/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: IMAGE
otherformats: JPEG2000 EMZ  WMZ TGA PSD DXF WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PDF σε IMAGE μέσω Java" h2="Εξαγωγή αρχείου PDF σε IMAGE εντός οποιασδήποτε εφαρμογής Java J2SE, J2EE, J2ME χωρίς τη χρήση του Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το αρχείο pdf σε εικόνα IMAGE σε Java με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/), μπορείτε να εξαγάγετε το PDF σε JPEG. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, μπορείτε να αποδώσετε το JPEG σε IMAGE. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή PDF σε IMAGE μέσω Java" %}}
1. Ανοίξτε το αρχείο PDF χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Αρχικοποιήστε το αντικείμενο κλάσης και αποδώστε το PDF σε JPEG χρησιμοποιώντας το [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. μέθοδος aspose.pdf.Page-java.io.OutputStream-).
3. Φορτώστε το αρχείο JPEG χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Αποθηκεύστε το έγγραφο σε μορφή IMAGE χρησιμοποιώντας [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PDF σε IMAGE σε ένα μόνο αρχείο μέσω Java" %}}
Το API σάς επιτρέπει επίσης να εξάγετε αρχείο PDF σε IMAGE σε ένα μόνο αρχείο. Για να μετατρέψετε όλες τις σελίδες, μπορείτε πρώτα να αποδώσετε το έγγραφο PDF σε ένα αρχείο TIFF και μετά να εξαγάγετε το αρχείο TIFF σε IMAGE. Μπορείτε να ανοίξετε το αρχείο εισόδου χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) και να δημιουργήσετε αντικείμενα συσκευής Resolution, TiffSettings και TIFF. Μπορείτε να λάβετε μία εικόνα TIFF χρησιμοποιώντας το [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) μέθοδος της κλάσης [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Τέλος, μπορείτε να φορτώσετε το αρχείο TIFF χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) και να το αποθηκεύσετε σε μορφή IMAGE χρησιμοποιώντας [save](https:// μέθοδο apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PDF σε IMAGE με υδατογράφημα μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να εξάγετε το αρχείο PDF σε IMAGE με υδατογράφημα στο έγγραφό σας IMAGE. Για να προσθέσετε ένα υδατογράφημα, μπορείτε πρώτα να μετατρέψετε το PDF σε JPEG και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε υδατογράφημα, φορτώστε ένα αρχείο εικόνας χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), δημιουργήστε ένα αντικείμενο του [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) κλάση και αρχικοποιήστε την με αντικείμενο Image, δημιουργήστε ένα νέο [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) αντικειμένου και ορίστε τη μετάφραση και τον μετασχηματισμό στην επιθυμητή γωνία και προσθέστε υδατογράφημα χρησιμοποιώντας το [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Μέθοδος drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Αφού προσθέσετε το υδατογράφημα στην εικόνα σας, μπορείτε να αποθηκεύσετε το JPEG σε μορφή IMAGE. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή & περιστροφή αρχείου PDF σε IMAGE μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να περιστρέψετε την εικόνα εξόδου IMAGE σύμφωνα με τις ανάγκες σας. Η μέθοδος Image.rotateFlip μπορεί να χρησιμοποιηθεί για την περιστροφή της εικόνας κατά 90/180/270 μοίρες και την αναστροφή της εικόνας οριζόντια ή κάθετα. Η βιβλιοθήκη παρέχει απλές μεθόδους για την εκτέλεση σύνθετων λειτουργιών, ενώ συγκεντρώνει όλες τις άσχημες λεπτομέρειες. Μπορείτε να καθορίσετε τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. Για να περιστρέψετε και να αναστρέψετε την εικόνα, μπορείτε να φορτώσετε την εικόνα JPEG που έχει μετατραπεί χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) και να καλέσετε την εικόνα. μέθοδο rotateFlip ενώ καθορίζετε το κατάλληλο [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
## Μετατροπή **PDF σε ΕΙΚΟΝΑ**
Η μετατροπή **PDF σε ΕΙΚΟΝΑ** είναι ένα από τα πιο συνηθισμένα ροές εργασίας, επιτρέποντας στα έγγραφα να μετατραπούν σε διάφορες μορφές εικόνας όπως PNG, JPG ή TIFF. Αυτό καθιστά τα PDF ευκολότερα στη χρήση σε περιβάλλοντα **δημοσίευσης στον ιστό, αρχειοθέτησης και ψηφιακής παρουσίασης**.
{{% blocks/products/pf/agp/feature-section-col title="Κύριες Περιπτώσεις Χρήσης" %}}
- Αρχειοθέτηση εγγράφων PDF ως αρχεία εικόνας
- Ενσωμάτωση σελίδων PDF σε ιστότοπους ως PNG ή JPG
- Δημιουργία μικρογραφιών και προεπισκοπήσεων από PDF
- Ενσωμάτωση PDF σε Ϩψηφιακές διαφάνειες και παρουσιάσεις
- Αποθήκευση βασισμένη σε εικόνες για συμμόρφωση και ελέγχους
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Σενάρια Αυτοματοποίησης" %}}
- Αυτοματοποιημένες **διαδικασίες μαζικής μετατροπής PDF σε ΕΙΚΟΝΑ**
- Ροές εργασίας PDF σε PNG ή JPG για ιστοπλατφόρμες
- Δημιουργία προεπισκόπησης εικόνας για συστήματα διαχείρισης εγγράφων
- PDF σε πολλαπλές σελίδες TIFF για επιχειρησιακή αρχειοθέτηση
- Αυτοματοποιημένη μετατροπή PDF σε ΕΙΚΟΝΑ βασισμένη σε API
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}