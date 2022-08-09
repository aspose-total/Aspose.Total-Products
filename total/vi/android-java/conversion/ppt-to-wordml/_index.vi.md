---
title: Xuất PPT sang WORDML trên Andorid qua Java
description: Chuyển đổi PPT sang WORDML trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào
url: /vi/android-java/conversion/ppt-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: WORDML
otherformats: DOTX FLATOPC OTT DOTM ODT DOT DOCM TEXT WORD DOC DOCX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PPT sang WORDML trên Andorid qua Java" h2="Các API định dạng tệp để chuyển đổi PPT sang WORDML trong ứng dụng Android mà không phụ thuộc vào Microsoft PowerPoint hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/) cho phép thao tác các định dạng tệp trong các ứng dụng Android. Bằng cách sử dụng các API được cung cấp trong gói, bạn có thể tự động hóa quy trình chuyển đổi PowerPoint PPT sang Word WORDML trong ứng dụng của mình.
Bạn có thể chuyển đổi tài liệu đã cho của mình trong hai bước. Bạn có thể sử dụng [Aspose.Slides cho Andorid qua Java](https://products.aspose.com/slides/android-java/) là một API PowerPoint cho các ứng dụng Android để hiển thị PPT sang HTML. Sau đó, bằng cách sử dụng API xử lý tài liệu [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/android-java/), bạn có thể chuyển đổi HTML thành WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT to WORDML Rendering trong Android" %}}
1. Mở tệp PPT bằng lớp [Trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi PPT sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)ương thứcISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng lớp [Wordmlument](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument)
4. Lưu tài liệu sang định dạng WORDML bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument#save(java.lang.String, int)) và đặt Wordml dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Slides dành cho Android qua Java](https://wordmls.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) và [Aspose.Words dành cho Andorid qua Java](https://wordmls.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("htmlOutput.html");
// save wordmlument in WORDML format
wordmlument.save("output.wordml",SaveFormat.WordML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-dotx/" name="PPT Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-flatopc/" name="PPT Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-ott/" name="PPT Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-dotm/" name="PPT Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-odt/" name="PPT Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-dot/" name="PPT Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-wordmlm/" name="PPT Đến WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-text/" name="PPT Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-word/" name="PPT Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-wordml/" name="PPT Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-wordmlx/" name="PPT Đến WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppt-to-rtf/" name="PPT Đến RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}