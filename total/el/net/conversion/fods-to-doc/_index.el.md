---
title: Μετατροπή FODS σε DOC με .NET 
description: Μετατροπή FODS σε DOC σε πλατφόρμες .NET Framework, .NET Core, Mono ή Xamarin

family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOC
otherformats: PPTX POWERPOINT WORD DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Μετατροπή FODS σε DOC μέσω C#" h2="Εξαγωγή Excel&reg; FODS σε DOC σε πλατφόρμες .NET Framework, .NET Core, Mono ή Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή FODS σε DOC στο .NET" %}}
1. Ανοίξτε το αρχείο FODS χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Μετατρέψτε το FODS σε PDF και ορίστε το SaveFormat σε Auto
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας τη μέθοδο [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) και ορίστε το Doc ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Κωδικός .NET C# για μετατροπή FODS σε DOC" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/csv-to-word/" name="CSV Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/csv-to-powerpoint/" name="CSV Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/csv-to-pptx/" name="CSV Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/csv-to-docx/" name="CSV Προς την DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}