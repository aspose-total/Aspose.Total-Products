---
title: Kết xuất MSG thành PNG trong ứng dụng Andorid
description: Xuất MSG sang PNG mà không cần sử dụng Microsoft Word hoặc Outlook trong các ứng dụng Andorid của bạn

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOC DOCM GIF TIFF WORDML XPS ODT FLATOPC EMF RTF PS EPUB DOT BMP PCL MD DOTM DOCX DOTX TEXT JPEG OTT PDF SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi MSG thành PNG trong Ứng dụng Andorid" h2="Sử dụng các ứng dụng Andorid để xuất MSG sang PNG bằng cách sử dụng Andorid thông qua Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ứng dụng Andorid dễ sử dụng cho người dùng cuối hàng ngày. Ngày qua, số lượng người dùng điện thoại Andorid ngày càng tăng. Sử dụng thư viện Tự động hóa Định dạng Tệp [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) mạnh mẽ, bạn có thể phát triển các ứng dụng chuyển đổi và thao tác Msg. Bạn có thể chuyển đổi MSG thành PNG bằng sự kết hợp của [Aspose.Msg dành cho Android Java](https://products.aspose.com/msg/android-java/) & [Aspose.Words dành cho Andorid Java](https://products.aspose.com/words/android-java/). Sử dụng API đầu tiên, bạn có thể chuyển đổi định dạng tệp MSG sang HTML và bằng cách sử dụng API thứ hai, bạn có thể hiển thị HTML dưới dạng PNG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi MSG sang PNG trong Andorid" %}}
1. Mở tệp MSG bằng lớp [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. Chuyển đổi MSG sang HTML bằng cách sử dụng [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save (java.io.OutputStream,% 20com.aspose.msg.SaveOptions )) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng PNG bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) và đặt PNG làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Msg dành cho Android qua Java](https://docs.aspose.com/msg/androidjava/installation/) và [Aspose.Words dành cho Andorid qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-doc/" name="MSG Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-docm/" name="MSG Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-gif/" name="MSG Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-tiff/" name="MSG Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-wordml/" name="MSG Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-xps/" name="MSG Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-odt/" name="MSG Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-flatopc/" name="MSG Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-emf/" name="MSG Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-rtf/" name="MSG Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-ps/" name="MSG Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-epub/" name="MSG Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-dot/" name="MSG Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-png/" name="MSG Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-pcl/" name="MSG Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-md/" name="MSG Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-dotm/" name="MSG Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-docx/" name="MSG Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-dotx/" name="MSG Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-text/" name="MSG Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-jpeg/" name="MSG Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-ott/" name="MSG Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-pdf/" name="MSG Đến PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/msg-to-svg/" name="MSG Đến SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}