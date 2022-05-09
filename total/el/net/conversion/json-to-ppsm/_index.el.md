---
title: Μετατροπή μορφής JSON σε PPSM μέσω .NET
description: Ανάλυση JSON σε PPSM σε C# χωρίς χρήση του Microsoft PowerPoint
url_ignore: /el/net/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POTM PPS PPSM POWERPOINT POT OTP PPT POTX PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή μορφής JSON σε PPSM μέσω C#" h2="C# API για ανάλυση JSON σε PPSM χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε JSON σε PPSM σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/), μπορείτε να αναλύσετε το JSON σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), μπορείτε να μετατρέψετε το PPTX σε PPSM. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή μορφής JSON σε PPSM μέσω C#" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/bookbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Εισαγάγετε αρχείο JSON στο φύλλο εργασίας χρησιμοποιώντας την κλάση [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) και το [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) το ως PPTX
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPSM χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ορισμός διάταξης και μετατροπή μορφής JSON σε PPSM μέσω C#" %}}
Κατά την ανάλυση του JSON σε PPSM, μπορείτε επίσης να ορίσετε επιλογές διάταξης για τη μορφή JSON χρησιμοποιώντας το [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Σας επιτρέπει να επεξεργαστείτε τον πίνακα ως πίνακα, να αγνοήσετε τα μηδενικά, να αγνοήσετε τον τίτλο του πίνακα, να αγνοήσετε τον τίτλο του αντικειμένου, να μετατρέψετε τη συμβολοσειρά σε αριθμό ή ημερομηνία, να ορίσετε μορφή ημερομηνίας και αριθμού και να ορίσετε στυλ τίτλου. Όλες αυτές οι επιλογές σάς επιτρέπουν να παρουσιάζετε τα δεδομένα σας σύμφωνα με τις ανάγκες σας. Το παρακάτω απόσπασμα κώδικα σάς δείχνει πώς να ορίσετε τις επιλογές διάταξης.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε τη μορφή JSON σε PPSM με υδατογράφημα" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε JSON σε PPSM με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφο PPSM, μπορείτε πρώτα να αναλύσετε το JSON σε PPTX και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το νέο αρχείο PPTX χρησιμοποιώντας την κλάση [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation), επιλέξτε την κύρια παρουσίαση, προσθέστε τύπο σχήματος χρησιμοποιώντας AddAutoShape και προσθέστε κείμενο υδατογραφήματος χρησιμοποιώντας το AddTextFrame. Αφού προσθέσετε το υδατογράφημα, μπορείτε να αποθηκεύσετε το έγγραφο στο PPSM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ppt/" name="JSON Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-otp/" name="JSON Προς την OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ppsx/" name="JSON Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-powerpoint/" name="JSON Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-potm/" name="JSON Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pot/" name="JSON Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ppsm/" name="JSON Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-potx/" name="JSON Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pptm/" name="JSON Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pps/" name="JSON Προς την PPS" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}