---
title: Μετατροπή μορφής JSON σε ODT μέσω .NET
description: Αναλύστε το JSON σε ODT σε C# χωρίς να χρησιμοποιήσετε το Microsoft Word
url_ignore: /el/net/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: DOTX WORD DOT RTF DOC DOCM MOBI OTT WORDML PCL ODT PS FLATOPC EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή μορφής JSON σε ODT μέσω C#" h2="C# API για ανάλυση JSON σε ODT χωρίς χρήση Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for .NET](https://products.aspose.com/total/net/) μπορείτε να αναλύσετε το JSON σε ODT σε οποιαδήποτε εφαρμογή .NET, C#, ASP.NET και VB.NET σε δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells για .NET](https://products.aspose.com/cells/net/), μπορείτε να εξαγάγετε το JSON σε PDF. Στη συνέχεια, χρησιμοποιώντας το [Aspose.Words για .NET](https://products.aspose.com/words/net/), μπορείτε να μετατρέψετε το PDF σε ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή μορφής JSON σε ODT μέσω C#" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [Workbook](https://reference.aspose.com/cells/net/aspose.cells/bookbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Εισαγάγετε αρχείο JSON στο φύλλο εργασίας χρησιμοποιώντας την κλάση [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) και το [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) ως PDF
3. Φορτώστε το έγγραφο PDF χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Αποθηκεύστε το έγγραφο σε μορφή ODT χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ρυθμίστε τη διάταξη και μετατρέψτε τη μορφή JSON σε ODT μέσω C#" %}}
Κατά την ανάλυση του JSON σε ODT, μπορείτε επίσης να ορίσετε επιλογές διάταξης για το JSON χρησιμοποιώντας το [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Σας επιτρέπει να επεξεργαστείτε τον πίνακα ως πίνακα, να αγνοήσετε τα μηδενικά, να αγνοήσετε τον τίτλο του πίνακα, να αγνοήσετε τον τίτλο του αντικειμένου, να μετατρέψετε τη συμβολοσειρά σε αριθμό ή ημερομηνία, να ορίσετε την ημερομηνία και τη μορφή αριθμού και να ορίσετε στυλ τίτλου. Όλες αυτές οι επιλογές σάς επιτρέπουν να παρουσιάζετε τα δεδομένα σας σύμφωνα με τις ανάγκες σας. Το παρακάτω απόσπασμα κώδικα σάς δείχνει πώς να ορίσετε τις επιλογές διάταξης.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Αναλύστε τη μορφή JSON σε ODT με υδατογράφημα" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε το JSON σε ODT με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας ODT, μπορείτε πρώτα να αναλύσετε το αρχείο JSON σε PDF και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το αρχείο PDF που δημιουργήθηκε πρόσφατα χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/net/aspose.words/document), δημιουργήστε μια παρουσία του TextWatermarkOptions και ορίστε τις ιδιότητές του , Καλέστε τη μέθοδο Watermark.SetText και περάστε κείμενο υδατογραφήματος & αντικείμενο του TextWatermarkOptions. Αφού προσθέσετε το υδατογράφημα, μπορείτε να αποθηκεύσετε το έγγραφο στο ODT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ott/" name="JSON Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-flatopc/" name="JSON Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-ps/" name="JSON Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-dotx/" name="JSON Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-rtf/" name="JSON Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-wordml/" name="JSON Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-odt/" name="JSON Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-word/" name="JSON Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-epub/" name="JSON Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-doc/" name="JSON Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-dot/" name="JSON Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-pcl/" name="JSON Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-mobi/" name="JSON Προς την MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/json-to-docm/" name="JSON Προς την DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}