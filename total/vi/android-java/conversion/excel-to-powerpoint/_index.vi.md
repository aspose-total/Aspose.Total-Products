---
title: Xuất EXCEL sang POWERPOINT trong Android
description: API Android để chuyển đổi EXCEL sang POWERPOINT mà không cần sử dụng Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: EXCEL
outformat: POWERPOINT
otherformats: WORD DOC DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất EXCEL sang POWERPOINT trên Android qua Java" h2="Chuyển đổi EXCEL sang POWERPOINT trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) là một gói API tự động hóa tệp mạnh mẽ. Bằng cách sử dụng hai trong số các API của nó, bạn có thể tích hợp tính năng chuyển đổi EXCEL sang POWERPOINT bên trong các ứng dụng Android của mình. Trong bước đầu tiên, bạn có thể xuất EXCEL sang PDF bằng cách sử dụng [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Sau đó, bằng cách sử dụng [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), bạn có thể chuyển đổi PDF sang POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất EXCEL sang POWERPOINT" %}}
1. Mở tệp EXCEL bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi EXCEL sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Lưu tài liệu sang định dạng POWERPOINT bằng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) và [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells / java / aspose-cells-for-android-via-java-install / # install-asposecells-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa thuộc tính tùy chỉnh khỏi tệp EXCEL trong Android qua Java" %}}
Ngoài chuyển đổi tài liệu, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) cũng cung cấp rất nhiều tính năng khác. Trước quá trình chuyển đổi, bạn có thể xóa các thuộc tính tùy chỉnh của tài liệu EXCEL. Để xóa thuộc tính tùy chỉnh, hãy gọi phương thức [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove (java.lang.String)) và chuyển tên của thuộc tính tài liệu sẽ bị xóa.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}