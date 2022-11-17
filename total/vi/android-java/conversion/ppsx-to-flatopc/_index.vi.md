---
title: Xuất PPSX sang FLATOPC trên Andorid qua Java
description: Chuyển đổi PPSX sang FLATOPC trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: FLATOPC
otherformats: RTF DOC DOCM DOCX DOT DOTM ODT WORD TEXT WORDML DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PPSX sang FLATOPC trên Andorid qua Java" h2="Các API định dạng tệp để chuyển đổi PPSX sang FLATOPC trong ứng dụng Android mà không phụ thuộc vào Microsoft PowerPoint hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) cho phép thao tác các định dạng tệp trong các ứng dụng Android. Bằng cách sử dụng các API được cung cấp trong gói, bạn có thể tự động hóa quy trình chuyển đổi PowerPoint PPSX sang Word FLATOPC trong ứng dụng của mình.
Bạn có thể chuyển đổi tài liệu đã cho của mình trong hai bước. Bạn có thể sử dụng [Aspose.Slides cho Andorid qua Java](https://products.aspose.com/slides/android-java/) là một API PowerPoint cho các ứng dụng Android để hiển thị PPSX sang HTML. Sau đó, bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), bạn có thể chuyển đổi HTML thành FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSX to FLATOPC Rendering trong Android" %}}
1. Mở tệp PPSX bằng lớp [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi PPSX sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)ương thứcISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng lớp [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)
4. Lưu tài liệu sang định dạng FLATOPC bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String, int)) và đặt Flatopc dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Slides for Android via Java](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) và [Aspose.Words dành cho Andorid qua Java](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-rtf/" name="PPSX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-flatopc/" name="PPSX Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-flatopcm/" name="PPSX Đến FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-flatopcx/" name="PPSX Đến FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-dot/" name="PPSX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-dotm/" name="PPSX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-odt/" name="PPSX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-word/" name="PPSX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-text/" name="PPSX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-wordml/" name="PPSX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-dotx/" name="PPSX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/ppsx-to-ott/" name="PPSX Đến OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}