---
title: Μετατρέψτε τη μορφή JSON σε DOTX μέσω C++
description: C++ API t0 Ανάλυση JSON σε DOTX χωρίς χρήση του Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOC MOBI DOT ODT WORD WORDML FLATOPC PS CHM PCL OTT EPUB DOCM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε τη μορφή JSON σε DOTX μέσω C++" h2="Ανάλυση JSON σε DOTX σε εφαρμογές C++ χωρίς χρήση Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Χρησιμοποιώντας το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) μπορείτε να αναλύσετε το JSON σε DOTX στις εφαρμογές σας C++ με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), μπορείτε να εξαγάγετε το JSON σε PDF. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cppp/), μπορείτε να μετατρέψετε το PDF σε DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε τη μορφή JSON σε DOTX σε C++" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Αποθηκεύστε το JSON ως PDF χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Φορτώστε το έγγραφο PDF χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOTX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ορίστε Layout & Convert JSON Format σε DOTX σε C++" %}}
Κατά την ανάλυση του JSON σε DOTX, μπορείτε επίσης να ορίσετε το μέγεθος των σειρών και των στηλών φορτώνοντας το JSON με την κλάση [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Εάν χρειάζεται να ορίσετε το ίδιο ύψος σειράς για όλες τις σειρές στο φύλλο εργασίας, μπορείτε να το κάνετε χρησιμοποιώντας το [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b3f1461e ) μέθοδο της συλλογής [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Ομοίως, για να ορίσετε το ίδιο πλάτος στήλης για όλες τις στήλες στο φύλλο εργασίας, χρησιμοποιήστε τη μέθοδο [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e64b8502) της συλλογής ICElls.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε τη μορφή JSON σε DOTX με υδατογράφημα σε C++" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να αναλύσετε το JSON σε DOTX με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας DOTX, μπορείτε πρώτα να μετατρέψετε το JSON σε PDF και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το αρχείο PDF που δημιουργήθηκε πρόσφατα χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), ορίστε διαφορετικές ιδιότητες για το υδατογράφημα κειμένου,
καλέστε τη μέθοδο SetText και περάστε κείμενο υδατογραφήματος και αντικείμενο του TextWatermarkOptions. Αφού προσθέσετε το υδατογράφημα, μπορείτε να αποθηκεύσετε το έγγραφο στο DOTX.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}