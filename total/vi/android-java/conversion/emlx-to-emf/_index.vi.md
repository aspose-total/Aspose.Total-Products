---
title: Kết xuất EMLX thành EMF trong ứng dụng Andorid
description: Xuất EMLX sang EMF mà không cần sử dụng Microsoft Word hoặc Outlook trong các ứng dụng Andorid của bạn

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: EMF
otherformats: PNG DOC DOTX MD ODT FLATOPC JPEG TIFF DOTM PCL PS DOT OTT WORDML SVG PDF RTF EPUB GIF BMP XPS TEXT DOCM DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi EMLX thành EMF trong Ứng dụng Andorid" h2="Sử dụng các ứng dụng Andorid để xuất EMLX sang EMF bằng cách sử dụng Andorid thông qua Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ứng dụng Andorid dễ sử dụng cho người dùng cuối hàng ngày. Ngày qua, số lượng người dùng điện thoại Andorid ngày càng tăng. Sử dụng thư viện Tự động hóa Định dạng Tệp [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) mạnh mẽ, bạn có thể phát triển các ứng dụng chuyển đổi và thao tác Emlx. Bạn có thể chuyển đổi EMLX thành EMF bằng sự kết hợp của [Aspose.Emlx dành cho Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words dành cho Andorid Java](https://products.aspose.com/words/android-java/). Sử dụng API đầu tiên, bạn có thể chuyển đổi định dạng tệp EMLX sang HTML và bằng cách sử dụng API thứ hai, bạn có thể hiển thị HTML dưới dạng EMF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi EMLX sang EMF trong Andorid" %}}
1. Mở tệp EMLX bằng lớp [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Chuyển đổi EMLX sang HTML bằng cách sử dụng [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save (java.io.OutputStream,% 20com.aspose.emlx.SaveOptions )) phương pháp
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Lưu tài liệu sang định dạng EMF bằng cách sử dụng [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) và đặt EMF làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.Emlx dành cho Android qua Java](https://docs.aspose.com/emlx/androidjava/installation/) và [Aspose.Words dành cho Andorid qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EMF
document.save("output.emf", SaveFormat.EMF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}