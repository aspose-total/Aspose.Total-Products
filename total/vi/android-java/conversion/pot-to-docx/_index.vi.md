---
title: Xuất POT sang DOCX trên Andorid qua Java
description: Chuyển đổi POT sang DOCX trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào
url: /vi/android-java/conversion/pot-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOCX
otherformats: WORDML OTT DOT DOC DOTM DOTX ODT DOCM FLATOPC WORD RTF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất POT sang DOCX trên Andorid qua Java" h2="Các API định dạng tệp để chuyển đổi POT sang DOCX trong ứng dụng Android mà không phụ thuộc vào Microsoft PowerPoint hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/) cho phép thao tác các định dạng tệp trong các ứng dụng Android. Bằng cách sử dụng các API được cung cấp trong gói, bạn có thể tự động hóa quy trình chuyển đổi PowerPoint POT sang Word DOCX trong ứng dụng của mình.
Bạn có thể chuyển đổi tài liệu đã cho của mình trong hai bước. Bạn có thể sử dụng [Aspose.Slides cho Andorid qua Java](https://products.aspose.com/slides/android-java/) là một API PowerPoint cho các ứng dụng Android để hiển thị POT sang HTML. Sau đó, bằng cách sử dụng API xử lý tài liệu [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/android-java/), bạn có thể chuyển đổi HTML thành DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POT to DOCX Rendering trong Android" %}}
1. Mở tệp POT bằng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi POT sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)ương thứcISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng lớp [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
4. Lưu tài liệu sang định dạng DOCX bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String, int)) và đặt Docx dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Slides dành cho Android qua Java](https://docxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) và [Aspose.Words dành cho Andorid qua Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docxument
Docxument docxument = new Docxument("htmlOutput.html");
// save docxument in DOCX format
docxument.save("output.docx",SaveFormat.Docxx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-wordml/" name="POT Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-ott/" name="POT Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-dot/" name="POT Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-docx/" name="POT Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-dotm/" name="POT Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-dotx/" name="POT Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-odt/" name="POT Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-docxm/" name="POT Đến DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-flatopc/" name="POT Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-word/" name="POT Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-rtf/" name="POT Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pot-to-text/" name="POT Đến TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}