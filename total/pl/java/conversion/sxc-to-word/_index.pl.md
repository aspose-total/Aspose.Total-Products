---
title: Konwertuj SXC na WORD za pomocą Java
description: Java API do eksportu SXC do WORD za pomocą programu Excel lub Word
url_ignore: /pl/java/conversion/sxc-to-word/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: WORD
otherformats: WORDX PPTX POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do eksportu SXC do WORD" h2="On Premise Java API do eksportu SXC do WORD bez korzystania z Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderowanie SXC do WORD to proces dwuetapowy. Najpierw użyjesz interfejsu API [Aspose.Cells for Java](https://products.aspose.com/cells/java), aby przekonwertować dany dokument SXC na PDF, a następnie użyjesz [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, możesz łatwo przekonwertować dokument PDF na WORD. Oba interfejsy API należą do kolekcji bibliotek automatyzacji formatu plików [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować SXC do WORD za pomocą Java API" %}}
1. Otwórz plik SXC za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konwertuj SXC na PDF i ustaw SaveFormat na AUTO
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Zapisz dokument w formacie WORD za pomocą [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metodę i ustaw Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Musisz użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/sxc-to-wordx/" name="SXC W celu WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/sxc-to-pptx/" name="SXC W celu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/sxc-to-powerpoint/" name="SXC W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/sxc-to-word/" name="SXC W celu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}