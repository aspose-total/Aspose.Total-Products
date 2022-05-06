---
title: Μετατροπή μορφής JSON σε EMZ μέσω .NET
description: Αναλύστε το JSON σε EMZ σε C# χωρίς να χρησιμοποιήσετε εξαρτήσεις τρίτων
url_ignore: /el/net/conversion/json-to-emz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EMZ
otherformats: IMAGE TGA SVGZ JPEG2000 EMZ DXF WMZ WMF DICOM PSD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή μορφής JSON σε EMZ μέσω C#" h2="C# API για ανάλυση JSON σε EMZ χωρίς χρήση εξαρτήσεων τρίτων" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να αναλύσετε το JSON σε EMZ σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/), μπορείτε να εξαγάγετε το JSON σε JPEG. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), μπορείτε να μετατρέψετε το JPEG σε EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή μορφής JSON σε EMZ μέσω C#" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) και διαβάστε τα δεδομένα JSON από το αρχείο
2. Μετατρέψτε το JSON σε JPEG χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Φορτώστε το έγγραφο JPEG χρησιμοποιώντας την κλάση [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Αποθηκεύστε το έγγραφο σε μορφή EMZ χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ορισμός διάταξης και μετατροπή μορφής JSON σε EMZ μέσω C#" %}}
Κατά την ανάλυση του JSON σε EMZ, μπορείτε επίσης να ορίσετε επιλογές διάταξης για το JSON χρησιμοποιώντας το [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Σας επιτρέπει να επεξεργαστείτε τον πίνακα ως πίνακα, να αγνοήσετε τα μηδενικά, να αγνοήσετε τον τίτλο του πίνακα, να αγνοήσετε τον τίτλο του αντικειμένου, να μετατρέψετε τη συμβολοσειρά σε αριθμό ή ημερομηνία, να ορίσετε την ημερομηνία και τη μορφή αριθμού και να ορίσετε στυλ τίτλου. Όλες αυτές οι επιλογές σάς επιτρέπουν να παρουσιάζετε τα δεδομένα σας σύμφωνα με τις ανάγκες σας. Το παρακάτω απόσπασμα κώδικα σάς δείχνει πώς να ορίσετε τις επιλογές διάταξης.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αναλύστε τη μορφή JSON σε EMZ με υδατογράφημα" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε το JSON σε EMZ με υδατογράφημα στο έγγραφό σας EMZ. Για να προσθέσετε ένα υδατογράφημα, μπορείτε πρώτα να αποδώσετε το έγγραφό σας JSON σε JPEG και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να επιδείξετε τη λειτουργία, μπορείτε να φορτώσετε την εικόνα JPEG που έχετε μετατρέψει, να προσθέσετε μετασχηματισμούς χρησιμοποιώντας ένα αντικείμενο της κλάσης Matrix και να σχεδιάσετε μια συμβολοσειρά ως υδατογράφημα στην επιφάνεια της εικόνας χρησιμοποιώντας το [Graphics](https://apireference.aspose.com/imaging/ net/aspose.imaging/graphics) class' [DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) μέθοδος. Αφού προσθέσετε το υδατογράφημα σε αυτό, μπορείτε να αποθηκεύσετε το JPEG ως μορφή EMZ. Ακολουθεί ένα παράδειγμα κώδικα που δείχνει πώς να προσθέσετε ένα διαγώνιο υδατογράφημα στο έγγραφό σας. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-wmz/" name="JSON Προς την WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-dicom/" name="JSON Προς την DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-psd/" name="JSON Προς την PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-jpeg2000/" name="JSON Προς την JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-tga/" name="JSON Προς την TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-emz/" name="JSON Προς την EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-svgz/" name="JSON Προς την SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-wmf/" name="JSON Προς την WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-image/" name="JSON Προς την IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-dxf/" name="JSON Προς την DXF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}