---
title: Преобразование EXCEL в изображение с помощью Python
description: Преобразование EXCEL в изображение TIFF BMP PNG JPEG GIF EMF SVG в ваших приложениях Python без использования Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование EXCEL в изображение через Python" h2="Преобразование изображений EXCEL в JPG, TIFF, BMP, PNG, GIF в приложениях Python без установки Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить в приложение функцию преобразования изображений EXCEL в PNG, BMP, TIFF, JPEG и GIF. Так как иногда требуется встроить электронные таблицы Excel в веб-приложения или настольные приложения. В таких случаях экспорт электронных таблиц в изображения является единственным решением. API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) может помочь экспортировать файлы Excel в изображения, а также автоматизировать процесс преобразования. Это полный пакет различных API, работающих с различными форматами, включая форматы Microsoft Excel, через дочерний API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/). В настоящее время Python Excel to Image Converter API поддерживает преобразование файлов Excel в EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM и совместимый с Office EMF или проверьте поддерживаемый [Форматы](https://docs.aspose.com/cells/python-java/supported-file-formats/). 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как преобразовать EXCEL в изображения в Python" %}}

- Создайте объект класса [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) для загрузки файла EXCEL
- Используйте класс [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) и укажите соответствующие параметры выходного изображения.
- Получите доступ к рабочему листу для преобразования с использованием метода [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)).
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Сохраните все страницы рабочего листа в виде изображения, используя метод [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Теперь файл EXCEL конвертируется в изображения по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования EXCEL в изображения (JPG, PNG, GIF, BMP, TIFF) ссылки на API в проекте непосредственно из PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Или используйте следующую команду pip ```pip install aspose.cells``` 
- Кроме того, загрузите пакет API из раздела [Загрузки](https://releases.aspose.comcells/python-java). 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Преобразование EXCEL в изображения через Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}