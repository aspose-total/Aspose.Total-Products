---
title: Μετατρέψτε τη μορφή JSON σε PPS μέσω C++
description: Ανάλυση JSON σε PPS σε C++ χωρίς χρήση του Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPSX PPSM PPTM POWERPOINT POTM POTX PPT ODP OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατρέψτε τη μορφή JSON σε PPS μέσω C++" h2="C++ API για ανάλυση JSON σε PPS χωρίς χρήση Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε JSON σε PPS σε οποιαδήποτε εφαρμογή C++ με δύο απλά βήματα. Πρώτον, χρησιμοποιώντας το [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), μπορείτε να αναλύσετε το JSON σε PPTX. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), μπορείτε να μετατρέψετε το PPTX σε PPS. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε τη μορφή JSON σε PPS μέσω C++" %}}
1. Δημιουργήστε ένα νέο αντικείμενο [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) και διαβάστε έγκυρα δεδομένα JSON από το αρχείο
2. Αποθηκεύστε το JSON ως PPTX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή PPS χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση μέσω της Κονσόλας Package Manager του Visual Studio με "``Install-Package Aspose.Total.Cpp``".

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ορίστε τη διάταξη και μετατρέψτε τη μορφή JSON σε PPS μέσω C++" %}}
Κατά την ανάλυση του JSON σε PPS, μπορείτε επίσης να ορίσετε το μέγεθος των σειρών και των στηλών φορτώνοντας το JSON με την κλάση [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Εάν χρειάζεται να ορίσετε το ίδιο ύψος σειράς για όλες τις σειρές στο φύλλο εργασίας, μπορείτε να το κάνετε χρησιμοποιώντας το [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b3f1461e ) μέθοδο της συλλογής [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Ομοίως, για να ορίσετε το ίδιο πλάτος στήλης για όλες τις στήλες στο φύλλο εργασίας, χρησιμοποιήστε τη μέθοδο [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e64b8502) της συλλογής ICElls.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε τη μορφή JSON σε PPS με υδατογράφημα σε C++" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να μετατρέψετε JSON σε PPS με υδατογράφημα. Για να προσθέσετε ένα υδατογράφημα στο έγγραφό σας PPS, μπορείτε πρώτα να αναλύσετε το JSON σε PPTX και να προσθέσετε ένα υδατογράφημα σε αυτό. Για να προσθέσετε ένα υδατογράφημα, φορτώστε το νέο αρχείο PPTX χρησιμοποιώντας την κλάση [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), λάβετε την πρώτη διαφάνεια, Προσθέστε μια AutoShape τύπου Rectangle, προσθέστε TextFrame στο Rectangle, δημιουργήστε το αντικείμενο Paragraph για ένα πλαίσιο κειμένου, δημιουργήστε αντικείμενο τμήμα για την παράγραφο, προσθέστε υδατογράφημα χρησιμοποιώντας set_Text() και μπορείτε να αποθηκεύσετε το έγγραφο στο PPS.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}