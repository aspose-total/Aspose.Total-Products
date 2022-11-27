---
title: Обновление файлов Excel с помощью Java 

description: Редактируйте документы Microsoft Excel XLSX, XLS, CSV без установки Microsoft Office в приложениях на основе Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновление документов Excel через Java" h2="Изменяйте файлы Microsoft Excel XLSX, XLS в приложениях на основе Java без установки Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Организации часто обновляют свои данные, хранящиеся в файлах Excel, таких как данные студентов, записи пациентов, список складских товаров и т. Д., С помощью программного обеспечения компании. API [Aspose.Total for Java](https://products.aspose.com/total/java/) предоставляет возможность модификации электронных таблиц с помощью собственного программного обеспечения. Программисты могут улучшить программное обеспечение с помощью возможностей модификации, просто написав несколько строк кода API. API [Aspose.Cells for Java](https://products.aspose.com/cells/java/), являющийся частью пакета [Aspose.Total for Java](https://products.aspose.com/total/java/), упрощает процесс модификации. Ниже показан процесс обновления документа Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Обновление документов Excel с помощью Java" %}}

API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) предоставляет класс [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook), который обрабатывает загрузку электронных таблиц Excel. Процесс прост. Создайте объект класса Workbook, указав исходный файл в качестве параметра. Получите доступ к соответствующему рабочему листу и соответствующей ячейке, используя метод [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Используйте метод [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) для изменения содержимого в доступной ячейке и, наконец, вызовите метод save() для сохранения документа.

{{% blocks/products/pf/feature-page-code h3="Java-код — обновление документов Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Обновлять">}}