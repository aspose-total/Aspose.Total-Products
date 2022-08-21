---
title: Kết xuất EML thành DOC trong ứng dụng Andorid
description: Xuất EML sang DOC mà không cần sử dụng Microsoft Word hoặc Outlook trong các ứng dụng Andorid của bạn
url: /vi/android-java/conversion/eml-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOC
otherformats: ODT OTT PS DOTM PNG XPS FLATOPC PCL DOT BMP DOCX TEXT WORDML EMF EPUB SVG DOTX TIFF GIF DOCM RTF JPEG MD PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi EML thành DOC trong Ứng dụng Andorid" h2="Sử dụng các ứng dụng Andorid để xuất EML sang DOC bằng cách sử dụng Andorid thông qua Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ứng dụng Andorid dễ sử dụng cho người dùng cuối hàng ngày. Ngày qua, số lượng người dùng điện thoại Andorid ngày càng tăng. Sử dụng thư viện Tự động hóa Định dạng Tệp [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) mạnh mẽ, bạn có thể phát triển các ứng dụng chuyển đổi và thao tác Eml. Bạn có thể chuyển đổi EML thành DOC bằng sự kết hợp của [Aspose.Eml dành cho Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words dành cho Andorid Java](https://products.aspose.com/words/android-java/). Sử dụng API đầu tiên, bạn có thể chuyển đổi định dạng tệp EML sang HTML và bằng cách sử dụng API thứ hai, bạn có thể hiển thị HTML dưới dạng DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi EML sang DOC trong Andorid" %}}
1. Mở tệp EML bằng lớp [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Chuyển đổi EML sang HTML bằng cách sử dụng [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save (java.io.OutputStream,% 20com.aspose.eml.SaveOptions )) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng DOC bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) và đặt DOC làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Eml dành cho Android qua Java](https://docs.aspose.com/eml/androidjava/installation/) và [Aspose.Words dành cho Andorid qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOC
document.save("output.doc", SaveFormat.DOC); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-odt/" name="EML Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-ott/" name="EML Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-ps/" name="EML Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-dotm/" name="EML Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-png/" name="EML Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-xps/" name="EML Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-flatopc/" name="EML Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-pcl/" name="EML Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-dot/" name="EML Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-doc/" name="EML Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-docx/" name="EML Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-text/" name="EML Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-wordml/" name="EML Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-emf/" name="EML Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-epub/" name="EML Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-svg/" name="EML Đến SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-dotx/" name="EML Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-tiff/" name="EML Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-gif/" name="EML Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-docm/" name="EML Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-rtf/" name="EML Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-jpeg/" name="EML Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-md/" name="EML Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/eml-to-pdf/" name="EML Đến PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}