---
title: Обновление файлов Excel с помощью C++ 

description: Редактируйте документы Microsoft Excel XLSX, XLS, CSV без установки Microsoft Office с приложениями на основе C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновление документов Excel через C++" h2="Изменяйте файлы Microsoft Excel XLSX, XLS в приложениях на основе C++ без установки Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Организации часто обновляют свои данные, хранящиеся в файлах Excel, таких как данные студентов, записи пациентов, список складских товаров и т. Д., С помощью программного обеспечения компании. API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) предоставляет возможность изменения электронных таблиц с помощью программного обеспечения. Программисты могут улучшить программное обеспечение с помощью возможностей модификации, просто написав несколько строк кода API. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), являющийся частью пакета [Aspose.Total for C++](https://products.aspose.com/total/cpp/), упрощает процесс модификации. Ниже показан процесс обновления документа Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Обновление документов Excel с помощью C++" %}}

Используя API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), загрузите исходный документ в формате [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Получите доступ к [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet), используя GetIWorksheets()->GetObjectByIndex(0), и требуемую ячейку, используя GetICells()->GetObjectByIndex. Используя метод PutValue, измените содержимое в доступной ячейке. Наконец, вызовите метод save(), чтобы сохранить документ.

{{% blocks/products/pf/feature-page-code h3="Код C++ — обновление документов Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Обновлять">}}