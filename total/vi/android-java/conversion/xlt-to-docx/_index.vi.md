---
title: Xuất XLT sang DOCX trong Android hoặc với Trình chuyển đổi trực tuyến miễn phí
description: API Android để chuyển đổi XLT sang DOCX mà không cần sử dụng Microsoft Word hoặc trực tuyến. Kiểm tra trình chuyển đổi trực tuyến CSV sang DOC miễn phí một cách nhanh chóng trước khi tích hợp mã.

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOCX
otherformats: WORD POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất XLT sang DOCX trên Android qua Java hoặc Ứng dụng trực tuyến" h2="Chuyển đổi XLT sang DOCX trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) là một gói API tự động hóa tệp mạnh mẽ. Bằng cách sử dụng hai trong số các API của nó, bạn có thể tích hợp tính năng chuyển đổi XLT sang DOCX bên trong các ứng dụng Android của mình. Trong bước đầu tiên, bạn có thể xuất XLT sang PDF bằng cách sử dụng [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Sau đó, bằng cách sử dụng [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), bạn có thể chuyển đổi PDF sang DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất XLT sang DOCX" %}}
1. Mở tệp XLT bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi XLT sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Lưu tài liệu sang định dạng DOCX bằng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions -) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Cells for Android via Java](https://docs.aspose.com/cells / java / aspose-cells-for-android-via-java-install / # install-asposecells-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho XLT sang DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Xóa thuộc tính tùy chỉnh khỏi tệp XLT trong Android qua Java" %}}Document
Ngoài chuyển đổi tài liệu, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) cũng cung cấp rất nhiều tính năng khác. Trước quá trình chuyển đổi, bạn có thể xóa các thuộc tính tùy chỉnh của tài liệu XLT. Để xóa thuộc tính tùy chỉnh, hãy gọi phương thức [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove (java.lang.String)) và chuyển tên của thuộc tính tài liệu sẽ bị xóa.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
Documentve a list of all custom document properties of the Excel fileDocument
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}