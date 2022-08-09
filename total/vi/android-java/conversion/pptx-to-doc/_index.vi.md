---
title: Xuất PPTX sang DOC trên Andorid qua Java
description: Chuyển đổi PPTX sang DOC trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào
url: /vi/android-java/conversion/pptx-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOC
otherformats: WORD DOT WORDML DOTM TEXT OTT DOCM ODT DOCX DOTX RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PPTX sang DOC trên Andorid qua Java" h2="Các API định dạng tệp để chuyển đổi PPTX sang DOC trong ứng dụng Android mà không phụ thuộc vào Microsoft PowerPoint hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/) cho phép thao tác các định dạng tệp trong các ứng dụng Android. Bằng cách sử dụng các API được cung cấp trong gói, bạn có thể tự động hóa quy trình chuyển đổi PowerPoint PPTX sang Word DOC trong ứng dụng của mình.
Bạn có thể chuyển đổi tài liệu đã cho của mình trong hai bước. Bạn có thể sử dụng [Aspose.Slides cho Andorid qua Java](https://products.aspose.com/slides/android-java/) là một API PowerPoint cho các ứng dụng Android để hiển thị PPTX sang HTML. Sau đó, bằng cách sử dụng API xử lý tài liệu [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/android-java/), bạn có thể chuyển đổi HTML thành DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTX to DOC Rendering trong Android" %}}
1. Mở tệp PPTX bằng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi PPTX sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)ương thứcISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng DOC bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt Doc dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Slides dành cho Android qua Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) và [Aspose.Words dành cho Andorid qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document document = new Document("htmlOutput.html");
// save document in DOC format
document.save("output.doc",SaveFormat.Doc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-word/" name="PPTX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-dot/" name="PPTX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-wordml/" name="PPTX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-dotm/" name="PPTX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-text/" name="PPTX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-ott/" name="PPTX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-docm/" name="PPTX Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-odt/" name="PPTX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-docx/" name="PPTX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-dotx/" name="PPTX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-rtf/" name="PPTX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pptx-to-flatopc/" name="PPTX Đến FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}