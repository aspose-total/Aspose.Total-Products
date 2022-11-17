---
title: Xuất CSV sang WORD trong Android
description: API Android để chuyển đổi CSV sang WORD mà không cần sử dụng Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: POWERPOINT DOCX DOC PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất CSV sang WORD trên Android qua Java" h2="Chuyển đổi CSV sang WORD trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) là một gói API tự động hóa tệp mạnh mẽ. Bằng cách sử dụng hai trong số các API của nó, bạn có thể tích hợp tính năng chuyển đổi CSV sang WORD bên trong các ứng dụng Android của mình. Trong bước đầu tiên, bạn có thể xuất CSV sang PDF bằng cách sử dụng [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Sau đó, bằng cách sử dụng [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), bạn có thể chuyển đổi PDF sang WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất CSV sang WORD" %}}
1. Mở tệp CSV bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi CSV sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Lưu tài liệu sang định dạng WORD bằng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) và [Aspose.Cells for Android via Java](https://words.aspose.com/cells / java / aspose-cells-for-android-via-java-install / # install-asposecells-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// save CSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa thuộc tính tùy chỉnh khỏi tệp CSV trong Android qua Java" %}}
Ngoài chuyển đổi tài liệu, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) cũng cung cấp rất nhiều tính năng khác. Trước quá trình chuyển đổi, bạn có thể xóa các thuộc tính tùy chỉnh của tài liệu CSV. Để xóa thuộc tính tùy chỉnh, hãy gọi phương thức [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove (java.lang.String)) và chuyển tên của thuộc tính tài liệu sẽ bị xóa.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/csv-to-powerpoint/" name="CSV Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/csv-to-wordx/" name="CSV Đến WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/csv-to-word/" name="CSV Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/csv-to-pptx/" name="CSV Đến PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}