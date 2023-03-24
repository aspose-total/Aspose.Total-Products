---
title: Xuất POTX sang RTF trên Andorid qua Java hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Chuyển đổi POTX sang RTF trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào hoặc trực tuyến. Kiểm tra trình chuyển đổi trực tuyến CSV sang DOC miễn phí một cách nhanh chóng trước khi tích hợp mã.

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: RTF
otherformats: FLATOPC OTT WORD DOTM DOCM DOC DOTX DOT DOCX WORDML TEXT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất POTX sang RTF trên Andorid qua Java hoặc Ứng dụng trực tuyến" h2="Các API định dạng tệp để chuyển đổi POTX sang RTF trong ứng dụng Android mà không phụ thuộc vào Microsoft PowerPoint hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) cho phép thao tác các định dạng tệp trong các ứng dụng Android. Bằng cách sử dụng các API được cung cấp trong gói, bạn có thể tự động hóa quy trình chuyển đổi PowerPoint POTX sang Word RTF trong ứng dụng của mình.
Bạn có thể chuyển đổi tài liệu đã cho của mình trong hai bước. Bạn có thể sử dụng [Aspose.Slides cho Andorid qua Java](https://products.aspose.com/slides/android-java/) là một API PowerPoint cho các ứng dụng Android để hiển thị POTX sang HTML. Sau đó, bằng cách sử dụng API xử lý tài liệu [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), bạn có thể chuyển đổi HTML thành RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTX to RTF Rendering trong Android" %}}
1. Mở tệp POTX bằng lớp [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi POTX sang HTML bằng cách sử dụng [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)ương thứcISaveOptions-) và đặt Html làm SaveFormat
3. Tải tệp HTML đã chuyển đổi bằng cách sử dụng lớp [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. Lưu tài liệu sang định dạng RTF bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String, int)) và đặt Rtf dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) và [Aspose.Words dành cho Andorid qua Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Công cụ chuyển đổi trực tuyến miễn phí cho POTX sang RTF</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}