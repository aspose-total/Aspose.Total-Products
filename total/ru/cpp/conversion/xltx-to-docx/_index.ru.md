---
title: Преобразование XLTX в DOCX с помощью C++
description: Преобразование XLTX в DOCX в приложениях C++
url: /ru/cpp/conversion/xltx-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: DOC POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Конвертировать XLTX в DOCX через C++" h2="Экспорт Excel<sup>&reg;</sup> XLTX в DOCX в полнофункциональных приложениях C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование XLTX в DOCX на C++" %}}
1. Откройте XLTX-файл, используя [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) функцию-член [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) ссылка на класс
2. Преобразуйте XLTX в PDF и установите SaveFormat в Pdf.
3. Загрузите преобразованный PDF-файл, используя ссылку на класс [Docxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument).
4. Сохраните документ в формате DOCX с помощью функции-члена [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) и установите Docx как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/xltx-to-docx/" name="XLTX К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/xltx-to-powerpoint/" name="XLTX К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/xltx-to-word/" name="XLTX К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/xltx-to-pptx/" name="XLTX К PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}