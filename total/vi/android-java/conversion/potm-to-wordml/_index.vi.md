---
title: Xuất POTM sang WORDML trên Andorid qua Java
description: Chuyển đổi POTM sang WORDML trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào
url: /vi/android-java/conversion/potm-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: WORDML
otherformats: FLATOPC ODT DOCX DOCM WORD RTF DOTM DOC DOTX OTT TEXT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất POTM sang WORDML trên Andorid qua Java" h2="Các API định dạng tệp để chuyển đổi POTM sang WORDML trong ứng dụng Android mà không phụ thuộc vào Microsoft PowerPoint hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) cho phép thao tác các định dạng tệp trong các ứng dụng Android. Bằng cách sử dụng các API được cung cấp trong gói, bạn có thể tự động hóa quy trình chuyển đổi PowerPoint POTM sang Word WORDML trong ứng dụng của mình.
Bạn có thể chuyển đổi tài liệu đã cho của mình trong hai bước. Bạn có thể sử dụng [Aspose.Slides cho Andorid qua Java](https://products.aspose.com/slides/android-java/) là một API PowerPoint cho các ứng dụng Android để hiển thị POTM sang HTML. Sau đó, bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), bạn có thể chuyển đổi HTML thành WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM to WORDML Rendering trong Android" %}}
1. Mở tệp POTM bằng lớp [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi POTM sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)ương thứcISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng lớp [Wordmlument](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument)
4. Lưu tài liệu sang định dạng WORDML bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument#save(java.lang.String, int)) và đặt Wordml dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Slides for Android via Java](https://wordmls.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) và [Aspose.Words dành cho Andorid qua Java](https://wordmls.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-flatopc/" name="POTM Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-odt/" name="POTM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-wordmlx/" name="POTM Đến WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-wordmlm/" name="POTM Đến WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-word/" name="POTM Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-rtf/" name="POTM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-dotm/" name="POTM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-wordml/" name="POTM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-dotx/" name="POTM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-ott/" name="POTM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-text/" name="POTM Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/potm-to-dot/" name="POTM Đến DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}