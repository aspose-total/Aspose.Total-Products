---
title: Konwertuj ODS na PPTX za pomocą Java
description: Java API do eksportu ODS do PPTX za pomocą programu Excel lub Word
url_ignore: /pl/java/conversion/ods-to-pptx/
family: total
platformtag: net
feature: conversion
informat: ODS
outformat: PPTX
otherformats: PPTX POWERPOINT WORD PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API do eksportu ODS do PPTX" h2="On Premise Java API do eksportu ODS do PPTX bez korzystania z Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderowanie ODS do PPTX to proces dwuetapowy. Najpierw użyjesz interfejsu API [Aspose.Cells for Java](https://products.aspose.com/cells/java), aby przekonwertować dany dokument ODS na PDF, a następnie użyjesz [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, możesz łatwo przekonwertować dokument PDF na PPTX. Oba interfejsy API należą do kolekcji bibliotek automatyzacji formatu plików [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować ODS do PPTX za pomocą Java API" %}}
1. Otwórz plik ODS za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konwertuj ODS na PDF i ustaw SaveFormat na AUTO
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Zapisz dokument w formacie PPTX za pomocą [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metodę i ustaw Pptx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Musisz użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ods-to-pptxx/" name="ODS W celu PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ods-to-pptx/" name="ODS W celu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ods-to-powerpoint/" name="ODS W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ods-to-word/" name="ODS W celu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}