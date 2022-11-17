---
title: Kết xuất EMLX thành DOT trong ứng dụng Andorid
description: Xuất EMLX sang DOT mà không cần sử dụng Microsoft Word hoặc Outlook trong các ứng dụng Andorid của bạn

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOT
otherformats: ODT PNG PS TIFF JPEG DOCX EPUB RTF DOC PCL FLATOPC SVG WORDML BMP DOTX EMF XPS DOCM GIF MD OTT DOTM TEXT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi EMLX thành DOT trong Ứng dụng Andorid" h2="Sử dụng các ứng dụng Andorid để xuất EMLX sang DOT bằng cách sử dụng Andorid thông qua Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ứng dụng Andorid dễ sử dụng cho người dùng cuối hàng ngày. Ngày qua, số lượng người dùng điện thoại Andorid ngày càng tăng. Sử dụng thư viện Tự động hóa Định dạng Tệp [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) mạnh mẽ, bạn có thể phát triển các ứng dụng chuyển đổi và thao tác Emlx. Bạn có thể chuyển đổi EMLX thành DOT bằng sự kết hợp của [Aspose.Emlx dành cho Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words dành cho Andorid Java](https://products.aspose.com/words/android-java/). Sử dụng API đầu tiên, bạn có thể chuyển đổi định dạng tệp EMLX sang HTML và bằng cách sử dụng API thứ hai, bạn có thể hiển thị HTML dưới dạng DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi EMLX sang DOT trong Andorid" %}}
1. Mở tệp EMLX bằng lớp [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Chuyển đổi EMLX sang HTML bằng cách sử dụng [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save (java.io.OutputStream,% 20com.aspose.emlx.SaveOptions )) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng DOT bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) và đặt DOT làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Emlx dành cho Android qua Java](https://docs.aspose.com/emlx/androidjava/installation/) và [Aspose.Words dành cho Andorid qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-odt/" name="EMLX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-png/" name="EMLX Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-ps/" name="EMLX Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-tiff/" name="EMLX Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-jpeg/" name="EMLX Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-docx/" name="EMLX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-epub/" name="EMLX Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-rtf/" name="EMLX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-doc/" name="EMLX Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-pcl/" name="EMLX Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-flatopc/" name="EMLX Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-svg/" name="EMLX Đến SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-wordml/" name="EMLX Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-dot/" name="EMLX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-dotx/" name="EMLX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-emf/" name="EMLX Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-xps/" name="EMLX Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-docm/" name="EMLX Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-gif/" name="EMLX Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-md/" name="EMLX Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-ott/" name="EMLX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-dotm/" name="EMLX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-text/" name="EMLX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/emlx-to-pdf/" name="EMLX Đến PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}