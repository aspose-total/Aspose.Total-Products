---
title: API Android để kết xuất MHTML thành PCL
description: Chuyển đổi MHTML thành PCL qua Android thông qua Java API

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: PCL
otherformats: RTF ODT WORDML DOT DOTX PS FLATOPC DOTM MARKDOWN DOCM OTT XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất MHTML thành PCL trên Android qua Java" h2="Chuyển đổi MHTML sang PCL trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi MHTML sang PCL trong ứng dụng dành cho thiết bị di động của mình bằng cách sử dụng hai API của gói [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Trước tiên, bạn cần chuyển đổi tệp MHTML sang DOC bằng [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Thứ hai, bằng cách sử dụng API xử lý văn bản [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), bạn có thể kết xuất DOC thành PCL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi MHTML sang PCL trên Android qua Java" %}}
1. Mở tệp MHTML bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MHTML sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng PCL bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt PCL dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PCL
outputDocument.save("output.pcl", SaveFormat.PCL);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận thông tin tệp MHTML trên Android qua Java" %}}
Trước khi chuyển đổi MHTML sang PCL, bạn có thể cần thông tin về tài liệu bao gồm tác giả, ngày tạo, từ khóa, ngày sửa đổi, chủ đề và tiêu đề. Thông tin này rất hữu ích cho việc đưa ra quyết định cho quá trình chuyển đổi. Bằng cách sử dụng API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) mạnh mẽ, bạn có thể nhận được tất cả. Để nhận thông tin cụ thể về tệp về tệp MHTML, trước tiên hãy lấy đối tượng [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) bằng cách sử dụng đối tượng [getInfo](https: // phương thức reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Khi đối tượng DocumentInfo được truy xuất, bạn có thể nhận các giá trị của các thuộc tính riêng lẻ.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML document
Document doc = new Document("template.mhtml");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chèn chú thích vào tài liệu PCL trong Android qua Java" %}}
Ngoài chuyển đổi tài liệu, bạn cũng có thể thêm một loạt các tính năng khác bên trong Ứng dụng Android của mình bằng cách sử dụng API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Một trong những tính năng đó là chèn chú thích cuối và đánh số trong tài liệu PCL. Nếu bạn muốn chèn chú thích cuối trang hoặc chú thích cuối vào tài liệu PCL, vui lòng sử dụng phương thức DocumentBuilder.InsertFootnote. Phương pháp này chèn chú thích cuối trang hoặc chú thích cuối vào tài liệu. Các lớp EndnoteOptions và FootnoteOptions đại diện cho các tùy chọn đánh số cho footnote và endnote.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.pcl", SaveFormat.PCL);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-rtf/" name="MHTML Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-odt/" name="MHTML Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-wordml/" name="MHTML Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-dot/" name="MHTML Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-dotx/" name="MHTML Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-ps/" name="MHTML Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-flatopc/" name="MHTML Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-dotm/" name="MHTML Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-markdown/" name="MHTML Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-pcl/" name="MHTML Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-ott/" name="MHTML Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/mhtml-to-xamlflow/" name="MHTML Đến XAMLFLOW" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}