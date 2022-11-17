---
title: Kết xuất OFT thành BMP trong ứng dụng Andorid
description: Xuất OFT sang BMP mà không cần sử dụng Microsoft Word hoặc Outlook trong các ứng dụng Andorid của bạn

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: BMP
otherformats: PS DOT OTT SVG GIF JPEG EMF DOC XPS ODT PDF TIFF FLATOPC DOTM PNG PCL MD EPUB TEXT DOCM DOCX DOTX WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi OFT thành BMP trong Ứng dụng Andorid" h2="Sử dụng các ứng dụng Andorid để xuất OFT sang BMP bằng cách sử dụng Andorid thông qua Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ứng dụng Andorid dễ sử dụng cho người dùng cuối hàng ngày. Ngày qua, số lượng người dùng điện thoại Andorid ngày càng tăng. Sử dụng thư viện Tự động hóa Định dạng Tệp [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) mạnh mẽ, bạn có thể phát triển các ứng dụng chuyển đổi và thao tác Oft. Bạn có thể chuyển đổi OFT thành BMP bằng sự kết hợp của [Aspose.Oft dành cho Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words dành cho Andorid Java](https://products.aspose.com/words/android-java/). Sử dụng API đầu tiên, bạn có thể chuyển đổi định dạng tệp OFT sang HTML và bằng cách sử dụng API thứ hai, bạn có thể hiển thị HTML dưới dạng BMP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi OFT sang BMP trong Andorid" %}}
1. Mở tệp OFT bằng lớp [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Chuyển đổi OFT sang HTML bằng cách sử dụng [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save (java.io.OutputStream,% 20com.aspose.oft.SaveOptions )) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng BMP bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) và đặt BMP làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Oft dành cho Android qua Java](https://docs.aspose.com/oft/androidjava/installation/) và [Aspose.Words dành cho Andorid qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-ps/" name="OFT Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-dot/" name="OFT Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-ott/" name="OFT Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-svg/" name="OFT Đến SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-gif/" name="OFT Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-jpeg/" name="OFT Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-emf/" name="OFT Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-doc/" name="OFT Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-xps/" name="OFT Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-odt/" name="OFT Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-pdf/" name="OFT Đến PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-tiff/" name="OFT Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-flatopc/" name="OFT Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-dotm/" name="OFT Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-png/" name="OFT Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-pcl/" name="OFT Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-md/" name="OFT Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-epub/" name="OFT Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-text/" name="OFT Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-docm/" name="OFT Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-docx/" name="OFT Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-dotx/" name="OFT Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-wordml/" name="OFT Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/oft-to-rtf/" name="OFT Đến RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}