---
title: Μετατρέψτε τη μορφή JSON σε MOBI μέσω C++
description: C++ API t0 Ανάλυση JSON σε MOBI χωρίς χρήση του Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: WORD FLATOPC DOT RTF DOCM WORDML CHM OTT PS DOTX EPUB ODT PCL DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε τη μορφή JSON σε MOBI μέσω C++" h2="Ανάλυση JSON σε MOBI σε εφαρμογές C++ χωρίς χρήση Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) μπορείτε να αναλύσετε το JSON σε MOBI στις εφαρμογές σας C++ με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), μπορείτε να εξαγάγετε το JSON σε PDF. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cppp/), μπορείτε να μετατρέψετε το PDF σε MOBI. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε τη μορφή JSON σε MOBI σε C++" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Αποθηκεύστε το JSON ως PDF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Φορτώστε το έγγραφο PDF χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή MOBI χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ορίστε Layout & Convert JSON Format σε MOBI σε C++" %}}
Κατά την ανάλυση του JSON σε MOBI, μπορείτε επίσης να ορίσετε το μέγεθος των σειρών και των στηλών φορτώνοντας το JSON με την κλάση [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Εάν χρειάζεται να ορίσετε το ίδιο ύψος σειράς για όλες τις σειρές στο φύλλο εργασίας, μπορείτε να το κάνετε χρησιμοποιώντας το [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b3f1461e ) μέθοδο της συλλογής [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Ομοίως, για να ορίσετε το ίδιο πλάτος στήλης για όλες τις στήλες στο φύλλο εργασίας, χρησιμοποιήστε τη μέθοδο [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e64b8502) της συλλογής ICElls.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε τη μορφή JSON σε MOBI με υδατογράφημα σε C++" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να αναλύσετε το JSON σε MOBI με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας MOBI, μπορείτε πρώτα να μετατρέψετε το JSON σε PDF και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το αρχείο PDF που δημιουργήθηκε πρόσφατα χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), ορίστε διαφορετικές ιδιότητες για το υδατογράφημα κειμένου,
καλέστε τη μέθοδο SetText και περάστε κείμενο υδατογραφήματος και αντικείμενο του TextWatermarkOptions. Αφού προσθέσετε το υδατογράφημα, μπορείτε να αποθηκεύσετε το έγγραφο στο MOBI.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-word/" name="JSON Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-flatopc/" name="JSON Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-dot/" name="JSON Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-rtf/" name="JSON Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-docm/" name="JSON Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-wordml/" name="JSON Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-mobi/" name="JSON Προς την MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-ott/" name="JSON Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-ps/" name="JSON Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-dotx/" name="JSON Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-epub/" name="JSON Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-odt/" name="JSON Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-pcl/" name="JSON Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/json-to-doc/" name="JSON Προς την DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}